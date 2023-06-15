# Page Load Started

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({ page_data: null });  // Clear the previous page_data object.
dataLayer.push({
  "event": "page_load_started",
  "detailed_event": "Page Load Started",
    "event_data": {
        "archived": <archived>,
        "author": "<author>",
        "author_id": "<author_id>",
        "author_type": "<author_type>",
        "center": "<center>",
        "chart_id": "<chart_id>",
        "content_type": "<content_type>",
        "email_subscribers": <email_subscribers>,
        "format": "<format>",
        "historical_url": "<historical_url>",
        "interactive": <interactive>,
        "original_post_id": "<original_post_id>",
        "parent": "<parent>",
        "post_id": "<post_id>",
        "primary_topic": "<primary_topic>",
        "program": "<program>",
        "project": "<project>",
        "publish_date": "<publish_date>",
        "region": "<region>",
        "subtype": "<subtype>",
        "tag_id": "<tag_id>",
        "tags": "<tags>",
        "template": "<template>",
        "topic": "<topic>",
        "type": "<type>",
        "word_count": "<word_count>"
    },
    "page_data": {
        "country": "<country>",
        "language": "<language>",
        "name": "<name>",
        "page_location": "<page_location>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.archived|boolean|Has the content been archived||||||||
|event_data.author|string|Author||||||||
|event_data.author_id|string|Author ID||||||||
|event_data.author_type|string|What type of author||||||||
|event_data.center|string|Center||||||||
|event_data.chart_id|string|ID number for chart||||||||
|event_data.content_type|string|Type of content||||||||
|event_data.email_subscribers|integer|Users who have signed up for email subscriptions.||||||||
|event_data.format|string|Format||||||||
|event_data.historical_url|string|Historical URL||||||||
|event_data.interactive|boolean|Is the content interactive or not.||||||||
|event_data.original_post_id|string|Original Post ID||||||||
|event_data.parent|string|Parent||||||||
|event_data.post_id|string|Post ID||||||||
|event_data.primary_topic|string|Primary Topic||||||||
|event_data.program|string|Program||||||||
|event_data.project|string|Project||||||||
|event_data.publish_date|string|Publish Date||||||||
|event_data.region|string|Region||||||||
|event_data.subtype|string|Subtype||||||||
|event_data.tag_id|string|Tag ID||||||||
|event_data.tags|string|Tags||||||||
|event_data.template|string|Template||||||||
|event_data.topic|string|Topic||||||||
|event_data.type|string|Type||||||||
|event_data.word_count|string|Word Count||||||||
|page_data.country|string|The country associated with the current page.|US, CA, FR, UK|||||||
|page_data.language|string|The language of the current page, usually pulled from the &lt;html&gt; tag lang attribute.|en-us, en-gb, ch-cn, fr-ca, fr-fr|||||||
|page_data.name|string|Captures the name of the page the user is on|product - XYZ123, Mens - Tops - Sweaters, Order Confirmation|||||||
|page_data.page_location|string|The URL of the page currently being viewed. This value will include the full, unaltered URL of the page\/screen the user is currently viewing, including query parameters, fragments, etc., for example https:\/\/www.example.com\/home?user=true&audience=test\#aboutus.|https:\/\/www.example.com\/home?user=true&audience=test\#aboutus|||||||




