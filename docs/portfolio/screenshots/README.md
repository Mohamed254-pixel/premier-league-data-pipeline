# Visual evidence inventory

This directory is reserved for genuine, sanitized project screenshots. No
Airflow UI, SQL client, or AWS console screenshots were retained with the
project records, so no screenshot files are included. Capturing a new Airflow
or database view would require starting or accessing services that are not
currently verified as running; the AWS EC2 instance was stopped after the
time-boxed demonstration. No service was started and no AWS resource was
restarted to create portfolio imagery.

Use these verified records in place of screenshots:

| Evidence | Source |
| --- | --- |
| Successful five-stage local Airflow run | [Phase 2 scheduling activation](../../phase2-scheduling-results.md) |
| Season counts, historical preservation, and checkpoint results | [Phase 2 bootstrap](../../phase2-bootstrap-results.md) and [repeat run](../../phase2-repeat-results.md) |
| CloudFormation, EC2 Airflow runs, MySQL validation, S3 objects, resource use, and cost assumptions | [Sanitized Phase 3 AWS report](../phase3/README.md) |
| Current recorded CI status | [GitHub Actions workflow](https://github.com/Mohamed254-pixel/premier-league-data-pipeline/actions/workflows/tests.yml) |
| Architecture | Mermaid diagram in the [project README](../../../README.md#architecture) and the detailed [architecture guide](../../architecture.md) |

If screenshots are added later, capture the actual interface and run, remove
credentials and private network details, retain readable task/query results,
and document capture date and verification scope. Never replace a missing
capture with a fabricated dashboard or terminal image.
