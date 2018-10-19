# terraform-vsphere-photon

copy variables.json_example to variables.json and edit them accordingly
```
$ terraform -var-file='variables.json' init
$ terraform -var-file='variables.json' plan
$ terraform -var-file='variables.json' apply
$ terraform -var-file='variables.json' destroy
```

for logs
```
$ export TF_LOG=DEBUG
$ export TF_LOG_PATH=terraform.log
```
