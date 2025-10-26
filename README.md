# Portal Prototype Preview

This repository contains a Kazbah-inspired static demo page with a scroll-scrubbing background video.

## Instant Live Preview

- [Open the demo page now](https://htmlpreview.github.io/?https://github.com/smbehm/Portal/blob/main/index.html)
  (powered by the community `htmlpreview.github.io` service).

## Live Preview Options

- **Local quick preview**: Run a lightweight web server from the project root and open the page in your browser.
  ```bash
  python -m http.server 8000
  ```
  Then visit [http://localhost:8000/index.html](http://localhost:8000/index.html).
- **GitHub Pages**: Push this repository to GitHub and enable GitHub Pages for the branch. The `index.html` file will serve as the landing page.

## Screenshot

![Scroll scrubbing preview](browser:/invocations/wwtpcfxr/artifacts/artifacts/scroll-preview.png)

## Assets

- Background video: `scrolltest.mp4` (hosted on GitHub raw CDN in the demo page)

## Notes

- Ensure the remote video link remains publicly accessible for the scroll-scrubbing effect to work.
- The demo intentionally pauses the video so that scroll position fully controls playback.
