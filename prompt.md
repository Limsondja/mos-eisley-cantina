Prompt used:
Complete the existing `<section id="features">` in `index.html` using HTML and Tailwind CSS Play CDN only. Do not modify the existing header, hero, or any other part of the page.

**Requirements**

- Keep the existing section and its accessibility attributes.
- Add a meaningful section title inside the existing `<h2 id="features-title">`.
- Create a responsive grid using exactly `grid-cols-1 md:grid-cols-3 gap-6`.
- Create exactly three `<article>` cards. Each card must contain:
  - An icon inside a box styled with `size-12 rounded-xl bg-violet-500/10 ring-1 ring-violet-400/20`.
  - A heading using `<h3>`.
  - One paragraph containing the exact copy specified below.
- Style each card with `bg-white/[0.03] border border-white/10 backdrop-blur`.
- Add a subtle hover lift using `hover:-translate-y-1` and an appropriate transition.
- Use inline SVG icons or simple text symbols only. Do not add external icon libraries, JavaScript, frameworks, or dependencies.
- Ensure the cards stack in one column on mobile and display in three columns from the `md` breakpoint.
- If you add any interactive links, provide visible keyboard focus styles using `focus-visible`. Do not invent links that are not needed.
- Match the existing dark slate and violet visual theme of the page.

**Exact card content**

1. Heading: `Live music nightly`  
   Paragraph: `Sunset to sunrise, loud enough to drown out a bounty hunter.`

2. Heading: `Smugglers welcome`  
   Paragraph: `No questions asked. Back booths, no records kept.`

3. Heading: `Droids: see house policy`  
   Paragraph: `Limits on the floor. Power-down recommended.`

**Constraints**

- Generate only the contents needed for the existing features section.
- Preserve the surrounding HTML structure.
- Use valid, semantic HTML and Tailwind utility classes.
- Do not add unnecessary elements or classes.


## Corrections after generation

- Removed the redundant `transition-transform` class from the three cards, keeping `transition hover:-translate-y-1 duration-200`.