# The Reddening Line Project software

This repo provides the tools necessary to reproject a 2-dimensional set of colours using the reddening curve projection described in [Fraser et al. (under review)](https://arxiv.org/abs/2206.04068). In summary, the colours are reprojected to two new components: the perpendicular distance from the reddening curve to the point defined by the colours, and the line integral along the reddening curve to that point from a reference colour (usually the Solar colour).

The module contains an array which tabulates the Col-OSSOS colours (u-g), (g-r), (r-i), and (r-J), and the H/WTSOSS colours (F606w-F814w), (F814w-F139m), and (F139m-F153m) for spectral slopes -6 <= s <= 73 %/100 nm normalized at 550 nm. The user can provide arrays for other colours or filter systems.

To do:

1. remove the Col-OSSOS specific code in __main__
2. include a very basic example of how to use
3. update this readme with the example
