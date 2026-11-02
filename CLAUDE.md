# Rave Planner (personal project)

A personal website that helps me plan music festivals: a festival list, and a page per festival with dates, lineup, and set times. Later it will also show flights, hotels, and tickets. For my own use only. Do not spend effort on monetization, SEO, or scale.

Read PRODUCT.md for what to build and what "done" means for version one.

## About me (how to work with me)
- I am new to coding, GitHub, and the terminal. I'm on a Mac.
- Explain things in plain language. When you run a command or make a technical choice, say in one sentence what it does and why.
- Don't use jargon without defining it the first time.
- I want to be as hands-off as possible once I approve a direction.

## How to work
- For anything bigger than a small fix, start in plan mode: propose a plan, wait for my approval, then build.
- Build in small steps. After each milestone, run the site and check that it actually works before telling me it's done.
- Ask before installing new packages, adding paid services, or creating accounts.
- Never put passwords, API keys, or tokens in code. Use environment variables and tell me what to set.
- Commit to git after each working milestone with a clear message. Don't push to GitHub until I say so.
- After finishing each milestone, update the Status section in PRODUCT.md: what's done, what's in progress, what's next, and any open decisions for me. At the start of a new session, read that section first so you know where we left off.
- If you make a mistake or I correct you, suggest a one-line rule to add to this file.

## Design
- Minimalist: lots of whitespace, bold simple type, flat pastel color accents, no gradients, small corner radius (not pill-shaped), big graphics and little text. Full details are in the Design direction section of PRODUCT.md.
- Animation: only subtle button/hover feedback and a gentle scroll fade-in.
- I will provide example sites for reference later. Until then, keep styling simple and easy to change.
- Laptop/desktop first. Don't build a mobile layout yet, but avoid choices that make one hard later.

## Technical principles
- Keep it as simple as possible. Prefer fewer files, fewer dependencies, and free hosting.
- Stack is not decided. In plan mode, propose the simplest option that can be hosted online at a link and can later pull in live data, and explain the tradeoffs briefly.
- Store festival information as structured data (one data file per festival or a single list), separate from the page layout. Later, automated integrations (flights, hotels, tickets) must be able to update this data without redesigning pages.
- Mark unknown information as "TBD" in the data. Don't invent lineups, set times, or prices.
