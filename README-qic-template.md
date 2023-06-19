# Quantium Innovation Challenge 

This repo contains participant information for the Quantium Innovation Challenge event. Please use information in this repo to ...

## Summary 

The Innovation Challenge is an opportunity to build solutions to real business problems using leading edge services on Google Cloud, which has foundations within the client.

In order to explore more ideas, please use this repo to form ideas and use examples for your team.

Please find the project links for your team.

- [Team Name](link-to-console-dashboard)

## Team Resources

Each team recieves a dedicated Google Cloud project `<team-name-random-suffix>`, with the Project Owner permission.

By default, the following servers/APIs are enabled:

- "aiplatform.googleapis.com"
- "artifactregistry.googleapis.com"
- "bigquery.googleapis.com"
- "compute.googleapis.com"
- "cloudbuild.googleapis.com"
- "cloudfunctions.googleapis.com"
- "datacatalog.googleapis.com"
- "dataflow.googleapis.com"
- "datastudio.googleapis.com"
- "dlp.googleapis.com"
- "eventarc.googleapis.com"
- "logging.googleapis.com"
- "sourcerepo.googleapis.com"
- "run.googleapis.com"
- "pubsub.googleapis.com"
- "monitoring.googleapis.com"
- "notebooks.googleapis.com"
- "eventarcpublishing.googleapis.com"
- "storage.googleapis.com"

Additional servers/APIs can be enabled when required.

By default, each team will be provided a *data landing zone cloud storage bucket* . The naming convention is `<team_name>-bigquery-csv-import`. Please note that we only support CSV format at the moment, and those CSV files must be uploaded to the bucket root. We are working on supporting more data format and nested directory structures.

By default, each team will be provided a *cloud source repository*. Please use this command to clone it to your local. `gcloud source repos clone  --project=countdown-<team_name>-repo`.

By default, each team will be provisioned a *Vertex AI managed notebook instance* (JupyterLab notebook) with owner permission. The imported datasets should be accessible via GCS bucket browser on the instance.

### Datasets

#### OpenSea NFT Asset Data
Data including NFT details and sale history will be loaded into your BigQuery instance.
- https://opensea.io/collection/art-blocks-factory 
- https://docs.opensea.io/reference/asset-object

#### Public Datasets
Google have a [repository](https://cloud.google.com/bigquery/public-data) of sample datasets which can be found [here](https://console.cloud.google.com/bigquery?project=bigquery-public-data&page=project) in BigQuery. Popular datasets are `catalonian_mobile_coverage` and `catalonian_mobile_coverage_eu`.

Additional datasets can be found in the `Quantium-id-datasets` bucket within the Quantium-id-shared project.

## Sample Apps

These are available as a simple one-click deployment for hosting applications on managed Cloud Run.

|Framework|Description|Deploy|
|---|---|---|
|[name.js](link)|description|[![Run on Google Cloud](https://deploy.cloud.run/button.svg)](link)|

## Resources

Additional information and resources are available at the links below:

- [Howto for JupyterLab Notebooks](https://jupyterlab.readthedocs.io/en/stable/user/notebook.html)

## Additional Resources

- [Introduction to Vertex AI Workbench](https://cloud.google.com/vertex-ai/docs/workbench/introduction)
- [Vertex AI Jupyter Notebook tutorials](https://cloud.google.com/vertex-ai/docs/tutorials/jupyter-notebooks#vertex-ai-workbench)
