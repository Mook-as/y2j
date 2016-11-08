# y2j-docker

This is a docker image for [echojc/y2j](https://github.com/echojc/y2j) to
attempt to reduce the image size.  That is, it's a static go binary instead of
a whole Debian image.

## Installation

```bash
docker run --rm mookas/y2j | sudo sh -
```

You might want to examine the output before running it with sudo — but it's just
hard-coded in the Dockerfile anyway.
