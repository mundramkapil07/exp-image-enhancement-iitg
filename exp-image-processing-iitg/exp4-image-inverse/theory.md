## Theory

A degraded image can be modeled as:

      g(x, y) = f(x, y) * h(x, y) + n(x, y)

where:
- h(x, y) is the point spread function (PSF)
- n(x, y) is noise

### 1. Inverse Filtering

F(u, v) = G(u, v) / H(u, v)

Inverse filtering attempts to recover the original image in the frequency domain.
It is sensitive to noise when H(u, v) is close to zero.

### 2. Wiener Filtering

F(u, v) = [H*(u, v) / (|H(u, v)|² + K)] G(u, v)

where:
- H*(u, v) is complex conjugate of PSF
- K is noise-to-signal ratio

Wiener filtering balances blur inversion and noise suppression.
