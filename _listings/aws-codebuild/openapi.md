swagger: "2.0"
x-collection-name: AWS CodeBuild
x-complete: 1
info:
  title: AWS CodeBuild API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=BatchGetBuilds:
    get:
      summary: Batch Get Builds
      description: Gets information about one or more builds.
      operationId: batchGetBuilds
      x-api-path-slug: actionbatchgetbuilds-get
      parameters:
      - in: query
        name: ids
        description: The IDs of the builds to get information about
        type: string
      responses:
        200:
          description: OK
      tags:
      - Builds
  /?Action=BatchGetProjects:
    get:
      summary: Batch Get Projects
      description: Gets information about one or more build projects.
      operationId: batchGetProjects
      x-api-path-slug: actionbatchgetprojects-get
      parameters:
      - in: query
        name: names
        description: The names of the build projects to get information about
        type: string
      responses:
        200:
          description: OK
      tags:
      - Projects