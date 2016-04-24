CMS para proyecto de Usecm
==========================

Server-API
----------

Se basa en el codigo del curso de BackEdge de Alberto Basalo

Instalacion MongoDB en Imac
---------------------------
==> Summary
🍺  /usr/local/Cellar/openssl/1.0.2g: 1,678 files, 12.0M
==> Installing mongodb
==> Downloading https://homebrew.bintray.com/bottles/mongodb-3.2.5.el_capitan.bo
######################################################################## 100,0%
==> Pouring mongodb-3.2.5.el_capitan.bottle.tar.gz
==> Caveats
To have launchd start mongodb now and restart at login:
  brew services start mongodb
Or, if you don't want/need a background service you can just run:
  mongod --config /usr/local/etc/mongod.conf
==> Summary
🍺  /usr/local/Cellar/mongodb/3.2.5: 17 files, 263.7M

```
./bin/mongod --dbpath "./data"
```
