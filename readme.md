<a href="https://furore.dev/propensive/escritoire"><img src="/doc/images/furore.png" style="vertical-align:middle" valign="middle"></a>&nbsp;&nbsp;<a href="https://furore.dev/propensive/escritoire">__Develop with Fury__ </a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://riot.im/app/#/room/#propensive.escritoire:matrix.org"><img src="/doc/images/riotim.png" style="vertical-arign:middle" valign="middle"></a>&nbsp;&nbsp;<a href="https://riot.im/app/#/room/#propensive.escritoire:matrix.org">__Discuss on Riot__</a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://search.maven.org/search?q=g:com.propensive%20AND%20a:escritoire_2.12"><img src="/doc/images/mavencentral.png" style="vertical-arign:middle" valign="middle"></a>&nbsp;&nbsp;<a href="https://search.maven.org/search?q=g:com.propensive%20AND%20a:escritoire_2.12">__Download from Maven Central__</a>

<img src="/doc/images/github.png" valign="middle">

[![Build](https://github.com/propensive/escritoire/workflows/Build/badge.svg)](https://github.com/propensive/escritoire/actions)

# Escritoire

_Escritoire_ is a simple library for printing tabular data in monospaced fonts, typically for use in console applications.

## Features

- prints data using Unicode box-drawing characters
- supports multiline cells
- cell contents may be left, right or centrally aligned
- compact display for tables which don't include multiline contents


## Getting Started

TBC


## Status

Escritoire is classified as __fledgling__. Propensive defines the following five stability levels for open-source projects:

- _embryonic_: for experimental or demonstrative purposes only, without guarantee of longevity
- _fledgling_: of proven utility, seeking contributions, but liable to significant redesigns
- _maturescent_: major design decisions broady settled, seeking probatory adoption and refinement of designs
- _dependable_: production-ready, subject to controlled ongoing maintenance and enhancement; tagged as version `1.0` or later
- _adamantine_: proven, reliable and production-ready, with no further breaking changes ever anticipated

## Availability

Escritoire&rsquo;s source is available on GitHub, and may be built with [Fury](https://github.com/propensive/fury) by
cloning the layer `propensive/escritoire`.
```
fury layer clone -i propensive/escritoire
```
or imported into an existing layer with,
```
fury layer import -i propensive/escritoire
```
A binary will be made available on Maven Central.

## Contributing

Contributors to Escritoire are welcome and encouraged. New contributors may like to look for issues marked
<a href="https://github.com/propensive/escritoire/labels/good%20first%20issue"><img alt="label: good first issue"
src="https://img.shields.io/badge/-good%20first%20issue-67b6d0.svg" valign="middle"></a>.

We suggest that all contributors read the [Contributing Guide](/contributing.md) to make the process of
contributing to Escritoire easier.

Please __do not__ contact project maintainers privately with questions, as other users cannot then benefit from
the answers.

## Author

Escritoire was designed and developed by [Jon Pretty](https://twitter.com/propensive), and commercial support and
training is available from [Propensive O&Uuml;](https://propensive.com/).



## License

Escritoire is copyright &copy; 2017-20 Jon Pretty & Propensive O&Uuml;, and is made available under the
[Apache 2.0 License](/license.md).
