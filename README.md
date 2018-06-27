# Course Information
This is a final project submission for the following course:

Python for Data Analysis and Scientific Computing

COMPSCI X433.3 - 005

David Lim Cheng (X017427)

# Credits
All credits to the following articles, which were used as outlines, and from which most of the code is based off of:

-   [Understanding Matrix Factorization for Recommendation](http://nicolas-hug.com/blog/matrix_facto_1)
-   [Recommender Systems in Python 101](https://www.kaggle.com/gspmoreira/recommender-systems-in-python-101/notebook)
-   [Matrix Factorization for Movie Recommendations in Python](https://beckernick.github.io/matrix-factorization-recommender/)

# Running
This project was built using the Conda package management system.  Included is an `environment.yml`, which can be used to create a conda environment:
```bash
// navigate to the project directory
cd ~/path/to/dir
conda env create -f environment.yml
```
This will create a conda environment called `ucbx-python`. Activate the environment and start a Jupyter Notebook server with the following commands:
```bash
source activate ucbx-python
jupyter notebook
```
This should automatically open a new tab at localhost:8888.  Once the notebook is open, the cells can be worked through linearly, with comments in the code as well.