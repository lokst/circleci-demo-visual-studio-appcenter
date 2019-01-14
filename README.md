# circleci-demo-visual-studio-appcenter [![CircleCI status](https://circleci.com/gh/lokst/circleci-demo-visual-studio-appcenter.svg "CircleCI status")](https://circleci.com/gh/lokst/circleci-demo-visual-studio-appcenter)
This is a project to demonstrate usage of Visual Studio App Center on CircleCI.
For now it demonstrates how to do a headless login on MacOS in your CircleCI build.

## Required CircleCI project environment variables
This demo requires the following [project environment variables](https://circleci.com/docs/2.0/env-vars/#setting-an-environment-variable-in-a-project) to be configured:

| Command                               | Description                                                    |
| ------------------------------------- | -------------------------------------------------------------- |
| `APP_CENTER_API_TOKEN` | App Center API token value |

