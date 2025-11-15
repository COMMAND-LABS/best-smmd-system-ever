# TLDR

How to implement the Airtable Base in your account the manual way. This is designed to be customizable so adjust the table structure to meet your needs.

## Manual Approach

- Create 3 tables
  - `Compilation Prompts` Table
    - Prompt (Long text)
    - Post Type (Single select)
      - Image
      - Video
      - Text
      - Image Carousel
    - Created Date (Date)
    - Note (Short text)
  - `Content` Table
    - ID (Autonumber)
    - Prompt (Long text) [TIP: Make it hidden]
    - Post Type (Single select)
      - Image
      - Video
      - Text
      - Image Carousel
    - Instagram Caption (Long text)
    - LinkedIn Post (Long text)
    - X.com Post (Long text)
    - YouTube Title + Description (Long text)
    - TikTok Post (Long text)
    - Facebook Post (Long text)
    - Creation Date (Date)
    - Distribution Date (Date) [Optional]
    - Media (Attachment)
    - Approved (Checkbox)
  - `Distribution Prompts` Table
    - Prompt (Long text)
    - Post Type (Single select)
      - Image
      - Video
      - Text
      - Image Carousel
    - Created Date (Date)
    - Note (Short text)
