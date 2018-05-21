{
  "info": {
    "name": "Azure Container Service API Container Services List",
    "_postman_id": "49b11cf8-0ce3-4ed0-a39e-b9484428ea03",
    "description": "Gets a list of container services in the specified subscription. The operation returns properties of each container service including state, orchestrator, number of masters and agents, and FQDNs of masters and agents.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "containers",
      "item": [
        {
          "id": "af2b30b6-b9b3-43d2-9860-2d7b49988ed3",
          "name": "ContainerServices_List",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/providers/Microsoft.ContainerService/containerServices"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "subscriptionId",
                  "value": "subscriptionId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets a list of container services in the specified subscription"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "54608ccb-eac4-421d-b032-2c48a66770de"
            }
          ]
        }
      ]
    }
  ]
}