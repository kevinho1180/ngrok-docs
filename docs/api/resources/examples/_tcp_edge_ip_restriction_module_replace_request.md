<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"ip_policy_ids":["ipp_2vqtyRF0ZSvRY6na80jqfCK6CBd"]}' \
https://api.ngrok.com/edges/tcp/edgtcp_2vqtySE8V4elo8t4U7MlkSP0cO9/ip_restriction
