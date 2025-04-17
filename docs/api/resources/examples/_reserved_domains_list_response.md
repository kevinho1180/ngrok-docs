<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Response
```json
{
  "next_page_uri": null,
  "reserved_domains": [
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": {
        "authority": "letsencrypt",
        "private_key_type": "ecdsa"
      },
      "certificate_management_status": {
        "provisioning_job": {
          "error_code": null,
          "msg": "Managed certificate provisioning in progress.",
          "retries_at": null,
          "started_at": "2025-04-17T10:10:57Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.2sudkadv2ewucecaa.local-ngrok-cname.com",
      "created_at": "2025-04-17T10:10:57Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_2vqtuvu4KDEc5THntZwVRlor8Bj",
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2vqtuvu4KDEc5THntZwVRlor8Bj"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_2vqtuozzHs0HgoiA6JZBkMQVXyf",
        "uri": "https://api.ngrok.com/tls_certificates/cert_2vqtuozzHs0HgoiA6JZBkMQVXyf"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.2sudkadv2ewucecaa.local-ngrok-cname.com",
      "created_at": "2025-04-17T10:10:56Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_2vqtuta72wyuOvRgZqrRQHXfxSv",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2vqtuta72wyuOvRgZqrRQHXfxSv"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
