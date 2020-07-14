# rlt_terraform_k8s_test
This repo holds the assets needed for our Terraform, Kubernetes, And Helm coding test

## Test Overview
The purpose of this test is to demonstrate your knowledge in the following areas: 
* GCP
* Terraform
* Kubernetes (GKE)
* Helm

## Test Instructions
1) The first thing we would like for you to do is setup a new google project. Give the project a name, following this convention: **rlt-test-firstname-lastname**.
2) Create a service account that will be used when running Terraform. Please make the service account project owner. 
3) Setup a GCS bucket that will hold your terraform remote state file. 
4) Create Terraform code to deploy the Infrastructure. The infrastructure diagram can be found here. The infrastructure should contain the following:
	1) VPC Network
	2) Regional GKE Cluster with an auto scaling node pool.
5) Deploy the helm chart supplied in this repo into the kubernetes cluster, from within Terraform. The helm chart will have some bugs/errors that you will need to fix.  
	1) Setup helm/tiller
	2) Deploy the helm chart
	3) Debug the errors in the helm chart

