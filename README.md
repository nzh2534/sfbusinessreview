# Salesforce API & USAID Business Forecast Metrics to Google Sheets

As my organization recently transferred to using Salesforce as their CRM, data from Salesforce needed to be adapted to previous report formats in Google Sheets. Manually calculating metrics from Salesforce Objects for specific records and their related objects took teams dozens of hours each month and manual input into the desired format in Google Sheets. Retrieving supporting figures from sources such as the USAID Business Forecast further bogged down the process.



### This repo automates this process: 
⚡️ Pulling data from Salesforce API for Objects with record type "Award" and their related objects (such as Budgets)

⚡️ Pulling data from the USAID Business forecast

⚡️ Using Object Oriented Programming to create objects related to timeframe

⚡️ Posting data to Google Sheets using the objects and mapping data to the necessary cells using [R1C1 notation](https://developers.google.com/sheets/api/guides/concepts#expandable-2)
