# basic Azure with terraform

## Install Azure CLI
```bash
brew update && brew install azure-cli       
```

## install terraform
```bash
brew tap hashicorp/tap
brew install hashicorp/tap/terraform
```

## Login into azure
```bash
az login
```

## init terraform
```bash
sudo terraform init          
```

## plan the deployment
```bash
sudo terraform plan     
```

## Deploy
```bash
sudo terraforn apply     
```

## Destroy 
```bash
 sudo terraform destroy   
```