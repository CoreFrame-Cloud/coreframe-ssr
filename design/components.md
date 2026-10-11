# CoreFrame Design System — Component Library (v1.0)
## Buttons
- Primary (filled): ink bg, cream text, gold hover ring, pill radius, 12px padding vertical 28px horizontal.
- Secondary (outline): ink border 1.5px, ink text, gold text hover, pill radius.
- Tertiary (text only): ink text, underline on hover, gold underline.

## Cards
- Feature card: cream bg, ink border 1px, 2rem radius, 2rem padding. Image top 16:9, body: label + h3 + body text + arrow link.
- Case card: ink bg, cream text, no border, 2rem radius. Image 4:3, body: client tag, title, result stat (gold), link.

## Forms
- Input: 1px ink border, cream bg on dark / cloud bg on light. Focus: gold border + glow shadow. Label above, helper below.
- Textarea: same; 120px min-height.
- Checkbox: ink square with gold check, label to right.

## Navigation
- Top nav: fixed, ink bg, 72px height. Logo left (Instrument Serif 22px), links center, CTA right.
- Mobile: hamburger → slide overlay with 48px links, gold divider lines.

## Footer
- Dark ink bg. 3 columns: brand (logo + tagline), links (Services/Case Studies/About), newsletter input + gold submit.
- Legal row below: copyright, privacy, terms.

## Motion guidelines
- Page load: content fades up 600ms ease-out with 100ms stagger per block.
- Card hover: scale 1.02, lift shadow 8px, 300ms ease-out.
- Buttons: scale 1.01 on press, gold glow ring on hover.
- Scroll reveal: opacity 0→1 + translateY(12px→0), 500ms ease-out, triggered at 0.15 visibility.
