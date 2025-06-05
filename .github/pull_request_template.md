### Developers must include the following in each pull request. This ensures reviewers can verify functionality and understand the context of the change.

### Summary Brief explanation of what this PR changes and why

**Jira Ticket Link:** APPEALS-12345

Validation Steps

 Ran job/query in dev
 Output matches expectations (row counts, filters, edge cases)
 Spot-checked results in staging (e.g., dashboard or query output)
 No PII exposed
Post PR Actions Steps that must be run manually in the AWS console, Tableau, or other locations to fully implement changes

ex. Update associated glue job in AWS console Related Assets

Glue job name: adp_transform_appeals_status
Redshift view: adp.fct_appeals_status
Tableau dashboard: Appeals Status Dashboard – Staging
