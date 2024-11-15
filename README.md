# ![icon](data/icon.png) Notejot

## Stupidly simple sticky notes applet

[![Get it on AppCenter](https://appcenter.elementary.io/badge.svg)](https://appcenter.elementary.io/com.github.lainsce.notejot)

[![Build Status](https://travis-ci.org/lainsce/notejot.svg?branch=master)](https://travis-ci.org/lainsce/notejot)
[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](http://www.gnu.org/licenses/gpl-3.0)

<div align="center">
    <img src="https://github.com/teamcons/notejot-gtk4/blob/main/data/shot.png" /></td>
</div>


## Dependencies

Please make sure you have these dependencies first before building.

```bash
granite
gtk+-4.0
gtksourceview-3.0
libjson-glib
libgee-0.8
meson
vala
```

## Building

Simply clone this repo, then:

```bash
meson build && cd build && meson configure -Dprefix=/usr
sudo ninja install
```

## Notes Storage
Notes are stored in `~/.local/share/com.github.lainsce.notejot/`

## Acknowledgments

A fork of https://github.com/lainsce/notejot

Current Notejot is very different, and much detached from its elementary OS roots
Consider giving a few penny the way of the original author !


