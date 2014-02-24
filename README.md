dotfiles
=========
<br>
Over time a developer adds many aliases, functions, and tools to ease the workflow process. This repo organizes them into seperate dotfiles allowing the developer to be up and running on a new machine in no time. Thanks to the developers for their original work below:

* [Simon Owen]
* [mathiasbynens]
* [dotfiles.github.io]
* [Paul Irish]

How To
----
- BACK UP YOUR DOTFILES! Do it.
- Open Terminal
- Make a directory for dotfiles. I recommend something like ~/dotfiles/okami-/.
- cd into that directory 

```sh
git clone git@github.com:Okami-/dotfiles.git
./bootstrap.sh  *WARNING* This will overwrite your dotfiles
source ~/.bash_profile
```
You should now have a new colorful terminal with a ton of aliases, functions and helpers. You probably want to start grabbing your old stuff and updating your new dotfiles. Later on your version of dotfiles will change and evolve and you most likely will want to create your own gitrepo of dotfiles ready to bootstrap.sh on any machine anytime.


[Simon Owen]:https://github.com/s10wen/dotfiles
[mathiasbynens]:https://github.com/mathiasbynens/dotfiles
[dotfiles.github.io]:http://dotfiles.github.io/
[Paul Irish]:https://github.com/paulirish/dotfiles    