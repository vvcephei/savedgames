This is a personal repo to store game scripts and states.

There are no actual game files (executables, data, etc.) here, just the configs and volatile state I'd like to preserve and move between machines.

For that reason, there doesn't seem to be a reason to keep the repo private. If you want to restore one of my saved games, go for it ;)

If it's randomly helpful for you to copy my configs, even better.

For context, I tend to add `${HOME}/bin` to the end of my `$PATH` and then symlink executables to my `~/bin` directory. This prevents my path from getting too polluted, and it also keeps all my user-space executables linked within my home directory rather than `/usr/bin` or something. 

## Quest for Glory I

I bought this game from GOG.

I followed these setup guides:
* http://www.gamersonlinux.com/forum/threads/dosbox-generic-guide.404/
* http://www.gamersonlinux.com/forum/threads/quest-for-glory-1-4-guide.558/

For this setup, I went the route of the EGA game, and installed Timidity. I noticed that the ubuntu package for it installs a SysV init script, so you don't have to start it on the command line every time. Nice.

For convenience, set up the symlink: `ln -s  ~/games/saves/qfg1/play-qfg1 ~/bin/quest-for-glory-1`.
