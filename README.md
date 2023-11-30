# Portfolio Optimization Project

## About Us:
Creators: Greg Peng, Diego Marquez, Jackson Song, Will McKinnon, Mac Prom. 

Created in University of Illinois Data Science Club, NOV 29 2023.

## PURPOSE: To give a client a stock portfolio with the HIGHEST rate of return given their MAXIMUM risk and maximum investment percentage in a stock they want to commit.

This Project was created with the idea of assisting the elderly with their retirement by providing an optimal portfolio. The following is a summmary of the project:

Resources utilized: Yahoo Finance Stock Market indexes and Government Bonds.  

1) Extraction of Stock Data
2) Calculation of historic annual rates of return and risk
3) Using XGBoost ML model to predict NEW rates of return and risk
4) Using Modern Portfolio Theory (MPT) on the predicted rates of return and risk from the ML Model to give the optimal portfolio
5) Printed out visuals showing our ML model accuracy and comparing the Machine generated portfolio to other stocks

PRESENTATION: https://docs.google.com/presentation/d/1fYfy8J9Yi-Vw2jI0SYlqxFTbSfe_E-BvaNWdBLMgBog/edit#slide=id.SLIDES_API505829097_5


## HOW TO USE:

1. Import/Copy the Portfolio Optimization to VS Studio or Google Colaboratory
2. Copy all stock/bond data from this google drive: https://drive.google.com/drive/folders/1epK-NO_fJwiJgeWf8kEYqNK7A9t8uJq2 OR download it yourself from Yahoo Finance
3. Run the code and adjust the max_investment and max_risk parameters

## VISUALS

Results of our ML Model:
Rate of Return:
<img width="686" alt="Screenshot 2023-11-30 104413" src="https://github.com/UIUC-DSC/Diego/assets/134166232/8184f9a4-cf9a-426d-bb1a-37fc87ad0990">
Risk:
<img width="684" alt="Screenshot 2023-11-30 104551" src="https://github.com/UIUC-DSC/Diego/assets/134166232/572e74d1-6e90-43ce-9d5f-7ab549468036">

## Final Comments:
We were in the process of creating a frontend but had difficulty integrating it. We may revisit this project for the integration

 
