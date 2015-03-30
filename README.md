bootya
======

A simple tool for bootstrapping an erlang project with yaws, jiffy and
erlang.mk. Primarily for my own purpose, but supposedly also for others that,
like me, often make similar projects using these tools. 

Usage
-----

> mkdir proj_name
> cd proj_name
> wget -O - https://raw.githubusercontent.com/peffis/bootya/master/bootya | sh
> make

and then running it

> _rel/proj_name_release/bin/proj_name_release console

which will start yaws on 8080 serving pages from proj_name/src/www and
also running the appmod proj_name_appmod.erl at /proj_name