# GK2103.github.io
### Skills
Python

SQL

Java
 
MATLAB 

XML

Android Studios 
 
### Education
• Queen Mary University of London: Computing and Information Systems MSc (Predicted Grade: 1st Class)

• Queen Mary University of London: Mechanical Engineering (Graduated with a 1st Class)
  
### Projects

#### Project: Is A “Centre-Forward” Footballer’s Market Value Determined only by Their Statistics?:
##### Link to GitHub repository of the project (Containing the code for the project and pdf of the project report):
[link](https://github.com/GK2103/Centre-Forward-Market-Value-Analysis)  

##### Problem Area: 
In professional football, there's ongoing debate about how a player's market value is determined, especially for "Centre-Forwards." This study uses data from the "Most Expensive Footballers 2021" dataset, which considers various factors like a player's performance and the league's competitiveness. We'll analyse the top 50 "Centre-Forwards" to assess how goals and assists significantly impact their market value.

##### Methodology: 
This project shows a range of data analyst skills and data-driven techniques while using essential Python libraries. 

• First, for data collection, I had sourced the "Most Expensive Footballers 2021" dataset from Kaggle. 

• Following this I had done rigorous data cleaning to ensure data integrity and consistency. Notably, during this process, I had combined a few data columns to create the "Goals + Assists per match" column, a key player performance metric. 

• Python served as the primary programming language, with essential libraries such as pandas for adept data manipulation, and numpy for precise numerical operations. 

• K-means clustering and Linear Regression were the two Machine learning techniques that were then deployed to model and evaluate the intricate relationship between market value and performance statistics. Where for linear Regression the the data set was spilt to create training data, to create a model, and test data to compare it against the model. 

• To further strengthen the analysis, I had done some data visualization with Python using matplotlib to present clear and informative visualisations and the pd.set_option for fine-tuning the display options.

##### Findings: (Full analysis can be found in the project report PDF) 
The project's findings revealed that player performance statistics significantly affect the market values of footballers who were valued below £60 million, while higher-valued players above £130 million are influenced by a broader range of factors beyond statistics, such as age, league, and playing style. K-Means clustering provided additional insights by demonstrating that players with higher performance statistics tend to be valued more in the lower price range. The linear regression analysis indicates a small positive correlation (R-Value of 0.243) (Table 3) between market value and player performance statistics, although the model's fit was poor, as seen in Graph 2, suggesting a more complex relationship. In summary, while statistics play a role in determining market values, their impact varies depending on a player's value range, highlighting the complex nature of football player valuation.

##### Results:
![Slide2](https://github.com/GK2103/GK2103.github.io/assets/99646891/133679ee-198f-4f54-9c45-1f66ec6bb9e5)
![Slide3](https://github.com/GK2103/GK2103.github.io/assets/99646891/8c0e9440-25a8-4b9f-8994-7a989d82815f)
  
#### Project: WeightLess Fitness App:

##### The Link to GitHub repository of the project (Containing the folder to download the app ): 
[project repository](https://github.com/GK2103/WeightLess)

##### Problem Area: 

This project aims to tackle the global obesity crisis as it been reported by EASO that obesity and being overweight is the 5th global cause of death (EASO, 2020). Despite abundant online information, misinformation and lack of motivation and engaging solutions hinder effective weight loss (Nakul, 2022). To combat this issue i Created a Fitness app called "WeightLess". The Fitness app had a Calorie and Workout Tracker which required the need for an SQLite database and SQL queries to manipulate data within the SQLite database.

###### References:

Halford, J. (2020) Statistics, EASO. Available at: 	https://easo.org/media-portal/statistics/ (Accessed: January 17, 2023). 

Nakul (2022) Rise of misinformation in the fitness industry, TheSocialTalks. Available at: https://thesocialtalks.com/health/rise-of-misinformation-in-the-fitness-industry/?utm_content=cmp-true (Accessed: 24 May 2023). 

Consagoustech (2023) From download to delete: The real reasons fitness apps fail users, Medium. Available at: https://medium.com/@itsconsagous/from-download-to-delete-the-real-reasons-fitness-apps-fail-users-b2e86424163d (Accessed: 15 August 2023). 

##### Methodology: 

The project introduces a mobile fitness app with educational features, goal setting, and tracking, as upon research they had shown promising user engagement results (Consagoustech, 2023). The App was implemented using Android Studios where XML was used for the Front End. The Backend used was mainly java for the functionality of the app and SQL for the database.

Weight Less included many features: 

• Calorie Tracker – A feature used to track the daily calorie intake of the user, the details of which the user enters manually. The entry is stored in a separate SQLite database and displayed back to the user to see their progress.  

• Workout Tracker - A feature used to track the Workout the user has done, the details of which the user enters manually. The entry is stored in a separate SQLite database and displayed back to the user to see their progress.  

• Information Station – A feature aimed to educate the user on sustainable WeightLoss, Workout Routines and Meal plans.
  
• Calorie Goal Calculator – A feature that calculates a user’s caloric goal based on their biometric data.


##### Implementation: 
Both tracking features worked by using a SQLite Database and writing SQL queries using both Java and SQL to write values into the database and then displaying this back to the user in an appealing format as well as changing and deleting pre-existing data/Enteries made.  

The “workoutdata” SQLite database was created in the DBHelper java class, as seen in the Results section below, line 9 and 10 of Figure 5. Then a table was created called “Workoutdata” using the .execSQL Java function by writing an SQL query on line 16. The query creates a table having columns for exercise, sets, reps and weight where exercise is the primary key. 


1.	View Entries: Users click "Workout Tracker" on the home page and are taken to the “Workout Tracker” Page (seen in Figure 2) and can see their stored exercise entries.
   
2.	Add Exercise: They can add new exercises by clicking a green button, which takes them to an “Add Exercise” page (seen in Figure 3), When they submit this data, the "add_exercise" Java class captures the information and saves it using the "saveuserdata" method from the "DBhelper" class. This data is stored in the "workoutdata" database.
   
3.	Display Data: The "Workout_Diary" class retrieves data from the database via the "displaydata" and "getdata" methods found in the, storing it in ArrayLists.
   
4.	UI Population: An instance of "MyAdapter" formats the data for display in a RecyclerView, showing both new and previous entries.
   
5.	Edit/Delete Entries: Users can edit or delete entries by clicking them. In doing do they would be taken to the “Edit Exercise Log”. Editing updates data in the database using "updateuserdata," and deletion uses "deleteuserdata." Both these methods use a combination of both Java and SQL to manipulate the “Workoutdata” Table and change the entries that are saved in the table. 

Further details on the implementation and the code for the app can be found in the code file and the research paper written about the implementation effectiveness of the app

##### Results:
![Slide4](https://github.com/GK2103/GK2103.github.io/assets/99646891/361540c9-eaf3-4bc5-81b7-f5fcfaedba83)
![Slide5](https://github.com/GK2103/GK2103.github.io/assets/99646891/34087a55-8a21-4d9e-87dc-6f3a937b3f71)

### Other Project:
COVID-19 Dashboard


### Work Experience
#### Store Assistant at Subra Enterprises: Convenience Store

• Led the successful integration of the store onto a well-established online platform within a set deadline and
analysed store data to identify the most popular, restocked, and frequently co-purchased items to advertise,
resulting in a 5% increase in monthly sales.

• Collaborated effectively with a sales team to offer products and deliver exceptional customer service, honing
communication and teamwork skills.

#### Property Management Intern at London Quays: Property Firm

• Acquired significant experience in client relations and interpersonal communication through shadowing
various landlords and interacting with clients in person. 

• Demonstrated effective organisational and managerial skills by efficiently managing company schedules and
coordinating appointments.






