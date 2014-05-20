Pronet Tools and APIs
=====================

**Pronet - Prodapt's M2M/IoT Application Enabling Platform Tools**

RESOURCES
---------

Pronet - Scl Base
-----------------
```
URL: http://abc.xyz.com/pronet
Method: HTTP:GET

```
Applications
------------
```
URL: http://abc.xyz.com/pronet/applications
Method: HTTP:GET, HTTP:POST
Data Model: Application
```
Application
-----------
```
URL: http://abc.xyz.com/pronet/applications/<appId>
Method: HTTP:GET, HTTP:PUT, HTTP:DELETE
```
Containers
----------
```
URL: http://abc.xyz.com/pronet/applications/<appId>/containers
Method: HTTP:GET, HTTP:POST
Data Model: Container
```
Container
---------
```
URL: http://abc.xyz.com/pronet/applications/<appId>/containers/<containerId>
Method: HTTP:GET, HTTP:PUT, HTTP:DELETE
```
ContentInstances
----------------
```
URL: http://abc.xyz.com/pronet/applications/<appId>/containers/<containerId>/contentInstances
Method: HTTP:GET, HTTP:POST
Data Model: ContentInstance
```
ContentInstance
---------------
```
URL: http://abc.xyz.com/pronet/applications/<appId>/containers/<containerId>
Method: HTTP:GET, HTTP:PUT, HTTP:DELETE
```
Commands
--------
```
URL: http://abc.xyz.com/pronet/applications/<appId>/containers/<containerId>/commands
Method: HTTP:GET, HTTP:POST
Data Model: Command
```
Command
-------
```
URL: http://abc.xyz.com/pronet/applications/<appId>/containers/<containerId>/commands/<commandId>
Method: HTTP:GET, HTTP:PUT, HTTP:DELETE
```
