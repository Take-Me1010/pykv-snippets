# Change Log

All notable changes to the "pyKv-snippet" extension will be documented in this file.
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

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