---
name: VersaPay
x-slug: versapay
description: VersaPay handles elements of both credit and debit card merchant payment
  processing in Canada. In offering a host of merchant account services and credit
  card POS terminals it allows for an efficient merchant payment service in all aspects-
  in person, on the go, online, and at the office. Founded in 2005 by Michael Gokturk,
  VersaPay is a Canadian owned and operated national financial transaction services
  provider partnered with Chase Paymentech. Versapay also offers electronic funds
  transfer through a system called Versapay EMT.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1208-versapay-corporation.jpg
x-kinRank: "9"
x-alexaRank: "410909"
tags: Batch
created: "2018-06-17"
modified: "2018-06-17"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/versapay/apis.md
specificationVersion: "0.14"
apis:
- name: VersaPay View In-Progress & Completed Batches
  x-api-slug: versapay
  description: View recent in-progress and completed import batches.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1208-versapay-corporation.jpg
  humanURL: http://developers.versapay.com/index.html
  baseURL: https://secure.versapay.com////api/imports
  tags: View, In-Progress, &, Completed, Batches
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/versapay/apiimports-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/versapay/apiimports-get-openapi.md
- name: VersaPay View In-Progress Batches
  x-api-slug: versapay
  description: View only recent in-progress import batches.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1208-versapay-corporation.jpg
  humanURL: http://developers.versapay.com/index.html
  baseURL: https://secure.versapay.com////api/imports/processing
  tags: View, In-Progress, Batches
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/versapay/apiimportsprocessing-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/versapay/apiimportsprocessing-get-openapi.md
- name: VersaPay View Completed Batches
  x-api-slug: versapay
  description: View only recent completed import batches.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1208-versapay-corporation.jpg
  humanURL: http://developers.versapay.com/index.html
  baseURL: https://secure.versapay.com////api/imports/completed
  tags: View, Completed, Batches
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/versapay/apiimportscompleted-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/versapay/apiimportscompleted-get-openapi.md
- name: VersaPay View Batch Details
  x-api-slug: versapay
  description: View batch details.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1208-versapay-corporation.jpg
  humanURL: http://developers.versapay.com/index.html
  baseURL: https://secure.versapay.com////api/imports/{id}
  tags: View, Batch, Details
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/versapay/apiimportsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/versapay/apiimportsid-get-openapi.md
- name: VersaPay
  x-api-slug: versapay
  description: VersaPay handles elements of both credit and debit card merchant payment
    processing in Canada. In offering a host of merchant account services and credit
    card POS terminals it allows for an efficient merchant payment service in all
    aspects- in person, on the go, online, and at the office. Founded in 2005 by Michael
    Gokturk, VersaPay is a Canadian owned and operated national financial transaction
    services provider partnered with Chase Paymentech. Versapay also offers electronic
    funds transfer through a system called Versapay EMT.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1208-versapay-corporation.jpg
  humanURL: http://developers.versapay.com/index.html
  baseURL: https://secure.versapay.com//
  tags: Batch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/versapay/openapi.md
x-common:
- type: x-base
  url: https://secure.versapay.com/api/
- type: x-blog
  url: https://www.versapay.com/blog/
- type: x-blog-rss
  url: http://www.versapay.com/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/versapay
- type: x-crunchbase
  url: https://crunchbase.com/organization/versapay
- type: x-github
  url: https://github.com/versapay
- type: x-partners
  url: https://www.versapay.com/partners/
- type: x-support
  url: https://www.versapay.com/support/
- type: x-twitter
  url: https://twitter.com/VersaPay
- type: x-website
  url: http://developers.versapay.com/index.html
- type: x-website
  url: https://www.versapay.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---