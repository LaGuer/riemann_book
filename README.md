[![Build Status](https://travis-ci.org/clawpack/riemann_book.svg?branch=master)](https://travis-ci.org/clawpack/riemann_book)
[![codecov](https://codecov.io/gh/LaGuer/riemann_book/branch/master/graph/badge.svg)](https://codecov.io/gh/LaGuer/Jupyt-Nb)
[![Coverage Status](https://coveralls.io/repos/github/LaGuer/riemann_book/badge.svg?branch=master)](https://coveralls.io/github/LaGuer/Jupyt-Nb?branch=master)
[![Travis](https://travis-ci.org/LaGuer/riemann_book.svg?branch=master)](https://travis-ci.org/LaGuer/riemann_book)
[![Build status](https://ci.appveyor.com/api/projects/status/3s7i0w7gw1iocaq1?svg=true)](https://ci.appveyor.com/project/LaGuer/riemann_book)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/LaGuer/riemann_book/master)
[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/LaGuer/riemann_book/blob/master/.ipynb)


# Riemann Problems and Jupyter Solutions

#### by David I. Ketcheson, Randall J. LeVeque, and Mauricio del Razo Sarmina

This repository contains work on a book in progress (nearly complete) to illustrate Riemann
solutions and approximate Riemann solvers in Jupyter notebooks.

Contributors: @ketch, @rjleveque, and @maojrs.

## View static webpages

The notebooks are saved in Github with the output stripped out.  You can view
the html rendered notebooks with output intact [on this
webpage](http://www.clawpack.org/riemann_book/index.html).  These are static
views (no execution or interactive widgets), but some notebooks include
animations that will play.  *These may not be up to date with the versions in
this repository during the development phase of this project.*

## Installation
To install the dependencies for the book, see
https://github.com/clawpack/riemann_book/wiki/Installation.  Then clone this
repository to get all the notebooks.  A table of contents and suggested order
for reading the notebooks is given in `Index.ipynb`.

## Docker

Rather than installing all the dependencies, if you have
[Docker](https://www.docker.com/) installed you can use the `Dockerfile` in
this repository.  See `Docker.md` for instructions.

*[Add instructions for Dockerhub]*

## Execute in the cloud

### Windows Azure

Rather than installing software, you can execute the notebooks on the cloud
using the [Microsoft Azure Notebooks](https://notebooks.azure.com) cloud
service:  Create a free account and then clone the [riemann_book
library](https://notebooks.azure.com/rjleveque/libraries/riemann-book).
*These may not be up to date with the versions in this repository during the
development phase of this project.*

### Binder

This is still under development using the latest version of
[binder](https://beta.mybinder.org/).  You can try it out for these notebooks
at this link: https://beta.mybinder.org/v2/gh/clawpack/riemann_book/master

This should start up a notebook server on a
[Jupyterhub](https://jupyterhub.readthedocs.io/en/latest/) that lets you
execute all the notebooks with no installation required.
