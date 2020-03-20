# cscope-maps

Just old good cscope maps for vim, taken from [1].
Made a mirror just to use it in unified way with pathogen.

## CSCOPE settings for vim
This file contains some boilerplate settings for vim's cscope interface,
plus some keyboard mappings that I've found useful.

### USAGE:
* __vim 8__:  Stick this file in `~/.vim/pack/<dir>/start/cscope/plugin/`
              where `<dir>` is any arbitrary name. Lookup Vim8 packages
              for more details.

* __vim 6__:   Stick this file in your `~/.vim/plugin` directory (or in a
              'plugin' directory in some other directory that is in your
              'runtimepath'.

* __vim 5__:  Stick this file somewhere and 'source cscope.vim' it from
              your `~/.vimrc` file (or cut and paste it into your `.vimrc`).

NOTE:
These key maps use multiple keystrokes (2 or 3 keys).  If you find that vim
keeps timing you out before you can complete them, try changing your timeout
settings, as explained below.

[1] http://cscope.sourceforge.net/cscope_maps.vim
