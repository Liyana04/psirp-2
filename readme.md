This landing page is a dark-mode hero design inspired by the Framer reference.

How to add the hero background video:
- Open `index.html`.
- Find the `<video>` block inside the hero section.
- Add one or more `<source>` tags with your video file(s), for example:

```html
<video class="hero__video" playsinline muted autoplay loop preload="metadata">
  <source src="videos/hero-loop.mp4" type="video/mp4">
  <source src="videos/hero-loop.webm" type="video/webm">
</video>
```

Where to get a good loopable background video:
- Pexels Videos: https://www.pexels.com/videos/
- Pixabay Videos: https://pixabay.com/videos/
- Coverr: https://coverr.co/
- Mixkit: https://mixkit.co/free-stock-video/

Video recommendations for web and mobile:
- Choose a short, loopable clip (3–8 seconds).
- Use MP4 (H.264) and optionally WebM for better compatibility.
- Keep the file size small (ideally under 5MB for mobile).
- Use a compressed 720p or 1080p clip rather than a very large resolution.
- Keep `playsinline`, `muted`, `autoplay`, `loop`, and `preload="metadata"` in the `<video>` tag.

If you want to avoid video lag on mobile, pick a subtle motion background instead of a highly detailed scene and compress it before uploading.