# Bike_Sharing
UTMCC DataViz Module 14, NYC_CitiBike_Challenge

## Title: NYC Citibike Analysis as a Study for a New Business in Des Moines 

| Link to the Story at Tableau Public: |
| :--- |
|  [https://public.tableau.com/profile/larry.dodson#!/vizhome/NYCCitibikeAnalysisStoryPresentation/NYCCityBikeStory?publish=yes](https://public.tableau.com/profile/larry.dodson#!/vizhome/NYCCitibikeAnalysisStoryPresentation/NYCCityBikeStory?publish=yes) |


---

## Contents 
  * Overview and Purpose
    - Resources
  * Results
  * Summary
 

---  

## Overview and Purpose 
  
  The project is to generate a business proposal with visuals that supports establishing a new bike-share company in Des Moines, Iowa. 
  
  The presentation materials of the proposal include several key data visualizations of graphs and charts, and are used to create dashboards and a data-analysis Story. The reference source data is from the "NYC Citibike" bike-share business, for August 2019, and includes information on the number of rides, customers demographics, and stations' locations. Overall, the data is used as a comparison with a similar like-business. Data handling and presentation Dashboards and Story building are created using the "Tableau Public" web-based software tool.
 
   The deliverables are: 
   - Deliverable 1: Change Trip Duration to a Datetime Format
   - Deliverable 2: Create Visualizations for the Trip Analysis
   - Deliverable 3: Create a Story and Report for the Final Presentation
   

   ### Resources
  * Data/content source file: 201908-citibike-tripdata.csv
  * Software: Windows10, Python 3.8.3, Jupyter Notebook, VS Code 1.49.1, Tableau Public 
  
<br>

--- 

## Results
   Below are the results of the Challenge Deliverable items.  
   

### Deliverable 1: Change Trip Duration to a Datetime Format


   | **Item** | **Examples from the Python, Jupyter Notebook code and results** |
   | :---: | :---: |
   | The code line used for the conversion and addition of a new column. | ![tripduration_dt_codeline.png](https://github.com/larrydodson/bikesharing/blob/main/tripduration_dt_codeline.png) |
   | Added new column within the dataframe: tripduration_dt | ![tripduration_dt_table.png](https://github.com/larrydodson/bikesharing/blob/main/tripduration_dt_table.png) |
   | Confirming the data type of the new column.<br> and, Outputting a new csv file, without the df index. | ![citibike_datatypes.png](https://github.com/larrydodson/bikesharing/blob/main/citibike_datatypes.png) |
   
 
.

### Deliverable 2: Create Visualizations for the Trip Analysis

#### Visualizations for the NYC Citibike analysis, and a description of the results for each visualization.


   | **Item Description** | **Visualization** |
   | :--- | :---: |
   | **1. A Line Graph displaying the number of Bikes checked out by duration for all Riders. <br> Filtered by: the Hour** | ![ChkoutDur_line.png](https://github.com/larrydodson/bikesharing/blob/main/ChkoutDur_line.png) |
   | **2. Line Graphs displaying the number of Bikes that are checked out by duration for each Gender by the Hour. <br> Filtered by: the Hour and Gender** | ![ChkoutDur_Gender_line.png](https://github.com/larrydodson/bikesharing/blob/main/ChkoutDur_Gender_line.png) |
   | **3. A Heatmap showing the number of Bike Trips for Each Hour of Each Day of the Week.** | ![TripWeekdayHr_heat.png](https://github.com/larrydodson/bikesharing/blob/main/TripWeekdayHr_heat.png) |
   | **4. A Heatmap showing the number of Bike Trips by Gender for Each Hour of Each Day of the Week. <br> Filtered by Gender** | ![TripWeekdayHr_Gender_heat.png](https://github.com/larrydodson/bikesharing/blob/main/TripWeekdayHr_Gender_heat.png) |
   | **5. A Heatmap showing the number of Bike Trips for Each Type of User and Gender for Each Day of the Week. <br> Filtered by: User and Gender** | ![TripWeekdayHr_User_Gender_heat.png](https://github.com/larrydodson/bikesharing/blob/main/TripWeekdayHr_User_Gender_heat.png) |
   | **6. A Bar Chart displaying the Peak Hours of Bike Checkout for All Riders. <br> Highlighting the peak hours for days in August 2019 were from 3:00PM to 8:00PM.** | ![Aug_PeakHrsDay_bar.png](https://github.com/larrydodson/bikesharing/blob/main/Aug_PeakHrsDay_bar.png) |
   | **7. An Area Graph, showing the Average Trip Duration by Customer Age and by Gender. <br> The Graph indicates a balance between the three sub-groups.** | ![AveTripDur_AgeGen_area.png](https://github.com/larrydodson/bikesharing/blob/main/AveTripDur_AgeGen_area.png) |


.


### Deliverable 3: Create a Story and Report for the Final Presentation

 
   | **Story** | **Visualization** |
   | :--- | :---: |
   | **1.**  Total number of Rides = 2,344,224.  <br>- Aug is a busy month, with higher tourist traffic. <br>- Ave trip duration is higher with younger riders. <br>- By Users, or Riders, most are Subscribers, and most are Males. <br>- The Peak Hours in a given day are from 3PM to 8PM. <br>- There are 1,000s of Starting and respective Ending locations. | ![CitiBike_DashB1.png](https://github.com/larrydodson/bikesharing/blob/main/CitiBike_DashB1.png) |
   | **2.**  Customers: Info to help predict User Profiles <br>- Subscribers are >4 times the no. of non-Subscribers. <br>- Ave Trip Duration is higher with Females, and also non-Subscribers (Customers), with much higer Trip Durations. | ![CitiBike_DashB2.png](https://github.com/larrydodson/bikesharing/blob/main/CitiBike_DashB2.png) | 
   | **3.**  A balance exists at a higher no. of Male Users, with longer Trips by Females Users. <br>- The most used times/days are also by the highest overall Users, Males, with Peak Times on Thurs and Fridays, and next busiest on Mon and Tues.  | ![CitiBike_DashB3.png](https://github.com/larrydodson/bikesharing/blob/main/CitiBike_DashB3.png) | 
   | **4.**  A Focus on Trip Routes will allow for good Planning and inventory locations for equipment. <br>- There are thousands of Starting and Ending locations, with most as the same location. | ![CitiBike_DashB4.png](https://github.com/larrydodson/bikesharing/blob/main/CitiBike_DashB4.png) |    
   | **5.**  Bicycle Usage tracking can be used in preparation planning for Maintenance as a Major Cost. <br>- Other major costs are likely to be: Initial Capital Equipment, Labor, Storage, Licensing fees, Training, Insurance. <br>- With unique I.D.s on equipment, Maintenance and Inventory locations can be tracked and updated, to plan for cost of these items, and most efficient locations. | ![CitiBike_DashB5.png](https://github.com/larrydodson/bikesharing/blob/main/CitiBike_DashB5.png) |


<br>

---

# Summary

####  Using the information from NYC Citibike is very valuable in planning for a new company to do similar business in Des Moines. Although Des Moines if very different from NYC, the overall business plan can benefit from using this information properly. From it we can estimate Users (customers), Lengths of time of checkouts by Users, the equipment types and quantities, and the locations. <br> What is needed to complete a business plan are costs of doing business, including the capital equipment, maintenance and repairs, insurance, licensing and permits, legal costs for set up and protections, and to arrive at a target rental fee structure. 


### Additional visualizations for future analysis (with the given dataset).
  Please see the table below: 
  

   | **Item Description** | **Visualization** |
   | :--- | :---: |
   | **1. Average Trip Duration by Customer Type and Gender** <br> A further deep-dive into the customer, and the reasons for using the services would be helpful to maintain competitiveness to reach profitability and against other similar competing services.  | ![AveTripDur_CustGen_bar.png](https://github.com/larrydodson/bikesharing/blob/main/AveTripDur_CustGen_bar.png) |
   | **2. Most Popular Routes, by Top Ten Starting Locations** <br> Additional and more complete information on the most popular or used bike routes would be helpful in planning for equipment usage, durations, and inventory locations, and service team member locations. | ![Routes_StartEnd_bar.png](https://github.com/larrydodson/bikesharing/blob/main/Routes_StartEnd_bar.png) |
   
.

.end
