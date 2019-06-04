# terraform-consul-cluster-aws

This is a terraform project to deploy a 3 node cluster of consul on AWS.

## TODO

### Packer code
- [ ] script to download and install consul
- [ ] create base VM with consul
- [ ] test AMI with kitchen-test, write test to test consul

### Terraform code

- [ ] terraform code to create 3 vm using custom AMI
- [ ] script to configure consul for 1 cluster
- [ ] run the consul service
- [ ] make the code a module
- [ ] add kitchen-test code to test module does what is supposed to do
- [ ] consume this a module with version in private module registry

## DONE
