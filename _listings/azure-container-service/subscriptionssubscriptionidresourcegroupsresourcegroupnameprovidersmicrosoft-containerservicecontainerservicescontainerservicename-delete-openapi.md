---
swagger: "2.0"
x-collection-name: Azure Container Service
x-complete: 0
info:
  title: Azure Container Service API Container Services Delete
  description: Deletes the specified container service in the specified subscription
    and resource group. The operation does not delete other resources created as part
    of creating a container service, including storage accounts, VMs, and availability
    sets. All the other resources created with the container service are part of the
    same resource group and can be deleted individually.
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /subscriptions/{subscriptionId}/providers/Microsoft.ContainerService/containerServices:
    get:
      summary: Container Services List
      description: Gets a list of container services in the specified subscription.
        The operation returns properties of each container service including state,
        orchestrator, number of masters and agents, and FQDNs of masters and agents.
      operationId: ContainerServices_List
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoft-containerservicecontainerservices-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Containers
      - Services
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ContainerService/containerServices/{containerServiceName}
  : put:
      summary: Container Services Create Or Update
      description: Creates or updates a container service with the specified configuration
        of orchestrator, masters, and agents.
      operationId: ContainerServices_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerservicecontainerservicescontainerservicename-put
      parameters:
      - in: path
        name: containerServiceName
        description: The name of the container service in the specified subscription
          and resource group
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to the Create or Update a Container Service
          operation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Containers
      - Services
    get:
      summary: Container Services Get
      description: Gets the properties of the specified container service in the specified
        subscription and resource group. The operation returns the properties including
        state, orchestrator, number of masters and agents, and FQDNs of masters and
        agents.
      operationId: ContainerServices_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerservicecontainerservicescontainerservicename-get
      parameters:
      - in: path
        name: containerServiceName
        description: The name of the container service in the specified subscription
          and resource group
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Containers
      - Services
    delete:
      summary: Container Services Delete
      description: Deletes the specified container service in the specified subscription
        and resource group. The operation does not delete other resources created
        as part of creating a container service, including storage accounts, VMs,
        and availability sets. All the other resources created with the container
        service are part of the same resource group and can be deleted individually.
      operationId: ContainerServices_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerservicecontainerservicescontainerservicename-delete
      parameters:
      - in: path
        name: containerServiceName
        description: The name of the container service in the specified subscription
          and resource group
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Containers
      - Services
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