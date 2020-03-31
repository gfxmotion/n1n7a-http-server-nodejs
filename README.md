# n1n7a-http-server-nodejs

Simple Express Nodejs Static File Server

A very simple static file server. For development use only.

## Installation

### Using as a local module (recommended)

    $ npm install 
    $ ./node_modules/.bin/simple-server my/public/dir


### Using the server as a global module

    $ sudo npm install -g 
    $ simple-server my/public/dir
    
## Contribute

Install dependencies (first time only):

    $ npm install

How to start:

    $ pm2 start server.js --watch

How to stop: 
    $ pm2 stop server.js


Open [http://localhost:4567](http://localhost:4567)

If you need a different port:

    $ PORT=9999 node server

Open [http://localhost:9999](http://localhost:9999)

If you need a different hostname:

    $ HOSTNAME=192.168.0.1 node server

Open [http://192.168.0.1:4567](http://192.168.0.1:4567)

pm2 docs: [https://pm2.keymetrics.io/docs/usage/process-management/](https://pm2.keymetrics.io/docs/usage/process-management/)

html5 boilerplate [https://html5boilerplate.com/]https://html5boilerplate.com/
inspired by [https://github.com/spadin/simple-express-static-server] https://github.com/spadin/simple-express-static-server