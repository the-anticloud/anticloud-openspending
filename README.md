# OPENSPENDING

> Anticloud offline package — upstream: openspending/openspending @ `master`.

## What This Project Does

The project aims to build and use open source tools and datasets to gather and analyse the financial transactions of governments around the world.

## Upstream README

# OpenSpending

[![Build Status](https://travis-ci.org/openspending/openspending.svg?branch=master)](https://travis-ci.org/openspending/openspending)
[![Issues](https://img.shields.io/badge/issue-tracker-orange.svg)](https://github.com/openspending/openspending/issues)
[![Docs](https://img.shields.io/badge/docs-latest-blue.svg)](http://docs.openspending.org/)
[![Discord](https://img.shields.io/discord/724381522966085712.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://discord.gg/xvS9hwj)

OpenSpending is a project to make government finances easier to explore and understand. It started out as "Where does my money go", a platform to visualize the United Kingdom's state finance, but has been renamed and restructured to allow arbitrary financial data to be loaded and displayed.

The main use for the software is the site [openspending.org](http://openspending.org) which aims to track government finance around the world.

OpenSpending's code is licensed under the GNU Affero Licence except where otherwise indicated. A copy of this licence is available in the file [LICENSE.txt](LICENSE.txt).

OpenSpending is a microservices platform made up of a number of separate apps, each maintained in their own git repository. This repository contains [docker-compose](https://docs.docker.com/compose/) files that can be used run an instance of Openspending for development, or as the basis for a production deployment. This repository also acts as a central hub for managing [issues](https://github.com/openspending/openspending/issues) for the entire platform.

### What are these files?

Most applications that make up the OpenSpending platform are maintained in their own repositories, with their own Dockerfiles, built and pushed to the [OpenSpending organisation on Docker Hub](https://hub.docker.com/r/openspending):

- [os-api](https://github.com/openspending/os-api)
- [os-conductor](https://github.com/openspending/os-conductor)
- [os-viewer](https://github.com/openspending/os-viewer)
- [os-explorer](https://github.com/openspending/os-explorer)
- [os-admin](https://github.com/openspending/os-admin)
- [os-packager](https://github.com/openspending/os-packager)
- [os-fdp-adapters](https://github.com/openspending/os-fdp-adapters)
- [os-data-importers](https://github.com/openspending/os-data-importers)

This repository maintains docker-compose files used to help get you started with the platform.

`docker-compose.base.yml`: This is the main docker-compose file for OpenSpending specific services. All installations will use this as the basis for running the platform.

`docker-compose.dev-services.yml`: This defines backing services used by the platform, such as Redis, ElasticSearch, and PostgreSQL. This file also includes fake-s3 in place of AWS S3, so you don't have to set up an S3 bucket for development. It is not recommended to use this for production.

`docker-compose.data-importers.yml`: This defines the services used for the separate [os-

## License

Upstream terms preserved in `THIRD_PARTY_LICENSES/`. Overlay licensed under Anticommons 0.1.0.

## Verification

Recompute the SHA3-256 of `BENCH.json` and compare to this package’s register. Any drift = invalid package.
