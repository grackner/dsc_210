# Instructions

## Setting Up Virtual Environment
1. Create a virtual environment: ``python3 -m venv .group7_env``
*Or just "python" depending on your python version
2. Activite your virtual environment: 

    ``source .group7_env/bin/activate``    -->  Mac/Linux
   
    ``source .group7_env/Scripts/activate``    -->  If git terminal                          
    ``.group7_env\Scripts\activate``       --> Windows
   

4. Install all dependencies: ``pip install -r requirements.txt``

5. When running a .ipynb file, select this ``.group7_env`` python environment as your kernel

6. If you get an error importing xgboost: ``brew install libomp``

## Results
Linear Regression with LASSO:
    
    R^2 = .61
    MAE = 187364.68
    RMSE = 274363.41

Newton's Method:

    R^2 = .61
    MAE = 187181.66
    RMSE = 273822.51

XGBoost:

    R^2 = .68
    MAE = 168259.50
    RMSE = 248893.27

1. To confirm these results, run all code cells in the following files:
    
    ``Linear_Regression_LASSO.ipynb``
    
    ``Newton's_Method.ipynb``
    
    ``XGBoost.ipynb``
