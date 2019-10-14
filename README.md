# docker-node10 #
## A largely compatible node 10 alpine base image baked to respond to vulnerabilities ##

As node-alpine is still using alpine 3.9 - the base image is vulnerable -
[CVE-2019-14697](https://github.com/alpinelinux/docker-alpine/issues/34).

This is fixed in alpine 3.10/latest and as there are other vulnerabilities coming to light so we will aim to keep
this image up to date as they pop up.

As I am planning to switch to node 12 soon - once it is LTS - I will likely branch off the base alpine docker node
image and use alpine 3.10 if official support still isn't merged.

This is a patched image based on alpine 3.10.1.
