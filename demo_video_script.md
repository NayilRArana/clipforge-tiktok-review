# TikTok Demo Video Script

Target: 2 to 4 minutes, one clean screen recording.

## Scene 1: Show the app and project

1. Start on the ClipForge folder or terminal.
2. Briefly show the landing page or repo name so the reviewer can match the product identity.
3. State that ClipForge is used to create short clips from creator-owned videos for Musikage.

## Scene 2: Show TikTok auth

1. Run:

```powershell
python main.py --only schedule --platforms tiktok --tiktok-auth
```

2. Show the TikTok authorization page opening.
3. Show the account approval flow.
4. Return to the terminal and show the success message that the token file was created.

## Scene 3: Show a prepared short

1. Show that the app already has prepared captioned clips in the campaign project folders.
2. Briefly open one clip file or its folder so the reviewer can see there is real media content being posted.

## Scene 4: Show TikTok schedule preview

1. Run:

```powershell
python main.py --campaign --platforms tiktok --campaign-end-date 2026-05-31 --dry-run
```

2. Scroll enough for the reviewer to see that ClipForge is building TikTok follow-up posts from an existing campaign schedule.

## Scene 5: Show an actual TikTok publish

1. Run a single real post using a time-safe mode, such as the next scheduled clip in run-now mode if available.
2. Show the terminal output that TikTok posting has started.
3. Show the resulting success status and returned publish information.

Suggested command if using a controlled test project:

```powershell
python main.py --campaign --platforms tiktok --run-now
```

If you prefer to demonstrate a standard schedule run instead, make sure the reviewer can still clearly see one actual post complete.

## Scene 6: Show result tracking

1. Show the local manifest or logs capturing TikTok post status.
2. If possible, show the resulting post inside TikTok or the creator account feed to confirm end-to-end behavior.

## Reviewer checklist

Make sure the video clearly demonstrates:

- Login Kit authorization
- creator-owned content being posted
- Content Posting API usage
- the `video.publish` scope use case
- successful publish/status result
