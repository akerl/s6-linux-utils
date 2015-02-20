s6-linux-utils
=========

[![ISC Licensed](https://img.shields.io/badge/license-ISC-green.svg)](https://tldrlegal.com/license/-isc-license)

This is my package repo for [s6-linux-utils](http://www.skarnet.org/software/s6-linux-utils/), a scripting language by [Laurent Bercot](http://skarnet.org/).

The `upstream/` directory is taken directly from upstream. The rest of the repository is my packaging scripts for compiling a distributable build.

## Usage

To build a new package, update the submodule and run `make`. This launches the docker build container and builds the package.

To start a shell in the build environment for manual actions, run `make manual`.

## License

The s6-linux-utils upstream code is ISC licensed. My packaging code is MIT licensed.

