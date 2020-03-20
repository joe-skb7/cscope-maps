# cscope-maps

Just old good cscope maps plugin for vim, taken from [1]. Made a mirror just to
use it in unified way with vim package manager. This repository has some
extra improvements on top of original plugin.

## Description

This plugin adds some boilerplate settings for vim's cscope interface, plus some
keyboard mappings that I've found useful.

These key maps use multiple keystrokes (2 or 3 keys). If you find that vim keeps
timing you out before you can complete them, try changing your timeout settings
in plugin file.

For more details please refer to [2].

## Changes

Next changes are made in this repository comparing to original plugin:

* Add key binding to search for C structure (Ctrl-S), in case the structure is
  defined using K&R style, e.g.: `struct abc {`
* Use Ctrl-Space key binding to split vertically (as opposed to horizontal
  split in original plugin). To split horizontally, use Ctrl-Space-Space.
* If `cscope.out` file is missing in current directory, try to look for it
  in upper directories
* Fix some typos

## Installation

* __vim 8__:  Stick this file in `~/.vim/pack/<dir>/start/cscope/plugin/`
              where `<dir>` is any arbitrary name. Lookup Vim8 packages
              for more details.
* __vim 6__:   Stick this file in your `~/.vim/plugin` directory (or in a
              'plugin' directory in some other directory that is in your
              'runtimepath'.
* __vim 5__:  Stick this file somewhere and 'source cscope.vim' it from
              your `~/.vimrc` file (or cut and paste it into your `.vimrc`).

[1] http://cscope.sourceforge.net/cscope_maps.vim

[2] http://cscope.sourceforge.net/cscope_vim_tutorial.html
