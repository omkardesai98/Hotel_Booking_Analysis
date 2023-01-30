# Hotel_Booking_Analysis




![Logo](https://sewahospitality.com/front_asset/img/Hotel%20Booking.jpeg)

**The A hotel is an establishment that provides paid lodging on a short-term basis. Today hospitality industry development, in the form of hotel software solutions as well as hotel websites that participate in the sales strategies of individual hotel and hotel chains, determines the business policy of creating a rate with respect to the season, occupancy. From customer perspective when customer try to book hotel room, they always think about what will be the best time of year to book a hotel room is? Which month of year should I choose to book hotel room to get maximum discount? Etc. In this project we were provided with data set which contain booking information for a city hotel and resort hotel, and including information such as when the booking was made, length of stay etc. our analysis can help those customers to get all the answers through data visualization.**![--](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
## Index

|  SI.No.            |   Content                                                              |
| ----------------- | ------------------------------------------------------------------ |
| 1 | <a href = "https://github.com/omkardesai98/Hotel_Booking_Analysis#1-Introduction"> Introduction </a> |
| 2| <a href = "https://github.com/omkardesai98/Hotel_Booking_Analysis#1-Data Collection and Understanding"> Data Collection and Understanding </a> |
| 3 | <a href = "https://github.com/omkardesai98/Hotel_Booking_Analysis#1-Data Cleaning and Manipulation"> Data Cleaning and Manipulation </a> |
| 4 | <a href = "https://github.com/omkardesai98/Hotel_Booking_Analysis#1-Exploratory Data Analysis (EDA)"> Exploratory Data Analysis (EDA) </a>  |
| 5 | <a href = "https://github.com/omkardesai98/Hotel_Booking_Analysis#1-Conclusion"> Conclusion </a>  |


![--](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 1. Introduction:
* **Hotels are certainly necessary, and now you can easily find them anywhere, even in small cities. The hotel industry is a business that provides travellers a place to stay. In this industry, success is based on satisfying targeted clients' needs, creating a desirable atmosphere, and providing a diversity of services and amenities. The hotel industry has grown from its modest roots of providing lodging to a large, diverse and multi-faceted industry. The hotel industry’s foundation is the business of providing lodging. The emerging online travel booking operator has become a global phenomenon and represents one third of total global travel sales. Best deals are an important motivation for customers to go online. Since the online agencies provide flexibility and accessibility, it is easy for tourists to search and buy travel products and services within a small fraction of time. Overall, sales from hotel accounts 87.3% of industry revenue (in India 53.9% and 8% total employment rate).**

![--](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 2. Data Collection and Understanding
* **Data collection is the process of gathering data for use in business decision-making, strategic planning, research and other purposes. It's a crucial part of data analytics applications and research projects, Effective data collection provides the information that's needed to answer questions, analyze business performance or other outcomes, and predict future trends, actions and scenarios.**
* **The data is originally from the article Hotel Booking Demand Datasets, written by Nuno Antonio, Ana Almeida, and Luis Nunes for Data in Brief, Volume 22, February 2019.
  The data is downloaded from Almabetter official website.**
![--](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 3. Data Cleaning and Manipulation

**Dealing with Nan Values** : Nan values were present in 4 columns namely company, agent, country and children
	Filling Nan values in company and agent with ‘0’
	Filling Nan values in country with ‘other’
	Filling Nan values in children with ‘0’. Assuming no children in family that visited the hotel 

**Handling Duplicate Values**: Dataset had 31994 duplicate values, so we have dropped these duplicate values

**Datetime Object**: We have changed datatype of ‘reservation status date’ column to ‘Datetime’ object which was earlier ‘String’ object

**Handling incorrect values** : Some wrong entries were made in the dataset as total people leaving in a room were recorded to be 0. So we have dropped these 166 rows, So after doing all the cleaning and manipulations we were left with 87230 rows and 34 columns.

![](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 4. Exploratory Data Analysis (EDA) 
## Screenshots





![--](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
## 5. Conclusion
1.	**Hotels can minimize cancellations by**: 

II.	The hotel can suggest a personalized itinerary.

2.	**Hotels can take specific measures for bookings from Portugal as most of the guests are from Portugal, such as**: 
I.	Tie up with airline partners and offer vouchers for booking flight tickets.

II.	Consider the bookings under the "overbooking" strategy to minimize the chance of unoccupied rooms as a result of cancellations.

3.	**As most of the guests come on vacation, such as in the months of July and August, hotels should give offers so that guests stay longer and give more special requests. This will help hotels to increase their revenue.**

4.	**Hotels should control and give less lead time so that guests will not cancel their reservations.**
