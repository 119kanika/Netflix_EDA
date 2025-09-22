# Netflix Movie EDA 🎬

This project explores and analyzes a dataset of Netflix movies to uncover insights about genres, popularity, and trends. It uses **Python, Pandas, Matplotlib, and Seaborn** for data analysis and visualization.

---

## Project Overview

- Dataset contains **9,827 movies** with **9 columns**.
- Key preprocessing steps:
  - Handled missing/duplicate values (none found).
  - Converted `release_date` to datetime and extracted **year**.
  - Dropped unnecessary columns (`original_lang`, `poster_url`).
  - Processed `Genre` column (comma-separated values cleaned and split).
  - Handled outliers in `popularity`.
  - Categorized `vote_average` into groups:
    - **Popular**
    - **Average**
    - **Below Average**
    - **Not Popular**

---

## Analysis & Insights

The notebook answers key questions such as:

- **Most frequent movie genres** on Netflix.
- Which movies received the **highest and lowest popularity**.
- Which genres got the **highest average votes**.
- The **year with the most movie releases**.

---

## Project Structure

```
├── movie_da.ipynb      # Main Jupyter Notebook (analysis + visuals)
├── mymoviedb.csv       # Dataset used (not included here, add if uploading)
└── README.md           # Project documentation
```

---

## Requirements

Install dependencies before running the notebook:

```bash
pip install pandas numpy matplotlib seaborn
```

---

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/netflix-movie-eda.git
   cd netflix-movie-eda
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook movie_da.ipynb
   ```
3. Run all cells to reproduce the analysis.

---

## Results

This analysis provides a clearer understanding of Netflix’s movie trends, such as:
- Most common genres uploaded.
- How **popularity** and **votes** vary across movies.
- Historical trends in movie releases.
