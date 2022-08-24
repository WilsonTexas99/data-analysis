# Ford GoBike System Data Exploration
## by Wilson Uduma


## Dataset

The data consists of information regarding over 175,000 member rides made in Ford GoBike system, covering the greater San Francisco Bay area. The dataset can be found in Udacity's
repository library [here](https://docs.google.com/document/d/e/2PACX-1vQmkX4iOT6Rcrin42vslquX2_wQCjIa_hbwD0xmxrERPSOJYDtpNc_3wwK_p9_KpOsfA6QVyEHdxxq7/pub)


## Summary of Findings

In the exploration, I observed that the average trip taken by all members in the dataset was around 726secs (about 12 minutes). I found that there were more Subscribers than Customers in the dataset as well as more of those members being male, compared to female and other. Also, most members were born between 1985 and 1995 and there was a huge number of members who did not bike share compared to those who did.

I further explored the relationship between these categorical variables and the birth year, and I observed irrespective of user_type, member_gender or bike_share, members were mostly born around 1980 and 1990. This was useful to have noticed as it showed that across all categorical data, Ford GoBike's members were millennials. After that, I explored the relationship between the categorical variables and the duration. I observed that Customers spent twice as more time on the bikes as subscribers. Also, Others gender category spent more time on the bike than Females and Males. Lastly, those who did not bike-share for all of their trips spent more time on their bikes than those who did (only by few seconds).

I went further to explore multiple relationships between some categorical variables and duration. I observed that for each user_type, Others gender category seem to spend more time on their bikes than other genders (with male the least - surprising for a gender category with the highest data). Interstingly, we observed that Customers don't generally bike-share but Subscribers do and each gender spend more time on their bikes when they are not bike-sharing during their trips than when they are bike-sharing.

Lastly, I explored multiple relationships between some categorical variables and birth_years. I observed that all gender categories, irrespective of user_type, seem to be born between 1980 and 1990. And the older you get, the less likely you are willing to bike share. To put in another way, younger generations seem to bike share more than older generations.


## Key Insights for Presentation

For the presentation, I focus on few of the influences of the categorical variables (user_type, member_gender, bike_share_for_all_trip) with the numerical variables (member_birth_year, duration_sec). I start by introducing the
duration variable, followed by the birth_year variable, then plot their respective distributions.

Afterwards, I introduce each of the categorical variables one by one. To start,
I used the bar plots of user_type and member_gender across duration. I'm only looking at
these two visuals because they are quite important in the dataset, as they show which user category spends more time on their bikes, as well as their gender category. Lastly, I used the boxplot to show the user_type and bike_share across members' birth years as there are some interesting insights discovered.