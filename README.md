# tomorrow-night-deepblue-theme.el (Emacs theme)
[![MELPA](https://melpa.org/packages/tomorrow-night-deepblue-theme-badge.svg)](https://melpa.org/#/tomorrow-night-deepblue-theme)
![](https://raw.githubusercontent.com/jamescherti/tomorrow-night-deepblue-theme.el/main/.images/made-for-gnu-emacs.svg)
![License](https://img.shields.io/github/license/jamescherti/tomorrow-night-deepblue-theme.el)

The **Tomorrow Night Deepblue Emacs theme** is a beautiful deep blue variant of the Tomorrow Night theme, which is renowned for its elegant color palette that is pleasing to the eyes.

The **Tomorrow Night Deepblue theme** features a deep blue background color that creates a calming atmosphere. The theme is also a great choice for those who miss the blue themes that were trendy a few years ago.

## Table of Contents

- [Screenshot](#screenshot)
- [Installation](#installation)
- [Authors](#authors)
- [Links](#links)

## Screenshot

![](https://raw.githubusercontent.com/jamescherti/tomorrow-night-deepblue-theme.el/master/.screenshot.png)

The theme was inspired by classic text editors such as QuickBASIC, RHIDE, and Turbo Pascal, which featured blue backgrounds by default. There's something special about the early days of programming and the tools we used that brings back fond memories.

## Installation

The `tomorrow-night-deepblue` theme can be installed from MELPA by adding the following to your init.el:
``` emacs-lisp
(use-package tomorrow-night-deepblue-theme
  :ensure t
  :config
  ;; Disable all themes and load the Tomorrow Night Deep Blue theme
  (mapc #'disable-theme custom-enabled-themes)
  (load-theme 'tomorrow-night-deepblue t))
```

## What are the differences between Tomorrow Night Blue and Deepblue themes?

The main differences lie in the background and a large number of additional faces, which enable support for many more modern Emacs packages. Currently, Tomorrow Night Deepblue supports over 1,170 faces (compared to 333 in the original version), featuring a background color reminiscent of classic editors. The author plans to make further changes to support even more faces. Contributions are welcome!

The background is also different. Here is the background color of the Tomorrow Night Deepblue:

![](https://raw.githubusercontent.com/jamescherti/tomorrow-night-deepblue-theme.el/master/.background-tomorrow-night-deepblue.png)

And this background color or the Tomorrow Night Blue, the previous version upon which this theme is based:

![](https://raw.githubusercontent.com/jamescherti/tomorrow-night-deepblue-theme.el/master/.background-tomorrow-night-blue.png)

## Authors

Tomorrow Night Deepblue theme maintainer: [James Cherti](https://www.jamescherti.com/)

The tomorrow-night-deepblue theme is based on Tomorrow Night Blue by Chris Kempson, Steve Purcell, and Donald Curtis.

## Links
- [tomorrow-night-deepblue-theme.el @GitHub](https://github.com/jamescherti/tomorrow-night-deepblue-theme.el)
- [tomorrow-night-deepblue-theme.el @melpa.org](https://melpa.org/#/tomorrow-night-deepblue-theme)
- [Announcement in James Cherti's website about the Tomorrow Night Deepblue Emacs theme](https://www.jamescherti.com/emacs-tomorrow-night-deepblue-theme-a-refreshing-color-scheme-with-a-deep-blue-background/)
- [Vim version: Tomorrow Night Deepblue for the Vim editor](https://www.jamescherti.com/vim-tomorrow-night-seablue-theme-color-scheme/)

Other Emacs packages by the same author:
- [minimal-emacs.d](https://github.com/jamescherti/minimal-emacs.d): This repository hosts a minimal Emacs configuration designed to serve as a foundation for your vanilla Emacs setup and provide a solid base for an enhanced Emacs experience.
- [vim-tab-bar.el](https://github.com/jamescherti/vim-tab-bar.el): Make the Emacs tab-bar Look Like Vim’s Tab Bar.
- [outline-indent.el](https://github.com/jamescherti/outline-indent.el): An Emacs package that provides a minor mode that enables code folding and outlining based on indentation levels for various indentation-based text files, such as YAML, Python, and other indented text files.
- [easysession.el](https://github.com/jamescherti/easysession.el): Easysession is lightweight Emacs session manager that can persist and restore file editing buffers, indirect buffers/clones, Dired buffers, the tab-bar, and the Emacs frames (with or without the Emacs frames size, width, and height).
- [elispcomp](https://github.com/jamescherti/elispcomp): A command line tool that allows compiling Elisp code directly from the terminal or from a shell script. It facilitates the generation of optimized .elc (byte-compiled) and .eln (native-compiled) files.
- [Ultyas](https://github.com/jamescherti/ultyas/): A command-line tool designed to simplify the process of converting code snippets from UltiSnips to YASnippet format.
