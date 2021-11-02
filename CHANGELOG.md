# Change Log

All notable changes to the "pyKv-snippet" extension will be documented in this file.
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

## [1.0.9] - 2021-11-02

### Changed

- about orientation (one of keywords of BoxLayout)
  - you can select "vertical" or "horizontal".
  - thus the snippets "vertical" and "horizontal" have removed.


## [1.0.8] - 2021-03-07

### Changed

- Most all snippets for keyword argument in python is ended with "="
  - While "onpress" -> "on_press" before, "onpress" -> "on_press=${1:callback}" now.

- changed some prefix in KvLang
  - pad -> padding
  - fontsize -> font_size
- changed some snippets
  - from "size_hint" -> "size_hint: " to "size_hint" -> "size_hint: $1, $2"
  - from "pos_hint" -> "pos_hint: {\$1, \$2}\$0" to "pos_hint" -> "pos_hint: {'\${1|x,right,center_x|}': \$2, '\${3|y,top,center_y|}': \$4}\$0"
    - in order to allow you to write KvLang comfortably.

## [1.0.7] - 2020-10-01
### Added

- New import snippets
  - kvbuilder -> from kivy.lang.builder import Builder
- New keyword snippet in kivy
  - size_hint -> size_hint: 
  - pos_hint -> pos_hint: {$1, $2}

### Changed

- changed some prefix in python
  - poshint -> pos_hint
  - sizehint -> size_hint
  - fontsize -> font_size

## [1.0.6] - 2020-8-30
### Added
- New import snippets
  - kvfactory -> from kivy.factory import Factory
- New keyword snippet
  - poshint -> pos_hint={'x':, 'y'}

## [1.0.5] - 2020-8-25
### Added
- New import snippets
  - kvimage -> from kivy.uix.image import Image
  - kvwin -> from kivy.core.window import Window
  - kvcarousel -> from kivy.uix.carousel import Carousel

- New Kivy snippets
  - rect -> rectangle: 
  - color -> Color: 
  - color -> color: 

- Support Lang Directives (#: comments) snippets
  - #: set
  - #: import
  - #: include

## [1.0.4] - 2020-8-22
### Added
- New import snippets
  - kvconfig -> from kivy.config import Config
  - kvimport -> from kivy.$1 import $2

- New Kivy snippets
  - ontext -> on_text: 
  - ontextvalidate -> on_text_validate: 

## [1.0.3] - 2020-8-19
### Added
- New import snippets
  - kvanim -> from kivy.animation import Animation

- New snippets : some keyword argments of kivy in .py files.
  - e.g. sx -> size_hint_x mainly used in Widget().
  - and background_color, duration, opacity mainly used in Animation().
  - in additon, on_press, on_start and so on used in Widget.bind().


### Changed
- prefix changed.
  - kvstart -> kvtemplate
    - coz I often select kvstack by mistake.
- Set version 1.0.3
- rename some files in git.

## [0.0.2]

- Minor changes.

## [Unreleased]

- Initial release