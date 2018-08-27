---
name: Postmark
x-slug: postmark
description: Trusted by thousands of developers, Postmark is a fast and reliable transactional
  email service. Send with Postmark to ensure your transactional emails get to the
  inbox on time, every time.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
x-kinRank: "8"
x-alexaRank: "87545"
tags: Batch
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/postmark/apis.md
specificationVersion: "0.14"
apis:
- name: Postmark - Parameters Email Batch
  x-api-slug: emailbatch-parameters
  description: Parameters email batch.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com//
  tags: Target, Imports, Stack Network, Technology, SaaS, Emails, Messages, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/postmark/emailbatch-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/postmark/emailbatch-parameters-openapi.md
- name: Postmark - Post Email Batch
  x-api-slug: emailbatch-post
  description: "While Postmark is focused on transactional email, we understand that
    developers with higher volumes or processing time constraints need to send their
    messages in batches. To facilitate this we provide a batching endpoint that permits
    you to send up to 500 well-formed Postmark messages in a single API call.\n                    \nThe
    format of the batched message is a JSON array containing multiple message requests
    like the following example:\n[\n    {From: 'sender@example.com', To: 'receiver1@example.com',
    Subject: 'Postmark test #1', HtmlBody: 'Hello dear Postmark user.'},\n    {From:
    'sender@example.com', To: 'receiver2@example.com', Subject: 'Postmark test #2',
    HtmlBody: 'Hello dear Postmark user.'}\n]\n\nYou can use SSL encryption by issuing
    requests to https://api.postmarkapp.com/email/batch.\n\nSimilarly, you will receive
    a matching JSON array containing each response for the messages you sent in your
    batched call:\n\n[\n    {\n        \"ErrorCode\" : 0,\n        \"Message\" : \"OK\",\n
    \       \"MessageID\" : \"b7bc2f4a-e38e-4336-af7d-e6c392c2f817\",\n        \"SubmittedAt\"
    : \"2010-11-26T12:01:05.1794748-05:00\",\n        \"To\" : \"receiver1@example.com\"\n
    \   },\n    {\n        \"ErrorCode\" : 0,\n        \"Message\" : \"OK\",\n        \"MessageID\"
    : \"e2ecbbfc-fe12-463d-b933-9fe22915106d\",\n        \"SubmittedAt\" : \"2010-11-26T12:01:05.1794748-05:00\",\n
    \       \"To\" : \"receiver2@example.com\"\n    },\n]"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com//
  tags: Target, Imports, Stack Network, Technology, SaaS, Emails, Messages, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/postmark/emailbatch-post-openapi.md
x-common:
- type: x--net-library
  url: http://developer.postmarkapp.com/developer-official-libs.html#dot-net
- type: x-api-gallery
  url: http://polygon.api.gallery.streamdata.io
- type: x-api-stack
  url: http://postmark.stack.network
- type: x-base
  url: https://api.postmarkapp.com
- type: x-blog
  url: http://blog.postmarkapp.com/
- type: x-blog-rss
  url: http://blog.postmarkapp.com/rss
- type: x-contact-form
  url: http://support.postmarkapp.com/customer/portal/emails/new
- type: x-crunchbase
  url: https://crunchbase.com/organization/postmark
- type: x-crunchbase
  url: http://www.crunchbase.com/company/postmark
- type: x-developer
  url: http://developer.postmarkapp.com/
- type: x-email
  url: support@postmarkapp.com
- type: x-email
  url: 451d9b70cf9364d23ff6f9d51d870251569e+ahoy@inbound.postmarkapp.com
- type: x-faq
  url: http://support.postmarkapp.com/
- type: x-pricing
  url: http://developer.postmarkapp.com/developer-api-messages.html
- type: x-privacy
  url: https://postmarkapp.com/privacy-policy
- type: x-ruby-library
  url: http://developer.postmarkapp.com/developer-official-libs.html#rails
- type: x-ruby-library
  url: http://developer.postmarkapp.com/developer-official-libs.html#ruby
- type: x-selfservice-registration
  url: https://postmarkapp.com/sign_up
- type: x-status
  url: http://status.postmarkapp.com/
- type: x-terms-of-service
  url: https://postmarkapp.com/terms-of-service
- type: x-twitter
  url: https://twitter.com/postmarkapp
- type: x-website
  url: http://postmarkapp.com
- type: x-website
  url: http://postmarkapp.com/
- type: x-website
  url: https://postmarkapp.com
- type: x-wordpress-pdk
  url: http://developer.postmarkapp.com/developer-official-libs.html#wordpress
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---