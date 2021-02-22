# WeNet Documentation

## Component availability

The production components can be reached at the following urls:

* service APIs: https://wenet.u-hopper.com/service
* profile manager: https://wenet.u-hopper.com/profile_manager
* task manager: https://wenet.u-hopper.com/task_manager
* personal context builder: https://wenet.u-hopper.com/personal_context_builder
* social context builder: https://wenet.u-hopper.com/social_context_builder

## Documentation

Here's some _quick links_ for accessing the documentation currently available:

* [Service REST APIs](http://swagger.u-hopper.com/?url=https://bitbucket.org/wenet/wenet-components-documentation/raw/master/sources/wenet-service_api-openapi.yaml)

* [Service REST APIs](http://swagger.u-hopper.com/?url=https://bitbucket.org/wenet/wenet-components-documentation/raw/master/sources/wenet-hub-openapi.yaml)

* [Interactions Logger and Analytics APIs](http://swagger.u-hopper.com/?url=https://bitbucket.org/wenet/wenet-components-documentation/raw/master/sources/wenet-logging_analytics-openapi.yaml)

* [Authentication Manager APIs](http://swagger.u-hopper.com/?url=https://bitbucket.org/wenet/wenet-components-documentation/raw/master/sources/wenet-auth_manager-openapi.yaml)

* [Incentive Server APIs](http://swagger.u-hopper.com/?url=https://bitbucket.org/wenet/wenet-components-documentation/raw/master/sources/wenet-incentive_server-openapi.json)

* [Profile Manager APIs](http://swagger.u-hopper.com/?url=https://bitbucket.org/wenet/wenet-components-documentation/raw/master/sources/wenet-profile_manager-openapi.yaml)

* [Interaction Protocol Engine APIs](http://swagger.u-hopper.com/?url=https://bitbucket.org/wenet/wenet-components-documentation/raw/master/sources/wenet-interaction_protocol_engine-openapi.yaml)

* [Social Context Builder APIs](http://swagger.u-hopper.com/?url=https://bitbucket.org/wenet/wenet-components-documentation/raw/master/sources/wenet-social_context_builder-openapi.json)

* [Personal Context Builder APIs](http://swagger.u-hopper.com/?url=https://bitbucket.org/wenet/wenet-components-documentation/raw/master/sources/wenet-personal_context_builder-openapi.json)

* [IlogBase APIs](http://swagger.u-hopper.com/?url=https://bitbucket.org/wenet/wenet-components-documentation/raw/master/sources/wenet-ilogbase-openapi.yaml)

* [IlogBase Common APIs](http://swagger.u-hopper.com/?url=https://bitbucket.org/wenet/wenet-components-documentation/raw/master/sources/wenet-common_api-openapi.yaml)

* [Task Manager APIs](http://swagger.u-hopper.com/?url=https://bitbucket.org/wenet/wenet-components-documentation/raw/master/sources/wenet-task_manager-openapi.yaml)

Also, you can jump start directly from this [Swagger starting point](http://swagger.u-hopper.com/?url=https://bitbucket.org/wenet/wenet-components-documentation/raw/master/start-openapi.yaml).

The structures of the messages created by WeNet for the applications as responses to the users' messages are described [here](http://swagger.u-hopper.com/?url=https://bitbucket.org/wenet/wenet-components-documentation/raw/master/sources/wenet-messages_for_apps-openapi.yaml).

The models common to the various components can be found [here](http://swagger.u-hopper.com/?url=https://bitbucket.org/wenet/wenet-components-documentation/raw/master/sources/wenet-models-openapi.yaml).

*Note*: please, keep the above links updated with the reference to the latest stable version of each documentation file.

## Postman collections

_"Postman is a collaboration platform for API development. Postman's features simplify each step of building an API and streamline collaboration so you can create better APIs—faster."_ - _Postman_

The postman collections of the various components defined in this documentation are available in the folder `/postman_collections`.
In addition to each component's collection, the export of the required environmental variables may be present: use it in order to simplify the setup of the queries you are going to reproduce.

## How to

### 1. Write your documentation

In order to write the documentation for your component you can take advantage of a Swagger editor.
Swagger offers a public online editor that is available [here](https://editor.swagger.io/).

If you prefer to work locally or offline, it is possible to run the editor locally with Docker by running the following command:

```
docker run -p 8080:8080 swaggerapi/swagger-editor
```

This will run a local version of the editor that you can use at the link `http://localhost:8080/`.
Simply:

* import the file you want to edit (either from a _public URL_ or from a _local file_);
* apply the required modifications;
* _convert and save_ the new version of the documentation;
* include the new version of the documentation in this repository so that everyone is always up to date with the documentation status.

*Note*: if you are writing your documentation from scratch, you can start modifying the example structure you are presented with (it is a good way also to wrap your head about the basic rules).

### 2. Access the documentation of the various components

It is possible to browse a documentation file by opening it in the same editor interface used for creating it.

A dedicated Swagger UI has also been deployed and it is available at [here](http://swagger.u-hopper.com/).

The files in this repository are public, in order to view them in the Swagger UI you can either:

* append the url of your documentation file in the UI link (`http://swagger.u-hopper.com?url=<file_url>`);
* paste the link to the documentation file in the _explore_ tab of the UI.

*Notes*:

* we will be appending the _quick access links_ (already configured with the correct _file url_) at the beginning of this document.
* the link provided to the Swagger UI must point to the raw version of the file
