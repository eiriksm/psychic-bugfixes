psychic-bugfixes
================

Stupid script to get path working dir of a process

A typical use case I use is I don't remember where I have a `compass` process running in some tmux session (when working on multiple projects).

`psychic-bugfixes compass` will tell me what the working directories are of all processes with the word compass. In fact, you can also use it like `psychic-bugfixes comp` and it will probably give you what you need.

## Installation
Assuming you have `pgrep` and `pwdx` installed, and that ~/bin is in your path, you can just run `make install`.

## Requirements
- pgrep
- pwdx

## Licence
[WTFPL](http://en.wikipedia.org/wiki/WTFPL)
