

# Anti-AI Website Design

## Purpose

Create websites that feel deliberately designed by a thoughtful human
designer---not assembled from a generic AI landing-page template.

The goal is **not** to ban every modern design technique. The goal is to
avoid predictable combinations, decorative excess, fake credibility, and
visual decisions that are unrelated to the product.

Apply this skill to landing pages, SaaS products, dashboards,
portfolios, business websites, web apps, and responsive interfaces.

## Core principles

1.  **Design for the actual product.** Understand the audience, task,
    content, brand, and business context before choosing a visual
    direction.
2.  **Prefer restraint over decoration.** Every visual element must
    serve hierarchy, usability, identity, or comprehension.
3.  **Make deliberate choices.** Typography, color, spacing, layout,
    imagery, and motion should form one coherent system.
4.  **Use real content.** Never invent customers, testimonials, ratings,
    statistics, awards, certifications, partner logos, case studies, or
    product capabilities.
5.  **Prioritize usability.** Responsive behavior, accessibility,
    readable contrast, clear states, and useful feedback matter more
    than visual tricks.
6.  **Avoid template convergence.** Do not default to the same
    fashionable SaaS layout, palette, font stack, or component
    arrangement on every project.
7.  **Do not overcorrect.** A listed pattern may be appropriate when the
    product, brand, user request, or information architecture genuinely
    calls for it. Use it intentionally, not automatically.

## Anti-patterns to avoid by default

Treat these as warning signs, not absolute prohibitions. Do not add them
merely because they are common in generated website concepts.

### Visual style and decoration

-   Harsh, arbitrary, or excessive gradients.
-   Pure white backgrounds everywhere when a warmer, darker, textured,
    or brand-specific surface would work better.
-   Rainbow color schemes or too many unrelated accent colors.
-   Purple-and-black as an automatic default.
-   Neon colors without a clear brand or functional reason.
-   Generic pastel palettes chosen without regard to the product.
-   Glassmorphism / "liquid glass" used as a fashionable overlay rather
    than for a clear layering purpose.
-   Glowing spheres, floating blobs, dotted backgrounds, sparkle icons,
    and other generic AI-tech decorations.
-   Shadows under nearly every element. Use elevation sparingly and
    consistently.
-   A colored vertical stripe on the left of cards or sections when it
    has no semantic meaning.
-   Excessively soft, identical rounded corners on every component.
-   Bento grids used automatically, even when a simpler editorial or
    structured layout would communicate better.

### Components and layout clichés

-   Three cards in a row as the default section layout.
-   Three pricing tiers by habit rather than because the business model
    needs them.
-   Terminal windows included only to make a product look technical.
-   Checkmark lists repeated as generic filler.
-   Emoji used as a substitute for a coherent icon or illustration
    system.
-   Lucide icons (or any icon library) used indiscriminately. Use icons
    only when they improve recognition or navigation; keep a consistent
    visual language.
-   Animated arrows and hover effects on nearly every element.
-   Skeleton loaders omitted where loading takes time, or added where
    they provide no value. Implement appropriate loading, empty, error,
    and success states.
-   A live demo omitted when users need to evaluate an interactive
    product. Provide a real demo, preview, sample workflow, or honest
    explanation of what can be tried.
-   Responsive layouts that simply stack desktop cards without
    reconsidering hierarchy and interaction on mobile.

### Typography and writing

-   Defaulting automatically to Inter, Geist, or Space Grotesk without
    considering the brand and content.
-   Overusing long dashes as a stylistic crutch.
-   Repeating constructions such as "This is not X, this is Y".
-   Generic AI marketing language, vague claims, repetitive slogans, and
    inflated promises.
-   Headings that sound polished but do not tell users what the product
    actually does.

Choose typography for legibility, language coverage, personality, and
available weights. Check that the chosen font supports every required
language and character set.

### Trust and product integrity

-   Fabricated testimonials, reviews, customer logos, user counts,
    ratings, statistics, or success stories. If real material is
    unavailable, omit the section or label clearly marked sample content
    in a private prototype.
-   Fake terminal output, fake dashboards, fake activity feeds, and fake
    integrations presented as real.
-   Missing privacy policy, terms of service, or other required legal
    information. Determine which pages and disclosures are appropriate
    for the product, jurisdiction, and data practices. Do not generate
    legal claims or pretend that boilerplate guarantees compliance.
-   Unclear ownership of data, missing consent, or misleading
    privacy/security claims.
-   Decorative buttons and links that do nothing.
-   A "live" label for static or mocked content.

## Required design workflow

### 1. Understand before styling

Inspect the existing project and identify:

-   What the product does and who uses it.
-   The primary user task and most important conversion or action.
-   Required pages, sections, and content.
-   Existing brand assets, design constraints, and technical stack.
-   Languages, accessibility needs, and responsive breakpoints.
-   Which claims and data are verified versus placeholders.

If key information is missing, make conservative assumptions and state
them. Ask only for information that materially changes the design.

### 2. Establish a visual direction

Before implementing components, define a compact design direction:

-   A product-appropriate color palette with a restrained number of
    roles.
-   A typography system selected for the brand, readability, and
    language support.
-   A spacing scale and a small set of purposeful radii.
-   A clear layout/grid system suited to the content.
-   A consistent approach to photography, illustration, icons, borders,
    and elevation.
-   Motion principles, including reduced-motion behavior.

Do not choose a visual direction just because it is currently
fashionable. Make it recognizable and appropriate to this specific
product.

### 3. Build hierarchy from content

-   Put the most important information first.
-   Use layouts that fit the content rather than forcing content into a
    repeated card pattern.
-   Vary section composition only when it improves scanning or
    understanding.
-   Use whitespace intentionally.
-   Avoid decorative sections that add no information or functionality.
-   Prefer real product screenshots, real photography, meaningful
    diagrams, or carefully art-directed visuals over generic abstract
    decoration.

### 4. Implement real interface states

For every interactive feature, consider:

-   Default state.
-   Hover and focus states where relevant.
-   Active/selected state.
-   Disabled state.
-   Loading state when an operation takes time.
-   Empty state.
-   Error state.
-   Success/confirmation state.

Use motion sparingly. It should explain a state change, guide attention,
or make an interaction clearer---not animate every element on hover.
Respect `prefers-reduced-motion`.

### 5. Protect credibility

-   Never fabricate evidence or present mock data as real.
-   Clearly label demo/sample data.
-   Do not claim security, privacy, compliance, performance, or
    integrations that have not been implemented and verified.
-   Include appropriate legal and privacy links based on the actual
    product and its data practices.
-   Ensure all visible actions work and all links lead somewhere
    meaningful.

### 6. Review the result

Before declaring the work complete, inspect the actual running
website---not just the source code.

Check:

-   Desktop, tablet, and mobile layouts.
-   Visual hierarchy and consistency across pages.
-   Typography, contrast, and language rendering.
-   Navigation, forms, buttons, and links.
-   Loading, empty, and error states.
-   Keyboard navigation and visible focus.
-   Reduced-motion behavior.
-   Console errors and broken assets.
-   Whether any decorative element can be removed without losing
    meaning.

## Final anti-cliché audit

Before delivery, review the 30 warning signs below. Remove each one that
is present without a clear reason:

1.  Harsh gradients.
2.  Lucide icons used by default or excessively.
3.  Pure-white backgrounds everywhere.
4.  Rainbow color schemes.
5.  Shadows under everything.
6.  Three cards in every row or section.
7.  Decorative emoji.
8.  Unnecessary liquid-glass effects.
9.  Excessive long dashes in copy.
10. Inter, Geist, or Space Grotesk chosen automatically.
11. Meaningless colored stripe on the left.
12. Invented reviews or testimonials.
13. Automatic bento grids.
14. Decorative terminal windows.
15. Repetitive "not X, but Y" copy.
16. Generic checkmark lists.
17. Three pricing plans without a business reason.
18. No meaningful live demo or honest product preview where one is
    needed.
19. Identical soft rounded corners everywhere.
20. Automatic purple-and-black palette.
21. Missing appropriate loading skeletons or other loading feedback.
22. Decorative glowing spheres.
23. Generic dotted backgrounds.
24. Unnecessary sparkle icons.
25. Animated arrows without functional purpose.
26. Missing appropriate terms of service.
27. Missing appropriate privacy policy.
28. Hover animation on every element.
29. Unjustified neon colors.
30. Generic pastel colors.

A pattern may remain if it has a clear, product-specific reason. Be able
to explain that reason.

## Completion report

When finishing a design or redesign, briefly report:

-   The visual direction and why it fits the product.
-   The key UX and responsive decisions.
-   Which real assets/data were used and which placeholders remain.
-   Any unfinished states, legal pages, or functionality.
-   The anti-cliché issues deliberately avoided.
-   Any exceptions from this skill and why they were justified.

Do not claim a check was completed unless it was actually performed.
