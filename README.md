
# Sales Insights Power BI Project

This project is centred on a computer hardware company that is confronting issues in a rapidly changing market. The sales director chooses to invest in a data analysis project and wants to create a Power BI dashboard that will provide him with real-time sales insights.

# Sales-Dashboard

[Sales - Dashboard](https://github.com/Ayangroy13/Test/blob/main/Ayan_Project_One.pbix)

## Problem Statement

Here in this dashboard we've created a strategic framework to address Atliq Hardware's sales insights challenge, using advanced data mining and analytics techniques specific to their Excel dataset. We've created an integrated system that not only effectively processes and cleanses data, but also employs powerful machine learning algorithms to reveal hidden patterns, forecast future sales trends, and offer personalised marketing strategies. The solution should provide decision-makers with actionable information, resulting in increased revenue and market competitiveness for Atliq.



### Steps followed 

- Step 1 : Load data into Power BI Desktop and MySQL
- Step 2 : We analyze the data into the MySQL 
![Transaction Data](https://github.com/Ayangroy13/Test/assets/165015521/55dd3727-bf1c-4172-8d02-a8f2a77566a0)

- Step 3 : Open power query editor & do some data cleaning and ETL.



# Snapshot of Dashboard (Power BI Service)
![photo_2024-03-29_13-09-44](https://github.com/Ayangroy13/Test/assets/165015521/5ba53937-6f20-4060-ab0f-669598411b25)

![photo_2024-03-29_13-09-48](https://github.com/Ayangroy13/Test/assets/165015521/f0019e7f-8b28-4ddb-b958-c3d0d9ca721f)

![photo_2024-03-29_13-09-52](https://github.com/Ayangroy13/Test/assets/165015521/25e1bcf4-138b-4597-b256-104447058bbb)


# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1] Total Number of Customers = 129880

   Number of satisfied Customers (Male) = 28159 (21.68 %)

   Number of satisfied Customers (Female) = 28269 (21.76 %)

   Number of neutral/unsatisfied customers (Male) = 35822 (27.58 %)

   Number of neutral/unsatisfied customers (Female) = 37630 (28.97 %)


           thus, higher number of customers are neutral/unsatisfied.
           
### [2] Average Ratings

    a) Baggage Handling - 3.63/5
    b) Check-in Service - 3.31/5
    c) Cleanliness - 3.29/5
    d) Ease of online booking - 2.88/5
    e) Food & Drink - 3.21/5
    f) In-flight Entertainment - 3.36/5
    g) In-flight service - 3.64/5
    h) In-flight Wifi service - 2.81/5
    i) Leg room service - 3.37/5
    j) On-board service - 3.38/5
    k) Online boarding - 3.33/5
    l) Seat comfort - 3.44/5
    m) Departure & arrival convenience - 3.22/5
  
  while calculating average rating, null values have been ignored as they were not relevant for some customers. 
  
  These ratings will change if different visual filters will be applied.  
  
  ### [3] Average Delay 
  
      a) Average delay in arrival(minutes) - 15.09
      b) Average delay in departure(minutes) - 14.71
Average delay will change if different visual filters will be applied.

 ### [4] Some other insights
 
 ### Class
 
 1.1) 47.87 % customers travelled by Business class.
 
 1.2) 44.89 % customers travelled by Economy class.
 
 1.3) 7.25 % customers travelled by Economy plus class.
 
         thus, maximum customers travelled by Business class.
 
 ### Age Group
 
 2.1)  21.69 % customers belong to '0-25' age group.
 
 2.2)  52.44 % customers belong to '25-50' age group.
 
 2.3)  25.57 % customers belong to '50-75' age group.
 
 2.4)  0.31 % customers belong to '75-100' age group.
 
         thus, maximum customers belong to '25-50' age group.
         
### Customer Type

3.1) 18.31 % customers have customer type 'First time'.

3.2) 81.69 % customers have customer type 'returning'.
       
       thus, more customers have customer type 'returning'.

### Type of travel

4.1) 69.06 % customers have travel type 'Business'.

4.2) 30.94 % customers have travel type 'Personal'.

        thus, more customers have travel type 'Business'.
