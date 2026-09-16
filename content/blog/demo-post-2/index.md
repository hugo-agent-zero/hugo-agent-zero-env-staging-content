---
title: "Demo post 2: taxonomies and archives"
date: 2026-04-23T14:30:00-07:00
lastmod: 2026-04-23T14:30:00-07:00
publishdate: 2026-04-22T14:30:00-07:00
author_id: author_0001
authors:
  - author_0001
  - author_0002
categories:
  - Notes
  - Product
tags:
  - hugo
  - taxonomy
  - demo
slug: demo-post-2
params:
  desc_short: Second demo post sharing categories/tags with post 1 so taxonomy pages show multiple entries.
  head_tags:
    document:
      title:
        _title: "Demo post 2 (local title)"
        _title_prefix: "page prefix"
        _title_suffix: "page suffix"
    meta:
      _apple_basic:
        apple-mobile-web-app-status-bar-style: black-translucent-123
      _web_app_global:
        apple-mobile-web-app-title: TODO Child 
      html_basic:
        _description: "Demo page for single blog post layout and params.meta.html_basic meta tags."
        _author: "Author Meta (local)"
        _robots: "noindex,nofollow"
        _canonical: "https://example.org/about/"
      # List replaces site collection; omit height/width/type → Atomic defaults fill gaps.
      # _og_video:
      #   - url: /defaults/meta_tag_default_video.mp4
      og_audio:
        - url: "https://test.com/demo-post-2.mp3"
          title: "OG AUDIO TITLE (PAGE)"
      _og_basic:
        og:image: cover.svg
        og:description: "My Page Desc"
      _og_global:
        og:site_name: "Page Site NAme"
---

The front matter sets **`slug: demo-post-2`**, which matches this folder name anyway — if you changed it to another slug, the URL’s last segment would follow `slug` instead of the folder name.

{{< haz key="blog" >}}

![Second FPO cover](cover.svg)

<!--more-->

## Shared metadata

This post shares **Notes** and the tag **hugo** with demo post 1 so the generated taxonomy pages list more than one article. **Product** appears only here for variety.
