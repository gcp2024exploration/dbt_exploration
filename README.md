# dbt_exploration
### Steps:
Create a virtual env using virtual env python package and activate environment

    virtualenv <env_name>

    source my_env/bin/activate (linux+mac)

    .\my_env\Scripts\activate (windows)

Install the dbt package using pip with BQ adapter

    pip install dbt-bigquery

Intialise the DBT project using below command

    dbt init <project_name> 