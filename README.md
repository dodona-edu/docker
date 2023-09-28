# Dodona docker image

This repository contains the files to create a Dodona docker image. A nightly version is published every night based on the develop branch of the main Dodona repo.

## Usage

```bash
git clone https://github.com/dodona-edu/dodona
git clone https://github.com/dodona-edu/docker-image
cp docker-image/* dodona/
cd dodona/
docker-compose up -d
```
