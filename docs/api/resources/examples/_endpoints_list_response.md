<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Response
```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-04-17T10:11:18Z",
      "description": "sample cloud endpoint",
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
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-04-17T10:11:16Z",
      "hostport": "836b25f79c22.ngrok.paid:443",
      "id": "ep_2vqtxLH3zXU1DtYAzDjmmmC2iOo",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_2vqtuiL7bYri5vsRYNNLA1Yc5fQ",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://836b25f79c22.ngrok.paid",
      "tunnel": {
        "id": "tn_2vqtxLH3zXU1DtYAzDjmmmC2iOo",
        "uri": "https://api.ngrok.com/tunnels/tn_2vqtxLH3zXU1DtYAzDjmmmC2iOo"
      },
      "tunnel_session": {
        "id": "ts_2vqtxGoaGusowQ9MBjncUkEGUic",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_2vqtxGoaGusowQ9MBjncUkEGUic"
      },
      "type": "ephemeral",
      "updated_at": "2025-04-17T10:11:16Z",
      "upstream_url": "http://localhost:80",
      "url": "https://836b25f79c22.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-04-17T10:11:13Z",
      "domain": {
        "id": "rd_2vqtwkLHEJjcVHs0tvHvt5HmRTl",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2vqtwkLHEJjcVHs0tvHvt5HmRTl"
      },
      "edge": {
        "id": "edgtls_2vqtwwwFuzIqSRExDLfm9tTRhlS",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_2vqtwwwFuzIqSRExDLfm9tTRhlS"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2vqtwrabUGeeiOUSB9FoSKi07EQ",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-04-17T10:11:13Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
