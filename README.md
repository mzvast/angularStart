## Build & development

Run `grunt` for building and `grunt serve` for preview.

## Testing

Running `grunt test` will run the unit tests with karma.

## Production
Run `node index.js` will serve the dist folder.

## Simple API server forward 
###Development env: 

Defined in Gruntfile.js

For testing purpose, run `grunt serve --api=qq`to set the API server to be www.qq.com

By default(without --api param), the api server is set to localhost:8080

To set any API server you want, just run `grunt serve --apiHost=hostname --apiPort=portnumber

###Production env:

Defined in index.js.Change variable apiForwardingUrl to set your host:port
