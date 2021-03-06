# Easymotion Plus

> Jump to any character with a speed of light ⚡️

* * *

**Note:** this package is a partial rewrite of the great [easy-motion package](https://github.com/adrian-budau/easy-motion) from Adrian Budau.

The original package seems dead and, with the deprecation of the atom API pre-1.0, it's sad that we can't use easy-motion in atom anymore. So, i rewrite the package, waiting for news from Adrian.

* * *

Check out that repository to better understand what this plugin does.

## Modes

By default the characters used for markers are **ABC....Z**. You can replace this if you want, also from settings.

### Jump to words

**Command:** `easymotion-plus:words`  
Jump to words.

<img src="./caps/mode-words.gif" styles="text-align:center;">

#### Select to words

**Command:** `easymotion-plus:words-select`  
Select from current cursor position to word.

### Jump to letter

**Command:** `easymotion-plus:letter`  
Jump to given letter.

<img src="./caps/mode-letter.gif" styles="text-align:center;">

#### Select to letter

**Command:** `easymotion-plus:letter-select`  
Select from current cursor position to given letter.

### Jump to words starting by letter

**Command:** `easymotion-plus:words-starting`  
Jump to words starting by given letter.

<img src="./caps/mode-words-starting.gif" styles="text-align:center;">

#### Select to words starting by letter

**Command:** `easymotion-plus:words-starting-select`  
Select from current cursor position to words starting by given letter.

## Keybindings

With the success of Atom, it's really difficult to choose keybindings that will not enter in conflict whit anyone else's packages, so I have removed the default keystrokes and let the keymap empty to let you set your own keybindings.
