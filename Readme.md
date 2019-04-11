# WeNet Documentation

This repository collects the API documentation of the various components of the WeNet platform.

Here's some _quick links_ for accessing the documentation currently available:

* [Interaction Protocol Engine APIs](http://swagger.u-hopper.com/?url=https://bitbucket.org/wenet/wenet-components-documentation/raw/f856bb044ba902c2842322f76db392950cdf05b1/sources/wenet-interaction_protocol_engine-api.json)
* [Personal Context Builder APIs](http://swagger.u-hopper.com/?url=https://bitbucket.org/wenet/wenet-components-documentation/raw/f856bb044ba902c2842322f76db392950cdf05b1/sources/wenet-personal_context_builder.json)
* [Private Data Manager](http://swagger.u-hopper.com/?url=https://bitbucket.org/wenet/wenet-components-documentation/raw/f856bb044ba902c2842322f76db392950cdf05b1/sources/wenet-private_data_manager-api.json)
* [Service REST APIs](http://swagger.u-hopper.com/?url=https://bitbucket.org/wenet/wenet-components-documentation/raw/2b5e9f15375c1bd76bc9ee24736625523833fc08/sources/wenet-service-api.json)
* [Social Learning APIs](http://swagger.u-hopper.com/?url=https://bitbucket.org/wenet/wenet-components-documentation/raw/f856bb044ba902c2842322f76db392950cdf05b1/sources/wenet-social-learning-dummy-api.json)

*Note*: please, keep the above links updated with the reference to the latest stable version of each documentation file.

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
