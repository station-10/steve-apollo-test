# Error Message Presented

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Error Message Presented",
    "error": {
        "errorCode": "<errorCode>",
        "errorType": "<errorType>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|errorCode|string|Error code or Error message presented to the user|Credit Card Authorization Failed , EC345, Form is incomplete|||||||
|errorType|string|General type of error presented|Payment, System, Form|||||||




