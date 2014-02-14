Syncerator
================

Keeps things in Sync!


Deployment Watcher
------------------

In a directory tree like
project root/
	src/
	lib/

```bash
git submodule add git@github.com:smj10j/Syncerator.git lib/Syncerator
npm install
./lib/Syncerator/src/autodeployer.sh
```


   
Deployment Dependencies
-----------------------

- Linux
```bash
npm install inotify
```

- OSX 
	- If you want Growl notifications instad of through the Notification center, install Growl Notify:
		1. [Growl](https://itunes.apple.com/us/app/growl/id467939042?mt=12&ign-mpt=uo%3D4)
		1. [Growl Notify](http://growl.cachefly.net/GrowlNotify-2.1.zip)


