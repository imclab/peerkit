# TODO:


## Move images not on page out of ResourceManager into memory for possible sharing
## What to do if getFile fails for image we thought was in cache? (Image will not make it on to downloadList)
## If we get expired images, we currently use it anyways but remove from cache for next time. What if a peer requests this image (that is expired but in memory)?
## What is expiry of image received from peer? (This should be coming from server but currently is not)
## Detect if browser not compatible and fallback gracefully
## Replenish CONN objects with message from server to client
##Implement this._pc.oniceconnections when it exists See peer.js lines 43-44 for details. https://groups.google.com/d/msg/discuss-webrtc/vTCvw-L0P20/kie7GKDOKj4J