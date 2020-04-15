Reviewing pointers:
Unit tests for the API: unittests/ApiTests.py

Unit tests for the model: unittests/ModelTests.py

Unit tests for the logging: unittests/LoggerTests.py

Run all of the unit tests with a single script: run-tests.py

Read/write unit tests are isolated from production models and logs

APIs for training and prediction: /app.py

Data ingestion automation pipeline: /cslib.py

Multiple models comparison: notebooks/

EDA investigation with visualizations: notebooks/data_ingestion_eda_part1.ipynb

Containerization within a working Docker image: /Dockerfile

Visualization to compare the model to the baseline model: notebooks/time_series_iteration.ipynb
