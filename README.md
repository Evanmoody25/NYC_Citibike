# NYC_Citibike

# Overview of Project 

Now that we've gotten a good idea of how to create our story, there is still some more work to be done to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis.

For this analysis, I will use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, you’ll create a set of visualizations to:

-Show the length of time that bikes are checked out for all riders and genders

-Show the number of bike trips for all riders and genders for each hour of each day of the week

-Show the number of bike trips for each type of user and gender for each day of the week.

# index 

-Deliverable 1: Change Trip Duration to a Datetime Format

-Deliverable 2: Create Visualizations for the Trip Analysis

-Deliverable 3: Create a Story and Report for the Final Presentation

-Written Analysis

# Tools

-Jupyter Notebook, CSV, and Tableau

# Deliverable 1

Using Python and Pandas functions, you’ll convert the "tripduration" column from an integer to a datetime datatype to get the time in hours, minutes, and seconds (00:00:00). After you convert the "tripduration" column to a datetime dataytpe, you’ll export the DataFrame as a CSV file to use for the trip analysis in Deliverable 2.

Here lies the code I used in Jupyter Notebook to convert "tripduration."

![Python_pandas](https://user-images.githubusercontent.com/89880015/145671743-e3bc1905-6675-48c4-8369-eb11033ff0e4.PNG)

Here lies the results of the code.

![tripduration_updated](https://user-images.githubusercontent.com/89880015/145671825-342faec0-35ca-4e8f-afae-df9255e02541.PNG)

# Deliverable 1 Requirments 

-The data in the "tripduration" column is converted to a datetime datatype and has the correct time format (15 pt)

-The DataFrame is exported as a new file without the index column (5 pt) 

# Deliverable 2

Using Tableau, create visualizations that show:

-How long bikes are checked out for all riders and genders.

-How many trips are taken by the hour for each day of the week, for all riders and genders.

-A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.

# Checkout Times for Users

![Checkout_for_users](https://user-images.githubusercontent.com/89880015/145672009-237ec51a-3371-49de-bfdc-f5a7c408cb13.PNG)

# Checkout Times by Gender

![Checkout_by_gender](https://user-images.githubusercontent.com/89880015/145672018-3ad02d48-c4fa-42db-9026-6b8e2f6588f7.PNG)

# Trips by Weekday

![Trips_by_gender](https://user-images.githubusercontent.com/89880015/145672035-dfdfebd2-0a4e-45e1-92ef-49d6479045a7.PNG)

# Trips by Gender

![Trips_by_Gender_week_hour](https://user-images.githubusercontent.com/89880015/145672053-85dd6d75-93ba-4d1d-bfdb-04e475f371c4.PNG)

# User trips by gender by weekday

![Trips_by_gender_by_weekday](https://user-images.githubusercontent.com/89880015/145672068-91a26e0f-4283-4dda-ae9f-48750e10cfbe.PNG)

# Deliverable 2 Requirements:

-There is a line graph displaying the number of bikes checked out by duration for all users, and the graph can be filtered by the hour (10 pt)

-There is a line graph displaying the number of bikes that are checked out by duration for each gender by the hour, and the graph can be filtered by the hour and gender (10 pt)

-A heatmap is created showing the number of bike trips for each hour of each day of the week (10 pt)

-A heatmap is created showing the number of bike trips by gender for each hour of each day of the week, and the heatmap can be filtered by gender (10 pt)

-A heatmap is created showing the number of bike trips for each type of user and gender for each day of the week, and you can only filter by user and gender (10 pt)

# Deliverable 3 (the link to the story can be found on the main branch of the repository, my findings will be posted there as well)

For this part of the Challenge, you’ll create a story in Tableau and write a report that describes the key outcomes of the NYC Citibike analysis you did in the module and in Deliverable 2.

Follow the instructions below to complete Deliverable 2.

In Tableau, create a new Story using visualizations that will support the key findings you want to show.

You must use the five visualizations that you created in Deliverable 2.

# analysis

- We know that the majority of rides take place whithin the first hour and do not go over. This leads me to believe that, when matched with the spikes in usage during to and from work commutes, that the bikes are being used to travel to and from one's occupation. 

- The majority of our users ae men, in what ways can we boost our customers and subscriptions by making our product more attractive to females? 

- There is also a spike in usage during the weekend. 

- There is also about 80% subscriptions and 20% customers. 

# summary 

- I believe the next best study that can be done is where are the bikes being checked out the most. I want to know if there is a high spike near residential areas and near areas of occupation. Living in a city presents bikes the opportunity to overtake cars due to their inherent advantage of not needing a parking space and not needing to put up with city traffic. Perhaps we can maximize profit by locating our bike terminals near residential and occupational locations. 

- Second, we need to see how weather affects the bikes' popularity. New York can be an extreme city. Having fewer bikes out during the cold months may allow us to cut back on maintanence costs by removing the bikes from the elements and sporatic usage when marginal cost is greater then the marginal benefit. 

- I also am fixated on the high rate of men using the bikes compared to women. Does fear of crime prevent women from using the bikes? What else may be causing the stark divide? 

# Deliverable 3 Requirements

You will earn a perfect score for Deliverable 3 by completing all requirements below:

Structure, Organization, and Formatting (6 points)

The written analysis has the following structure, organization, and formatting:

There is a title, and there are multiple sections. (2 pt)

Each section has a heading and subheading. (2 pt)

Links to images are working and displayed correctly. (2 pt)

Analysis (24 points)

The written analysis has the following:

Overview of the statistical analysis:

The purpose of the analysis is well defined. (5 pt)

Results:

There are at least seven visualizations for the NYC Citibike analysis (7 pt)

There is a description of the results for each visualization (7 pt)

Summary:

There is a high-level summary of the results and two additional visualizations are suggested for future analysis (5 pt)




