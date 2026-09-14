# Medical Imaging Portfolio — Lab 02

Three independent tasks applying mathematical image-processing pipelines (histogram equalization, color mapping, color balance, thresholding, log/gamma transforms) to medical imaging data.

| Task | Folder | Modality |
|---|---|---|
| 1 | `Task_1_Chest_XRay/` | Chest X-Ray |
| 2 | `Task_2_Cardiac_Fusion/` | CT + MRI fusion |
| 3 | `Task_3_Echo_Analysis/` | Ultrasound video |

## Setup
```
python -m venv venv
source venv/bin/activate      # Windows: venv\Scripts\activate
pip install -r requirements.txt
```

Then open each task's notebook (`.ipynb`) in VS Code (with the Jupyter extension) or `jupyter notebook`.

Each task's `README.md` lists exactly which sample files to drop into its `data/` folder — only a couple of images/one short clip per task, not the full Kaggle datasets (see root submission rule: 100MB GitHub limit).
