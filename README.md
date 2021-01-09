# PHP on Azure App Service for Containers using OpenLiteSpeed
[![docker pulls](https://img.shields.io/docker/pulls/johnwcarew/azure-app-service-openlitespeed-php?style=flat&color=blue)](https://hub.docker.com/r/johnwcarew/azure-app-service-openlitespeed-php)

This repository contains Docker images for PHP running on Azure App Service Linux container using OpenLiteSpeed web server.

## Image Repository
https://hub.docker.com/r/johnwcarew/azure-app-service-openlitespeed-php

## Known issues
None.

## Build Components

| Component     | Version      |
| ------------- | ------------ |
| Linux         | Ubuntu 18.04 |
| OpenLiteSpeed | 1.6.18       |
| PHP           | 7.4          |

SSH has been enabled on port 2222 to be able to SSH to the container in Azure App Service.

## Deployment

### ARM Template
A sample Azure arm template is available in the [github repo](https://github.com/johnwc/azure-app-service-openlitespeed-php-container/blob/master/infra.arm.json). 
* The app plan must be an Azure App Service Linux plan.