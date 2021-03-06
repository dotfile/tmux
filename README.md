tmux configs
============
Opinionated tmux configs that might get updated.

Installation
------------
Because I'm lazy af sometimes,

```
cd ~/.config
git clone git@github.com:dotfile/tmux.git
ln -s ~/.config/tmux/tmux.conf ~/.tmux.conf
```

Or at work,

```
mkdir -p ~/Development/1st && cd ~/Development/1st
git clone git@github.com:dotfile/tmux.git
ln -s ~/Development/1st/tmux/tmux.conf ~/.tmux.conf
```

And add a local `.git/config` user override:

```
[user]
	name = "Brandon Thomas"
	email = "EMAIL"
```

Reading material
----------------
* https://ebzzry.io/en/tmux/
* https://www.hamvocke.com/blog/a-guide-to-customizing-your-tmux-conf/

License
-------
This isn't code, so it doesn't even really matter. 
If you care, why not the [GNU Free Documentation License 1.3] [1]? 

[1] https://www.gnu.org/licenses/fdl-1.3.en.html

