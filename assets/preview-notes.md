# Stage 1 asset notes

The profile uses repository-hosted SVGs so its visual identity remains stable and does not depend on a third-party image service.

## Asset map

| File | Purpose |
| --- | --- |
| `hero-banner.svg` | Primary identity banner: name, role, location/opportunity signal, and ERP-themed system graphic. |
| `profile-overview.svg` | Compact recruiter scan of experience, Odoo range, delivery scope, and domain breadth. |
| `tech-visual.svg` | Connected stack map centered on Odoo ERP, with the core engineering and operations technologies. |
| `workflow-or-domains.svg` | Visual domain map for manufacturing, retail, real estate, healthcare, education, and restaurant/POS work. |
| `contact-strip.svg` | Closing contact panel linked to email from the README. The individual contact badges above it provide direct links. |
| `section-divider.svg` | Reusable transition between major README sections. |

## WhatsApp link

The WhatsApp badge in `README.md` is configured with the following public link:

```text
https://wa.me/966547894198
```

The number uses digits only after `wa.me`, with no leading `+`, spaces, or dashes. The matching display label in `contact-strip.svg` is `WhatsApp Business · Direct message`.

## Add future screenshots or badges

- Put curated screenshots in a future `assets/showcase/` directory. Prefer compressed PNG or WebP images without client data, credentials, personal data, or confidential business logic.
- Add a small showcase block below **Current focus** when public project material exists. Link each screenshot to its real repository or case summary; do not add empty project cards.
- The selective contact badges live directly below the hero in `README.md`. Keep additions limited and use the existing dark badge color (`0B1220`) for visual consistency.
- Update the profile overview only when the claims remain current and verifiable. Avoid repository counts, client counts, star counts, or performance claims without public evidence.

## Editing guidance

All SVG assets use system fonts, standard vector primitives, gradients, and SMIL animation. They contain no JavaScript, embedded raster images, external font requests, or tracking resources. Preserve each SVG's `viewBox` when resizing so it remains responsive in GitHub's README renderer.
