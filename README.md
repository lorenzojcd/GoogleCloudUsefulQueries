# GoogleCloudUsefulQueries

BigQuery is a serverless, highly-scalable, and cost-effective cloud data warehouse with an in-memory BI Engine and machine learning built in. This repository provides useful utilities to assist you in migration and usage of BigQuery.

Open in Cloud Shell

Getting Started
This repository is broken up into:

Dashboards - Pre-built dashboards for common use cases
Scripts - Python, Shell, & SQL scripts
billing - Example queries over the GCP billing export
Stored Procedures - Example stored procedures
UDFs - User-defined functions for common usage as well as migration
community - Community contributed user-defined functions
migration - UDFs which mimic the behavior of proprietary functions in the following databases:
netezza
oracle
redshift
snowflake
teradata
vertica
Views - Views over system tables such as audit logs or the INFORMATION_SCHEMA
query_audit - View to simplify querying the audit logs which can be used to power dashboards (example).
Public UDFs
For more information on UDFs and using those provided in the repository with BigQuery, see the README in the udfs folder.

Contributing
See the contributing instructions to get started contributing.

To contribute UDFs to this repository, see the instructions in the udfs folder.

License
All solutions within this repository are provided under the Apache 2.0 license. Please see the LICENSE file for more detailed terms and conditions.

Disclaimer
This repository and its contents are not an official Google Product.
