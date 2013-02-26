About
=====

An emacs 24 (deftheme) color theme. It's super nice!

![subatomic.el - kind of nice, eh?](https://raw.github.com/cryon/subatomic/master/readme-files/subatomic.png "subatomic emacs theme")

Installation
============

MELPA
-----

Subatomic is available in [MELPA](http://melpa.milkbox.net/). Assuming MELPA is added to your archive list you can list the available packages by typing <code>M-x list-packages</code>, look for subatomic-theme, mark it for installation by typing <code>i</code> and then execute (install) by typing <code>x</code>.

(Or you can install it directly with <code>M-x package-install RET subatomic-theme</code>)

After that, enable the theme by <code>M-x load-theme RET subatomic</code>.

Or if you want to do it in your init file, add:

```lisp
(load-theme 'subatomic t)
```

Manual installation
-------------------
If you prefer, you can install Subatomic manually by downloading <code>subatomic-theme.el</code> and place it somewhere in your <code>custom-theme-load-path</code>.

You can set your <code>custom-theme-load-path</code> by adding this to your <code>.emacs.d</code> or <code>.emacs.d/init.el</code>:

```lisp
(add-to-list 'custom-theme-load-path "~/.emacs.d/themes")
```

You should now be able to load Subatomic with <code>M-x load-theme RET subatomic</code>!

Improvements
============

Feel free to report any problems or make suggestions. There are always more faces to color!