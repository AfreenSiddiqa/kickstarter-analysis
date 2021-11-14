# kickstarter-analysis
performing analysis on kickstarter data to uncover trends

## Overview of Project
The project wil find campaigan outcomes based on launch dates and their funding goals.

### Purpose
The purpose of this project is to analyse the outcomes based on launch date and outcomes based on goals from the kickstarter challenge data.

## Analysis and Challenges


### Analysis of Outcomes Based on Launch Date
For this, I created pivot table from parent category and years as filters and then filtered the column tabels to show only "sucessful", "failed", and "canceled", I also had to group the "row labels" column to show the months of the year.

### Analysis of Outcomes Based on Goals
I created a new sheet with columns and used countifs() functions to populate the number "successful, failes and canceled" columns and used the sum() function to calculate the percentage of the columbus created.

### Challenges and Difficulties Encountered
The challenges I faced in this was first creating the date created conversion column and then extract years from it by using years() function.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
- One conclusion was from May-June were most sucessful months to launch and December is the least sucessful month.

- What can you conclude about the Outcomes based on Goals?
conclusion on outcomes based on goals was there was no canceled projects in subcategory "Play" in greater than 50000.

- What are some other possible tables and/or graphs that we could create?
- you can use other tables in the data sheet like pledge amount, currency, country etc..
