Much Fire - So Hot
==================

AGILE Workflow
--------

###Deprecated!
#This repository will no longer use the Waffle.io service and will migrate to another service soon.
#
#https://waffle.io/Auruss/MuchFireSoHot is our AGILE issue board which is connected with github issues.
#
### Using our Agile board at waffle.io
#It is self explaining, you grab any 'ready' issue you want but try to do things from the top to bottom since they #are sorted.
#
## Agile
#Our workflow is currently Kanban orientated, but we might switch to Scrum if the game reaches a further state.
#
## Backlog
#People with access to backlog:
#- Rene Eichhorn
#
#Anybody else should not grab these issues however you are free create new tickets (this is encouraged)
###

Building
--------
Our build system is currently development only (no release builds yet)
On windows simply run build.bat on any other system build.sh

Checklist before building:
- CMake 2.x
- Emscripten
    -- we made some changes to emscripten which are not live yet, so you need to use the incoming branch of emscripten or the master of my fork

Running
-------
Since modern browsers use safe checks you can't use debugger.html using file:// protocol, you are going to need at least a simple web server (http)

WebApp
------
The web-app is currently completely on hold since the game should be focus #1 at the moment.
Once the game reaches an stage where you can actually play and enjoy it the web-app is continued.
