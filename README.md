# Case Study: How does a bike-share navigate speedy success?   
<img width="107" alt="logo" src="https://user-images.githubusercontent.com/98569224/172212218-1bc87981-9b94-4d5e-bd1e-1908c02ff98d.png">  

## Cyclistic Bike-Share Riders Analysis  
#### [Scope of Work](https://docs.google.com/document/d/1p84NlKBkxdx4eRQEho3dA7x1J4lrLyPF/edit?usp=sharing&ouid=106826003681178819109&rtpof=true&sd=true)  
### Summary
I am wearing the hat of a junior data analyst working in the marketing analyst team at **Cyclistic** (fictitious name), a bike-share company in Chicago. Cyclistic is a bike-share program that features more than 5,800 bicycles and 600 docking stations. Cyclistic sets itself apart by also offering reclining bikes, hand tricycles, and cargo bikes, making bike-share more inclusive to people with disabilities and riders who can’t use a standard two-wheeled bike. The majority of riders opt for traditional bikes; about 8% of riders use the assistive options. Cyclistic users are more likely to ride for leisure, but about 30% use them to commute to work each day. Customers who purchase single-ride or full-day passes are referred to as casual riders. Customers who purchase annual memberships are Cyclistic members.

The director of marketing believes the company’s future success depends on maximizing the number of annual memberships. Therefore, my team wants to understand how casual riders and annual members use Cyclistic bikes differently. From these insights, my team will design a new marketing strategy to convert casual riders into annual members. But first, Cyclistic executives must approve the recommendations, so they must be backed up with compelling data insights and professional data visualizations.

### Purpose 
The purpose of analysis is to understand how annual members and casual riders use Cyclistic bikes differently?  The insights gained from this study will help to understand the behaviour and usage pattern of different category of customers. This will lead to creation of a focused marketing campaign based on these findings to convert casual riders into annual members. The study will analyze the Cyclistic historical bike trip data of last one year to identify trends. 

### Characters and teams
- **Cyclistic**: A bike-share program that features more than 5,800 bicycles and 600 docking stations. Cyclistic sets itself apart by also offering reclining bikes, hand tricycles, and cargo bikes, making bike-share more inclusive to people with disabilities and riders who can’t use a standard two-wheeled bike. The majority of riders opt for traditional bikes; about 8% of riders use the assistive options. Cyclistic users are more likely to ride for leisure, but about 30% use them to commute to work each day.<br>
- **Lily Moreno**: The director of marketing and your manager. Moreno is responsible for the development of campaigns and initiatives to promote the bike-share program. These may include email, social media, and other channels.<br>
- **Cyclistic marketing analytics team**: A team of data analysts who are responsible for collecting, analyzing, and reporting data that helps guide Cyclistic marketing strategy. You joined this team six months ago and have been busy learning about Cyclistic’s mission and business goals — as well as how you, as a junior data analyst, can help Cyclistic achieve them.<br>
- **Cyclistic executive team**: The notoriously detail-oriented executive team will decide whether to approve the recommended marketing program.

### Data Sources
Cyclistic’s historical [trip data](https://divvy-tripdata.s3.amazonaws.com/index.html) (last 12 months). The data is usable and is in .csv format. It has clean dates and times, with no outliers. It is relevant to the presented problem. The data has been made available by Motivate International Inc. under [this](https://www.divvybikes.com/data-license-agreement) license. This is public data that you can use to explore how different customer types are using Cyclistic bikes.

### [Major Project Activities](https://github.com/akgupta10/Google-Certification-Capstone-Project/blob/58670dc2833aad10b136d941dd51cbeb4e2bee4b/Steps.md)
- **[Ask Phase](https://github.com/akgupta10/Google-Certification-Capstone-Project/blob/main/Data%20Analysis%20Steps.md#1-ask)**:	Defining the problem, business task, and key stakeholders.
- **[Prepare Data](https://github.com/akgupta10/Google-Certification-Capstone-Project/blob/main/Data%20Analysis%20Steps.md#2-prepare)**:	Complete the process of data collection, required for analysis.
- **[Process Data](https://github.com/akgupta10/Google-Certification-Capstone-Project/blob/main/Data%20Analysis%20Steps.md#3-process)**:	Check the data for errors, identify tools to be employed for data cleaning and clean the data for analysis.
- **[Analyze Data](https://github.com/akgupta10/Google-Certification-Capstone-Project/blob/main/Data%20Analysis%20Steps.md#4-analyze)**:	Aggregate the data and perform calculations to identify trends and relationships.
- **[Share Phase](https://github.com/akgupta10/Google-Certification-Capstone-Project/blob/main/Data%20Analysis%20Steps.md#5-share)**:	Prepare data visualization supporting the trends identified using the chosen tool.
- **[Act Phase](https://github.com/akgupta10/Google-Certification-Capstone-Project/blob/main/Data%20Analysis%20Steps.md#6-act)**:	Recommendations based on your findings to be shared with the executive team.

### This project does not include
-	Trip data older than last one year.
-	Further analysis at individual customer level as Data-privacy issues prohibit using riders’ personally identifiable information.
-	Implementation of recommendations.

### Tools Used: R and Tableau.
The complete R code written for this case study can be accessed [here](https://github.com/akgupta10/Google-Certification-Capstone-Project/blob/4e8d60e67df0b7d4b099120f0882ed4854f89224/R-code.md).

#### The detailed step-wise analysis in R can be accessed [here](https://github.com/akgupta10/Google-Certification-Capstone-Project/blob/61cf8d11ea510942845970e1433d04ffdaa5a23d/R-code.md).

#### Detailed Vizualization in Tableau can be accessed here: [Tabealu Viz](https://public.tableau.com/views/CapstoneProjectViz/Dashboard2?:language=en-US&:display_count=n&:origin=viz_share_link) and [Tabealu Story](https://public.tableau.com/views/CyclisticBikes-CaseStudy/CaseStory?:language=en-US&:display_count=n&:origin=viz_share_link)

#### Conclusions/Insights 
  - Casual riders have less rides as compared to members but have higher average ride lengths.
  - Classic bike is the most preferred bike, followed by electric bike.
  - Casual riders prefer to ride on Weekends and around 5 PM in the evening.
  - The influx of casual riders is more in third quarter, which shows most of the casual riders are tourists/visitors.
  - The most popular station have more than twice the rides started from it as compared to the second most popular one.
  
#### Recommendations
  - The best time to launch the new marketing campaign are between 15:00 to 19:00, Weekends and Holidays, in the month of June to September. 
  - The promotion should be focused on Classic Bike. 
  - A targeted strategy at most popular station will reach the maximum number of Casual riders.
  - Introduce 2-day or weekly passes to attract more casual riders.
  - Health benefits of bike riding should be included in promotion.
 
 #### Acknowledgement
 Thanks to Google Data Analytics Professional Certificate provided by Coursera!
 
 **Thank you for checking out my project!**
