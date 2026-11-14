# AGROBoT — GitHub Pages Website

A premium dark-themed, responsive one-page website for the AGROBoT student innovation project.

## Publish with GitHub Pages

1. Create a GitHub repository named `agrobot` (or another name you prefer).
2. Upload `index.html` to the repository's root folder.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then click **Save**.
6. Wait a minute or two. GitHub will show the published website URL in the Pages section.

Typical URL: `https://YOUR-USERNAME.github.io/agrobot/`

## Add your own prototype media

The current page includes a clearly marked media placeholder. To add a photo:

1. Create a folder named `assets` in the repository.
2. Upload your photo as `prototype.jpg`.
3. In `index.html`, find the `media-placeholder` block and replace it with:

```html
<img src="assets/prototype.jpg" alt="AGROBoT physical prototype"
     style="width:100%;height:100%;object-fit:cover;border-radius:24px;">
```

For a video uploaded to YouTube, replace the placeholder with an embedded YouTube iframe using your own video ID.

## Accuracy notes

- Current prototype: mobile phone control, live camera feed to laptop, ultrasonic obstacle detection, liquid spraying mechanism, rechargeable battery operation.
- Four main agricultural features: spraying (demonstrated), seed planting (future), soil preparation (future), smart harvesting (future).
- The Blender 3D model is a proposed design, not the physical prototype.
- The website does not claim that AGROBoT is fully autonomous.
