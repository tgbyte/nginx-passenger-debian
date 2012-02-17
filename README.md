This repository contains a version of nginx patched to include support for Phusion Passenger that can be built as a Debian package.

## Build Instructions ##

Make sure that Ruby is correctly set up (we recommend rvm for this task) and install the passenger gem. Next, check out this repository and build its Debian packages using

    fakeroot dpkg-buildpackage

Install the resulting `nginx-passenger` and `nginx-common` .deb packages and you are done.

## General Information ##

General documentation for nginx is available at http://nginx.org

