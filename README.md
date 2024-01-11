# NYC-Park-Violations-Project
Getting Familiar With dbt

## Medallion Structure
In bronze directory, we didn't have to use ref statement because it's the bronze table (the raw data part), it's the first start of a data pipeline. 
So since it's the beginning it doesn't need to reference anything.

Bronze is our raw data model.

Silver is our transformed data model.

Gold  data is ideally for metrics and aggregates that'll be utilized by downstream data consumers via reports and dashboards.