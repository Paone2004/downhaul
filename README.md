# Downhaul

A browser extension that finds video and audio playing on a web page and lets you download it.

Open the panel, play the media you want on the page, and it shows up in the list ready to save. Works on plain video/audio files, HLS and DASH streams, and has extra handling for a bunch of specific sites (YouTube, Vimeo, Facebook, VK, Bilibili, Kick, and others).

## Install

Not on the Chrome Web Store, so you install it as an unpacked extension:

1. Download or clone this repo.
2. Open `chrome://extensions` (or `edge://extensions` on Edge).
3. Turn on **Developer mode** (top right).
4. Click **Load unpacked** and select the folder you downloaded.

The Downhaul icon shows up in your toolbar.

## Use

1. Click the toolbar icon. By default it opens as a popup, which closes if you click on the page — annoying if you need to click play first. Go to **Settings → Panel position → Show in sidebar** to dock it instead; the sidebar stays open no matter what you click on the page.
2. Browse to a page with video or audio and start playing it.
3. Detected media shows up in the panel. Pick a format if there's a choice, then hit download.

## Notes

- No account, no premium tier, nothing to sign up for.
- Some sites use DRM (Netflix and most paid streaming) — nothing can download that, browser or otherwise.
- If a site plays media in a way the extension doesn't catch, it's likely a site-specific quirk that needs its own fix rather than a bug in the general detector.
