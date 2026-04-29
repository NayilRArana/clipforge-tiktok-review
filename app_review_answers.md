# TikTok App Review Answers

## Basic description

Autoclips creator-owned longform videos into short-form clips, then posts and schedules them to connected platforms.

## Web/Desktop URL

Use the landing page you publish from this folder:

`/submission/tiktok_review/index.html`

## Terms of Service URL

Use the Terms page you publish from this folder:

`/submission/tiktok_review/terms.html`

## Privacy Policy URL

Use the Privacy page you publish from this folder:

`/submission/tiktok_review/privacy.html`

## Explain how each product and scope works within your app or website

ClipForge is a desktop creator workflow used by Musikage to turn creator-owned long-form music videos into short-form clips for social posting. The app downloads or imports a source video, automatically creates multiple short clips, formats them for vertical viewing, generates titles and hashtags, and prepares platform-specific metadata. For TikTok, the app uses Login Kit so the creator can explicitly authorize ClipForge to act on their own account. After authorization, ClipForge uses the Content Posting API with the video.publish scope to upload and publish creator-owned short clips to TikTok. The TikTok integration is only used for publishing content that the creator has already prepared and chosen to post. The app also stores token data locally so the creator does not need to re-authorize every session, and it checks post status after submission.

## Suggested app review notes

- Product used: `Login Kit`
- Product used: `Content Posting API`
- Scope used: `video.publish`
- Optional scope mention: `user.info.basic` for confirming the authorized TikTok account identity
