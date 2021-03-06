PyWavelets - Wavelet Transforms in Python
=========================================

PyWavelets is free and Open Source wavelet transform software for the Python_
programming language. It combines a simple high level interface with low level
C and Cython performance.

PyWavelets is very easy to use and get started with. Just install the package,
open the Python interactive shell and type:

  .. sourcecode:: python

    >>> import pywt
    >>> cA, cD = pywt.dwt([1, 2, 3, 4], 'db1')

Voilà! Computing wavelet transforms has never been so simple :)

Main features
-------------

The main features of PyWavelets are:

  * 1D, 2D and nD Forward and Inverse Discrete Wavelet Transform (DWT and IDWT)
  * 1D, 2D and nD Multilevel DWT and IDWT
  * 1D and 2D Stationary Wavelet Transform (Undecimated Wavelet Transform)
  * 1D and 2D Wavelet Packet decomposition and reconstruction
  * 1D Continuous Wavelet Transform
  * Computing Approximations of wavelet and scaling functions
  * Over 100 `built-in wavelet filters`_ and support for custom wavelets
  * Single and double precision calculations
  * Real and complex calculations
  * Results compatible with Matlab Wavelet Toolbox (TM)

Requirements
------------

PyWavelets is a package for the Python programming language. It requires:

 - Python_ 2.7 or >=3.4
 - Numpy_ >= 1.9.1

Download
--------

The most recent *development* version can be found on GitHub at
https://github.com/PyWavelets/pywt.

The latest release, including source and binary packages for Intel Linux,
macOS and Windows, is available for download from the `Python Package Index`_.
You can find source releases at the `Releases Page`_.

Install
-------

There are binary wheels for Intel Linux, Windows and macOS / OSX on PyPi.  If
you are on one of these platforms, you should get a binary (precompiled)
installation with::

    pip install PyWavelets

Users of the Anaconda_ Python distribution may wish to obtain pre-built
Windows, Intel Linux or macOS / OSX binaries from the default channel.
This can be done via::

    conda install pywavelets

Several Linux distributions have their own packages for PyWavelets, but these
tend to be moderately out of date.  Query your Linux package manager tool for
``python-pywavelets``, ``python-wavelets``, ``python-pywt`` or a similar
package name.

If you want or need to install from source, you will need a working C compiler
(any common one will work) and a recent version of `Cython`_.  Navigate to the
PyWavelets source code directory (containing ``setup.py``) and type::

    pip install .

To run all the tests for PyWavelets, you will also need to install the
Matplotlib_ package.

The most recent *development* version can be found on GitHub at
https://github.com/PyWavelets/pywt.

The latest release, including source and binary packages, is available for
download from the `Python Package Index`_ or on the `Releases Page`_.

.. seealso::  :ref:`Development notes <dev-index>` section contains more
              information on building and installing from source code.

Documentation
-------------

Documentation with detailed examples and links to more resources is available
online at http://pywavelets.readthedocs.org.

For more usage examples see the `demo`_ directory in the source package.

State of development & Contributing
-----------------------------------

PyWavelets started in 2006 as an academic project for a masters thesis
on `Analysis and Classification of Medical Signals using Wavelet Transforms`
and was maintained until 2012 by its `original developer`_.  In 2013
maintenance was taken over in a `new repo <https://github.com/PyWavelets/pywt>`_)
by a larger development team - a move supported by the original developer.
The repo move doesn't mean that this is a fork - the package continues to be
developed under the name "PyWavelets", and released on PyPi and Github (see
`this issue <https://github.com/nigma/pywt/issues/13>`_ for the discussion
where that was decided).

All contributions including bug reports, bug fixes, new feature implementations
and documentation improvements are welcome.  Moreover, developers with an
interest in PyWavelets are very welcome to join the development team! Please
see our `guidelines for pull requests`_ for more information.

Contributors are expected to behave in a productive and respectful manner in
accordance with our `community guidelines`_.

Contact
-------

Use `GitHub Issues`_ or the `PyWavelets discussions group`_ to post your
comments or questions.

License
-------

PyWavelets is a free Open Source software released under the MIT license.

Citing
------

If you use PyWavelets in a scientific publication, we would appreciate
citations of the project:

    Lee G, Wasilewski F, Gommers R, Wohlfahrt K, O'Leary A, Nahrstaedt H,
    and Contributors, "PyWavelets - Wavelet Transforms in Python", 2006-,
    https://github.com/PyWavelets/pywt [Online; accessed 2018-MM-DD].


Contents
--------

.. toctree::
   :maxdepth: 1

   ref/index
   regression/index
   dev/index
   resources
   contents

.. include:: common_refs.rst
