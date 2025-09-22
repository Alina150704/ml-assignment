# ML Assignment – My Submission

Hi! This repo contains my work for the ML  assignment. The project has two main parts: preprocessing 3D mesh data and building a simple PyTorch baseline model. Together, they show my ability to handle both geometry processing and basic machine learning workflows.

---

## Project Summary

This project is divided into two stages that connect data preprocessing with machine learning:

- **3D Mesh Preprocessing (Part 1):**
  - Implemented in `data_prep.py`
  - Loads `.obj` mesh files
  - Extracts useful statistics (vertices, faces, bounding box dimensions)
  - Normalizes each mesh by centering it and scaling it to a unit size
  - Saves cleaned meshes as `.ply` files inside a `normalized/` folder
  - Exports a summary table of stats to `results.csv`

- **Simple ML Baseline with PyTorch (Part 2 - Bonus):**
  - Implemented in `ml_baseline.py`
  - Loads `pose_params.csv` (uses `height` as the target if available, otherwise generates a synthetic one)
  - Builds a lightweight MLP (multi-layer perceptron) using PyTorch
  - Trains for 10 epochs using MSE loss
  - Outputs a `loss_curve.png` that visualizes the training process

---

## How to Run

### Run Part 1:
```bash
python data_prep.py

### Run Part 2:
```bash
python ml_baseline.py
