#terraform-provider-hpegl

## Introduction

This is the main repo for the GreenLake terraform provider which provides terraform support fot GreenLake services.

We're currently in the process of open sourcing all the code, meanwhile, this repository holds the following:

1. HPEGL release binaries,
1. HPEGL documentation,
1. A script to automate the provider installation for Linux.

## Installation

### Linux

Use the script `tools/install-hpegl-provider.sh` to automatically download and install hpegl provider:

```shell
bash <(curl -sL https://raw.githubusercontent.com/HewlettPackard/terraform-provider-hpegl/main/tools/install-hpegl-provider.sh)
```

The above will install the latest available release. To install a specific release:

```shell
VERSION=v0.0.5 bash <(curl -sL https://raw.githubusercontent.com/HewlettPackard/terraform-provider-hpegl/main/tools/install-hpegl-provider.sh)
```


### Windows

Use the script `tools/install-hpegl-provider-windows.ps1` to automatically download and install hpegl provider:

```shell
 . { iwr -useb https://raw.githubusercontent.com/HewlettPackard/terraform-provider-hpegl/Windows-Install/tools/install-hpegl-provider-windows.ps1 } | iex; install)
```

<!-- The above will install the latest available release. To install a specific release:

```shell
VERSION=v0.0.5 bash <(curl -sL https://raw.githubusercontent.com/HewlettPackard/terraform-provider-hpegl/main/tools/install-hpegl-provider.sh)
``` -->