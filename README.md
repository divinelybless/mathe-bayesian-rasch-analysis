# MathE hierarchical Bayesian Rasch analysis

Research code and derived analysis tables accompanying Dorcas Attuabea Addo's manuscript, *Beyond Basic and Advanced: Do Lecturer-Assigned Difficulty Levels Reflect Empirical Mathematics Item Difficulty in Higher Education?* (PLOS ONE manuscript PONE-D-26-43811).

## Original data

The original dataset is **not redistributed** in this repository. Obtain *Assessing Mathematics Learning in Higher Education* from the UCI Machine Learning Repository: https://doi.org/10.34620/dadosipb/PW3OWY. Place the downloaded CSV at `data/MathE dataset (4).csv`, or change `DATA_PATH` in the notebook. The notebook expects semicolon-delimited CSV text encoded as `cp1252`.

## Repository contents and status

The intended upload comprises `analysis/MathE_hierarchical_Rasch_analysis.ipynb`, derived tables in `results/`, and `requirements.txt`. **Verify these files are present before citing this repository as the location of the analysis code or results.**

The notebook has passed a Python-cell syntax check but has **not** been independently rerun end-to-end with fresh MCMC sampling and numerical comparison of all archived results. The derived CSV files are existing research outputs, not independently regenerated during repository preparation. The repository should not be described as fully verified or independently reproduced until that work is complete.

## Running the analysis

Use a Python environment compatible with `requirements.txt`; install dependencies with `pip install -r requirements.txt`, obtain the original dataset as described above, and run the notebook cells in order. The MCMC and prior-sensitivity sampling may be time-consuming. Outputs are written to `mathe_final_outputs/`.

## Citation and reuse

Cite the original MathE dataset and the associated manuscript. A GitHub URL is not an archival DOI; a versioned DOI can be obtained separately by archiving a release in Zenodo. A code license has not yet been selected by the repository owner, so do not assume permission to redistribute or adapt the code beyond applicable law.
