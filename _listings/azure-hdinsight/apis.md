---
name: Azure HDInsight
x-slug: azure-hdinsight
description: Azure HDInsight is a Hadoop-based service that brings an Apache Hadoop
  solution to the cloud. Gain the full value of big data with a cloud-based data platform
  that manages data of any type and size.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-hdinsights-open-source-analytics.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Applications
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/azure-hdinsight/apis.md
specificationVersion: "0.14"
apis:
- name: HDInsightManagementClient - Applications List
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclusternameapplications-get
  description: Lists all of the applications HDInsight cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-hdinsights-open-source-analytics.png
  humanURL: https://azure.microsoft.com/en-us/services/hdinsight/
  baseURL: ://management.azure.com//
  tags: Data, Analysis, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/azure-hdinsight/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclusternameapplications-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/azure-hdinsight/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclusternameapplications-get-openapi.md
- name: HDInsightManagementClient - Applications Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclusternameapplicationsapplicationname-get
  description: Lists properties of the application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-hdinsights-open-source-analytics.png
  humanURL: https://azure.microsoft.com/en-us/services/hdinsight/
  baseURL: ://management.azure.com//
  tags: Data, Analysis, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/azure-hdinsight/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclusternameapplicationsapplicationname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/azure-hdinsight/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclusternameapplicationsapplicationname-get-openapi.md
- name: HDInsightManagementClient - Applications Create
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclusternameapplicationsapplicationname-put
  description: The operation creates applications for the HDInsight cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-hdinsights-open-source-analytics.png
  humanURL: https://azure.microsoft.com/en-us/services/hdinsight/
  baseURL: ://management.azure.com//
  tags: Data, Analysis, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/azure-hdinsight/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclusternameapplicationsapplicationname-put-openapi.md
- name: HDInsightManagementClient - Applications Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclusternameapplicationsapplicationname-delete
  description: Lists all of the applications HDInsight cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-hdinsights-open-source-analytics.png
  humanURL: https://azure.microsoft.com/en-us/services/hdinsight/
  baseURL: ://management.azure.com//
  tags: Data, Analysis, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/azure-hdinsight/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclusternameapplicationsapplicationname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/azure-hdinsight/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclusternameapplicationsapplicationname-delete-openapi.md
x-common:
- type: x-api-gallery
  url: http://azure.event.hubs.api.gallery.streamdata.io
- type: x-api-stack
  url: http://azure.hdinsight.stack.network
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/hdinsight/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/hdinsight/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/hdinsight/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/hdinsight/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---