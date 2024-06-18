# tomorrow-night-deepblue-theme.el (Emacs theme)

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

# Installation

## Install using straight (preferred)

To install the `tomorrow-night-deepblue-theme` using `straight.el`, you need to add the following code to your Emacs configuration:
```
(use-package tomorrow-night-deepblue-theme
  :straight (tomorrow-night-deepblue-theme
             :type git
             :host github
             :repo "jamescherti/tomorrow-night-deepblue-theme.el")
  :config
  ;; Disable all themes and load the Tomorrow Night Deep Blue theme
  (mapc #'disable-theme custom-enabled-themes)
  (load-theme 'tomorrow-night-deepblue t))
```

## What are the differences between Tomorrow Night Blue and Deepblue themes?

The main differences lie in the large number of additional faces and the background color, which enable support for many more modern Emacs packages. Currently, Tomorrow Night Deepblue supports over 1170 faces (compared to 333 in the original version), with a background color reminiscent of classic editors.

The author plans to make further changes to support even more faces. Contributions are welcome!

## Authors

Tomorrow Night Deepblue theme maintainer: [James Cherti](https://www.jamescherti.com/)

The tomorrow-night-deepblue theme is based on Tomorrow Night Blue by Chris Kempson, Steve Purcell, and Donald Curtis.

## Links
- [GitHub: Tomorrow Night Deepblue Emacs theme](https://github.com/jamescherti/tomorrow-night-deepblue-theme.el)
- [Announcement in James Cherti's website about the Tomorrow Night Deepblue Emacs theme](https://www.jamescherti.com/emacs-tomorrow-night-deepblue-theme-a-refreshing-color-scheme-with-a-deep-blue-background/)
- [Vim version: Tomorrow Night Deepblue for the Vim editor](https://www.jamescherti.com/vim-tomorrow-night-seablue-theme-color-scheme/)
- [vim-tab-bar.el](https://github.com/jamescherti/vim-tab-bar.el): Make Emacs tab-bar look like Vim's tab bar.
