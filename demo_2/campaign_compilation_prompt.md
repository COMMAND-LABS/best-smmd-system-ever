# TASK

Generate copy for a multi-day marketing campaign to post once per day to LinkedIn & Instagram. You should generate about 5-6 days of posts in total. The last day of posting should be 11/20/2025 (aka the day of the event on 11/20/2025).

The posts should promote an event happening Thursday November 20th, 2025 6pm-10pm EST in Wynwood, Miami, FL called "AI SALES SYSTEMS MASTERCLASS". Each post should highlight how many days are left until the event and include the EVENT PROMO IMAGE AS WELL.

You will later loop over these posts and store them into Airtable.

## LINK TO EVENT PROMO IMAGE

{
"url": "https://www.dropbox.com/scl/fi/20fofdxacj6x9nxweixf8/NOV_20th_AI_MASTERCLASS_v2.png?rlkey=uu8hxx0jdcvvn30bnyzoeoo8t&st=ehfv4g7d&dl=1",
}

## ABOUT THE IMAGE

This image is an event promo graphic containing the event details (time, location, title, etc.) for THE AI SALES SYSTEMS MASTERCLASS taking place on Thursday evening 11/20/2025 at The DOCK in Wynwood, Miami, FL

Event starts at 6pm EST and ends at 10pm EST sharp on 11/20/2025

## GENERAL REQUIREMENT

- Make the output natural and impossible to detect as being A.I. generated
- Use spacing and new lines to make the marketing copy easy to read
- Use minimal emojis
- Do NOT bold any text when generating the copy for LinkedIn
- Avoid em-dashes
- Make the posts short and succinct
- CTA is for people who are interested in attending the event to grab a seat here: https://luma.com/sales-systems
- Date format is MM/DD/YYYY
- Include the event image in each posts media field

## TODAY'S DATE

11/15/2025 (we are ~5 days from the actual event)

## OUTPUT SCHEMA

Your output should adhere to the following JSON schema

{
"type": "array",
"items": {
"type": "object",
"properties": {
"prompt": {
"type": "string"
},
"content_type": {
"type": "string",
"enum": ["Image", "Image Carousel", "Text", "Video"]
},
"ig_caption": {
"type": "string"
},
"linkedin_post": {
"type": "string"
},
"x_post": {
"type": "string"
},
"youtube_post": {
"type": "string"
},
"tiktok_post": {
"type": "string"
},
"facebook_post": {
"type": "string"
},
"link_to_media": {
"type": "array",
"items": {
"type": "object",
"properties": {
"url": {
"type": "string"
},
"filename": {
"type": "string"
}
},
"required": ["url", "filename"]
}
},
"creation_date": {
"type": "string",
"format": "date"
},
"distribution_date": {
"type": "string",
"format": "date"
}
},
"required": [
"prompt",
"content_type",
"ig_caption",
"linkedin_post",
"x_post",
"youtube_post",
"tiktok_post",
"facebook_post",
"link_to_media",
"creation_date",
"distribution_date"
]
}
}

## SEO KEYWORDS

ai, course, masterclass, miami, south, florida, learn, network
