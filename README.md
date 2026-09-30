# PCA From Scratch on African Development Indicators

Principal Component Analysis implemented from scratch using only NumPy and Matplotlib, applied to African development indicators from 2010 to 2022.

## What this project does

- **Task 1:** Computes the covariance matrix, eigenvalues and eigenvectors, and projects the data onto the principal components.
- **Task 2:** Selects the number of components dynamically based on explained variance, with a written explanation of the trade-offs.
- **Information loss:** Discusses what is lost when reducing dimensions, such as economic activity and population pressure.
- **Task 3:** Optimises the implementation and benchmarks it on larger data.

## Dataset

You need to download and use this dataset to run the notebook:

**`africa_wdi_2010_2022.csv`**

- **Location in this repo:** `data/africa_wdi_2010_2022.csv`
- **Source:** [add the source link]
- Contains missing values and at least one non-numeric column, both handled in the notebook.

## Repository contents

```
├── PCA_Formative_TEAM_24(3).ipynb
├── data/
│   └── africa_wdi_2010_2022.csv
├── PCA_Formative_TEAM_24-1.pdf
└── README.md
```

## How to run

1. Clone the repo or download it as a ZIP:
```
   git clone https://github.com/igorntwari/pca-from-scratch-africa-development-indicators.git
```
2. Make sure `africa_wdi_2010_2022.csv` is in the `data/` folder.
3. Open `pca_from_scratch.ipynb` in Google Colab or Jupyter.
4. If you use Colab, upload `africa_wdi_2010_2022.csv` to the session first (folder icon, then Upload).
5. Run all cells from top to bottom.

Only `numpy` and `matplotlib` are required.

## Authors

- Igor Ntwali
- Erin Leyian

African Leadership University, 2026
