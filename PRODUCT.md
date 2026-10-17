# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack
Astro (existing scaffold in this repo, static output).

## Users
Any Mac user who copies things all day (text, links, code, screenshots) and loses them. Not limited to developers, though secrets handling resonates with people who copy keys and tokens.

## Product Purpose
ClipMac is a macOS menu-bar clipboard manager and screenshot tool. It remembers text and images you copy for 24 hours, hides secrets automatically, and lets you capture, beautify and share screenshots. Success for this site: a visitor understands it in seconds and downloads it.

## Positioning
Everything stays on the Mac: no network requests, on-device OCR hides secrets even inside screenshots, and clipboard, screenshot capture and an Xnapper-style editor live in one small free app.

## Operating Context
Menu-bar app, closing the window keeps it running. Global shortcuts per capture mode. Keyboard-driven list (arrows, Enter, Cmd+F, Cmd+D, Cmd+E). Light/dark with system accent color.

## Capabilities and Constraints
- Clipboard history for text and images, auto-deleted after 24h; favorites never expire. Search, filter, sort.
- Secrets (API keys, tokens, passwords, JWTs, private keys, credentials in URLs) hidden in text and, via Vision OCR, in screenshots. Best effort, not a guarantee.
- Screenshots: selection, window, full screen, native Retina PNG, delay, cursor, shadow, global shortcuts.
- Image editor: backgrounds, padding, radius, shadow, zoom/pan, aspect ratio; Save Copy or Overwrite.
- Drag images into Finder/Mail/Slack/Figma; Copy as File; export PNG/JPEG.
- Code detection with syntax highlighting; Format via Prettier (JS, TS, JSON, CSS, SCSS, Less, HTML, Markdown, YAML) and rustfmt.
- macOS only, v1.0.1, MIT licensed, built with Tauri 2. Not eligible for Mac App Store. Builds are ad-hoc signed, not notarized: Gatekeeper warning (right-click, Open, or `xattr -cr ClipMac.app`); Screen Recording permission must be re-granted after each update. History is stored unencrypted locally.
- Does not detect credit card numbers, emails or phone numbers.

## Brand Commitments
Name: ClipMac. Existing app icon in the app repo (src-tauri/icons). Free and open source (user-approved claim). Primary CTA: download from GitHub Releases (github.com/coros-hq/clipmac).

## Evidence on Hand
README facts only. No testimonials, user counts, benchmarks or pricing exist; do not fabricate. App screenshots do not exist as files; any product imagery on the page is authored and must be labeled illustrative.

## Product Principles
1. Private by construction: say what stays on the Mac, and be honest about the limits of secret detection.
2. Small and always there: a menu-bar tool, not a workspace.
3. Show the real behavior (hiding, 24h expiry, shortcuts), not adjectives.
4. Free and open source, plainly stated.
