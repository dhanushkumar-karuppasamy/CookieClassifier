# assets/

This folder holds images and animations used by the repository `README.md` and notebooks.

What to add
- `cookie_animation.gif` — small animated GIF used in the README header (recommended width ~220px)
- `ml_animation.gif` — wider GIF showing ML workflow or model training (recommended width ~600px)
- `success.gif` — optional small footer animation
- `model_comparison.png`, `confusion_matrix.png`, `feature_importance.png` — plots used in the README

How to add files safely
1. Put the image/GIF files into this folder locally.
2. Commit them (avoid extremely large GIFs; prefer <5–10 MB each). Example:

```powershell
git add assets/cookie_animation.gif assets/ml_animation.gif
git commit -m "Add README animations"
git push
```

If you prefer not to keep large GIFs in the repo, upload them via GitHub's web UI and then use the raw.githubusercontent.net URL, or keep smaller GIFs and optimized PNGs instead.
