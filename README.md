# An Analysis of Kickstarter Campaigns

## 1 Overview of Project

### 1.1 Background

A Kickstarter campaign is a platform where creators get their projects funding by sharing their vision to the communities.  To get the project funded, every creator needs to share their ideas, funding goal and deadline to the backers.  Afterwards, the backers will decide whether they will pledge the money or not. If the project does not reach its intended goal, the backers will not be charged, and the creators will not get the funding. 
This analysis is based on Kickstarter campaigns trends in 15 countries (AT, AU, CH, DE, DK, ES, FR, GB, IE, IT, LU, MX, NL, NO) from 2009 to 2017 and will be more focused on the theater category. 


### 1.2 Purpose

The purpose of the project is to provide Louise (Kickstarter Creator) useful information by extracting and finding patterns of the data and visualizing it in charts, which will benefit to crowdfund her project in theater/play category.  The information can be used to support Louise to make decisions on the timing and goal for her campaign to make the project successful.


## 2 Analysis And Challenges

### 2.1 Analysis of Outcomes Based on Launch Date

Launch Date is a date where the campaign is starting.  It is important for the creator to know when the right times will be to launch the campaign.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/88597187/131266945-9b5ac56f-815a-4a72-947e-89d1eaf691a7.png)

<p align="center">
<sub>Figure 1 Theater Outcomes based on Launch Date </sub>
</p>

Figure 1 illustrates the theater outcomes based on Launch Date from 2009 to 2017. The figure data is based on how many successful, failed and canceled campaigns, categorized by their month launch date. Showcased in the figure, Launching the campaign in May amassed the highest successful campaigns rate (>100), while December was the lowest (<40). The number of successful campaigns started to increase in January from (<60) and rose steadily to reach a peak in May (>100), before falling rapidly to December (<40).
The rate of failed campaigns reaches the highest number in May and October. In January, the line started from the (<40) campaign and increased slightly until May (>40). But overall, the graph is quite steady in range >30 to <60. 
As for the canceled campaign, the graph is steady in the range (<20) from January to December.


### 2.2 Analysis of Outcomes Based on Goals

One of the key factors to successful project crowdfunding is to analyze the range of the previous Kickstarter campaign goal amount. This will help creator to estimate the amount they need to ask.

![Outcomes_vs_Goal](https://user-images.githubusercontent.com/88597187/131266961-032d26ee-3519-4225-80c9-3288b67edb16.png)


<p align="center">
<sub>Figure 2 Theater Play Outcomes based on Goal </sub>
</p>

Figure 2 shows the comparison between goal amount  and percentage of outcomes in theater play category from the year 2009 to 2017. The highest percentage for successful outcomes lies in the goal amount between less than 1,000 and 1,000 to 4,999 (both in range 60-80%). This graph also fluctuates by decreasing to the range of 20% (goal amount =25,000 to 29,999), increasing to the range of >60% (goal amount = 35,000 to 39,999) and falling rapidly to 0%. Typically, the campaigns with lower goal amounts have the bigger chance to succeed, however, a sudden increase appears to >60% success percentage on goal amount 35,000 to 44,999. From the observation of the graph data in the following table 1, the number of successful campaigns on goal amount 35,000 to 39,999 is only 4 from within 6 total projects and 2 successful campaigns within 3 total projects on goal amount 40,000 to 44,999. With this data it can be assumed that the rate of success percentage increment could be influenced by the decreasing number of total projects.


<p align="center">
<sub>Table 1 Theater Play Outcomes based on Goal </sub>
</p>

|Goal|Number Successful|Number Failed|Number Canceled|Total Projects|Percentage Successful|Percentage Failed|Percentage Canceled|
|---|---|---|---|---|---|---|---|
|Less Than 1000|141|45|0|186|75.80645161|24.19354839|0|
|1000 to 4999|388|146|0|534|72.65917603|27.34082397|0|
|5000 to 9999|93|76|0|169|55.0295858|44.9704142|0|
|10000 to 14999|39|33|0|72|54.16666667|45.83333333|0|
|15000 to 19999|12|12|0|24|50|50|0|
|20000 to 24999|9|11|0|20|45|55|0|
|25000 to 29999|1|4|0|5|20|80|0|
|30000 to 34999|3|8|0|11|27.27272727|72.72727273|0|
|35000 to 39999|4|2|0|6|66.66666667|33.33333333|0|
|40000 to 44999|2|1|0|3|66.66666667|33.33333333|0|
|45000 to 49999|0|1|0|1|0|100|0|
|Greater than 50000|2|14|0|16|12.5|87.5|0|

The failed graph is the opposite of the success graph due to the absence of canceled campaigns in this category. This graph shows the increasing failed campaign percentage within the higher goal amount, except for goal amount 35,000 to 44,999 where the number of percentages are decreasing.


### 2.3 Challenges and Difficulties Encountered

The challenge encountered in analyzing the data is converting the data in some of the dataset. The date for instance, is a “unix timestamps” data type which is required to be converted to “date” data type for a better reading.
Possibilities of misinterpreting the data when reading the figure also poses a difficulty. In figure 2 for instance, the data shows us the percentage of campaign outcomes compared to goal amount. If Louise is not comparing the success percentage with the number of the projects presented, she may interpret that there is a high chance of success by pledging 35,000 to 44,999 goal amounts, while the high success percentage was due to the small number of projects.


## 3 Results

### 3.1 Theater Outcomes by Launch Date Result

Throughout the Figure 1 Theater Outcomes by Launch Date, we can make two conclusions:

- The highest number of successful theater campaigns is in May. Therefore, it is advisable for Louise to launch the crowdfunding campaign in May or end of spring / early summer for a better chance of success. 

- The lowest number is between November, December and January. Hence, the campaign should not be launched in Winter between November to January due to the risk of failure.


### 3.2 Outcomes based on Goals Result

Figure 2 (Outcomes based on Goals) indicates that the highest percentage of successful campaigns lies in the goal amount between <1000 and 4999. Even though there is an increment in success probability on the campaigns with a goal amount between 35,000 to 44,999, there are far fewer total projects within this scope to guarantee its reliability. The total project with goal amount <1000 and 4999 is 720, while the total project with goal amount between 35,000 to 44,999 is 9. Louise will have the best chance for better crowdfunding performance by submitting a goal amount between <1000 and 4999. However, if 35,000 to 44,999 is preferred, she will be required to gather further information from the campaign with the similar pledge range, especially on how they attract the backer to fund their campaign, i.e : marketing strategy, backers reward system, etc.


### 3.3 Limitations of dataset

The dataset is based on Kickstarter campaigns trends in 15 countries (AT, AU, CH, DE, DK, ES, FR, GB, IE, IT, LU, MX, NL, NO) from 2009 to 2017. For further analysis to help Louise with the fundraising, we may add:
- New Kickstarter Campaign Data
The current dataset only contains the data from 2009 to 2017. If Louise intends to launch her campaign in 2021 or 2022, she will require additional data which span from 2017 to 2021 for the purpose of analyzing the newest trend. 

- Demographic
To encourage the backer to fund the campaign, demographic information could be included to the dataset which can be utilized to accurately devise the marketing strategy based on their preference. 

- Reward
Another factor that could attract the backers to fund the campaign is the desirable rewards offered by the campaign. Adding reward information in the dataset will allow an analysis for the impact of certain types of rewards that leads to a project success. Additionally, reward tier data could be analyzed to further determine the effective rewarding strategy. 


### 3.4 Other Possible tables and/or Graphs

The following feature can be added to expand the analysis from this dataset:
- Country only graph
Figure 1 and Figure 2 gathers data from all countries in the world. By presenting the chart which specifically shows the data of the country where Louise's theater performance will take place, she will have a better understanding of the trend based in that specific country. Furthermore, she can compare it with all country data whether the trend is the same or different.

- Descriptive Statistics
Including the descriptive statistic to show average, median, standard deviation and quartile could help Louise to decide the amount of goal and compare it to the pledged amount. The box and whisker can be added to know if there is an outlier in the data and further analyze the data. 

- Clustered Column Chart 
Clustered column charts in addition to Table 1 will help to visualize the number of of successful, canceled , failed  and total projects compared with the goal amount.


![NumberOfOutcomes_vs_Goal](https://user-images.githubusercontent.com/88597187/131266969-d7e65659-1a8f-4fa8-9e34-0ff22a923840.png)


<p align="center">
<sub>Figure 3 Number of Outcomes based on Goal  </sub>
</p>





