docker-nginx-builder
====================

Builds nginx inside a docker container against the target version and then exports the resultant pkg

* Packer builds the main image.
* Packer calls ansible to run host.yml
