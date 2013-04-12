mapservice-upstart
==================

mapservice.conf file for ubuntu upstart

Using the Script
================

Find this line and edit the directory to point towards your install of mapservice:  

```env HOME=/opt/apps/mapservice```  

If you need to change the operating user, directory of node install, or logging location, find and edit the following line accordingly:  

```exec /usr/bin/node server.js > logs/node.log &```  

When the script is configured to your liking, place it in the following directory:  

```/etc/init ```  

If you kept the script the same name ```mapservice.conf``` then you can run the following self-descriptive commands:  

```
start mapservice
stop  mapservice
```

You're done! Move on.
