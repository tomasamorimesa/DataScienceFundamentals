# Data Science Fundamentals

Teaching materials for the Data Science Fundamentals course at ISCTE. Each week has its own folder with the lecture notebook (or slides), the exercises, and their solutions.

## Weekly index

| Week | Topic | Materials |
|---|---|---|
| 1 | Introduction | slides: [Part 1](Week%201/FCD_1st_week_1-Introduction.pdf), [Part 2](Week%201/FCD_1st_week_2.pdf) |
| 2 | Introduction to Python | [notebook](Week%202/FCD_2nd_week_2nd_session-IntroductionToPython.ipynb), `exercises/`, `solutions/` |
| 4 | Python data structures | [notebook](Week%204/FCD_4th_week_PythonDataScrutures.ipynb), `exercises/`, `solutions/` |
| 5 | NumPy arrays and data loading with Pandas | [NumPy](Week%205/FCD_5th_week_NumPy-Arrays.ipynb), [Pandas](Week%205/FCD_5th_week_DataLoading-Pandas.ipynb), `data/`, `extra/`, `solutions/` |
| 6 | Data wrangling and visualization | [Data Wrangling](Week%206/FCD_6th_week_1-DataWrangling.ipynb), [Matplotlib](Week%206/FCD_6th_week_4-PlottingVisualization-MatPlotLib.ipynb), [Seaborn](Week%206/FCD_6th_week_5-PlottingVisualization-Seaborn.ipynb), `FCD_6th_week_Exercises/`, `FCD_6th_week_datasets/` |
| 7 | Practice and review | `FCD_7th_week_Notebooks + Dataset/`, `FCD_7th_week_Exercises/`, `FCD_7th_week_Exercises-Solutions/` |
| 8 | Decision trees, random forests, and k-means | [Decision Trees](Week%208/FCD_8th_week_1-DecisionTrees.ipynb), [Random Forests](Week%208/FCD_8th_week_3-RandomForests.ipynb), [k-Means](Week%208/FCD_8th_week_5-kMeans.ipynb), `data/`, `exercises/`, `solutions/` |

Week 3 is not yet in the repository.

## Folder layout

Layout varies slightly week to week, but the general pattern is:

```
Week N/
├── FCD_Nth_week_*.ipynb   # lecture notebook(s), one per topic covered that week
├── data/                  # datasets used by the notebook(s), where applicable
├── exercises/              # exercise notebooks/files for students
└── solutions/               # worked solutions to the exercises
```

Some weeks add an `extra/` folder for supplementary material.

## Running the notebooks

The notebooks are plain Jupyter notebooks (no Colab-specific mounting steps). To run them locally:

```bash
pip install -r requirements.txt
jupyter notebook
```

Open the relevant week's notebook and run the cells in order. Where a notebook reads from a `data/` folder, keep that folder alongside the notebook — the paths are relative.

## Dependencies

Core libraries used across the weeks: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`. If a `requirements.txt` isn't present yet, these can be installed directly:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

## Course

Data Science Fundamentals — ISCTE Technology School.