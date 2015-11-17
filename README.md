# urxvt-perls

Modifications to urxvt perl scripts. On Arch Linux these are found in:

    /usr/lib/urxvt/perl/

To use my modifications, just replace my files for the ones in the folder above.

## .Xdefaults/.Xresources file

To be able to see which tab is active, I can recommend following settings:

    URxvt.tabbed.tabbar-fg: 15
    URxvt.tabbed.tabbar-bg: 0
    URxvt.tabbed.tab-fg:    15
    URxvt.tabbed.tab-bg:    8

## tabbed

* Alt-1, Alt-2, ... can now be used to change tab, like most terminals.
* Ctrl-Shift-t creates a new tab.
* Removed the "NEW" button.
* New tabs open in the same directory as the current (does not work with urxvtd and urxvtc).

## Resources and thanks to

- [clchiou](https://github.com/clchiou/urxvt-config) for adding support for opening tabs with Ctrl-Shift-T and changing tab with Alt-1, Alt-2, Alt-3, ...
- [df7cb](https://www.df7cb.de/blog/2014/New_urxvt_tab_in_current_directory.html) for a patch that makes new tabs open in the current directory.
