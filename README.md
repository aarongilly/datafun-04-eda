# datafun-04-eda
For 44608 CC4.2

## How to Install and Run the Project

This section is a sequential list of steps I took to get create and modify this repository.

1. Clicked `New Repository` in GitHub
   1. Named it & supplied description
   2. Checked the "Add README.md" button
   3. Added a `.gitignore` using the `Python` template, which I'd never tried before.
2. Cloned the repository to my machine using VS Code
   1. Edited this `README.md` up to this point.
3. Added `.venv` to the repository
   1. utilizing:
```shell
python3 -m venv .venv  
source .venv/bin/activate
python3 -m pip install --upgrade pip  
python3 -m pip install --upgrade -r requirements.txt
```
4. Copied an existing `requirements.txt` file into the repo

## Notebooks

### gillespie_notebook.ipynb
This is essentially just a "Hello World!" notebook.

### iris_eda.ipynb
This notebook is an analysis of the famous "iris" dataset. It utilizes pandas dataframes to overview the dataset and seaborn to visualize it with Pairwise & Scatter plots. 
