---
layout: post
title:  "Why BPG will change image encoding as we know it."
date:   2015-10-20 21:41:00
description: BPG not only is way smaller than JPEG but also delivers a better quality. And that's not all! It also supports animations! Goodbye GIFs!

categories:
- blog
permalink: sample-post
---

Just a sample post to show some of the *typography* elements supported from 
**harmony** theme.


Let's start with a some history. BPG or Better Portable Graphics is how the author puts it:
 
> BGP is a new image format with the purpose to replace JPEG image format when quality or file size is an issue.
> - By Fabrice Bellard

This means that BPG not only is way smaller than JPEG but also delivers a better quality. And that's not all! It also supports animations!

And when I say animation, I actually say GIF-like movies with MP4 quality that are actually smaller than the mp4 it was built from.

Let's see an example (I have not included a GIF example because the same quality size and frame rate means that the GIF will have exactly 33.8MB.

So let's go:

{% include bpg_example.html %}

Spot the differences? :)

The mp4 doesn't include audio, and neither does the BPG.

Everywhere you look today, the rise of the GIF has started again, but the GIFs are not as we know them, they are all mp4s with loop attribute set, the only thing that makes them gifs are the fact that they of short duration and they loop.
imgur even release a "new" format called gifv which are actually mp4's if the device supports mp4s or GIF if they don't, on mobile they are by default GIF because you can't autoplay (cannot start without a user interaction) mp4.

BPG's don't have this problem, they autoplay like any GIF, and they are rendered in CANVAS (all devices today support HTML5 canvas).
 
The only downside is that no browsers supports them. You need to include a decompiling javascript. But if browsers will realize how great they are, they will definitely rule the world!

You can see another good comparison between BPG and JPEG [here.](http://xooyoozoo.github.io/yolo-octo-bugfixes/#pont-de-quebec-at-night&jpg=s&bpg=t)

JPEG is 55.3kb, BPG is 32Kb and the BPG has way better quality. 