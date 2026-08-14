# The Fivetran + dbt Interactive Guide

Live: **https://hicham-bab.github.io/fivetran-dbt-guide/**

A hands-on interactive guide to the Fivetran + dbt value proposition. Eleven chapters from a source
system to an agent that acts, with every claim runnable as a simulation.

- Topic tabs into sub-tabs into mode tabs, 37 panels in all
- 26 simulators you can run live in front of a room
- Without/with toggles, and side-by-side comparisons against the native services
- Product UI mocks with a "what is happening" panel
- Three lenses: business, technical, and services practice

`v1-gates-first.html` is an earlier version that reads as a single linear narrative around six gates.

## Notes on the numbers

Native-service facts were checked against vendor documentation in August 2026: Fivetran 700+ connectors
plus the Connector SDK; Snowflake Openflow around 26 GA connectors; Databricks Lakeflow Connect managed
connectors GA for Salesforce, Workday and SQL Server, with more in preview and ingestion billed as your
own platform compute. Preview connectors move fast, so re-check vendor docs before quoting a number.

Worked examples run on data defined in the page, so the numbers on screen are computed rather than
asserted. Rates and tiers are deliberately absent.

No build step, no dependencies. Open `index.html` in a browser.
