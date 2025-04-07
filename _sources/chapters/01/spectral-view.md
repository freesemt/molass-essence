# Spectral View

## UV Absorbance Curve

In the spectral view of UV absorbance data, they are called absorbance curves. To the best of our knowleged, there are no usable models[^1] for them, while ... at least for amino acids.

## X-ray Scattering Curve

In the spectral (or angular) view of X-ray scattering data, they are called scattering curves. Here is an example of simplest case below.

In SAXS theory, it is known that a detector image is a spherical average of squared absolute values of Fourier transform of an object, which is represented in electron density.[^2] These four related sets of data are depicted in the following firure, in case where the particle shape is equally an ellipsoid.

```{figure} ../../_static/images/saxs_illust.png
:name: saxs_illustration

SAXS Illustraion through Fourier Transform of a homogeneous Ellipsoid
```

[^1]: in the sense that you can use on personal computers.

[^2]: `Molass Library` currently does not directly utilize this relation, while `DENSS` {cite:p}`Grant:2018` is an excellent application of its smart use, from which we learned coding for the figure.