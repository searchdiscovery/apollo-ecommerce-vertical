# User Registered

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "User Registered",
    "user": {
        "registrationType": "<registrationType>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|registrationType|string|Describes the thing that was registered for |account, loyalty program, event, sweepstakes, warranty|||||||
