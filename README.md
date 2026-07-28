# standalone potree viewer

This repo is a basic repackaging of the viewer.html example in https://github.com/potree/potree.
It has been modified so that remote potree pointclouds can be passed to the viewer through a
URL parameter, and it is published here through Github pages.

## Example

https://legiongis.github.io/standalone-potree-viewer/?url=https://lcai-assets.s3.us-gov-west-1.amazonaws.com/pointclouds/CrescentCityCabin/cloud.js

## Purpose

The goal is to put a potree viewer in an iframe while supplying remote data to it.

```
<iframe height="600" width="100%" src="https://legiongis.github.io/standalone-potree-viewer/?url=https://lcai-assets.s3.us-gov-west-1.amazonaws.com/pointclouds/CrescentCityCabin/cloud.js"></iframe>
```
