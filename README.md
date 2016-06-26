# README #

A simple bash script to link/ unlink nginx webserver config files from sites available to sites-enabled.

### What is this repository for? ###

* nginx link/unlinker
* 1.0

### How do I set it up? ###

* Just mv|copy|link it to /usr/bin/nginxctl to make it usable

### How to use? ###

* nginxctl [ENTER]													# lists args and existing servernames
* nginxctl start servername [ENTER]					# link servername into sites-enabled
* nginxctl stop  servername [ENTER]					# unlink servername from sites-enabled
* nginxctl reload  [ENTER]									# reload nginx server configs
* nginxctl restart [ENTER]									# restart nginx main server
* nginxctl create  servername 1 1 1[ENTER]	# create servername config (php log index)
																						# first param {0|1} add php-fpm stuff
																						# secnd param {0|1} add logfile stuff
																						# third param {0|1} add index file into webroot
* nginxctl destroy servername [ENTER]				# delete a server (remove all files!)

