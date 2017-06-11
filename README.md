# ULTIMATE PAGE, DIV BACKGROUND
This is the jQuery plugin to add image/video background to any divs on your HTML page. It supports both YouTube videos and self hosted video.

If you have questions, please send an email to dat.tm24 (I use gmail)

Thanks!

# How to use
Using the plugin is very simple. You need to include it in your page first, of course. After that, suppose you want to add YouTube video background to div#video, do this

```javascript
jQuery('#video').c47bg({
  type: 'youtube',
  container: 'div',
  source: 'youtube video ID'
});
```
If you want to use self hosted video, make sure you have .mp4, .ogv and .webm

```javascript
jQuery('#video').c47bg({
  type: 'self-hosted',
  container: 'div',
  source: {
    mp4: 'mp4 url',
    webm: 'webm url',
    ogv: 'ogv url'
  }
});
```

If you want to apply the video to the body, replace container from div to body.

