[![License GPL 3][badge-license]](http://www.gnu.org/licenses/gpl-3.0.txt)
![issues](http://img.shields.io/github/issues/rocher/ubuntu-theme.svg)
[![Gratipay](http://img.shields.io/gratipay/rocher.svg)](https://www.gratipay.com/rocher/)


## About ##

`ubuntu-theme` has been inspired by the default terminal colors in Ubuntu.


## Installation ##

### Manual ###

Download `ubuntu-theme.el` to the dierctory `~/.emacs.d/themes` and add this
line to your `.emacs` file:

```lisp
(add-to-list 'custom-theme-load-path "~/.emacs.d/themes/")
```

### Package.el ###

Ubuntu theme is available in [MELPA](http://melpa.org).

You can install `ubuntu-theme` with:

`M-x package-install ubuntu-theme`

## Load ##

To load `ubuntu-theme` automatically on Emacs startup, add this to your init
file:

```lisp
(load-theme 'ubuntu t)
```

You can load the theme manually with the interactive function `load-theme`:

`M-x load-theme RET ubuntu RET`


# Bugs & Improvements #

Please report any problems that you find on the
[project issue tracker](https://github.com/rocher/ubuntu-theme/issues). If
you've added some improvements and you want them included upstream don't
hesitate to send me a patch or even better - a GitHub pull
request.


[![Support via Gratipay](https://cdn.rawgit.com/gratipay/gratipay-badge/2.3.0/dist/gratipay.png)](https://gratipay.com/rocher/)
