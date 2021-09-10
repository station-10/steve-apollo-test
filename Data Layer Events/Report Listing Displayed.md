# Report Listing Displayed

### This event is part of the page load sequence, including virtual page loads in the case of single page apps, and must be pushed between the `Page Load Started` and `Page Load Completed` events.

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Report Listing Displayed",
    "listingDisplayed": {
        "displayCount": "<displayCount>",
        "listing": [
            {
                "isDisplayed": "<isDisplayed>",
                "itemPosition": "<itemPosition>",
                "report": {
                    "reportID": "<reportID>",
                    "reportType": "<reportType>"
                }
            }
        ],
        "listingDriver": "<listingDriver>",
        "resultsCount": "<resultsCount>"
    },
    "listingRefined": {
        "listingType": "<listingType>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|displayCount|integer|The total number of items displayed out of all returned items. \(Integer\)|10, 20, 30, 40||||0|||
|isDisplayed|boolean|Helper node used by AA Product String Builder to set product scoped events|true|||||||
|itemPosition|integer|Integer position of a property within a sorted result. The first returned is position 1. For map results, this value can be the rank by distance from POI.|1, 2, 3, 4, 5||||0|||
|listingDriver|string|Describes the action that caused the listing to be displayed|Onsite Search, Curated Assortment, Navigation|||||||
|listingType|string|The type of listings shown|Product, Location, Event, Room, Content|||||||
|reportID|string|Unique ID for a Report||||||||
|reportType|string|The type of the report|Transactions, Financial|||||||
|resultsCount|integer|The total number of items returned that matched the search criteria. \(Integer\)|1, 21, 111, 166||||0|||



