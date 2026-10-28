# Rituj & Ria — A Little World

A lightweight, production-oriented static wedding invitation for Sunday, 24 January 2027 in Nagpur.

## Included
- `index.html` — complete website, with custom inline SVG illustrations and JavaScript interactions.
- `assets/couple.png` — supplied couple photograph, used without face-generation or substitution.

## Features
- Cinematic invitation intro with CSS 3D card arrival and open/skip controls.
- No top navigation bar and no music bar/control.
- Custom illustrated mandap, reception, map, floral and travel scenes.
- Countdown to the start of 24 January 2027 (India time; no invented event time).
- Interactive event-card tilt, photo depth, scroll reveals and petal burst.
- Venue directions link to a Google Maps search for Ladies Club, Civil Lines, Nagpur.
- Functional WhatsApp RSVP flow with conditional attendance/accommodation fields.
- Responsive layout for mobile, tablet and desktop.
- Reduced-motion support and accessible labels/focus states.

## Deploy
Upload the entire folder to any static host such as Cloudflare Pages, Netlify or GitHub Pages. No build step is required.

## RSVP storage
The current RSVP action prepares a WhatsApp message and opens the selected family contact. It does **not** store submissions centrally. If central storage/email notifications are later desired, connect a backend/form service and keep credentials server-side.

## Music
No music control is included. If a licensed/user-provided track is later supplied, audio can be added with explicit user activation and muted-by-default behaviour.
