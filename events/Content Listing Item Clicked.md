# Content Listing Item Clicked

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Content Listing Item Clicked",
    "listingItemClicked": {
        "listing": [
            {
                "content": {
                    "contentAuthor": "<contentAuthor>",
                    "contentID": "<contentID>",
                    "contentTitle": "<contentTitle>"
                }
            }
        ]
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|contentAuthor|string|Unique identifer of the content author.|Betsy Ross, Ben Franklin, Howard Hughes, Tipper Gore|||||||
|contentID|string|Unique identifer of the content.||||||||
|contentTitle|string|Title of a piece of content. |50 ways to use jello, Another look at pandas, Year end giving|||||||
