# Hi, I'm Sayan Banerjee

I have a background in computer science. Right now, I'm focusing on **Data Engineering** and building projects that help me understand how data moves from raw files to something people can actually use.

I use this GitHub to keep track of what I'm building, what I'm learning, and the things I've tried along the way.

## Projects

### [CityRide — NYC Taxi Data Pipeline](https://github.com/codewithsayan7/cityride-data-pipeline)

A PySpark project based on the January 2024 NYC Yellow Taxi dataset.

- Built a batch pipeline with Bronze, Silver, quarantine and Gold outputs.
- Added checks for invalid records and duplicate trips.
- Processed **2,964,624 source records** in one local run; **2,869,912** were accepted and **94,712** were quarantined.
- Created five Parquet summary tables and a Streamlit dashboard.

[Open the live dashboard](https://cityride-data-pipeline-fkn9erbfxfqmwqr64ipf6q.streamlit.app/)

The full Spark job runs locally. The hosted dashboard reads the precomputed Gold tables, so it doesn't start a Spark job in the cloud.

### [RetailPulse — Retail ELT & Data Warehouse](https://github.com/codewithsayan7/RetailPulse)

A small e-commerce data warehouse project using a fictional retailer and generated sample data.

- Used Python to generate and load customer, product and order data into PostgreSQL.
- Built fact and dimension tables, SQL analytics views and dbt models.
- Used Docker Compose for the local setup and Airflow to run the ELT workflow.
- Checked the pipeline with pytest and data-quality tests.

[Open the live dashboard](https://retailpulse-g8dmcd3mk49darsxzhkt9g.streamlit.app/)

The dataset is synthetic. The hosted dashboard reads the included CSV files; the PostgreSQL and Airflow workflow runs locally.

## Tools I'm using

**Languages:** Python, SQL  
**Data:** PostgreSQL, PySpark, Apache Spark, dbt  
**Workflow:** Apache Airflow, Docker, Git, GitHub Actions  
**Exploration:** Pandas, Streamlit, Plotly

## What I'm learning

I'm spending most of my time improving my SQL, data modelling and pipeline-building skills. I also want to get better at writing tests, debugging data issues and making projects easier for someone else to run.

I learn best by building something, running it, checking the results and fixing what doesn't work. I try to document the decisions I make and be clear about what is finished and what still needs work.

I'm currently exploring entry-level Data Engineering roles and internships.

---

Thanks for taking a look at my work. Feedback and suggestions are always welcome.
