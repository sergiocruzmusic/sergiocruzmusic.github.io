# Website Management Instructions

This guide explains how to update the content of the website directly through GitHub, without needing any technical tools.

## Quick Links to Content Files
- **Videos List**: [_data/videos.yml](_data/videos.yml)
- **Contact Information**: [_data/contact.yml](_data/contact.yml)

---

## How to Update the Website

### 1. Adding or Editing Videos
To add a new video or change existing ones:

1. Click on the **Videos List** link above (or navigate to the `_data` folder and click `videos.yml`).
2. Look for the pencil icon **(Edit this file)** in the top right corner of the file view and click it.
3. You will see a list of videos. Each video block looks like this:
   ```yaml
   - title: Name of the Video
     youtube_id: WO6Ic_GGDsM
     description: >-
       A brief description of the video goes here.
   ```
4. **To add a new video**: Copy an existing block (from the `-` dash to the description) and paste it at the top or bottom of the list.
   - **title**: The title that appears on the site.
   - **youtube_id**: This is the code at the end of a YouTube link. 
     - *Example*: If the link is `https://www.youtube.com/watch?v=WO6Ic_GGDsM`, the ID is **`WO6Ic_GGDsM`**.
   - **description**: The text describing the video.
5. **Important**: Be careful to keep the spacing and alignment exactly the same as the other items.

### 2. Updating Contact Info
To change email, social media links, or other contacts:

1. Click on the **Contact Information** link above (or navigate to `_data/contact.yml`).
2. Click the pencil icon **(Edit this file)**.
3. Update the `url` (the web link) or `label` (the text shown on the site) as needed.

---

## How to Save Your Changes

Once you have finished editing a file:

1. Scroll to the top right of the page and click the green button labeled **Commit changes...**.
2. A small window will pop up. You can write a short message describing what you did (e.g., "Added new video"), or leave the default message.
3. Click the green **Commit changes** button to confirm.

**That's it!** The website will automatically update with your changes shortly (usually within a minute or two).

---
[https://www.sergiocruzmusic.com.br](sergiocruzmusic.com.br)
