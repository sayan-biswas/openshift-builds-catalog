# OpenShift Builds File-Based Catalog

File-Based Catalog for Red Hat OpenShift Builds Operator

## How to update

Update config.yaml with a new bundle digest, order doesn't matter.
Use fbc-utils to generate and verify the new catalog, then commit and push back to this repo.

```
$ git clone https://github.com/ASzc/fbc-utils.git temp
$ temp/generate.sh
$ temp/verify-catalog.sh

