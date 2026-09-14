# Task 2: Multi-Modal Cardiac Image Fusion

## Pipeline
1. Load one CT slice + its matched MRI slice
2. Histogram equalization on both, independently
3. Color-map each modality
4. Weighted fusion with `cv2.addWeighted()` (CT weighted higher for edges, MRI lower for tissue detail)
5. Log + gamma transform on the fused result
6. Side-by-side comparison of CT / MRI / fused
