# Packer to build customized AMI using Packer

Follow below steps in order to use the packer template application.

## Validate template

```
packer validate -var-file=./vars.json ubuntu-ami.json
```

## Build the Packer Template 

```
packer build -var-file=./vars.json ubuntu-ami.json
```