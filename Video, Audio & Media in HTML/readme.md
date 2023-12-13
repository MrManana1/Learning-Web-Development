# README: Video, Audio & Media in HTML

This HTML document showcases the usage of video, audio, image, and an embedded YouTube video, along with styling adjustments. 

## HTML Code:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Video, Audio & Media in HTML</title>
</head>
<style>
    video {
        height: 200px;
    }
</style>
<body>
    <!-- Video -->
    <video src="video.mp4" controls autoplay loop muted poster="1.PNG"></video>

    <!-- Audio -->
    <audio src="audio.m4a" controls autoplay></audio>

    <!-- Image -->
    <img src="imag.svg" alt="hi">

    <!-- YouTube Video -->
    <iframe width="560" height="315" src="https://www.youtube.com/embed/XZwBNDGuWGU?si=fFadpNDlLGz3OJCe&amp;start=777" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</body>
</html>
```

## Description:

### Video (`<video>`):
- A video element is embedded with controls for play/pause, autoplay, loop, and muted attributes.
- The video file "video.mp4" is linked.
- A poster image ("1.PNG") is displayed before the video plays.

### Audio (`<audio>`):
- An audio element is embedded with controls for play/pause and autoplay.
- The audio file "audio.m4a" is linked.

### Image (`<img>`):
- An image element is embedded with the source "imag.svg" and an alt attribute for accessibility.

### YouTube Video (`<iframe>`):
- An embedded YouTube video using an iframe with specific attributes for playback control.
- The video starts at the specified timestamp (start=777).

## Styling:

### CSS Code:
```css
video {
    height: 200px;
}
```

- The video element is styled to have a fixed height of 200 pixels.

## How to Use:

1. Open the HTML file in a web browser.
2. Observe the video, audio, image, and embedded YouTube video on the page.
3. Interact with the controls provided for the video and audio elements.

## Note:

- The use of autoplay, loop, and muted attributes in the video tag controls its behavior.
- The YouTube video is embedded using an iframe with specific settings for responsiveness and playback control.
- Customize the source URLs and attributes as needed for your media files and preferences.