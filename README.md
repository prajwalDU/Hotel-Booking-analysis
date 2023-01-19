# Hotel Booking Analysis
![hotel-jobs2-d6ebf43935](https://user-images.githubusercontent.com/67784512/211192193-3627b8ce-0082-486b-9a3b-0a61cd536c7c.jpg)

Hotel bookings depend on many factors such as type of hotels, seasonality, days of week, meals available, parking spaces, charges etc. Hence analysing the patterns available in the past data is very important to help the hotels plan well accordingly in order to benefit the business. The given data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, the number of adults, children, and/or babies, and the number of available parking spaces etc, we tried to understand the customer’s’ behaviour and useful patterns in the data to help hotel managements improve the business by taking better decisions. The sequence of processes carried out to analyse the data is mentioned below:

We tried to understand the customer’s’ behaviour and useful patterns in the data to help hotel managements improve the business by taking better decisions. The sequence of processes carried out to analyse the data is mentioned below:


**Data preparation**

It includes basic inspection on the raw data, Data Cleaning by handling missing values. We also treated outliers first by capping method, we defined some thresholds to cap some of the categorical features, then we handled the outliers in remaining features by standard IQR method, after that we did some feature engineering in order to understand the patterns in latent features.



**EDA - (Exploratory data analysis)**
Here we answering some of the questions which we wrote

Q1. Which year the hotels (both city and resort) have the highest footfall?

Q2. Which are the top 10 countries from travelers and tourists visit the hotels?

Q3. What type of Bookings is majorly seen in the hotels?

Q4. How much customer pay in for accomodation per night ?

Q5. What is the booking relation between Resort Hotel and City Hotel?

Q6. Find Top 20 agents with highest bookings?

Q7. Which was the most booked accommodation type (Single, Couple, Family)?

Q8. What is the busiest month for hotels?

Q9. Booking cancellation as per month ?

Q10. Finding the occupancy and level of profitability over month?

Q11. How long the customer stays in the hotel ?



And We also we draw a heat map to find which variables are correlated more.

![Screenshot (70)](https://user-images.githubusercontent.com/67784512/211192963-a785f2b1-f8dc-47b9-b9bc-ea9faabcc33a.png)

**We encountered following patterns in the given historical data:**

* Top Hotel - City Hotel. Top meal - Bread and Breakfast. Top Agent - Agent No. 9. Top room type - A
* One out of every three bookings are cancelled.
* People prefer to tour more in August.
* Most preferred meal is BB(Bread and Breakfast.
* Online marketing is the best way to attract customers.
* People do not want to pre-deposit the money for booking.
* Most of the visitors are couples.
*Resort hotel is preferred mostly for longer stay,day time stays. and when the parking space is needed.
* More than 15 days advance bookings have high chances of cancellation.
* Direct bookings have very less cancellation%.
* Best time to book a hotel is in January.
* Average days in advance booking : 77 days
* Average nights spent by visitors: 3
* Most visitors are from these countries: Portugal, Britain, France, Spain and Germany.
* Total Special requests and the revenue depends more on total members arrived.

**In this project, we also analysed the factors affecting the hotel bookings which may be useful to predict the future bookings, cancellations and number of special requests.**



