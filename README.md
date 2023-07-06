# chromeos-docker
Bash script to launch ChromeOS with Chromebrew in Docker

## Prerequisites
- [Docker](https://hub.docker.com/search?offering=community&operating_system=linux&q=&type=edition)

## Installation
```bash
$ git clone https://github.com/uberhacker/chromeos-docker.git
$ cd chromeos-docker
$ sudo cp chromeos-docker /usr/local/bin
$ cd /path/to/projects
$ git clone https://github.com/chromebrew/chromebrew.git
$ mkdir pkg_cache
```

## Usage
```bash
$ cd /path/to/projects (the parent directory where chromebrew was cloned)
$ chromeos-docker armv7l|i686|x86_64
```

## Troubleshooting
TBD
