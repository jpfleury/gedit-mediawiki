**Note: This syntax highlighting file is now officially [included in GtkSourceView](https://github.com/GNOME/gtksourceview/commit/db965e3ac704c574d04023606d4b7afc4ec133ad) since version 3.9.2.**

## Overview

gedit-mediawiki adds [MediaWiki](http://meta.wikimedia.org/wiki/Help:Editing) syntax highlighting to gedit, the default GNOME text editor.

Here's a screenshot:

<img src="https://raw.githubusercontent.com/jpfleury/gedit-mediawiki/master/doc/exemple1.png" width="685" height="1112" alt="MediaWiki syntax highlighting in gedit." />

## Installation

- [Download the archive of the latest version.](https://github.com/jpfleury/gedit-mediawiki/archive/master.zip)

- Extract the archive.

- Copy the file `mediawiki.lang` in one of the following two locations (create the folder if it doesn't yet exist):

	- for gedit 2: `~/.local/share/gtksourceview-2.0/language-specs/`
	- for gedit 3: `~/.local/share/gtksourceview-3.0/language-specs/`

MediaWiki syntax highlighting will be added for the current user (so no need root privileges). The folder created by the extraction can be deleted after installation.

## Uninstallation

Remove the file previously installed.

## Usage

First of all, restart gedit if it's already running.

Choose syntax highlighting by going to *View > Highlight Mode > Others* and selecting *MediaWiki*.

The folder `doc` contains a demo file.

## Development

Git is used for revision control. [Repository can be browsed online or cloned.](https://github.com/jpfleury/gedit-mediawiki)

## License

Author: Jean-Philippe Fleury (<https://github.com/jpfleury>)  
Copyright © 2009 Jean-Philippe Fleury

This library is free software; you can redistribute it and/or
modify it under the terms of the GNU Lesser General Public
License as published by the Free Software Foundation; either
version 2.1 of the License, or (at your option) any later version.

This library is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public
License along with this library; if not, write to the Free Software
Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA  02110-1301  USA
