st-pizz
--------------------

Added Droid Sans Font and [base16 colorscheme](https://github.com/d3m1gd/base16-st).
Added PKGBUILD https://aur4.archlinux.org/packages/st-pizz/

Vim colorscheme can be obtained [here](https://github.com/chriskempson/base16-vim/)

st - simple terminal
--------------------
st is a simple terminal emulator for X which sucks less.


Requirements
------------
In order to build st you need the Xlib header files.


Installation
------------
Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

    make clean install


Running st
----------
If you did not install st with make clean install, you must compile
the st terminfo entry with the following command:

    tic -s st.info

See the man page for additional details.

Credits
-------
Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.

