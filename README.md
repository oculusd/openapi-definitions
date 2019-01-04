# openapi-definitions

The OpenAPI definition files for OculusD.com, Inc API based on
[OpenAPI version 3](https://swagger.io/docs/specification/basic-structure/).

## Status

This documentation is still in very active development and the actual API end-points may not exist yet or themselves
very unstable as development is being done.

Please watch out for important announcements [on our blog](https://www.oculusd.com/blog) or subscribe to notifications
on this repository by [adding a watch](https://help.github.com/articles/watching-and-unwatching-repositories/).

## Using the Swagger UI

The `oculusd-api.yml` file is the main file and also the one we use to edit in the Swagger Editor. 

The instructions is based on the [Swagger UI Documentation](https://github.com/swagger-api/swagger-ui) as on
4 January 2018

First, clone this repository and change into the `openapi-definitions` directory:

    $ git clone https://github.com/oculusd/openapi-definitions.git
    $ cd openapi-definitions/

Commands:

    $ docker pull swaggerapi/swagger-ui

Open a web browser [and point to 127.0.0.1:83/](http://127.0.0.1:83/).

When the Swagger UI is open, point to the YAML location [https://raw.githubusercontent.com/oculusd/openapi-definitions/master/oculusd-api.yml](https://raw.githubusercontent.com/oculusd/openapi-definitions/master/oculusd-api.yml)
