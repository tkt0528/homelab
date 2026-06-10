# Target Architecture

## Goals

* Separate production and development environments.
* Standardize service deployment with Docker.
* Improve maintainability and reproducibility.
* Implement monitoring and backup solutions.
* Build a portfolio-quality infrastructure environment.

## Production Environment

Production services provide stable access to users.

Services:

* Samba
* Kavita
* Jellyfin

Characteristics:

* Stable operation
* Limited changes
* Regular backup
* Monitored health status

## Development Environment

Development services are used for testing and learning.

Purpose:

* Test new containers
* Verify configuration changes
* Practice Linux administration
* Validate upgrades before production deployment

Characteristics:

* Disposable environment
* Frequent changes allowed
* Independent from production

## Container Platform

Docker will be used as the standard deployment platform.

Benefits:

* Reproducible deployments
* Version-controlled configurations
* Easier migration between hosts
* Simplified maintenance

## Monitoring

Monitoring should provide visibility into system health.

Targets:

* Host resource usage
* Container status
* Storage usage
* Service availability

## Backup

Backup should protect both configuration and data.

Targets:

* Service configuration files
* Docker compose files
* Application data
* Documentation repository

## Storage

All media and document services should use centralized NAS storage.

Shared Data:

* Manga
* Videos
* Documents
* Temporary files
