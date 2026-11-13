# Add your videos here

Upload your `.mp4` files into this folder. To show a video on the site, open the repository's `index.html`, copy the example video card, uncomment it, then replace `my-video.mp4` with your exact filename and change the title.

For example, if you upload `videos/family-trip.mp4`, use:

```html
<article>
  <video controls playsinline preload="metadata">
    <source src="videos/family-trip.mp4" type="video/mp4">
    Your browser does not support HTML video.
  </video>
  <h2>Family Trip</h2>
</article>
```

Commit the HTML change and the video file. The page uses native video controls and adapts to mobile screens.
