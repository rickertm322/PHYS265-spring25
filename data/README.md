# fits cube

* ngc6503.fits

This is the galaxy NGC6503 observed with the VLA.  It has very clear
signal in the (neutral) HI line. Good example of flat rotation curve
from which we think it showcases the dark matter problem.  There's a
program online you can download from
https://sites.google.com/cfa.harvard.edu/saoimageds9/download that
allows you to preview the different slices in this cube, and even plot
a spectrum as a selected region.


# fits images

Specifically for aplpy, there is a http://aplpy.github.io/downloads/tutorial.tar.gz
but also included here as **tutorial.zip**

There are also many examples on https://www.astropy.org/astropy-data/ but
you will need to download them manually. If you use them, include them in
your repository as we may need to run your notebook!

# spectral lines in a MUSE dataset of NGC253

* ngc253_ha.tab - Halpha.    x=Angstrom y=arbitrary units    - this spectrum also has the two [NII] lines
* ngc253_hb.tab - Hbeta      x=Angstrom y=arbitrary units    - nice clean spectrum with one line

My advice is to use the Hbeta line.

A good model would be:

    a+b*exp(-(x-c)^2/(2*d^2)):

where

 a   baseline flux
 b   peak of gauss
 c   location of gauss
 d   with of gauss
