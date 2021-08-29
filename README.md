# Ford Gobike Data Exploration
Data analysis of bike renting company data, producing some insights and assessing the relation between different variables.

## Dataset
The data consists of information regarding 183412 bicycle trips with associated data about trip info like duration, start and end time, start and end stations, bike id, also data about the users like thier birth year, gender, and subscribtion type.

## Summary of Findings
The duration histogram follows a uniform distribution when plotted on a log scale with 8 minutes trips as the most common duration. The strongest effect on duration was with the age of users, all trips which are longer than 400 minutes are made by users below 58 years old. Also, the trip starting hour was greatly affected by users age, mainly users in their 30s made most of the trips in 8:00 a.m and in 5:00 p.m. Although gender variations in trip duration were not large, the user type variation is noticable, on average customers take much longer trips than subscribers.

As for the distance, most of the distances falls below 6000 meters, and the most common trip distance being 800 meters. All trips longer than 9000 metes were made by users under 45 years old. no specific gender has average distance higher than the other, but same as duration, customers across all genders make longer trips than users do.

## Key Insights
The main focus of the presentation is the duration and distance of the trip against the user information like gender, age, and service type.
A simple introduction to the distance and duration pattern and common values, and user data variables and their percentages (gender, user type, age).
Then a deeper dive into the effect age has on the duration and distancewith a scatter plot, then a heat map for the starting hour and age.
After that a more detailed scatter plot to study different genders plots against distance and duration, then bar chart to study the different user types in each gender against the duration and the distance.
