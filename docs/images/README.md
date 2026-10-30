# Darknetzz artwork

Dark flat-vector branding for README / GitLab avatar / social share.

**Palette:** accent `#f97316` · secondary `#fdba74` · canvas `#1a0f08`

## Layouts

### Adb-keeper style (root)

| File | Size |
|------|------|
| `logo-{solid,gradient,transparent}.png` | 512×512 |
| `banner-{solid,gradient,transparent}.png` | 1280×640 |

### Code style

| Path | Contents |
|------|----------|
| `repo/` | Transparent 1×1 / 16×9 (+ label) |
| `bg-solid/repo/` | Solid dark canvas variants |
| `bg-gradient/repo/` | Gradient + glow variants |
| `og/Darknetzz.png` | Open Graph 1280×640 |
| `svg-src/` | SVG sources |
| `ai/` | Optional AI atmospheric banner |
| `profile-banner.png` | Profile README header (source: `svg-src/profile-banner.svg`, rendered 2× via headless Chrome) |

## Regenerate

```bash
python batch_generate.py --only Darknetzz
```
