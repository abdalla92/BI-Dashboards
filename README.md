# BI-Dashboards
Analysing car sales and profits for each dealer using IBM's Cognos Analytics and Google's Looker Studio tools

## Scenerio
I have been hired by SwiftAuto Traders, a chain of car dealerships, as a data scientist. My first task is to analyze car sales and profits for each dealer. I need to create some visualizations and present them as a dashboard/report to your regional manager for a better understanding of car sales and profits for each dealer.

I use IBM's Cognos Analytics tool (part a) to create a dashboard
And
Create visuals and submit a report using Google's Looker Studio tool (part b).

## About the dataset
The dataset used in this project comes from here in the IBM Accelerator Catalog. The Terms of use for such are located at https://developer.ibm.com/terms/ibm-developer-terms-of-use/.

I am using a modified subset of that dataset for the project, rather than the dataset from the original source.

### Accessing the Dataset for BM's Cognos Analytics
The dataset used in this final assignment is provided as sample data within my Cognos environment, in a data module called Auto group data module.

To load and open the data module:

On the navigation panel of Cognos Analytics, select Team content.

Now go to By industry > Automotive > Data.

Here, the sample data used in this final assignment can be found, in a data module called Auto group data module. Right-click on Auto group data module and select Create Dashboard.

### Accessing the Dataset for the Google Looker
To access the dataset, I need to download this dataset (all files) and import them into my Google Drive.

Upload all these files to my drive. I use the Google Sheets connector in Looker Studio to connect with these Excel worksheets to add data into my report

In case it doesn't show the files while adding, then open a blank Google Sheet in your drive.

Click on Import from the File menu, and then select the relevant file from your drive.

Then you can use the Google Sheets connector in Looker Studio to connect with these Excel worksheets to add data to my report. Select the data sheets one by one and add them to your report or create a data source.

Alternatively, I can use the CSV versions of these files, which can be downloaded from here.


## PART a: Create Visualizations using IBM's Cognos Analytics (OR Google's Looker Studio )
## Objective:
The objective of this part of the Final Assignment is to analyze the historical trends in car sales for SwiftAuto Traders. The goal is to provide insights on car sales and profits for each dealer.

In this project, I will create a dashboard or report using IBM's Cognos Analytics and Google's Looker Studio.

## Task Information


Task 1: Create a dashboard/report page titled as Sales to capture the following KPI metrics:

 - Capture Profit (formatted to 1 decimal place in millions of US dollars)
 - Capture Quantity sold
 - Create a bar chart to capture Quantity sold by model
 - Capture Average quantity sold

Task 2: Develop a column chart to display Profit by Dealer ID in the Sales dashboard/report page sorted in ascending order.

Task 3: Create another dashboard/report page titled as Service and capture the following KPI metrics as visualizations:

 - Create a column chart to capture the number of recalls per model of car
 - Create a treemap to capture the customer sentiment by comparing positive, neutral, and negative reviews.
 - Create a line and column chart to capture the quantity of cars sold per month compared to the profit.
 - Create a heatmap (in Cognos) / Pivot table with heatmap (in Looker) to capture the number of recalls by model and affected system

Task 4: Export the dashboard/report as a PDF to your Downloads folder.
