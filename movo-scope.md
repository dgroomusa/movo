# movo — Project scope v1

**Purpose:** Concept pitch & validation · **Platform:** iOS + iPad · **Flow depth:** Full journey (~24 screens)
**Positioning:** "The AI that knows how you travel."

---

## 1. What we're validating

The pitch must prove three claims, in this order:

1. **Personalization is real** — movo learns taste and builds trips that feel personally designed, not templated.
2. **Trust through realism** — movo pushes back on unrealistic plans instead of blindly generating them. This is the credibility moment competitors miss.
3. **Calm during chaos** — when plans break, movo fixes them before the traveler panics.

Booking is shown as *proof the loop closes*, not as a differentiator — it gets one moment in the demo, not a deep flow.

---

## 2. V1 pillars & priority

| Pillar | Priority | Demo depth |
|---|---|---|
| Trip setup wizard (dates, origin/distance, destination) with **feasibility guardrails** | Must | Deep — this is new and central |
| Taste profile + AI itinerary generation | Must | Deep — the differentiator |
| Real-time replanning | Must | Deep — one scripted disruption moment |
| Conversational co-pilot | Must | Medium — 2–3 exchanges that modify the plan |
| In-app booking | Should | Shallow — one bundled "Book" confirmation |
| Voice assistant, loyalty, sustainability, social | Out of v1 | Roadmap slide only |

---

## 3. The trip setup wizard (new requirement)

The user starts from **what they know**, and movo fills the gaps:

- **Dates** — picker, or "I'm flexible" → movo suggests windows (price + weather + their calendar).
- **Where** — three entry modes:
  - *I know where* → type destination
  - *Somewhere within reach* → distance/travel-time radius from origin ("under 4 hours from SLC")
  - *Surprise me* → movo proposes from taste profile
- **Budget** — range slider with "movo estimate" prefill.

**Reality-check guardrails (must be visible in the pitch):**

- Pace check: "Rome, Florence, and Venice in 3 days is rushed — pick a base, or add 2 days?"
- Distance vs. dates: flags when travel time eats the trip ("14 hrs of flying for a 2-day stay").
- Season/weather: "Oaxaca in June is rainy season — still go, or shift to October?"
- Budget honesty: warns when the budget can't cover the ambition, offers the nearest realistic version.

Every guardrail is a **prompt with options**, never a dead end. Movo suggests; the user decides.

---

## 4. Screen inventory (~24 screens)

**A. First run & taste (4)**
1. Welcome / value promise
2–3. Taste check (swipe cards ×2 screen states)
4. Profile building / "designing your trips" moment

**B. Trip setup wizard (5)**
5. Dates (+ flexible mode)
6. Where (3 entry modes)
7. Budget
8. **Reality-check prompt** (the guardrail moment)
9. Generating… (AI working state)

**C. Itinerary (4)**
10. Trip overview (match score, bundle price)
11. Day-by-day timeline
12. Stop detail (why movo picked it — "because you…")
13. Edit/swap a stop

**D. Booking (2)**
14. Bundle review (flight + stay + activities, one price)
15. Confirmation

**E. Live trip & replanning (4)**
16. Trip-in-progress home (today view)
17. Disruption alert
18. Replan proposal (old vs. new, one-tap accept)
19. Updated timeline with change log

**F. Co-pilot chat (2)**
20. Chat with suggestion chips
21. Chat applying a change to the itinerary (split view on iPad)

**G. Profile & system (3)**
22. Taste profile (learned tags, retake)
23. Live connections (flights, weather, calendar)
24. Post-trip feedback ("rate the trip, teach movo")

**iPad adaptations (not extra screens, same content):** two-pane layouts — itinerary list + map/detail side by side; chat alongside the live itinerary so changes are visible as movo makes them. Pick 3–4 hero screens to show in both sizes; don't produce all 24 twice.

---

## 5. Pitch demo storyline (golden path)

1. Taste check → movo learns David likes slow mornings, markets, live music.
2. Trip setup: flexible dates, "within 4 hours," modest budget → **movo flags an unrealistic 3-city idea, proposes Lisbon instead** ← trust moment.
3. Generated itinerary, 96% match, one bundled price → Book.
4. Mid-trip: Tram 28 cancelled → movo has already rebooked → accept in one tap.
5. Chat: "What if it rains Thursday?" → plan reshuffles live.

---

## 6. Out of scope for v1

Android · voice assistant · group/social trip planning · loyalty program · sustainability scoring · user-generated reviews · real inventory/payment integrations (mocked in pitch) · offline mode.

## Design parking lot

- **Outline maps** (ref: glimpses-of-the-world.com/destinations) — minimal country outline + orange pin. Candidate homes: destination detail header, "Surprise me" reveal, trip share card, post-trip "places you've been" passport-stamp collection. Style rule: single-weight geometric stroke matching Material icon language, ink or on-color, pin in movo orange.
- **Photo sourcing** — treated real photography per the movo grade recipe (warm lift, −18% sat, 8% orange tint, bottom scrim).

## 7. Deliverables checklist for the pitch

- [x] Brand foundation & research summary (done)
- [x] Design system v1 (done)
- [x] Clickable concept prototype (done — extend with wizard + guardrail screens)
- [x] Figma screens started (4 frames — extend toward inventory above)
- [ ] Wizard + reality-check screens (the new core)
- [ ] iPad hero layouts (3–4)
- [ ] Pitch deck wrapping it all
