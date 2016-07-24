WinScreenyCmder
======
WinScreenyCmder is Screenfetch for Windows, made for using together with Cmder console emulator and bash shell.
You know those linux desktop hipster threads that everyone goes around posting
their OS information with the ASCII OS logo next to it? That's this. But, for Windows.

![WinScreenyCmder](http://i.imgur.com/M4Z7NHl.png)

# Requirements
Download and install required software:
- **Cmder**, with `bash` and `git-for-windows`: http://cmder.net/. This program was developed for using with Cmder, and may not work properly under other console emulators.
- **XMLStarlet**: http://xmlstar.sourceforge.net/.

# Installation
Download `screeny` and place it in your `$CMDER_ROOT/bin` or another folder.

# Usage
If the script was placed in a folder which is included to the `$PATH` envvar:
``` bash
$ screeny
```

Otherwise:
``` bash
$ ./screeny
```

# License
Licensed under AOL <http://aol.nexua.org>.

Forked from WinScreeny (by Nijikokun, https://github.com/nijikokun/WinScreeny).

Fixed for compatibility with Cmder & Windows 10 by Slava Eremenko, https://github.com/yaroslaveremenko
