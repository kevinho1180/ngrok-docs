<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"ip_policy_ids":["ipp_2vqtyR96ISXncKUdBDDp1ytK81f","ipp_2vqtyStiu7uUCpMDTr0Y9PD2dkX"]}' \
https://api.ngrok.com/edges/tls/edgtls_2vqtyTbVJJcaPRVtraiqMeofket/ip_restriction
