# Kickstarter Excel Pivots

## **Objective:**
The objective of this project is to use conditional formatting, formulas, pivot tables, and pivot charts in Excel to modify and analyze the data of 4,000 past Kickstarter projects to uncover potential market trends. Since Kickstarter is a crowdfunding service, the dataset includes information such as funding goal, percent funded, average donation, currency, country, and category. 

The following graphs were created:
* Number of Projects by Category and outcome
![graph1.jpg](Images/CategoryStats.png)


* Number of Projects by Sub-Category and outcome
![graph2.jpg](Images/SubcategoryStats.png)


* Number of Projects by Campaign Launch Month and outcome
![graph3.jpg](Images/LaunchDateOutcomes.png)


* Goal Amount vs. Percentage of Successful, Failed, and Cancelled Projects
![graph4.jpg](Images/GoalOutcomes.png)

## **Tools:**
Microsoft Excel

## **Formatting:**
The dates stored within the `deadline` and `launched_at` columns use Unix timestamps.[There is a formula](https://www.extendoffice.com/documents/excel/2473-excel-timestamp-to-date.html) that was used to convert these timestamps to a normal date.
![screen1.jpg](Images/DateConversion.png)

Conditional formatting applied based on funding percentage and outcome.
![screen1.jpg](Images/PercentageFundedFormat.png)






