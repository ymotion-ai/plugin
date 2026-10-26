---
name: ymotion
description: Make and edit videos with Ymotion through its tools (ymotion_*). Use when someone asks to edit a video, make a reel, add captions, hook text or other text, cut, grade, add transitions, sound effects or music, or export a video.
---

# Ymotion

Ymotion is a video editor you drive through its tools. Every change is a real edit to a film that opens
in the web editor at https://ymotion.ai, where the person can see and change it too.

## Start here

1. `ymotion_help` with no arguments: what Ymotion is and the order of calls that works.
2. Making a reel: `ymotion_help {"name":"reels"}` says what each kind of reel needs, and each thing it
   names (captions, hook text, cuts, sound effects…) has its own card: `ymotion_help {"name":"hook_text"}`.
3. Bringing a video, a photo or music in: `ymotion_upload`, then `ymotion_media` to see what arrived.
4. Templates (captions, hook text, calls to action, charts…) and presets (grades, text animations,
   transitions): `ymotion_find`.
5. Edits go through `ymotion_edit`; look at the result with `ymotion_render`, and export from there.

The replies say what to do next: follow them rather than guessing a call.

## AI credits

Ymotion is free to use. Only jobs that run on a GPU cost AI credits — cutting a person out of a video,
a photo's cut-out or background removed, and enhancing a video — at 3 credits for every started 30
seconds of video (31 seconds counts as a minute), and 3 for a photo. Run them only on the stretch that
needs it, never the whole video by habit. `ymotion_help {"topic":"account"}` shows the balance and what
costs what. A job refused for credits says so, and nothing was charged.

## Signing in

The first Ymotion call asks the person to sign in at ymotion.ai. Their films, uploads and credits are
their account's.
