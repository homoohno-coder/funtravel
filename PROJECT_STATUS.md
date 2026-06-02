# Project Status

## Current State

- Static single-page storefront for Fun Travel by Elena.
- Homepage, product listings, lightbox, gallery, ordering helpers, and inline CSS live in `index.html`.
- Product images and the Gemini hero video live in `images/`.

## Latest Update

- Implemented `images/gemini_generated_video_5AF01A89.MP4` as the homepage landing hero video.
- The hero video autoplays, is muted, loops, uses `playsinline`, has no controls, and sits behind the hero text and buttons.
- The hero uses the existing jewelry image as a CSS background fallback if video playback fails or motion is paused.
- Reduced-motion users see the fallback image instead of autoplaying video.
- A small `Pause Motion` control allows visitors to pause or resume the hero video.

## Notes

- No product data, pricing, product descriptions, or product image behavior were intentionally changed.
- No external build tooling is present in the repository; Netlify can deploy this as a static site.
