## Theory

Thresholding is used to segment objects from the background based on intensity.

1. Binary Thresholding
- Uses fixed global threshold T.
- Pixels above T → 255.
- Pixels below T → 0.

2. Otsu Thresholding
- Automatically selects optimal threshold.
- Minimizes intra-class variance.
- Works best for bimodal histograms.

3. Adaptive Thresholding
- Computes local threshold for each region.
- Useful under uneven lighting.
- Types:
  - Adaptive Mean
  - Adaptive Gaussian
