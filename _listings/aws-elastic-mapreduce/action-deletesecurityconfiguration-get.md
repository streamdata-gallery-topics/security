---
swagger: "2.0"
info:
  title: AWS Elastic MapReduce API Delete Security Configuration
  version: 1.0.0
  description: Deletes a security configuration.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DeleteSecurityConfiguration:
    get:
      summary: ' Delete Security Configuration '
      description: Deletes a security configuration
      operationId: deleteSecurityConfiguration
      parameters:
      - in: query
        name: Name
        description: The name of the security configuration
        type: string
      responses:
        200:
          description: OK
      tags:
      - security configurations
definitions: []
x-collection-name: AWS Elastic MapReduce
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