_suitable and lovely tools_

<!-- toc-begin -->
# Table of Content
* [Runtime environments](#runtime-environments)
  * [Terminals](#terminals)
  * [Shells and shell extensions](#shells-and-shell-extensions)
  * [Unix-like systems](#unix-like-systems)
    * [Emulators](#emulators)
    * [Terminal emulators](#terminal-emulators)
    * [Sudo](#sudo)
* [File managers](#file-managers)
* [Command line tools](#command-line-tools)
  * [Internet and related](#internet-and-related)
  * [Clipboard processing](#clipboard-processing)
  * [Backup tools](#backup-tools)
  * [Converters](#converters)
    * [Pandoc and friends](#pandoc-and-friends)
    * [PDF converters](#pdf-converters)
    * [RTF converters](#rtf-converters)
    * [JSON, YAML](#json-yaml)
    * [AsciiDoctor and friends](#asciidoctor-and-friends)
    * [Code converters (decompilers)](#code-converters-decompilers)
    * [Others](#others)
* [Viewers, editors and converters](#viewers-editors-and-converters)
  * [Alternatives for Office and other MS applications](#alternatives-for-office-and-other-ms-applications)
  * [Media](#media)
    * [Pictures](#pictures)
    * [Audio](#audio)
    * [Video](#video)
  * [Text](#text)
    * [Viewers](#viewers)
    * [Editors](#editors)
    * [Comparison and merging](#comparison-and-merging)
* [What is this and How to...](#what-is-this-and-how-to)
<!-- toc-end -->

# Runtime environments

## Terminals

Customizable Windows terminals with tabs, hotkeys and more

* ConEmu https://github.com/Maximus5/ConEmu
* ConsoleZ https://github.com/cbucher/console

## Shells and shell extensions

* Clink (by Martin Ridgers) https://github.com/mridgers/clink
* Clink (by Chris Antos) https://github.com/chrisant996/clink

## Unix-like systems

### Emulators

* Cygwin https://cygwin.com
* MSYS2 https://www.msys2.org/wiki/MSYS2-installation/
* BusyBox https://github.com/rmyorston/busybox-w32

### Terminal emulators

A Windows software packages providing an interface similar to a Unix pty-master for communicating with Windows console programs.

* winpty https://github.com/rprichard/winpty
* mintty https://github.com/mintty/mintty

### Sudo

A Sudo for Windows

* https://github.com/gerardog/gsudo

# File managers

* Far Manager https://farmanager.com/download.php
* Explorer++ https://github.com/derceg/explorerplusplus

# Command line tools

## Internet and related

* cURL https://curl.se/windows/

## Clipboard processing

* NirCmd https://www.nirsoft.net/utils/nircmd.html
* Outwit (winclip, etc) https://www.spinellis.gr/sw/outwit/

## Backup tools

* nnBackup https://web.archive.org/web/20150401170226/http://nncron.ru/forums/viewtopic.php?f=11&t=11442

## Converters

### Pandoc and friends

* Pandoc https://github.com/jgm/pandoc
* wkhtmltopdf https://wkhtmltopdf.org/downloads.html

### PDF converters

* PDF converters https://blog.alivate.com.au/poppler-windows/
* PDF converters https://www.xpdfreader.com/download.html

### RTF converters

* RTF to HTML converter https://github.com/lvu/rtf2html

### JSON, YAML

* json2yaml https://github.com/bronze1man/json2yaml
* yaml2json https://github.com/bronze1man/yaml2json
* jq https://github.com/stedolan/jq
* yq https://github.com/mikefarah/yq

### AsciiDoctor and friends

* AsciiDoctorJ https://docs.asciidoctor.org/asciidoctorj/latest/distribution/
* docToolchain https://github.com/docToolchain/docToolchain

Open Document Text Backends for Asciidoctor

* https://github.com/gregturn/asciidoctor-packt
* https://github.com/kubamarchwicki/asciidoctor-fodt

### Code converters (decompilers)

* Java https://github.com/leibnitz27/cfr
* Java https://github.com/intoolswetrust/jd-cli

### Others

* Online book creator https://github.com/rust-lang/mdBook

# Viewers, editors and converters

## Alternatives for Office and other MS applications

* LibreOffice https://www.libreoffice.org/
* OnlyOffice https://personal.onlyoffice.com/
* Diagrams (draw.io desktop) https://github.com/jgraph/drawio-desktop

## Media

### Pictures

* FastStone Image Viewer https://www.faststone.org/FSIVDownload.htm

### Audio

* foobar2000 https://www.foobar2000.org/download

### Video

* Media Player Classic - Home Cinema (MPC-HC) https://github.com/clsid2/mpc-hc
* VLC media player - https://www.videolan.org/vlc/download-windows.html

## Text

### Viewers

* STDU Viewer http://www.stdutility.com/stduviewer.html
* Sumatra PDF reader https://www.sumatrapdfreader.org/download-free-pdf-viewer
* WinDjView https://windjview.sourceforge.io/

### Editors

* Notepad++ https://github.com/notepad-plus-plus/notepad-plus-plus
* Notepad3 https://github.com/rizonesoft/Notepad3
* Textadept https://github.com/orbitalquark/textadept
* BowPad https://github.com/stefankueng/BowPad

### Comparison and merging

* WinMerge https://github.com/WinMerge/winmerge

# What is this and How to...

This document is the permanently moderated collection of scripts, tools and applications I use, would like to use or something I probably try to use.

I edit it time to time and update passing it through the filter as follows:

```
git-md-toc -ut -- README.md
```

* `git-md-toc` - the Perl script for detecting/creating/updating the Table of Content. It is hosted at https://github.com/ildar-shaimordanov/git-markdown-toc.
