% IPOL Library Image Input-Output.

# ABOUT

* Author : Nicola Pierazzo   <nicolapierazzo@gmail.com>
* Author : Gabriele Facciolo <gfacciol@gmail.com>
* Copyright : (C) 2017 IPOL Image Processing On Line http://www.ipol.im/
* Licence   : GPL v3+, see GPLv3.txt
* Based on the 2010 implementation of DCT denoising by:
  Guoshen Yu <yu@cmap.polytechnique.fr> and Guillermo Sapiro <guille@umn.edu>
* Latest version available at: https://github.com/zvezdochiot/libiio

# OVERVIEW

This source code provides an implementation of the "Image Input-Output"
described in the IPOL article: http://www.ipol.im/

# UNIX/LINUX/MAC USER GUIDE

The code is compilable on Unix/Linux and Mac OS. 

- Compilation. 
Automated compilation requires the Cmake and make.

- Dependencies.
This code requires the libpng, libtiff, libjpeg.

- Image formats. 
Only the PNG, JPEG, and TIFF (float) formats are supported. 
 
-------------------------------------------------------------------------
Usage:
1. Download the code package and extract it. Go to that directory. 

2. Compile the source code (on Unix/Linux/Mac OS). 

    mkdir build; cd build;
    cmake ..; make;

# ABOUT THIS FILE
Copying and distribution of this file, with or without modification,
are permitted in any medium without royalty provided the copyright
notice and this notice are preserved.  This file is offered as-is,
without any warranty.
