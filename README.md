_Set of lovely tools_

<!-- toc-begin -->
# Table of Content
* [Runtime environments](#runtime-environments)
  * [Terminals](#terminals)
  * [Unix-like systems](#unix-like-systems)
  * [Shells and shell extensions](#shells-and-shell-extensions)
* [File managers](#file-managers)
* [Internet and related](#internet-and-related)
* [Viewers, editors and converters](#viewers-editors-and-converters)
  * [Viewers](#viewers)
  * [Editors](#editors)
  * [Comparison and merging](#comparison-and-merging)
  * [Converters](#converters)
    * [Text converters](#text-converters)
      * [Pandoc and friends](#pandoc-and-friends)
      * [AsciiDoctor and friends](#asciidoctor-and-friends)
      * [PDF converters](#pdf-converters)
      * [Others](#others)
    * [Code converters (decompilers)](#code-converters-decompilers)
    * [Data formatters](#data-formatters)
* [What is this and How to...](#what-is-this-and-how-to)
<!-- toc-end -->

# Runtime environments

## Terminals

Customizable Windows terminals with tabs, hotkeys and more

* ConEmu https://github.com/Maximus5/ConEmu
* ConsoleZ https://github.com/cbucher/console

## Unix-like systems

* Cygwin https://cygwin.com
* MSYS2 https://www.msys2.org/wiki/MSYS2-installation/

A Windows software package providing an interface similar to a Unix pty-master for communicating with Windows console programs.

* winpty https://github.com/rprichard/winpty

WIN32 native port of BusyBox

* BusyBox https://github.com/rmyorston/busybox-w32

## Shells and shell extensions

* Clink (by Martin Ridgers) https://github.com/mridgers/clink
* Clink (by Chris Antos) https://github.com/chrisant996/clink

# File managers

* Far Manager https://farmanager.com/download.php
* Explorer++ https://github.com/derceg/explorerplusplus

# Internet and related

* cURL https://curl.se/windows/

# Viewers, editors and converters

## Viewers

* FastStone Image Viewer https://www.faststone.org/FSIVDownload.htm
* STDU Viewer http://www.stdutility.com/stduviewer.html
* Sumatra PDF reader https://www.sumatrapdfreader.org/download-free-pdf-viewer

## Editors

* Notepad++ https://github.com/notepad-plus-plus/notepad-plus-plus
* Notepad3 https://github.com/rizonesoft/Notepad3
* Textadept https://github.com/orbitalquark/textadept
* BowPad https://github.com/stefankueng/BowPad

## Comparison and merging

* WinMerge https://github.com/WinMerge/winmerge

## Converters

### Text converters

#### Pandoc and friends

* Pandoc https://github.com/jgm/pandoc
* wkhtmltopdf https://wkhtmltopdf.org/downloads.html

#### AsciiDoctor and friends

* AsciiDoctorJ https://docs.asciidoctor.org/asciidoctorj/latest/distribution/
* docToolchain https://github.com/docToolchain/docToolchain

Open Document Text Backends for Asciidoctor

* https://github.com/gregturn/asciidoctor-packt
* https://github.com/kubamarchwicki/asciidoctor-fodt

#### PDF converters

* PDF converters https://blog.alivate.com.au/poppler-windows/
* PDF converters https://www.xpdfreader.com/download.html

#### Others

* Online book creator https://github.com/rust-lang/mdBook

### Code converters (decompilers)

* Java https://github.com/leibnitz27/cfr
* Java https://github.com/intoolswetrust/jd-cli

### Data formatters

* json2yaml https://github.com/bronze1man/json2yaml
* yaml2json https://github.com/bronze1man/yaml2json
* jq https://github.com/stedolan/jq
* yq https://github.com/mikefarah/yq

# What is this and How to...

This document is the permanently moderated collection of scripts, tools and applications I use, would like to use or something I probably try to use.

I edit it time to time and update passing it through the filter as follows:

```
git-md-toc -ut -- README.md
```

* `git-md-toc` - the Perl script for detecting/creating/updating the Table of Content. It is hosted at https://github.com/ildar-shaimordanov/git-markdown-toc.
