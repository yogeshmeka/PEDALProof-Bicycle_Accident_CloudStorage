# PEDALProof-Bicycle_Accident_CloudStorage

PEDAL PROOF: Data Engineering to Prevent Bicycle Collisions

I am excited to present our data engineering project on safe city cycling in the United States.
Under the guidance of Prof. Schenita Floyd, PhD, Our team has devoted five precious tools and combined them into an end-to-end cloud pipeline which cleanses and processes raw crash data into action data for city planners and public safety activists.

Problem
Cyclists are exposed to tens of thousands of deaths and injuries every year through dangerous roads, dangerous drivers, and poor infrastructure. We wondered if we could search for patterns in the crashes from publicly released accident reports/datasets from:

https://www.pedbikedata.org/

New York City
Tempe, Arizona
San Diego, California

What We Built:
We built a cloud data pipeline with:
OpenRefine – Data cleaning (outlier correction, type casting, normalization)
Hive – Crash query HDFS to crash data sets
SparkSQL – Scale-out data analysis using SparkSQL
BigQuery – Scale-out time series & seasonality crash analysis and aggregation
GCP – Central data processing and storage

Key Findings
Brooklyn had the highest number of cyclist crash events (~26,000 in NYC).
Day-night was the main cause of most crashes, 3–6 PM primarily.
The best-represented cyclists were 16–25-year-old males.
Rider behaviors such as reckless riding and giving way were the main causes—not weather.
Night-time crashes, although fewer in number, tended to be fatal.
What We Recommend
More segregated cycle lanes in top-performing boroughs
Public campaigns during times of peak-crash window times
Boost nighttime illumination & visibility kit uptake
Enhance crash data gathering such as behavior/environmental information
Second, secondly, we also created interactive dashboards in Tableau to share those insights with stakeholders.

Data engineering isn't magic on the back-end, it’s a method for making the actual world better. Do you care about smarter cities and safer travel? Just have a look.

Team:Yogesh Meka - Teja Sai Srinivas Kunisetty - Divyasree Pithani - Siva Karthik Sangaraju - Sai Bhargav Dasaraju - Pranavi Battula

#DataEngineering #UrbanSafety #GCP #Hive #BigQuery #SparkSQL #OpenRefine #BicycleSafety #Tableau #SmartCities #Teamwork #CloudEngineering
