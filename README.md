# RADHIKA - DISTRICT CROP-PROFILE CLUSTERING

## Student Details
- Name: Radhika
- University Roll No.: 24020570050
- Course: Machine Learning, B.Sc. (H) Computer Science, Semester V
- College: Ramanujan College, University of Delhi
- Supervisor: Dr. Nikhil Kumar Rajput
- Email: Radhika93962@gmail.com

## Generate the Submission PDF
1. Open this folder in File Explorer.
2. Click the address bar, type `powershell`, and press Enter.
3. Run this command twice:

   ```bash
   pdflatex -interaction=nonstopmode -halt-on-error main.tex
   ```

   The first run creates `main.pdf`. The second run updates cross-references.
4. If `pdflatex` is not recognized, install or finish setting up MiKTeX or TeX Live, then reopen PowerShell and repeat the command.

The folder also contains an older PDF named `Radhika_Crop_Clustering_Journal.pdf`. After checking the newly generated `main.pdf`, use that new PDF for submission. You may rename `main.pdf` to `Radhika_Crop_Clustering_Journal.pdf` if the submission portal requires it.

## Project Files
- `main.tex`: editable LaTeX source for the report.
- `Radhika_Crop_Clustering.ipynb`: analysis notebook; use Run All to reproduce analysis.
- `data/crop_production.csv`: source dataset in CSV format.
- `results/`: generated analysis tables and district-level outputs.
- `00_dataset_overview.png`, `01_elbow_silhouette.png`, `02_pca_clusters.png`, and `03_cluster_profiles.png`: figures used in the report.
- `requirements.txt`: Python packages for running the notebook.

The notebook reads the CSV directly and saves generated figures and result tables into the project folders. Review the report and AI-use declaration before submission.
