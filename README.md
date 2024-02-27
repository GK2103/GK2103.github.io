# GK2103.github.io 
## Skills
Python 
 
SQL

PowerBI

Java 
 
MATLAB 

XML 
 
Android Studios 



## Education
• Queen Mary University of London: Computing and Information Systems MSc (Merit)

• Queen Mary University of London: Mechanical Engineering (Graduated with a 1st Class)


  
## Projects

## Project 1: Sales and Customer Data Analysis and Visualization Project
[Link To GitHub Repository of Sales and Customer Data Analysis and Visualization Project](https://github.com/GK2103/Sales-and-Customer-Data-Analysis-Project)
##### Problem Area: 
This project involves analyzing dummy data for a company and its customer loyalty system. The analysis aims to present an update on sales performance, changes in customer behaviour, and data-driven insights and recommendations through a PowerBI dashboard and PowerPoint presentation, supported by evidence from the data.


##### Methodology: 

• Data Cleaning and Wrangling: Cleaned and wrangled the raw data in Excel to ensure data integrity and prepare it for analysis.

• Data Import to SQL: The cleaned data was exported as a CSV file and imported into SQL for further processing. SQL queries were then executed to extract relevant insights from the dataset.

• Data Analysis in SQL: SQL queries were utilized to analyze the data, uncovering patterns, trends, and correlations that provide valuable insights into sales performance and customer behaviour.

• Data Visualization with Power BI: The analysed data was exported from SQL and imported into Power BI for visualization. Power BI was used to create interactive visualizations, allowing for in-depth exploration of the data and presentation of key findings to stakeholders. Visualizations such as charts, graphs, and dashboards were employed to effectively communicate trends and patterns in the data.

##### Results:
Page 1:
![analysis on sales](https://github.com/GK2103/GK2103.github.io/assets/99646891/f94b6c5a-eb56-4a51-b0f7-53c90ba7ba26)
Page 2:
![customer analaysis](https://github.com/GK2103/GK2103.github.io/assets/99646891/6b339451-5085-4e90-bc78-9143a89e29f8)

##### Findings: (Full analysis can be found in the project report PDF):



## Project 2: Is A “Centre-Forward” Footballer’s Market Value Determined only by Their Statistics?:
[Link To GitHub Repository of Footballer Project](https://github.com/GK2103/Centre-Forward-Market-Value-Analysis)  

##### Problem Area: 
In professional football, there is an ongoing debate about how a player's market value is determined, especially for 'Centre-Forwards.' This study analyses the influence of goals and assists on the market value of the top 50 'Centre-Forwards' using the 'Most Expensive Footballers 2021' dataset.


##### Methodology: 
This project shows a range of data analyst skills and data-driven techniques while using essential Python libraries. 

•	Data Collection: The 'Most Expensive Footballers 2021' dataset was sourced from Kaggle.

•	Data Processing: Python was the primary language, utilising pandas for data manipulation and NumPy for numerical operations. Data cleaning ensured integrity, including creating the "Goals + Assists per match" metric.

•	Data Analysis/Machine learning Techniques: K-means clustering, and Linear Regression were employed to model the relationship between market value and performance statistics. The dataset was split into training and test data for linear regression.

•	Data Visualisation: Matplotlib was used for creating informative visualisations.

##### Results:
![Slide2](https://github.com/GK2103/GK2103.github.io/assets/99646891/8195b0e1-1619-4a43-bf13-dc8757552d5c)
![Slide3](https://github.com/GK2103/GK2103.github.io/assets/99646891/8e1f14be-2b32-4353-ac6a-db3fadd89982)

##### Findings: (Full analysis can be found in the project report PDF) 
The project's findings revealed that player performance statistics significantly affected the market values of footballers who were valued below £60 million, while higher-valued players above £130 million were influenced by a broader range of factors beyond statistics, such as age, league, and playing style. K-Means clustering provided additional insights by demonstrating that players with higher performance statistics tend to be valued more in the lower price range. The linear regression analysis indicated a small positive correlation (R-Value of 0.243) (Table 3) between market value and player performance statistics, although the model's fit was poor, as seen in Graph 2, suggesting a more complex relationship. In summary, while player statistics play a role in determining market values, their impact varies depending on a player's value range, highlighting the complex nature of football player valuation.



## Project 3: WeightLess Fitness App:

##### The Link to GitHub repository of the project (Containing the folder to download the app ): 
[Link To GitHub Repository of WeightLess App](https://github.com/GK2103/WeightLess)

##### Problem Area: 

This project aims to tackle the global obesity crisis as it been reported by EASO that obesity and being overweight is the 5th global cause of death (EASO, 2020). Despite abundant online information, misinformation and lack of motivation and engaging solutions hinder effective weight loss (Nakul, 2022). To combat this issue I created a Fitness app called "WeightLess". The Fitness app had a Calorie and Workout Tracker which required the need for a SQLite database and SQL queries to manipulate data within the SQLite database.

##### Methodology: 

The project introduces a mobile fitness app with educational features, goal setting, and tracking, as upon research they had shown promising user engagement results (Consagoustech, 2023). I implemented the app using Android Studios where XML was used for the Front End and for the Backend I mainly used java for the functionality of the app and SQL for the database.

Weight Less included many features: 

• Calorie Tracker – A feature used to track the daily calorie intake of the user, the details of which the user enters manually. The entry is stored in a separate SQLite database and displayed back to the user to see their progress.  

• Workout Tracker - A feature used to track the Workout the user has done, the details of which the user enters manually. The entry is stored in a separate SQLite database and displayed back to the user to see their progress.  

• Information Station – A feature aimed to educate the user on sustainable WeightLoss, Workout Routines and Meal plans.
  
• Calorie Goal Calculator – A feature that calculates a user’s caloric goal based on their biometric data.

##### Results:
![Slide4](https://github.com/GK2103/GK2103.github.io/assets/99646891/cb9d36e0-77a7-43bb-ab30-bc2134e71910)
![Slide5](https://github.com/GK2103/GK2103.github.io/assets/99646891/69227769-8518-4d7b-8338-56d0c0825f50)
![Slide6](https://github.com/GK2103/GK2103.github.io/assets/99646891/abd103a3-6385-4f97-ac16-8fe03340426b)
![Slide7](https://github.com/GK2103/GK2103.github.io/assets/99646891/890fde5a-7306-412b-896b-3d4b0829f8b3)

##### Implementation: 
 
Both tracking features were implemented by using an SQLite Database, and I wrote SQL queries using both Java and SQL to insert, edit and delete values in the database. Subsequently, I displayed this information to the user in an appealing format and provided functionality to modify or delete existing entries.

I created the "workoutdata" SQLite database within the DBHelper Java class, as can be observed in the Results section below, specifically on lines 9 and 10 of Figure 5. Next, I proceeded to create a table named "Workoutdata" using the .execSQL Java function, as demonstrated on line 16. This SQL query defined a table with columns for exercise, sets, reps, and weight, with the exercise column serving as the primary key.
 

1.	View Entries: Users click "Workout Tracker" on the home page and are taken to the “Workout Tracker” Page (seen in Figure 2) and can see their stored exercise entries.
   
2.	Add Exercise: They can add new exercises by clicking a green button, which takes them to an “Add Exercise” page (seen in Figure 3), When they submit this data, the "add_exercise" Java class captures the information and saves it using the "saveuserdata" method from the "DBhelper" class. This data is stored in the "workoutdata" database.
   
3.	Display Data: The "Workout_Diary" class retrieves data from the database via the "displaydata" and "getdata" methods found in the, storing it in ArrayLists.
   
4.	UI Population: An instance of "MyAdapter" formats the data for display in a RecyclerView, showing both new and previous entries.
   
5.	Edit/Delete Entries: Users can edit or delete entries by clicking them. In doing do they would be taken to the “Edit Exercise Log”. Editing updates data in the database using "updateuserdata," and deletion uses "deleteuserdata." Both these methods use a combination of both Java and SQL to manipulate the “Workoutdata” Table and change the entries that are saved in the table. 

Further details on the implementation and the code for the app can be found in the code file and the research paper written about the implementation effectiveness of the app

###### References:

Halford, J. (2020) Statistics, EASO. Available at: 	https://easo.org/media-portal/statistics/ (Accessed: January 17, 2023). 

Nakul (2022) Rise of misinformation in the fitness industry, TheSocialTalks. Available at: https://thesocialtalks.com/health/rise-of-misinformation-in-the-fitness-industry/?utm_content=cmp-true (Accessed: 24 May 2023). 

Consagoustech (2023) From download to delete: The real reasons fitness apps fail users, Medium. Available at: https://medium.com/@itsconsagous/from-download-to-delete-the-real-reasons-fitness-apps-fail-users-b2e86424163d (Accessed: 15 August 2023).



## Other Project:
COVID-19 Dashboard
[Link To GitHub Repository of COVID-19 Dashboard](https://github.com/GK2103/COVID-19DashBoard)

In my project, I make use of Python libraries, including pandas, numpy, and matplotlib, to analyse and visualise COVID-19 data pertinent to the UK. For Data Retrieval, I employed the uk-covid19 package, which enables the collection and organisation of data based on area type and selected metrics. This data is subsequently stored in JSON format and structured into DataFrames, ensuring efficient data handling. As part of Data Cleaning and Transformation, I performed tasks like date string conversion and age range parsing to enhance data quality. Notably, I had done some Data Visualization as I leveraged matplotlib to craft interactive visualisations and dynamic time series plots that empower users to track the evolving trends of COVID-19 statistics, encompassing cases, hospital admissions, and deaths, over time. The integration of interactive widgets, facilitated by ipywidgets, enriches the user experience, offering real-time data selection and scale adjustments delivering a comprehensive and interactive platform for COVID-19 data exploration and analysis.

![Slide8](https://github.com/GK2103/GK2103.github.io/assets/99646891/ad0e4e83-8603-47a3-968b-a8037bccdf5f) 













