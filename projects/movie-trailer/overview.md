# 1. Overview

## Why Does This Project Exist?

Support for native video and audio are still inconsistent across Browsers. JavaScript is required to provide hooks for styling, and consistency of playback across browser. Also, responsive design of video is very cumbersome. This is why YouTube, Vimeo, Daily Motion, etc. embeds are very popular and easy-to-use.

The downsides of this ease-of-use are:

* UI \(user interface\) does not match website or content
* YouTube and others show advertisements
* Use of `object`, `embeds`, and Flash \(no mobile support\)

Videos have been apart the Web for decades. Yet, support for native video \(and audio\) are still inconsistent across browser, the [`video` element specification is still in a work in progress](https://www.w3.org/TR/2011/WD-html5-20110113/video.html#video), and requires JavaScript to provide hooks for styling. Also, responsive design of videos is very cumbersome. This is why YouTube, Vimeo, Daily Motion, etc. embeds are very popular and easy-to-use.

For now, we HTML, CSS, and JS to:

* Create a video UI that matches the brand and _Art Direction_
* Avoid time consuming process of encoding video for [every platform and resolution](https://support.google.com/youtube/answer/6375112?co=GENIE.Platform%3DDesktop&hl=en)
* Utilize existing video sources like YouTube, Vimeo, etc. as CDN \(content delivery network\)



