---
name: Browshot
x-slug: browshot
description: Browshot is a service to take screenshot of web pages. Use any of our
  mobile and desktop browsers. We provide a powerful API and libraries.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/717-browshot-com.jpg
x-kinRank: "7"
x-alexaRank: "1714303"
tags: Batch
created: "2018-08-25"
modified: "2018-08-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/browshot/apis.md
specificationVersion: "0.14"
apis:
- name: Browshot - Requests thousands of screenshtos at once
  x-api-slug: batchceate-post
  description: Get hundreds or thousands of screenshots from a text file. You can
    use this API call or the dashboard. Unlike the other API calls, you must issue
    a POST request with the Content-Type "multipart/form-data" in order to upload
    the text file. The text file must contain the list of URLs to request, 1 URL per
    line. Failed screenshots will be tried up to 3 times before giving up.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/717-browshot-com.jpg
  humanURL: http://browshot.com/
  baseURL: https://api.browshot.com//api/v1
  tags: BROWSER, Screenshot, Utility, Screen Capture, Mobile, Technology, SaaS, internet,
    API Provider, Profiles, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/browshot/batchceate-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/browshot/batchceate-post-openapi.md
- name: Browshot - Get the batch status
  x-api-slug: batchinfo-get
  description: Get the status of a batch requested through the API or through the
    dashboard.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/717-browshot-com.jpg
  humanURL: http://browshot.com/
  baseURL: https://api.browshot.com//api/v1
  tags: BROWSER, Screenshot, Utility, Screen Capture, Mobile, Technology, SaaS, internet,
    API Provider, Profiles, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/browshot/batchinfo-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/browshot/batchinfo-get-openapi.md
x-common:
- type: x-website
  url: http://browshot.com/
- type: x-api-gallery
  url: http://broadleaf.commerce.api.gallery.streamdata.io
- type: x-api-stack
  url: http://browshot.stack.network
- type: x-base
  url: https://api.browshot.com/api/
- type: x-blog
  url: http://blog.browshot.com/
- type: x-blog-rss
  url: http://blog.browshot.com/feeds/posts/default
- type: x-crunchbase
  url: http://www.crunchbase.com/company/browshot
- type: x-crunchbase
  url: https://crunchbase.com/organization/browshot
- type: x-developer
  url: http://browshot.com/api/documentation
- type: x-email
  url: feedback@browshot.com
- type: x-twitter
  url: https://twitter.com/BrowshotCom
- type: x-website
  url: http://browshot.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---