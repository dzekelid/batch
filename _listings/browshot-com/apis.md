---
name: Browshot.com
x-slug: browshot-com
description: Browshot is a service to take screenshot of web pages. Use any of our
  mobile and desktop browsers. We provide a powerful API and libraries.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/717-browshot-com.jpg
x-kinRank: "7"
x-alexaRank: "1714303"
tags: Batch
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/browshot-com/apis.md
specificationVersion: "0.14"
apis:
- name: Browshot Requests thousands of screenshtos at once
  x-api-slug: browshot
  description: Get hundreds or thousands of screenshots from a text file. You can
    use this API call or the dashboard. Unlike the other API calls, you must issue
    a POST request with the Content-Type "multipart/form-data" in order to upload
    the text file. The text file must contain the list of URLs to request, 1 URL per
    line. Failed screenshots will be tried up to 3 times before giving up.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/717-browshot-com.jpg
  humanURL: http://browshot.com
  baseURL: https://api.browshot.com//api/v1//batch/ceate
  tags: Batch,Ceate
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/browshot-com/batchceate-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/browshot-com/batchceate-post-openapi.md
- name: Browshot Get the batch status
  x-api-slug: browshot
  description: Get the status of a batch requested through the API or through the
    dashboard.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/717-browshot-com.jpg
  humanURL: http://browshot.com
  baseURL: https://api.browshot.com//api/v1//batch/info
  tags: Batch,Info
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/browshot-com/batchinfo-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/browshot-com/batchinfo-get-openapi.md
- name: Browshot
  x-api-slug: browshot
  description: 'A service to easily make screenshots of web pages in any screen size,
    as any device: iPhone, iPad, Android, Nook, PC, etc. Test your site on different
    devices in many resolutions.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/717-browshot-com.jpg
  humanURL: http://browshot.com
  baseURL: https://api.browshot.com//api/v1
  tags: Batch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/browshot-com/openapi.md
x-common:
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