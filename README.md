# chromeos-docker
Bash script to launch ChromeOS with Chromebrew in Docker

## Prerequisites
- [QEMU](https://www.qemu.org/)
- [Docker](https://hub.docker.com/search?offering=community&operating_system=linux&q=&type=edition)
- [qemu-user-static](https://github.com/multiarch/qemu-user-static)

## Installation
```bash
$ git clone git@github.com:uberhacker/chromeos-docker.git
$ cd chromeos-docker
$ sudo cp chromeos-docker /usr/local/bin
$ cd /path/to/projects
$ git clone git@github.com:skycocker/chromebrew.git
$ mkdir pkg_cache
$ docker run --rm --privileged multiarch/qemu-user-static --reset -p yes
```

## Usage
```bash
$ cd /path/to/projects (the parent directory where skycocker/chromebrew was cloned)
$ chromeos-docker armv7l|i686|x86_64
```

## Troubleshooting
TBD
