# Clusterio

Clusterio allows factorio mods to communicate outside the game. This is the client side mod. To work, 
it also requires a server side mod located at https://github.com/clusterio/factorioClusterio . It also
has the full readme, so head over there. 

Another practical side project is the clusterio client, which is a standalone app that makes it easier to 
connect to clusterio servers. Its still very much WIP at the point of writing and not really recommended.

https://github.com/Danielv123/factorioClusterioClient

## Build Instructions

Install Node.js version 10 or later and run `npm install` then run `node build`.  It will output the
built mod into the `dist` folder by default.  See `node build --help` for options.
