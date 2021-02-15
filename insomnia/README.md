# Insomnia Workspace

This folder includes the export of an Insomnia workspace.

In order to use it, the following is required:

* [Insomnia](https://insomnia.rest/products/core/)
* the [repo sync plugin](https://insomnia.rest/plugins/@klicksite/insomnia-plugin-repo-sync)


## Configuration

### Workspace

The Workspace needs to be names `WeNet`.

### Environments

Create as many environments as needed.
It is important that they are all private. This will allow to ignore them during exports.

## Variables

Each Insomnia environment requires the following variables:

* `host` the WeNet base host
* `componentApikey` the apikey for cross-component authentication
* `appId` the application id
* `userId` the user id

Here's an example:

```json
{
  "host": "https://internetofus.u-hopper.com/prod",
  "componentApikey": "apikey",
  "appId": "appId",
  "userId": "userId"
}
```
