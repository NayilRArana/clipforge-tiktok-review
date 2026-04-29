# TikTok Portal Values

Use these values in the TikTok Developer Portal.

## Production > App details

### App icon

Upload:

`submission/tiktok_review/icon_1024.png`

### App name

`ClipForge (Musikage)`

### Category

`Photo & Video`

### Description

`Autoclips creator-owned longform videos into shorts, then posts and schedules them.`

### Terms of Service URL

Use your hosted public URL:

`https://YOUR-HOSTNAME/terms.html`

### Privacy Policy URL

Use your hosted public URL:

`https://YOUR-HOSTNAME/privacy.html`

### Platforms

Select:

- `Desktop`

You may also select `Web` if you want, but `Desktop` is the cleaner match for this workflow.

### Configure for Web/Desktop > Web/Desktop URL

Use your hosted public landing page URL:

`https://YOUR-HOSTNAME/`

## Products

Add:

- `Login Kit`
- `Content Posting API`

## Scopes

Add:

- `video.publish`
- `user.info.basic`

## App review > Explain how each product and scope works

Paste:

`ClipForge is a desktop creator workflow used by Musikage to turn creator-owned long-form music videos into short-form clips for social posting. The app downloads or imports a source video, automatically creates multiple short clips, formats them for vertical viewing, generates titles and hashtags, and prepares platform-specific metadata. For TikTok, the app uses Login Kit so the creator can explicitly authorize ClipForge to act on their own account. After authorization, ClipForge uses the Content Posting API with the video.publish scope to upload and publish creator-owned short clips to TikTok. The TikTok integration is only used for publishing content that the creator has already prepared and chosen to post. The app also stores token data locally so the creator does not need to re-authorize every session, and it checks post status after submission. The user.info.basic scope is only used to confirm the identity of the connected TikTok account.`

## App review > Demo video

Use:

`submission/tiktok_review/demo_video_script.md`

That script shows exactly what to record.
