# Supported tags and respective `Dockerfile` links

-	[`1.6.4`, `1.6` (*1.6/Dockerfile*)](https://github.com/docker-library/golang/blob/fddc8c18282871b554cb0d74780767690bdda3ec/1.6/Dockerfile)
-	[`1.6.4-onbuild`, `1.6-onbuild` (*1.6/onbuild/Dockerfile*)](https://github.com/docker-library/golang/blob/ce284e14cdee73fbaa8fb680011a812f272eae2e/1.6/onbuild/Dockerfile)
-	[`1.6.4-wheezy`, `1.6-wheezy` (*1.6/wheezy/Dockerfile*)](https://github.com/docker-library/golang/blob/fddc8c18282871b554cb0d74780767690bdda3ec/1.6/wheezy/Dockerfile)
-	[`1.6.4-alpine`, `1.6-alpine` (*1.6/alpine/Dockerfile*)](https://github.com/docker-library/golang/blob/bfbd521de2942d10d96b14f99c491536490db018/1.6/alpine/Dockerfile)
-	[`1.6.4-windowsservercore`, `1.6-windowsservercore` (*1.6/windows/windowsservercore/Dockerfile*)](https://github.com/docker-library/golang/blob/3bccc597c14b6274d7855d968f881ac6407b0a61/1.6/windows/windowsservercore/Dockerfile)
-	[`1.6.4-nanoserver`, `1.6-nanoserver` (*1.6/windows/nanoserver/Dockerfile*)](https://github.com/docker-library/golang/blob/fddc8c18282871b554cb0d74780767690bdda3ec/1.6/windows/nanoserver/Dockerfile)
-	[`1.7.5`, `1.7` (*1.7/Dockerfile*)](https://github.com/docker-library/golang/blob/349270dbc128e396888cb2423ffc85d2c3039a27/1.7/Dockerfile)
-	[`1.7.5-onbuild`, `1.7-onbuild` (*1.7/onbuild/Dockerfile*)](https://github.com/docker-library/golang/blob/2372c8cafe9cc958bade33ad0b8b54de8869c21f/1.7/onbuild/Dockerfile)
-	[`1.7.5-wheezy`, `1.7-wheezy` (*1.7/wheezy/Dockerfile*)](https://github.com/docker-library/golang/blob/349270dbc128e396888cb2423ffc85d2c3039a27/1.7/wheezy/Dockerfile)
-	[`1.7.5-alpine`, `1.7-alpine` (*1.7/alpine/Dockerfile*)](https://github.com/docker-library/golang/blob/349270dbc128e396888cb2423ffc85d2c3039a27/1.7/alpine/Dockerfile)
-	[`1.7.5-alpine3.5`, `1.7-alpine3.5` (*1.7/alpine3.5/Dockerfile*)](https://github.com/docker-library/golang/blob/349270dbc128e396888cb2423ffc85d2c3039a27/1.7/alpine3.5/Dockerfile)
-	[`1.7.5-windowsservercore`, `1.7-windowsservercore` (*1.7/windows/windowsservercore/Dockerfile*)](https://github.com/docker-library/golang/blob/3bccc597c14b6274d7855d968f881ac6407b0a61/1.7/windows/windowsservercore/Dockerfile)
-	[`1.7.5-nanoserver`, `1.7-nanoserver` (*1.7/windows/nanoserver/Dockerfile*)](https://github.com/docker-library/golang/blob/349270dbc128e396888cb2423ffc85d2c3039a27/1.7/windows/nanoserver/Dockerfile)
-	[`1.8.0`, `1.8`, `1`, `latest` (*1.8/Dockerfile*)](https://github.com/docker-library/golang/blob/132cd70768e3bc269902e4c7b579203f66dc9f64/1.8/Dockerfile)
-	[`1.8.0-onbuild`, `1.8-onbuild`, `1-onbuild`, `onbuild` (*1.8/onbuild/Dockerfile*)](https://github.com/docker-library/golang/blob/132cd70768e3bc269902e4c7b579203f66dc9f64/1.8/onbuild/Dockerfile)
-	[`1.8.0-stretch`, `1.8-stretch`, `1-stretch`, `stretch` (*1.8/stretch/Dockerfile*)](https://github.com/docker-library/golang/blob/132cd70768e3bc269902e4c7b579203f66dc9f64/1.8/stretch/Dockerfile)
-	[`1.8.0-alpine`, `1.8-alpine`, `1-alpine`, `alpine` (*1.8/alpine/Dockerfile*)](https://github.com/docker-library/golang/blob/132cd70768e3bc269902e4c7b579203f66dc9f64/1.8/alpine/Dockerfile)
-	[`1.8.0-windowsservercore`, `1.8-windowsservercore`, `1-windowsservercore`, `windowsservercore` (*1.8/windows/windowsservercore/Dockerfile*)](https://github.com/docker-library/golang/blob/132cd70768e3bc269902e4c7b579203f66dc9f64/1.8/windows/windowsservercore/Dockerfile)
-	[`1.8.0-nanoserver`, `1.8-nanoserver`, `1-nanoserver`, `nanoserver` (*1.8/windows/nanoserver/Dockerfile*)](https://github.com/docker-library/golang/blob/132cd70768e3bc269902e4c7b579203f66dc9f64/1.8/windows/nanoserver/Dockerfile)

For more information about this image and its history, please see [the relevant manifest file (`library/golang`)](https://github.com/docker-library/official-images/blob/master/library/golang). This image is updated via [pull requests to the `docker-library/official-images` GitHub repo](https://github.com/docker-library/official-images/pulls?q=label%3Alibrary%2Fgolang).

For detailed information about the virtual/transfer sizes and individual layers of each of the above supported tags, please see [the `repos/golang/tag-details.md` file](https://github.com/docker-library/repo-info/blob/master/repos/golang/tag-details.md) in [the `docker-library/repo-info` GitHub repo](https://github.com/docker-library/repo-info).

# What is Go?

Go (a.k.a., Golang) is a programming language first developed at Google. It is a statically-typed language with syntax loosely derived from C, but with additional features such as garbage collection, type safety, some dynamic-typing capabilities, additional built-in types (e.g., variable-length arrays and key-value maps), and a large standard library.

> [wikipedia.org/wiki/Go_(programming_language)](http://en.wikipedia.org/wiki/Go_%28programming_language%29)

![logo](https://raw.githubusercontent.com/docker-library/docs/01c12653951b2fe592c1f93a13b4e289ada0e3a1/golang/logo.png)

# How to use this image

## Start a Go instance in your app

The most straightforward way to use this image is to use a Go container as both the build and runtime environment. In your `Dockerfile`, writing something along the lines of the following will compile and run your project:

```dockerfile
FROM golang:1.6-onbuild
```

This image includes multiple `ONBUILD` triggers which should cover most applications. The build will `COPY . /go/src/app`, `RUN go get -d -v`, and `RUN go install -v`.

This image also includes the `CMD ["app"]` instruction which is the default command when running the image without arguments.

You can then build and run the Docker image:

```console
$ docker build -t my-golang-app .
$ docker run -it --rm --name my-running-app my-golang-app
```

*Note:* the default command in `golang:onbuild` is actually `go-wrapper run`, which includes `set -x` so the binary name is printed to stderr on application startup. If this behavior is undesirable, then adding `CMD ["app"]` (or `CMD ["myapp"]` if a [Go custom import path](https://golang.org/s/go14customimport) is in use) will silence it by running the built binary directly.

## Compile your app inside the Docker container

There may be occasions where it is not appropriate to run your app inside a container. To compile, but not run your app inside the Docker instance, you can write something like:

```console
$ docker run --rm -v "$PWD":/usr/src/myapp -w /usr/src/myapp golang:1.6 go build -v
```

This will add your current directory as a volume to the container, set the working directory to the volume, and run the command `go build` which will tell go to compile the project in the working directory and output the executable to `myapp`. Alternatively, if you have a `Makefile`, you can run the `make` command inside your container.

```console
$ docker run --rm -v "$PWD":/usr/src/myapp -w /usr/src/myapp golang:1.6 bash -c make
```

## Cross-compile your app inside the Docker container

If you need to compile your application for a platform other than `linux/amd64` (such as `windows/386`):

```console
$ docker run --rm -v "$PWD":/usr/src/myapp -w /usr/src/myapp -e GOOS=windows -e GOARCH=386 golang:1.6 go build -v
```

Alternatively, you can build for multiple platforms at once:

```console
$ docker run --rm -it -v "$PWD":/usr/src/myapp -w /usr/src/myapp golang:1.6 bash
$ for GOOS in darwin linux; do
>   for GOARCH in 386 amd64; do
>     go build -v -o myapp-$GOOS-$GOARCH
>   done
> done
```

# Image Variants

The `golang` images come in many flavors, each designed for a specific use case.

## `golang:<version>`

This is the defacto image. If you are unsure about what your needs are, you probably want to use this one. It is designed to be used both as a throw away container (mount your source code and start the container to start your app), as well as the base to build other images off of. This tag is based off of [`buildpack-deps`](https://registry.hub.docker.com/_/buildpack-deps/). `buildpack-deps` is designed for the average user of docker who has many images on their system. It, by design, has a large number of extremely common Debian packages. This reduces the number of packages that images that derive from it need to install, thus reducing the overall size of all images on your system.

## `golang:onbuild`

This image makes building derivative images easier. For most use cases, creating a `Dockerfile` in the base of your project directory with the line `FROM golang:onbuild` will be enough to create a stand-alone image for your project.

While the `onbuild` variant is really useful for "getting off the ground running" (zero to Dockerized in a short period of time), it's not recommended for long-term usage within a project due to the lack of control over *when* the `ONBUILD` triggers fire (see also [`docker/docker#5714`](https://github.com/docker/docker/issues/5714), [`docker/docker#8240`](https://github.com/docker/docker/issues/8240), [`docker/docker#11917`](https://github.com/docker/docker/issues/11917)).

Once you've got a handle on how your project functions within Docker, you'll probably want to adjust your `Dockerfile` to inherit from a non-`onbuild` variant and copy the commands from the `onbuild` variant `Dockerfile` (moving the `ONBUILD` lines to the end and removing the `ONBUILD` keywords) into your own file so that you have tighter control over them and more transparency for yourself and others looking at your `Dockerfile` as to what it does. This also makes it easier to add additional requirements as time goes on (such as installing more packages before performing the previously-`ONBUILD` steps).

## `golang:alpine`

This image is based on the popular [Alpine Linux project](http://alpinelinux.org), available in [the `alpine` official image](https://hub.docker.com/_/alpine). Alpine Linux is much smaller than most distribution base images (~5MB), and thus leads to much slimmer images in general.

This variant is highly recommended when final image size being as small as possible is desired. The main caveat to note is that it does use [musl libc](http://www.musl-libc.org) instead of [glibc and friends](http://www.etalabs.net/compare_libcs.html), so certain software might run into issues depending on the depth of their libc requirements. However, most software doesn't have an issue with this, so this variant is usually a very safe choice. See [this Hacker News comment thread](https://news.ycombinator.com/item?id=10782897) for more discussion of the issues that might arise and some pro/con comparisons of using Alpine-based images.

To minimize image size, it's uncommon for additional related tools (such as `git` or `bash`) to be included in Alpine-based images. Using this image as a base, add the things you need in your own Dockerfile (see the [`alpine` image description](https://hub.docker.com/_/alpine/) for examples of how to install packages if you are unfamiliar).

## `golang:windowsservercore`

This image is based on [Windows Server Core (`microsoft/windowsservercore`)](https://hub.docker.com/r/microsoft/windowsservercore/). As such, it only works in places which that image does, such as Windows 10 Professional/Enterprise (Anniversary Edition) or Windows Server 2016.

For information about how to get Docker running on Windows, please see the relevant "Quick Start" guide provided by Microsoft:

-	[Windows Server Quick Start](https://msdn.microsoft.com/en-us/virtualization/windowscontainers/quick_start/quick_start_windows_server)
-	[Windows 10 Quick Start](https://msdn.microsoft.com/en-us/virtualization/windowscontainers/quick_start/quick_start_windows_10)

# License

View [license information](http://golang.org/LICENSE) for the software contained in this image.

# Supported Docker versions

This image is officially supported on Docker version 1.13.1.

Support for older versions (down to 1.6) is provided on a best-effort basis.

Please see [the Docker installation documentation](https://docs.docker.com/installation/) for details on how to upgrade your Docker daemon.

# User Feedback

## Issues

If you have any problems with or questions about this image, please contact us through a [GitHub issue](https://github.com/docker-library/golang/issues). If the issue is related to a CVE, please check for [a `cve-tracker` issue on the `official-images` repository first](https://github.com/docker-library/official-images/issues?q=label%3Acve-tracker).

You can also reach many of the official image maintainers via the `#docker-library` IRC channel on [Freenode](https://freenode.net).

## Contributing

You are invited to contribute new features, fixes, or updates, large or small; we are always thrilled to receive pull requests, and do our best to process them as fast as we can.

Before you start to code, we recommend discussing your plans through a [GitHub issue](https://github.com/docker-library/golang/issues), especially for more ambitious contributions. This gives other contributors a chance to point you in the right direction, give you feedback on your design, and help you find out if someone else is working on the same thing.

## Documentation

Documentation for this image is stored in the [`golang/` directory](https://github.com/docker-library/docs/tree/master/golang) of the [`docker-library/docs` GitHub repo](https://github.com/docker-library/docs). Be sure to familiarize yourself with the [repository's `README.md` file](https://github.com/docker-library/docs/blob/master/README.md) before attempting a pull request.
