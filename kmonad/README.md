
KMonad configurations for Colemak-DH with Extend
================================================

KMonad is a program which allows you to customize the functionality of almost any keyboard by manipulating the raw input from the keyboard device. It allows remappings, layers and other advanced functionality. Because it's cross platform, it allows users to have a similar configuration on Windows, Linux and Mac operating systems.

See the [KMonad Project](https://github.com/david-janssen/kmonad) for instructions on how to install and set it up.

In this folder are _KMonad_ configuration files for the [Colemak-DH](https://colemakmods.github.io/mod-dh/) layout. Both ANSI and ISO keyboards are supported, they are similar except the mapping for Z, which occupies the ISO key where available. To use these files, you will need to ensure KMonad is correctly installed and configured to listen to the input events of your specific keyboard. Please read the documentation on the KMonad project.

Also included here is an [Extend layer](https://colemakmods.github.io/ergonomic-mods/extend.html) which is activated via the CapsLock key. The Extend layer is similar to [DreymaR's original](https://forum.colemak.com/topic/2014-extend-extra-extreme/), but with some modifications.

There is also a symbols layer allowing you to type common characters such as brackets using more convenient home-row keys, plus a numeric keypad on the right hand. This symbols layer is not enabled by default. To enable it on the AltGr key for example, replace "altgr" with "@sym" in the main output layer.
