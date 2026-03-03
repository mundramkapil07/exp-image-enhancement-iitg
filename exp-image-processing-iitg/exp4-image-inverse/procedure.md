## Procedure

1. Load input image and convert to grayscale.
2. Apply motion blur PSF to degrade the image.
3. Restore using inverse filter.
4. Apply Gaussian blur PSF and restore using inverse filter.
5. Add noise to blurred image.
6. Restore using Wiener filter.
7. Compare all results visually.

## Feedback

- Which restoration looked better: inverse or Wiener?
- Was PSF modeling clear?

## Additional Help

- Use small K for low noise.
- Use larger K for high noise.
