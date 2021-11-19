# User Signed In

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "User Signed In",
    "user": {
        "custKey": "<custKey>",
        "loyalty": {
            "memberId": "<memberId>",
            "memberStatus": "<memberStatus>"
        },
        "loyaltyPoints": <loyaltyPoints>,
        "organizationID": "<organizationID>",
        "persistedLogin": <persistedLogin>,
        "system": "<system>",
        "userType": "<userType>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|custKey|string|Unique identifier of a customer.  Any id's considered PII must be hashed. ||||||||
|loyaltyPoints|integer|Number of loyalty points |100, 101, 1000||||0|||
|memberId|string|Member Identifier in a Loyalty program|abc1234, def876, 87987659|||||||
|memberStatus|string|Member status, level, or tier in a Loyalty program|Gold, Bronze, Platinum, Diamond, Silver|||||||
|organizationID|string|Customer Organization ID associated with website or mobile app behavior.|1234, G72345, Alaska|||||||
|persistedLogin|integer|Count of times users selected the option to persist their login \(i.e.,"keep me logged in"\) when signing in.||||||||
|system|string|Describes the system that the user is logged into.  \(rarely used\). |admin, shop, member|||||||
|userType|string|Describes the type of the user.  Often used to differentiate customers from employees or associates. |employee, guest, agent, customer|||||||




