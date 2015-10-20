---
layout: post
title:  "Why BPG will replace GIFs and not only."
date:   2015-10-20 21:41:00
description: BPG not only is way smaller than JPEG but also delivers a better quality. And that's not all! It also supports animations! Goodbye GIFs!

categories:
- technology
- image encoding
- gifs
permalink: why-bpg-will-replace-gifs-and-not-only
---

Let's start with some history. BPG or Better Portable Graphics is:
 
> BGP is a new image format with the purpose to replace JPEG image format when quality or file size is an issue.
> - By Fabrice Bellard

This means that BPG not only is way smaller than JPEG but also delivers a better quality. And that's not all! It also supports animations!

And when I say animation, I actually say GIF-like movies with MP4 quality that are actually smaller than the mp4 it was built from.

Let's see an example (I have not included a GIF example because the same quality size and frame rate means that the GIF will have exactly 33.8MB.

So let's go:

{% include bpg_example.html %}

The movies is called [Ambition](fnd.ie/vid/BJ3B) and you can view it for on [Findie](fnd.ie/vid/BJ3B)

###Spot the differences? :) 

* There's none (the mp4 doesn't include audio, and neither does the BPG.)

###Downsides?

We got just a few...

* Decompiling time! - Current example is around 8-10s (the bigger the file, the slower the decompiling)... This would be easily solved if browsers would add native support.
* Main thread blocking while decompiling large files
* No sound support (but who cares, this is image encoding, we're not talking better video formats)

###Advantages?

* Animation support. You can have a GIF half the size of an MP4.
* Video inline play (but without sound). One of the biggest problems is that on Mobile Safari no video can be played inline. GIFs solve, and when we have GIFs that are 5% the size of the original, that's epic!
* High compression ratio. Smaller than a JPG and even smaller than Google's [WebP](https://developers.google.com/speed/webp/) with similar quality if not better.
* You can start using today with a Javascript decoder (gzipped size: 56 KB).
* And plenty other.

GIFs today are not even GIFs anymore. With the release of Imgur's [gifv](https://imgur.com/blog/2014/10/09/introducing-gifv/) the internet went nuts for nothing than a mp4 that has autoplay, and where's that not possible (mobiles), a very very low quality GIF.


###So what can we do?

Do some buzz, so that browsers actually start supporting it. Or start using it today, it requires some CPU processing, but hey? We're saving bandwidth! :D

For example there's a feature request on the Bugzilla Tracker of Firefox - [here](https://bugzilla.mozilla.org/show_bug.cgi?id=1111277)
 
Or share this article if you liked it! :D

More links:

* [BPG's official Page](bellard.org/bpg/)
* [Mirror Repository on GitHub](https://github.com/mirrorer/libbpg)
* [Visual Comparison of BPG vs JPG/WebP](http://xooyoozoo.github.io/yolo-octo-bugfixes/#pont-de-quebec-at-night&jpg=s&bpg=t)
* [Nice article BPG vs JPG](http://petapixel.com/2014/12/13/bpg-new-image-format-wants-replace-jpeg-equal-quality-half-size/)