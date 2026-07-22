# curio — waitlist landing page

Single-page waitlist landing for **curio**, a swipeable, source-grounded knowledge feed.

Built for Software Product Management, ISB.

## Contents

`index.html` — the entire page. One self-contained file: no build step, no dependencies,
no external requests. Open it in a browser or drop it on any static host.

## Structure

Four sections, in order:

1. **Hero** — wordmark, one-liner, and a "Join the waitlist" CTA that scrolls to the form.
   The right side shows a real Curio card at rest, with its source line and pass/keep affordances.
2. **Benefits** — the three load-bearing product rules: source-grounding, the swipe loop,
   and visible personalization.
3. **Signup** — email capture. Visual only; the form is not wired to a backend.
4. **Footer** — course and team attribution.

## Design notes

| Token | Hex | Role |
| --- | --- | --- |
| Beige | `#F7F4D5` | Page ground (light theme) |
| Dark green | `#0A3323` | Ink (light) / ground (dark) |
| Moss green | `#839958` | Hairlines and small labels |
| Rosy brown | `#D3968C` | Accent — used only on the CTA and one headline word |
| Midnight green | `#105666` | Reserved for the verified / source marker |

Sans for display, serif for card prose — the inversion mirrors the product's own split
between app chrome and sourced knowledge. Responsive from 375px up; light and dark
themes both defined.

## Deploying

Any static host works. For Vercel:

```bash
vercel --prod
```

## Related

- Prototype: https://curio-three-iota.vercel.app/
