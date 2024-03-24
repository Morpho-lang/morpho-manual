![Morpho](src/Figures/morphologosmall.png#gh-light-mode-only)![Morpho](src/Figures/morphologosmall-white.png#gh-dark-mode-only)

# Morpho-manual

This repository contains the current version of the manual for the [morpho](https://github.com/Morpho-lang/morpho) language. Please see the main repository for more information and installation instructions.

The most recent version of the manual is available as a PDF document in this repository's root folder.

## Contributions welcome

Suggestions to improve the manual are welcome. Please feel free to report errors, suggest additional topics or identify user needs using the Issue tracker in this repository.

Contributions to the manual are also welcome. Please follow the same style as used in the manual and submit changes via a pull request.

## Building the manual from source

The source LyX file is included in the `src` folder, and requires some subsidiary files. To build these, `cd` to `src` and run the script: 

    python3 build.py

This script does two things:

1. All figures are generated from a morpho program, and rendered with `povray`.

2. The reference manual is automatically build from `help` files included in the morpho-libmorpho repository. (Note that the build script assumes that the morpho-libmorpho repository has been cloned into the same folder as this repository).

The manual can then be built using the [LyX](http://www.lyx.org) document processor.
