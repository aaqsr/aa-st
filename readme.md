# New build of st 

This is my new build of suckless' simple terminal (st).
It is very WIP, and currently quite barebone until I stop deciding what I want to patch in and actually patch it in.
You shouldn't really install it rn.

## Dependencies

* Compton (or xcompmgr) *(transparency)*
* libxft-bgra *(colour emoji)*

## Currently applied patches:

* Alpha *(transparency)*
* AnySize *(Resizing better)*
* Bold is not bright *(Bold text is not bright)*
* Desktopentry *(Add a .desktop for st file in /usr/share/applications)*
* Font2 *(Set a second font for better emoji support)*
* Scrollback (all 3 diffs) *(For scrolling with mousewheel with editable speed)*
