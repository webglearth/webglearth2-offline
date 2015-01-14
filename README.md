WebGL Earth offline demo
========================

The WebGL Earth API with custom tiles derived from Natural Earth data.
Tiles rendered by MapTiler (http://www.maptiler.com/).

The example runs offline, but the data must be opened over HTTP protocol.

If you start in a local directory a simple web server with command:

$ python -m SimpleHTTPServer

then you can (even without connection to Internet) open the globe at:

http://localhost:8000/

and you should see this:

![WebGL Earth Offline](https://cloud.githubusercontent.com/assets/59284/5442815/cc863142-849c-11e4-8b1b-47b78eafc3ab.jpg)

If you can't start a local web server, then an alternative is to turn off the security restrictions of your web browser as described at: https://github.com/mrdoob/three.js/wiki/How-to-run-things-locally
