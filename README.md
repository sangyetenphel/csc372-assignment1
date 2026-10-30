# Community Event Guide: NC Youth & Family Voices Amplified

A two-page community guide built with plain HTML and CSS for CSC 372 at UNC Greensboro, Assignment 1. It introduces NC Youth & Family Voices Amplified, a program at the UNC Greensboro Center for Youth, Family & Community Partnerships, and spotlights one of its trainings.

## Pages

| Page | File | What it shows |
|---|---|---|
| Home | `index.html` | The program's mission, its vision, and a list of the services it provides |
| Events | `event.html` | A spotlight on a Youth Peer Support training: overview, featured activities, attendee tips and a testimonial |

Both pages share the same header (logo plus Home and Events links) and footer.

## Features

- **Semantic HTML:** pages are organized with `header`, `nav`, `main`, `article`, `section`, `blockquote`, `cite` and `footer`, with ordered and unordered lists.
- **One shared stylesheet:** `style.css` styles both pages, using element selectors plus a class (`.testimonial`) and an ID (`#event-image`).
- **Extra features:**
  - a **favicon** in the browser tab (`images/favicon.png`)
  - **custom list markers** that replace the bullets in unordered lists with a ⭐ through the CSS `::marker` pseudo-element
- **Accessible images:** every image has descriptive alt text.

## Project structure

```
index.html    Home page: mission, vision and services
event.html    Event page: Youth Peer Support training spotlight
style.css     Shared styles for both pages
images/       Logo, favicon and the event photo
```

## Running it locally

No installation is needed: open `index.html` in a browser. Everything is local, so it also works offline.

## Built with

- HTML5
- CSS3

The program description is adapted from NC Youth & Family Voices Amplified for this class assignment.

Created by Sangye Tengkhar, September 2026.
