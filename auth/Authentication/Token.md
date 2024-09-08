# Auth Token

URL: https://account-public-service-prod.ol.epicgames.com/account/api/oauth/token \
Method: POST \

## Example Request

- `client_credentials`

  grant_type=client_credentials&token_type=eg1

  ```

  ```

---

_Example Response (`client_credentials` Grant)_

```json
{
  "access_token": "FtZSI6ImV4YW1wbGVVc2VyIiwiaWQiOiIxMjM0NTY3O",
  "expires_in": 14400,
  "expires_at": "2023-08-30T20:32:21.466Z",
  "token_type": "bearer",
  "client_id": "ec684b8c687f479fadea3cb2ad83f5c6",
  "internal_client": true,
  "client_service": "prod-fn",
  "product_id": "prod-fn",
  "application_id": "fghi4567FNFBKFz3E4TROb0bmPS8h1GW"
}
```

_Example Response (`exchange_code` Grant)_

```json
{
  "access_token": "FtZSI6ImV4YW1wbGVVc2VyIiwiaWQiOiIxMjM0NTY3O",
  "expires_in": 7200,
  "expires_at": "2024-09-08T02:15:29.993Z",
  "token_type": "bearer",
  "refresh_token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VybmFtZSI6",
  "refresh_expires": 28800,
  "refresh_expires_at": "2024-09-08T08:15:29.993Z",
  "account_id": "7478627437294822bacb5b44b7f5c2da",
  "client_id": "ec684b8c687f479fadea3cb2ad83f5c6",
  "internal_client": true,
  "client_service": "prod-fn",
  "displayName": "example",
  "app": "prod-fn",
  "in_app_id": "7478627437294822bacb5b44b7f5c2da",
  "product_id": "prod-fn",
  "application_id": "fghi4567FNFBKFz3E4TROb0bmPS8h1GW"
}
```
