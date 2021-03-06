OpenTele Android Client
=======================
Android-based patient app for the OpenTele platform.

Please note
----------------------
This repository is maintained exclusively by Silverbullet. The official version maintained by 4S can be found [here](https://bitbucket.org/4s/opentele-client-android).

How to build and install
------------------------
The build is Maven-based, so build and run tests by running

    mvn clean install

Setting server URL
------------------
The server URL is set by the Maven variable ``server.url``. When starting the app in a development environment, it may
be more convenient to log in with user name ``admin``, password ``admin``, which will give you a menu from where you
can change the server URL. This is only possible if the Maven variable ``server.url.locked`` is ``false``.