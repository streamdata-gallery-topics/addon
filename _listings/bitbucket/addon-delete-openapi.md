---
swagger: "2.0"
x-collection-name: Bitbucket
x-complete: 0
info:
  title: Bitbucket Delete Add On
  description: Delete addon
  termsOfService: https://www.atlassian.com/legal/customer-agreement
  contact:
    name: Bitbucket Support
    url: https://support.atlassian.com/bitbucket
    email: support@bitbucket.org
  version: 1.0.0
host: api.bitbucket.org
basePath: /2.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /addon/linkers/{linker_key}/values/:
    parameters:
      summary: Parameters Add On Linkers Linker Key Values
      description: Parameters addon linkers linker key values
      operationId: parametersAddonLinkersLinkerKeyValues
      x-api-path-slug: addonlinkerslinker-keyvalues-parameters
      responses:
        200:
          description: OK
      tags:
      - Addon
      - Linkers
      - Linker
      - Key
      - Values
    get:
      summary: Get Add On Linkers Linker Key Values
      description: Get addon linkers linker key values
      operationId: getAddonLinkersLinkerKeyValues
      x-api-path-slug: addonlinkerslinker-keyvalues-get
      responses:
        200:
          description: OK
      tags:
      - Addon
      - Linkers
      - Linker
      - Key
      - Values
    delete:
      summary: Delete Add On Linkers Linker Key Values
      description: Delete addon linkers linker key values
      operationId: deleteAddonLinkersLinkerKeyValues
      x-api-path-slug: addonlinkerslinker-keyvalues-delete
      responses:
        200:
          description: OK
      tags:
      - Addon
      - Linkers
      - Linker
      - Key
      - Values
  /addon/linkers/{linker_key}/values:
    put:
      summary: Update Add On Linkers Linker Key Values
      description: Put addon linkers linker key values
      operationId: putAddonLinkersLinkerKeyValues
      x-api-path-slug: addonlinkerslinker-keyvalues-put
      responses:
        200:
          description: OK
      tags:
      - Addon
      - Linkers
      - Linker
      - Key
      - Values
    post:
      summary: Add Add On Linkers Linker Key Values
      description: Post addon linkers linker key values
      operationId: postAddonLinkersLinkerKeyValues
      x-api-path-slug: addonlinkerslinker-keyvalues-post
      responses:
        200:
          description: OK
      tags:
      - Addon
      - Linkers
      - Linker
      - Key
      - Values
    parameters:
      summary: Parameters Add On Linkers Linker Key Values
      description: Parameters addon linkers linker key values
      operationId: parametersAddonLinkersLinkerKeyValues
      x-api-path-slug: addonlinkerslinker-keyvalues-parameters
      responses:
        200:
          description: OK
      tags:
      - Addon
      - Linkers
      - Linker
      - Key
      - Values
    get:
      summary: Get Add On Linkers Linker Key Values
      description: Get addon linkers linker key values
      operationId: getAddonLinkersLinkerKeyValues
      x-api-path-slug: addonlinkerslinker-keyvalues-get
      responses:
        200:
          description: OK
      tags:
      - Addon
      - Linkers
      - Linker
      - Key
      - Values
    delete:
      summary: Delete Add On Linkers Linker Key Values
      description: Delete addon linkers linker key values
      operationId: deleteAddonLinkersLinkerKeyValues
      x-api-path-slug: addonlinkerslinker-keyvalues-delete
      responses:
        200:
          description: OK
      tags:
      - Addon
      - Linkers
      - Linker
      - Key
      - Values
  /addon/linkers/{linker_key}:
    parameters:
      summary: Parameters Add On Linkers Linker Key
      description: Parameters addon linkers linker key
      operationId: parametersAddonLinkersLinkerKey
      x-api-path-slug: addonlinkerslinker-key-parameters
      responses:
        200:
          description: OK
      tags:
      - Addon
      - Linkers
      - Linker
      - Key
    get:
      summary: Get Add On Linkers Linker Key
      description: Get addon linkers linker key
      operationId: getAddonLinkersLinkerKey
      x-api-path-slug: addonlinkerslinker-key-get
      responses:
        200:
          description: OK
      tags:
      - Addon
      - Linkers
      - Linker
      - Key
  /addon/linkers:
    parameters:
      summary: Parameters Add On Linkers
      description: Parameters addon linkers
      operationId: parametersAddonLinkers
      x-api-path-slug: addonlinkers-parameters
      responses:
        200:
          description: OK
      tags:
      - Addon
      - Linkers
    get:
      summary: Get Add On Linkers
      description: Get addon linkers
      operationId: getAddonLinkers
      x-api-path-slug: addonlinkers-get
      responses:
        200:
          description: OK
      tags:
      - Addon
      - Linkers
  /addon:
    put:
      summary: Update Add On
      description: Put addon
      operationId: putAddon
      x-api-path-slug: addon-put
      responses:
        200:
          description: OK
      tags:
      - Addon
    parameters:
      summary: Parameters Add On
      description: Parameters addon
      operationId: parametersAddon
      x-api-path-slug: addon-parameters
      responses:
        200:
          description: OK
      tags:
      - Addon
    delete:
      summary: Delete Add On
      description: Delete addon
      operationId: deleteAddon
      x-api-path-slug: addon-delete
      responses:
        200:
          description: OK
      tags:
      - Addon
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