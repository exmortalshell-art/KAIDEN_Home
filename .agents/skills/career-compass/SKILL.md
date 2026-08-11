---
name: career-compass
description: Turn a confirmed career/profile.md into a concrete navigation plan. Use when the user runs /career-compass or asks for next career steps after grilling.
disable-model-invocation: true
---

# Career Compass

Prerequisite: `career/profile.md` with **confirmed** shared understanding. If the file is missing, unconfirmed, or empty of a target portrait, stop and tell the user to finish `/grill-me` (and save the profile) first.

## Job

Read `career/profile.md`. Produce an actionable compass — not another full interview, not motivational fluff.

1. Pull market facts yourself when needed (local salary bands, vacancy patterns for the stated city/role). Do not ask the user for facts you can look up.
2. Do **not** re-litigate settled profile decisions.
3. Write or update `career/compass.md` with the sections below.
4. Show the user a short summary of the bearings and point them to `career/compass.md`.
5. If a critical edge left open in the profile **blocks** the compass (e.g. no geography, no money floor, no role target), ask at most **3** frontier questions in `/grilling` format, wait for answers, update `career/profile.md`, then finish the compass. Soft open edges (e.g. which hobby to try first) go into **Open edges** — do not block the whole compass on them.

## `career/compass.md` sections

1. **North star** — one sentence distilled from the profile’s one-line criterion  
2. **Primary bearing** — role #1: what to hunt, what “good” looks like  
3. **Secondary bearing** — backup role and when to take it  
4. **Hard filters** — money floor + stop-flags as a yes/no checklist for any vacancy  
5. **Search queries** — concrete queries for the user’s city/market (hh / SuperJob style)  
6. **Interview probe kit** — questions and signals to catch stop-flags before accepting  
7. **30-day navigation** — week-by-week actions (job search + any parallel from the profile)  
8. **Open edges** — only decisions still unset; each with a recommended next experiment  

Keep the file terse and usable. Prefer checklists and queries over essays.
