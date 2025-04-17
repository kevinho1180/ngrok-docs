<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"ip_policy_ids":["ipp_2vqtxrWFbAghKiix13w6UK56BMl","ipp_2vqtxyKFXZDXsn9kvrNRUiRn49u"]}' \
https://api.ngrok.com/edges/https/edghts_2vqtxthOLpwWHkz6Ar2ltu78hGk/routes/edghtsrt_2vqtxvMlCx0biRYL9PISHBP3w0f/ip_restriction
