# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/) 
and this project adheres to [Semantic Versioning](http://semver.org/).

## [0.3.1 "Git With It"] - 2017-03-11

This is a more secrative release. It really only exists because I made the error
of including the "lumped" `spirit-zones.rpg` instead of using
[unlump](https://rpg.hamsterrepublic.com/ohrrpgce/UNLUMP) to create
`spirit-zones.rpgdir`. The repo grew to a size of ~200mb really quickly because
OHRRPGCE stores all its data in one `.rpg` file, and even if you make a small
edit it changes this binary file and git just stores a new version every commit.
`unlumping` solves this.

So now we get to enjoy a smaller git repo! Hooray!

In addition, I was in the middle of working on stuff, so there are changes to
the game as well!

To see older git history, including older changelog, see:
https://github.com/SlimeMaid/spirit-zones-archive

### Added

  * Animated slime tube tiles
  * Tube tiles
  * Animated tube star contents
  * Fence tiles
  * Secret zone/map "lamp path" which is a boardwalk, very stylized scene,
    including a paralax script of sorts
  * New song by emamouse, "rainbow crayons," used for god's train trial

### Changed

  * `.rpg` file `unlumped` into `.rpgdir`
  * Hallway sokoban puzzle
  * Hidden wall appearance
  * Existing hallway maps to be more interesting, detailed.
  * Flashlight overlay, it's bigger now and just... better

### Deleted

  * `spirit-zones.rpg` because now using unlumped `spirit-zones.rpgdir`
