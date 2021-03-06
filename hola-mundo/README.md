# Supported tags and respective `Dockerfile` links

-	[`latest` (*hola-mundo/Dockerfile*)](https://github.com/docker-library/hello-world/blob/85fd7ab65e079b08019032479a3f306964a28f4d/hola-mundo/Dockerfile)

[![](https://badge.imagelayers.io/hola-mundo:latest.svg)](https://imagelayers.io/?images=hola-mundo:latest)

For more information about this image and its history, please see [the relevant manifest file (`library/hola-mundo`)](https://github.com/docker-library/official-images/blob/master/library/hola-mundo). This image is updated via [pull requests to the `docker-library/official-images` GitHub repo](https://github.com/docker-library/official-images/pulls?q=label%3Alibrary%2Fhola-mundo).

For detailed information about the virtual/transfer sizes and individual layers of each of the above supported tags, please see [the `hola-mundo/tag-details.md` file](https://github.com/docker-library/docs/blob/master/hola-mundo/tag-details.md) in [the `docker-library/docs` GitHub repo](https://github.com/docker-library/docs).

# ¡Hola, DockerCon EU 2015 (Barcelona)!

This image is a vanity variant of [the `hello-world` image](https://hub.docker.com/_/hello-world/) created specifically for [DockerCon EU 2015](http://europe-2015.dockercon.com/). Its use is discouraged.

```console
$ docker run hola-mundo

¡Hola de DockerCon EU 2015 (Barcelona)!
This message shows that your installation appears to be working correctly.

To generate this message, Docker took the following steps:
 1. The Docker client contacted the Docker daemon.
 2. The Docker daemon pulled the "hola-mundo" image from the Docker Hub.
 3. The Docker daemon created a new container from that image which runs the
    executable that produces the output you are currently reading.
 4. The Docker daemon streamed that output to the Docker client, which sent it
    to your terminal.

To try something more ambitious, you can run an Ubuntu container with:
 $ docker run -it ubuntu bash

Share images, automate workflows, and more with a free Docker Hub account:
 https://hub.docker.com

For more examples and ideas, visit:
 https://docs.docker.com/engine/userguide/

```

See [the `hello-world` image description](https://hub.docker.com/_/hello-world/) for more information about this image (and its construction).

# Supported Docker versions

This image is officially supported on Docker version 1.11.2.

Support for older versions (down to 1.6) is provided on a best-effort basis.

Please see [the Docker installation documentation](https://docs.docker.com/installation/) for details on how to upgrade your Docker daemon.

# User Feedback

## Documentation

Documentation for this image is stored in the [`hola-mundo/` directory](https://github.com/docker-library/docs/tree/master/hola-mundo) of the [`docker-library/docs` GitHub repo](https://github.com/docker-library/docs). Be sure to familiarize yourself with the [repository's `README.md` file](https://github.com/docker-library/docs/blob/master/README.md) before attempting a pull request.

## Issues

If you have any problems with or questions about this image, please contact us through a [GitHub issue](https://github.com/docker-library/hello-world/issues). If the issue is related to a CVE, please check for [a `cve-tracker` issue on the `official-images` repository first](https://github.com/docker-library/official-images/issues?q=label%3Acve-tracker).

You can also reach many of the official image maintainers via the `#docker-library` IRC channel on [Freenode](https://freenode.net).

## Contributing

You are invited to contribute new features, fixes, or updates, large or small; we are always thrilled to receive pull requests, and do our best to process them as fast as we can.

Before you start to code, we recommend discussing your plans through a [GitHub issue](https://github.com/docker-library/hello-world/issues), especially for more ambitious contributions. This gives other contributors a chance to point you in the right direction, give you feedback on your design, and help you find out if someone else is working on the same thing.
