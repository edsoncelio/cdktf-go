# cdktf-golang
A few examples using CDKTF with Golang to compare with HCL.


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
$ ckdtf sync
```

## features to validate
 - [ ] variables
 - [ ] outputs
 - [ ] datasources
 - [ ] modules (stacks)
 - [ ] built-in functions
 - [ ] backends
 





