Case Study: Cyclistic Bike-Share

INTRODUCTION

Case study from Google Coursera – Professional Data Analytics Certificate Capstone. 
In this case study was performed data analysis for a fictional bike-share company Cyclistic Bike-Share, in order to answer the business questions, applying the data analysis process: ask, prepare, process, analyse, share, and act.
The bike-share company is based in Chicago, and as part of the marketing analyst team, the work will be on maximizing the number of annual memberships for the company's future success.
The customers are classified as casual and members who purchase Cyclistic annual memberships. The goal is to design marketing strategies aimed to convert casual riders into annual members.  The analysis was made from the past 12 months, applying BiQuery SQL and Google DataStudio.

ASK

The questions that will guide the future marketing program:
How do annual members and casual riders use Cyclistic bikes differently?
Why would casual riders buy Cyclistic annual membership?
How can Cyclistic use digital media to influence casual riders to become members?

PREPARE

Applying ROCCC to check for good data by Reliable, Original, Comprehensive, Current and Cited. The Cyclistic’s historical trip data to analyse and identify trends were made available by Motivate International Inc. This is public data that can be used to explore how different customer types are using Cyclistic bikes. The data was uploaded and stored on a monthly basis to the index of bucket “divvy-tripdata”.
The latest 12 months of data, spanning between June 2021 to May 2022 are available and used for this analysis.
The files were organized by following columns:

ride_id: unique key for each ride

rideable_type: kind of bike used for the ride (docket bike, electric bike, classic bike)

started_at: date/time for the beginning of the ride

ended_at: date/time for the ending of the ride

start_station_name

start_station_id

end_station_name

end_station_id

start_lat: beginning of the ride latitude

start_lng: beginning of the ride longitude

end_lat: ending of the ride latitude

end_lng: ending of the ride longitude

member_casual: type of ride by member or casual.

