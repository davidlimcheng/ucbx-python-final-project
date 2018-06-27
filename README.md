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

# Dependencies
```bash
blas                      1.0             
ca-certificates           2018.03.07          
certifi                   2018.4.16              
cycler                    0.10.0           
freetype                  2.8                
intel-openmp              2018.0.0           
kiwisolver                1.0.1          
libcxx                    4.0.1            
libcxxabi                 4.0.1                
libedit                   3.1.20170329        
libffi                    3.2.1              
libgfortran               3.0.1            
libpng                    1.6.34           
matplotlib                2.2.2            
mkl                       2018.0.2       
mkl_fft                   1.0.1           
mkl_random                1.0.1           
ncurses                   6.1               
nltk                      3.3.0             
numpy                     1.14.3       
numpy-base                1.14.3           
openssl                   1.0.2o            
pip                       10.0.1              
pyparsing                 2.2.0          
python                    3.6.5               
python-dateutil           2.7.3  
pytz                      2018.4        
readline                  7.0               
scikit-learn              0.19.1          
scipy                     1.1.0         
setuptools                39.1.0         
six                       1.11.0      
sqlite                    3.23.1    
tk                        8.6.7              
tornado                   5.0.2               
wheel                     0.31.1                   
xz                        5.2.4                 
zlib                      1.2.11               
```
