# Panini Keyboard

[ISO15919 standard](https://en.wikipedia.org/wiki/ISO_15919) defines transliteration scheme for converting Brahmic script characters to Latin characters.
However, the standard QWERTY keyboard does not support characters in this standard.

The keyboard released in this repository is meant to fill that gap. It is created using Microsoft Keyboard Layout creator tool (https://www.microsoft.com/en-us/download/details.aspx?id=22339)

*Note* The above tool is not officially supported on Windows 10.

Installation instructions for Windows 10
========================================
+ Download the latest zip file from [Releases](https://github.com/pikeview/Panini/releases)
+ Run the `setup.exe`. The installation requires Administrative privileges.
+ Restart the computer

Configuration instructions for Windows 10
=========================================
+ In windows search "Region" to open `Region & Language` settings in control panel
+ On the right side of the opened window, click on `Advanced Keyboard` settings
+ In the `Default input methods` drop down you should be able to find `English (India) with romanization` keyboard available.
+ Clik on `Language bar options`. Select `Advanced Key Settings` tab. Assign shortcuts such as `Left shift + Alt 1` to switch between regular keyboard and the new keyboard.

Uninstallation instructions for Windows 10
==========================================

Run the `setup.exe` and choose `Remove` option to uninstall the keyboard. Restart the computer for the changes to take effect.

Usage guide 
===========
The transliteration keys can be typed by choosing the key combination of right ALT key and the desired key.
See [ISO15919 standard](https://en.wikipedia.org/wiki/ISO_15919) for the specification.

Problems with `d` and `t`
-------------------------
The ISO standards uses the characters  `d` and `t` to represent the `द` and `त`. However, this is counter intuitive from the perspective of a native English speaker from the US or UK.
The characters `d` and `t` are phonetically close to the letters `ड` and `ट`. 
To prove this point, all one needs to do is to hear a native English speaker spell words such as "Hindu", "Damodar", "Drishti", "Tripti". 
They would utter these words as "हिंडु", "डामोडर", "ड्रिश्टि", "ट्रिप्टि ", "హిండూ", "డామోడర్ ","డ్రిష్టి" ,"ట్రిప్టి"
This is entirely different from they way Indians utters the words.

A non breaking change would be to extend the ISO standard to allow `ḏ` and `ṯ` also to map to  `द` and `त`. This keyboard includes these keys to allow such usage.

Justification for this proposal: The line below the character is a reminder about how native English speakers stretch and byte their tongues to utter the sounds of `द` and `त` in words such as "this", "thank you". 

The keyboard layout is as follows

Keys available by holding down the right `Alt` key
--------------------------------------------------
![Right Alt Keys](https://github.com/pikeview/Panini/blob/master/PaniniAltGr.jpg)

Keys available by holding down the right `Alt` key along with `Shift` key
-------------------------------------------------------------------------
![Right Alt + Shift](https://github.com/pikeview/Panini/blob/master/PaniniShftAltGr.jpg)

Regular
-------
![Regular](https://github.com/pikeview/Panini/blob/master/Panini.jpg)


Links
-----
+ ![https://www.Unicode.org](https://www.unicode.org)
+ [Unicode Character Name index](https://www.unicode.org/charts/charindex.html)
+ [Unicode combining diactrics marks](https://www.unicode.org/charts/PDF/U0300.pdf)
+ [Unicode latin extended additial characters](https://www.unicode.org/charts/PDF/U1E00.pdf)
+ [Library of Congress Romanization standard](https://www.loc.gov/catdir/cpso/roman.html)
