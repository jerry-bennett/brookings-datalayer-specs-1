# Navigation Click

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "navigation_click",
  "detailed_event": "Navigation Click",
    "event_data": {
        "archived": <archived>,
        "author": "<author>",
        "author_id": "<author_id>",
        "author_type": "<author_type>",
        "center": "<center>",
        "content_type": "<content_type>",
        "format": "<format>",
        "historical_url": "<historical_url>",
        "language": "<language>",
        "module_name": <module_name>,
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
|event_data.content_type|string|Type of content||||||||
|event_data.format|string|Format||||||||
|event_data.historical_url|string|Historical URL||||||||
|event_data.interactive|boolean|Is the content interactive or not.||||||||
|event_data.language|string|Language of the content||||||||
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




