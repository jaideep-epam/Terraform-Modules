Start by setting up you cloud workspace

cd setup_workspace.

Run to following commands in order:

terraform init

terraform apply or terraform apply -var-file="$HOME/.aws/terraform.tfvars"


Deploy:-

Change directory to deploy dir (previous command auto generates backend.hcl)

cd ../deploy

Open dev.auto.tfvars and edit the default values to match your enviornment

terraform apply or terraform apply -var-file="$HOME/.aws/terraform.tfvars"
