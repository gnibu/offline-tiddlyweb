offline-tiddlyweb
=================

Synchronize a local dir both ways with a remote tiddlyweb bag or recipe to allow offline editing with any editor.

I intend to synchronize to a dropbox folder to allow offline editing on mobile devices.

The authentication is mandatory.

Files created in the local dir are not created on the server at the moment.

Here is a sample config file

```
[server.test.org]
url = http://server.test.org/wiki/bags/common
authentication = true
user = me
localfolder = ~/tiddlers
passwordfile = ~/.mypassfile
testmode = true 
#will not write local tiddlers on server

[general]
repositories = server.test.org
metadatafolder = ~/.offlinetw
```

