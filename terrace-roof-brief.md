# BBQ terrace light roof: wind, rain and sun brief (Rev D)

This is a preliminary design input for the architect. It covers **only the BBQ + seating terrace** on the SW side, at floor level. The 8.2 m length, grill position and other dimensions below refer to the earlier Rev D, not the current 12 × 10 / 10 × 12 m concepts; adapt and verify them for the selected layout.

The **winter-sun terrace** on the SE side stays **open, with no roof or cover**. It is used only on sunny winter days, and any cover would block the low winter sun that heats the great room through the SE glass.

## 1. Data used

- **Source:** ERA5 reanalysis, hourly, 2015-01-01 to 2024-12-31 (10 years, about 87,700 h). Retrieved through the Open-Meteo archive API for the site, at about 2,000 m.
- **Variables:** wind direction and speed at 10 m, gusts at 10 m, precipitation, rain, snowfall, temperature at 2 m.
- **Method:**
  - Directions are where the wind **comes from**, in 16 sectors.
  - Rain and driving-rain shares are weighted by mm, and by mm × wind speed.
  - Calm hours (< 3 km/h, 5.5 % of hours) are excluded from the roses.
- **Caveat:** ERA5 cells are about 10–25 km wide. Local valley channelling, the ranch buildings and trees can change the local wind. **Verify on site** before fixing the screen positions: ask the ranch staff, look at how the trees lean, and check where dust and snow drift.

## 2. Findings

### Wind

| | Prevailing (vector mean) | Main sectors |
|---|---|---|
| All year | 293° (WNW) | NW 18 %, W 16 %, NNW 11 %, WNW 11 %, WSW 10 % |
| Winter (Dec–Feb) | 277° (W) | W 16 %, NW 15 %, WSW 14 %, NNW 12 % |
| Summer (Jun–Aug) | 324° (NW) | W 33 % in the afternoon |
| **BBQ evenings, Nov–Mar (17–22 h)** | W–NW | NW 22 %, W 19 %, WNW 14 %, WSW 13 % |
| **BBQ evenings, May–Sep (17–22 h)** | W–NW | W 29 %, WNW 23 %, NW 21 % |

- Mean wind speed is 7.9 km/h in winter and 10.7 km/h in summer. The gust p90 is 35 km/h in winter and 40 km/h in summer.
- **Strong gusts come from the SW–W:**
  - Gusts ≥ 50 km/h come from about 249°. Winter gusts ≥ 40 km/h come from about 236°.
  - The gust p99 is 55 km/h. The highest recorded gust was **86 km/h** on 2020-12-06, from 255°.
  - ERA5 tends to underestimate local peaks.

### Rain and snow

- About **390 mm a year**, almost all in Nov–Mar: Jan 81, Feb 76, Mar 78, Nov 51 and Dec 53 mm. There are about 350 wet hours a year.
- **Rain comes from the S half:**
  - Mean direction about 183°.
  - SW 14 %, SE 12 %, SSE 10 %, ESE 10 %, S 10 %, SSW 10 %.
  - Driving rain (mm × speed) follows the same pattern, with the SW the strongest.
- Snow is light and occasional, mostly from the SE (about 148°). Snowfall is about 22 cm a month in January.
- Wind during rain is mostly light: median 9 km/h, p90 17 km/h (gust p90 53 km/h).
- **How far rain blows in under the roof** (drops falling at about 5 m/s, eave at 2.4 m):

| Wind | Rain angle from vertical | Reach under the eave |
|---|---|---|
| 9 km/h (typical) | 26° | ≈ 1.2 m |
| 17 km/h (p90) | 44° | ≈ 2.3 m |
| 30 km/h (gusty) | 59° | ≈ 4.0 m, the whole terrace |

### Temperature (for material choice)

- Mean daily minimum/maximum: January −3 / 8 °C, July 19 / 33 °C.
- Extremes in 2015–2024: −17 °C and 38 °C.

## 3. What this means for the terrace

| Side of the terrace | Exposure | Treatment |
|---|---|---|
| **NW end** (behind the BBQ station) | Evening wind W–NW, cold winter-night wind | **Fixed windscreen, about 2 m high**: low masonry or stone wall with toughened glass above it. Return it about 1.5 m along the SW side. |
| **SW long side** (open to the yard and sunset) | Driving rain from SW, strongest gusts SW–W, low summer sun in the afternoon | **Roll-down zip screens**: mesh in summer for sun and insects, clear PVC in winter. Keep them retracted in strong wind if the product requires it. |
| **SE end** (towards the winter-sun terrace) | Rain from S–SE, snow from SE | **Roll-down zip screen** (clear PVC), so the terrace can still be opened to the winter terrace. |
| House side (NE) | Sheltered | The roof ledger is fixed here. |

## 4. Roof over the BBQ terrace (light, not concrete)

**R1 – strip over the BBQ station** (NW end, about 1.3 m deep)
- Use a **solid, non-combustible** roof: steel sheet or fibre-cement on a steel frame.
- **No polycarbonate or PVC above the grill.**
- Fit a **hood and flue** over the grill. The flue must end at least about 1 m above the house parapet and the future roof-terrace level.

**R2 – seating area** (the rest, about 6.9 × 4 m)
- First choice: an **adjustable aluminium louvre roof** ("bioclimatic pergola").
  - Louvres closed: rain-tight and full summer shade.
  - Louvres open: winter sun, and the smoke and heat can escape.
- Budget choice: opal or solar-control multiwall polycarbonate on a steel frame, with removable summer shade mats.

**General**
- Fall **≥ 5° (≈ 9 %) away from the house**, with a gutter and downpipes on the outer SW edge. The water must not run to the house wall or the terrace door.
- Eave height about **2.4–2.6 m**. Overhang **0.3–0.5 m** past the deck edge on the SW and SE sides.
- Fix a ledger on the house wall **below the parapet**. Posts on the outer line at **no more than about 3 m centres**.
- **Wind uplift** governs the design:
  - Use tie-down anchors to the foundation, and keep in mind the 86 km/h gust (and higher locally).
  - Design to the Iranian National Building Regulations, Part 6 (loads, مبحث ششم), for wind and for the occasional snow load.
  - The structural engineer sets the numbers.
- Size the louvre-roof motor and rain sensor for the gust levels above, with auto-close on rain and auto-open in strong wind if the product requires it.
- Material choices:
  - UV-stable, frost-proof materials (−17 to +38 °C).
  - Powder-coated aluminium or galvanised steel.
  - No uncoated mild steel.

## 5. BBQ smoke: a decision for the architect

- The evening wind blows from W–NW. A grill at the NW end therefore sends smoke **across the seating towards the SE**, and partly towards the house glass.
- Rev D keeps the BBQ station at the NW end (next to the frying-room door for short service runs). For that reason, **the hood and flue are required**, not optional.
- **Alternative:** move the grill to the **S corner**. It would then sit downwind of the seating, and the smoke would leave the terrace. The trade-off is a longer walk from the frying room. Decide this after the on-site wind check.

## 6. Checklist for the architect

- [ ] Confirm the local prevailing wind on site (season and evening).
- [ ] Decide where the BBQ goes: NW end with hood and flue, or S corner.
- [ ] Roof system: louvre roof or polycarbonate + steel strip over the grill.
- [ ] Structural check for wind uplift and snow (Part 6); post and footing layout.
- [ ] Drainage: gutter on the SW edge, downpipes, a soakaway or the garden irrigation.
- [ ] Screens: fixed NW windscreen; zip screens on the SW and SE; lighting and outdoor sockets.
- [ ] Keep the **winter-sun terrace uncovered**.
