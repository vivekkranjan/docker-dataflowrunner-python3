Reference: https://github.com/GoogleCloudPlatform/cloud-builders-community/tree/master/dataflow-python3
Pull Request: https://github.com/GoogleCloudPlatform/cloud-builders-community/pull/486/files

1. Assign permission:
gcloud auth configure-docker  gcr.io
gcloud services enable container.googleapis.com containerregistry.googleapis.com cloudkms.googleapis.com

2. Build using Dockerfile in:
gcloud builds submit --config=docker-cloudbuild.yaml









 