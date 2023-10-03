## Portfolio

---


### Data Modelling & Advanced SQL for Analytics 

[SQL scripts view here](https://github.com/thyanhbui1412/DataPipelinesPracticeSQL)
#### *Knowledge: Star Schema, Slow Changing Dimension, Data Quality, KPI, Experimentation, Data Visualization* ####

The repo compiles SQL scripts for pipelines I built for dimensional modellings, fact table, cumulative table, SCD, backfill, dedups, datelist data structure, OLAP cubes/advanced analytics using grouping sets, windows-based analytics, state changing.
What I learned and reviewed: 
- Fact and Dimensional Modeling with Slowly Changing Dimensions (SCD)
- Data Quality Practices and Data Spec Pipelines
- Streaming Pipelines with Flink
- Advanced SQL Techniques for Analytics such as Growth Accounting, Funnel Analytics, and Survivorship Analysis.
- Experimentation (A/B Testing) with Statsig and defining KPI
- High-Performance Data Visualization


[Dashboard for Executives](https://public.tableau.com/views/ZachWilsonBootcamp-ExecView/Bootcamp-Execview?:language=en-US&:display_count=n&:origin=viz_share_link)

<img src="/ExecutiveDashboards.png?raw=true"/>

[Dashboard for EDA:](https://public.tableau.com/views/ZachWilsonBootcamp-EDA/ZachWilsonBootcamp-EDA?:language=en-US&:display_count=n&:origin=viz_share_link)

<img src="/EDAViz.png?raw=true"/>

---

### ETL - Data Pipelines

[How fast are NYC firefighters?](https://github.com/thyanhbui1412/FireDispatch)
#### *Tools & Knowledge: AWS (EC2, Elasticsearch, OpenSearch, OpenSearch Dashboards), NoSQL, Docker, API, Linux Shell* ####

<img src="ezgif.com-video-to-gif.gif"/>

I automated workflow to extract data from NYC Fire dispatch, clean and visualize with ELK Stack.
Turned out crazy traffic in Manhattan doesn't stop it from being the 2nd quickest borough to response to fire alarm!

*This project streams data directly into OpenSearch cluster provisioned via AWS and analyzez NYC fire alarms between 2012 and 2021. This project is applied with the knowledge of principles of containerization, terminal navigation, python scripting, artifact deployment and AWS EC2 provisioning.*

---
[Quiet and safe neighborhood in NYC: possible or not?](https://github.com/thyanhbui1412/Noise-Crime)
#### *Tools & Knowledge: Python, SQL, Google Cloud, dbt, Tableau, API* ####
<img src="/DimensionalModel.png?raw=true"/>
<img src="/dag.png?raw=true"/>

This is a team project when I took the class Data Warehouse at Baruch College, which sparked a lot of curiosity from me and I therefore embarked on data engineer career path. In this project,

I learn to build a mini ETL where I streamlined NYC open data with Socrata API to target data warehouse GCP, then streamed from GCP to Jupiter Notebook for data profiling, then used dbt built data marts, fact tables in GCP.

I developed [Python script](https://github.com/thyanhbui1412/Noise-Crime/DWProject-ExtractingNoiseData.py) to stream real-time data. I also took main part in performing ETL logic, workflows and data transformation with dbt, which was documented [here](https://github.com/thyanhbui1412/Noise-Crime/blob/src/ETL%20project%20-%20311%20NYC%20Open%20Data%20Source.pdf). Working in a team, I learned to maintain well-documented codes and process. If time permitted, I want to build Python scripts to backfill archive data and upcoming data, schedule a production run in dbt so that the ETL process is continously streamed and transformed.


---
[Rhythmic Insights: Banding Sleep, Stress and Music- WIP](http://example.com/)
#### *Tools & Knowledge: AWS S3, Snowflake, dbt, API, SQL, Python, Linux Shell, parquet* ####

Besides my big passion for data, I also love wellness, swimming and music. I combined my interests and created data pipelines where I can derive insights about my stress and sleep index correlating to swimming and music variations. 

I extracted personal sleep, stress, RHR data from Garmin API, music data from Spotify streaming history, then I stored large datasets in parquet and push them to S3. I developed ETL, designed OLAP data warehouse with Snowflake, and built data QA processes with dbt connected to Snowflake. 


---
## Mini project
### Big Data Technology

- [Movie Reccomdation System/Movie Analysis](https://github.com/thyanhbui1412/FirstTimeWithNoSQL/blob/src/Project2_Analysis.pdf.pdf)

Store IMDB data in S3 bucket. Data manipulation and analysis using PySpark. Recommendation system is based on popularity. 
### SQL
- [SQL-Employee ranking system](https://github.com/thyanhbui1412/SQLDataManipulation/blob/src/Who%20is%20the%20best%20sale%20manager%20Real-Time%20Analysis%20and%20Visualization%20with%20BigQuery%20SQL.pdf)

Create tables from GCP public data. Rank employee using weighted criteria models.


---




---
<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
