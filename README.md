# Launch a simple web site in a load balanced and highly available manner utilizing automation and AWS best practices

We are using Terraform and Packer in below example 
```
https://www.terraform.io/
https://www.packer.io/

```
cd s3
```
terraform init
terraform plan
terraform apply 
```
cd iam
```
terraform init
terraform plan
terraform apply 
```

cd Packer
```
packer build packer.json
```

cd Infra 
```
terraform init
terraform plan
terraform apply 
```

In Order to use Route53 as your DNS service After Route53 is up and Running you will have to update Name Servers inside domain from NS Record inside hosted zone you have
# http://approach1.net/
