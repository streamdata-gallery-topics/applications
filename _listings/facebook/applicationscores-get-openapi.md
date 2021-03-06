---
swagger: "2.0"
x-collection-name: Facebook
x-complete: 0
info:
  title: Facebook Get Application Scores
  description: Scores for the user and their friends.
  version: 1.0.0
host: graph.facebook.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{application}:
    get:
      summary: Get Application
      description: An application's profile
      operationId: getApplication
      x-api-path-slug: application-get
      parameters:
      - in: path
        name: application
        description: Represents the ID of the application object
      responses:
        200:
          description: OK
      tags:
      - Application
  /{application}/accounts:
    get:
      summary: Get Application Accounts
      description: Test User accounts associated with the application.
      operationId: getApplicationAccounts
      x-api-path-slug: applicationaccounts-get
      parameters:
      - in: path
        name: application
        description: Represents the ID of the application object
      responses:
        200:
          description: OK
      tags:
      - Application
      - Accounts
  /{application}/accounts/test-users:
    post:
      summary: Post Application Accounts Test Users
      description: Creates a test account for the application
      operationId: postApplicationAccountsTestUsers
      x-api-path-slug: applicationaccountstestusers-post
      parameters:
      - in: path
        name: application
        description: Represents the ID of the application object
      - in: query
        name: installed
        description: Install app for the test user upon creation
      - in: query
        name: name
        description: A name for the test user
      - in: query
        name: permissions
        description: List of extended permissions app granted for the new test user
          if installed is true
      responses:
        200:
          description: OK
      tags:
      - Application
      - Accounts
      - Test
      - Users
  /{application}/albums:
    get:
      summary: Get Application Albums
      description: The photo albums this application has created.
      operationId: getApplicationAlbums
      x-api-path-slug: applicationalbums-get
      parameters:
      - in: path
        name: application
        description: Represents the ID of the application object
      responses:
        200:
          description: OK
      tags:
      - Application
      - Albums
  /{application}/feed:
    get:
      summary: Get Application Feed
      description: The application's wall.
      operationId: getApplicationFeed
      x-api-path-slug: applicationfeed-get
      parameters:
      - in: path
        name: application
        description: Represents the ID of the application object
      responses:
        200:
          description: OK
      tags:
      - Application
      - Feed
    post:
      summary: Post Application Feed
      description: Posts a status message on the application's profile page
      operationId: postApplicationFeed
      x-api-path-slug: applicationfeed-post
      parameters:
      - in: path
        name: application
        description: Represents the ID of the application object
      - in: query
        name: message
        description: Status Message content
      responses:
        200:
          description: OK
      tags:
      - Application
      - Feed
  /{application}/insights:
    get:
      summary: Get Application Insights
      description: Usage metrics for this application
      operationId: getApplicationInsights
      x-api-path-slug: applicationinsights-get
      parameters:
      - in: path
        name: application
        description: Represents the ID of the application object
      responses:
        200:
          description: OK
      tags:
      - Application
      - Insights
  /{application}/links:
    get:
      summary: Get Application Links
      description: The application's posted links.
      operationId: getApplicationLinks
      x-api-path-slug: applicationlinks-get
      parameters:
      - in: path
        name: application
        description: Represents the ID of the application object
      responses:
        200:
          description: OK
      tags:
      - Application
      - Links
    post:
      summary: Post Application Links
      description: Posts a link on the application's profile page
      operationId: postApplicationLinks
      x-api-path-slug: applicationlinks-post
      parameters:
      - in: path
        name: application
        description: Represents the ID of the application object
      - in: query
        name: link
        description: Link URL
      - in: query
        name: message
        description: Link message
      responses:
        200:
          description: OK
      tags:
      - Application
      - Links
  /{application}/picture:
    get:
      summary: Get Application Picture
      description: The application's logo
      operationId: getApplicationPicture
      x-api-path-slug: applicationpicture-get
      parameters:
      - in: path
        name: application
        description: Represents the ID of the application object
      - in: query
        name: type
        description: One of square (50x50), small (50 pixels wide, variable height),
          and large (about 200 pixels wide,                                                        variable
          height)
      responses:
        200:
          description: OK
      tags:
      - Application
      - Picture
  /{application}/posts:
    get:
      summary: Get Application Adds
      description: The application's own posts.
      operationId: getApplicationAdds
      x-api-path-slug: applicationposts-get
      parameters:
      - in: path
        name: application
        description: Represents the ID of the application object
      responses:
        200:
          description: OK
      tags:
      - Application
      - Posts
  /{application}/reviews:
    get:
      summary: Get Application Reviews
      description: Reviews of this application
      operationId: getApplicationReviews
      x-api-path-slug: applicationreviews-get
      parameters:
      - in: path
        name: application
        description: Represents the ID of the application object
      responses:
        200:
          description: OK
      tags:
      - Application
      - Reviews
  /{application}/staticresources:
    get:
      summary: Get Application Staticresources
      description: Usage stats about the canvas application's static resources, such
        as javascript and CSS, and which ones are being flushed to browsers early.
      operationId: getApplicationStaticresources
      x-api-path-slug: applicationstaticresources-get
      parameters:
      - in: path
        name: application
        description: Represents the ID of the application object
      responses:
        200:
          description: OK
      tags:
      - Application
      - Staticresources
  /{application}/statuses:
    get:
      summary: Get Application Statuses
      description: The application's status updates
      operationId: getApplicationStatuses
      x-api-path-slug: applicationstatuses-get
      parameters:
      - in: path
        name: application
        description: Represents the ID of the application object
      responses:
        200:
          description: OK
      tags:
      - Application
      - Statuses
    post:
      summary: Post Application Statuses
      description: Posts a status message on the application's profile page
      operationId: postApplicationStatuses
      x-api-path-slug: applicationstatuses-post
      parameters:
      - in: path
        name: application
        description: Represents the ID of the application object
      - in: query
        name: message
        description: Status Message content
      responses:
        200:
          description: OK
      tags:
      - Application
      - Statuses
  /{application}/subscriptions:
    get:
      summary: Get Application Subscriptions
      description: All of the subscriptions this application has for real-time notifications.
      operationId: getApplicationSubscriptions
      x-api-path-slug: applicationsubscriptions-get
      parameters:
      - in: path
        name: application
        description: Represents the ID of the application object
      responses:
        200:
          description: OK
      tags:
      - Application
      - Subscriptions
    post:
      summary: Post Application Subscriptions
      description: Adds a real-time notification subscription for this application.
      operationId: postApplicationSubscriptions
      x-api-path-slug: applicationsubscriptions-post
      parameters:
      - in: path
        name: application
        description: Represents the ID of the application object
      - in: query
        name: callback_url
        description: A callback URL to which Facebook will post subscription updates
      - in: query
        name: fields
        description: List of properties for the `object` to monitor
      - in: query
        name: object
        description: Object to monitor - `user`, `permissions`, or `page`
      - in: query
        name: verify_token
        description: Token sent in the verification request
      responses:
        200:
          description: OK
      tags:
      - Application
      - Subscriptions
    delete:
      summary: Delete Application Subscriptions
      description: Deletes a real-time notification subscription for this application.
      operationId: deleteApplicationSubscriptions
      x-api-path-slug: applicationsubscriptions-delete
      parameters:
      - in: path
        name: application
        description: Represents the ID of the application object
      - in: query
        name: object
        description: Object to monitor - `user`, `permissions`, or `page`
      responses:
        200:
          description: OK
      tags:
      - Application
      - Subscriptions
  /{application}/tagged:
    get:
      summary: Get Application Tagged
      description: The photos, videos, and posts in which this application has been
        tagged.
      operationId: getApplicationTagged
      x-api-path-slug: applicationtagged-get
      parameters:
      - in: path
        name: application
        description: Represents the ID of the application object
      responses:
        200:
          description: OK
      tags:
      - Application
      - Tagged
  /{application}/translations:
    get:
      summary: Get Application Translations
      description: The translated strings for this application.
      operationId: getApplicationTranslations
      x-api-path-slug: applicationtranslations-get
      parameters:
      - in: path
        name: application
        description: Represents the ID of the application object
      responses:
        200:
          description: OK
      tags:
      - Application
      - Translations
    post:
      summary: Post Application Translations
      description: Uploads translated strings for this application.
      operationId: postApplicationTranslations
      x-api-path-slug: applicationtranslations-post
      parameters:
      - in: path
        name: application
        description: Represents the ID of the application object
      - in: query
        name: native_strings
        description: A JSON-encoded array of strings to translate
      responses:
        200:
          description: OK
      tags:
      - Application
      - Translations
    delete:
      summary: Delete Application Translations
      description: Deletes a translation string for this application.
      operationId: deleteApplicationTranslations
      x-api-path-slug: applicationtranslations-delete
      parameters:
      - in: path
        name: application
        description: Represents the ID of the application object
      - in: query
        name: native_hashes
        description: An array of native hashes
      responses:
        200:
          description: OK
      tags:
      - Application
      - Translations
  /{application}/scores:
    get:
      summary: Get Application Scores
      description: Scores for the user and their friends.
      operationId: getApplicationScores
      x-api-path-slug: applicationscores-get
      parameters:
      - in: path
        name: application
        description: Represents the ID of the application object
      responses:
        200:
          description: OK
      tags:
      - Application
      - Scores
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