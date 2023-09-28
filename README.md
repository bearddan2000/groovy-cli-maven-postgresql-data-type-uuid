# groovy-cli-maven-postgresql-data-type-uuid

## Description
Creates a small table `dog` that uses
a uuid data type.

A groovy maven build, that connects to postgresql database.

## Tech stack
- groovy
- maven
  - log4j
  - postgresql drivers

## Docker stack
- postgresql:alpine
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
