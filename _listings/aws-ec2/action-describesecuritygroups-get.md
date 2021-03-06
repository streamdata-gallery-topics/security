---
swagger: "2.0"
info:
  title: AWS EC2 API Describe Security Groups
  version: 1.0.0
  description: Describes one or more of your security groups.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeSecurityGroups:
    get:
      summary: Describe Security Groups
      description: Describes one or more of your security groups
      operationId: describesecuritygroups
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the operation,
          without actually making the request, and provides an error response
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this request
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - security group
definitions: []
x-collection-name: AWS EC2
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