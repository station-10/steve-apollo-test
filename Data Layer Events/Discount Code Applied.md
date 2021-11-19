# Discount Code Applied

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Discount Code Applied",
    "voucherDiscount": {
        "applicationType": "<applicationType>",
        "discountCode": "<discountCode>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|applicationType|string|Captures the method that was used to apply the discount.|automatic, manual entry|||||||
|discountCode|string|Discount code entered or applied|5OFFSHOES, AKRONCANDLES2019|||||||




