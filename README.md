<h1>High-Performance Concrete Strength Predictor</h1>

<p>
This repository contains the dataset and source code developed for the study:
</p>

<p>
<strong>“Prediction of High-Performance Concrete Compressive Strength Using Machine Learning: An Experimental Data-Driven Study.”</strong>
</p>

<p>
The project presents a data-driven machine learning framework for predicting the compressive strength of High-Performance Concrete (HPC). An experimental dataset containing eight material and curing parameters—cement, Ground Granulated Blast Furnace Slag (GGBS), fly ash, water, superplasticizer, coarse aggregate, fine aggregate, and curing age—is processed through statistical characterization, correlation analysis, and feature scaling. 

Multiple machine learning regression models are implemented to capture the complex nonlinear relationships between mix design parameters and compressive strength. Six algorithms—Linear Regression (LR), Decision Trees (DT), Random Forest (RF), Gradient Boosting (GB), Support Vector Regressor (SVR), and Extra Trees (ET)—are evaluated using an 80:20 training and testing split. Model performance is assessed using the coefficient of determination (R²), Root Mean Square Error (RMSE), and Mean Absolute Error (MAE).

The Extra Trees Regressor demonstrated the highest predictive performance, achieving an R² of 91.3%, RMSE of 4.60 MPa, and MAE of 3.02 MPa. Feature importance analysis highlights cement and curing age as the most influential parameters affecting HPC strength, followed by water and GGBS content. Post-analysis including residual and error distribution evaluation confirms the stability and reliability of the predictive models. The framework demonstrates the capability of machine learning to support efficient concrete mix design optimization while reducing experimental effort and cost in engineering applications.
</p>

<h2>Contents</h2>
<ul>
  <li>Experimental HPC dataset and statistical analysis</li>
  <li>Data preprocessing including correlation analysis and feature scaling</li>
  <li>Implementation of six machine learning regression algorithms</li>
  <li>Model evaluation using R², RMSE, and MAE performance metrics</li>
  <li>Feature importance and residual error analysis</li>
</ul>

<p>
<em>The repository will be fully updated and documented upon paper acceptance.</em>
</p>
