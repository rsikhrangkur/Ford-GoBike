# Ford GoBike Data Exploration
## by Ryan Sikhrangkur


## The Ford GoBike Dataset

The dataset contains more than 180,000 observations made of the Ford GoBike system use in the San Fransisco Bay area. The dataset included several features, including ride duration, the IDs and names of stations where the ride starts and ends, the latitude and longitude coordinates of where the ride starts and ends, And user information such as subscription status, birth year and gender.

After exploring the basic structure of the dataset, I theorized the GoBike system would be used primarily as a regular commuting option. Because the system was used for a commute that would imply several points:

> There would be a strong positive correlation between ride duration and ride distance, and the correlation will slowly grow weaker as the data approaches the maximum values of the two.

> The most popular user type would be subscribers, and the most popular stations would be used by mostly subscribers.

> Under the condition that the time spent on rides are the same, it's expected that distance by user type would decrease in order of Subscriber > Customer > Bike Share for All. That is I assumed the Bike Share for All would be for group or family activities.

## Summary of Findings

In my findings I discovered that the data supported a few of my assumptions.

> An overwhelming 89.7% of users were subscribers with 9.3% of rides made by subscribers were Bike Share for All.

> By weekday the travel duration and distance are as expected with a positive correlation as rides approach 2,000 seconds and 6,000 to 7,000 meters, then the correlation weakens beyond those values. However, the data for Tuesday contradicts this and shows a high concentration of rides occurring between a duration of approximately 125 to 2,100 seconds and a distance of  0 to 7,000 meters.

> Bike Share for All rides did average the lowest travel duration and distance (with the exception of Saturdays where they averaged about the same as subscribers), but surprisingly customers averaged higher than subscribers regardless of weekday.

> Subscribers have the most condensed 95% confidence intervals.

## Key Insights for Presentation

The key insights for my presentation will be to demonstrate how the Ford GoBike system could be used as a method for commuting, and that the trend for this use is done primarily or exclusively with subscribers.