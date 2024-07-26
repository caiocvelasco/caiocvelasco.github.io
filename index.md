---
layout: default
---

<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta property="og:image" content="https://caiocvelasco.github.io/assets/img/etl.png"> <!-- Change this URL to the image you want -->
  <meta property="og:url" content="https://github.com/caiocvelasco/caiocvelasco.github.io">
  <title>Caio Velasco</title>
</head>
<body>
</body>
</html>

I'm a Mechanical Engineer from Brazil with a Master in Economics & Public Policy from the University of California Los Angeles (UCLA). 

In 2021, because of the pandemic, I decided to stop a Ph.D. in Economics in the Netherlands and transition into **Data Science**.

My professional experience ranges from Business (Business Analysis, Product Ownership, and Consulting) to Tech (Data Engineering and Data Science). I also have very good Communication, Teaching and Leadership skills.

My academic experience includes Advanced Math, Statistics, Economics, and Econometrics (Multiple Regression, Causal Inference, Difference in Differences, Instrumental Variables, Time Series) as well as basic knowledge of Corporate Finance and Financial Markets.

I grew up in Rio de Janeiro and education was the only weapon I had to succeed in life. As a consequence of my efforts, I was awarded by Yale University, UCLA, General Electric Foundation, Lemann Foundation, and The Club of Rome.

Moreover, I bring strong entrepreneurial skills to the table. In the past, I helped build Stone Payments, a famous Brazilian FinTech payment company (NASDAQ: STNE), and I created my own mathematics digital product (MePrepara) from scratch with over 140 videos teaching low-income Brazilian students who need to take the GMAT and GRE exams to apply for MBAs/ or PhDs abroad.

Thank you for visiting :)

## Projects (Data Engineering)
---

### ETL Pipeline from Crypto API to Tableau (CSV), with Dockerized Postgres, Jupyter Notebook, and Python.

[Check it out here!](https://github.com/caiocvelasco/project01-docker-ETL-from-API-CSV-to-Tableau.git)

This ETL pipeline uses Python functions to perform ETL steps, extracting from an external API and transforming the data to be saved as CSV files for later use by Tableau or any other visualization tool. This project runs within a Dockerized environment, using PostgreSQL as a database and Jupyter Notebook as a quick way to interact with the data.

<img src = "assets/img/project01-etl-tableau.png">

--- 

### ETL (Medallion Architecture and Kimball Dimensional Modeling) for Machine Learning (Churn Prediction), with Dockerized Postgres, Jupyter Notebook, and Python.

[Check it out here!](https://github.com/caiocvelasco/project02-docker-medallion-postgres-kimball-star-schema.git)

I built a Python ETL pipeline using Python functions to perform ETL steps. This project runs within a Dockerized environment, using PostgreSQL as a database and Jupyter Notebook as a quick way to interact with the data and materialize schemas and tables. The ETL process followed the Medallion Architecture (bronze, silver, and gold schemas) and Kimbal's Dimensional Modeling (Star Schema).

<img src = "assets/img/project_02-elt-medallion.png">

---  

### Migrating ETL (Medallion Architecture and Kimball Dimensional Modeling) to dbt, with Dockerized Postgres, Jupyter Notebook, and dbt.

[Check it out here!](https://github.com/caiocvelasco/project02-docker-dbt-migration-medallion-kimball-postgres.git)

I expanded a previous work to mimic a project where we want to migrate Python ETL Processes to dbt, within a Dockerized environment. The data is extracted from multiple CSV files and both the Transformation and Loading steps are done against PostgreSQL, via dbt. The ETL process followed the Medallion Architecture (bronze, silver, and gold schemas) and Kimbal's Dimensional Modeling (Star Schema).

<img src = "assets/img/project_02-elt-medallion_dbt.png">

--- 

### Part 1 of 2 - Leveraging dbt-DuckDB to perform an Ingestion Step (Postgres -> AWS S3 Bucket (Parquet)).

[Check it out here!](https://github.com/caiocvelasco/project03-docker-dbt-DuckDB-from-postgres-to-s3-parquet.git)

This projects uses a Dockerized environment to extract data from Postgres (as if it were data in "Production"). Then, it converts the data into a Parquet files, saving them into AWS S3 Bucket. I used my AWS Free Tier account and implemented the dbt-DuckDB adapter to expand dbt's core function (the Transformation step) into an Ingestion machine. 

<img src = "assets/img/dbt_1_ingestion.jpg">
 
--- 

### Part 2 of 2 - Leveraging dbt-Snowflake to perform a Transformation Step (Parquet in S3 -> Snowflake External Tables -> Transformation in Snowflake via dbt).

[Check it out here!](https://github.com/caiocvelasco/project03-docker-dbt-from-s3-parquet-to-Snowflake-external-tables)

This project uses a Dockerized environment to extract Parquet files stored in S3 Buckets. External Tables were In Snowflake following Snowflake's Storage Integration and External Stage procedures. Then, dbt perfors the Transformation step and materialize dimension and facts in the Silver Layer and Aggregated tables in the Gold schema, following the Medallion Architecture and Kimbal's Dimensional Modeling. 

<img src = "assets/img/dbt_2_transformation.jpg">

## Projects (Data Science & Analytics)
---

### Data Analysis and Inferential Statistics with Python

[Healthcare Cardio & Covid Data Analysis](https://github.com/caiocvelasco/cardio-covid-project.git)
<img src = "assets/img/health.jfif">

--- 

## Sharing Knowledge

As hobbies, I play football competitively (forward), it's my passion. I have played in amateur leagues in Brazil, USA, and the Netherlands. I also have a strong passion for teaching and educating others. A personal characteristic I am proud of is the ability to transform very complex subjects into intuitive topics for any audience.

I find happiness in the little things in life and I also learned a lot from every mistake I have made so far (and still do).

---

### Statistics & Data Science
I have a passion for teaching and I have been trained by amazing professors in top notch universities around the globe.

Therefore, I have started to write a book that belongs to a (future) course I call "**An Intuitive Course in Probability (and Statistics)**, _for data science_. The idea is to provide strong intuition for every major concept while keeping the mathematical formalization and rigor very close. I had this idea after taking a Probability Theory course from MIT. I am a fan. It will be available both in English and Portuguese.

Please, check the English version [here](https://caiocvelasco.github.io/assets/my_course/An_Intuitive_Course_in_Probability__draft_EN.pdf) and the Portuguese version [aqui!](https://caiocvelasco.github.io/assets/my_course/Um_Curso_Intuitivo_de_Probabilidade__draft_PT.pdf)

It's a working in progress, so you may find only part of Chapter 1 now.

### Math
Sometimes, I try to contribute to some interesting communities. You can check an example below.

* Math StackExchange\
Here is an [example](https://math.stackexchange.com/a/3444354/727414).