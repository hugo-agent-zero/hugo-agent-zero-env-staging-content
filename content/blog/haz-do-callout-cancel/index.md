---
title: "haz_do callout: cancel"
date: 2026-10-08T12:10:00-07:00
authors:
  - author_0001
categories:
  - Notes
tags:
  - hugo
  - demo
  - haz-do
params:
  desc_short: "Dogfood haz_do callout type cancel."
  desc_long: "Cancel callout with a circle-slash icon. Same red as warning and love. Samples cover a title, no title, and Markdown in the body."
---

Type **cancel**. Circle with a slash. Same red as warning and love. Not allowed.

{{< haz_do add="callout" type="cancel" title="Cancel" >}}
Do not ship this build.
{{< /haz_do >}}

## Test samples

No title.

{{< haz_do add="callout" type="cancel" >}}
This cancel callout has no title.
{{< /haz_do >}}

Markdown in the body.

{{< haz_do add="callout" type="cancel" title="With Markdown" >}}
Skip the step that **deletes** the database.

1. Stop the job.
2. Restore the backup.
{{< /haz_do >}}
