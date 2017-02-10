[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/echi-converter.svg)](https://hub.docker.com/r/rubygem/echi-converter/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/echi-converter.svg)](https://hub.docker.com/r/rubygem/echi-converter/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/echi-converter.svg)](https://hub.docker.com/r/rubygem/echi-converter/)
[![Gem Downloads](https://img.shields.io/gem/dt/echi-converter.svg)](https://rubygems.org/gems/echi-converter/)
# echi-converter

Auto-Generated Docker image for echi-converter to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/echi-converter`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/echi-converter`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/echi-converter`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/echi-converter/)
