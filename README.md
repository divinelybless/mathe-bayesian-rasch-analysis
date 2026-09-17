# MathE hierarchical Bayesian Rasch analysis

Research code and derived analysis tables accompanying Dorcas Attuabea Addo's manuscript, *Beyond Basic and Advanced: Do Lecturer-Assigned Difficulty Levels Reflect Empirical Mathematics Item Difficulty in Higher Education?* (PLOS ONE manuscript PONE-D-26-43811).

## Original data

The original dataset is **not redistributed** here. Obtain *Assessing Mathematics Learning in Higher Education* from the UCI Machine Learning Repository: https://doi.org/10.34620/dadosipb/PW3OWY. Place its CSV at `data/MathE dataset (4).csv`, or change `DATA_PATH` in the notebook. The notebook expects semicolon-delimited CSV text encoded as `cp1252`.

## Repository contents

The current upload stores `MathE_hierarchical_Rasch_analysis.ipynb` and the `S2_`, `S3_`, and `S4_` derived CSV tables in the repository root. `requirements.txt` lists Python dependencies. The `data/` directory is a placeholder for a local copy of the original dataset, not a redistribution of that dataset.

**Verification status:** Notebook code cells have passed a Python syntax check, but the notebook has not been independently executed end-to-end with fresh MCMC sampling and comparison of every result. The CSVs are existing research outputs, not independently regenerated during repository preparation. Do not describe the analysis as independently reproduced until this verification is complete.

**Student-level data:** `S3_Data_PPC_Student.csv` was temporarily removed from the current branch pending a review of whether its student-level IDs and derived results may be redistributed. Deleting a file from the current branch does **not** erase it from Git history; please review the original dataset's data-sharing terms and whether history remediation is necessary before considering the file private.

## Running the analysis

Install dependencies with `pip install -r requirements.txt`, obtain the original dataset as above, and run `MathE_hierarchical_Rasch_analysis.ipynb` in order. The MCMC and prior-sensitivity sampling may be time-consuming. Outputs are written to `mathe_final_outputs/`.

## Citation and reuse

Cite the original MathE dataset and associated manuscript. This GitHub URL is not an archival DOI; a version-specific DOI can be obtained by archiving a release in Zenodo. **No explicit code license has yet been selected by the repository owner.** Public visibility alone does not grant unrestricted reuse. A suitable license should be selected before describing the code as unrestricted for reuse.
