# bikesharing
UTMCC DataViz Module 14, NYC_CitiBike_Challenge

Tableau  
  [link to dashboard](LINK GOES HERE)

---

## Contents 
  * Overview
    - Purpose
    - Resources
  * Results
  * Summary
 

---  

## Overview 
  
  The project is in support of Kate, to generate a business presentation that supports establishing a bike share enterprise in Des Moines, IA. The source data on rides, customers and locations is from "NYC Citi Bike", already an operation in New York city. 

   ### Purpose
   To prepare a visualization business proposal that will use data-based dashboards and a data-analysis story to support creation of a new company for bicycle sharing/renting in Des Moines. Data is from the "NYC Citi Bike" bike-share business for August 2019, used as the model. Data handling and presentation Dashboards and Story building are created using the "Tableau Public" web-based software tool.
 
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
   Below are outlined the results of the Challenge Deliverable items.  
   

### Deliverable 1: Change Trip Duration to a Datetime Format


   | **Item** | **Examples from the Python, Jupyter Notebook code and results** |
   | :---: | :---: |
   | The code line used for the conversion and addition of a new column. | ![tripduration_dt_codeline.png](https://github.com/larrydodson/bikesharing/blob/main/tripduration_dt_codeline.png) |
   | Added new column within the df: tripduration_dt | ![tripduration_dt_table.png](https://github.com/larrydodson/bikesharing/blob/main/tripduration_dt_table.png) |
   | Confirming the data type of the new column.<br> and, Outputting a new csv file, without the df index. | ![citibike_datatypes.png](https://github.com/larrydodson/bikesharing/blob/main/citibike_datatypes.png) |
   
   
.

### Deliverable 2: Create Visualizations for the Trip Analysis

#### Visualizations showing:  (There are at least seven visualizations for the NYC Citibike analysis, and a description of the results for each visualization ).
  1. How long bikes are checked out for all riders and genders.
  2. How many trips are taken by the hour for each day of the week, for all riders and genders.
  3. A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.



   | **Item Description** | **Visualization sample** |
   | :---: | :---: |
   | **1. Line Graph displaying the number of Bikes checked out by duration for all Riders. Filtered by: the Hour ** | ![ChkoutDur_line.png](https://github.com/larrydodson/bikesharing/blob/main/ChkoutDur_line.png) |
   | **2. Line Graph displaying the number of Bikes that are checked out by duration for each Gender by the Hour. Filtered by: the Hour and Gender** | ![ChkoutDur_Gender_line.png](https://github.com/larrydodson/bikesharing/blob/main/ChkoutDur_Gender_line.png) |
   | **3. A Heatmap showing the number of Bike Trips for Each Hour of Each Day of the Week.** | ![TripWeekdayHr_heat.png](https://github.com/larrydodson/bikesharing/blob/main/TripWeekdayHr_heat.png) |
   | **4. A Heatmap showing the number of Bike Trips by Gender for Each Hour of Each Day of the Week. Filtered by Gender** | ![TripWeekdayHr_Gender_heat.png](https://github.com/larrydodson/bikesharing/blob/main/TripWeekdayHr_Gender_heat.png) |
   | **5. A Heatmap showing the number of Bike Trips for Each Type of User and Gender for Each Day of the Week. Filtered by: User and Gender** | ![TripWeekdayHr_User_Gender_heat.png](https://github.com/larrydodson/bikesharing/blob/main/TripWeekdayHr_User_Gender_heat.png) |
   | **6. ** | ![]() |
   | **7. ** | ![]() |

   

.


### Deliverable 3: Create a Story and Report for the Final Presentation




 
   | **Item** | **Viz** |
   | :---: | :---: |
   | **Story** | ![CitiBike_DashB1.png](https://github.com/larrydodson/bikesharing/blob/main/CitiBike_DashB1.png) |
   | **Report** | ![]() |
   | **7** | ![]() |
   | **8** | ![]() |  



<br>

---

# Summary

###  a high-level summary of the results 
   Abc def sllsl.


### Additional visualizations for future analysis (with the given dataset).
  1. abc 
  2. def 

   | **Item Description** | **Visualization** |
   | :---: | :---: |
   | **1. Average Trip Duration by Customer Type and Gender** | ![AveTripDur_CustGen_bar.png](https://github.com/larrydodson/bikesharing/blob/main/AveTripDur_CustGen_bar.png) |
   | **2. Most Popular Routes, by Top Ten Starting Locations** | ![Routes_StartEnd_bar.png](https://github.com/larrydodson/bikesharing/blob/main/Routes_StartEnd_bar.png) |



.

.end
