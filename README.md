**Life Expectancy Project**

This project aims to analyze and predict life expectancy based on various factors such as country, adult mortality , infant deaths , alcoholism , percentage expenditure, hepatitis B Measles , BMI , under five deaths,polio, HIV/AIDS , thinness 1-19years , income resources , schooling . I explored different statistical models, machine learning algorithms, and data visualization techniques to gain insights into the trends and patterns of life expectancy across different regions and demographic groups.

**Data**
I use publicly available data from the World Health Organization (WHO) and other sources to develop our predictive models. The data includes information on life expectancy, health indicators, socio-economic factors, and environmental factors for different countries and regions.

** Dataset Description **
Country                         
Continent                        
Year                               
Status                            
Life_expectancy                    
Adult_Mortality                   
infant_deaths                     
Alcohol                            
percentage_expenditure             
Hepatitis_B                        
Measles                          
BMI                                
under_five_deaths                 
Polio                             
Total_expenditure                  
Diphtheria                        
HIV/AIDS                          
GDP                                
Population                         
thinness  1-19 years              
thinness 5-9 years                    
Income_composition_of_resources     : More the willingness of the expenditure for the disease may acquire quality treatment .
Schooling                           :   This feature is about if the said person is educated then he/she would know how dreadful. 

**Methods**
I applied various data preprocessing techniques, feature engineering methods, and model selection strategies to develop our predictive models. I used  '

Random Forest Regressor , Decision tree Regressor , XGB boost regressor , Gradient Boost regressor among which random forest regressor performed well .
I evaluate the performance of our models using R-square  technique ( Independent variable explains the variance of dependent feature)  and measure their accuracy using RMSE metric.

**Results**
I present the results of my analysis in the form of  interactive visualizations where I included the plots  which show the residual variance  , the predicted line , the residual variances were uniform , this observed strength vs  predicted strength plot would show the actual strength values (observed strength) on the y-axis and the predicted strength values on the x-axis. Each data point represents an observation (e.g., a sample) in the dataset. The closer the data points are to the 45-degree line (i.e., the line where observed strength equals predicted strength), the better the model's predictions are.   . I compare the performance of different models and highlight the factors that have the most significant impact on life expectancy.

**Conclusion**
My project provides valuable insights into the factors that influence life expectancy and offers a robust predictive model that can be used to estimate life expectancy for different populations. The results of this project could have significant implications for public health policies, healthcare interventions, and personalized medicine.

**Dependencies**
The project requires the following libraries:

Pandas
Numpy
Scikit-learn
Matplotlib
Seaborn
Usage
To run the project, clone the repository and install the required dependencies. Then run the life_expectancy.ipynb Jupyter Notebook to reproduce the analysis and results. The notebook includes detailed explanations and code for each step of the analysis.

**Credits**
This project was created by Samhita Kolichala  as part of project at Bombay Stock Exchange . I thank Indrani Sen Mam for her guidance and support.
