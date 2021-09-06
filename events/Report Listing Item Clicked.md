# Report Listing Item Clicked

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Report Listing Item Clicked",
    "listingItemClicked": {
        "listing": [
            {
                "itemPosition": "<itemPosition>",
                "report": {
                    "reportID": "<reportID>",
                    "reportType": "<reportType>"
                }
            }
        ]
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|itemPosition|integer|Integer position of a property within a sorted result. The first returned is position 1. For map results, this value can be the rank by distance from POI.|1, 2, 3, 4, 5||||0|||
|reportID|string|Unique ID for a Report||||||||
|reportType|string|The type of the report|Transactions, Financial|||||||
