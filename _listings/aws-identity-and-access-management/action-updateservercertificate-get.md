---
swagger: "2.0"
info:
  title: AWS Identity and Access Management API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=UpdateServerCertificate&k=1:
    get:
      summary: ' Update Server Certificate '
      description: |-
        Updates the name and/or the path of the specified server certificate stored in
              IAM
      operationId: updateServerCertificate
      parameters:
      - in: query
        name: NewPath
        description: The new path for the server certificate
        type: string
      - in: query
        name: NewServerCertificateName
        description: The new name for the server certificate
        type: string
      - in: query
        name: ServerCertificateName
        description: The name of the server certificate that you want to update
        type: string
      responses:
        200:
          description: OK
      tags:
      - server certificates
definitions: []
x-collection-name: AWS Identity and Access Management
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