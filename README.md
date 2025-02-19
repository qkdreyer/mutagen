# Mutagen

Mutagen is a new kind of remote development tool that enables your existing
local tools to work with code in remote environments like cloud servers and
containers. It does this by providing high-performance real-time
[file synchronization](https://mutagen.io/documentation/synchronization/) and
flexible [network forwarding](https://mutagen.io/documentation/forwarding/).
Support is currently implemented for synchronization and forwarding between
[local systems](https://mutagen.io/documentation/transports/local/),
[SSH-accessible locations](https://mutagen.io/documentation/transports/ssh/),
and [Docker containers](https://mutagen.io/documentation/transports/docker/),
with more on the way!


## Getting started

The best way to understand Mutagen and its features is to read the
[Overview](https://mutagen.io/documentation/introduction/) and
[Getting started](https://mutagen.io/documentation/introduction/getting-started/)
guides. You can find information about all of Mutagen's features in the
[documentation](https://mutagen.io/documentation/).


## Installation

You can find
[installation instructions](https://mutagen.io/documentation/introduction/installation/)
in the [Mutagen documentation](https://mutagen.io/documentation/).


## Community

Mutagen's community chat is the place to go for discussion, questions, and
ideas:

[![Join the community on Spectrum](https://withspectrum.github.io/badge/badge.svg)](https://spectrum.chat/mutagen)

For updates about the project and its releases, you can:

- Subscribe to the
  [mutagen-announce](https://groups.google.com/forum/#!forum/mutagen-announce)
  mailing list
- Follow Mutagen [on Twitter](https://twitter.com/mutagen_io)


## Status

Mutagen is built and tested on Windows, macOS, and Linux, and it's available for
[many more platforms](https://github.com/mutagen-io/mutagen/releases/latest).

| Windows                           | macOS/Linux                                   | Code coverage                           | Report card                         | License                                   |
| :-------------------------------: | :-------------------------------------------: | :-------------------------------------: | :---------------------------------: | :---------------------------------------: |
| [![Windows][win-badge]][win-link] | [![macOS/Linux][mac-lin-badge]][mac-lin-link] | [![Code coverage][cov-badge]][cov-link] | [![Report card][rc-badge]][rc-link] | [![License][license-badge]][license-link] |

[win-badge]: https://ci.appveyor.com/api/projects/status/mr8rmxl5hbxgyged/branch/master?svg=true "Windows build status"
[win-link]:  https://ci.appveyor.com/project/havoc-io/mutagen-87cwp/branch/master "Windows build status"
[mac-lin-badge]: https://travis-ci.org/mutagen-io/mutagen.svg?branch=master "macOS/Linux build status"
[mac-lin-link]:  https://travis-ci.org/mutagen-io/mutagen "macOS/Linux build status"
[cov-badge]: https://codecov.io/gh/mutagen-io/mutagen/branch/master/graph/badge.svg "Code coverage status"
[cov-link]: https://codecov.io/gh/mutagen-io/mutagen/tree/master/pkg "Code coverage status"
[rc-badge]: https://goreportcard.com/badge/github.com/mutagen-io/mutagen "Report card status"
[rc-link]: https://goreportcard.com/report/github.com/mutagen-io/mutagen "Report card status"
[license-badge]: https://img.shields.io/github/license/mutagen-io/mutagen.svg "MIT licensed"
[license-link]: LICENSE "MIT licensed"


## Contributing

If you'd like to contribute to Mutagen, please see the
[contribution documentation](CONTRIBUTING.md).


## External projects

Users have built a number of cool projects to extend and integrate Mutagen into
their workflows:

- [**Mutagen Helper**](https://github.com/gfi-centre-ouest/mutagen-helper) is a
  tool that makes the orchestration of synchronization sessions even easier by
  letting you define sessions with configuration files that live inside your
  codebase. Thanks to [**@Toilal**](https://github.com/Toilal)!
- [**docker-magento-mutagen**](https://github.com/mage2click/docker-magento-mutagen)
  (from [Mage2click](https://mage2.click/)) is a Docker-based development
  environment for Magento that uses Mutagen for file synchronization. Thanks to
  [**@u-maxx**](https://github.com/u-maxx) and
  [**@shkoliar**](https://github.com/shkoliar).


## Security

Mutagen takes security very seriously. If you believe you have found a security
issue with Mutagen, please practice responsible disclosure practices and send an
email directly to [security@mutagen.io](mailto:security@mutagen.io) instead of
opening a GitHub issue. For more information, please see the
[security documentation](SECURITY.md).


## Versioning and support

Mutagen uses [semantic versioning](https://semver.org/) for tracking releases.
Each minor release series is supported for the release cycle of the next minor
release series or for 3 months, whichever is longer.

The builds for each minor release series are pinned to the same Go minor release
and dependency versions used for developing that series (though patch releases
will be incorporated if they contain security fixes).

We reserve the right to break or bend these rules if necessary for the sake of
security, e.g. discontinuing support for a minor release to which a security fix
cannot be backported or upgrading Go minor versions for a release series to
incorporate important security fixes.


## Building

Please see the [build instructions](BUILDING.md).
