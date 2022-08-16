# PredictingMPG
Gas is EXPENSIVE! My car has very low mpg, let's use stats to fix that! 

## Table of Contents
* [Background](#background)
* [Experimental Design](#experimental-design)
* [Methodology](#methodology)
* [Findings](#findings)
* [Limitations](#limitations)
* [Learnings](#learnings) 
* [References](#references)

## Background
This summer I have had the luxury of commuting to UCLA twice a week for a total of around 200 miles driven just for school. With my car only having an average of 16.5 mpg and gas prices at an all time high, my gas bill is extremely expensive. There are a lot of different ways I could potentially lower this cost. I can commute using cheaper methods of travel sacrificng comfort and time. I can get a new car with higher mpg. Or simply I can just not attend school. While these options do present a much lower gas bill, I would like to keep my car, learn more about statistics, and travel on my own. Luckily I know statistics, and maybe by understanding which factors are most important in predicting MPG, I can use those factors to change my driving habits and increase my car's average MPG. Through this research process I hope to reduce the money spent on gas while also learning the entire data science process. I will collect and clean my own data, use data analysis to see certain trends in the data, and lastly I will build models to predict MPG. 

## Experimental Design
Unlike other projects, for this research study I will have to design my own experiment and collect data on my own. I will be utilizing random basic factorial design and select predictor variables based on literature and my own experience driving. Because I am using factorial design all my variables will have to be categorical variables. This means that if I used numerical values like temperature of the day or time departed, I would have to transform these into categorical variables. 

## Factors 
Passengers, Lane, Weather, Time of Departure, Length of Journey, Speed, Machine, Operator. 

Fixed: Operator, Vehicle
Controlled: Lane
Uncontrolled: Passengers, Time of Departure, Day of the Week, Weather, Speed, Route, Traffic

Operator: Acceleration, Deceleration, How Person Drives
Vehicle: Lexus 
Speed: High(70+), Low
Passengers: 1 , More than 1 
Weather: Hot, Cold
Time of Departure: Morning, Night
Day of the Week: Weekday, Weekend
Route: Freeway, Street
Length of Journey: Long, Short
Elevation: Up, Down/Neutral


### Sources
fueleconomy.gov/feg/factors.shtml
https://wgntv.com/weather/how-do-you-define-daytime-and-evening-times-in-a-weather-forecast/#:~:text=Early%20morning%3A%206%2D9%20a.m.,%2Dmorning%3A%208%2D10%20a.m.&text=Afternoon%3A%20noon%2D6%20p.m.,Early%20afternoon%3A%20noon%2D3%20p.m.
https://www.wired.com/story/is-there-an-optimal-driving-speed-that-saves-gas-and-money/
https://weather.com/weather/tenday/l/48b93e49a11f590ed49e1223fa2b66fe5d8e8c1b914049ea73b0b758a4e0e39f#detailIndex5
