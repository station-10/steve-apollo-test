# Interstitial Viewed

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Interstitial Viewed",
    "interstitial": {
        "viewType": "<viewType>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|viewType|string|Type of interstitial view|alert, offer, info required|||||||
