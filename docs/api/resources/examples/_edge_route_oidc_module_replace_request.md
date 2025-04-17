<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"client_id":"some-client-id","client_secret":"some-client-secret","enabled":true,"issuer":"https://accounts.google.com","scopes":["profile"]}' \
https://api.ngrok.com/edges/https/edghts_2vqty48jTndA6xVQ8DT7wXrIHd5/routes/edghtsrt_2vqty49kCiGiNknTTWQzpMDlceX/oidc
