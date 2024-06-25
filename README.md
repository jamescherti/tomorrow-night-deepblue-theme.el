# tomorrow-night-deepblue-theme.el (Emacs theme)
[![MELPA](https://melpa.org/packages/tomorrow-night-deepblue-theme-badge.svg)](https://melpa.org/#/tomorrow-night-deepblue-theme)

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
```
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
- [tomorrow-night-deepblue-theme.el @melpa.org](https://melpa.org/#/tomorrow-night-deepblue-theme)
- [tomorrow-night-deepblue-theme.el @GitHub](https://github.com/jamescherti/tomorrow-night-deepblue-theme.el)
- [Announcement in James Cherti's website about the Tomorrow Night Deepblue Emacs theme](https://www.jamescherti.com/emacs-tomorrow-night-deepblue-theme-a-refreshing-color-scheme-with-a-deep-blue-background/)
- [Vim version: Tomorrow Night Deepblue for the Vim editor](https://www.jamescherti.com/vim-tomorrow-night-seablue-theme-color-scheme/)
- [vim-tab-bar.el](https://github.com/jamescherti/vim-tab-bar.el): Make Emacs tab-bar look like Vim's tab bar.
