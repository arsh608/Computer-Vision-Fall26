# Task 3: Real-Time Echocardiogram Video Analysis

## Pipeline
Per-frame loop over an ultrasound video:
1. Histogram equalization
2. JET colormap
3. Color balance adjustment
4. Log transform (reveal dark heart-chamber detail)
5. Gamma transform (suppress bright backscatter noise)
6. Raw feed and enhanced feed shown side by side via `cv2.imshow()`

## Data required
Place **one short .mp4 clip** (5–10 seconds, trimmed from EchoNet-Dynamic) in `data/` as `echo_sample.mp4`. Keep it short — a few MB, well under the 100MB GitHub limit.

## How to run
**Must be run locally** — `cv2.imshow()` does not work in Colab (no GUI window).
```
cd Task_3_Echo_Analysis
jupyter notebook realtime_echo.ipynb
```
Press `q` in the video window to stop the loop. Screenshots of the running pipeline go in `output/`.
