# Kickstarter_Challenge
Kickstarter Challenge Final Version


## **Purpose of the Analysis**

This analysis was created to define and understand how different factors affected the outcome of projects in the Parent Category of “Theater” and the Subcategory of “Plays”. Furthermore, the relative relationship between the projects, their launch dates and funding are represented to provide a contextual explanation on the projects’ outcomes and identify data limitations and possible factors that could enhance and affect the outcome of future projects.

## **Analysis and Challenges**

####  *Analysis of Theater Outcomes by Launch Date*

The analysis was performed by selecting “Theater” as the main filter and by extracting and sorting data relative to the launch date and to the outcome. By looking at the correlation and variances between the months of the year and the number of successful, failed, and cancelled projects, it is possible to determine which months are more likely to have successful launch dates and which ones will not be as successful. 

![image](https://user-images.githubusercontent.com/75655852/103191341-a2e8ce00-48a2-11eb-9991-acd0a41d1194.png)

####  *Analysis of the Outcomes based on Goals*

For the Outcomes Based on Goals, the analysis was conducted based on the dollar amount criteria, the number of different outcomes and the percentages based on the outcomes. A statistical function, COUNTIF, was used to find out different outcomes relative to the dollar amount criteria. 

![image](https://user-images.githubusercontent.com/75655852/103191390-cc095e80-48a2-11eb-93fc-c576d086cc1e.png)

####  *Challenges*

One challenge that I encountered was making sure that the values entered in “number successful”, “number failed” and “number cancelled” matched the correct formula and had different values to reflect the goal (dollar amount criteria). An effective way to confirm that all the numbers match is to compare the sum of the outcome columns with COUNTIF>0. If there is a match, it means that the equations were done properly. 

## **Results, Llimitations of the Dataset and Recommendations**

####  *Conclusions about the Theater Outcomes by Launch Date*

After further analysis, there are several conclusions that can be drawn about the Theater Outcomes by Launch Date. The first one is that the most popular months for launching a campaign are May, June, and July. Despite a high number of failed projects during these three months, they registered the highest number of successful projects during the year. It can be concluded that the summer is not only a popular time for launching projects but it is also the time of year when projects are the most successful. In contrast, the second conclusion to be drawn is that December is the least popular month for launching a campaign, but it is also the least successful month of the year when launched. The end of the year (December) is therefore not an appropriate time to launch a campaign, as it is the least likely to produce a successful outcome.

####  *Conclusions of the Outcomes based on Goals*

The main conclusion that can be derived from the Outcomes Based on Goals, is that the campaigns that had a goal of <$1000, $1000 to $4999 and $5000 to $9999, had a higher number of completed goals compared to other higher dollar amount categories. We can therefore conclude that the campaigns most likely to succeed had a goal of $1000 to $4999 and the ones least likely to have a successful outcome were the ones that had set a higher dollar amount target goal, in which case, the failed outcomes surpassed the successful ones. 

####  *Limitations of the Dataset*

This dataset does not take into consideration the themes of the projects, and various demographical components, such as the theaters' advertised locations and the main target audience. Furthermore, the methods used to advertise projects and subsequently increase their funding are not mentioned. Analyzing and understanding the different methods used to advertise projects could have provided important insights regarding the outcome of these campaigns.

####  *Additional Recommendations*
##### Contributions relative to the month of the year

To understand the funding behaviour of backers, a table and graph could be created to show the recorded contribution relative to the month of the year (during which month of the year is the contribution the highest and for which one it is the lowest).
