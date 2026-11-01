# Platform Intelligence Index

Checked: 2026-11-01

| Mode | Platform | Primary distribution context | Current rule |
|---|---|---|---|
| A | Douyin / 抖音 | Personalized recommendation, search, profile/share surfaces | [v2](douyin/platform-algorithm-visual-rule-v2.md) |
| B | WeChat Channels / 微信视频号 | Friends recommendation + algorithm recommendation, sharing | [v2](wechat-channels/platform-algorithm-visual-rule-v2.md) |
| C | Xiaohongshu / 小红书 | Recommendation feed + active search | [v2](xiaohongshu/platform-algorithm-visual-rule-v2.md) |

## Routing

- First select A/B/C; never apply one platform's cover/title assumptions to another.
- For multi-platform publication, create separate platform briefs, titles, cover structures, aspect ratios and QA.
- Separate public facts, research evidence, implementation observations and practitioner hypotheses.
- Legacy `wechat/` refers to WeChat Official Accounts (公众号). It is not the B-mode WeChat Channels source.

## Source hierarchy

1. Current official platform rules, creator-center pages and regulator disclosures.
2. Platform-team / primary research papers.
3. GitHub implementation and UI acceptance evidence.
4. Practitioner samples and third-party commentary.

No source in this index proves an unpublished algorithm weight or guarantees traffic.
