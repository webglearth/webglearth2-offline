WebGL Earth offline demo
========================

The WebGL Earth API with custom tiles derived from Natural Earth data.

Tiles rendered by MapTiler (http://www.maptiler.com/).
For preparing custom map tiles see this step-by-step tutorial: http://www.maptiler.com/how-to/3d-online-globe/

Download and unzip this repository (or clone it with git):
https://github.com/webglearth/webglearth2-offline/archive/gh-pages.zip

This example runs offline as well, but the data must be opened over HTTP protocol.

Direct opening of the HTML file in a downloaded directory is unfortunatelly not possible because of the default security restrictions of the web browser for loading WebGL textures.

Once the globe is hosted on your webserver it runs perfectly.

To develop and work with this example locally on your computer:

A) either turn off temporarily the security restrictions of your web browser. See:
https://github.com/mrdoob/three.js/wiki/How-to-run-things-locally#change-local-files-security-policy

B) or start in the directory with the code a simple web server with the command:

$ python -m SimpleHTTPServer

then you can (even without connection to Internet) open the globe at:

http://localhost:8000/

and you should see this:

![WebGL Earth Offline](https://cloud.githubusercontent.com/assets/59284/5442815/cc863142-849c-11e4-8b1b-47b78eafc3ab.jpg)
