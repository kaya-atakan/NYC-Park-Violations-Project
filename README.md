# NYC-Park-Violations-Project
Getting Familiar With dbt

## Medallion Structure


Bronze is our raw data model.

**Notes**: In bronze directory, we didn't have to use ref statement because it's the bronze table (the raw data part), it's the first start of a data pipeline. So since it's the beginning it doesn't need to reference anything.

Silver is our transformed data model.

Gold  data is ideally for metrics and aggregates that'll be utilized by downstream data consumers via reports and dashboards.
And again, the goal tables, just make it so that for your dashboards downstream, or for your analytics downstream, the data's already prepared and moves very quickly for 'em. Many times these are some easy wins you can get for your stakeholders to get dashboard move really quickly.