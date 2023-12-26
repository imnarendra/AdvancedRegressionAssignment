# Project Name
> Advanced Regression (Surprise Housing)


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.<br /><br />
The company is looking at prospective properties to buy to enter the market. We need to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.<br /><br />The company wants to know:<br /> Which variables are significant in predicting the price of a house, and <br />How well those variables describe the price of a house.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
### Linear Regression Model:
<li>R-squared = 93.5%</li>

### Ridge Regression Model:
  <li>alpha: 0.1</li>
  <li>R Squared on train set =  95%</li>
  <li>R Squared on test set =  74%</li>
  <li>RMSE =  0.041</li>
  <br />  
 
  <strong>Top 10 feature variables:</strong>
      <li>MSSubClass</li>
      <li>RoofMatl_Membran</li>
      <li>MSZoning_RL</li>
      <li>MSZoning_FV</li>
      <li>MSZoning_RH</li>
      <li>MSZoning_RM</li>
      <li>RoofMatl_Roll</li>
      <li>RoofMatl_Metal</li>
      <li>RoofMatl_WdShngl</li>
      <li>PoolQC_No_Pool</li>
        
### Lasso Regression Model:
  <li>alpha: 0.0001</li>
    <li>R Squared on train set =  95%</li>
    <li>R Squared on test set =  65%</li>
    <li>RMSE =  0.056</li>
     <br /> 
  <strong>Top 10 feature variables:</strong>
  <li>MSSubClass</li>
  <li>MSZoning_RL</li>
  <li>MSZoning_FV</li>
  <li>MSZoning_RH</li>
  <li>MSZoning_RM</li>
  <li>SaleType_ConLD</li>
  <li>Neighborhood_Crawfor</li>
  <li>Neighborhood_StoneBr</li>
  <li>Functional_Typ</li>
   <li>Exterior1st_BrkFace</li>

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
<li>numpy - version 1.24.3</li>
<li>pandas - version 1.5.3</li>
<li>matplotlib - version 3.7.1</li>
<li>seaborn - version 1.2.2</li>
<li>statsmodels - version 0.12.2</li>
<li>sklearn - version 0.13.5</li>


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
<p>"I want to express our heartfelt gratitude to the teachers and peers at Upgrad/IIITB for their consistently clear and informative sessions, as well as for patiently addressing our queries every day. I also extend my appreciation to the entire Upgrad team for providing us with this incredible learning platform."</p>


## Contact
Created by [Narendra Jha]
