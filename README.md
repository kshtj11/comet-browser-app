# Comet Browser App

A single-file, touch-first **mid-fidelity prototype** of a minimal mobile web browser for a 540 × 620 Linux handheld device (the "Comet") with a keyboard extension.

**[▶ Live demo](https://kshtj11.github.io/comet-browser-app/)**

## Features

- **540 × 620 fixed device frame**, centered, no scrollbars, touch-first (Pointer Events only).
- **Multi-tab** browsing with a 2×2 tab switcher (scrollable), live tab count, per-tab back/forward history.
- **Per-tab page theme** — opens with two tabs of the same mock page, one light, one dark.
- **Bottom bar** — address pill (tap to type a URL/query), new tab, tabs switcher, and a menu that opens from the bottom-right.
- **Settings menu** — New tab, History, Bookmarks, Downloads, Settings, Accessibility, plus a quick-action row (back / forward / reload / bookmark).
- **Accessibility** — text-size control (small / default / large), high-contrast and larger-tap-target toggles. All touch targets ≥ 44 px.
- **Scroll-to-hide bottom bar** — scrolling down hides the bar, the slightest scroll up brings it back.
- **Android-style edge back gesture** — swipe inward from the left or right edge; a Material-style bubble with a back arrow follows your finger and commits past ~35% progress.
- Mouse drag-to-scroll for desktop preview; neutral grayscale UI.

## Run locally

It's one file — just open `index.html` in a browser.

---

Built as a prototype for Mecha Systems.
