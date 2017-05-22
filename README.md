pup
===

pup is a command line tool for processing HTML. It reads from stdin, prints to stdout, and allows the user to filter parts of the page using CSS selectors.

Inspired by jq, pup aims to be a fast and flexible way of exploring HTML from the terminal.

See the official [`pup` GithHub project](https://github.com/ericchiang/pup).

# How to use?

Simply build the image using `docker build -t pup:local .`

and run it with all needed parameter:

```console
wget -qO- https://example.com | docker run --rm pup:local
```

That's it.


# Additional Information

The user you use to push the README.md need to be admin of the repository.


# Updates and updating

To update your setup simply pull the newest image version from docker hub and run it.


# License

View [license information](https://github.com/ericchiang/pup) for the software contained in this image.

# Supported Docker versions

This image is officially supported on Docker version 17.03.1-CE.

Support for older versions (down to 1.12) is provided on a best-effort basis.

Please see [the Docker installation documentation](https://docs.docker.com/installation/) for details on how to upgrade your Docker daemon.


# User Feedback

## Issues

If you have any problems with or questions about this image, please contact us through a [GitHub issue](https://github.com/SISheogorath/pup-docker/issues).


## Contributing

You are invited to contribute new features, fixes, or updates, large or small; we are always thrilled to receive pull requests, and do our best to process them as fast as we can.
