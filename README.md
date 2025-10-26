# Portal Prototype Preview

This repository contains a Kazbah-inspired static demo page with a scroll-scrubbing background video.

## Instant Live Preview

- **Recommended:** [Launch the live demo via RawGitHack](https://raw.githack.com/smbehm/Portal/main/index.html).
  - RawGitHack serves the latest commit directly from GitHub with the right headers so the
    MP4 background streams correctly.
  - The link becomes active as soon as the repository (and media assets) are public.
- **HTMLPreview fallback:** [Open with htmlpreview.github.io](https://htmlpreview.github.io/?https://github.com/smbehm/Portal/blob/main/index.html).
  - HTMLPreview requires the repository to be public *and* may cache aggressively. If you
    just flipped the repo visibility, wait a few minutes or hard-refresh the page.
  - The service expects a standard `github.com/.../blob/...` URL; avoid using the raw file
    link because it will redirect and produce a blank page inside the preview frame.

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
