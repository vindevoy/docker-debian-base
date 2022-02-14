# docker-debian-base

Debian base image

## Purpose

- This image is created as a base image for the rest of the images I build using Debian.
- The first version of this image, was based on Debian 10.0.
- The version number of my images corresponds (as of 11.0) with the version of Debian.
- It's always the slim Debian image that is used.
- The image sets the timezone.

## Versioning

Considering the versions are labelled x.y-z, the meaning of each version is:

- x.y: corresponds with the version of Debian slim version
- z: corresponds with the build of this image