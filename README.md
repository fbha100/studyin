# StudyIn — Midnight / Guiding Light

An **unofficial concept redesign** of the StudyIn homepage, plus a WhatsApp conversation-UX concept for the mascot, Studi.

> ⚠️ This is a student design concept and is **not affiliated with, endorsed by, or produced for StudyIn**. It is published for portfolio purposes only. All StudyIn brand marks belong to their owner.

**Live demo:** https://YOUR-USERNAME.github.io/studyin-midnight/

---

## The idea

Students navigate the uncertainty of studying abroad in the dark. Studi, a firefly, is the guiding light.

The design rule that holds the whole thing together is **one colour, one meaning**:

| Colour | Meaning | Where it appears |
|---|---|---|
| Amber `#FFE66D` | "look here" | Fireflies, Studi's lantern, trust markers, journey path |
| Lime `#B8FF6A` | "you are here" | Answered fields, active destination, hover states |
| Pink `#F5335B` | "act" | Conversion buttons only — four on the whole page |
| Midnight `#070B1F → #16255A` | the environment | Everything else |

Nothing glows decoratively. If something is glowing, it is telling you where to go.

## Files

| File | What it is |
|---|---|
| `index.html` | The homepage redesign. Single file — no build step, no dependencies. |
| `whatsapp.html` | Studi on WhatsApp: an interactive conversation-UX concept with four playable flows. |

Both are standalone HTML. Open either directly in a browser.

## Built with

Vanilla HTML, CSS and JavaScript. No framework, no bundler. Fonts from Google Fonts (Fraunces + Hanken Grotesk). Studi is hand-built inline SVG — edit the single `<symbol id="studi">` block in `index.html` and all six instances on the page update.

## Accessibility

- Full keyboard navigation with visible focus rings
- `prefers-reduced-motion` honoured throughout — fireflies disable, animations collapse
- Text contrast maintained against the dark environment
- Live regions on the destination preview and the Studi guidance panel

## Known limitations

- **Photography is hotlinked from gostudyin.com.** Fine for a concept, but images will break if that site changes or blocks hotlinking. Replace with your own assets before treating this as a portfolio piece.
- **The StudyIn logo is a recreation** and shown reversed (white) for dark backgrounds. Not a redesign of the mark.
- Course finder and event data are illustrative placeholders.

## Credits

Concept, design and build: **Kushal**
Studi mascot artwork: original character reference redrawn as SVG.
