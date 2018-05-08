# ami-debian
Base Debian AMI

This will grab the latest EC2-ready Debian Stretch AMI off the shelf, run automated configurations on it, and pack it up as a private, reusable AMI.

It also demonstrates a few concepts:

1. no credentials need to be set in packer; set them [properly], [elsewhere]. 
2. variables can be set and reused
3. there is a method to search for the latest AMI of a specification
4. additional volumes of a type can be added
5. environment variables can be set/reset once
6. environment variables can be called from subsequent scripts

This is a good place to start. And remember...


This is a test. This is _only_ a test.

[elsewhere]:https://github.com/todd-dsm/mac-ops/wiki/Install-awscli
[properly]:https://docs.aws.amazon.com/sdk-for-java/v1/developer-guide/setup-credentials.html