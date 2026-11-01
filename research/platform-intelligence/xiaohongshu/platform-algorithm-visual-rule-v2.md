# Xiaohongshu / 小红书 — Platform algorithm & cover visual rule v2

Checked: 2026-11-01

## Public research

- **GenRank / Explore Feed:** https://arxiv.org/html/2505.04180v2 — describes a cascade of retrieval, pre-ranking, ranking and policy re-ranking; public examples include click probability, expected duration, user history, hashtags, publish time, author follower count, multimodal item embeddings and author graph embeddings. It is not a creator-facing weight table.
- **Search relevance / KDD 2026:** https://arxiv.org/pdf/2512.00968 — describes five query-note relevance levels and semantic analysis including query understanding, taxonomy, keyword matching and content proportion. Its search experiment uses CES aggregating likes, favorites, comments, shares and follows; this is not a published universal ranking formula.
- **NoteLLM:** https://arxiv.org/html/2403.01744v1 — research on note summaries, hashtags/categories and note-to-note retrieval.
- **IDProxy:** https://arxiv.org/html/2603.01590v1 — research on multimodal content signals for cold-start CTR prediction.

## Cover design implications

1. Treat recommendation feed and active search as separate entry paths.
2. For search, align query intent, cover subject, note title, body and image content. Use natural terms; do not stuff or repeat keywords.
3. For feed, make the audience, problem/benefit/result or aesthetic subject clear in the thumbnail.
4. Keep cover promise, note title and body consistent. The cover can complement the title field rather than duplicating it word-for-word.
5. Tutorial/resource content should deliver save-worthy utility; product/case/portfolio content should show real evidence and useful detail.
6. A 3:4 working canvas is a practical default for many image-note covers. Xiaohongshu merchant training suggests 3:4 for product-note covers, while its video-note teaching discusses 16:9/9:16 video covers; do not apply one ratio to every content type.

## Commerce and AI compliance

Some Xiaohongshu School rules are explicitly scoped to merchants/buyers publishing product/service or sales content. Apply them only within scope. They warn against low-quality collages, excessive text, subject occlusion, low-resolution images and misleading clickbait. All creators must also follow current platform rules and AI labelling requirements.

AI-generated/synthetic content must be labelled according to the applicable law and current publish UI; do not claim synthetic scenes are real.

## Post-publish review

Separate recommendation and search sources. Use actual backend fields for impressions/opens/clicks, search exposure, reading/retention, saves, comments, shares, follows and product clicks/conversions when available. Do not invent CTR or infer all performance from the cover.
