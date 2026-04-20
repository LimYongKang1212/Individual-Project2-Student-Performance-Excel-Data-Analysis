<h1 align="left">Student Performance Descriptive Analysis</h1>

###

<h2 align="left">Introduction</h2>

###

<p align="left">This report provides an in-depth analysis of student performance, based on data from Sling Academy, to uncover insights for better student development and strategic decision-making, using Exploratory Data Analysis and Data visualization in Excel.</p>

###

<h2 align="left">Objective</h2>

###

<p align="left">• To identify the key features that influence student performance<br><br>• To develop an interactive dashboard to monitor the real - time  student performance</p>

###

<h2 align="left">Dataset Description</h2>

<table align="center">
  <tr>
    <th>Attibute Name</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>ID</td>
    <td>Unique Student Identifier</td>
  </tr>
  <tr>
    <td>First_name</td>
    <td>Student’s first name</td>
  </tr>
  <tr>
    <td>Last_name </td>
    <td>Student’s last name</td>
  </tr>
  <tr>
    <td>Email</td>
    <td>Student’s Academy email</td>
  </tr>
  <tr>
    <td>Gender</td>
    <td>The gender of a student.</td>
  </tr>
  <tr>
    <td>Math_score</td>
    <td>Mathematics score (0-100) </td>
  </tr>
  <tr>
    <td>History_score</td>
    <td>History score (0 – 100)</td>
  </tr>
  <tr>
    <td>Physic_score</td>
    <td>Physic score (0 – 100)</td>
  </tr>
   <tr>
    <td>Chemistry_score</td>
    <td>Chemistry score (0 – 100)</td>
  </tr>
   <tr>
    <td>Biology_score</td>
    <td>Biology score (0 – 100)</td>
  </tr>
   <tr>
    <td>English_score</td>
    <td>English score (0 – 100)</td>
  </tr>
</table>

###

<h2 align="left">Data Preprocessing</h2>

###

<p align="left">Before analysing data, data preparation is required to ensure it is valid and easier to analyse. Data preparation also allows the analyser to identify additional hidden outcomes, thereby improving data accuracy. Data preparation for this project includes checking and removing duplicate and missing values, and feature engineering.</p>

###

<h4 align="left">1. Identify and Remove Missing Value</h4>

<p align="center"> <img width="466" height="248" alt="Image" src="https://github.com/user-attachments/assets/e52f129d-2035-4ea9-9271-1a1447e6c07f" /> </p>

###

<p align="left">The image shows that the total number of values in this dataset was 34000 (2000 data points × 17 columns). It can prove that there are no missing values in this dataset. Additionally, the formula “COUNTBLANK” can count the total number of missing values. The formula also proves that the number of missing values in this dataset was 0.</p>

###

<h4 align="left">2. Identify and Remove Duplicate Value</h4>

###
<p align="center"> <img width="400" height="350" alt="Image" src="https://github.com/user-attachments/assets/997af059-4e5a-4d3a-8cf2-5e12c906620d" /> </p>

<p align="center"> <img width="400" height="250" alt="Image" src="https://github.com/user-attachments/assets/46ad4ead-96d5-473b-a89c-585cae6de787" /> </p>

<p align="left">Remove Duplicates function was applied to remove duplicate records, and the result above shows that this dataset contains no duplicates.</p>

###

<h4 align="left">3. Feature Engineering</h4>

###

<p align="left">New features will be created to provide more meaningful and logical insight.</p>

<p align="center"> <img width="660" height="300" alt="Image" src="https://github.com/user-attachments/assets/b175d248-6397-49f5-ac12-751d1875d524"/> </p>
  
<p align="center"> <img width="660" height="300" alt="Image" src="https://github.com/user-attachments/assets/793735b1-e6fc-4584-8651-f965cf2a4e70" /> </p>

<p align="center"> <img width="660" height="300" alt="Image" src="https://github.com/user-attachments/assets/563b3648-0b9f-4986-b809-136fab5658ff" /> </p>

<p align="center"> <img width="660" height="300" alt="Image" src="https://github.com/user-attachments/assets/7a82b8d2-f828-4cec-af55-f1ee9a54e717" /> </p>

<p align="center"> <img width="660" height="300" alt="Image" src="https://github.com/user-attachments/assets/2df6d002-8e40-4870-a4f7-fa1abd7e9e1f" /> </p>

<p align="center"> <img width="660" height="300" alt="Image" src="https://github.com/user-attachments/assets/f12590b8-ee2e-474d-a812-ca4164469a6c" /> </p>

<p align="center"> <img width="660" height="300" alt="Image" src="https://github.com/user-attachments/assets/d4f61f1f-5ffd-4e13-8988-94cedd4d84e6" /> </p>

###

<h2 align="left">Data Finding And Analysis</h2>

###

<p align="left">1. Gender Distribution - 1002 students at Sling Academy were female,, while 998 were male.<br><br>2. Career Aspiration - 15 students dream of becoming software engineers, followed by business owners (309), and 223 students have not yet defined their career aspirations. Sling Academy suggested organising a counselling program to provide career guidance and suggestions based on the students' performance.<br><br>3. Subject Performance - Mathematics recorded the highest average score with 83.45. Then, it’s followed by Physics (81.34) and English (81.28). Biology had the lowest average score, at 79.58.<br><br>4. Overall Grade Distribution - Majority of the students in Sling Academy score A (993 students) and A- (560 students) for the overall result. The lower grades, like B- and C, are minimal, with 9 and 2 students, respectively.<br><br>5. Top 10 Students Performance - Top-performing students' scores of 95.00 to 96.14. The top students' continuously exceptional performance and the close gap in achievement at the highest level are demonstrated by the small score differences among them.<br><br>6. Part-Time Job Distribution - 84.20% of the students do not take any part-time job, whereas 316 students or 15.8% of 2000 students, have part-time jobs<br><br>7. Attendance Performance - Highest average score of 81.85 was reached by students with Excellent attendance, closely followed by those with Good attendance (81.28).Students with poor attendance, on the other hand, had a much lower average score of 78.01.<br><br>8. Extracurricular Activities Distribution - There are 1592 students, or 79.60% of the students do not take any extracurricular activities , whereas 408 students or 20.40% of 2000 students, have extracurricular activities.</p>

###

<h2 align="left">Data Visualization</h2>

###

<p align="left">This dashboard is divided into three parts: Profile Distributions, Academic Performance, and Behavior Analysis. 3 cards offer a quick overview of the overall interaction with student performance. Users can explore the data based on 5 criteria: gender, career aspirations, part-time job, extracurricular activities, and attendance performance.</p>

###

<h2 align="left">Recommendations</h2>

###

<p align="left">1. Tutorial programs - The institution is encouraged to conduct targeted tutorial or review classes for low-performing students and those with poor attendance.<br><br>2. Counselling & Support Services - Teachers or administrators need to engage with students who consistently miss class to identify the reasons behind the absences and provide mental support, whether academic or personal.<br><br>3. Increase engagement in extracurricular activities: The university should create and promote a broader range of activities to encourage greater student participation.</p>

###
