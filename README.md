# yerbylabs.com

GitHub Pages site for Yerby Labs and IronBeak.

---

## ⚠️ IMPORTANT: Which files to edit

| URL | File to edit | Notes |
|-----|-------------|-------|
| `yerbylabs.com/` | `index.html` | Main Yerby Labs homepage |
| `yerbylabs.com/ironbeak.html` | **`ironbeak.html` (root)** | IronBeak landing page — **edit this one** |
| `yerbylabs.com/ironbeak/` | `ironbeak/index.html` | ⚠️ Legacy duplicate — DO NOT edit |
| `yerbylabs.com/ironbeak/privacy` | `ironbeak/privacy.html` | Privacy policy |
| `yerbylabs.com/ironbeak/terms` | `ironbeak/terms.html` | Terms of service |

### The trap to avoid

There are **two IronBeak HTML files**:
- `ironbeak.html` — served at `yerbylabs.com/ironbeak.html` — **this is the live page**
- `ironbeak/index.html` — served at `yerbylabs.com/ironbeak/` — legacy, not linked from anywhere

**Always edit `ironbeak.html` at the root.** Edits to `ironbeak/index.html` will not appear on the live site at `yerbylabs.com/ironbeak.html`.

---

## Deployment

This repo is served via GitHub Pages from the `main` branch root. Changes pushed to `main` go live within a few minutes.

---

## Asset locations

App screenshots used in the carousel are embedded as relative paths — they live in the same repo. If you add new screenshots, place them in the root or a clearly named subfolder and update the `<img>` src paths in `ironbeak.html`.
