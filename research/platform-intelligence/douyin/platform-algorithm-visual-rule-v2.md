# Douyin / 抖音 — Platform algorithm & cover visual rule v2

Checked: 2026-11-01

## Public mechanism

Douyin's Security & Trust Center explains recommendation as a multi-stage system: recall, ranking, time/context considerations and diversity adjustment. Its public explainer describes user-history behavior and content features, interaction behavior prediction, and signals such as likes, saves, shares and comments. This is a simplified public explanation, not a full model disclosure.

Official sources:
- https://trust.douyin.com/algorithm/
- https://trust.douyin.com/transparency
- https://trust.douyin.com/article/15358
- User agreement updated 2026-02-13, effective 2026-02-20: https://www.douyin.com/draft/douyin_agreement/douyin_agreement_user.html?id=6773906068725565448&ug_source=microsoft_dy_360dh
- AI governance: https://trust.douyin.com/article/15868
- CAC algorithm governance: https://www.cac.gov.cn/2025-05/22/c_1749536203490537.htm

## Cover design implications

1. Separate uploaded cover, video first frame and opening segment. A static cover does not replace the first frame or opening.
2. Show one clear subject/action/result: real presenter, product test, screen operation, transformation or on-site evidence.
3. Keep one viewing promise. Cover headline, post title, opening and body must tell the same story.
4. Use real UI and real footage when available. Never invent a software state, product test or customer result.
5. Keep text compact and legible; the title field can add context. Avoid turning the cover into a subtitle wall.
6. The 9:16 video canvas is not automatically the cover-image ratio. Check the actual publish slot. A 3:4 working cover (e.g. 1080×1440) may fit a portrait-card slot, but this is an implementation observation, not a universal platform rule. Use the live editor preview.

## Post-publish review

Use actual creator-center fields: source, plays/effective plays, early retention, average watch duration, completion/play progress, likes, comments, shares, follows, negative feedback and search source where available. Do not assume every account exposes cover CTR. Do not attribute all performance to the cover.

## Compliance

AI-generated non-real audio/video or content likely to confuse the public must be visibly labelled according to the current publish UI and platform rules. Do not impersonate real people, fabricate events, hide labels or create false endorsements. Commercial claims must be supported.

## Not established

No public fixed initial-exposure pool, universal first-three-second threshold, exact cover CTR weight or guaranteed-viral formula.
