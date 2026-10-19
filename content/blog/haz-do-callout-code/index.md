---
title: "haz_do callout: code"
date: 2026-10-15T13:26:00-04:00
authors:
  - author_0001
categories:
  - Notes
tags:
  - hugo
  - demo
  - haz-do
params:
  desc_short: "Dogfood haz_do callout type code."
  desc_long: "Code callout with the FA </> icon. Color is Simple --code. Samples cover a title, no title, and Markdown in the body."
---

Type **code**. `</>` icon. Use it for snippets, commands, and API notes. The inner may be more than code. Do not write `<pre>` or `<code>`. After trimming, zero fences means the body is wrapped as one code block. One or more fences are left as written.

{{< haz_do add="callout" type="code" title="Command" >}}
Pin core at `@v1.x.x`. Pages pulls that branch, not `main`.
{{< /haz_do >}}

## Test samples

No title.

{{< haz_do add="callout" type="code" >}}
This code callout has no title.
{{< /haz_do >}}

Markdown in the body.

{{< haz_do add="callout" type="code" title="With Markdown" >}}
Recolor `--haz_callout_code` in `theme.css`.

```toml
[[module.imports]]
path = "github.com/hugo-agent-zero/hugo-agent-zero-core"
```
{{< /haz_do >}}
