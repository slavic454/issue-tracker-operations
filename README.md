# Operations for issue-tracker application

## Create docker network

```shell
docker network create issue-tracker
 ```

## Run docker containers

```shell
docker-compose up -d
 ```

## Seed mongo database with example data

```shell
mongoimport --db issueTracker --collection issues issues.json
 ```

 ## Aplication entry point

 ```shell
http://localhost:8181
 ```