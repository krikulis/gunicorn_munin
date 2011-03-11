=====================
Gunicorn munin plugin
=====================

Based on Unicorn munin plugin by Shinji Furuya.

============
Requirements 
============
Ruby 

============
Install
============
* drop into your munin plugins directory 
* add to plugins-conf.d folllowing line 
  `
    env.GUNICORN_PIDFILE /path/to/gunicorn.pid 
  ` 



