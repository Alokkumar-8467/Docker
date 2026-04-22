## what Is Docker?

Virtualization software

Makes developing and deploying applications much easier

Packages application with all the necessary dependencies,
configuration, system tools and runtime

A standardized unit, that has everything the application needs to run.

Potable artifact, easily shared and distributed.

## What problem Docker solves?

### Development process before containers?
Each developer needs to install and configure all services directly on their OS on their local machine.

Installation process different for each OS envirmnment
Many steps, where something can go wrong.

### Developers process with containers?

Own isolated envirenment
Postgres package with all dependencies and configs

Start service as a Docker container using a 1 Docker command

Command same for all OS
Command same for all services
Standardizes process of running any services on any local dev environment
Easy to run different versionds of same app without any conflicts.

### Deployment process before containers?
Artifact and instructions handed over to Ops team
Ops team handles installing and configuring apps and its dependencies

### Problem before containers
Installations and configurations done directly on the server's OS.

