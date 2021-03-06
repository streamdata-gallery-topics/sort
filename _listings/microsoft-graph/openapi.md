swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 1
info:
  title: Microsoft Graph API
  description: microsoft-graph-exposes-multiple-apis-from-office-365-and-other-microsoft-cloud-services-through-a-single-endpoint-httpsgraph-microsoft-com--microsoft-graph-simplifies-queries-that-would-otherwise-be-more-complex-
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
  /workbook/names(&lt;name&gt;)/range/sort/apply:
    post:
      summary: Range Sort Apply
      description: 'RangeSort: apply Perform a sort operation.'
      operationId: RangeSort:Apply
      x-api-path-slug: workbooknamesltnamegtrangesortapply-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Sort
      - Apply
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/sort/apply:
    post:
      summary: Range Sort Apply
      description: 'RangeSort: apply Perform a sort operation.'
      operationId: RangeSort:Apply
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtsortapply-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Sort
      - Apply
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/sort/apply:
    post:
      summary: Range Sort Apply
      description: 'RangeSort: apply Perform a sort operation.'
      operationId: RangeSort:Apply
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangesortapply-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Sort
      - Apply
  /workbook/tables(&lt;id|name&gt;)/sort/apply:
    post:
      summary: Table Sort Apply
      description: 'TableSort: apply Perform a sort operation.'
      operationId: TableSort:Apply
      x-api-path-slug: workbooktablesltidnamegtsortapply-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Sort
      - Apply
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/sort/apply:
    post:
      summary: Table Sort Apply
      description: 'TableSort: apply Perform a sort operation.'
      operationId: TableSort:Apply
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtsortapply-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Sort
      - Apply
  /workbook/tables(&lt;id|name&gt;)/sort/clear:
    post:
      summary: Table Sort Clear
      description: 'TableSort: clear Clears the sorting that is currently on the table.
        While this doesn''t modify the table''s ordering, it clears the state of the
        header buttons.'
      operationId: TableSort:Clear
      x-api-path-slug: workbooktablesltidnamegtsortclear-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Sort
      - Clear
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/sort/clear:
    post:
      summary: Table Sort Clear
      description: 'TableSort: clear Clears the sorting that is currently on the table.
        While this doesn''t modify the table''s ordering, it clears the state of the
        header buttons.'
      operationId: TableSort:Clear
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtsortclear-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Sort
      - Clear
  /workbook/tables(&lt;id|name&gt;)/sort:
    get:
      summary: Get Table Sort
      description: Get TableSort Retrieve the properties and relationships of tablesort
        object.
      operationId: GetTableSort
      x-api-path-slug: workbooktablesltidnamegtsort-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Sort
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/sort:
    get:
      summary: Get Table Sort
      description: Get TableSort Retrieve the properties and relationships of tablesort
        object.
      operationId: GetTableSort
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtsort-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Sort
  /workbook/tables(&lt;id|name&gt;)/sort/reapply:
    post:
      summary: Table Sort Reapply
      description: 'TableSort: reapply Reapplies the current sorting parameters to
        the table.'
      operationId: TableSort:Reapply
      x-api-path-slug: workbooktablesltidnamegtsortreapply-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Sort
      - Reapply
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/sort/reapply:
    post:
      summary: Table Sort Reapply
      description: 'TableSort: reapply Reapplies the current sorting parameters to
        the table.'
      operationId: TableSort:Reapply
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtsortreapply-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Sort
      - Reapply