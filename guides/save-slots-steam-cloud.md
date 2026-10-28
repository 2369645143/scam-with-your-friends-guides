---
title: "Save Slots, Steam Cloud & Missing Recordings"
description: "Understand Scam With Your Friends save slots, cloud progress, local settings and recordings before switching computers, resetting or changing saves."
category: "Technical"
badge: "SOURCE CHECK · 2026-10-28"
readingTime: "4 min read"
publishDate: "2026-10-28"
updatedDate: "2026-10-28"
lang: "en"
---


## What is saved where?
The October 23 **0.1.84** update added three save files, selected in Settings with day/prestige previews. Steam Cloud covers all saves. The October 25 **0.1.90** update separates saved media from Cloud progress.

| Content | Officially described storage behavior |
| --- | --- |
| Progress, cosmetics, prestige, checkpoints and permanent app purchases | Steam Cloud support was added in 0.1.83. |
| All three save files | Synced through Steam Cloud in 0.1.84. |
| Graphics, microphone, language, controls and volume settings | Stay on the current computer. |
| Recordings, pictures and other new saved media | Device-local storage in 0.1.90; not synced through Steam Cloud. |
| Lifetime achievements, statistics and playtime | Retained across resets, switches and prestige per 0.1.84. |

## Before switching a save or computer
1. Note the selected slot and its day/prestige preview. A different slot can look like lost progress.
2. Finish the current session and inspect Steam's Cloud status before launching elsewhere. If Steam shows a conflict, compare the available timestamps and progress before choosing; do not blindly replace either copy.
3. Recheck local microphone, language and graphics settings on the other computer.
4. Test progress separately from recordings. Missing recordings alone do not establish a Cloud progress failure.

These are precautionary checks, not a guarantee that a particular conflict can be recovered. This page does not invent a save-folder path or advise deleting save files.

## Why did a recording disappear?
**Stored Media History** offers 10, 100, everything or None, with separate video and picture limits. The default is 10; older managed files are removed as the limit is enforced. None stops new saved videos, photos and artwork, while temporary boss-review media can still be available.

Check the selected history limit, the computer where the capture was made, and whether it was saved media or a temporary review. A failed review can fall back to other playback; this does not promise a permanent video file. See [speech and logs](/guides/audio-microphone-setup/) if a review is also silent.

## What does Reset Save remove?
The **RESET SAVE** action introduced in 0.1.83 erases progress, cosmetics and permanent app purchases while retaining device settings. Its confirmation is not a normal connection fix. Do not reset to test a lobby or microphone issue.

## Multiplayer progress report
For an apparent guest-progress loss, record host and guest versions, chosen slots, day/prestige previews and which item is missing. 0.1.84 improved guest money and app-purchase persistence, but that note does not prove every current save is healthy.

## Source
[Official 0.1.83, 0.1.84 and 0.1.90 notes](https://steamcommunity.com/app/4954910/allnews/), checked October 28, 2026. Storage behavior is sourced; the inspection sequence is editorial guidance, not a playtest. [Co-op joining guide](/guides/coop-team-strategies/).
