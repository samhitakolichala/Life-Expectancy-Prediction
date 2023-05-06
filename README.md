**Life Expectancy Project**

This project aims to analyze and predict life expectancy based on various factors such as country, adult mortality , infant deaths , alcoholism , percentage expenditure, hepatitis B Measles , BMI , under five deaths,polio, HIV/AIDS , thinness 1-19years , income resources , schooling . I explored different statistical models, machine learning algorithms, and data visualization techniques to gain insights into the trends and patterns of life expectancy across different regions and demographic groups.

**Data**

I used publicly available data from the World Health Organization (WHO) and other sources to develop our predictive models. The data includes information on life expectancy, health indicators, socio-economic factors, and environmental factors for different countries and regions.


**Methods**

I applied Standard Scaling to transform the features , Imputed missing values using 'mean' because 'skewness' was less than 'one' , Splitted the data into 80 to 20 ratio for training and test set . Used  Random Forest Regressor , Decision tree Regressor , XGB boost regressor , Gradient Boost regressor models to develop predictive models. Among all the models  random forest regressor performed well . Used  R-square metric ( Independent variable explains the variance of dependent feature)  and measure their accuracy using RMSE metric.

**Insights Gained**


1. **Country** Life expectancy can vary greatly between countries due to factors such as healthcare access and quality, lifestyle habits, and socioeconomic conditions.

2. **Adult mortality**: High rates of adult mortality can have a significant impact on life expectancy, and identifying the causes and prevalence of adult mortality can help improve healthcare and public health interventions.

3. **Infant deaths**: Infant mortality is a key indicator of the overall health and well-being of a population, and studying trends and patterns in infant mortality can help identify areas for targeted interventions and improvements in healthcare.

4. **Alcoholism**: Alcoholism can have a negative impact on health and can lead to premature death, and understanding its prevalence and impact on life expectancy can inform public health interventions and policies.

5. **Percentage expenditure**: Percentage expenditure on healthcare can impact life expectancy by affecting access to and quality of healthcare services, and studying healthcare expenditure patterns can help identify areas for improvement in healthcare systems.

6.**Hepatitis B**: Hepatitis B is a viral infection that can impact liver health and can be transmitted through blood and bodily fluids, and understanding its prevalence and impact on health can inform public health interventions.

7. **Measles**: Measles is a highly contagious viral disease that can be prevented through vaccination, and understanding the prevalence of measles and the impact of vaccination on life expectancy can help inform healthcare policies and interventions.

8. **BMI**: High BMI can be a risk factor for a variety of health conditions that can impact life expectancy, including heart disease and diabetes.

9. **Under five deaths**: Deaths in children under the age of five can have a significant impact on life expectancy, and understanding the causes and prevalence of under five deaths can help identify areas for targeted interventions and improvements in healthcare.

10. **Polio**: Polio is a viral infection that can cause paralysis and can be prevented through vaccination, the impact of vaccination on life expectancy can inform healthcare policies and interventions.

11. **HIV/AIDS**: HIV/AIDS is a viral infection that can lead to the impact of treatment on life expectancy can inform healthcare policies and interventions.

12. **Thinness 1-19 years**: Thinness in children and adolescents can be a sign of malnutrition and can lead to a variety of health problems, and understanding its prevalence and impact on health can help inform public health interventions.

13. **Income resources**: Income and resources can impact access to healthcare, education, and other resources that can influence life expectancy, and understanding their impact on health can help identify areas for targeted interventions.

14. **Schooling**: Education can impact health outcomes by influencing knowledge and behaviors related to health, and understanding its impact on health can help identify areas for targeted interventions and improvements in healthcare.

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

**A quick glance**

# XGB boost regressor

<img width="389" alt="image" src="https://user-images.githubusercontent.com/119112861/236635891-f6df2852-94ae-44f4-a792-89defeb27b15.png">

<img width="390" alt="image" src="https://user-images.githubusercontent.com/119112861/236635907-d207ad86-e859-4b75-a691-d88870d02453.png">

## Gradient boost regressor

<img width="429" alt="image" src="https://user-images.githubusercontent.com/119112861/236635867-f0f31236-cc0f-455b-a6ea-d37bb2e263f8.png">

<img width="386" alt="image" src="https://user-images.githubusercontent.com/119112861/236635875-27c0d659-8680-44e6-92c2-59a137b13862.png">


<img width="698" alt="image" src="https://user-images.githubusercontent.com/119112861/236600675-494c5df6-d78f-4630-b44d-889f1f89b97f.png">

<img width="461" alt="image" src="https://user-images.githubusercontent.com/119112861/236635725-beb49006-4050-4fd7-a4c5-469019cb850b.png">

**Credits**
This project was created by Samhita Kolichala  as part of project at Bombay Stock Exchange . I thank Indrani Sen Mam for her guidance and support.
