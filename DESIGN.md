## Lucius Personal Site Design System

### Intent

Build a GitHub Pages profile site for Lucius (張育榮) that feels like an academic homepage, but with stronger personality and a cleaner editorial rhythm than the reference page.

The site should communicate three things fast:

1. He is grounded in engineering and research.
2. His work sits at the intersection of VLMs, autonomous navigation, UAV systems, and AI safety.
3. He is still early in his path, but already building toward embodied, deployable intelligent systems.

### Content Guardrails

- Do not mention professor names.
- Do not include phone numbers.
- Keep the tone personal and technical, not like an admissions statement.
- Use current identity first: Lucius / 張育榮.
- Present the work as an evolving research trajectory rather than a finished CV dump.

### Visual Direction

Academic editorial + warm engineering lab.

- Background: parchment white with layered radial gradients and faint grid lines.
- Accent: NCKU-inspired burgundy with brass and graphite support colors.
- Composition: one-page, anchored navigation, alternating dense and breathable sections.
- Mood: confident, quiet, precise.

### Typography

- Display / headings: `Noto Serif TC`
- UI labels / English accents: `Sora`
- Body copy: `Noto Sans TC`

The serif display should make the page feel authored, not templated. Sans should keep technical details crisp.

### Color Palette

- `--bg`: `#f6f1e8`
- `--paper`: `rgba(255, 252, 247, 0.76)`
- `--ink`: `#161514`
- `--muted`: `#5c5852`
- `--accent`: `#8b1e2d`
- `--accent-strong`: `#65111d`
- `--gold`: `#b98a45`
- `--line`: `rgba(22, 21, 20, 0.12)`
- `--shadow`: `0 24px 60px rgba(69, 42, 24, 0.14)`

### Layout Rules

- Sticky top navigation with section anchors.
- Hero split layout: narrative on the left, portrait on the right.
- Use chips and stat blocks to front-load identity.
- Major work should appear as large project cards, not a bullet list.
- Education should read as a timeline with institutional marks.
- End with a short vision section and simple external links.

### Motion

- Fade-up reveal on section entry.
- Gentle floating motion on hero accents.
- Hover lifts on cards and buttons.
- Keep motion short and calm.

### Responsive Rules

- Collapse hero to single column below tablet widths.
- Preserve image prominence on mobile.
- Keep line length short for Chinese text.
- Nav may wrap or scroll horizontally, but anchors must remain usable.

### Asset Use

- Use the provided portrait as the primary identity image.
- Use downloaded NCKU / EE marks as supporting education icons.
- Keep logos secondary. Lucius should remain the visual focus.
