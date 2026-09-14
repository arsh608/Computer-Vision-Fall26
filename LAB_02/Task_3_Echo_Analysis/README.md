# Task 3: Real-Time Echocardiogram Video Analysis

## Pipeline
Per-frame loop over an ultrasound video:
1. Histogram equalization
2. JET colormap
3. Color balance adjustment
4. Log transform (reveal dark heart-chamber detail)
5. Gamma transform (suppress bright backscatter noise)
6. Raw feed and enhanced feed shown side by side via `cv2.imshow()`
