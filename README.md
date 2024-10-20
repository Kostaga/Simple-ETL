# Simple-ETL
A very simple data pipeline using PostgreSQL and PySpark made for practice. It showcases data ingestion, transformation, and loading processes with a focus on movie-related datasets.
# Features
<li> Data ingestion using Pandas from CSV files. </li>
<li>Transformation with PySpark for data cleaning and aggregation. </li>
<li> Storage and querying of transformed data with PostgreSQL. </li>
<li>Dockerized PostgreSQL database to streamline deployment.</li>
<li>Connection between PostgreSQL and Python using SQLAlchemy and psycopg2.</li>
<li>Visualizations using matplotlib </li>

# Architecture
Below is a high-level architecture diagram that explains the flow of the project.

Data Ingestion: Raw movie data is imported into a PySpark DataFrame from CSV.
Data Transformation: Data is cleaned, merged, and aggregated using PySpark transformations.
Storage: Transformed data is loaded into a PostgreSQL database using to_sql() from Pandas.
Analytics: Queries can be run on the PostgreSQL database to generate insights such as the total streams per movie or per artist.
