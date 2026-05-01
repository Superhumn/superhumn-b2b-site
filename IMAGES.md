# Superhumn Site — Image Guide

Drop your photos into the `images/` folder using the exact filenames below.
Recommended formats: JPG or WebP. Keep files under 500KB for fast load times.

The site uses scroll-driven **parallax** — backgrounds drift at a slower rate
than the rest of the page as you scroll, so taller, cinematic compositions
look best.

---

## Parallax images (scroll-driven)

| Filename | Where it appears | Recommended size | Notes |
|---|---|---|---|
| `hero-bg.jpg` | Full-bleed hero background | 2000 × 1400px | Hero food shot — moody, dark works best. The overlay darkens it heavily. Compose with the subject roughly centered or right-of-center; copy sits on the left. |
| `parallax-grilled.jpg` | First parallax divider — "Flavor First" | 2000 × 1200px | Grilled / charred protein close-up. Smoke, char marks, texture. |
| `parallax-tray.jpg` | Second parallax divider — "Built for Volume" | 2000 × 1200px | Institutional tray service, prepped meals at scale, kitchen line. Right-aligned copy, so leave breathing room on the right. |
| `parallax-mushrooms.jpg` | Third parallax divider — "Whole Mushroom Structure" | 2000 × 1200px | Whole / sliced mushrooms, raw ingredient shot. Earthy, clean. |
| `product-feature.jpg` | Product section background | 1400 × 1000px | Close-up beauty shot of the protein. Rings + icon overlay on top. |

Because parallax shifts the image up to ~20% during scroll, **leave roughly
10% headroom on the top and bottom** of each shot so the subject stays in view.

## Channel card images (no parallax)

| Filename | Where it appears | Recommended size | Notes |
|---|---|---|---|
| `channel-healthcare.jpg` | Healthcare channel card | 600 × 400px | Food/meal photo — doesn't need to be medical |
| `channel-education.jpg` | Higher Education channel card | 600 × 400px | Campus dining or food bowl |
| `channel-corporate.jpg` | Corporate Dining channel card | 600 × 400px | Upscale plated dish or catering spread |
| `channel-k12.jpg` | K–12 channel card | 600 × 400px | Colorful healthy food, approachable |

---

## Already included

| Filename | Notes |
|---|---|
| `logo.png` | Superhumn white logotype — already in place |

---

## Tips

- All parallax images have dark gradient overlays applied in CSS, so bright
  food photography will still read against the white text.
- Parallax is automatically disabled on mobile (≤720px) and for users with
  `prefers-reduced-motion` set — images fall back to a static crop.
- Square crops work fine — the CSS handles sizing.
- If a channel card has no image, it falls back to the dark background color
  gracefully.
- To swap the logo: replace `logo.png` with your new file (keep the same
  filename).
