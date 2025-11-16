# Metricool Scheduling Instructions

Only schedule the approved content in Airtable from the `Content` table to all the relevant Metricool brands and platform accounts outlined below. Content MUST BE checked as being approved.

## RELEVANT BRANDS

COMMAND - (Instagram, Facebook, YouTube, LinkedIn, TikTok)
Tad - (LinkedIn)

## REQUIREMENTS

- Video means include a video with the post
- Schedule to each platform separately
- Do not hallucinate. If you are unsure then ask for clarification
- Use the Dropbox URLs when uploading the content to Metricool
- The media content is already in Dropbox
- Make sure the media is uploaded properly
- When distributing to YouTube, use the title for the YouTube title and the description for the YouTube description, and make the category `Science & Technology`
- Upload this video to YouTube shorts
- Upload this video to IG as a Reel
- Upload the video to Facebook as a Reel
- Be sure to post to TikTok
- TikTok should work

## DISTRIBUTE AT THE FOLLOWING DATE/TIME

11/16/2025 around 9am ET (right now is it 11/16/2025 1:00 AM ET)

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
