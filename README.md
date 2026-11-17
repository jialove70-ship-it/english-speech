# From Operating Room to Publication

- GitHub Pages：[https://jialove70-ship-it.github.io/english-speech/](https://jialove70-ship-it.github.io/english-speech/)

A buildless, single-page English presentation adapted from the supplied 13-slide PowerPoint by Chih-Chien Wu, MD (SCRS Taiwan Annual Meeting / ICRSF 2026).

Open `index.html` directly, or serve this directory with a static HTTP server. All styling, speaker notes, and progressive enhancement JavaScript are embedded. The original supplied cover image is served from `assets/cover.png` and must be kept beside the HTML in that relative path. There are no third-party scripts, fonts, or runtime dependencies. The preferred font is Microsoft YaHei, using local fallback fonts on devices where it is unavailable.

The cover includes a **Jump to chapter** selector for all 13 chapters. Choose a chapter, then press **Go →** to navigate. Selecting an option alone does not move the page. Without JavaScript, the cover links to the full chapter table of contents.

## GitHub Pages

Publish this directory as the repository root (or place it in `/docs` and select that folder). In Settings → Pages, select **Deploy from a branch**, the deployment branch, and **/(root)** (or `/docs`, matching the chosen layout). The included `.nojekyll` keeps the site buildless. Keep `assets/cover.png` alongside `index.html` at the indicated relative path when publishing or copying the site.

The source presentation’s operative figure citation is retained; the operative image itself is omitted.
