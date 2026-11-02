# Product brief: Rave Planner

## Goal
A minimalist personal website, hosted online at a link, to organize music festivals I want to attend. Version one is a skeleton; live integrations come later.

## Version one scope

### Page 1: Festival list
- Two sections: **Local (NYC)** and **Travel**.
- Local section: empty for now. Show a simple empty state.
- Travel section: contains only **EDC Las Vegas 2027**.
- Each festival is a clickable card/row showing name, location, and dates.

### Page 2: Festival detail (EDC Las Vegas 2027)
- Name, venue, city, and dates (see data below).
- **Lineup:** TBD (not yet released).
- **Set times:** TBD (not yet released).
- Page layout must handle lineup and set times being empty now and filled in later.
- Back link to the festival list.

### EDC Las Vegas 2027 data (researched Oct 28, 2026)
- Venue: Las Vegas Motor Speedway, Las Vegas, NV.
- 2027 is the first year with two festival weekends:
  - **EDC Dusk:** May 14-16, 2027
  - **EDC Dawn:** May 21-23, 2027
- A wider "Dusk Till Dawn" program runs across Las Vegas May 13-24, 2027.
- Reported: lineup is the same both weekends.
- Which weekend I'm attending: **EDC Dawn (Weekend 2), May 21-23, 2027**. Show both weekends on the page, but highlight Dawn as mine.
- Official site: lasvegas.electricdaisycarnival.com. Verify against it before treating any detail as final.

## Design direction
References: Mobbin and Cofolios (screenshots I shared). Dribbble shots (Travel App Landing Page, Airportr redesign, Blockio) not yet reviewed.

**What I like from the references**
- Mobbin: very large, bold, centered headlines; lots of white space; short supporting text; clean top nav; simple buttons; grids of big visual cards with minimal labels.
- Cofolios: floating top nav bar; flat pastel color blocks behind big images; two-column card grid; one clear accent button; bold name/title with a quiet gray subtitle.

**My changes to those references**
- More color than they have, but still pastel and flat.
- Less round: small corner radius (about 6-8px) on cards and buttons. No pill shapes, no heavily rounded cards.

**Rules**
- Big graphics, little text. No blocky paragraphs. Every screen should be quick to scan and functional first.
- Colors (chosen palette: "Garden"): page background #FAF9F4, text #20241F, gray for secondary text. Pastel accents: sage #D3E3CB, blush #F1D4C7, sand #EFE3C4, sky #CFE0EA, lilac #DED6EA. Used as flat backgrounds for cards and sections. Each festival gets its own pastel, which also serves as its card background whenever no photo is available.
- Festival cards: each card shows a photo of the festival as the card background. Put the festival name and dates in a flat pastel label area (not directly over the photo) so text is always readable. Photos must be images I provide or have the right to use. Never pull pictures from random websites. Until I provide one, use the flat pastel color.
- No gradients (or as close to none as possible).
- Type: one bold, clean sans-serif font. Large headings, tight spacing, plenty of room around text.
- Animation: minimal. Subtle press/hover feedback on buttons and cards, and a gentle fade-in while scrolling. Nothing else.
- Laptop first.

**Layout ideas (to confirm in the first design)**
- Festival list: big headline, then a grid of large cards, one per festival, each with a pastel background and a big graphic. Local (NYC) and Travel as two clear sections.
- EDC page: large title, dates shown big, both weekends visible with Dawn highlighted as mine, then Lineup and Set times blocks showing "TBD" until released. Reserve clear spots for flights, hotels, and tickets later.

## Not in version one (later)
- Flights (including one-way prices and points deals)
- Hotels near the venue, or shuttles
- Ticket prices from the official site; resale checks (e.g., CrowdVolt, Radiate) if sold out
- Automatic updates of lineup, set times, and prices
- More festivals, and a mobile version
I want to see the design first so I know where these will go. Leave sensible space or placeholders without building them.

## Definition of done for version one
1. I can open the site at an online link on my laptop.
2. The festival list shows Local (empty) and Travel (EDC only).
3. Clicking EDC opens a page with correct dates and TBD lineup/set times.
4. The design is minimalist and consistent.
5. Adding a second festival requires only adding data, not rewriting pages.

## Status (Claude keeps this updated after each milestone)
**Done:** Brief and CLAUDE.md written (Oct 28, 2026).
**In progress:** Nothing yet. Project not started.
**Next:** Set up tools on personal Mac, create the project, plan the site in plan mode.
**Open decisions for me:**
- Tech stack and hosting (Claude to propose options)
- Example minimalist sites for design reference (I will provide)
