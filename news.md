---
layout: page
title: News
permalink: /news/
---

### Plugins page added 

Added a [plugins page](https://gnome-terminator.github.io/plugins/) to highlight 3rd party plugins.   There's a page at https://gnome-terminator.readthedocs.io/en/latest/plugins.html that lists 3rd party plugins but I'd like to have a more public place for them.


### History plugin released

[History Commands Plugin](https://github.com/Aravind-art/commads-history-plugin)

A Terminator plugin that displays a searchable command history sidebar, making it easy to browse and re-execute previous commands.

### Terminator 2.1.5 is released

Another Year, another release [Terminator 2.1.5](https://github.com/gnome-terminator/terminator/releases/tag/v2.1.5) As usual, a lot of small bugfixes and quality of life improvements


### Terminator Remote Plugin released

Thanks to Asif Amin, there's a new remote plugin.

This plugin will look for a child remote session inside terminal using the psutil API and provide mechanisms in the context menu to clone session into a new terminal and/or change profiles based on the remote type or host.

* Cloning sessions inspired from <https://github.com/ilgarm/terminator_plugins>
* Host profile matching inspired from <https://github.com/GratefulTony/TerminatorHostWatch>

You can download it from <https://github.com/gnome-terminator/terminator/blob/master/terminatorlib/plugins/remote.py> and install it by putting the file in ~/.config/terminator/plugins/

### Terminator 2.1.4 is released

This release is the result of a year's worth of small bugfixes and features from a vast array of contributors.  Go to [the releases page](https://github.com/gnome-terminator/terminator/releases/tag/v2.1.4) to see all the fixes and new features, and all of the fantastic contributors that made this release possible

The update is currently available for Ubuntu through the [Terminator PPA](https://launchpad.net/~gnome-terminator/+archive/ubuntu/ppa), and is winding it's way through the Debian packaging process and is currently in testing [Package Page](https://packages.debian.org/trixie/terminator).  Hopefully we can get it backported to the current release.  It has also been released for Fedora 40, and is in EPEL 8 and EPEL 9, so if you're running the current version of Fedora, or any of the RedHat derivatives, it should just be a `dnf install terminator` away.
