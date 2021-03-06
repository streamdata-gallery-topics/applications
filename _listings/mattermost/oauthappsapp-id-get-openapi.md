---
swagger: "2.0"
x-collection-name: Mattermost
x-complete: 0
info:
  title: Mattermost API Get an OAuth app
  description: |-
    Get an OAuth 2.0 client application registered with Mattermost.
    ##### Permissions
    If app creator, must have `mange_oauth` permission otherwise `manage_system_wide_oauth` permission is required.
  termsOfService: https://about.mattermost.com/default-terms/
  version: 4.0.0
host: your-mattermost-url.com
basePath: /api/v4
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /teams/{team_id}/import:
    post:
      summary: Import a Team from other application
      description: |-
        Import a team into a existing team. Import users, channels, posts, hooks.
        ##### Permissions
        Must have `permission_import_team` permission.
      operationId: import-a-team-into-a-existing-team-import-users-channels-posts-hooks-permissionsmust-have-permission
      x-api-path-slug: teamsteam-idimport-post
      parameters:
      - in: formData
        name: file
        description: A file to be uploaded in zip format
      - in: formData
        name: filesize
        description: The size of the zip file to be imported
      - in: formData
        name: importFrom
        description: String that defines from which application the team was exported
          to be imported into Mattermost
      - in: path
        name: team_id
        description: Team GUID
      responses:
        200:
          description: OK
      tags:
      - Import
      - Team
      - From
      - Other
      - Application
  /oauth/apps:
    post:
      summary: Register OAuth app
      description: |-
        Register an OAuth 2.0 client application with Mattermost as the service provider.
        ##### Permissions
        Must have `manage_oauth` permission.
      operationId: register-an-oauth-20-client-application-with-mattermost-as-the-service-provider-permissionsmust-have
      x-api-path-slug: oauthapps-post
      parameters:
      - in: body
        name: body
        description: OAuth application to register
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Register
      - OAuth
      - App
  /oauth/apps/{app_id}:
    get:
      summary: Get an OAuth app
      description: |-
        Get an OAuth 2.0 client application registered with Mattermost.
        ##### Permissions
        If app creator, must have `mange_oauth` permission otherwise `manage_system_wide_oauth` permission is required.
      operationId: get-an-oauth-20-client-application-registered-with-mattermost-permissionsif-app-creator-must-have-ma
      x-api-path-slug: oauthappsapp-id-get
      parameters:
      - in: path
        name: app_id
        description: Application client id
      responses:
        200:
          description: OK
      tags:
      - OAuth
      - App
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---