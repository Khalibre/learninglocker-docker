Learning locker docker images
This repository contains the Dockerfile to build images for:

learning locker, a LRS to store and analyze xAPI statements.

Building learning locker image
To build a learning locker image, you have to pick the right tag to use and then build it using the following docker command (here with the v7.0.0 tag):

$ docker build -t fundocker/learninglocker:v2.6.2 --build-arg LL_VERSION="v7.0.0" learninglocker/
