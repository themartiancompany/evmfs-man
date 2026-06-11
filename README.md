[comment]: <> (SPDX-License-Identifier: AGPL-3.0)

[comment]: <> (----------------------------------------------------)
[comment]: <> (Copyright © 2024, 2025, 2026)
[comment]: <> (            Pellegrino Prevete)
[comment]: <> (All rights reserved)
[comment]: <> (----------------------------------------------------)

[comment]: <> (This program is free software: you can redistribute)
[comment]: <> (it and/or modify it under the terms of the)
[comment]: <> (GNU Affero General Public License as published)
[comment]: <> (by the Free Software Foundation, either version)
[comment]: <> (3 of the License.)

[comment]: <> (This program is distributed in the hope that it)
[comment]: <> (will be useful, but WITHOUT ANY WARRANTY;)
[comment]: <> (without even the implied warranty of)
[comment]: <> (MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.)
[comment]: <> (See the GNU Affero General Public License)
[comment]: <> (for more details.)

[comment]: <> (You should have received a copy of the)
[comment]: <> (GNU Affero General Public License)
[comment]: <> (with this program.)
[comment]: <> (If not, see <https://www.gnu.org/licenses/>.)

# Ethereum Virtual Machine File System (EVMFS) manuals

The [Ethereum Virtual Machine File System](
  https://github.com/themartiancompany/evmfs)
(EVMFS) manuals.

Includes manuals for the Bash and the Javascript
[`evmfs.js`](
  https://github.com/themartiancompany/evmfs.js)
client.

## Installation

The manuals in this source repo
can be installed from source using GNU Make.

```bash
make \
  install
```

The tools have been published officially on the
the uncensorable
[Ur](
  https://github.com/themartiancompany/ur)
user repository and application store as
`evmfs`.
The source code is published on the
[Ethereum Virtual Machine File System](
  https://github.com/themartiancompany/evmfs)
so it can't possibly be taken down.

To install it from there just type

```bash
ur \
  evmfs
```

A censorable HTTP Github mirror of the recipe published there,
containing a full list of the software dependencies needed to run the
tools is hosted on
[evmfs-ur](
  https://github.com/themartiancompany/evmfs-ur).
Be aware the mirror could go offline any time as Github and more
in general all HTTP resources are inherently unstable and censorable.

A package has also been released on NPM as `evm-wallet.js` and
can be installed with

```bash
npm \
  install \
    evmfs
```

## License

This manual is released by Pellegrino Prevete under the terms
of the GNU Affero General Public License version 3.
