# mkarduino

This makefile nets you a dockerized arduino application.  I made this as
the community AUR packages were giving me issues awhile back.  Now that
it's in docker I have not had an issue since.


### Usage

`make` 

This will prompt you for your sketchbook directory (usually
`~/sketchbook`, and sometimes `~/Arduino`). And a `git` directory, which
is where most of my code lives, but you can feed it any directory and it
will be mounted in your arduino environment. It will then create an
Xauthority file and boot an arduino IDE for you to program arduinos.

#### Enter

`make enter` - This will get you a bash shell inside the running container

#### Logs 

`make logs` - This will show you the logs of the running container

#### Help

`make help`  - This will print some useless information
