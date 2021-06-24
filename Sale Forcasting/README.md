Sale Forcasting by Machine Learning Algorithm 
- Linear Regressions 
- Polynomial Regressions 
- Support Vector Regressions 
- Decision Tree Regressions 
- Random Forest Regressions 



Dataset Information
CONTEXT On the morning of 10 January 2017, Opplysningsrådet for Veitrafikken (OFV), Norwegian road association, held a business breakfast for its member organizations, where they presented the annual presentation under the title "Car Year 2016. Status and trends" (Bilåret 2016 – status og trender). Among the highlights for the year, OFV reported all-time-high sales of electric cars, with fully electric and plug-in hybrid cars accounting for 40,2% of all new car sales (compare to 7.4% for Sweden and 3.6% for Denmark). No other country in the world has this level of popularity of battery-equipped vehicles! In November 2016, 12 out of 15 most popular cars sold in Norway were either hybrids of fully electric vehicles with BWM-i3 snapping the title as the most popular car in Norway, ahead of undisputed leader of the last decade VW Golf (including eGolf), according to bilnorge.no. Among 10 most popular cars for the year, OFV reported, there was only one(!) fossil fuel vehicle.

OFV makes annual forecast of new passenger car sales. Short summary of their methodology:

Based on OFV statistics over several years Taking into account the actual monthly figures for the last four years Actual same-month sales for the previous year is combined with the average for the eight previous months, weighed by the month's proportion in a year, adjusted by year's actual sales compared with those of the last year. OFV forecast for 2016 was 157 500 new passenger cars. Actual sales were 154 603 cars. Applying the same model for 2017, OFV forecasts 152 400 new passenger cars to be sold in Norway.

CONTENT

Year - year of sales
Month - month of sales
Quantity - total number of units sold
Quantity_YoY - change YoY in units
Import - total number of units imported (used cars)
Import_YoY - change YoY in units
Used - total number of units owner changes inside the country (data available from 2012)
Used_YoY - change YoY in units
Avg_CO2 - average CO2 emission of all cars sold in a given month (in g/km)
Bensin_CO2 - average CO2 emission of bensin-fueled cars sold in a given month (in g/km)
Diesel_CO2 - average CO2 emission of diesel-fueled cars sold in a given month (in g/km)
Quantity_Diesel - number of diesel-fueled cars sold in the country in a given month
Diesel_Share - share of diesel cars in total sales (Quantity_Diesel / Quantity)
Diesel_Share_LY - share of diesel cars in total sales a year ago
Quantity_Hybrid - number of new hybrid cars sold in the country (both PHEV and BV)
Quantity_Electric - number of new electric cars sold in the country (zero emission vehicles)
Import_Electric - number of used electric cars imported to the country (zero emission vehicles)
Note: The Context and The Content get from references [1]

Download link: https://www.kaggle.com/abdullahbarha/car-sale-in-norway

Environment: Google Colab

Libraries
numpy
pandas
matplotlib
scikit-learn
Neural Network

