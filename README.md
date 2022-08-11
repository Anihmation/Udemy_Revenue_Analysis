# UDEMY_REVENUE_ANALYSIS
![download](https://user-images.githubusercontent.com/78387629/183259440-fc80e63d-cb6c-4142-80c5-ccd93718373d.jpg)
 ## PROJECT DESCRIPTION
The Project data collected consists of four different Courses namely:
Data Sheet Udemy Courses - Business Courses - an XLSX file of 1193 rows; Data Sheet Udemy Courses - Design Courses – a CSV file of 604 rows; Data Sheet Udemy Courses - Music Courses – a CSV file of 681rows; Data Sheet Udemy Courses - Web Development – a CSV file of 1198 rows.
With all the entries under 12 columns – “Course ID”, “Course Title”, “Url”, “Price”, “Num of Subscribers”, “Num of Reviews”, “Num of Lectures”, “Level”, “Rating”, “Content Duration”, “Published Timestamp” and “Subject”.
I consolidated the data into one Xlsx file via extracting, cleaning, and transforming the given data to get it ready for the analysis. I used Microsoft Excel to carry out the ETL (Extract, Transform and Load), Data query, EDA (Exploratory Data Analysis) and Visualization.
_____________________
## DATA SOURCE
The Data used is from Github. Links below:
- https://github.com/Fabulousnani/Data-Developer-Bootcamp/blob/main/Data_Sheet_Udemy_Courses_-_Business_Courses.xlsx 
- https://github.com/Fabulousnani/Data-Developer-Bootcamp/blob/main/Data_Sheet_Udemy_Courses_-_Design_Courses.csv
- https://github.com/Fabulousnani/Data-Developer-Bootcamp/blob/main/Data_Sheet_Udemy_Courses_-_Music_Courses.csv
- https://github.com/Fabulousnani/Data-Developer-Bootcamp/blob/main/Data_Sheet_Udemy_Courses_-_Web_Development.csv
______________________

## PROBLEM STATEMENT
The Business problem is the growth of the business revenue over the courses offered. Through my analysis, I want to arrive at offering workable solution to increase the next quarterly earnings of the Company.
______________
## RESEARCH QUESTION
A research question from the Problem Statement: If Price of courses are increased, will it assure more revenue for the company?
___________
## HYPOTHESIS
The increase of price of a course with the highest demand i.e., Subscribers is likely to affect the company’s revenue positively once content reviews remain positive.
________
## DATA DESIGN/METHODOLOGY
I extracted the data from a GitHub account and loaded it to my workspace, hence the Data Lake was created as a folder in my desktop.
- I made use of Microsoft Excel in the Data consolidation, exploring the raw files, transforming, and loading the data. Afterwards, I appended the Data to one workbook, cleaned run data queries, exploratory data analysis (EDA) and Visualizations.
-	I keenly wrangled the Appended Data as it wasn’t that clean. I took away duplicates and empty rows and other several functions to get the valid entries. This process reduced the number of rows in the data of just two data given by 2 to 3 rows down.
-	Afterwards, I included 4 extra columns that helped in my analysis namely: Published Date”, “Free or Paid” to determine the Paid courses; “Beginner Course Status” to basically ascertain beginners who paid; “Revenue” to ascertain the generated revenue so far.
-	While doing all this, I sorted by highest number of Subscribers to ascertain the most in demand course. All these helped in my process of get more insights and arriving at a conclusion.
____
## FINDINGS AND DATA ANALYSIS
![UDEMY SUBJECT DASHBOARD](https://user-images.githubusercontent.com/78387629/183259301-599ec86d-cac1-4cfe-a553-80543dd0068d.jpg)
-	I found out that Web Development has the most subscribers and generates the most revenue, 63% of the company’s revenue.
-	I found out that Musical Instrument is the Course with the least subscribers and as well generates the least revenue, just a 9% of the company’s revenue.
-	I also found Web Development with the highest content duration couldn’t deter Subscribers from subscribing proves its content rich. 
-	The course, Graphics design outperformed every other course in rating, reveals Subscribers interest is high on it.
______________
## RECOMMENDATION
-	Based on my crucial findings I highly recommend that Web Development having the interest of the target audience, it is a course, the price should be reviewed and increased a little.
-	As well, Graphics Design course content alongside the price of its courses reviewed.
_________
###### As a Student in a Data Developer Bootcamp, I have been given a task to run a data analysis on Udemy Course Revenue. Disclaimer: This is purely for an Educational purpose, a trial project to mark my learning journey and has nothing to do with Udemy. 
 _________________________________________________________________________________________
