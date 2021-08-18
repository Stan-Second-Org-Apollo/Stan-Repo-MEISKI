# Content Loaded

### This event is part of the page load sequence, including virtual page loads in the case of single page apps, and must be pushed between the `Page Load Started` and `Page Load Completed` events.

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Content Loaded",
    "content": {
        "contentID": "<contentID>",
        "licensor": "<licensor>"
    },
    "items": [
        {
            "contentAuthor": "<contentAuthor>",
            "contentTitle": "<contentTitle>"
        }
    ]
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|contentAuthor|string|Unique identifer of the content author.|Betsy Ross, Ben Franklin, Howard Hughes, Tipper Gore|||||||
|contentID|string|Unique identifer of the content.||||||||
|contentTitle|string|Title of a piece of content. |50 ways to use jello, Another look at pandas, Year end giving|||||||
|licensor|string|The licensee or owner of content \(i.e. HBO\)|HBO, Disney|||||||
