## This is my bindings file, there are many like it but this one is mine
## I use the micro text editor, it's quite good, find it here
https://micro-editor.github.io/

- My bindings are always evolving 
- I wish I had more fingers
- to get the full experience bind Alt-W to toggle window max (keyboard settings)
- and Alt-t to open new terminal window
- and Alt-= to zoom in and Alt-- to zoom out in term
- and Alt-Spacebar to open menu
- and bind Alt-, to close  window
- and bind Alt-7 to Show Desktop
- and put this stuff belowin your ~/.bashrc
```
bind '"\eh": backward-char'
bind '"\el": forward-char'
bind '"\en": beginning-of-line'
bind '"\em": end-of-line'
bind '"\ed": "\C-a\C-k"'
```
- and replace your ~/.config/micro/bindings.json file with this one (usually in ~/.config/micro) delete the old and paste mine in


NOTE: 

Currently I'm trying to bind Alt + hjkl to the arrow keys in general to use on my computer. Running into a few problems.
It seems like no file I put the bind commands in actually executes at startup of the computer. It also seems like
all other Alt + yada yada commands cease to work, which is no bueno. Trying to figure out different ways.
I also want to bind Alt + n and Alt + m to the begining and end of a line, very helpful.


UPDATE!!! Use inputremapper, it's great

https://github.com/sezanzeb/input-remapper

really simple just record your keys and set what you want

KEY_LEFT
KEY_RIGHT
KEY_UP
KEY_DOWN
KEY_HOME
KEY_END

these are the output


--------------------

updates

well I removed a fair bit of the bindings to free up other keys for more useful things

I removed the bindings for d,r,f, T, u, i,g, overall they werent all that useful, i and u specifically are prime real estate
o was a tough one, but i can think of no better way that I like to switch between two pannels, it's really good e is still great and 
can be used for lots of the others because it's command mode and the others that were lost were mostly commands
