**Tools Used**: R and Tableau.
The complete R code written for this case study can be accessed [here](https://github.com/akgupta10/Google-Certification-Capstone-Project/blob/4e8d60e67df0b7d4b099120f0882ed4854f89224/R-code.md).

## Major Project Activities / Data Analysis Steps:

###  ❓ [Ask](#1-ask)
### 💻 [Prepare](#2-prepare)
### 🛠  [Process](#3-process)
### 📊 [Analyze](#4-analyze)
### 📋 [Share](#5-share)
### 🚲 [Act](#6-act)

## Details
### 1. Ask
- **Business Task:** Recommend marketing strategies aimed at converting casual riders into annual members by better understanding how annual members and casual riders use Cyclistic bikes differently.
- **Stakeholder(s):** Lily Moreno, director of marketing and Cyclistic executive team.
<br> *Persona1: **Lily Moreno**. Persona2: **Terrence**, Executive Team Member*  
<img src="https://user-images.githubusercontent.com/98569224/172294266-52845b66-ee85-4f2b-8d20-e3ee431d722a.jpg" width="900" height="700">  

<img src="https://user-images.githubusercontent.com/98569224/172295342-255c862f-c63a-4957-a871-00f8bf95b439.jpg" width="900" height="700"> <br>  
- **Subject-Matter Experts:** Cyclistic marketing analytics team: A team of data analysts who are responsible for collecting, analyzing, and reporting data that helps guide Cyclistic marketing strategy.

### 2. Prepare
- **Data Source:** Cyclistic’s historical [trip data](https://divvy-tripdata.s3.amazonaws.com/index.html) (last 12 months). The data is usable and is in .csv format.
The data is organized in monthly files. January 2021 to december 2021 data is employed for analysis purpose.
- **ROCCC:** The data is Reliable, Original, Comprehensive, Current and Cited. The data has been made available by Motivate International Inc. under [this](https://www.divvybikes.com/data-license-agreement) license.
- **Limitation:** Data-privacy issues prohibit you from using riders’ personally identifiable information. This means that you won’t be able to connect pass purchases to credit card numbers to determine if casual riders live in the Cyclistic service area or if they have purchased multiple single passes. 
 
The **R** code related to this step can be accessed [here](https://github.com/akgupta10/Google-Certification-Capstone-Project/blob/main/R-code.md#step-1-collect-data).

### 3. Process
- **Choose Tools:** The combined size of all the 12 datasets is close to 1 GB. Data cleaning in spreadsheet will be time-consuming and slow compared to SQL or R. I am choosing R simply because I could do both data wrangling and analysis even visualizations in the same platform.
- **Transform the data:** Involves the processes such as data migration, data warehousing, data integration, and data wrangling.
- **Check the data for errors** 
- **Clean the data**
- **Document the cleaning process** <br>  

The **R** code related to this step can be accessed [here.](https://github.com/akgupta10/Google-Certification-Capstone-Project/blob/main/R-code.md#step-2-clean-up-and-add-data-to-prepare-for-analysis)  

### 4. Analyze
- Aggregate the data and perform calculations to identify trends and relationships
  - [Rides distribution](https://github.com/akgupta10/Google-Certification-Capstone-Project/blob/main/R-code.md#1-rides-distribution)
  - [The summary statistics on the ride length](https://github.com/akgupta10/Google-Certification-Capstone-Project/blob/main/R-code.md#2-the-summary-statistics-on-the-ride-length)
  - [Analysis of Bike type](https://github.com/akgupta10/Google-Certification-Capstone-Project/blob/main/R-code.md#3-analysis-of-bike-type)
  - [Descriptive analysis on the station](https://github.com/akgupta10/Google-Certification-Capstone-Project/blob/main/R-code.md#4-descriptive-analysis-on-the-station)

The **R** code related to this step can be accesed [here.](https://github.com/akgupta10/Google-Certification-Capstone-Project/blob/main/R-code.md#step-3-conduct-descriptive-analysis)

### 5. Share
- **Create effective data visualizations:** Prepare data visualization supporting the trends identified using the chosen tool, Tableau.  
🎨 **Access complete [Tabealu Viz](https://public.tableau.com/views/CapstoneProjectViz/Dashboard2?:language=en-US&:display_count=n&:origin=viz_share_link)**    

![Dashboard 1](https://user-images.githubusercontent.com/98569224/172636138-1858afef-2ced-411a-aa02-e56d726c7da7.jpg)

![Dashboard 2](https://user-images.githubusercontent.com/98569224/172636534-f2087131-4f71-433a-b7ef-748e34a5f1b0.jpg)

![Dashboard 3](https://user-images.githubusercontent.com/98569224/172636565-eb84b273-04ce-4e8e-90d4-def02e84d1c5.jpg)

![Dashboard 4](https://user-images.githubusercontent.com/98569224/172636601-264e4408-fd8a-4ef3-8f65-2b7f1c310ef6.jpg)

- **Present the findings:** Using Story Points in Tableau  
🎨 **[Tabealu Story](https://public.tableau.com/views/CyclisticBikes-CaseStudy/CaseStory?:language=en-US&:display_count=n&:origin=viz_share_link)**  

### 6. Act
- **Conclusions/Insights** gained from the analysis - 
  - Casual riders have less rides as compared to members but have higher average ride lengths.
  - Classic bike is the most preferred bike, followed by electric bike.
  - Casual riders prefer to ride on Weekends and around 5 PM in the evening.
  - The influx of casual riders is more in third quarter, which shows most of the casual riders are tourists/visitors.
  - The most popular station have more than twice the rides started from it as compared to the second most popular one.
  
- **Recommendations**
  - The best time to launch the new marketing campaign are between 15:00 to 19:00, Weekends and Holidays, in the month of June to September. 
  - The promotion should be focused on Classic Bike. 
  - A targeted strategy at most popular station will reach the maximum number of Casual riders.
  - Introduce 2-day or weekly passes to attract more casual riders.
  - Health benefits of bike riding should be included in promotion.


