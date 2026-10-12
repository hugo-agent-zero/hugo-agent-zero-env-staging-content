---
title: "haz_do grid, more"
date: 2026-10-12T08:30:00-04:00
authors:
  - author_0001
categories:
  - Notes
tags:
  - hugo
  - demo
  - haz-do
params:
  desc_short: "Show All overrides on a haz_do grid."
  desc_long: "more_after picks how many cells show on a phone. more_button is the label. 0 turns the button off."
---

`more_after` is how many cells a phone shows before the button. `more_button` is only the words. `more_after=0` stacks the whole list.

## Two, then the rest

{{< haz_do add="grid" more_after=2 more_button="Voir plus" >}}
<a class="haz_do_grid__item" href="/blog/">
  <h3>Write</h3>
  <p>Draft the page in Markdown.</p>
</a>
<a class="haz_do_grid__item" href="/blog/">
  <h3>Ship</h3>
  <p>Merge, then fast-forward the tag.</p>
</a>
<a class="haz_do_grid__item" href="/blog/">
  <h3>Notes</h3>
  <p>Leave a trail for the next pass.</p>
</a>
<a class="haz_do_grid__item" href="/blog/">
  <h3>Markup</h3>
  <p>One element is one cell.</p>
</a>
{{< /haz_do >}}

## No button

{{< haz_do add="grid" more_after=0 >}}
<a class="haz_do_grid__item" href="/blog/">
  <h3>Write</h3>
  <p>Draft the page in Markdown.</p>
</a>
<a class="haz_do_grid__item" href="/blog/">
  <h3>Ship</h3>
  <p>Merge, then fast-forward the tag.</p>
</a>
<a class="haz_do_grid__item" href="/blog/">
  <h3>Notes</h3>
  <p>Leave a trail for the next pass.</p>
</a>
<a class="haz_do_grid__item" href="/blog/">
  <h3>Markup</h3>
  <p>One element is one cell.</p>
</a>
<a class="haz_do_grid__item" href="/blog/">
  <h3>Review</h3>
  <p>Read it once before you merge.</p>
</a>
<a class="haz_do_grid__item" href="/blog/">
  <h3>Publish</h3>
  <p>The page is the demo.</p>
</a>
{{< /haz_do >}}
