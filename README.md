# Instructions

## Setting Up Virtual Environment
1. Create a virtual environment: ``python3 -m venv .group7_env``

2. Activite your virtual environment: 

    ``source .group7_env/bin/activate``    # Mac/Linux
                                       
    ``.group7_env\Scripts\activate``       # Windows

3. Install all dependencies: ``pip install -r requirements.txt``

4. When running a .ipynb file, select this python environment as your kernel

5. If you get an error importing xgboost: ``brew install libomp``

## Results
Linear Regression with LASSO:
    
    R^2 = .61
    MAE = 187364.68
    RMSE = 274363.41

Newton's Method:

    R^2 = .635
    MAE = 179695.41
    RMSE = 262443.67

XGBoost:

    R^2 = .68
    MAE = 168259.50
    RMSE = 248893.27

1. To confirm these results, run the following files:
    
    ``Linear_Regression_LASSO.ipynb``
    
    ``Newton's_Method.ipynb``
    
    ``XGBoost.ipynb``
