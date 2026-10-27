# Shadow Probe — Schematic Document

© 2026 Curtis Ray Dyess · Crimson Rose

**Status: DRAFT / GATHERED.** This is Curtis's design, drawn from his hand
sketch titled "Shadow Probe" and developed in conversation on October 26, 2026.
It is not yet declared standing. Nothing here is a build order, a funding
commitment, or a claim that any hardware exists.

Diagram: [shadow-probe-schematic.svg](shadow-probe-schematic.svg) — drawn
programmatically, every element labeled in plain language.

## 1. System overview

The Shadow Probe is a sun-diving spacecraft concept with one job, stated in
Curtis's own words: **safely relay and harvest the sun's energy** — as a
potential replacement for nuclear power plants.

The core idea has two halves that fit together:

- **Harvest at the source.** Sunlight near the sun is hundreds of times
  stronger than what reaches Earth, with no clouds and no night. A probe that
  collects energy close to the sun is the biggest solar farm there is.
- **Survive by shadow.** The probe lives in the shadow of its own heat shield,
  the way Parker Solar Probe flies behind its shield. The shield takes the
  heat; everything behind it works in the shade. That is what the name means:
  the shadow is the instrument that makes the mission possible.

The probe's center, in both Curtis's sketch and this schematic, is the
**Beacon**: a dark center point with a ring of fire around it. The Beacon has
two jobs — read the sun up close, and send the harvested energy on.

Curtis's caption on the sketch, kept verbatim: *"The beacon will allow for
further indepth info on the suns characteristics."*

## 2. Component list

| Component | Function, in plain language |
|---|---|
| The Sun | The energy source. Also the thing being studied: irradiance swings, flare timing, solar wind. |
| Heat shield | Faces the sun and takes the heat, so the rest of the probe does not have to. Casts the shadow the probe lives in. |
| Shadow zone | The shaded space behind the shield. The probe bus, computers, and instruments sit here, protected. |
| Harvesting array | Panels that collect sunlight for power. The wings reach out of the shadow into sunlight; the bus stays shaded. |
| Probe bus | The spacecraft body: power handling, computers, cooling. Carries the Beacon at its center. |
| Beacon | Sensor + relay in one package. Senses the sun's characteristics up close, and relays harvested energy outward. |
| Relay station(s) | Step the energy home. If one hop is too far for a beam to stay tight, a chain of stations carries it in steps. |
| Ground receivers | A rectenna field on the ground that catches the downlink beam and turns it back into power for the grid. |
| Safety systems | Heat cut-out, beam interlock, fail-secure behavior. If signal is lost, the system goes safe — no beam without a confirmed receiver lock. |

## 3. Energy path (sun to receiver)

1. Sunlight strikes the harvesting array near the sun.
2. The array converts it to power aboard the probe bus, in the shield's shadow.
3. The Beacon relays the energy outward as a beam, and sends sensor data with it.
4. Relay station(s) receive the beam and step it onward, in a chain if one hop
   is too far.
5. Ground receivers (rectenna field) catch the downlink beam at low density
   and feed power to the grid.
6. Goal: firm, always-on power — the job nuclear plants do today — with no
   fuel burned and no long-lived waste.

## 4. Data path (what the Beacon learns)

The Beacon's sensing job is as important as its relay job. Close-up readings of
the sun's characteristics — irradiance, flare timing, solar wind — feed
forecasting for solar farms and protection for the power grid. This is the same
space-weather work as the daily solar brief: know what the sun is doing before
its weather reaches us.

## 5. Safety doctrine

Safety over power. That rule governs the whole design:

- **The shield comes first.** No instrument, panel, or crew-equivalent system
  sits in direct sun without the shield between it and the star.
- **Fail-secure.** If signal is lost, the system goes safe on its own. A beam
  that cannot confirm its receiver does not fire.
- **Safe at ground level.** The downlink beam must be weak enough at the
  ground that it cannot hurt anything it misses. Low density at the receiver
  is a design requirement, not an afterthought.
- **No single long shot assumed.** If a beam spreads too much over one hop,
  the design uses a chain instead of hoping the physics cooperates.

## 6. Technology connections (Curtis's direction)

- **CERN — the cage.** CERN does not make power, but it makes the things
  star-heat engineering needs: superconducting magnets, cryogenics colder than
  deep space, vacuum systems. The LHC's magnets are cousins to a tokamak's cage.
- **China's EAST tokamak — the bottled star.** The "artificial sun" in Hefei
  is a magnetic bottle holding plasma past a hundred million degrees for
  hundreds of seconds. It proves the containment half of the problem: holding
  star-heat safely.
- **Space solar power — the relay precedent.** China's published roadmap
  toward beaming power down by microwave is the relay idea already being tested
  in pieces. The Shadow Probe applies the same relay thinking at the source.

## 7. Open decisions (Curtis to decide — not invented here)

1. **Relay form:** microwaves to ground stations, laser to orbital receivers,
   or a station-to-station chain? Each shapes the machine differently.
2. **Closest approach:** how close does the probe get to the sun? Distance
   sets both the harvest and the heat problem.
3. **Shield material:** what the heat shield is made of. The material choice
   decides how close the probe can fly and how long it lasts.

## 8. What this is not

- Not a claim that the probe exists, has flown, or has funding.
- Not a partnership with CERN or any Chinese program. Those are technology
  connections Curtis named, not agreements.
- Not a replacement for any existing power plant until the open decisions
  above are answered and the safety case is proven.

---

© 2026 Curtis Ray Dyess · Crimson Rose
