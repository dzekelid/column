---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph Table Column Delete
  description: 'TableColumn: delete Deletes the column from the table.'
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /workbook/names(&lt;name&gt;)/range/Column:
    post:
      summary: Range Column
      description: 'Range: Column Gets a column contained in the range.'
      operationId: Range:Column
      x-api-path-slug: workbooknamesltnamegtrangecolumn-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Column
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/Column:
    post:
      summary: Range Column
      description: 'Range: Column Gets a column contained in the range.'
      operationId: Range:Column
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtcolumn-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Column
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/Column:
    post:
      summary: Range Column
      description: 'Range: Column Gets a column contained in the range.'
      operationId: Range:Column
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangecolumn-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Column
  /workbook/names(&lt;name&gt;)/range/EntireColumn:
    post:
      summary: Range Entire Column
      description: 'Range: EntireColumn Gets an object that represents the entire
        column of the range.'
      operationId: Range:EntireColumn
      x-api-path-slug: workbooknamesltnamegtrangeentirecolumn-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Entire
      - Column
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/EntireColumn:
    post:
      summary: Range Entire Column
      description: 'Range: EntireColumn Gets an object that represents the entire
        column of the range.'
      operationId: Range:EntireColumn
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtentirecolumn-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Entire
      - Column
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/EntireColumn:
    post:
      summary: Range Entire Column
      description: 'Range: EntireColumn Gets an object that represents the entire
        column of the range.'
      operationId: Range:EntireColumn
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeentirecolumn-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Entire
      - Column
  /workbook/tables(&lt;id|name&gt;)/columns:
    post:
      summary: Create Table Column
      description: Create TableColumn Use this API to create a new TableColumn.
      operationId: CreateTableColumn
      x-api-path-slug: workbooktablesltidnamegtcolumns-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns:
    post:
      summary: Create Table Column
      description: Create TableColumn Use this API to create a new TableColumn.
      operationId: CreateTableColumn
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtcolumns-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/DataBodyRange:
    post:
      summary: Table Column Data Body Range
      description: 'TableColumn: DataBodyRange Gets the range object associated with
        the data body of the column.'
      operationId: TableColumn:DataBodyRange
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtdatabodyrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
      - Data
      - Body
      - Range
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/DataBodyRange:
    post:
      summary: Table Column Data Body Range
      description: 'TableColumn: DataBodyRange Gets the range object associated with
        the data body of the column.'
      operationId: TableColumn:DataBodyRange
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegtdatabodyrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
      - Data
      - Body
      - Range
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/delete:
    post:
      summary: Table Column Delete
      description: 'TableColumn: delete Deletes the column from the table.'
      operationId: TableColumn:Delete
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtdelete-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/delete:
    post:
      summary: Table Column Delete
      description: 'TableColumn: delete Deletes the column from the table.'
      operationId: TableColumn:Delete
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegtdelete-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
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