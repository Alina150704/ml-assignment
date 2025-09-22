# ML  Assignment – My Submission

Hi! This repo contains my work for the ML  assignment.  
I’ve split the solution into two parts, as mentioned in the instructions.

---

## Part 1 – 3D Mesh Preprocessing (Mandatory)

- **Script:** `data_prep.py`  
- **What it does:**
  - Reads all `.obj` mesh files in the current folder
  - Extracts key stats: number of vertices, number of faces, bounding box min/max
  - Normalizes each mesh (centers it and scales to a unit box)
  - Saves the cleaned meshes in `.ply` format inside the `normalized/` folder
  - Stores the summary in `results.csv`

**How to run:**
```bash
python data_prep.py
