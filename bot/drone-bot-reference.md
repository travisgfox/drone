# Part 107 reference corpus — Drone Journalism course helper

Public-domain source material for the course helper. Sent to the model along with the
system prompt (`drone-bot-context.md`). Everything here is a US government work: no
copyright, safe to host publicly.

**Sources**
- 14 CFR Part 107, retrieved from eCFR (current as of Aug 2026) — https://www.ecfr.gov/current/title-14/chapter-I/subchapter-F/part-107
- FAA-S-ACS-10B, Remote Pilot sUAS Airman Certification Standards, effective April 6, 2021 — https://www.faa.gov/sites/faa.gov/files/training_testing/testing/acs/uas_acs.pdf

**Precedence rule for the bot:** where this file and any textbook disagree, the regulation
text below wins. Two known drift points: §107.9 was renamed "Safety event reporting" in a
2022 amendment (the ACS, dated 2021, still calls it "Accident reporting"), and the FAA has
amended night-operations and operations-over-people rules since many study guides were
written. Quote the text here.

---

# PART 1 — THE EXAM ITSELF

Official name: Unmanned Aircraft General – Small (UAG) knowledge test.

- **60 multiple-choice questions**, single correct answer each, **2 hours** to complete.
- **70% required to pass** (42 of 60).
- Question mix by topic:
  - Regulations — 15–25%
  - Airspace & requirements — 15–25%
  - Weather — 11–16%
  - Loading & performance — 7–11%
  - **Operations — 35–45%** (the largest block by far)
- Minimum age **14 to sit the test**; **16 to hold the certificate** (§107.61).
- Failure: must wait **14 calendar days** to retake (§107.71). No instructor endorsement
  needed to retest.
- Passing test report (AKTR) is valid **24 calendar months** for the certificate application.
- Testing centers run by PSI: https://faa.psiexams.com/faa/login
- Allowed in the test room: the proctor-supplied supplement book, plotters, straightedges,
  simple calculators. Not allowed: any handwritten/printed notes, dictionaries, programmable
  memory devices.
- Recency to keep exercising privileges: complete the free online recurrent training within
  the previous **24 calendar months** (§107.65).

Test-taking note worth passing to students: Operations is 35–45% of the exam — bigger than
Regulations. Students who only drill the regs under-prepare.

---

# PART 2 — WHAT THE EXAM COVERS (ACS knowledge areas)

**I. Regulations** — A. General (applicability, definitions, falsification, accident/safety
event reporting, inspection & compliance, multiple-category sUAS, record retention) ·
B. Operating Rules (registration, condition for safe operation, medical conditions, remote
PIC authority, in-flight emergencies, hazardous ops, moving vehicles, alcohol/drugs, daylight
& civil twilight & night ops, VLOS, visual observer, multiple aircraft prohibition, hazmat,
right-of-way, ops over people, airspace authorization, airports, prohibited/restricted areas,
NOTAMs, preflight, operating limitations, transponder and ADS-B prohibitions) ·
C. Certification (alcohol/drug offenses, eligibility, knowledge recency) · D. Waivers ·
E. Operations Over People (categories 1–4, minimum distances, moving vehicles, kinetic
energy, exposed rotating parts, declarations of compliance) · F. Remote ID (standard,
alternative, message elements, labeling).

**II. Airspace** — A. Classification (Classes B, C, D, E, G; special use: prohibited,
restricted, warning, MOA, alert, controlled firing; other: MTRs, TFRs, parachute ops, TRSAs,
NSAs, VFR routes) · B. Operational requirements (weather minimums, ATC authorization,
operations near airports, flight hazards including thermal plumes and the wire environment,
NOTAM system, lighting).

**III. Weather** — A. Sources (METAR, TAF, weather charts, ASOS/AWOS) · B. Effects on
performance (density altitude, wind, stability, air masses and fronts, thunderstorms and
microbursts, icing, fog, ceiling and visibility, lightning).

**IV. Loading & performance** — effects of loading changes, balance/stability/CG, using
performance data.

**V. Operations** (largest section) — A. Radio comms (CTAF, UNICOM, ATIS, phonetic alphabet,
phraseology) · B. Airport operations (airport types, runway markings, traffic patterns,
chart supplements, wildlife hazards, lighting) · C. Emergency procedures (**lithium battery
hazards**, lost link and flyaways, GPS loss, frequency spectrum) · D. Aeronautical
decision-making (ADM, CRM, situational awareness, **hazardous attitudes**, risk assessment) ·
E. Physiology (dehydration, drugs/alcohol, hyperventilation, stress and fatigue, vision,
night illusions) · F. Maintenance & inspection (preflight, mitigating mechanical failure,
recordkeeping, who may maintain).

---

# PART 3 — REGULATION TEXT (verbatim, 14 CFR Part 107)

## §107.51 Operating limitations — the most-tested section

A remote pilot in command and the person manipulating the flight controls must comply with
all of the following:

> (a) The groundspeed of the small unmanned aircraft may not exceed 87 knots (100 miles per hour).
>
> (b) The altitude of the small unmanned aircraft cannot be higher than 400 feet above ground
> level, unless the small unmanned aircraft: (1) Is flown within a 400-foot radius of a
> structure; and (2) Does not fly higher than 400 feet above the structure's immediate
> uppermost limit.
>
> (c) The minimum flight visibility, as observed from the location of the control station must
> be no less than 3 statute miles. For purposes of this section, flight visibility means the
> average slant distance from the control station at which prominent unlighted objects may be
> seen and identified by day and prominent lighted objects may be seen and identified by night.
>
> (d) The minimum distance of the small unmanned aircraft from clouds must be no less than:
> (1) 500 feet below the cloud; and (2) 2,000 feet horizontally from the cloud.

## §107.31 Visual line of sight

> (a) With vision that is unaided by any device other than corrective lenses, the remote pilot
> in command, the visual observer (if one is used), and the person manipulating the flight
> control must be able to see the unmanned aircraft throughout the entire flight in order to:
> (1) Know the unmanned aircraft's location; (2) Determine the unmanned aircraft's attitude,
> altitude, and direction of flight; (3) Observe the airspace for other air traffic or hazards;
> and (4) Determine that the unmanned aircraft does not endanger the life or property of another.

Corrective lenses are fine; binoculars, FPV goggles, and telephoto screens do not satisfy VLOS.

## §107.29 Operation at night

Night operations are permitted without a waiver if:

> (1) The remote pilot in command has completed an initial knowledge test or training under
> §107.65 after April 6, 2021; and (2) The small unmanned aircraft has lighted anti-collision
> lighting visible for at least 3 statute miles that has a flash rate sufficient to avoid a
> collision. The remote pilot in command may reduce the intensity of, but may not extinguish,
> the anti-collision lighting if he or she determines that, because of operating conditions, it
> would be in the interest of safety to do so.

Civil twilight requires the same anti-collision lighting. Civil twilight = 30 minutes before
official sunrise, and 30 minutes after official sunset (except Alaska).

## §107.41 Operation in certain airspace

> No person may operate a small unmanned aircraft in Class B, Class C, or Class D airspace or
> within the lateral boundaries of the surface area of Class E airspace designated for an
> airport unless that person has prior authorization from Air Traffic Control (ATC).

Class G requires no authorization. In practice authorization comes through LAANC.

## §107.39 Operation over human beings

> No person may operate a small unmanned aircraft over a human being unless — (a) That human
> being is directly participating in the operation; (b) That human being is located under a
> covered structure or inside a stationary vehicle that can provide reasonable protection from
> a falling small unmanned aircraft; or (c) The operation meets the requirements of at least
> one of the operational categories specified in subpart D.

**The four categories (subpart D):**
- **Category 1** — aircraft weighs **0.55 lb (250 g) or less** on takeoff including everything
  attached, and has no exposed rotating parts that could lacerate skin. No sustained flight
  over open-air assemblies unless remote ID requirements are met.
- **Category 2** — will not cause injury equal to or greater than **11 foot-pounds** of kinetic
  energy transfer on impact; no exposed rotating parts that could lacerate; FAA-accepted
  declaration of compliance; labeled.
- **Category 3** — **25 foot-pounds** threshold; same labeling/declaration requirements;
  **may not operate over open-air assemblies**; only over people within a closed- or
  restricted-access site where people are on notice, or without sustained flight over anyone
  not participating or under cover.
- **Category 4** — requires an airworthiness certificate issued under Part 21.

## §107.49 Preflight familiarization, inspection, and actions

> Prior to flight, the remote pilot in command must: (a) Assess the operating environment,
> considering risks to persons and property in the immediate vicinity both on the surface and
> in the air. This assessment must include: (1) Local weather conditions; (2) Local airspace
> and any flight restrictions; (3) The location of persons and property on the surface; and
> (4) Other ground hazards. (b) Ensure that all persons directly participating are informed
> about the operating conditions, emergency procedures, contingency procedures, roles and
> responsibilities, and potential hazards; (c) Ensure that all control links between ground
> control station and the small unmanned aircraft are working properly; (d) If the small
> unmanned aircraft is powered, ensure that there is enough available power ... for the
> intended operational time; (e) Ensure that any object attached or carried ... is secure and
> does not adversely affect the flight characteristics or controllability.

## §107.19 Remote pilot in command

> (b) The remote pilot in command is directly responsible for and is the final authority as to
> the operation of the small unmanned aircraft system.
> (c) ... must ensure that the small unmanned aircraft will pose no undue hazard to other
> people, other aircraft, or other property in the event of a loss of control ... for any reason.

## §107.9 Safety event reporting

> No later than 10 calendar days after an operation ... a remote pilot in command must report
> to the FAA ... any operation of the small unmanned aircraft involving at least:
> (a) Serious injury to any person or any loss of consciousness; or
> (b) Damage to any property, other than the small unmanned aircraft, unless one of the
> following conditions is satisfied: (1) The cost of repair (including materials and labor)
> does not exceed $500; or (2) The fair market value of the property does not exceed $500 in
> the event of total loss.

## Other operating rules, condensed

- **§107.25** — no operation from a moving aircraft; from a moving land or water vehicle only
  over a **sparsely populated area** (and not carrying another's property for hire).
- **§107.35** — one person may not operate more than one aircraft at a time.
- **§107.36** — no carriage of hazardous material.
- **§107.37** — sUAS must **yield right of way to all** aircraft; may not pass over, under, or
  ahead unless well clear.
- **§107.23** — no careless or reckless operation; no dropping objects so as to create an
  undue hazard.
- **§107.15** — aircraft must be in a condition for safe operation; RPIC checks before each flight.
- **§107.17** — no operating with a known physical or mental condition that would interfere.
- **§107.21** — in an emergency the RPIC may deviate from any rule as needed, and must send a
  written report if the Administrator requests it.
- **§107.43 / §107.45 / §107.47** — no interference with airport operations; no prohibited or
  restricted areas without permission; comply with TFRs (§§91.137–91.145).
- **§107.13** — registration required (Part 48).
- **§107.52 / §107.53** — no transponder; no ADS-B Out in transmit mode.
- **§107.27** — alcohol/drug rules of §§91.17 and 91.19 apply (8 hours bottle-to-throttle,
  0.04 BAC).

## §107.205 — What can be waived

Waivable: §107.25 (moving vehicle) · §107.29(a)(2) and (b) (anti-collision light) · §107.31
(VLOS) · §107.33 (visual observer) · §107.35 (multiple aircraft) · §107.37(a) (yielding right
of way) · §107.39 (over people) · §107.41 (airspace) · §107.51 (operating limitations) ·
§107.145 (over moving vehicles).

**Not waivable** — and a favorite exam trap: you cannot waive the requirement to hold a
certificate, the prohibition on carrying hazardous material (§107.36), the medical-condition
rule, the careless-and-reckless rule, or the requirement that the aircraft be in a condition
for safe operation.

## §107.73 — Knowledge areas by regulation

> (a) Applicable regulations ... (b) Airspace classification, operating requirements, and
> flight restrictions ... (c) Aviation weather sources and effects of weather on small
> unmanned aircraft performance; (d) Small unmanned aircraft loading; (e) Emergency
> procedures; (f) Crew resource management; (g) Radio communication procedures; (h)
> Determining the performance of the small unmanned aircraft; (i) Physiological effects of
> drugs and alcohol; (j) Aeronautical decision-making and judgment; (k) Airport operations;
> (l) Maintenance and preflight inspection procedures; and (m) Operation at night.

---

# PART 4 — NUMBERS CHEAT SHEET

| Item | Value | Cite |
|---|---|---|
| Max altitude | 400 ft AGL (or 400 ft above a structure within 400 ft of it) | §107.51(b) |
| Max groundspeed | 87 knots / 100 mph | §107.51(a) |
| Min flight visibility | 3 statute miles | §107.51(c) |
| Cloud clearance | 500 ft below, 2,000 ft horizontal | §107.51(d) |
| Anti-collision light visibility | 3 statute miles | §107.29 |
| Civil twilight | 30 min before sunrise / 30 min after sunset | §107.29(c) |
| Category 1 weight | 0.55 lb (250 g) | §107.110 |
| Category 2 / 3 kinetic energy | 11 / 25 foot-pounds | §107.120 / §107.130 |
| Safety event report deadline | 10 calendar days | §107.9 |
| Property damage reporting threshold | $500 | §107.9 |
| Certificate age minimum | 16 | §107.61 |
| Test-taking age minimum | 14 | ACS App. 1 |
| Knowledge recency | 24 calendar months | §107.65 |
| Retest wait after failure | 14 calendar days | §107.71 |
| Exam | 60 questions, 2 hours, 70% to pass | ACS App. 1 |
| Registration marking | required, Part 48 | §107.13 |
