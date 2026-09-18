# Ahim Notnim — Premium Charity Web Skill

## Purpose
This repository is the official website of עמותת אחים נותנים. Every future change must preserve one coherent premium design system. The site serves a Jewish religious/Haredi audience and must feel dignified, trustworthy, warm, modern and established.

## Non-negotiable workflow
1. Read the relevant existing code before editing.
2. Preserve content, contact details, assets, links and functionality not explicitly requested to change.
3. Reuse the tokens and components below. Do not invent one-off visual systems.
4. Design mobile-first and RTL-first.
5. Check 360, 390, 430, 768, 1024 and 1440px.
6. Check overflow, layout shift, keyboard focus, contrast, image crop and reduced-motion.
7. Premium does not mean noisy: use depth, layering, restrained 3D surfaces, refined gradients and shadows. Avoid gimmicky flashing and random effects.

## Brand character
Keywords: חסד, כבוד, אמון, יהדות, שותפות, איכות.
Visual direction: premium modern charity; warm ivory surfaces; deep turquoise; restrained antique gold; charcoal text; subtle glass/3D depth.

## Color tokens
--brand-900: #063F42
--brand-800: #07585B
--brand-700: #087A7C
--brand-500: #18A5A2
--gold-500: #C7A253
--gold-300: #E5CC8A
--ivory-50: #FCFAF5
--ivory-100: #F5F0E5
--ink-900: #142B2C
--ink-600: #607071
--white: #FFFFFF

Do not introduce a fifth major brand color without an explicit reason.

## Typography
Display/H1: Frank Ruhl Libre 800–900; clamp(2.7rem, 6vw, 5.6rem); line-height .98–1.08.
Section headings: Frank Ruhl Libre 700–800; clamp(2rem, 4vw, 3.3rem).
UI/subheads/body: Heebo.
Body: 16–18px, line-height 1.7–1.85.
Use at most these two font families unless explicitly approved.

## Spacing and layout
8px base rhythm: 8/16/24/32/48/64/80/96.
Container: min(1200px, 92vw).
Sections: 72–112px vertical depending on viewport.
Cards: 20–28px radius.
Large media/hero surfaces: 28–38px radius.

## Premium depth
Use 3D depth through layered borders, soft shadows, highlights and restrained gradients.
Standard card shadow: 0 18px 50px rgba(6,63,66,.10).
Premium surface may use an inset white highlight plus one external shadow.
Hover movement: max 4–6px translateY.
No excessive neon glow, continuous bouncing, or multiple competing animations.

## Information architecture
Home = fast understanding + trust + path to partnership.
About = deeper story, mission, values and operating principles.
Activity = detailed structured list of actual programs.
Gallery = real project imagery.
Contact = keep official email and website.
Partnership = clear CTA and donation area.

## Header
Desktop: navigation split around a clearly visible centered logo. Logo is prominent but never overlaps links.
Primary navigation: דף הבית / על העמותה / הפעילות שלנו.
Secondary: סיפורי חסד / גלריה / צור קשר.
Desktop may show a "לשותפות" CTA.
Mobile: compact centered logo + menu; no floating partnership CTA.

## Home hero
Logo remains visually important in the header/top composition.
Hero uses a balanced RTL composition:
right: eyebrow, strong headline, concise explanation, primary "לשותפות" CTA, secondary activity CTA.
left: premium editorial collage using existing real activity photos.
Use depth: overlapping photo cards, gold hairline borders, soft shadows, subtle decorative turquoise geometry.
Never obscure the copy with imagery.

## Components
Use shared patterns for Button, SectionHeader, ActivityCard, StoryCard, ImpactStep, GalleryCard, ContactCard, CTA and Footer.
Do not create visually unrelated cards per section.

## Floating actions
Desktop (>900px): floating "לשותפות" button is allowed.
Mobile (<=900px): hide floating partnership button. Show only the floating WhatsApp icon.
WhatsApp must remain visually available. Until an official number exists, it may route to Contact rather than inventing a phone number.

## Content integrity
Never invent impact numbers, testimonials, beneficiaries or regulatory claims.
Keep achimnotnim@gmail.com and www.ahim-notnim.com unless explicitly changed.
Use existing repository images and logo unless explicitly asked to replace them.

## Motion
Reveal transitions: 350–650ms, opacity + 8–18px translate.
Decorative background motion may be slow and subtle.
Respect prefers-reduced-motion.
Do not smooth-jack normal page scrolling.

## Responsive rules
Avoid absolute positioning for primary layout.
Use Grid/Flex/clamp/minmax.
Mobile content must not wait for desktop styles to settle; no visible layout jump.
Touch targets >=44px.
No horizontal scrolling.

## Accessibility/performance
Semantic HTML, visible focus, useful alt text, aria-labels where needed.
Lazy-load below-fold images.
Do not load unnecessary libraries.
Prefer CSS/SVG over heavy JS effects.
