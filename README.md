# alpine-envsubst

This Docker image is the latest alpine:3 image with the envsubst (gettext package) installed.

It will be automatically built nightly, so it is always up-to-date.

The intended use cases are Kubernetes init containers when I have to replace variables in template files.