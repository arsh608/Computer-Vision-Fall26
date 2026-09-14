# Task 1: Diagnostic Enhancement of Chest X-Rays

## Pipeline
1. Load a grayscale chest X-ray
2. Histogram equalization (contrast enhancement)
3. JET colormap (false-color heatmap)
4. Color balance correction
5. Threshold to isolate dense tissue
6. Logarithmic transform (reveal dark background detail)
7. Power-law / gamma transform (soften bone contrast)

## Data required
Place **2–3 sample chest X-ray images** in `data/` (e.g. one NORMAL, one PNEUMONIA, one COVID19 — one per class from the dataset gives a nice before/after contrast comparison). Do not upload the full dataset.

## How to run
```
cd Task_1_Chest_XRay
jupyter notebook xray_enhancement.ipynb
```
Outputs are saved to `output/`.
