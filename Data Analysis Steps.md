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
