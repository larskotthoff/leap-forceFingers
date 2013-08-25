Demo for the [Leap Motion Controller](https://www.leapmotion.com/) using the [D3
force layout](https://github.com/mbostock/d3/wiki/Force-Layout). The node
clusters correspond to your hands and fingers and will be matched accordingly.
Matched nodes will change colour; moving the corresponding finger will move the
node. When the finger is removed, the node "snaps" back into place.

See http://www.larsko.org/v/lff for a live demo. You'll need a Leap Motion
Controller hooked up with the Websocket interface running, otherwise it'll
behave like a normal force layout.
