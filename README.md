# Social media video specs 2026

Upload specs for Instagram Reels, TikTok, YouTube Shorts, Facebook, X, LinkedIn, Pinterest, Snapchat and Threads: aspect ratios, resolutions, max length, file size, caption and hashtag limits. Every value is sourced, mostly from the platforms' own help pages.

**Browse it with filters and sources:** https://shortformkit.com/social-media-video-specs-2026/

Updated 2026-10-13. Files in [`data/`](data/): one JSON with everything and one CSV per table.

## Rows (23 rows)

Sources for every row are in the CSV/JSON (`sources` column).

| platform | format | aspect ratios | recommended resolution | max duration seconds | max file size mb | caption char limit | hashtag limit | confidence |
|---|---|---|---|---|---|---|---|---|
| Instagram | Reels | 9:16 | 1440x2560 | 1200 |  | 2200 | 5 | mixed |
| Instagram | Feed video | 9:16 |  | 1200 |  | 2200 | 5 | mixed |
| Instagram | Stories | 9:16 | 1440x2560 | 60 |  |  |  | official |
| Instagram | Feed photo | 1.91:1 / 1:1 / 4:5 / 3:4 | 1080x1440 |  | 8 | 2200 | 5 | mixed |
| Instagram | Carousel | 1.91:1 / 1:1 / 4:5 / 3:4 | 1080x1440 |  | 8 | 2200 | 5 | mixed |
| TikTok | Video | 9:16 / 1:1 / 16:9 | 1080x1920 | 3600 |  | 2200 |  | mixed |
| TikTok | Photo mode / carousel |  |  |  | 20 | 4000 |  | official |
| YouTube | Long-form video | 16:9 |  | 43200 | 262144 | 5000 | 60 | official |
| YouTube | Shorts | 9:16 / 1:1 | 1080x1920 | 180 |  | 5000 | 60 | mixed |
| YouTube | Thumbnail | 16:9 / 9:16 | 3840x2160 |  | 50 |  |  | official |
| YouTube | Channel banner | 16:9 | 2560x1440 |  | 6 |  |  | official |
| Facebook | Reels | 9:16 | 1080x1920 |  |  | 63206 |  | mixed |
| Facebook | Feed video | 16:9 / 1:1 / 4:5 / 9:16 | 1440x1800 | 14460 | 4096 | 63206 |  | mixed |
| Facebook | Stories | 9:16 | 1080x1920 | 60 |  |  |  | official |
| X (Twitter) | Video | 16:9 / 1:1 / 9:16 / 4:5 / 2:3 / 1.91:1 | 1920x1080 (16:9) or 1080x1920 (9:16) | 140 | 512 | 280 |  | mixed |
| X (Twitter) | Image | 16:9 / 1:1 / 4:5 / 2:3 / 1.91:1 / 9:16 | 1080x1080 (1:1) or 1920x1080 (16:9) |  | 5 | 280 |  | official |
| LinkedIn | Video | 1:2.4 / 2.4:1 |  | 900 | 5120 | 3000 |  | mixed |
| LinkedIn | Document / carousel |  |  |  | 100 | 3000 |  | mixed |
| Pinterest | Video Pin | 1:1 / 2:3 / 4:5 / 9:16 |  | 900 | 2048 | 800 |  | official |
| Pinterest | Standard Pin | 2:3 | 1000x1500 |  | 20 | 800 |  | official |
| Snapchat | Spotlight | 9:16 | 1080x1920 | 300 |  |  |  | mixed |
| Threads | Video | 9:16 |  | 300 | 1024 | 500 | 1 | official |
| Threads | Image |  |  |  | 8 | 500 | 1 | official |

## Changes 2025 2026 (14 rows)

Sources for every row are in the CSV/JSON (`sources` column).

| platform | change |
|---|---|
| Instagram | January 2025: maximum Reels length raised from 90 seconds to 3 minutes, and the profile grid switched from squares to vertical rectangles. |
| Instagram | November 2025: Reels camera can record up to 20 minutes. Help Centre now states record and upload up to 20 minutes, but Reels over 3 minutes are not recommended to new audiences. |
| Instagram | December 2025: hashtags limited to 5 per post or reel (previously 30). Help Centre now says up to 5; the Graph API reference still says 30. |
| Instagram | Help Centre now lists supported photo aspect ratios as 1.91:1 to 3:4 (1080x1440 max); the Graph API still says 4:5 to 1.91:1. Change date not stated. |
| YouTube | From 2025-03-31 Shorts views count every start or replay with no minimum watch time. |
| YouTube | Official Artist Channels: square or vertical videos up to 3 minutes uploaded on or after 2025-12-08 are classified as Shorts (standard channels since 2024-10-15). |
| YouTube | Custom thumbnail guidance now recommends 3840x2160 (2160x3840 for Shorts) with up to 50 MB on desktop (2 MB on mobile). Change date not stated. |
| Facebook | June 2025: Videos tab renamed Reels; all videos posted to Facebook (except stories and live) are shared as reels of any length or orientation. Help Centre update dated September 2025 confirms the unification. |
| Snapchat | From 2025-02-01 eligible creators can monetize Spotlight videos longer than 1 minute (unified Monetization Program). |
| Threads | 2025-09-04: text attachments of up to 10,000 characters can be added to a post (base post limit stays 500). |
| TikTok | No dated 2025/2026 spec change confirmed in official TikTok sources. Current Support page: record up to 10 min, upload up to 60 min; photo posts up to 35 images. |
| X (Twitter) | No dated 2025/2026 spec change confirmed. Current Help Center: Premium uploads up to 4 hours / 16 GB, non-Premium 140 s / 512 MB. |
| LinkedIn | No dated 2025/2026 spec change confirmed; video help page shows 15 min max for all uploads (older pages said 10 min on mobile). |
| Pinterest | No dated 2025/2026 spec change confirmed. |

## How to cite

Shortform Kit (2026), Social media video specs 2026, https://shortformkit.com/social-media-video-specs-2026/

## More

- [All datasets](https://shortformkit.com/data/)
- [Free tools for creators](https://shortformkit.com/): downloader, transcripts, LUFS meter, safe zone checker, YouTube money calculator

## License

Data: CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). Compiled by Shortform Kit (https://shortformkit.com). Every value lists its original source; facts belong to their publishers, the compilation and the CSV/JSON files are CC BY 4.0. Please credit "Shortform Kit, shortformkit.com" with a link.
