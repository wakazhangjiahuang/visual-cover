# WeChat Channels / 微信视频号 — Platform algorithm & cover visual rule v2

Checked: 2026-11-01

## Public mechanism

The Cyberspace Administration of China stated on 2025-05-22 that WeChat Channels has continued to improve a **dual mechanism of friends recommendation and algorithm recommendation**, alongside recommendation-content governance. The regulator page links to the official Channels announcement “视频号算法推荐优化，一键开启更多兴趣探索”.

Sources:
- https://www.cac.gov.cn/2025-05/22/c_1749536203490537.htm
- https://mp.weixin.qq.com/s/ANFSKXeED9jdZmWch-dpzQ
- AI-generated-content labelling rules: https://www.cac.gov.cn/2025-03/14/c_1743654684782215.htm

The public disclosure does not provide the weight split, exact ranking thresholds or a fixed share-count rule.

## Cover design implications

1. Design for feed recognition and social-share context: a viewer should understand the subject even when the sender's caption is absent.
2. Use a recognizable presenter/brand, credible work scene or real evidence when it helps trust; do not force a face into every cover.
3. For enterprise/knowledge content, show the real problem, system/process, delivered result and limits. Do not present a concept demo as a launched client system.
4. Use one complete proposition or question. A 7–15 character title range observed in one project sample is not an official character limit.
5. Avoid dense text blocks, fake chat screenshots, fake friend endorsements and artificial engagement prompts.
6. Distinguish video canvas from uploaded cover. Some current publisher implementations support vertical 3:4 and horizontal 4:3 cover slots; verify the actual account's publish UI and preview before export.

## Post-publish review

Use available creator-backend fields such as plays, watch duration, completion, likes, comments, shares/forwards, follows, profile visits and source split if available. Sharing is a business-relevant behavior but must not be described as a published algorithm weight.

## Boundary

This document is for WeChat Channels (视频号), not WeChat Official Accounts (公众号). The legacy `wechat/` document remains an official-account reference only.
