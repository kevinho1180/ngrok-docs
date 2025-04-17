<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Response
```json
{
  "bindings": [
    "public"
  ],
  "created_at": "2025-04-17T10:11:18Z",
  "description": "Sample Cloud Endpoint",
  "domain": {
    "id": "rd_2vqtwkLHEJjcVHs0tvHvt5HmRTl",
    "uri": "https://api.ngrok.com/reserved_domains/rd_2vqtwkLHEJjcVHs0tvHvt5HmRTl"
  },
  "hostport": "endpoint-example2.com:443",
  "id": "ep_2vqtxU6a139BcBMfge6wwpsSfxL",
  "metadata": "{\"environment\": \"staging\"}",
  "pooling_enabled": false,
  "proto": "https",
  "public_url": "https://endpoint-example2.com",
  "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
  "type": "cloud",
  "updated_at": "2025-04-17T10:11:18Z",
  "uri": "https://api.ngrok.com/endpoints/ep_2vqtxU6a139BcBMfge6wwpsSfxL",
  "url": "https://endpoint-example2.com"
}
