# Changelog

## Unreleased

- **WeChat Official Account articles** (mp.weixin.qq.com) are supported: right-click an article for a card with the account, title, cover and an excerpt of the opening paragraphs, or highlight a passage for a quote card credited to the account. Image posts keep their pictures.
- Four softer styles: **Blossom** (pale pink with two sparkles), **Cloud** (sky blue with a small cloud), **Memo** (cream paper with washi tape) and **Matcha** (sage with a stitched edge), each in light and dark.
- Fix: cards with a title (Reddit, Zhihu, Xiaohongshu) failed to render because of a variable used before it was declared.
- Handles that are labels (a Zhihu badge, a WeChat writer) no longer get an "@" in front.
- Several images share one box like on X (side by side, one tall plus two, 2×2) instead of stacking full width; longer galleries continue in rows of two.
- Video covers in the main post get a play badge.
- X avatars use the 400px image, so they're no longer blurry.
- Quoted posts on X now render as a nested card (author, date, text and media, with a play badge on videos) instead of being merged into the main post's text and images.
- Link previews on X render as a card (image, domain, title) instead of being dropped.
- Chinese and Japanese text wraps at any character, so a line no longer ends early after a Latin word; paragraph breaks are kept as a gap.
- Links in a post no longer leave X's hidden "https://" prefix on a line of its own; emoji drawn as images are kept.

## 1.3.0 — 2026-10-02

- **Copy as image** now matches X's own share menu (font, spacing, hover) and closes the menu after you click it.
- The share-menu item follows the page's language (English, Simplified or Traditional Chinese).
- New **Adjust** panel in the toast: style, theme, size and whole thread in one place.
- New sizes: Auto, 1:1, 4:5 and 9:16.
- Select a sentence inside a post to get a quote card that still credits the author, date and link.
- Platform logo next to the author, mirrored with the avatar (can be turned off in Settings).
- More accurate X stats: read from the post's action bar only, and shown compactly (4.2M instead of 4188675).
- Clearer wording everywhere: "Copy as image", "Copy post as image", "Copy selection as image".

## Earlier versions

Not tracked in this file.
