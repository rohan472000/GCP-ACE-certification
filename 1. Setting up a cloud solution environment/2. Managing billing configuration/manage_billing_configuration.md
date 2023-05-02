1. Creating one or more billing accounts:

A billing account is used to manage billing for GCP services. 
You can create a new billing account using the Cloud Console or the Cloud Billing API. 
Here's an example command to create a new billing account:

```
gcloud alpha billing accounts create --description="[DESCRIPTION]" --display-name="[DISPLAY_NAME]"
```

2. Linking projects to a billing account:

To use GCP services within a project, the project must be linked to a billing account. 
You can link a project to a billing account using the Cloud Console or the Cloud Billing API. 
Here's an example command to link a project to a billing account:

```
gcloud beta billing projects link [PROJECT_ID] --billing-account=[BILLING_ACCOUNT_ID]
```

3. Establishing billing budgets and alerts:

Billing budgets and alerts help you monitor and control costs for GCP services.
You can set up billing budgets and alerts using the Cloud Console or the Cloud Billing API. 
Here's an example command to create a new budget and set an alert threshold:

```
gcloud alpha billing budgets create [BUDGET_NAME] --billing-account=[BILLING_ACCOUNT_ID] --amount=[AMOUNT] 
--currency=[CURRENCY_CODE] --threshold-percentage=[THRESHOLD_PERCENTAGE] --all-updates-rule
```

4. Setting up billing exports:

Billing exports allow you to export your GCP billing data to other systems for analysis and reporting. 
You can set up billing exports using the Cloud Console or the Cloud Billing API. 
Here's an example command to export billing data to a BigQuery table:

```
gcloud alpha billing export bq [BQ_DATASET_ID] --billing-account=[BILLING_ACCOUNT_ID] --table-prefix=[TABLE_PREFIX] 
--bucket-name=[BUCKET_NAME] --format=csv
```
