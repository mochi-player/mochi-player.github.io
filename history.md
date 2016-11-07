---
layout: page
title: History
permalink: /history/
---

{{ site.program_name }} has had different names before, but it's fundamental goals were the same. An easy to use multimedia player that could play anything and was not in your way.

## AniPlayer (our early high school years)

Before it was called {{ site.program_name }}, or even Baka MPlayer, it was called AniPlayer (then AniPlayer X). This was written in `VB.NET`. Design wise, it wasn't beautiful. It used Windows Vista-era graphics and default .NET controls.

![AniPlayer 0.7.9 screenshot](/images/screenshots/AniPlayer/AniPlayer 0.7.9.png "AniPlayer 0.7.9")

![AniPlayer 1.0.5 screenshot](/images/screenshots/AniPlayer/AniPlayer X 1.0.5.png "AniPlayer 1.0.5")

![AniPlayer 1.3 screenshot](/images/screenshots/AniPlayer/AniPlayer X 1.3.png "AniPlayer 1.3")

![AniPlayer 1.4 screenshot](/images/screenshots/AniPlayer/AniPlayer X 1.4.png "AniPlayer 1.4")

## Niko Neko Puryea (our late high school years)

Technology change! I gained experience and it was now coded in `C#`. The name was also changed to Niko Neko Puryea. It still wasn't beautiful but it no longer used stock controls.

![Niko Neko Pureya 0.9.1 screenshot](/images/screenshots/Niko Neko Pureya/Niko Neko Pureya 0.9.1.png "Niko Neko Pureya 0.9.1")

![Niko Neko Pureya 0.9.8.2 BETA screenshot](/images/screenshots/Niko Neko Pureya/Niko Neko Pureya 0.9.8.2 BETA.png "Niko Neko Pureya 0.9.8.2 BETA")

## Baka MPlayer (our early college years)

A new name! The word "baka" is a non offending way of saying stupid in Japanese. I switched from `VB.NET` to `C#`. The playback engine used `MPlayer`, then `mplayer2`, then finally `mpv`. It allowed Baka MPlayer to open almost any media file. It's design also started to settle down. A simple voice command ability that was based off of Window's speech-to-text API was added.

![Baka MPlayer pre-1.5.0 screenshot](/images/screenshots/Baka MPlayer/pre-1.5.0 (mpv based).png "Baka MPlayer pre-1.5.0")

![Baka MPlayer 1.5.0 screenshot](/images/screenshots/Baka MPlayer/1.5.0 (mpv based).png "Baka MPlayer pre-1.5.0")

## Baka MPlayer (our later college years till ~2015)

My friend u8sand showed interest in helping out with the project. He was a Linux user so we agreed to make it cross platform. We decided to utilize the open source, `cross-platform Qt framework`. Qt had a different way of styling its UI from .NET. It allows the usage of `CSS` to customize it's look and feel. I took advantage of that.

![Baka MPlayer 2.0.2 screenshot](/images/screenshots/Baka MPlayer/2.0.2.png "Baka MPlayer 2.0.2")

![Baka MPlayer 2.0.4 screenshot](/images/screenshots/Baka MPlayer/2.0.4.png "Baka MPlayer 2.0.4")

## {{ site.program_name }}

We started from the ground up again. The last version of Baka MPlayer used `Qt Widgets`. We've decided to transition to `Qt Quick` + `QML`.

* Moved to popup settings from menu items

  While menu items are limited in technical functionality, popup menu allows you to incorperate whatever appropriate control (ie textbox, button, etc) whenever you need it. This allows us to organize the controls the way that makes the most sense, not limited to the cumbersome menu items.
  Menu items duplicate functionality of some playback controls.
