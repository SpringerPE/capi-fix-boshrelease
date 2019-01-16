# Add-on BOSH Release for capi-release (CF deployment)

Add-on release which fixes https://github.com/cloudfoundry/cloud_controller_ng/issues/1107
by patching the buggy ruby file.

## Usage

Deploy this release together with capi-release


# Dev

Make your changes, recreate it and upload it to Bosh Director
 

```
bosh create release --final --force
bosh upload release
```


# License

Apache 2.0 License

