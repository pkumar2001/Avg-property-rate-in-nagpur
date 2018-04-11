# Avg-property-rate-in-nagpur

**The objetive of this assignment is to predict top 5 localities in Nagpur where Average Property Rate per sq yard is highest.**

To accomplish this assignment data is collected from various property websites of Nagpur. I have collected data from mainly 3 websites.They are following:
1. http://property.sulekha.com/nagpur-real-estate-price-trend
2. https://www.makaan.com/price-trends/property-rates-for-buy-in-nagpur?page=3
3. https://www.99acres.com/property-rates-and-price-trends-in-nagpur

Data contains 101rows x 9columns

**Columns in data**       **data type**

1.Locality                      object

2.Apartment and Flats_1         float64

3.Individual Houses_1           float64

4.Plot_1                        float64

5.Apartment and Flat_2          float64

6.Individual House_2            float64

7.Plot_2                        float64

8.Plot_3                        float64

9.Aparrtment and Flats_3        float64

**I have created 4 new to columns.**
1.Apartment and Flat avg 
2.Individual House avg
3.Plot avg
4.Avg rate per sq ft

**Data cleaning is done to remove null values from featured variables.**

**I have used RandomForestRegressor and GradientBoostingRegressor to build a model and using RSME I have choosen best model between these two.**

**Predicted value is saved in result.csv file**

**Top 5 localities in Nagpur are :**
  1. Bajaj Nagar
  2. Chatrapati Nagar
  3. Dharampeth
  4. Ambazari
  5. Somalvada
  
**Accuracy of model can be improved by training and testing more data.**
