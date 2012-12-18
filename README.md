# rnc-mode

rnc-mode is an Emacs major mode for editing XML schemas in
[RELAX-NG](http://relaxng.org/)
[Compact](http://relaxng.org/compact-20021121.html) syntax.

The mode was originally written by David Rosenborg at Pantor Engineering, but
recently canonical URL for the mode stopped working, and the code didn't run
in Emacs 23 and later without some minor modifications.

This repo contains an updated version of `rnc-mode` that works in GNU Emacs 23
and later: I have not tried it on XEmacs.

## Installation

Put `rnc-mode.el` in your Emacs path and put the following into your Emacs
initialization file:

    (autoload 'rnc-mode "rnc-mode")
    (add-to-list 'auto-mode-alist '("\\.rnc\\'" . rnc-mode))

I will be adding this to either Marmalade or MELPA in the near future, at
which point the `autoload` will be unnecessary.

## License

I am __not__ the original author.

Copyright &copy; 2002 Pantor Engineering AB.

Distributed under the [BSD Revised License](http://opensource.org/licenses/BSD-3-Clause).
