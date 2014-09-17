# gedit-pig

This project adds [Apache Pig](http://pig.apache.org/) syntax highlighting to any editor that uses GtkSourceView.

Currently, Pig 0.11 is supported.

## Installation Instructions for Gedit

Place the appropriate *pig.lang* file in your gedit installation and restart gedit. Files with the *.pig* extension should be highlighted.

### Windows

1. Go to the *language-specs* directory within your gedit installation (normally within *C:\Program Files (x86)\gedit\share\gtksourceview-2.0*)

2. Add the *pig.lang* file from the *gtksourceview-2.0* directory in this repository there.

### Linux

## Local Installation

1. If it does not exist, add the *gtksourceview-3.0* directory and its contents from this repository to *~/.local/share/*

2. If it does exist, add the appropriate *pig.lang* file from this repository there.

3. When you are done, the file's path should be *~/.local/share/gtksourceview-3.0/language-specs/pig.lang*

## Global Installation

1. Add the *pig.lang* files from this repository to their matching directories in */usr/share*

2. When you are done, the file's path should be */usr/share/gtksourceview-3.0/language-specs/pig.lang*
