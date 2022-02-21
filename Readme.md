# WeNet Documentation

## Component availability

The production components can be reached at the following urls:

* service APIs: https://internetofus.u-hopper.com/service
* profile manager: https://internetofus.u-hopper.com/profile_manager
* task manager: https://internetofus.u-hopper.com/task_manager
* personal context builder: https://internetofus.u-hopper.com/personal_context_builder
* social context builder: https://internetofus.u-hopper.com/social_context_builder

## Postman collections

_"Postman is a collaboration platform for API development. Postman's features simplify each step of building an API and streamline collaboration so you can create better APIs—faster."_ - _Postman_

The postman collections of the various components defined in this documentation are available in the folder `/postman_collections`.
In addition to each component's collection, the export of the required environmental variables may be present: use it in order to simplify the setup of the queries you are going to reproduce.

## How to

### Write your documentation

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
