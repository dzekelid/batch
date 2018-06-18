---
swagger: "2.0"
x-collection-name: AWS Machine Learning
x-complete: 1
info:
  title: AWS Machine Learning API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateBatchPrediction:
    get:
      summary: Create Batch Prediction
      description: Generates predictions for a group of observations.
      operationId: createBatchPrediction
      x-api-path-slug: actioncreatebatchprediction-get
      parameters:
      - in: query
        name: BatchPredictionDataSourceId
        description: The ID of the DataSource that points to the group of observations
          to predict
        type: string
      - in: query
        name: BatchPredictionId
        description: A user-supplied ID that uniquely identifies the                BatchPrediction
        type: string
      - in: query
        name: BatchPredictionName
        description: A user-supplied name or description of the BatchPrediction
        type: string
      - in: query
        name: MLModelId
        description: The ID of the MLModel that will generate predictions for the
          group of observations
        type: string
      - in: query
        name: OutputUri
        description: The location of an Amazon Simple Storage Service (Amazon S3)
          bucket or directory to store the batch prediction results
        type: string
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Batches
  /?Action=DeleteBatchPrediction:
    get:
      summary: Delete Batch Prediction
      description: Assigns the DELETED status to a BatchPrediction, rendering it unusable.
      operationId: deleteBatchPrediction
      x-api-path-slug: actiondeletebatchprediction-get
      parameters:
      - in: query
        name: BatchPredictionId
        description: A user-supplied ID that uniquely identifies the BatchPrediction
        type: string
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Batches
  /?Action=DescribeBatchPredictions:
    get:
      summary: Describe Batch Predictions
      description: Returns a list of BatchPrediction operations that match the search
        criteria in the request.
      operationId: describeBatchPredictions
      x-api-path-slug: actiondescribebatchpredictions-get
      parameters:
      - in: query
        name: EQ
        description: The equal to operator
        type: string
      - in: query
        name: FilterVariable
        description: 'Use one of the following variables to filter a list of BatchPrediction:'
        type: string
      - in: query
        name: GE
        description: The greater than or equal to operator
        type: string
      - in: query
        name: GT
        description: The greater than operator
        type: string
      - in: query
        name: LE
        description: The less than or equal to operator
        type: string
      - in: query
        name: Limit
        description: The number of pages of information to include in the result
        type: string
      - in: query
        name: LT
        description: The less than operator
        type: string
      - in: query
        name: NE
        description: The not equal to operator
        type: string
      - in: query
        name: NextToken
        description: An ID of the page in the paginated results
        type: string
      - in: query
        name: Prefix
        description: A string that is found at the beginning of a variable, such as
          Name or Id
        type: string
      - in: query
        name: SortOrder
        description: A two-value parameter that determines the sequence of the resulting
          list of MLModels
        type: string
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Batches
  /?Action=GetBatchPrediction:
    get:
      summary: Get Batch Prediction
      description: |-
        Returns a BatchPrediction that includes detailed metadata, status, and data file information for a
                    Batch Prediction request.
      operationId: getBatchPrediction
      x-api-path-slug: actiongetbatchprediction-get
      parameters:
      - in: query
        name: BatchPredictionId
        description: An ID assigned to the BatchPrediction at creation
        type: string
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Batches
  /?Action=UpdateBatchPrediction:
    get:
      summary: Update Batch Prediction
      description: Updates the BatchPredictionName of a BatchPrediction.
      operationId: updateBatchPrediction
      x-api-path-slug: actionupdatebatchprediction-get
      parameters:
      - in: query
        name: BatchPredictionId
        description: The ID assigned to the BatchPrediction during creation
        type: string
      - in: query
        name: BatchPredictionName
        description: A new user-supplied name or description of the BatchPrediction
        type: string
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Batches
---