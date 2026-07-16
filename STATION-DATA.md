# Portland Downtown EV Charging Stations

Charging station data within 5 km of downtown Portland, OR — covering the commute corridor to Beaverton, OR (~12.8 km / ~8 miles).

Last updated: July 16, 2025 | Data source: OpenStreetMap (ODbL 1.0), Plug Share, Super Charge Info

## Search Parameters

| Field | Value |
|---|---|
| **Center point** | Downtown Portland (45.5159, -122.6822) |
| **Radius** | 5,000 meters |
| **Commute destination** | Beaverton, OR (45.4872, -122.8038) |
| **Commute distance** | ~12.8 km via Sunset Highway |

## Station Summary Table

| # | Station | Operator | Lat/Lon | Distance | Connectors | Power | Access | Notes |
|---|---|---|---|---|---|---|---|---|
| 1 | Unnamed | Unknown | 45.5175, -122.6801 | ~242m | J-1772 | L2 | Public | Closest station to downtown core |
| 2 | Unnamed | Unknown | 45.5153, -122.6782 | ~315m | J-1772 (Basic L2) | L2 | Public | Near Oregon Historical Society area |
| 3 | **Tesla Supercharger** | Tesla | 45.5184, -122.6805 | ~317m | NACS x4 @ 250 kW | **DC Fast** | Tesla customers only | 805 SW Broadway, 24/7 |
| 4 | Blink | Blink | 45.5187, -122.6762 | ~565m | J-1772 x4 @ L2 | L2 | Public | 4-port downtown core station |
| 5 | Unnamed | Unknown | 45.5122, -122.6769 | ~580m | Unknown (5 ports) | Unknown | Customers | Restricted access, details unknown |
| 6 | Blink | Blink | 45.5154, -122.6742 | ~624m | J-1772 @ L2 | L2 | Public | Fee applies |
| 7 | **Unnamed Multi-Protocol** | Unknown | 45.5161, -122.6739 | ~644m | J-1772 + CCS + CHAdeMO | DC Fast+ | Public | **Best multi-EV compatibility** |
| 8 | ChargePoint | ChargePoint | 45.5113, -122.6763 | ~682m | J-1772 @ L2 | L2 | Public | Nationwide network |
| 9 | Unnamed | Unknown | 45.5110, -122.6766 | ~692m | Unknown | Unknown | Public | Needs field verification |
| 10 | Blink | Blink | 45.5174, -122.6730 | ~735m | J-1772 @ L2 | L2 | Public | Near downtown |
| 11 | Unnamed Multi-Protocol | Unknown | 45.5110, -122.6763 | ~692m | J-1772 + CCS + CHAdeMO | DC Fast+ | Public | Additional multi-protocol option |

## Key Findings

### 🔋 DC Fast Chargers
- **Tesla Supercharger** (250 kW) — Only DC Fast from a major network within 1 km. 24/7, requires Tesla app/account. Located at 805 SW Broadway.

### 🔌 Multi-Protocol Champions (J-1772 + CCS + CHAdeMO)
- Station #7 at 644m — the most versatile charger near downtown. Supports virtually every non-Tesla EV (Chevy, Ford, Nissan, BMW, VW, etc.).
- Station #11 at ~692m — another multi-protocol option further from downtown.

### ⚡ Level 2 Network Coverage
- **Blink** → 3 stations within ~750 m, J-1772 connectors, Level 2 charging
- **ChargePoint** → Nationwide network access with J-1772 L2
- **Best environmental**: Many L2 chargers located within 500-700 m walk of the downtown core

### ⚠️ Coverage Gaps
- **No Electrify America or EVgo stations** within the immediate 1 km radius — available further out toward Beaverton
- Several stations are "unnamed" or "unknown" operator — highlights the value of verification & contribution
- Half the stations have "Unknown" hours / fee structures — consider chipping in for [Open Charge Map](https://openchargemap.org) to fill in global details

## Commute Sustainability Analysis

### Portland → Beaverton (~12.8 km)

| Mode | Duration | Feasibility | CO₂ Impact |
|---|---|---|---|
| 🚗 **EV** | ~15–20 min | ✅ Practical | ~2.6 kg (gas) → ~0.6 kg (EV average US grid) |
| 🚴 **Bike** | ~25–40 min | ⚠️ Dangerous (Sunset Hwy is a busy 4-lane) | Zero emissions |
| 🚶 **Walk** | ~2.5–3 hrs | ❌ Not practical — highway corridor | Zero emissions |
| 🚌 **Bus/Transit** | ~35–50 min | ✅ Practical | ~1/3 car |
| 🚗 **Solo Gas Car** | ~15–20 min | Yes (current) | ~2.6 kg CO₂ |

> **Key insight**: The Sunset Highway (US-26) corridor is a busy highway. Walking and cycling are unsafe and impractical on the direct route. Surfaced-street alternatives add significant distance. **EV driving remains the most sustainable practical personal vehicle option for this commute.**

### Suggested Ideal EV Commute Scenario

1. **Charge at the multi-protocol station** (~644m or ~735m) before heading out — Level 2 overnight or Level 2 top-up is usually sufficient for a 12.8 km commute (<4 kWh)
2. **Tesla owners** should use the Supercharger on SW Broadway for quick top-ups (250 kW in ~15 min for 80% charge)
3. **Route**: SW Broadway → SW Madison → Sunset Highway → Beaverton-Tigard Freeway → SW Beaverton Hillsdale Highway → SW Farmington Road → SW Hall Blvd → work

## Sources
- OpenStreetMap (ODbL 1.0) — primary data
- Plug Share —-operator details
- Super Charge Info — Tesla Supercharger location data
- Commute analysis: OSM routing + pedestrian/bicycle path analysis

## License
Data is contributed under Open Database License (ODbL). Please attribute OSM contributors if redistributing.

See [stations.json](stations.json) for raw data including GPS coordinates.