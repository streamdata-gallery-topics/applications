---
name: Azure Batch
x-slug: azure-batch
description: Batch processing began with mainframe computers and punch cards. Today,
  it still plays a central role in business, engineering, science, and other areas
  that require running lots of automated tasks&mdash;processing bills and payroll,
  calculating portfolio risk, designing new products, rendering animated films, testing
  software, searching for energy, predicting the weather, and finding new cures for
  disease. Previously, few people had access to the computing power for these scenarios.
  With Azure Batch, that power is available to you when you need it, without any capital
  investment.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Applications
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/azure-batch/apis.md
specificationVersion: "0.14"
apis:
- name: BatchManagement - Application Create
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplicationsapplicationid-put
  description: Adds an application to the specified Batch account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com//
  tags: Microsoft, Batch, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplicationsapplicationid-put-openapi.md
- name: BatchManagement - Application Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplicationsapplicationid-delete
  description: Deletes an application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com//
  tags: Microsoft, Batch, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplicationsapplicationid-delete-openapi.md
- name: BatchManagement - Application Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplicationsapplicationid-get
  description: Gets information about the specified application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com//
  tags: Microsoft, Batch, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplicationsapplicationid-get-openapi.md
- name: BatchManagement - Application Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplicationsapplicationid-patch
  description: Updates settings for the specified application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com//
  tags: Microsoft, Batch, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplicationsapplicationid-patch-openapi.md
- name: BatchManagement - Application List
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplications-get
  description: Lists all of the applications in the specified account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com//
  tags: Microsoft, Batch, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplications-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://azure.automation.api.gallery.streamdata.io
- type: x-api-stack
  url: http://azure.batch.stack.network
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/batch/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/batch/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/batch/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/batch/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---