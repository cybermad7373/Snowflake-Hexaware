```
snowflake-databricks-learning/
│
├── README.md                          # Overall repository description
├── setup/
│   ├── environment-setup.md           # Prerequisites & environment setup
│   └── azure-snowflake-config.md      # Azure-Snowflake connectivity setup
│
├── day-1-introduction/
│   ├── README.md                      # Day 1 objectives & overview
│   ├── lab-1-sso-setup/
│   │   ├── azure-ad-config.json
│   │   └── snowflake-sso-setup.sql
│   ├── lab-2-ddl-operations/
│   │   ├── create-database-schema.sql
│   │   ├── create-tables.sql
│   │   └── sample-data-load.sql
│   ├── lab-3-databricks-connector/
│   │   ├── snowflake-connector.py
│   │   └── databricks-config.json
│   ├── lab-4-adls-mount/
│   │   ├── mount-adls.py
│   │   └── load-to-snowflake.py
│   ├── lab-5-rbac-setup/
│   │   ├── create-roles.sql
│   │   ├── assign-privileges.sql
│   │   └── databricks-user-setup.sql
│   ├── lab-6-marketplace/
│   │   ├── marketplace-dataset.sql
│   │   └── sample-queries.sql
│   ├── lab-7-snowpark-intro/
│   │   ├── snowpark-basic.py
│   │   └── query-snowflake.py
│   └── case-study/
│       ├── sql-server-extract.py
│       ├── databricks-transform.py
│       └── snowflake-load.py
│
├── day-2-data-ingestion/
│   ├── README.md                      # Day 2 objectives & overview
│   ├── lab-1-copy-into/
│   │   ├── create-external-stage.sql
│   │   ├── copy-into-command.sql
│   │   └── adls-to-snowflake.py
│   ├── lab-2-snowpipe/
│   │   ├── snowpipe-setup.sql
│   │   ├── event-grid-config.json
│   │   └── auto-ingestion-setup.py
│   ├── lab-3-pyspark-transform/
│   │   ├── pyspark-transformations.py
│   │   └── snowpark-dataframe.py
│   ├── lab-4-delta-lake/
│   │   ├── create-delta-table.py
│   │   ├── delta-to-snowflake.py
│   │   └── snowpark-delta-integration.py
│   ├── lab-5-adf-orchestration/
│   │   ├── adf-pipeline.json
│   │   ├── databricks-activity.json
│   │   └── snowflake-copy-activity.json
│   ├── lab-6-semi-structured/
│   │   ├── json-query.sql
│   │   ├── parquet-query.py
│   │   └── semi-structured-snowpark.py
│   ├── lab-7-snowpark-udf/
│   │   ├── data-cleansing-udf.py
│   │   └── register-udf-snowflake.py
│   └── case-study/
│       ├── log-ingestion.py
│       ├── json-transformation.py
│       └── analytics-pipeline.py
│
├── day-3-performance-optimization/
│   ├── README.md                      # Day 3 objectives & overview
│   ├── lab-1-warehouse-scaling/
│   │   ├── warehouse-scaling.sql
│   │   ├── performance-test.py
│   │   └── snowpark-benchmark.py
│   ├── lab-2-snowpipe-monitoring/
│   │   ├── snowpipe-azure-blob.sql
│   │   ├── copy-history-monitor.sql
│   │   └── snowpipe-monitoring.py
│   ├── lab-3-azure-functions/
│   │   ├── function-trigger.py
│   │   ├── function-app.json
│   │   └── snowpipe-automation.py
│   ├── lab-4-query-optimization/
│   │   ├── clustering-keys.sql
│   │   ├── materialized-views.sql
│   │   └── snowpark-optimization.py
│   ├── lab-5-resource-monitors/
│   │   ├── create-resource-monitor.sql
│   │   ├── credit-usage-alerts.sql
│   │   └── cost-management.py
│   ├── lab-6-query-analysis/
│   │   ├── query-performance.sql
│   │   ├── snowpark-analysis.py
│   │   └── optimization-suggestions.py
│   ├── lab-7-multi-cluster/
│   │   ├── multi-cluster-setup.sql
│   │   ├── concurrency-test.py
│   │   └── snowpark-concurrent.py
│   └── case-study/
│       ├── bottleneck-analysis.py
│       ├── clustering-implementation.py
│       └── auto-scaling-setup.py
│
├── day-4-security-governance/
│   ├── README.md                      # Day 4 objectives & overview
│   ├── lab-1-azure-ad-auth/
│   │   ├── azure-ad-integration.sql
│   │   ├── sso-configuration.py
│   │   └── authentication-setup.md
│   ├── lab-2-column-security/
│   │   ├── data-masking-policies.sql
│   │   ├── column-masking.py
│   │   └── snowpark-masking.py
│   ├── lab-3-row-security/
│   │   ├── secure-views.sql
│   │   ├── row-level-policies.sql
│   │   └── snowpark-rls.py
│   ├── lab-4-cdc-streams/
│   │   ├── create-streams.sql
│   │   ├── tasks-scheduling.sql
│   │   └── cdc-databricks.py
│   ├── lab-5-key-vault/
│   │   ├── key-vault-integration.py
│   │   ├── secrets-management.py
│   │   └── secure-credentials.py
│   ├── lab-6-role-automation/
│   │   ├── logic-apps-config.json
│   │   ├── role-assignment.py
│   │   └── snowpark-automation.py
│   ├── lab-7-stored-procedures/
│   │   ├── dynamic-masking-sp.sql
│   │   ├── snowpark-sp.py
│   │   └── masking-procedure.py
│   └── case-study/
│       ├── rbac-implementation.py
│       ├── healthcare-masking.py
│       └── cdc-patient-records.py
│
├── day-5-elt-pipelines/
│   ├── README.md                      # Day 5 objectives & overview
│   ├── lab-1-elt-pipeline/
│   │   ├── pipeline-design.md
│   │   ├── databricks-extract.py
│   │   ├── snowpark-transform.py
│   │   └── snowflake-load.py
│   ├── lab-2-dynamic-tables/
│   │   ├── dynamic-tables-setup.sql
│   │   ├── incremental-processing.py
│   │   └── snowpark-dynamic.py
│   ├── lab-3-stored-procedures/
│   │   ├── create-sprocs.sql
│   │   ├── snowpark-sprocs.py
│   │   └── automation-scripts.py
│   ├── lab-4-zero-copy/
│   │   ├── clone-environments.sql
│   │   ├── testing-setup.py
│   │   └── snowpark-cloning.py
│   ├── lab-5-time-travel/
│   │   ├── time-travel-queries.sql
│   │   ├── historical-analysis.py
│   │   └── snowpark-time-travel.py
│   ├── lab-6-adf-orchestration/
│   │   ├── adf-pipeline.json
│   │   ├── snowpark-activities.py
│   │   └── monitoring-setup.py
│   ├── lab-7-monitoring/
│   │   ├── pipeline-monitor.py
│   │   ├── logging-setup.py
│   │   └── snowpark-logging.py
│   └── case-study/
│       ├── retail-extract.py
│       ├── sales-transformation.py
│       └── snowflake-load-pipeline.py
│
├── config/
│   ├── snowflake-connection.json      # Snowflake connection parameters
│   ├── databricks-config.json         # Databricks configuration
│   └── azure-credentials.json         # Azure service principal details
│
└── utilities/
    ├── common-functions.py            # Shared utility functions
    ├── error-handling.py              # Error handling utilities
    ├── logging-config.py              # Logging configuration
    └── performance-utils.py           # Performance monitoring utilities
```