**Linear Regression on California Housing Data**\
Marie Gondeck

---

**Introduction**\
This repository contains one of my first projects, completed during a basic Python course at university. It explores linear regression analysis using the California housing dataset to predict median house values in various districts during the 1990s.

**Project Structure**\
`Linear_regression_california_housing.ipynb`: Jupyter notebook containing the full analysis pipeline, from data loading to visualization and model evaluation.

**Data**\
The dataset comprises 20,640 entries, each with 8 features describing aspects of housing in California, such as average number of rooms and median income of the area. The target variable is the median house value, scaled to hundreds of thousands of dollars (MedHouseVal).

**Usage**\
To run the notebook, ensure you have Python installed along with the packages: matplotlib, seaborn, pandas, numpy, scikit-learn

You can install all necessary libraries using the provided `requirements.txt` file:

```bash
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate 
pip install -U pip
pip install -r requirements.txt  
```

Then run:

```bash
jupyterlab
```
