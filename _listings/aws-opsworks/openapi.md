swagger: "2.0"
x-collection-name: AWS OpsWorks
x-complete: 1
info:
  title: AWS OpsWorks API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateApp:
    get:
      summary: Create App
      description: Creates an app for a specified stack.
      operationId: createApp
      x-api-path-slug: actioncreateapp-get
      parameters:
      - in: query
        name: AppSource
        description: A Source object that specifies the app repository
        type: string
      - in: query
        name: Attributes
        description: One or more user-defined key/value pairs to be added to the stack
          attributes
        type: string
      - in: query
        name: DataSources
        description: The apps data source
        type: string
      - in: query
        name: Description
        description: A description of the app
        type: string
      - in: query
        name: Domains
        description: The app virtual host settings, with multiple domains separated
          by commas
        type: string
      - in: query
        name: EnableSsl
        description: Whether to enable SSL for the app
        type: string
      - in: query
        name: Environment
        description: An array of EnvironmentVariable objects that specify environment
          variables to be      associated with the app
        type: string
      - in: query
        name: Name
        description: The app name
        type: string
      - in: query
        name: Shortname
        description: The apps short name
        type: string
      - in: query
        name: SslConfiguration
        description: An SslConfiguration object with the SSL configuration
        type: string
      - in: query
        name: StackId
        description: The stack ID
        type: string
      - in: query
        name: Type
        description: The app type
        type: string
      responses:
        200:
          description: OK
      tags:
      - App
  /?Action=DeleteApp:
    get:
      summary: Delete App
      description: Deletes a specified app.
      operationId: deleteApp
      x-api-path-slug: actiondeleteapp-get
      parameters:
      - in: query
        name: AppId
        description: The app ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - App
  /?Action=UpdateApp:
    get:
      summary: Update App
      description: Updates a specified app.
      operationId: updateApp
      x-api-path-slug: actionupdateapp-get
      parameters:
      - in: query
        name: AppId
        description: The app ID
        type: string
      - in: query
        name: AppSource
        description: A Source object that specifies the app repository
        type: string
      - in: query
        name: Attributes
        description: One or more user-defined key/value pairs to be added to the stack
          attributes
        type: string
      - in: query
        name: DataSources
        description: The apps data sources
        type: string
      - in: query
        name: Description
        description: A description of the app
        type: string
      - in: query
        name: Domains
        description: The apps virtual host settings, with multiple domains separated
          by commas
        type: string
      - in: query
        name: EnableSsl
        description: Whether SSL is enabled for the app
        type: string
      - in: query
        name: Environment
        description: An array of EnvironmentVariable objects that specify environment
          variables to be      associated with the app
        type: string
      - in: query
        name: Name
        description: The app name
        type: string
      - in: query
        name: SslConfiguration
        description: An SslConfiguration object with the SSL configuration
        type: string
      - in: query
        name: Type
        description: The app type
        type: string
      responses:
        200:
          description: OK
      tags:
      - App
  /?Action=DescribeApps:
    get:
      summary: Describe Apps
      description: Requests a description of a specified set of apps.
      operationId: describeApps
      x-api-path-slug: actiondescribeapps-get
      parameters:
      - in: query
        name: AppIds
        description: An array of app IDs for the apps to be described
        type: string
      - in: query
        name: StackId
        description: The app stack ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Describe
      - Apps