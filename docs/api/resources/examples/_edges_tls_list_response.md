<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Response
```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-04-17T10:11:24Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_2vqtyG2ORLjLI4Mn8iME8sBM0up",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2vqtyG2ORLjLI4Mn8iME8sBM0up"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_2vqtwuYAR9YvyKDWUJEsHFjC3nH",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_2vqtwuYAR9YvyKDWUJEsHFjC3nH"
        },
        "enabled": true
      },
      "created_at": "2025-04-17T10:11:13Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_2vqtwwwFuzIqSRExDLfm9tTRhlS",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2vqtwwwFuzIqSRExDLfm9tTRhlS"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
