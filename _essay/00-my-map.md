---
title: My map test
order: 1
byline: Alice McGrath
part: Alice's essay
---

## Introduction

This is my first essay using CB-Essay. I can write in **Markdown** with _formatting_.

Here's a paragraph with a [link](https://example.com).

## Another Section

- Bullet points work
- As expected<sup class="aside-ref"></sup><span class="aside">So do asides!
</span>

### Subsections too

I can add blockquotes:

{% include essay/feature/blockquote.html
   quote="This is a quotation"
   speaker="Someone Important" %}

## Let's have some fun now

I wonder how this text will appear.

{% include essay/feature/scrolly-map.html latitude="40.024197" longitude="-75.318314" zoom="12" caption="Bryn Mawr, PA" %}

I'm not sure where we are now. It seems like a long way from Idaho.


{% include essay/feature/scrolly-step.html latitude="40.024197" longitude="-75.318314" zoom="12" caption="This is where we are" %}

### Bryn Mawr

{% include essay/feature/scrolly-step.html map-lat="45.64579" map-lng="-114.62838" map-zoom="10" %}

{% include essay/feature/scrolly-end.html %}

### subheader?

## A forest

{% include essay/feature/scrolly-media.html objectid="demo_031" %}

I am lost in the forest.