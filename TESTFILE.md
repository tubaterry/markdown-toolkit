# Markdown TOC
============

Generate and update magically a table of contents based on the headlines of a parsed [markdown](http://en.wikipedia.org/wiki/Markdown) file.
(This is the old readme for now)

# test1
## test2
### test3
#### test4
##### test5
###### test6
####### test7

<!-- # test1
## test2
### test3
#### test4
##### test5
###### test6 -->

H1 Alternative
=====

H2 Alternative
-----

# Table of Contents
[[toc]]


## Usage


![Magic](https://raw.githubusercontent.com/nok/markdown-toc/master/RECORD.gif)

## Installation

```bash
apm install markdown-toc
```


## Features

- Auto linking via  anchor tags, e.g.  `# A 1` → `#a-1`
- Depth control [1-6] with `depthFrom:1` and `depthTo:6`
- Enable or disable links with `withLinks:1`
- Refresh list on save with `updateOnSave:1`
- Use ordered list (1. ..., 2. ...) with `orderedList:0`


## Contributors

Thanks to all contributors for any fix or improvement, whether small or large.

- [Giacomo Bresciani](https://github.com/brescia123)
- [Kévin Lanceplaine](https://github.com/lanceplaine)
- [Ilya Zelenin](https://github.com/wyster)
- [spjoe](https://github.com/spjoe)
- [Tom Byrer](https://github.com/tomByrer)
- [betrue12](https://github.com/betrue12)


## Questions?

Don't be shy and feel free to contact me on [Twitter](https://twitter.com/darius_morawiec).


## License

The package is Open Source Software released under the [MIT](LICENSE.md) license.
