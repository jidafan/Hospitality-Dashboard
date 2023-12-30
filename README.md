# Hospitality Dashboard

## Table of Contents
* [Introduction](#introduction)
* [Data Review](#data-review)
* [PowerBI Dashboard](#powerbi-dashboard)
* [Conclusion](#conclusion)

## Introduction

In this project, we will use PowerBI to create a dashboard using data from AtliQ Grands Hotel data. We will create a dashboard that displays relevant KPIs that will help the company regain its market share and increase its revenue. The data is sourced from [Code Basics](https://codebasics.io/) from their resume projects.

## Data Review

The data contains information regarding various hotels that are owned by AtliQ. The information pertains to the booking, occupancy, revenue and other such metrics. The data can be viewed [here](https://github.com/jidafan/Hospitality-Dashboard/tree/main/Input%20Files).

## PowerBI Dashboard

![image](https://github.com/jidafan/Hospitality-Dashboard/assets/141703009/c7712d16-a34b-4cef-8de1-5cebc1808113)



The dashboard allows the user to filter by City, Room Type, Hotel, Month and Week. It provides information on the revenue, occupancy and bookings differences between the weekend and the weekday. Furthermore, it provides information on many key metrics that stakeholders would be interested in. The variables used were created by utilizing dax in powerBI.

| Variable      | Description           | 
| ------------- |:---------------------| 
| `Revenue`     | Total amount of income generated from the hotel    |
| `Revpar`     | Revenue per available room   |   
| `DSRN` | Average amount of rooms that are available to be booked over a time period                              |
| `Occupancy%`     | The percentage of the hotel that is occupied   |
| `Realisation%`     | The percentage of successful checkouts    |   
| `ADR` | The ratio of revenue over the total bookings                                 |
| `Cancellation%`     | The percentage of the bookings that have been cancelled   |
| `No Show%`     | The percentage of the bookings where the guest never checked in      |   
| `DBRN` | Average amount of rooms that are booked over a time period                 |
| `DURN` | Average amount of rooms that are utilized by the guests over a time period          |

## Conclusion

### Insights Gathered 

* Mumbai generates the highest revenue, which is followed by Bangalore, Hyderabad, and Delhi
* Atliq Seasons is probably proportionally worse than all other hotels.
* Elite room types contribute the most to the revenue, and possess the 2nd highest occupancy rate.
* Other platforms contribute to the majority of the bookings at the hotels and should be investigated.
