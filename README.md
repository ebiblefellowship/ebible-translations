# EBible Fellowship Translations

## Overview

This repository contains various source files requiring translation such as tracts and Facebook page information, etc.  

Depending on the purpose of the source and translated files, they may be further processed into web pages and PDF's or the translated text may just be manually copied and pasted into the desired application.

## Translation Integration

This repository is linked with an account on [WebTranslateIT.com](webtranslateit.com), a web based translation management application.  This software will pick up changes to the source files and post back updates to translations when they are made.

## File Naming

Files are named with a suffix before the file extension that has the 
[ISO-639 two letter lanugage code](http://en.wikipedia.org/wiki/List_of_ISO_639-1_codes), 
e.g. `spiritual-judgment.en.yml` where "en" is the code for English.  As English (en) is configured as the source language in *WebTranslateIT*, it will save the translated files with the same naming pattern but substituting the appropriate lanugage code or locale for the respective translation, e.g. "es" for Spanish or "zh" for Chinese. 

For more information, see the [WebTranslateIT Locale Help](https://webtranslateit.com/en/docs/locale/).  Note that WebTranslateIT supports *Locale*'s which also include country or regional information appended to the language code in the event that is needed.  However, for our purposes, one translation per language has been sufficient.
