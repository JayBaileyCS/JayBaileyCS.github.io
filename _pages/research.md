---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Research

This is a place to collect the research I've done. Mostly this'll be about short, self-contained explorations taking <20 hours rather than full-fledged papers or lengthy posts.

### Major (>20 hours)

[Features and Adversaries in MemoryDT](https://www.lesswrong.com/posts/yuQJsRswS4hKv3tsL/features-and-adversaries-in-memorydt) is part of a series of posts by [Joseph Bloom](https://www.lesswrong.com/users/joseph-bloom?from=post_header) about Decision Transformers trained on a GridWorld task. I helped on engineering, visualisation, and clarification of various concepts for this post.

### Minor (<20 hours)

[Articulating Latent Knowledge in Classification Problems](https://colab.research.google.com/drive/1nbN8g7s6oK7feeCi3EA8V13IZIgXPeOo?usp=sharing) When models do simple classification tasks, are they able to articulate the algorithm they use? When asked to give an algorithm, is the algorithm correct, and do they follow it? What edge cases, if any, cause it to fall apart?

[Current Word Head Investigation](https://colab.research.google.com/drive/1nbN8g7s6oK7feeCi3EA8V13IZIgXPeOo?usp=sharing) We find an attention head in GPT-2-small that looks to be activating on tokens that are part of the current word. I investigate what the head is doing, when it's accurate vs. not, identify several (flawed) metrics before selecting one, and find pretty conclusively that attention does not scale linearly with capabilities - accounting for 80% of the head's attention does not restore 80% of the loss when you write the head manually.
