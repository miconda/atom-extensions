# Kamailio.cfg Syntax Highlighting for Atom Editor

Atom editor extension that provides syntax highlighting for Kamailio configuration files.

## Overview

Atom is an open source editor developed by Github, more about it can be found at:

  * https://atom.io

Kamailio is an open source SIP server that can be used for VoIP, instant messaging and presence, with support for WebRTC, more about it can be found at:

  * [Kamailio Website](http://www.kamailio.org)
  * [Github Project](https://github.com/kamailio/kamailio)

The configuration file for Kamailio uses its own scripting language, so it needs a custom syntax highlighting extensions.

## Installation

Clone this repository via git from:

  * https://github.com/miconda/atom-extensions
  * copy the subfolder *language-kamailio* to *~/.atom/packages/*

Shell commands:

```
git clone https://github.com/miconda/atom-extensions
cp -a atom-extensions/language-kamailio ~/.atom/packages/
```

### Reload Atom Extensions

If Atom is already running, you will have to reload its extensions.

Type [cmd]-[shift]-[p] to bring up command panel and execute ```Window: Reload```. This flash the screen briefly. With recent version of Atom, a direct key combination is [cmd]-[alt]-[ctrl]-[l].

## Setting Syntax Language

The kamailio syntax highlighting language is set if the file has the extension **cfg** and the first line contains one of the words: kamailio, sip-router, openser or ser (both alternatives with lower and upper cases work).

The language can be explicitly set by running [ctrl]-[shift]-[l] and selecting **Kamailio** from the popup panel.

## Contributions

Any suggestions, improvements or new features are welcome. For submitting patches, do pull requests via Github.
