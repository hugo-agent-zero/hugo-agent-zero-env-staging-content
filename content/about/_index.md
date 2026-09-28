---
title: About
layout: single
params:
  head_tags:
    document:
      title:
        title: "About (local title)"
    meta:
      html_basic:
        description: "Demo page for single layout and params.meta.html_basic meta tags."
        author: "Author Meta (local)"
        # robots: "noindex,nofollow"
        # canonical: "https://example.org/about/"
      og_basic:
        og:title: "L - og title"
        og:type: "L - og type"
        #og:url: "L - og url"
        #og:image: "placeholder.svg"
        og:description: "L - og description"
      # false clears site default video list
      og_video: false
      # og_video:
      #   - url: video.mp4
      #     height: "456"
      #     width: "789"
      #     type: video/mp4
      og_audio:
        - url: "https://test.com/audio.mp3"
          title: "audio title"
          artist: "audio artist"
          album: "audio album"
          type: "application/mp3"
      apple_basic:
        #apple-mobile-web-app-status-bar-style: "todo"
      twitter_card:
        twitter:title: "this is my twitter title"
        twitter:description: "this is my twitter description"
---

This page checks single-template rendering.

{{< haz_tbd key="page" >}}
