# AFCON SQL publication notes

[Project overview](../README.md) · [Metric definitions](../docs/metric-definitions.md)

The AFCON project used SQL in its analytical workflow. The original working query exports were not available in the material retrieved for this GitHub update, so this folder does not present newly invented scripts as the author's completed analysis.

Before adding the working SQL, prepare a reviewed export that includes the source-table schema, table grain, import order and analytical queries. Remove table-reset commands, credentials, personal file paths and unrelated debugging fragments from the public copy.

Each published query should identify its date scope, source tables and metric definition. Validate duplicate keys, source completeness, country mappings, co-host assignments, attendance denominators and percentage scaling. Include at least one checked output for each principal analysis question.

The existing report guide and metric definitions describe the analytical requirements; they are not evidence that unprovided SQL or Power BI measures have been executed or inspected.
