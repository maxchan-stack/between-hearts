# Typography and layout V6.1

- UI sans, card serif, system fallback. No remote font dependency.
- CSS viewport 320–374 / 375–413 / 414–599 / >=600: quote 24 / 26 / 28 / 32 px; question 22 / 24 / 26 / 28; action 18 / 19 / 20 / 22. Values at 16px browser root; rem respects preferences.
- Body 16, section title 22, category 14, context 16, small text 13, minimum touch height 44 CSS px.
- Natural wrapping, scroll when necessary, no clipping or per-card fit-to-width.
- Projection is separate, print uses physical units.
- Acceptance: 320, 375, 390, 414, 430, 600, 768 widths; landscape, large text, iOS VoiceOver, Android TalkBack, airplane mode after cache install.


V6.2 cover: organic blobs using each dimension color; fixed two-column grid; pressed state uses check and inset outline; 44 CSS px minimum target. Intro mantra replaces large instruction heading.


V6.3 cover: three zones, bottom actions in normal flow, minimum separation 28px (24px short height), 72% primary CTA, three quiet secondary actions, collapsible system details. Organic silhouette masks; light warm background. No fixed footer.