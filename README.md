## Server for uploading and showing png files

Run <tt>npm install formidable</tt>.

<tt>var formidable = require("formidable");</tt>

Use formidable to parse the uploaded png file.

== Files included:

1. index.js: create the handle object and start the server.

2. server.js: http create server, listen on port 8888 and pass objects to router.

3. router.js: if pathname exists, pass req and res to handler.

4. requestHandlers.js: handle the request accordingly.