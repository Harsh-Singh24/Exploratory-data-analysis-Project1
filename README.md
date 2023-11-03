# Hotel Bookings Exploratory Data Analysis

In this project we are working with Hotel Booking Analysis dataset and review the features of this dataset. Dataset contains 32 columns and 119390 rows. The workflow of this project is divided into three steps.

Step 1: Data collection. In this step we load our data and check the basic features in our dataset. Basic description of the features is defined below in which detail of each column is given. In this step we will also analyse which feature is categorical and which feature is numerical.

Step 2: Data cleaning and Data wrangling. In this step we will deal with missing and duplicate values. After that we tranform our data in most suitable format.

Step 3: Exploratory Data Analysis (EDA). EDA is an analysis approach that identifies general patterns in the data. We will also use visualisation to find insights from the data

Main library used are: Numpy,Pandas,Matplotlib and Seaborn.

## Dataset
We are given a hotel bookings dataset. This dataset contains booking information for a city hotel and a resort hotel. It contains the following features.

```
- hotel: Name of hotel ( City or Resort)
- is_canceled: Whether the booking is canceled or not (0 for no canceled and 1 for canceled)
- lead_time: time (in days) between booking transaction and actual arrival.
- arrival_date_year: Year of arrival
- arrival_date_month: month of arrival
- arrival_date_week_number: week number of arrival date.
- arrival_date_day_of_month: Day of month of arrival date
- stays_in_weekend_nights: No. of weekend nights spent in a hotel
- stays_in_week_nights: No. of weeknights spent in a hotel
- adults: No. of adults in single booking record.
- children: No. of children in single booking record.
- babies: No. of babies in single booking record. 
- meal: Type of meal chosen 
- country: Country of origin of customers (as mentioned by them)
- market_segment: What segment via booking was made and for what purpose.
- distribution_channel: Via which medium booking was made.
- is_repeated_guest: Whether the customer has made any booking before(0 for No and 1 for 
                     Yes)
- previous_cancellations: No. of previous canceled bookings.
- previous_bookings_not_canceled: No. of previous non-canceled bookings.
- reserved_room_type: Room type reserved by a customer.
- assigned_room_type: Room type assigned to the customer.
- booking_changes: No. of booking changes done by customers
- deposit_type: Type of deposit at the time of making a booking (No deposit/ Refundable/ No refund)
- agent: Id of agent for booking
- company: Id of the company making a booking
- days_in_waiting_list: No. of days on waiting list.
- customer_type: Type of customer(Transient, Group, etc.)
- adr: Average Daily rate.
- required_car_parking_spaces: No. of car parking asked in booking
- total_of_special_requests: total no. of special request.
- reservation_status: Whether a customer has checked out or canceled,or not showed 
- reservation_status_date: Date of making reservation status.
```

- Total number of rows in data: 119390
- Total number of columns: 32

## Solution to Business Objective

1. We can clearly see that as lead time increases chaneces of cancelation increases. For lead time less than 10 days percentage cancelation increases from day 0 to day 10 linearly. After leadtime greater than 50 days percentage cancelation becames to uncertain. Business must look for the optimum time between arriving day and day of booking to reduce the chances the cancelation.

2. We can see that the most booking are occurred in the 3rd quater of year so service and resources should be allocated to that.

3. From the above data, we can see that only 9 percentage customers require parking and land space distributed accordingly to maximising the area utilisation.

4. We can see that only two agents are doing most of the booking. Business must look for the reason why other agents are not able to able to do so.

5. Only 3.9% customers are reapted customers. Business must focus on customer retention.

6. We can also see that Room type-'A' is most preffered room but 1 out 6 times business is not able to provide their customers a room of thier chioce.

# Conclusion

1. City Hotel is popular and profitable for travelers.

2. July and August see the most bookings.

3. Room Type A is preferred by travelers.

4. Top bookings from Portugal & Great Britain.

5. Lead time, waiting list, room assignment don't heavily affect cancellations.

6. Agent no. 9 made most bookings.

7. Only 3.9% customers are reapted customers. Business must focus on customer retention.


