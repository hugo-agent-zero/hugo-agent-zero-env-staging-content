---
title: "haz_img process POC"
date: 2026-10-28T09:00:00-04:00
authors:
  - author_0001
categories:
  - Engineering
tags:
  - hugo
  - haz_img
  - demo
params:
  desc_short: "One master image; process builds the ladder (small JPEG, lg+ WebP)."
  desc_long: "Dogfood for HQ #165. Bundle has only seed.jpg. process=true fills missing rungs; format inherit on xs–md, webp on lg+ (q.webp / preset override)."
---

POC for **process**: the page bundle has a single master (`files/seed.jpg`, from demo-post-1 `_xxl`). There are no `seed_xs.jpg` … stubs. With `process=true`, `haz_img` fills those rungs via Hugo `Resize` (width-only). Ship settings: `xs`/`sm`/`md` stay `format: inherit` (JPEG); `lg`+ use `format: webp`. Stubs would still win as written; `src` stays the master.

{{< haz_img name="full_widescreen" process=true >}}
<img src="files/seed.jpg" alt="process=true — Hugo builds the ladder from one master">
{{< /haz_img >}}

<!--more-->

Same master, half left square (still process). CSS frame may crop display; files keep the master’s aspect.

{{< haz_img name="half_left_sqr" process=true >}}
<img src="files/seed.jpg" alt="half_left_sqr with process=true">
{{< /haz_img >}}

**Preset gate:** `demo_off_redirect` is `enabled: false` with `enabled_false: as_is` — resolves like `as_is` (no frame). `demo_off_dead` is off with no redirect (HTML comment only; no enrich).

{{< haz_img name="demo_off_redirect" process=true >}}
<img src="files/seed.jpg" alt="demo_off_redirect → as_is">
{{< /haz_img >}}

{{< haz_img name="demo_off_dead" process=true >}}
<img src="files/seed.jpg" alt="demo_off_dead should not enrich">
{{< /haz_img >}}
