﻿WinCompose
==========

A compose key for Windows, free and opensource, created by Sam Hocevar
with the help of [dozens of contributors](https://github.com/samhocevar/wincompose/graphs/contributors).

A **compose key** allows to easily write special characters such as **é
ž à ō û ø ☺ ¤ ∅ « ♯ ⸘ Ⓚ ㊷ ♪ ♬** using short and often
very intuitive key combinations. For instance, **ö** is obtained using
<kbd>o</kbd> + <kbd>"</kbd>, and **♥** is obtained using <kbd>&lt;</kbd>
\+ <kbd>3</kbd>.

WinCompose also supports Emoji input for 😁 👻 👍 💩 🎁 🌹 🐊.

Download latest: [WinCompose 0.9.4](https://github.com/samhocevar/wincompose/releases/download/v0.9.4/WinCompose-Setup-0.9.4.exe) (December 6, 2019)
-----------------------------------

 * Installable version: [WinCompose 0.9.4 (installer)](https://github.com/samhocevar/wincompose/releases/download/v0.9.4/WinCompose-Setup-0.9.4.exe).

 * Portable version: [WinCompose 0.9.4 (portable)](https://github.com/samhocevar/wincompose/releases/download/v0.9.4/WinCompose-NoInstall-0.9.4.zip).

 * Older versions are available [in the releases section](https://github.com/samhocevar/wincompose/releases/).

**Note: the software is not digitally signed.** You can help with this by [donating to the project](http://wincompose.info/donate/).

Quick start
-----------

After installation, WinCompose should appear in the System Tray. Press and
release the <kbd>⎄ Compose</kbd> key to initiate a compose sequence (this key
defaults to <kbd>Right Alt</kbd>); the icon should change to indicate a compose
sequence is in progress.

Then type in the keys for a compose sequence, such as <kbd>A</kbd> then
<kbd>E</kbd> for **Æ**:

![Quick Launch](/web/shot1.png)

If <kbd>Right Alt</kbd> is not suitable for you, you can change it in the options.

Examples
--------

Compose rules are supposed to be intuitive. Here are some examples:

 - <kbd>⎄ Compose</kbd> <kbd>\`</kbd> <kbd>a</kbd> → **à**
 - <kbd>⎄ Compose</kbd> <kbd>'</kbd> <kbd>e</kbd> → **é**
 - <kbd>⎄ Compose</kbd> <kbd>^</kbd> <kbd>i</kbd> → **î**
 - <kbd>⎄ Compose</kbd> <kbd>~</kbd> <kbd>n</kbd> → **ñ**
 - <kbd>⎄ Compose</kbd> <kbd>/</kbd> <kbd>o</kbd> → **ø**
 - <kbd>⎄ Compose</kbd> <kbd>"</kbd> <kbd>u</kbd> → **ü**
 - <kbd>⎄ Compose</kbd> <kbd>o</kbd> <kbd>c</kbd> → **©**
 - <kbd>⎄ Compose</kbd> <kbd>+</kbd> <kbd>-</kbd> → **±**
 - <kbd>⎄ Compose</kbd> <kbd>:</kbd> <kbd>-</kbd> → **÷**
 - <kbd>⎄ Compose</kbd> <kbd>(</kbd> <kbd>7</kbd> <kbd>)</kbd> → **⑦**
 - <kbd>⎄ Compose</kbd> <kbd>C</kbd> <kbd>C</kbd> <kbd>C</kbd> <kbd>P</kbd> → **☭**
 - <kbd>⎄ Compose</kbd> <kbd>&lt;</kbd> <kbd>3</kbd> → **♥**

Emoji sequences typically start with two <kbd>⎄ Compose</kbd> hits:

 - <kbd>⎄ Compose</kbd> <kbd>⎄ Compose</kbd> <kbd>a</kbd> <kbd>n</kbd> <kbd>g</kbd> <kbd>r</kbd> <kbd>y</kbd> → 😠
 - <kbd>⎄ Compose</kbd> <kbd>⎄ Compose</kbd> <kbd>g</kbd> <kbd>r</kbd> <kbd>i</kbd> <kbd>n</kbd> <kbd>n</kbd> <kbd>i</kbd> <kbd>n</kbd> <kbd>g</kbd> → 😁
 - <kbd>⎄ Compose</kbd> <kbd>⎄ Compose</kbd> <kbd>s</kbd> <kbd>u</kbd> <kbd>s</kbd> <kbd>h</kbd> <kbd>i</kbd> → 🍣
 - <kbd>⎄ Compose</kbd> <kbd>⎄ Compose</kbd> <kbd>s</kbd> <kbd>n</kbd> <kbd>a</kbd> <kbd>k</kbd> <kbd>e</kbd> → 🐍

A special Unicode input mode can be activated in the options and lets
the user type in any Unicode character:

 - <kbd>⎄ Compose</kbd> <kbd>u</kbd> <kbd>5</kbd> <kbd>8</kbd> <kbd>d</kbd> <kbd>Enter</kbd> → ֍ (U+058D Right-Facing Armenian Eternity Sign)
 - <kbd>⎄ Compose</kbd> <kbd>u</kbd> <kbd>2</kbd> <kbd>3</kbd> <kbd>f</kbd> <kbd>0</kbd> <kbd>Enter</kbd> → ⏰ (U+23F0 Alarm Clock)

The full list of rules can be found by clicking on the WinCompose system tray
icon or using the “Show Sequences…” menu entry:

![Sequence List](/web/shot2.png)

The window allows you to filter the sequences being listed.

Features
--------

WinCompose supports the standard Compose file format. It provides more than
1700 compose rules from the [Xorg](http://www.x.org/wiki/) project and the
[dotXCompose](https://github.com/kragen/xcompose) project. You can add custom
rules by creating a file named `.XCompose` or `.XCompose.txt` in your
`%USERPROFILE%` directory. WinCompose must be restarted for changes to take
effect.

WinCompose supports rules of more than 2 characters such as <kbd>⎄ Compose</kbd>
<kbd>(</kbd> <kbd>3</kbd> <kbd>)</kbd> for **③**.

WinCompose supports early exits. For instance, <kbd>⎄ Compose</kbd> <kbd>q</kbd> will
immediately type **q** because there is currently no rule starting with <kbd>q</kbd>.

As of now, WinCompose is almost fully translated to Belarusian, Chinese,
Czech, Dutch, Estonian, French, German, Greek, Italian, Japanese, Lithuanian,
Norwegian, Polish, Portuguese, Brazilian Portuguese, Russian, Sardinian,
Spanish, and Swedish. It is partially translated to Danish, Esperanto, Finnish,
Hungarian, Indonesian, Irish, Romanian, Serbian, Slovak, and Slovenian. You
can help us translate it to more languages using the Weblate project:

<a href="https://hosted.weblate.org/engage/wincompose/?utm_source=widget"><img src="https://hosted.weblate.org/widgets/wincompose-287x66-white.png" alt="Translation status" /></a>

Sam wrote WinCompose because none of the alternatives (FreeCompose,
CKFW, AllChars or Unichars) were found to be satisfying.

Bugs and Improvements
---------------------

Please report bugs or suggest improvements to Sam Hocevar <sam@hocevar.net>
or to the [GitHub issue tracker](https://github.com/samhocevar/wincompose/issues).
