grSim
=====

RoboCup Small Size World Simulator

**This is an incomplete README file**


Min System Requirements
-----------------------

grSim will likely run on a modern dual core PC running Ubuntu with good graphics card. Typical configuration is:

* Dual Core CPU (2.0 Ghz+)
* 1GB of RAM
* 256MB nVidia or ATI graphics card
* Ubuntu Linux 9.10+ 


Software Requirements
---------------------

grSim uses these libraries:

- Nokia Qt 4.6+ (development libraries will be installed with libqt4-dev)
- OpenGL (development libraries will be installed with libqt4-dev)
- Open Dynamics Engine (ODE)
- VarTypes Library
- Google ProtoBuf


Installation
------------

Please refer to INSTALL file.


Usage
-----

Receiving data from grSim is exactly like receiving from SSL-Vision (http://code.google.com/p/ssl-vision) using Google Protobuf library
Sending data to Simulator is also possible using Google Protobuf. A sample client is included in "client" folder. The compilation procedure is like grSim itself. There is also a Java client available in the client folder.


Changelog
---------

Please refer to the CHANGELOG file.

