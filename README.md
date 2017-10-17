# Julia implementation of Lempel-Ziv Complexity

This repository contains a small, simple and efficient implementation of the [Lempel-Ziv complexity](https://en.wikipedia.org/wiki/LempelZiv.jl) algorithm.

## Examples
### Simple usage
If the [`LempelZiv.jl`](src/LempelZiv.jl) file is accessible in your PATH or in Python's path:

```python
>>> from lempel_ziv_complexity import lempel_ziv_complexity
>>> s = '1001111011000010'
>>> lempel_ziv_complexity(s)  # 1 / 0 / 01 / 1110 / 1100 / 0010
6
```

### Documentation
See [this file](https://naereen.github.io/LempelZiv.jl/doc/index.html).

> If you are really interested about the details of how the algorithm works, please see [this GIF screencast](https://github.com/Naereen/LempelZiv.jl/issues/2#issuecomment-312421968) from [PythonTutor.com](http://pythontutor.com/visualize.html#mode=edit).

## Demo on a [Jupyter notebook](https://www.Jupyter.org/)
See this notebook: [on nbviewever](https://nbviewer.jupyter.org/github/Naereen/LempelZiv.jl/blob/master/Short_study_of_the_LempelZiv.jl.ipynb), which also shows the [Python implementations](https://github.com/Naereen/Lempel-Ziv_Complexity).

----

## Install and build
### Manually ?
Easy!

Clone this repository, go in the folder, test, and if it works, install it.

```bash
$ cd /tmp/
$ git clone https://GitHub.com/Naereen/LempelZiv.jl
$ cd LempelZiv.jl/
$ julia LempelZiv.jl test     # should pass
$ julia
julia> Pkg.install("LempelZiv.jl")  # should work
```

## With FIXME ?
This project is hosted on [the FIXME package repository](https://FIXME/LempelZiv.jl/).

```bash
sudo FIXME install LempelZiv
# test it
python -c "from lempel_ziv_complexity import lempel_ziv_complexity; print(lempel_ziv_complexity('1001111011000010') == 6)"  # test
```

----

## Python implementation ?

The Python :snake: package is published here: [Naereen/Lempel-Ziv_Complexity](https://github.com/Naereen/Lempel-Ziv_Complexity),
and see [here for its documentation](https://naereen.github.io/Lempel-Ziv_Complexity/doc/index.html).

[![lempel_ziv_complexity in pypi](https://img.shields.io/pypi/v/lempel_ziv_complexity.svg)](https://pypi.org/project/LempelZiv.jl/)
![PyPI implementation](https://img.shields.io/pypi/implementation/lempel_ziv_complexity.svg)
![PyPI pyversions](https://img.shields.io/pypi/pyversions/lempel_ziv_complexity.svg)

----

## About
### Language?
[Julia](https://www.julialang.org/) version 0.5 at least.

### :scroll: License ? [![GitHub license](https://img.shields.io/github/license/Naereen/LempelZiv.jl.svg)](https://github.com/Naereen/badges/blob/master/LICENSE)
[MIT Licensed](https://lbesson.mit-license.org/) (file [LICENSE](LICENSE)).
© [Lilian Besson](https://GitHub.com/Naereen), 2017.

[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/LempelZiv.jl/graphs/commit-activity)
[![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](https://GitHub.com/Naereen/ama)
[![Analytics](https://ga-beacon.appspot.com/UA-38514290-17/github.com/Naereen/LempelZiv.jl/README.md?pixel)](https://GitHub.com/Naereen/LempelZiv.jl/)

[![ForTheBadge uses-badges](http://ForTheBadge.com/images/badges/uses-badges.svg)](http://ForTheBadge.com)
[![ForTheBadge uses-git](http://ForTheBadge.com/images/badges/uses-git.svg)](https://GitHub.com/)

[![forthebadge made-with-julia](http://ForTheBadge.com/images/badges/made-with-julia.svg)](https://www.julialang.org/)
[![ForTheBadge built-with-science](http://ForTheBadge.com/images/badges/built-with-science.svg)](https://GitHub.com/Naereen/)