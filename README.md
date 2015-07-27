# patches
Various patches that not into upstream or will not into upstream.


emacs-cjk-monospace-for-emacs-24.5.patch:

The width of CJK character in a code editor should always equal to double of English character width.
This is very useful when processing ascii tables contains cjk and english characters, for example, orgmode.

Since users use Latin fonts to display latin characters and CJK fonts to display CJK characters, There is a problem about the fonts' width.

GVIM/Konsole had special treatment about this issue. but emacs never had and seemed no plan to have one.

This patch is created for emacs-23 and submitted, and no more replies on it.

I ported it to emacs-24.5(should works with emacs-24.4).

