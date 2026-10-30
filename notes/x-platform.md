# X platform facts for tree-a-day
<!-- SUMMARY: what X allows for polls, scheduling and API posting, each with how it was checked · status: reference · updated: 2026-10-30 -->

Checked 2026-10-30. X changes often and its help pages lag, so re-check before relying on any of this.

## Polls

- 2 to 4 choices, up to 25 characters each, 5 minutes to 7 days. Source: X Help, "About X Polls" (help.x.com/en/using-x/x-polls), read in Chrome.
- Images on each choice exist on the web composer (an image button beside each choice, seen 2026-10-30). The same help page still says "Photos cannot be included in a X Poll", so the help pages are out of date.

## Scheduling

- X Pro's help page documents scheduling posts with images or video, and says nothing about polls (help.x.com/en/using-x/advanced-xpro-features).
- Web composer, 2026-10-30: with a poll attached, the Schedule button did nothing; with the poll removed, the schedule dialog opened. So polls can't be scheduled from the web. The phone app wasn't tested.
- Quote posts with an image can be scheduled from the web: Repost → Quote, add the image and text, then Schedule (done for 3 Nov 2026, 2026-10-30). The Repost button opens a small menu (Repost / Quote); choosing Repost reposts at once.
- Scheduled posts keep up to four images, each with its own alt text (up to 1,000 characters, "Add descriptions" under the images). Scheduled posts are listed at x.com/compose/post/unsent/scheduled.

## API (docs.x.com, fetched 2026-10-30)

- Pay-per-use pricing: "Post: Create" $0.015 per request; "Post: Create (with URL)" $0.200 per request (https://docs.x.com/x-api/getting-started/pricing.md). The 20 April 2026 start date for the URL price comes only from third-party blogs.
- Poll schema in POST /2/tweets: options are plain strings (2–4, 1–25 characters), duration 5–10080 minutes. There is no field for choice images, so the API can't post an image poll (https://docs.x.com/x-api/posts/create-post.md).
- "Quote-posting (using the `quote_tweet_id` parameter) requires an Enterprise plan. It is not available on self-serve (pay-per-use) tiers." (same page)
- A search summary said the docs call polls "mutually exclusive" with media. The create-post reference fetched here doesn't say that.

## What follows for automation

- A plain tree post (image, caption, no link) could be scheduled in X's composer or sent through the API for $0.015.
- Image polls have to be posted by hand: the API can't attach choice images and the web composer won't schedule polls. Quote-tweets can be scheduled in the web composer, though not sent through the self-serve API.
