# Create External Auths

URL: https://account-public-service-prod.ol.epicgames.com/account/api/public/account/:accountid/externalAuths \
Method: GET \

## Example Response

```json
[
  {
    "accountId": "7478627437294822bacb5b44b7f5c2da",
    "type": "github",
    "externalAuthId": "some id",
    "externalAuthIdType": "github_login",
    "externalDisplayName": "example",
    "authIds": [{ "id": "some id", "type": "github_login" }],
    "dateAdded": "2023-03-31T03:24:04.056Z"
  }
]
```
