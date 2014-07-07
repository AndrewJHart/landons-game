Up and Running
=====================

To get this running locally you need to have `homebrew` installed or checkout different instructions.
Using brew copy and paste these commands:

`brew install mercurial`
`brew install sdl sdl_image sdl_mixer sdl_ttf portmidi`
`sudo pip install hg+http://bitbucket.org/pygame/pygame`

Then test by running 

```bash

$ python
$ import pygame

```

if you get no errors then install the dependencies from requirements.txt using 
`pip install -r requirements.txt` preferrably in a virutal environment. 
