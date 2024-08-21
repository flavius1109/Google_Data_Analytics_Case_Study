# Google_Data_Analytics_Case_Study
Cyclistic Case Study
### Introduction
In this case study, I will perform tasks of a junior data analyst, working for a fictional company, this case study was part of the Google Data Analytics course.

Data Source: [divvy-tripdata](https://divvy-tripdata.s3.amazonaws.com/index.html).
I started working with this dataset on 13.08.2024. It took about 12-14 hours in total to finish the analysis + presentation.

I used excel and powerpoint for the first case study, below is the link for the data visualization.

Data viz: [Powerpoint](https://www.canva.com/design/DAGOPriaINA/lrNU5geKgNePR7jtSgt0jA/view?utm_content=DAGOPriaINA&utm_campaign=designshare&utm_medium=link&utm_source=editor).

### Background & Scenario

#### About the company

In 2016, Cyclistic launched a successful bike-share offering. Since then, the program has grown
to a fleet of 5,824 bicycles that are geotracked and locked into a network of 692 stations
across Chicago. The bikes can be unlocked from one station and returned to any other station
in the system anytime.
Until now, Cyclistic’s marketing strategy relied on building general awareness and appealing to
broad consumer segments. One approach that helped make these things possible was the
flexibility of its pricing plans: single-ride passes, full-day passes, and annual memberships.
Customers who purchase single-ride or full-day passes are referred to as casual riders.
Customers who purchase annual memberships are Cyclistic members.
Cyclistic’s finance analysts have concluded that annual members are much more profitable
than casual riders. Although the pricing flexibility helps Cyclistic attract more customers,
Moreno believes that maximizing the number of annual members will be key to future growth.
Rather than creating a marketing campaign that targets all-new customers, Moreno believes
there is a solid opportunity to convert casual riders into members. She notes that casual riders
are already aware of the Cyclistic program and have chosen Cyclistic for their mobility needs.
Moreno has set a clear goal: Design marketing strategies aimed at converting casual riders into
annual members. In order to do that, however, the team needs to better understand how
annual members and casual riders differ, why casual riders would buy a membership, and how
digital media could affect their marketing tactics. Moreno and her team are interested in
analyzing the Cyclistic historical bike trip data to identify trends

#### Scenario

I'm a junior data analyst working on the marketing analyst team at Cyclistic, a bike-share
company in Chicago. The director of marketing believes the company’s future success
depends on maximizing the number of annual memberships. Therefore, your team wants to
understand how casual riders and annual members use Cyclistic bikes differently. From these
insights, your team will design a new marketing strategy to convert casual riders into annual
members. But first, Cyclistic executives must approve your recommendations, so they must be
backed up with compelling data insights and professional data visualizations.


In this case study I have been tasked with the question:

# How do annual members and casual riders use Cyclistic bikes differently?

#### Let's begin

First and foremost, I made sure that I understood the question as it should and then began preparing the data.
I downloaded the last 12 months available and took a look around the data. First thought in mind was to gather the total rides for those months and group it to months.
After a first analysis it has been clear that most sales ( uses ) of bicycles have been in the warmer months of the year and the 
least in the colder months.

## Seasonal impact & Usage Frequency Analysis

![casualvsmembers](https://github.com/user-attachments/assets/b065b968-89fa-4cdf-8f1f-497a3e245eca)
![Ddt](https://github.com/user-attachments/assets/e1b71c8b-d17a-44fd-bfc6-5ddb31d2f8a4)

*From the analysis we could also see that the predominant amount of users are the annual members.*

From there I started to look into the trip duration of each category, members and casuals. That analysis gave me insight that members keep a steady amount of time riding ( due to them cycling to work/gym/personal needs, thus being more convenient for them to buy an annual subscription ).

## Trip duration comparison
![hlmembers](https://github.com/user-attachments/assets/357a369a-2c32-40ac-988f-f43dcaf11e78)

And casuals tend to have a higher rate of cycling time ( casual riders are tourists or first timers, they spend more time exploring, sightseeing and visiting different touristical attractions ).

![hlcasual](https://github.com/user-attachments/assets/cdf640d4-b4e4-44db-a5fb-efbde4dcf280)


I solely focused on the three most important insights with the given data even though more could've been explored like locations and type of bikes.

With that I delved even deeper into the time spent riding and came to the confirmation and conclusion that members keep riding for the 10-15 minutes overall, while casuals ride less in the weekdays and double in weekends, that could be because they are off work and have free time to relax, visit and try out new stuff, like cycling.

In the presentation I showed 4/12 months, here I will be attaching two more that confirm the theory.
![Aug2023](https://github.com/user-attachments/assets/5afcd6c2-da99-4cb0-82d1-8682509a804c)
![Mar2024](https://github.com/user-attachments/assets/64a2029f-38bc-47ba-a25b-e29fdd06c925)

### In Conclusion

|Member|Casual|
|------|------|
|Are the vast majority of users, dropping with colder months, yet still remaining in high numbers.|Represent the small minority of users, dropping with colder months.|
|Spend less time riding overall because of known routes and their usage for work and day to day activities.|Spend more time riding, with an increase in weekends for recreational activities.|
|They mostly use it for the same amount of time, no matter the day.|They use it less on weekdays and more on weekends.|
