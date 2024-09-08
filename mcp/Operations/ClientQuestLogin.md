## ClientQuestLogin

URL: https://fngw-mcp-gc-livefn.ol.epicgames.com/fortnite/api/game/v2/profile/:accountid/client/ClientQuestLogin \
Method: Post \

**Description**: `Generates new Quests if not added.` \
**Profiles**: `athena, campaign`

## Example Request

```json
{
  "streamingAppKey": ""
}
```

## Example Response

```json
{
{
  "profileRevision" : 0,
  "profileId" : "athena",
  "profileChangesBaseRevision" : 0,
  "profileChanges" : [ {
    "changeType" : "statModified",
    "name" : "quest_manager",
    "value" : {
      "dailyLoginInterval" : "2022-03-08T00:15:46.465Z",
      "dailyQuestRerolls" : 1
    }
  } ],
  "notifications" : [ {
    "type" : "redeemStwTokensNotification",
    "primary" : true,
    "client_request_id" : "",
    "totalMissionXPRedeemed" : 0,
    "totalQuestXPRedeemed" : 0
  } ],
  "profileCommandRevision" : 0,
  "serverTime" : "2022-03-08T00:15:46.543Z",
  "multiUpdate" : [ {
    "profileRevision" : 0,
    "profileId" : "common_core",
    "profileChangesBaseRevision" : 0,
    "profileChanges" : [ {
      "changeType" : "itemRemoved",
      "itemId" : "93034ed347f4431a978bdc9035281f3b"
    }, {
      "changeType" : "itemAdded",
      "itemId" : "e682cfe3f8414eff82d8c96b9bab18a9",
      "item" : {
        "templateId" : "EventPurchaseTracker:generic_instance",
        "attributes" : {
          "event_instance_id" : ""
        },
        "quantity" : 1
      }
    } ],
    "profileCommandRevision" : 0
  } ],
  "responseVersion" : 1
}
}
```
