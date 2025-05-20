# Developer Tools - Pythonic functional programming

Tools for iterables and iterators.

- **Repositories**
  - [dtools.iterables][1] project on *PyPI*
  - [Source code][2] on *GitHub*
- Detailed documentation for dtools.fp
  - [Detailed API documentation][3] on *GH-Pages*

This project is part of the [Developer Tools for Python][4] **dtools**
namespace project.

## Overview

Library of iterator related functions and enumerations.

- Concatenating and merging iterables
- Dropping and taking values from iterables
- Reducing and accumulating iterables
- Assumptions
  - iterables are not necessarily iterators
  - at all times iterator protocol is assumed to be followed
    - all iterators are assumed to be iterable
    - for all iterators `foo` we assume `iter(foo) is foo`

______________________________________________________________________

[1]: https://pypi.org/project/dtools.iterables/
[2]: https://github.com/grscheller/dtools-iterables/
[3]: https://grscheller.github.io/dtools-namespace-projects/iterables/
[4]: https://github.com/grscheller/dtools-namespace-projects/blob/main/README.md
