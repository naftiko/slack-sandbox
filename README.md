# Slack Sandbox
This is sandbox for the Slack Sandbox API, using an OpenAPI specification with examples, Microcks and Bruno as the sandbox interface, and this GitHub repository as the vehicle for delivering as a localized sandbox, or also enabling the working directly with production APIs.

## APIs.json Index
There is an APIs.yml file in the root of this repository, providing an index of all the artifacts used as part of this capability, providing a machine-readable way to read, manage, and execute the resources available here.

## OpenAPI
This capability uses OpenAPI as the definition, providing a complete definition of all available paths for the Slack Sandbox. The OpenAPI for this capability uses examples and Microcks extensions to mock the requests and responses for each API operation, something we will iterate and expand upon with richer examples as the capability evolves.

## Microcks
This capability uses Microcks to deliver the mock API. [You just install Microcks, with the Docker extension being the easiest](https://microcks.io/documentation/guides/installation/docker-desktop-extension/), [import the OpenAPI as a service](openapi/notion-openapi.yml), and you have a mocked API for all APIs, available via REST and MCP APIs--providing a multi-protocol sandbox.

## Bruno
This capability [uses Bruno as the client](https://www.usebruno.com/), leveraging Bruno Collections pre-generated from the OpenAPI and Bruno environments that uses the localhost and port of Microcks to work with the mocked API. You just have to install Microcks, then open the collection provided in this repository, select the available environments, and begin calling the Slack Sandbox via the sandbox or production.


## OpenAPIs
These are the OpenAPIs available for the Slack Sandbox, which are made available via this sandbox API, which can be imported into Microcks and deployed as a sandbox using their mock feature.

  - [Slack Admin Openapi](openapi/slack-admin-openapi.yml)
  - [Slack Apps Openapi](openapi/slack-apps-openapi.yml)
  - [Slack Auth Openapi](openapi/slack-auth-openapi.yml)
  - [Slack Bots Openapi](openapi/slack-bots-openapi.yml)
  - [Slack Calls Openapi](openapi/slack-calls-openapi.yml)
  - [Slack Chat Openapi](openapi/slack-chat-openapi.yml)
  - [Slack Conversations Openapi](openapi/slack-conversations-openapi.yml)
  - [Slack Dialog Openapi](openapi/slack-dialog-openapi.yml)
  - [Slack Dnd Openapi](openapi/slack-dnd-openapi.yml)
  - [Slack Files Openapi](openapi/slack-files-openapi.yml)
  - [Slack Migration Openapi](openapi/slack-migration-openapi.yml)
  - [Slack Oauth Openapi](openapi/slack-oauth-openapi.yml)
  - [Slack Pins Openapi](openapi/slack-pins-openapi.yml)
  - [Slack Reactions Openapi](openapi/slack-reactions-openapi.yml)
  - [Slack Reminders Openapi](openapi/slack-reminders-openapi.yml)
  - [Slack Rtm Openapi](openapi/slack-rtm-openapi.yml)
  - [Slack Search Openapi](openapi/slack-search-openapi.yml)
  - [Slack Stars Openapi](openapi/slack-stars-openapi.yml)
  - [Slack Team Openapi](openapi/slack-team-openapi.yml)
  - [Slack Test Api Openapi](openapi/slack-test-api-openapi.yml)
  - [Slack Usergroups Openapi](openapi/slack-usergroups-openapi.yml)
  - [Slack Users Openapi](openapi/slack-users-openapi.yml)
  - [Slack Views Openapi](openapi/slack-views-openapi.yml)
  - [Slack Workflows Openapi](openapi/slack-workflows-openapi.yml)

## Support
Please provide any questions or feedback via GitHub issues, or just email kinlane@naftiko.io with feedback. The goal is to keep iterating upon this sandboxes using existing OpenAPI, Microcks, and Bruno features, offering value out of the box via this forkable capability.

