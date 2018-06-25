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
tags: Batch
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/azure-batch/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Batch API Batch Account Create
  x-api-slug: azure-batch-api
  description: Creates a new Batch account with the specified parameters. Existing
    accounts cannot be updated with this API and should instead be updated with the
    Update Batch Account API.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Batch/batchAccounts/{accountName}
  tags: Batch Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountname-put-openapi.md
- name: Azure Batch API Batch Account Update
  x-api-slug: azure-batch-api
  description: Updates the properties of an existing Batch account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Batch/batchAccounts/{accountName}
  tags: Batch Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountname-patch-openapi.md
- name: Azure Batch API Batch Account Delete
  x-api-slug: azure-batch-api
  description: Deletes the specified Batch account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Batch/batchAccounts/{accountName}
  tags: Batch Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountname-delete-openapi.md
- name: Azure Batch API Batch Account Get
  x-api-slug: azure-batch-api
  description: Gets information about the specified Batch account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Batch/batchAccounts/{accountName}
  tags: Batch Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountname-get-openapi.md
- name: Azure Batch API Batch Account List
  x-api-slug: azure-batch-api
  description: Gets information about the Batch accounts associated with the subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.Batch/batchAccounts
  tags: Batch Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/azure-batch/subscriptionssubscriptionidprovidersmicrosoft-batchbatchaccounts-get-openapi.md
- name: Azure Batch API Batch Account List By Resource Group
  x-api-slug: azure-batch-api
  description: Gets information about the Batch accounts associated within the specified
    resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Batch/batchAccounts
  tags: Batch Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccounts-get-openapi.md
- name: Azure Batch API Batch Account Synchronize Auto Storage Keys
  x-api-slug: azure-batch-api
  description: Synchronizes access keys for the auto storage account configured for
    the specified Batch account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Batch/batchAccounts/{accountName}/syncAutoStorageKeys
  tags: Batch Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnamesyncautostoragekeys-post-openapi.md
- name: Azure Batch API Batch Account Regenerate Key
  x-api-slug: azure-batch-api
  description: Regenerates the specified account key for the Batch account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Batch/batchAccounts/{accountName}/regenerateKeys
  tags: Batch Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/azure-batch/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameregeneratekeys-post-openapi.md
- name: Azure Batch API
  x-api-slug: azure-batch-api
  description: Batch processing began with mainframe computers and punch cards. Today,
    it still plays a central role in business, engineering, science, and other areas
    that require running lots of automated tasks&mdash;processing bills and payroll,
    calculating portfolio risk, designing new products, rendering animated films,
    testing software, searching for energy, predicting the weather, and finding new
    cures for disease. Previously, few people had access to the computing power for
    these scenarios. With Azure Batch, that power is available to you when you need
    it, without any capital investment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-batch-100x-scale.png
  humanURL: https://azure.microsoft.com/en-us/services/batch/
  baseURL: ://management.azure.com//
  tags: Batch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/azure-batch/openapi.md
x-common:
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