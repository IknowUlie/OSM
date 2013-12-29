osm-tchoutchou
==============

An Open Street Map (leaflet) interface to Turblog's raildar.fr data.

Demo : http://raildar.bumblebee.cc

Some details on the original raildar map and API : http://blog.spyou.org/wordpress-mu/2013/11/30/jstchoutchou/


How to install :
----------------
Install python-pip and python-virtualenv on your system then run
```
./install.sh
```

If you have some porblems when compiling lxml you should install lxml source, for exemple on debian/ubuntu :

```
sudo apt-get install libxml2 libxslt1.1 libxml2-dev libxslt1-dev
```


How to run :
------------

```
./webserver.sh

```
Will launch a python webserver on http://localhost:5000/



Licence :
---------
CC by-sa / GNU AGPL