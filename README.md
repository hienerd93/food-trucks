# SF Food Trucks

> San Francisco's finger-licking street food now at your fingertips.

![img](shot.png)

The app is built with [Flask](http://flask.pocoo.org/) on the backend and [Elasticsearch](http://elastic.co/) is the search engine powering the searches. The front-end is built with [React](http://facebook.github.io/react/) and the beautiful maps are courtesy of [Mapbox](https://www.mapbox.com/).

## Docker Network
```
$ ./setup-docker.sh
```

## Docker Compose
```
$ docker-compose up
```

The app can also be easily deployed on AWS Elastic Container Service. Once you have [aws ecs cli](http://docs.aws.amazon.com/AmazonECS/latest/developerguide/ECS_CLI_installation.html) installed, you can run the following to deploy it on ECS!
```
$ ./setup-aws-ecs.sh
```