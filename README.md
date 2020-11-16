# CIND820-AndyLee
Data Analytics (Capstone) Project for Ryerson University CIND 820, Fall 2020

The dateset can be downloaded from https://ieee-dataport.org/open-access/coronavirus-covid-19-tweets-dataset. The tweets are filtered by COVID-19 related keywords and groupby date into their own respective CSV files. Each CSV file only contain the tweet ID, therefore they have to be "hydrated" again using [Hydrator](https://github.com/DocNow/hydrator). 

1. Download any dateset from https://ieee-dataport.org/open-access/coronavirus-covid-19-tweets-dataset.
2. The CSV file contains two attributes: the Tweet ID, and a sentiment score. Since our task is to conduct our own sentiment analysis on the tweets, we need to extract only the Tweet ID. Open the CSV file with any CSV editor of your choice, such as Excel, and remove the sentiment score (2nd attribute) from the CSV. There should only be one attribute with with one tweet ID on every row. Save this file as .txt and close the modified dataset.
3. Download [Hydrator](https://github.com/DocNow/hydrator), install, and open the Hydrator program.
4. In the Hydrator program, click "Setting" tab on the top, and follow the instructions on the program to link to a Twitter account. This Twitter account will provide permission for the Hydrator program to read Tweet IDs into Tweets.
5. Now switch to the Add" tab, click "Select Tweet ID file" and select the modified dataset from step #2.
6. Under "Title", give the dataset any name, then click "Add Dataset" button
7. This brings you to the Dataset tab, click start and the hydration process will begin. Note that this will take an extended amount of time, as there is a limit to how many tweets, as per Twitter API Rate Limits, a Twitter Account can read.
8. Once the Hydration process has complete, click "CSV" and a dialog box will pop up asking the filename of the CSV file you wish to save the results into. Give any descriptive filename.
