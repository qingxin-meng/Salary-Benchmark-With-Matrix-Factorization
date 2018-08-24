# Salary-Benchmark-With-Matrix-Factorization

SalaryBenchmark is Cython package used for salary predicting. 

The methods are based on SVD and NMF models with laplacian regularizers. 

## Data
You can download the Data from [Google Drive](https://drive.google.com/open?id=19YZ34nAI66ARFK5nTJKYBKa8ylOXlElj).
1. salary_lower_bound.p  records the salary lower bound level for each company ID and job ID, the data format is pandas dataframe.
2. salary_upper_bound.p records the salary upper bound level for each company ID and job ID, the data format is pandas dataframe.
3. companay_similarity_matrix.p records the similarities between companies, the coloumn/row indexes correspond with company ID. The format is numpy array.
4. job_similarity_matrix.p records the similarities between jobs, the coloumn/row indexes correspond with job ID. The format is numpy array.

## Installation:
Before to install the package, you need to meet the requirements listed below:

0. python2.7
1. numpy
2. pandas
3. Cython==0.27.2
4. scikit-surprise==1.0.4
5. ipython
6. pickle

Then you can use setup.py file to install this cython package. The commands are:

 $python setup.py build
  
 $python setup.py install
