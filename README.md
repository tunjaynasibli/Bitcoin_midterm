Definition:
We are going to use the dataset from Kaggle for our research on top German cities rental prices. 
Description of data set:
The data was scraped from Immoscout24, the biggest real estate platform in Germany. Immoscout24 has listings for both rental properties and homes for sale, however, the data only contains offers for rental properties.
The scraping process is described in this blog post and the corresponding code for scraping and minimal processing afterwards can be found in this Github repo.
At a given time, all available offers were scraped from the site and saved. This process was repeated three times, so the data set contains offers from the dates 2018-09-22, 2019-05-10 and 2019-10-08, 2020-02-01.

Content
The data set contains most of the important properties, such as living area size, the rent, both base rent as well as total rent (if applicable), the location (street and house number, if available, ZIP code and state), type of energy etc. It also has two variables containing longer free text descriptions: description with a text describing the offer and facilities describing all available facilities, newest renovation etc. The date column was added to give the time of scraping.

Our research:
The German selected city price difference; which has the highest or lowest rent prices; did they changed over time; which features are influencing the rent price and how much;

Tuesday
Data preparation: sorting and cleaning

Wednesday
Data Scraping

Thursday
Making dashboards and design

Steps:

•	We Select the top 3 biggest cities and compare data (considering adding Leipzig)
•	Find cheapest rent from the cities selected
•	Average rent per each city
•	Average price per square meter per flat (new houses) vs old houses / per city
•	Heating costs per newly constructed vs old house per city
•	Most influential features for the rent price
•	Additional price per feature e.g. balcony, garden, per household per city
•	Price heatmap of Germany

The project will be in collaboration with Ivas Liberis and Tunjay Nasibli



