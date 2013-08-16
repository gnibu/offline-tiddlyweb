offline-tiddlyweb
=================

Synchronize a local dir with a remote tiddlyweb bag or recipe to allow offline editing with any editor.

I intend to synchronize to a dropbox folder to allow offline editing on mobile devices.

At the moment synchro is possible only one way: server to local folder.
The authentication is mandatory.

Here is a sample comfig file

```
[server.test.org]
url = http://server.test.org/wiki/bags/common
authentication = true
user = gnibu
localfolder = ~/tiddlers
passwordfile = ~/.mypassfile

[general]
repositories = mind.niak.net
```

