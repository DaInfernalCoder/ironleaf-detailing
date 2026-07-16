# Ironleaf Mobile Auto Detailing Houston Texas

## Requested outcome

Build and launch a polished, call-led auto detailing website and Google Business Profile asset pack for Houston, Texas, end to end.

## Confirmed facts

- Canonical name: Ironleaf Mobile Auto Detailing Houston Texas
- Business type: auto detailing
- Primary market: Houston, Texas
- Phone: +1 346-509-7033
- Appointment link: https://cal.com/sumitdatta/auto-detail-service
- Domain: `ironleafdetailing.shop`
- Domain status: registered July 16, 2026 through July 16, 2027
- Registration settings: one year, high privacy, `autoRenew: false`

## Decisions and truth constraints

- The Ironleaf name was screened against Houston detailers and exact-name web results; no same-category Houston conflict was found.
- Visual direction: carbon, steel, cool white, and inspection orange; narrow industrial display type; an inspection-light beam with measurement ticks is the signature device.
- Plain HTML, CSS, and JavaScript with no runtime package dependencies.
- Calling is the primary action and online appointment scheduling is the secondary action everywhere.
- No public street address, public email route, or unverified service radius.
- Do not invent prices, reviews, certifications, guarantees, hours, staff, customer counts, or completed-work claims.
- Launch photography is licensed stock and is not represented as Ironleaf customer work.
- The header uses its own solid background so legibility does not depend on the hero photograph.

## Acceptance criteria

- Permanent repository at `/Users/sumit/Documents/websites & apps/ironleaf-detailing`.
- Responsive, accessible site using +1 346-509-7033 everywhere.
- Call and online appointment links appear together in the header, hero, mid-page action, final action, footer, and mobile sticky bar.
- Static preflight and desktop/mobile browser checks pass without broken assets, console errors, overflow, or unreadable header text.
- Clean `main` commit in a dedicated GitHub repository connected to Vercel.
- Apex and `www` serve the intended production site over HTTPS.
- GMB pack at `/Users/sumit/Documents/gmb/Ironleaf Mobile Auto Detailing Houston Texas` has one logo, four covers, four business photos, the description, and sources.

## Task list

- [x] Confirm Houston, Texas and phone number.
- [x] Screen the Ironleaf name for local and same-category conflicts.
- [x] Check `ironleafdetailing.shop` availability and current price through Spaceship.
- [x] Obtain explicit purchase approval.
- [x] Register with high privacy and auto-renew off.
- [x] Define and critique the design direction.
- [x] Save this handoff in the permanent project folder.
- [x] Source and record licensed imagery.
- [x] Build the static site.
- [x] Run preflight and browser QA at desktop and phone widths.
- [x] Initialize git and commit `main`.
- [x] Create a dedicated GitHub repository and push.
- [x] Deploy through Vercel and connect GitHub.
- [ ] Attach apex and `www`, configure DNS, and verify HTTPS.
- [x] Build and validate the final GMB asset pack.

## Current state

The phone, brand, domain, registration settings, and design direction are locked. The domain is registered with high privacy and auto-renew disabled.

The plain HTML, CSS, and JavaScript site is built with licensed local photography and copied into the permanent project folder. Static preflight passes. Browser QA passes at 1440×1000 and 390×844 with one H1, no missing images, no JavaScript or console errors, no horizontal overflow, a legible solid header, a working mobile menu, and a contained two-button mobile bar. The public copy passed the required trigger-word scan.

GitHub repository `DaInfernalCoder/ironleaf-detailing` is connected to Vercel project `ironleaf-detailing` for push deploys. Production deployment `dpl_68brkWE4GM8yqbZ6pQbk7tD8rzkV` is `READY` and aliased to `https://ironleaf-detailing.vercel.app`.

The apex and `www` hosts are attached to the Vercel project. Spaceship is configured with `ns1.vercel-dns.com` and `ns2.vercel-dns.com`; high privacy remains active and auto-renew remains off.

The validated GMB pack is saved at `/Users/sumit/Documents/gmb/Ironleaf Mobile Auto Detailing Houston Texas` with one 1200×1200 logo PNG, four unique 1600×900 cover JPGs, four unique business JPGs, a 695-character description, and complete source/license notes.

## Blocker

The new `.shop` registry delegation is still propagating. Public DNS does not yet return the Vercel nameservers even though Spaceship shows the correct custom selection.

## Exact next action

Poll the `.shop` parent delegation until Vercel's nameservers are public, then verify apex and `www` through Vercel and run the live HTTPS content checks.
