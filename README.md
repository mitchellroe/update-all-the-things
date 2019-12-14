# Update All The Things

This is a small Python script which works to Update All The Things on your
Linux installation.

Ever get tired of running `apt` or `yum`, then realizing that your snap
packages are probably out of date, then you remember flatpak sitting over
there, then pip, then ...  You get the idea.  This little program checks for a
set of commands on your Linux installation, and if it finds them, it tries to
update all the packages in those package managers.

This is still a work in progress, and primarily intended as a learning exercise
(i.e. to write this same code in bash would take literally 60 seconds).  I'm
working my way through `apt` right now, but have plans to implement support for
the following languages:

- apt
- yum / dnf
- flatpak
- snap
- pip3
- (maybe) npm
