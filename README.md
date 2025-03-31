# tomorrow-night-deepblue-theme.el (Emacs theme)
![Build Status](https://github.com/jamescherti/tomorrow-night-deepblue-theme.el/actions/workflows/ci.yml/badge.svg)
[![MELPA](https://melpa.org/packages/tomorrow-night-deepblue-theme-badge.svg)](https://melpa.org/#/tomorrow-night-deepblue-theme)
[![MELPA Stable](https://stable.melpa.org/packages/tomorrow-night-deepblue-theme-badge.svg)](https://stable.melpa.org/#/tomorrow-night-deepblue-theme)
![License](https://img.shields.io/github/license/jamescherti/tomorrow-night-deepblue-theme.el)
![](https://raw.githubusercontent.com/jamescherti/tomorrow-night-deepblue-theme.el/main/.images/made-for-gnu-emacs.svg)

The **Tomorrow Night Deepblue Emacs theme** is a beautiful deep blue variant of the Tomorrow Night theme, which is renowned for its elegant color palette that is pleasing to the eyes.

The **Tomorrow Night Deepblue theme** features a deep blue background color that creates a calming atmosphere. The theme is also a great choice for those who miss the blue themes that were trendy a few years ago.

## Table of Contents

- [Screenshot](#screenshot)
- [Installation](#installation)
- [Authors](#authors)
- [Links](#links)

## Screenshot

![](https://raw.githubusercontent.com/jamescherti/tomorrow-night-deepblue-theme.el/master/.screenshot.png)

The theme was inspired by classic text editors such as QuickBASIC, RHIDE, and Turbo Pascal, as well as tools such as Midnight Commander which featured blue backgrounds by default. There's something special about the early days of programming and the tools we used that brings back fond memories.

## Installation

To install `tomorrow-night-deepblue-theme` from MELPA:

1. If you haven't already done so, [add MELPA repository to your Emacs configuration](https://melpa.org/#/getting-started).

2. Add the following code to your Emacs init file to install `tomorrow-night-deepblue` from MELPA:
``` emacs-lisp
(use-package tomorrow-night-deepblue-theme
  :ensure t
  :config
  ;; Disable all themes and load the Tomorrow Night Deep Blue theme
  (mapc #'disable-theme custom-enabled-themes)
  ;; Load the tomorrow-night-deepblue theme
  (load-theme 'tomorrow-night-deepblue t))
```

## What are the differences between Tomorrow Night Blue and Deepblue themes?

The main differences lie in the background and a large number of additional faces, which enable support for many more modern Emacs packages. Currently, Tomorrow Night Deepblue supports over 1,170 faces (compared to 333 in the original version), featuring a background color reminiscent of classic editors. The author plans to make further changes to support even more faces. Contributions are welcome!

The background is also different. Here is the background color of the Tomorrow Night Deepblue:

![](https://raw.githubusercontent.com/jamescherti/tomorrow-night-deepblue-theme.el/master/.background-tomorrow-night-deepblue.png)

And this background color or the Tomorrow Night Blue, the previous version upon which this theme is based:

![](https://raw.githubusercontent.com/jamescherti/tomorrow-night-deepblue-theme.el/master/.background-tomorrow-night-blue.png)

## Authors

The `Tomorrow Night Deepblue` Emacs theme has been written by [James Cherti](https://www.jamescherti.com/) and is distributed under terms of the GNU General Public License version 3, or, at your choice, any later version.

The tomorrow-night-deepblue theme is based on Tomorrow Night Blue by Chris Kempson, Steve Purcell, and Donald Curtis.

## License

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.

## Links
- [tomorrow-night-deepblue-theme.el @GitHub](https://github.com/jamescherti/tomorrow-night-deepblue-theme.el)
- [tomorrow-night-deepblue-theme.el @melpa.org](https://melpa.org/#/tomorrow-night-deepblue-theme)
- [Announcement in James Cherti's website about the Tomorrow Night Deepblue Emacs theme](https://www.jamescherti.com/emacs-tomorrow-night-deepblue-theme-a-refreshing-color-scheme-with-a-deep-blue-background/)
- [Vim version: Tomorrow Night Deepblue for the Vim editor](https://www.jamescherti.com/vim-tomorrow-night-seablue-theme-color-scheme/)

Other Emacs packages by the same author:
- [minimal-emacs.d](https://github.com/jamescherti/minimal-emacs.d): This repository hosts a minimal Emacs configuration designed to serve as a foundation for your vanilla Emacs setup and provide a solid base for an enhanced Emacs experience.
- [compile-angel.el](https://github.com/jamescherti/compile-angel.el): **Speed up Emacs!** This package guarantees that all .el files are both byte-compiled and native-compiled, which significantly speeds up Emacs.
- [easysession.el](https://github.com/jamescherti/easysession.el): Easysession is lightweight Emacs session manager that can persist and restore file editing buffers, indirect buffers/clones, Dired buffers, the tab-bar, and the Emacs frames (with or without the Emacs frames size, width, and height).
- [outline-indent.el](https://github.com/jamescherti/outline-indent.el): An Emacs package that provides a minor mode that enables code folding and outlining based on indentation levels for various indentation-based text files, such as YAML, Python, and other indented text files.
- [vim-tab-bar.el](https://github.com/jamescherti/vim-tab-bar.el): Make the Emacs tab-bar Look Like Vim’s Tab Bar.
- [elispcomp](https://github.com/jamescherti/elispcomp): A command line tool that allows compiling Elisp code directly from the terminal or from a shell script. It facilitates the generation of optimized .elc (byte-compiled) and .eln (native-compiled) files.
- [Ultyas](https://github.com/jamescherti/ultyas/): A command-line tool designed to simplify the process of converting code snippets from UltiSnips to YASnippet format.
- [dir-config.el](https://github.com/jamescherti/dir-config.el): Automatically find and evaluate .dir-config.el Elisp files to configure directory-specific settings.
- [flymake-bashate.el](https://github.com/jamescherti/flymake-bashate.el): A package that provides a Flymake backend for the bashate Bash script style checker.
- [flymake-ansible-lint.el](https://github.com/jamescherti/flymake-ansible-lint.el): An Emacs package that offers a Flymake backend for ansible-lint.
- [inhibit-mouse.el](https://github.com/jamescherti/inhibit-mouse.el): A package that disables mouse input in Emacs, offering a simpler and faster alternative to the disable-mouse package.
- [quick-sdcv.el](https://github.com/jamescherti/quick-sdcv.el): This package enables Emacs to function as an offline dictionary by using the sdcv command-line tool directly within Emacs.
- [enhanced-evil-paredit.el](https://github.com/jamescherti/enhanced-evil-paredit.el): An Emacs package that prevents parenthesis imbalance when using *evil-mode* with *paredit*. It intercepts *evil-mode* commands such as delete, change, and paste, blocking their execution if they would break the parenthetical structure.
