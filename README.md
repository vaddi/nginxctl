# README #

A simple bash script to link/ unlink nginx webserver config files from sites available to sites-enabled.

### What is this repository for? ###

* nginx link/unlinker
* 1.0

### How do I get set up? ###

* Just mv/copy it to /usr/bin/nginxctl to make it usable

### How to use ###

nginxctl [ENTER]                        # lists args and possible servernames
nginxctl en servername [ENTER]          # link servername into sites-enabled
nginxctl dis servername [ENTER]         # unlink servername from sites-enabled

