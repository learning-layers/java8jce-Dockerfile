# java8jce-Dockerfile
A Dockerfile generating a Learning Layers base image with Oracle Java 8 incl. Crypto Extensions.

This image augments the default Learning Layers base image with an installation of Oracle Java 8, including respective Java Cryptography Extensions. These extensions are especially necessary for all [las2peer](https://las2peer.org) service modules to be included in Layers Boxes. Thus, any image designed to start las2peer nodes should be based on this image. 
