Only schedule the approved content in Airtable from the `Content` table to all the relevant Metricool brands and platform accounts outlined below. Content MUST BE checked as being approved.

## RELEVANT BRANDS

COMMAND - (Instagram, LinkedIn)
Tad Personal - (LinkedIn)

## REQUIREMENTS

- Include any relevant media for the supported "Post Types" (Image, Text, Video, Image Carousel)
  - Image means include an image with the post
  - Video means include a video with the post
  - Image Carousel means includes the array of image media with the post
- Do not hallucinate. If you are unsure then ask for clarification
- Use the Dropbox URLs when uploading the content to Metricool
- The media content is already in Dropbox
- Do not download the media as the link is intended to be forward to Metricool so that Metricool will download the media

## DISTRIBUTE AT THE FOLLOWING DATE/TIME

Distribute the content according to the distribution dates

### INSTAGRAM (Reel)

```json
{
  "autoPublish": true,
  "descendants": [],
  "draft": false,
  "firstCommentText": "",
  "hasNotReadNotes": false,
  "media": ["DROPBOX_URL"],
  "mediaAltText": [],
  "providers": [{ "network": "instagram" }],
  "publicationDate": {
    "dateTime": "2025-07-02T15:00:00",
    "timezone": "America/New_York"
  },
  "shortener": false,
  "smartLinkData": { "ids": [] },
  "text": "POST_TEXT_WITH_HASHTAGS",
  "instagramData": {
    "autoPublish": true,
    "tags": [],
    "type": "REEL",
    "showReelOnFeed": true
  }
}
```

### FACEBOOK (Works as regular post with video)

```json
{
  "autoPublish": true,
  "descendants": [],
  "draft": false,
  "firstCommentText": "",
  "hasNotReadNotes": false,
  "media": ["DROPBOX_URL"],
  "mediaAltText": [],
  "providers": [{ "network": "facebook" }],
  "publicationDate": {
    "dateTime": "2025-07-02T15:05:00",
    "timezone": "America/New_York"
  },
  "shortener": false,
  "smartLinkData": { "ids": [] },
  "text": "POST_TEXT_HERE",
  "facebookData": { "type": "REEL" }
}
```

### YOUTUBE (Minimal data approach)

```json
{
  "autoPublish": true,
  "descendants": [],
  "draft": false,
  "firstCommentText": "",
  "hasNotReadNotes": false,
  "media": ["DROPBOX_URL"],
  "mediaAltText": [],
  "providers": [{ "network": "youtube" }],
  "publicationDate": {
    "dateTime": "2025-07-02T15:10:00",
    "timezone": "America/New_York"
  },
  "shortener": false,
  "smartLinkData": { "ids": [] },
  "text": "VIDEO_DESCRIPTION",
  "youtubeData": {
    "title": "TITLE_HERE",
    "type": "short",
    "privacy": "public",
    "category": "SCIENCE_TECHNOLOGY",
    "madeForKids": false
  }
}
```

### LINKEDIN (Standard approach)

```json
{
  "autoPublish": true,
  "descendants": [],
  "draft": false,
  "firstCommentText": "",
  "hasNotReadNotes": false,
  "media": ["DROPBOX_URL"],
  "mediaAltText": [],
  "providers": [{ "network": "linkedin" }],
  "publicationDate": {
    "dateTime": "2025-07-02T15:15:00",
    "timezone": "America/New_York"
  },
  "shortener": false,
  "smartLinkData": { "ids": [] },
  "text": "PROFESSIONAL_POST_TEXT",
  "linkedinData": {
    "documentTitle": "",
    "publishImagesAsPDF": false,
    "previewIncluded": false,
    "type": ""
  }
}
```

### TIKTOK (Minimal approach)

```json
{
  "autoPublish": true,
  "descendants": [],
  "draft": false,
  "firstCommentText": "",
  "hasNotReadNotes": false,
  "media": ["DROPBOX_URL"],
  "mediaAltText": [],
  "providers": [{ "network": "tiktok" }],
  "publicationDate": {
    "dateTime": "2025-07-02T15:20:00",
    "timezone": "America/New_York"
  },
  "shortener": false,
  "smartLinkData": { "ids": [] },
  "text": "POST_TEXT_WITH_HASHTAGS"
}
```
