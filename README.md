# GCP-project-on-Ensuring-Access-Identity-in-Google-Cloud

## In this project, I:

* Created two service accounts and granted them the appropriate roles:
  * bigquery-qwiklab service account with BigQuery Data Viewer and BigQuery User roles the web portal.
  * my-sa-123 service account with editor role from the CLI
* Created the bigquery-instance virtual machine, associated it with the bigquery-qwiklab service account and installed some importantant dependecies on it and associated it.
* Used a python script to access BigQuery using the service account permissions to run a query on a BigQuery public dataset from a Compute Engine instance.
