

# CREATE THE DATABRICKS CLUSTER

STEP 1: Make sure your Databricks cluster is created

STEP 2: Upload you csv file for data to  FILESTORE/DATA

STEP 3: Create the token in user settings within Databricks

STEP 4: Add the token to the development environment as DATABRICKS_TOKEN

STEP 5: Push the Code to your github repo and the Workflow will create a table within Databricks

NOTES: 
-If you have you workbook file saved locally use local-notebook-path other wise execute you workbook from Databricks
with workspace-notebook-path 

- If you need to run multiple workbooks Add to the workflow or add multiple workflows