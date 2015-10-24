This library provides Haskell bindings to
[LevelDB](https://github.com/google/leveldb)

[![Build Status](https://secure.travis-ci.org/kim/leveldb-haskell.png)](http://travis-ci.org/kim/leveldb-haskell)

## Installation

Prerequisites:

* [GHC 7.*](http://www.haskell.org/ghc)
* [Cabal](http://www.haskell.org/cabal), version 1.3 or higher
* [LevelDB](https://github.com/google/leveldb)
* Optional: [Snappy](http://code.google.com/p/snappy),
  if compression support is desired
* Optional: `autoconf`

To install the latest version from hackage:

```shell
$ cabal install leveldb-haskell
```

To install from checked-out source:

```shell
$ autoconf
$ cabal install
```

## Notes

This library is in very early stage and has seen very limited testing. Comments
and contributions are welcome.

## Bugs and Contributing

Please report issues via http://github.com/kim/leveldb-haskell/issues.<br />
Patches are best submitted as pull requests, or via email
(kim.altintop@gmail.com).

## License

BSD 3, see LICENSE file.
