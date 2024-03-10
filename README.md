# Minecraft TranslateKey Pack Generator
This is the core script to generate a language file from the built-in one in Minecraft client JARs.

This script outputs values in MediaWiki "qqx" format.

## Prerequisites
* Linux
* Perl
  * Module `JSON` (for debian, in package `libjson-perl`)

## Usage
`./generate < <ORIGINAL_LANG_FILE> > <TARGET_LANG_FILE>`
* `<ORIGINAL_LANG_FILE>`: the language file from Minecraft client JARs, usually `asset/minecraft/lang/en_us.json`.
* `<TARGET_LANG_FILE>`: the destination for language file will output to.
