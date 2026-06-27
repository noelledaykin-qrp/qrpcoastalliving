# QRP Coastal Living Website

Landing page and guest resource site for **QRP Coastal Living**, starting with the Flamingo Landing Airbnb property.

This repository is connected to **Netlify** for deployment. Treat every push to the `main` branch like it could go live.

## Purpose

This website should:

- Showcase the Airbnb property clearly and professionally
- Send visitors to the Airbnb listing or booking call-to-action
- Provide a downloadable guest guidebook
- Explain what guests need to know before, during, and after their stay
- Preview local recommendations and Charleston-area highlights
- Support the QRP Coastal Living brand as it grows beyond one property

Keep the site clean, fast, useful, and guest-friendly. Do not overbuild it.

## Brand Information

### Parent Brand

**QRP Coastal Living**

### Property Name

**Flamingo Landing**

### Tagline

**Curated Stays. Coastal Charm.**

### Brand Feel

The site should feel:

- Warm
- Clean
- Coastal
- Boutique
- Trustworthy
- Helpful
- Slightly playful, but not cheesy

Avoid making the entire site overly flamingo-themed. Flamingo Landing can have personality, but the design should still feel elevated.

## Tech Stack

- **GitHub** for source control
- **Netlify** for hosting and deployment
- Static website unless a framework is intentionally added later

If a framework is added later, update this README with:

- Framework name
- Build command
- Publish directory
- Environment variables
- Any special deployment steps

## Netlify Deployment Notes

Netlify should deploy from the `main` branch.

For a basic static site:

- Build command: leave blank
- Publish directory: project root or `/`

Before pushing to `main`, assume Netlify may immediately publish the changes.

## Deployment Checklist

Before every push, confirm:

- The site loads correctly
- The mobile layout looks clean
- Images are not broken
- Buttons work
- Airbnb booking link works
- Guidebook download link works
- No placeholder text remains
- No console errors appear
- No private guest, property access, or owner information is exposed publicly

## Privacy and Guest Safety Rules

Do not publish private guest access information on the public website.

The public site may include:

- Property description
- General check-in expectations
- General check-out expectations
- House rules
- Local recommendations
- Amenities
- Photos
- Airbnb listing link
- A public-safe guidebook download

If a guidebook contains private arrival or access details, create a separate guest-only version instead of posting it publicly.

## Recommended Site Structure

The homepage should include:

1. Hero section
2. Property overview
3. Photo gallery
4. Amenities
5. Guest guidebook download section
6. Local area preview
7. Stay styles or package ideas
8. Booking call-to-action
9. Host or brand note

## Core Website Copy Direction

The site should position Flamingo Landing as more than just a basic Airbnb.

Suggested positioning:

> Flamingo Landing is a curated Charleston-area stay designed for comfort, convenience, and coastal charm. Whether guests are visiting for a weekend getaway, business trip, family stay, golf weekend, or Charleston adventure, the home should feel easy, welcoming, and thoughtfully prepared.

## Guidebook Purpose

The guidebook should help guests feel prepared before they arrive and supported during their stay.

Recommended guidebook sections:

1. Welcome note
2. Check-in instructions
3. Parking and entry details
4. Wi-Fi and house basics
5. House rules
6. Fire pit and outdoor space instructions
7. Check-out checklist
8. Emergency information
9. Local food recommendations
10. Charleston day-trip ideas
11. Beaches and outdoor activities
12. Shopping, coffee, and dessert
13. Golf and business traveler notes
14. Final thank-you page

Public guidebook versions should not include private guest-only information.

## Recommended File Structure

```text
/
├── README.md
├── index.html
├── styles.css
├── guidebook.pdf
└── images/
    ├── living-room.jpg
    ├── kitchen.jpg
    ├── bedroom-1.jpg
    ├── bedroom-2.jpg
    ├── bathroom.jpg
    ├── backyard.jpg
    └── exterior.jpg
```

If using a framework later, update this structure.

## Content Priorities

The site should make these things obvious within a few seconds:

- What the property is
- Where it is generally located
- Why it is worth staying there
- How to book
- How to download the guidebook

Do not bury the booking link or guidebook button.

## Design Rules

Keep the design simple and polished.

Avoid:

- Too many fonts
- Too many colors
- Giant walls of text
- Random clip art
- Low-quality images
- Overly themed flamingo graphics
- Confusing navigation

Use strong photos, clean spacing, and clear calls to action.

## Future Enhancements

Potential additions:

- Direct booking inquiry form
- Separate public and private guest guidebooks
- Password-protected guest resources
- Local recommendation map
- Email capture
- Stay package pages
- Girls' trip page
- Family stay page
- Business traveler page
- Golf getaway page
- Charleston weekend guide

## Do Not Break

These items matter most:

- Airbnb booking button
- Guidebook download button
- Mobile layout
- Image loading
- Netlify deployment
- Public/private information separation

If any of these are broken, the site is not ready to publish.
