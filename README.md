# Challenge_11 


This python notebook studies the correlation of search trend with other factors (stock price, hourly return on stocks price, lagged search trend) for MercadoLibre. MercadoLibre is the most popular e-commerce site in Latin America. The notebook focus on the following: 

- Visual depictions of seasonality (as measured by Google Search traffic) that are of interest to the company.

- An evaluation of how the company stock price correlates to its Google Search traffic.

- A Prophet forecast model that can predict hourly user search traffic.

## Conclusion: 

1. Google search traffic had increased during the month that MercadoLibre released its financial results. The month median for May 2020 was 38181. The month median for all months from 2016 to 2020 was Search Trends 35172.5. Research in May 2020 was more than median number for search every month from 2016 to 2020 by 3008.5. 

<br>

2. Search trend tend to increase over the hoildays. 

<br>

3. Search trend peak at midnight. 

<br>

4. The number of the search trend was maintained at same level and experienced same pattern over the years. In general, there is no increase in trend. There is a peak in 5/2020 and data is missing for 03-2020

    The close price of Mercado stock shows a different narrative. The close price of mercado stock had increased over the years. During period from 03-2020 to 05-2020, there is a decrease in Mercado's close price. 

5. Through Prophet forecast, the stock price are likely to decrease slightly. Yhat is around $89.5 ~ $ -4.18. Highest Yhat_upper going to be $ 95 ~ $ 5.2. Lowest Yhat_lower ranged between $ 80.82 ~ $ -12. 33. 

6. Tuesday gets the most search traffic. 

7. Late December is the lowest point for search traffic. 
