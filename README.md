# Photoyam 🎨

**A free, Photoshop-class image editor that runs entirely in your web browser.**
No account. No upload. No install. Just open a URL and start editing.

### 👉 **[Open Photoyam → photoyam.com](https://photoyam.com)**
### 💬 **[Join the Discussions](https://github.com/sexyzooc/photoyam-community/discussions)** — bugs, ideas, questions, and show-and-tell

![Photoyam editing a colorful portrait entirely in the browser](https://raw.githubusercontent.com/sexyzooc/photoyam-community/main/screenshot.png)

---

## 🔒 Your images never leave your device

This is the part we care about most: **Photoyam has no backend.** There is no
server that receives, processes, or stores your images. Everything — opening a
photo, every brush stroke, every filter, exporting the result — happens **locally
inside your own browser tab**.

- **Nothing is uploaded.** Your photos are read straight from your disk into the
  browser and never sent anywhere.
- **No account, no tracking of your content.** You don't sign in, and there's
  nowhere for your work to be collected.
- **No server round-trips while you edit.** Once the page has loaded, editing
  needs no network at all — filters, brushes, and exports all run on your own
  device. (Even AI background removal runs in your browser.)
- **You keep the files.** Save a `.psy` project or export to PSD/PNG/JPG/etc.
  directly to your device.
- **Even work-in-progress stays local.** As you edit, Photoyam auto-saves your
  session to your browser's own on-device storage (IndexedDB) so an accidental
  tab close, refresh, or crash can be recovered next time you open the app. This
  recovery data **also never leaves your device** — it's read straight from your
  browser, not from any server. It's a single most-recent snapshot that's
  overwritten as you work and removed once you restore or discard it (and it's
  gone entirely if you clear the site's browser data). So if you close without
  exporting, your unsaved image isn't sitting on someone's server — at most it's
  a recovery snapshot in your own browser, under your control.

If privacy or confidentiality matters to you — client work, personal photos,
sensitive documents — Photoyam is safe by design: there's simply no server for
your data to end up on.

---

## ✨ What Photoyam can do

**A real editor, not a toy.** It brings desktop-class editing to the browser:

- **Layers & groups** — blend modes, opacity/fill, layer styles (stroke, shadow,
  glow, overlays), clipping masks, and **nested groups**.
- **Non-destructive adjustments** — levels, curves, hue/saturation, color balance,
  exposure, channel mixer, selective color, photo filter, gradient map,
  black & white, and more, as re-editable adjustment layers.
- **Masks & selections** — layer masks, vector masks, alpha channels; marquee,
  lasso (incl. magnetic), magic wand, color range, refine edge; load a layer's
  transparency as a selection with a click.
- **Retouching & painting** — a real brush engine with dynamics, clone stamp,
  healing / spot healing, dodge / burn / sponge, smudge, patterns.
- **Filters** — blurs, smart sharpen, noise, stylize, liquify, and more, with
  **WebGL2 acceleration** and a graceful CPU fallback. Plus re-editable
  **smart filters**.
- **Text & vectors** — editable text layers, shape layers, and a pen tool with
  editable bezier paths.
- **Transforms** — scale / rotate / skew / distort / perspective / warp, crop &
  straighten, content-aware fill.

**Handy extras built in:**

- **🪄 AI background removal** — cut out the subject in one click. The AI model
  runs **on your device inside the browser** — the image is never uploaded.
- **🎨 Color Tools** — HEX/RGB/HSL/HSV/CMYK converter, palette & scheme generator,
  **WCAG contrast checker**, CSS gradient generator, extract a palette from any
  image, and a searchable CSS named-color chart.
- **🔄 File Converter** — batch-convert images between **PNG / JPG / WebP / BMP /
  TIFF / GIF / PDF / ICO / AVIF** and download them individually or as a single
  ZIP. (Open it from the start screen or `File ▸ Convert…`.)
- **📄 PDF tools** — turn a PDF into images or images into a PDF, and **merge,
  split, reorder, and compress** PDFs — all in the browser, nothing uploaded.
- **🖼️ Broad format support** — open PSD, TIFF, SVG, GIF (animated), HEIC, and
  camera-RAW previews; export PSD, PNG, JPG, WebP, TIFF, PDF, and animated GIF.

Prefer a single-purpose tool? Each of these has its own quick page at
**[photoyam.com/tools](https://photoyam.com/tools)** (convert, resize, crop,
compress, remove background, PSD viewer, PDF tools, and more).

**Made to be pleasant to use:**

- **Command palette** (fuzzy search over every command) and **customizable
  keyboard shortcuts** with a Photoshop preset.
- **7 themes** (Dark, Light, Midnight, Graphite, High Contrast, Nord, System) and
  saveable panel workspaces.
- **5 languages** — English, 한국어, 日本語, 中文, Español.
- **Works on phones & tablets** — a responsive layout with touch gestures
  (pinch-to-zoom, two-finger pan).
- **Autosave & crash recovery** so you don't lose work.
- **Ctrl/Cmd+S saves a real PSD** — with a heads-up before anything is flattened.

---

## 💬 Give feedback here

We'd love to hear from you in the
**[Discussions](https://github.com/sexyzooc/photoyam-community/discussions)** tab:

| Category | Use it for |
|---|---|
| 🐞 **Bugs / Q&A** | Something broke? Tell us what you did, what you expected, your browser + OS, and a screenshot. |
| 💡 **Ideas** | Request a feature — and upvote (👍) the ones you want most. |
| 🙋 **Q&A** | Ask how to do something; answers get marked as solutions. |
| 🖼️ **Show and tell** | Share what you made with Photoyam! |

---

*This repository intentionally contains no source code — it exists only to host
this public community space.*
