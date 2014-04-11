mobyle2.conf
============

Common configuration for mobyle2

To execute with paste deploy, see below.

To launch the default application (app:main), the mobyle.web application in our case:

    pserve mobyle.ini


To launch a specific application with a specific server/port (datamanager below):

    pserve  --app-name=datamanager --server-name=datamanager  mobyle.ini
