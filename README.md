# container-blueprints
DOKS Solution Blueprints

## my own actions:

## doks-with-terraform-flux
 - define terraform backend to share configuration (could be local if only one user)
   - `terraform init  --backend-config="access_key=$MINIO_ACCESS_KEY" --backend-config="secret_key=$MINIO_SECRET_KEY"`
