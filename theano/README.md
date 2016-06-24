# Theano Introduction
This introduction to Theano was part of the Concepts and Applications to Neural Networks (CANN) course at the Institute of Cognitive Science at the University of Osnabrück in the summer term 2016.

## Theano Installation
The installation steps for UNIX and MAC can be found on the projects homepage: [theano](http://deeplearning.net/software/theano/install.html#install), for Windows take a look here: [theanoWin](http://deeplearning.net/software/theano/install_windows.html#install-windows). There are some other dependencies that have to be fullfild before starting though:

* Python 3 (Python >= 2.6 is also supported but the example provided here will use Python 3)
* Libaries
 * Numpy >= 1.7.1
 * SciPy >= 0.11
 * Blas Framework with Level 3 functionality (Theano will per default link to the Blas system that numpy uses, if you want to change that take a look at your numpy and scipy installation, for homebrew the ```--with-openblas``` flag can be added)
* nose and nose-parameterized (those are optional but will be used to test the other installation steps):
```sh
$ pip3 install nose 
$ pip3 install nose-parameterized
```

Finally Theano itself can be installed using pip as well:
```sh
$ pip3 install Theano
```
If you would like to check your installation run the first section in the IPython Notebook in this repository.

## Reference
Theano Development Team. [“Theano: A Python framework for fast computation of mathematical expressions”](http://arxiv.org/pdf/1605.02688.pdf)
