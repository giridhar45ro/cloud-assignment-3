1. Login to GCP Console.
2. Go to Vertex AI section from the Menu.
3. Select your Project.
4. Goto dataset section and create a dataset.
5. You can you your own dataset or Google BigQuery Dataset.
6. I have used bq:// bigquery-public-data.ml_datasets.ulb_fraud_detection this dataset.
7. Click on Create a model and give the necessary configuration.
8. Then train model providing max node hours.
9. Then go to models section there you can see all the Evaluation matries and Confusion matrices.
10. Then you can deploy the model by selecting an end point.
11. After Deploying you can Test the data by giving test values.
12. If you want you can also export the model.