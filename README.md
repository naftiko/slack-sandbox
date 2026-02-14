# Slack API & MCP Sandbox
This is an API sandbox for the Slack API & MCP Sandbox, using an OpenAPI specification with examples, Microcks and Bruno as the sandbox interface, and this GitHub repository as the vehicle for delivering a localized sandbox.

## APIs.json
There is an APIs.yml file in the root of this repository, providing an index of all the artifacts used as part of this API sandbox, providing a machine-readable way to read, manage, and execute the sandbox available here.

## Microcks
This sandbox uses Microcks to deliver the mock API. [You just install Microcks, with the Docker extension being the easiest](https://microcks.io/documentation/guides/installation/docker-desktop-extension/), [import the OpenAPI as a service](openapi/notion-openapi.yml), and you have a mocked API for all APIs, available via REST and MCP APIs--providing a multi-protocol sandbox.

## Bruno
This sandbox [uses Bruno as the client](https://www.usebruno.com/), leveraging Bruno Collections pre-generated from the OpenAPI and Bruno environments that uses the localhost and port of Microcks to work with the mocked API. You just have to install Microcks, then open the collection provided in this repository, select the available environment, and begin calling the Slack API & MCP Sandbox via the sandbox.

## Summary
This is a summary of this sandbox, breaking down the available paths, operations, and other relevant detail regarding the scope of this sandbox, designed to support development and testing against the Slack API & MCP Sandbox.

- Number of Paths: 173
- Number of Operations: 173
- Number of Read Operations: 79
- Number of Write Operations: 94
- Number of Schemas: 509
- Number of Responses: 0
- Number of Parameters: 121
- Number of Examples: 352
- Number of Request Bodies: 0
- Number of Headers: 0

## OpenAPIs
These are the OpenAPIs available for the Slack API & MCP Sandbox, which are made available via this sandbox API, which can be imported into Microcks and deployed as a sandbox using their mock feature.

  - [Slack Admin Api](openapi/slack-admin-openapi.yml)
  - [Slack Apps Api](openapi/slack-apps-openapi.yml)
  - [Slack Auth Api](openapi/slack-auth-openapi.yml)
  - [Slack Bots Api](openapi/slack-bots-openapi.yml)
  - [Slack Calls Api](openapi/slack-calls-openapi.yml)
  - [Slack Chat Api](openapi/slack-chat-openapi.yml)
  - [Slack Conversations Api](openapi/slack-conversations-openapi.yml)
  - [Slack Dialog Api](openapi/slack-dialog-openapi.yml)
  - [Slack Dnd Api](openapi/slack-dnd-openapi.yml)
  - [Slack Files Api](openapi/slack-files-openapi.yml)
  - [Slack Migration Api](openapi/slack-migration-openapi.yml)
  - [Slack Oauth Api](openapi/slack-oauth-openapi.yml)
  - [Slack Pins Api](openapi/slack-pins-openapi.yml)
  - [Slack Reactions Api](openapi/slack-reactions-openapi.yml)
  - [Slack Reminders Api](openapi/slack-reminders-openapi.yml)
  - [Slack Rtm Api](openapi/slack-rtm-openapi.yml)
  - [Slack Search Api](openapi/slack-search-openapi.yml)
  - [Slack Stars Api](openapi/slack-stars-openapi.yml)
  - [Slack Team Api](openapi/slack-team-openapi.yml)
  - [Slack Tests Api](openapi/slack-test-api-openapi.yml)
  - [Slack User Groups Api](openapi/slack-usergroups-openapi.yml)
  - [Slack Users Api](openapi/slack-users-openapi.yml)
  - [Slack Views Api](openapi/slack-views-openapi.yml)
  - [Slack Workflows Api](openapi/slack-workflows-openapi.yml)

## Resources
These are the resources available via the Slack API & MCP Sandbox, which are made available via this sandbox API, which are applied as tags to each operation in the OpenAPI.

  - Api Testing
  - Applications
  - Authentication
  - Bots
  - Call Participants
  - Calls
  - Conversation History
  - Conversation Info
  - Conversation Management
  - Conversation Membership
  - Conversation Settings
  - Conversations
  - Dialogs
  - Do Not Disturb Control
  - Do Not Disturb Status
  - Emoji
  - Events
  - File Comments
  - File Sharing
  - Files
  - Get
  - Installation
  - Invite Requests
  - Message Utilities
  - Messages
  - Migration
  - Oauth Legacy
  - Oauth V2
  - Permissions
  - Pins
  - Reactions
  - Reminders
  - Remote Files
  - Resources
  - Rtm
  - Scheduled Messages
  - Search Messages
  - Stars
  - Team Access Logs
  - Team Billing
  - Team Information
  - Team Integration Logs
  - Team Profile
  - Teams
  - Token Management
  - Use Groups
  - User Conversations
  - User Group Members
  - User Groups
  - User Information
  - User Lookup
  - User Photo
  - User Presence
  - User Profile
  - Users
  - Views
  - Workflows

## Operations
These are all of the available operations in this sandbox, providing a complete view of what you can do within this sandbox using the mocked Slack API & MCP Sandbox.

  - Add Default Channels To Idp Group
  - Add Emoji
  - Add Emoji Alias
  - Add Idp Group To Channel Allowlist
  - Add Reaction
  - Add Reminder
  - Add Star
  - Add Workspaces To Idp Group
  - Add A Remote File
  - Add Participants To A Call
  - Approve App For Installation
  - Approve Invite Request
  - Archive Channel
  - Archive A Conversation
  - Assign User To Workspace
  - Close A Direct Message
  - Complete Reminder
  - Complete Workflow Step
  - Connect To Rtm
  - Convert Channel To Private
  - Create Channel
  - Create Enterprise Team
  - Create User Group
  - Create A Conversation
  - Delete Channel
  - Delete Reminder
  - Delete User Photo
  - Delete A File
  - Delete A File Comment
  - Delete A Message
  - Delete A Scheduled Message
  - Deny Invite Request
  - Disable User Group
  - Disconnect Shared Channel
  - Enable User Group
  - End Do Not Disturb
  - End A Call
  - End Snooze Mode
  - Exchange Oauth 2.0 Code For Access Token
  - Exchange Oauth Code For Access Token
  - Exchange Oauth Code For Workspace Token
  - Exchange User Ids For Migration
  - Fail Workflow Step
  - Get  Bots Info
  - Get App Permissions Info
  - Get Call Information
  - Get Connected Workspaces
  - Get Conversation Preferences
  - Get Dnd Status
  - Get Reactions
  - Get Reminder Info
  - Get Team Access Logs
  - Get Team Billable Info
  - Get Team Info
  - Get Team Integration Logs
  - Get Team Profile
  - Get User Identity
  - Get User Information
  - Get User Presence
  - Get User Profile
  - Get Workspace Settings
  - Get A Message Permalink
  - Get Conversation History
  - Get Conversation Info
  - Get Conversation Members
  - Get File Info
  - Get Remote File Info
  - Get Team Dnd Status
  - Get Thread Replies
  - Invalidate User Session
  - Invite User To Workspace
  - Invite Users To Channel
  - Invite Users To A Conversation
  - Join A Conversation
  - Leave A Conversation
  - List App Requests
  - List App Scopes
  - List Approved Apps
  - List Approved Invite Requests
  - List Denied Invite Requests
  - List Emoji
  - List Enterprise Teams
  - List Event Authorizations
  - List Idp Group Channels
  - List Idp Groups For Channel
  - List Original Connected Channel Info For Ekm
  - List Pending Invite Requests
  - List Pinned Items In Channel
  - List Reactions
  - List Reminders
  - List Resource Grants
  - List Restricted Apps
  - List Stars
  - List User Conversations
  - List User Grants
  - List User Group Members
  - List User Groups
  - List Users
  - List Workspace Admins
  - List Workspace Owners
  - List Workspace Users
  - List Conversations
  - List Files
  - List Remote Files
  - List Scheduled Messages
  - Lookup User By Email
  - Open View
  - Open A Conversation
  - Open A Dialog
  - Pin Item To Channel
  - Provide Custom Unfurl Behavior
  - Publish View
  - Push View
  - Register A New Call
  - Remove Channels From Idp Group
  - Remove Emoji
  - Remove Idp Group From Channel
  - Remove Pin From Channel
  - Remove Reaction
  - Remove Star
  - Remove User From Workspace
  - Remove A Remote File
  - Remove A User From A Conversation
  - Remove Participants From A Call
  - Rename Channel
  - Rename Emoji
  - Rename A Conversation
  - Request Additional Permissions
  - Request User Permissions
  - Reset User Sessions
  - Restrict App Installation
  - Revoke Authentication Token
  - Revoke Public Url
  - Schedule A Message
  - Search Channels
  - Search Messages
  - Send A Me Message
  - Send A Message
  - Send An Ephemeral Message
  - Set Channel Workspaces
  - Set Conversation Preferences
  - Set Default Channels
  - Set Guest User Expiration
  - Set User Active
  - Set User Photo
  - Set User Presence
  - Set User Profile
  - Set User As Admin
  - Set User As Owner
  - Set User As Regular
  - Set Workspace Description
  - Set Workspace Discoverability
  - Set Workspace Icon
  - Set Workspace Name
  - Set Conversation Purpose
  - Set Conversation Topic
  - Set Read Cursor
  - Set Snooze
  - Share A Remote File
  - Share File Publicly
  - Test Api Connection
  - Test Authentication
  - Unarchive Channel
  - Unarchive A Conversation
  - Uninstall App
  - Update Call Information
  - Update User Group
  - Update User Group Members
  - Update View
  - Update Workflow Step
  - Update A Message
  - Update A Remote File
  - Upload A File

## Backstage
We provide a Backstage software catalog entity for the Slack API & MCP Sandbox, allowing this sandbox to be registered with any catalog, making it discoverable by team and across an organization--allowing anyone to fork and deploy locally within the enterprise.

  - [Slack Admin API](backstage/slack-admin-api-sandbox-backstage.yml)
  - [Slack Apps API](backstage/slack-apps-api-sandbox-backstage.yml)
  - [Slack Auth API](backstage/slack-auth-api-sandbox-backstage.yml)
  - [Slack Bots API](backstage/slack-bots-api-sandbox-backstage.yml)
  - [Slack Calls API](backstage/slack-calls-api-sandbox-backstage.yml)
  - [Slack Chat API](backstage/slack-chat-api-sandbox-backstage.yml)
  - [Slack Conversations API](backstage/slack-conversations-api-sandbox-backstage.yml)
  - [Slack Dialog API](backstage/slack-dialog-api-sandbox-backstage.yml)
  - [Slack Dnd API](backstage/slack-dnd-api-sandbox-backstage.yml)
  - [Slack Files API](backstage/slack-files-api-sandbox-backstage.yml)
  - [Slack Migration API](backstage/slack-migration-api-sandbox-backstage.yml)
  - [Slack Oauth API](backstage/slack-oauth-api-sandbox-backstage.yml)
  - [Slack Pins API](backstage/slack-pins-api-sandbox-backstage.yml)
  - [Slack Reactions API](backstage/slack-reactions-api-sandbox-backstage.yml)
  - [Slack Reminders API](backstage/slack-reminders-api-sandbox-backstage.yml)
  - [Slack Rtm API](backstage/slack-rtm-api-sandbox-backstage.yml)
  - [Slack Search API](backstage/slack-search-api-sandbox-backstage.yml)
  - [Slack Stars API](backstage/slack-stars-api-sandbox-backstage.yml)
  - [Slack Team API](backstage/slack-team-api-sandbox-backstage.yml)
  - [Slack Tests API](backstage/slack-test-api-api-sandbox-backstage.yml)
  - [Slack User Groups API](backstage/slack-usergroups-api-sandbox-backstage.yml)
  - [Slack Users API](backstage/slack-users-api-sandbox-backstage.yml)
  - [Slack Views API](backstage/slack-views-api-sandbox-backstage.yml)
  - [Slack Workflows API](backstage/slack-workflows-api-sandbox-backstage.yml)
## Support
Please provide any questions or feedback via GitHub issues, or just email kinlane@naftiko.io with feedback. The goal is to keep iterating upon this sandbox using existing OpenAPI, Microcks, and Bruno features, offering value out of the box via this forkable third-party Slack API & MCP Sandbox.

