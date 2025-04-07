# Spectral View

## UV Absorbance Curve



## X-ray Scattering Curve

In the spectral (or angular) view of X-ray scattering data, they are called scattering curves. Here is an example of simplest case below.

In SAXS theory, it is known that a detector image is a spherical average of squared absolute values of Fourier transform of an object, which is represented in electron density.[^1] These four related sets of data are depicted in the following firure, in case where the particle shape is equally an ellipsoid.

```{figure} ../../_static/images/saxs_illust.png
:name: saxs_illustration

SAXS Illustraion through Fourier Transform of an Ellipsoid
```

[^1]: `Molass Library` currently does not directly utilize this relation, while `DENSS` {cite:p}`Grant:2018` is an excellent application of its smart use, from which we learned coding for the figure.