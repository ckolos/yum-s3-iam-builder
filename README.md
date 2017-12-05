# yum-s3-iam-builder
For building that damn RPM

Assumes you've already ```docker pull```'d ckolos/rpmbuild{6,7}

* From the checked out directory, run ```build {6,7}```
* Depending on the argument, an rpm6 or rpm7 directory will be created in the checkout dir
* The resulting RPM is in rpm{6,7}/noarch
