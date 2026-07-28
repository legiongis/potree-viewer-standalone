# standalone potree viewer

This repo is a basic repackaging of the viewer.html example in https://github.com/potree/potree. It has been modified slightly
so that remote potree pointclouds can be passed to the viewer through a `url` URL parameter. For example:

https://legiongis.github.io/potree-viewer-standalone/?url=https://lcai-assets.s3.us-gov-west-1.amazonaws.com/pointclouds/CrescentCityCabin/cloud.js

The purpose of this is simply to make it possible to put it in an iframe while supplying remote data to it.

```
<iframe height="600" width="100%" src="https://legiongis.github.io/potree-viewer-standalone/?url=https://lcai-assets.s3.us-gov-west-1.amazonaws.com/pointclouds/CrescentCityCabin/cloud.js"></iframe>
```
