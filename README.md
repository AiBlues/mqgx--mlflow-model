# {{  PROJECT_NAME }}

{{ DESCRIPTION }}

# Sample ML Flow Project

... works with Maquette MLFlow Stack

```bash
$ export MLFLOW_TRACKING_URI=http://localhost:5000 && \
    export AWS_ACCESS_KEY_ID=access && \
    export AWS_SECRET_ACCESS_KEY=secret1234 && \
    export AWS_DEFAULT_REGION=mzg && \
    export MLFLOW_S3_ENDPOINT_URL=http://localhost:9000

$ mlflow run .
```