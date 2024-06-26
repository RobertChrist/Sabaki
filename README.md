# Welcome to Robert Christ's fork of Sabaki

This fork contains several new features that the parent Sabaki repository have not yet merged, and are still pending review.

- **New Feature: Game Tree Annotations Options**
  - Summary: Allows users to bookmark, hotspot, change color and leave comments on nodes in the gametree menu by right clicking.
  - Parent Repository Github Tracking Issue: https://github.com/SabakiHQ/Sabaki/issues/940  
  - Local Stand-Alone Branch Name: feature/940_SupportGameTreeOptions
  - Open PR Into Parent Repository: https://github.com/SabakiHQ/Sabaki/pull/942
 
- **New Feature: Internationalization Support for Game Tree Annotations Options**
  - Summary: This repository uses Robert Christ's fork of Sabaki's il8n repository, in order to add English, Spanish, French, and both traditional and simplified Chinese support for "Game Tree Annotations Options" feature.
  - Parent Repository Github Tracking Issue: https://github.com/SabakiHQ/Sabaki/issues/940  
  - Local Stand-Alone Branch Name: feature/940_SupportGameTreeOptions
  - Open PR Into Parent il8n Repository: https://github.com/SabakiHQ/sabaki-i18n/pull/39
  
- **New Feature: Allow Users to Edit Territory Areas in Estimation/Scoring  Mode**
  - Summary: When in score estimation mode, allows users to edit the computer estimation, and draw their own territory areas.
  - Parent Repository Github Tracking Issue: https://github.com/SabakiHQ/Sabaki/issues/939
  - Local Stand-Alone Branch Name: feature/drawTerritoryMap
  - Open PR Into Parent Repository: https://github.com/SabakiHQ/Sabaki/pull/941

- **New Feature: New Theme for Sabaki**
  - Relevant Repository: https://github.com/RobertChrist/Sabaki-Subtle-Theme
  - Local Stand-Alone Branch Name: feature/add-subtle-theme
  - Open PR Into Parent Repository: https://github.com/SabakiHQ/Sabaki/pull/955

Original Repository README below

# ![Sabaki: An elegant Go/Baduk/Weiqi board and SGF editor for a more civilized age.](./banner.png)

[![Download the latest release](https://img.shields.io/github/downloads/SabakiHQ/Sabaki/latest/total?label=download)](https://github.com/SabakiHQ/Sabaki/releases)
[![CI](https://github.com/SabakiHQ/Sabaki/workflows/CI/badge.svg?branch=master&event=push)](https://github.com/SabakiHQ/Sabaki/actions)
[![Donate](https://img.shields.io/badge/donate-paypal-blue.svg)](https://www.paypal.me/yishn/5)

## Features

- Fuzzy stone placement
- Read and save SGF games and collections, open wBaduk NGF and Tygem GIB files
- Display formatted SGF comments using a
  [subset of Markdown](https://github.com/SabakiHQ/Sabaki/blob/master/docs/guides/markdown.md)
  and annotate board positions & moves
- Personalize board appearance with
  [textures & themes](https://github.com/SabakiHQ/Sabaki/blob/master/docs/guides/theme-directory.md)
- SGF editing tools, including lines & arrows board markup
- Copy & paste variations
- Powerful undo/redo
- Fast game tree
- Score estimator & scoring tool
- Find move by move position and comment text
- [GTP engines](https://github.com/SabakiHQ/Sabaki/blob/master/docs/guides/engines.md)
  support with
  [board analysis for supported engines](https://github.com/SabakiHQ/Sabaki/blob/master/docs/guides/engine-analysis-integration.md)
- Guess mode
- Autoplay games

![Screenshot](screenshot.png)

## Documentation

For more information visit the
[documentation](https://github.com/SabakiHQ/Sabaki/blob/master/docs/README.md).
You're welcome to
[contribute](https://github.com/SabakiHQ/Sabaki/blob/master/CONTRIBUTING.md) to
this project.

## Building & Tests

See
[Building & Tests](https://github.com/SabakiHQ/Sabaki/blob/master/docs/guides/building-tests.md)
in the documentation.

## License

This project is licensed under the
[MIT license](https://github.com/SabakiHQ/Sabaki/blob/master/LICENSE.md).

## Donators

A big thank you to these lovely people:

- Eric Wainwright
- Michael Noll
- John Hager
- Azim Palmer
- Nicolas Puyaubreau
- Hans Christian Poerschke
- David Göbel
- Dominik Olszewski
- Brian Weaver
- Philippe Fanaro
- James Tudor
- Frank Orben
- Dekun Song
- Dimitri Rusin
- Andrew Thieman
- Adrian Petrescu
- Karlheinz Agsteiner
- Petr Růžička
- Sergio Villegas
- Jake Pivnik

## Related

- [Shudan](https://github.com/SabakiHQ/Shudan) - A highly customizable,
  low-level Preact Goban component.
- [boardmatcher](https://github.com/SabakiHQ/boardmatcher) - Finds patterns &
  shapes in Go board arrangements and names moves.
- [deadstones](https://github.com/SabakiHQ/deadstones) - Simple Monte Carlo
  functions to determine dead stones.
- [go-board](https://github.com/SabakiHQ/go-board) - A Go board data type.
- [gtp](https://github.com/SabakiHQ/gtp) - A Node.js module for handling GTP
  engines.
- [immutable-gametree](https://github.com/SabakiHQ/immutable-gametree) - An
  immutable game tree data type.
- [influence](https://github.com/SabakiHQ/influence) - Simple heuristics for
  estimating influence maps on Go positions.
- [sgf](https://github.com/SabakiHQ/sgf) - A library for parsing and creating
  SGF files.
