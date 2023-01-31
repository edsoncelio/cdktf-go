# CDK for Terraform - with Go

A few examples using [CDKTF](https://developer.hashicorp.com/terraform/cdktf) with Golang to compare with HCL.

To install - check the [installation guide](https://developer.hashicorp.com/terraform/tutorials/cdktf/cdktf-install#install-cdktf).

## Commands
Initializing the project:
```shell
$ cdktf init --template="go" --providers="aws@~>4.0"
```
Running:
```shell
$ cdktf deploy
```

To generate `.json` files (that can be executed by terraform commands):
```shell
$ ckdtf synth
```

## features to validate
 - [ ] variables
 - [ ] outputs
 - [ ] datasources
 - [ ] modules (stacks)
 - [ ] built-in functions
 - [ ] backends
 





