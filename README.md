# Website

Personal portfolio for **Landon Coonrod** — static HTML/CSS, deployed on Cloudflare.

## Local preview

From this folder:

```bash
npx serve .
```

## Assets

| Path | Purpose |
|------|---------|
| `assets/Landon-Coonrod-Resume.pdf` | Résumé (linked from nav & contact) |
| `assets/images/landon-headshot.jpg` | Hero photo |
| `assets/images/projects/haptech-capstone.jpg` | Haptech / Franka photo |
| `assets/images/projects/biomechatronics-lab.jpg` | OpenExo / lab photo |
| `assets/images/projects/robot-hand-tracking.svg` | Placeholder thumb — optional `robot-hand-tracking.jpg` if you want a still instead |
| `assets/videos/robot-hand-tracking.mp4` | Demo video for the robot-hand project (add this file; linked from the project card) |
| `assets/images/projects/robot-hand-tracking-poster.jpg` | *(Optional)* Add a poster frame, then set `poster="..."` on the `<video>` in `index.html` |

## Cloudflare Pages / Workers

- **Build command:** *(empty)*  
- **Output:** `/` (repository root)

## Edit content

- Copy: `index.html`
- Layout & theme: `css/styles.css`
