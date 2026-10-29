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
  desc_long: "Dogfood for HQ #165 + fail knobs. Bundle has only seed.jpg. process=true fills missing rungs; format inherit on xs–md, webp on lg+. Also: omit name, bad name, missing src."
---

POC for **process**: the page bundle has a single master (`files/seed.jpg`, from demo-post-1 `_xxl`). There are no `seed_xs.jpg` … stubs. With `process=true`, `haz_img` fills those rungs via Hugo `Resize` (width-only). Ship settings: `xs`/`sm`/`md` stay `format: inherit` (JPEG); `lg`+ use `format: webp`. Stubs would still win as written; `src` stays the master.

{{< haz_img name="full_widescreen" process=true >}}
<img src="files/seed.jpg" alt="process=true — Hugo builds the ladder from one master">
{{< /haz_img >}}

<!--more-->

Same master, half left square (still process). This preset uses `fit: contain` (object-fit); files keep the master’s aspect.

{{< haz_img name="half_left_sqr" process=true >}}
<img src="files/seed.jpg" alt="half_left_sqr fit=contain">
{{< /haz_img >}}

**Preset gate:** `demo_off_redirect` is `enabled: false` with `enabled_false: as_is` — resolves like `as_is` (no frame). `demo_off_dead` is off with no redirect — same path as a missed name (HTML comment; Inner still prints when `name_not_in_presets.prod` is true).

{{< haz_img name="demo_off_redirect" process=true >}}
<img src="files/seed.jpg" alt="demo_off_redirect → as_is">
{{< /haz_img >}}

{{< haz_img name="demo_off_dead" process=true >}}
<img src="files/seed.jpg" alt="demo_off_dead: comment + Inner as-is (no enrich)">
{{< /haz_img >}}

**Rung gate:** `quarter_left_sqr` sets `lg`/`xl`/`xxl` `enabled: false` — srcset should stop at md (767w).

{{< haz_img name="quarter_left_sqr" process=true >}}
<img src="files/seed.jpg" alt="quarter_left_sqr without large rungs">
{{< /haz_img >}}

**Fail knobs (ship):** `preset_default: as_is`. `name_not_in_presets.prod: true` (comment + Inner). `src_404.prod: false` (comment only; no tag).

Omit `name=` → falls back to `as_is` (enrich, no frame):

{{< haz_img process=true >}}
<img src="files/seed.jpg" alt="omit name → preset_default as_is">
{{< /haz_img >}}

Bad `name=` → HTML comment in source; plain Inner still visible (no srcset/classes from haz_img):

{{< haz_img name="no_such_preset" process=true >}}
<img src="files/seed.jpg" alt="bad name → comment + Inner as-is">
{{< /haz_img >}}

Missing file → HTML comment only (no `<img>` in the page):

{{< haz_img name="as_is" process=true >}}
<img src="files/missing-nope.jpg" alt="src_404 false → comment only">
{{< /haz_img >}}
