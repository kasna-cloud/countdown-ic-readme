# Countdown Innovation Challenge 

This repo contains participant information for the Countdown Innovation Challenge event. Please use information in this repo to explore data and develop operational apps.

## Summary 

*EMBRACE A SUSTAINABLE FUTURE AND HARNESS YOUR INNOVATIVE IDEAS TO CREATE A GREENER ENVIRONMENT FOR ALL*
The focus for the event will be anchored to our strategic theme of Good and Green. A few examples of topics that align with the theme include:

1. Reduction of food waste from farm to fork
2. Increased energy efficiency in stores
3. Decarbonisation of our supply chain
4. Reduction of water usage, and;
5. Other environmental sustainability areas

In order to explore more ideas, please use this repo to form ideas and use examples for your team.

Please find the project links for your team.

- [Abnormal Distribution](https://console.cloud.google.com/home/dashboard?project=abnormal-distribution-5vwjev)
- [ECO Warrios](https://console.cloud.google.com/home/dashboard?project=eco-warriors-oonuj8)
- [EV All the Way](https://console.cloud.google.com/home/dashboard?project=ev-all-the-way-lhz1px)
- [Guardians of the Planet](https://console.cloud.google.com/home/dashboard?project=guardians-of-the-planet-xjr2s2)
- [Skinny Waste](https://console.cloud.google.com/home/dashboard?project=skinny-waste-awdrz7)
- [Team 3](https://console.cloud.google.com/home/dashboard?project=team-3-tbd-ksf7jk)

## Team Resources

Every team will be provisioned with a dedicated GCP project with project owner permission. The project naming convention is `<team_name>-<random_suffix>`.

By default, the following servers/APIs will be enabled for those team projects. Other services/APIs can be enabled when required.

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

By default, each team will be provided a *data landing zone cloud storage bucket* . The naming convention is `<team_name>-bigquery-csv-import`. Please note that we only support CSV format at the moment, and those CSV files must be uploaded to the bucket root. We are working on supporting more data format and nested directory structures.

By default, each team will be provided a *cloud source repository*. Please use this command to clone it to your local. `gcloud source repos clone  --project=countdown-<team_name>-repo`.

By default, each team will be provisioned a *Vertex AI managed notebook instance* (JupyterLab notebook) with owner permission. The imported datasets should be accessible via GCS bucket browser on the instance.

### Datasets

These datasets are available to teams and loaded either into your BigQuery instance, or available in a storage bucket `gs://<team_name>-bigquery-csv-import`.

The following custom datasets as per category are available on the GCS bucket.

#### Retail Data Analytics

- https://www.kaggle.com/datasets/manjeetsingh/retaildataset
- https://data.world/xfu022/australia-grocery-product-dataset

#### Environmental Store Data

- https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset

#### Transport Data (How long it's in trucks)

- https://www.kaggle.com/datasets/pingpang/lastmiledeliverytimes

#### Waste Data

- https://data.world/hxchua/waste-in-singapore
- https://www.kaggle.com/datasets/wastebase/plastic-bottle-waste

#### Grocery Products

- https://data.world/garyhoov/grocery-sales-by-store-type

#### Emissions Data

- https://data.world/makeovermonday/2020w16
- https://www.kaggle.com/datasets/skyliecampos/food-and-empact

#### Recipe Data 

- https://www.kaggle.com/datasets/kaggle/recipe-ingredients-dataset


#### Public Datasets

In addition to the supplied data sets, Google also have a repository of samples datasets which can be found [BigQuery Public Dataset](https://console.cloud.google.com/bigquery?project=bigquery-public-data&page=project&ws=!1m0).

Please feel free to add them via "ADD DATA" button on the top left of your BigQuery Explorer.

## Sample Apps

These are available as a simple one-click deployment for hosting applications on managed Cloud Run.

|Framework|Description|Deploy|
|---|---|---|
|[React.js](boilerplate-react|React Sample|[![Run on Google Cloud](https://deploy.cloud.run/button.svg)](https://deploy.cloud.run/?git_repo=https://github.com/gcloudan/boilerplates-cloudrun.git&dir=boilerplate-react)|
|[Sapper.js](boilerplate-sapper)|Sapper Sample|[![Run on Google Cloud](https://deploy.cloud.run/button.svg)](https://deploy.cloud.run/?git_repo=https://github.com/gcloudan/boilerplates-cloudrun.git&dir=boilerplate-sapper)|
|[Svelte Kit](boilerplate-sveltekit)|Sveltekit with TailwindCSS|[![Run on Google Cloud](https://deploy.cloud.run/button.svg)](https://deploy.cloud.run/?git_repo=https://github.com/gcloudan/boilerplates-cloudrun.git&dir=boilerplate-sveltekit)|
|[Nuxt.js](boilerplate-nuxt)|Nuxt.js with TailwindCSS and TypeScript|[![Run on Google Cloud](https://deploy.cloud.run/button.svg)](https://deploy.cloud.run/?git_repo=https://github.com/gcloudan/boilerplates-cloudrun.git&dir=boilerplate-nuxt)|
|[Next.js](boilerplate-next)|Next.js with TailwindCSS|[![Run on Google Cloud](https://deploy.cloud.run/button.svg)](https://deploy.cloud.run/?git_repo=https://github.com/gcloudan/boilerplates-cloudrun.git&dir=boilerplate-next)|

## Resources

Additional information and resources are available at the links below:

- [Howto for JupyterLab Notebooks](https://jupyterlab.readthedocs.io/en/stable/user/notebook.html)

## Additional Resources

- [Introduction to Vertex AI Workbench](https://cloud.google.com/vertex-ai/docs/workbench/introduction)
- [Vertex AI Jupyter Notebook tutorials](https://cloud.google.com/vertex-ai/docs/tutorials/jupyter-notebooks#vertex-ai-workbench)
