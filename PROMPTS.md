# AI Prompts — Placeholder Section (AI Challenge)

## What I built
I replaced the "Something Missing? Generate a relevant section with AI" placeholder with a
brand-new section: **"The 48-Hour Build Sprint"** — an on-site hackathon for DevConf 2026.
It shows the weekend schedule as three cards (Friday / Saturday / Sunday) and a highlighted
"Grand Prize" box below them.

**Why this idea (uniqueness):** none of the required sections cover what actually *happens*
at the event, so a live hackathon adds something new instead of repeating Speakers or Pricing.

**How it fits (visual + thematic):** it reuses the same design language as the rest of the
page — the Poppins font, the blue `#2563eb` accent, rounded cards, and a dark highlight box
that mirrors the dark "Pro" pricing card — so it blends in while still standing out.

## Tool used
ChatGPT

## Prompts I used

**1. Ideation — get a unique, on-theme idea**
> I'm building a landing page for a developer conference called DevConf 2026. I need one
> unique, creative section to replace a generic placeholder. It must fit a tech-conference
> theme and must NOT duplicate my existing Navbar, Hero, Speakers, Pricing, or Footer.
> Give me 3 fresh section ideas, and for each say why an attendee would care.

**2. Design + copy — pick one and shape it**
> Let's go with the on-site hackathon idea: "The 48-Hour Build Sprint." Structure it as a
> heading and subtitle, then a row of three cards for the weekend schedule — Friday 6 PM
> (Kickoff & Team Match), Saturday (Build with Mentors), Sunday 4 PM (Demo & Awards) — each
> with one short sentence. Below the cards, add a wide "Grand Prize" box with a $25,000 prize
> and one line about what winners get. Write all the copy in a friendly developer voice, no
> Lorem Ipsum, and make every sentence unique.

**3. Implementation — code it to match my page**
> Now write it in plain, beginner-friendly HTML and CSS only (no JavaScript, no frameworks).
> Match the rest of my site: Poppins font, blue `#2563eb` accent, simple rounded cards, light
> theme. Use a soft lavender background for the three schedule cards and a dark background for
> the prize box so it pops. Use CSS grid for the three cards and stack them into one column on
> mobile with a media query.

**4. Refine**
> Tighten the copy so each schedule card is one short line, and make sure the section spacing
> and card radius match the pricing section above it.
