# dbt_exploration
### Steps:
Create a virtual env using virtual env python package and activate environment

    virtualenv my_env -- give your desired name
    source my_env/bin/activate activate the env(linux+mac)
    .\my_env\Scripts\activate activate the env(windows)

Install the dbt package using pip with BQ adapter

    pip install dbt-bigquery

Intialise the DBT project using below command

    dbt init <project_name> 