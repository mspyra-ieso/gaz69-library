# S-21 engine and Weber 28/35 carburettor knowledge base

This knowledge base is for an FSO **S-21** engine (2.12 L OHV, about 70 hp) with a Polish-made **Weber 28/35** twin-throat carburettor that has an **EZ-20 idle cut-off solenoid**. The engine is fitted in a **GAZ-69**, which originally had the M-20. The carburettor is most likely the **28/35 S2A1**, the common type on S-21 Żuks and Nysas.

It was compiled in October 2026 from:
- factory Żuk documents on archive.org: owner's manuals from 1985, 1989 and 1994, the 1988 parts catalogue and the 1991 factory bulletins;
- the FSO manuals in this repo;
- Polish owner forums, mainly forum.polskiedostawczaki.pl, zlombol.pl and syrena.nekla.pl;
- Russian drive2.ru logbooks of S-21 GAZ-69s;
- shops and videos.

Every fact links to its source. Each file labels its sources as one of:
- **[DOC] / [FACTORY]**: manuals and documented data.
- **[FORUM]**: owner experience.
- **[GENERAL]**: general carburettor practice.

Owners rarely name the carburettor or the engine; they say "Weber" or "gaźnik" and name the vehicle (Żuk, Nysa, Tarpan, Warszawa 223/224).

> An earlier version of this knowledge base targeted the older **Weber 34S2B1** by mistake. That material is kept in [`weber-34s2b1/`](weber-34s2b1/) for reference. **Its float level (5–5.5 mm), jets and "no solenoid" notes do not apply to your 28/35.**

## How to use this knowledge base

- **Something is wrong:** go to "Diagnose by symptom" below, then the matching section of [weber-28-35/troubleshooting.md](weber-28-35/troubleshooting.md) or [s21-engine/diagnosis-guide.md](s21-engine/diagnosis-guide.md). Look for a case like yours in the owner reports.
- **Setting up or tuning:** [weber-28-35/tuning.md](weber-28-35/tuning.md) (what each jet does, re-jetting, economy vs power, modern fuel, an 11-step procedure from the factory baseline), [idle-and-mixture.md](weber-28-35/idle-and-mixture.md), [cold-start-device.md](weber-28-35/cold-start-device.md), [linkage-and-pump.md](weber-28-35/linkage-and-pump.md), [adjustment-procedures.md](weber-28-35/adjustment-procedures.md).
- **Rebuilding the carb:** [weber-28-35/overhaul-guide.md](weber-28-35/overhaul-guide.md), [wear-and-inspection.md](weber-28-35/wear-and-inspection.md), [rebuild-kits.md](weber-28-35/rebuild-kits.md), [interchangeability.md](weber-28-35/interchangeability.md). If the carb has just been cleaned or rebuilt and now runs worse, use [weber-28-35/after-cleaning-checklist.md](weber-28-35/after-cleaning-checklist.md).
- **Looking up a value:** "Quick reference" below.

## Diagnose by symptom

Owner reports repeat two lessons:
- **Rule out ignition and fuel supply before blaming the carb.** About 1 case in 7 blamed on the carb was really plugs, condensers, HT leads or timing. Timing is easily lost after oil-pump or distributor work, because the oil pump drives the distributor.
- **On the 28/35, check the EZ-20 idle cut-off solenoid early.** With no power, there is no idle at all.

| Symptom | Check first | Then | Details |
|---|---|---|---|
| **Won't start** | Spark and timing (firing order 1-2-4-3); fuel reaching the carb; plugs wet or dry | Float/needle (flooding); cold-start device; jets blocked | [troubleshooting §1](weber-28-35/troubleshooting.md), [engine diagnosis](s21-engine/diagnosis-guide.md) |
| **Starts, then dies** | Solenoid power (+12 V with ignition on, click test); fuel pump (sticking, valves) | Idle jet (45 on the solenoid tip) blocked or broken; vacuum leak at the base or spacer | [troubleshooting §2](weber-28-35/troubleshooting.md), [solenoid](weber-28-35/solenoid-ez20.md) |
| **No idle, or hunting idle** | Solenoid and its idle jet; vacuum leaks (base gaskets, phenolic spacer, hoses) | Mixture and idle screws; ignition (points, dwell 65°, timing); valve clearances | [troubleshooting §3](weber-28-35/troubleshooting.md) |
| **Runs on after switch-off** | Solenoid feed permanently live, or a plain jet fitted instead of the solenoid | Idle speed too high; carbon or overheating | [troubleshooting §4](weber-28-35/troubleshooting.md) |
| **Floods or leaks fuel** (fuel from the manifold drain holes) | Float level (6.25–6.75 mm S2A1, no gasket); needle valve; holed float (more than 18 g) | Fuel pump pressure (spacer missing, electric pump) | [troubleshooting §5](weber-28-35/troubleshooting.md) |
| **Hesitation, flat spot, no power** | Accelerator pump squirt; secondary opening; air filter | Main jets/emulsion tubes; float low; ignition advance; fuel supply at high flow | [troubleshooting §6](weber-28-35/troubleshooting.md) |
| **Backfire into the carb** | Lean mixture (vacuum leak, low float, blocked jet) | Timing too advanced; tight intake valve | [troubleshooting §7](weber-28-35/troubleshooting.md) |
| **Black smoke, high consumption** | Cold-start device not returning; float high or needle leaking | Jets enlarged or wrong; mixture screw; air filter blocked | [troubleshooting §8](weber-28-35/troubleshooting.md) |
| **Dies when hot, hard hot start** | Vapour lock: fuel lines near the exhaust, heat shield, spacer | Float level; condenser or coil failing hot | [troubleshooting §9](weber-28-35/troubleshooting.md) |
| **Overheating, knocking, oil pressure, smoke, noises** | Engine side | — | [s21-engine/common-problems.md](s21-engine/common-problems.md), [owner reports](s21-engine/owner-reports.md) |
| **Electrical oddities** (false gauge readings, no charge, intermittent stalling) | Earths: engine to body, battery earth (a painted clutch housing left one engine with no earth) | Senders, regulator, ignition switch | [s21-engine/electrics.md](s21-engine/electrics.md) |

**For a GAZ-69 with an S-21,** also go through the swap checklist at the end of [s21-engine/gaz69-s21-owner-reports.md](s21-engine/gaz69-s21-owner-reports.md). It covers the throttle linkage, cooling, crank pulley and water pump, exhaust clearance, fuel pump type and the carb spacer.

## Identify your 28/35 variant

| Check | S2A / S2A1 | S2B1 (from 1991–92) |
|---|---|---|
| Marking on body | "28/35 S2A" (often with GN.1113) | "28/35 S2B1" |
| Secondary main jet / air jet | 145 / 225 | 125 / 220 |
| Economiser feeding throat II (jet 80, nozzle 2.5) | no | **yes** |
| Mixture screw | adjustable | sealed with a cap (often missing on old carbs) |
| Float level | 6.25–6.75 mm | 7 ±0.25 mm |

Factory documents use "S2A" and "S2A1" for the same calibration. Details: [weber-28-35/variants.md](weber-28-35/variants.md).

## Quick reference

| Item | Value | Source |
|---|---|---|
| **28/35 S2A1 jets I / II** | Main 110/145, air 250/225, tubes F27/F35 | Factory: Żuk parts catalogue 1988, Żuk manual 1989 |
| 28/35 venturis I / II | 21 / 26 (aux. 4.5 / 4.5) | Factory |
| Idle jets | 45 (on the EZ-20 tip) / 100 secondary progression; idle air 175 / 80; mixture jet 170 | Factory |
| Accelerator pump | Jet 40, valve 80, stroke 10 mm, 5 cm³ per 10 strokes | Factory |
| Needle valve; float mass | 175; about 18 g | Factory |
| **Float level** | S2A/S2A1: 6.25–6.75 mm; S2B1: 7 ±0.25 mm; cover vertical, no gasket | Book (Wiejak & Zagaja) + 1994 manual |
| Idle speed | 600–800 rpm | Factory |
| EZ-20 solenoid | Fed from the coil's + terminal with the ignition on; part 033845, idle jet 033842 (45) | Factory |
| Firing order | **1-2-4-3** (every manual; 1-3-4-2 is the Andoria diesel) | Factory |
| Points gap / dwell | 0.35–0.45 mm / 65° ± 4° | Factory (Żuk 1985, 1989) |
| Static timing | **8° ± 1° BTDC** for 85/86-octane fuel (Żuk 1985/1989). 5° ± 1° was the setting for 78-octane. Confirm with the factory road test. | Factory |
| Spark plug | Iskra F75 (M14×1.25, 12.7 mm reach, heat value 225–240); gap about 0.6 mm | Factory (Żuk 1985) |
| Valve clearance, cold | **Intake 0.20–0.22 / exhaust 0.30–0.32 mm** | Factory (every manual) |
| **Head bolt torque** | **110–120 Nm cold**, spiral from the centre; re-torque after about 1,500 km | Factory (all five manuals) |
| Main bearings / big ends / flywheel | 121–133 / 67–74 / 75–81 Nm | Factory (Warszawa 1965) |
| Compression | New 10–11 kG/cm²; limit 9; max 7 % difference between cylinders | Factory |
| Oil pressure | 0.1–0.5 MPa; hot idle minimum about 0.8 kG/cm² | Factory |
| Fuel pump pressure | 0.2–0.285 kG/cm² | Factory (Warszawa 1965) |
| Thermostat | Opens about 71–83 °C (TS-3) | Factory (Żuk 1985) |
| All engine values with pages | [s21-engine/factory-service-data.md](s21-engine/factory-service-data.md) | — |

## Folder contents

### `weber-28-35/`: your carburettor
- [after-cleaning-checklist.md](weber-28-35/after-cleaning-checklist.md): what to check if the carb runs worse after a clean or rebuild.
- [troubleshooting.md](weber-28-35/troubleshooting.md): by symptom (won't start, no idle, dies, runs on, floods, hesitation, backfire, black smoke, dies when hot).
- [owner-reports.md](weber-28-35/owner-reports.md): 51 owner cases (37 carried over, 14 new). Each is marked confirmed or suggested, has a short Polish quote, and contradictions with factory data are flagged. The file ends with a "Patterns" ranking.
- [solenoid-ez20.md](weber-28-35/solenoid-ez20.md): how the solenoid works, wiring, tests, substitutes.
- [specs-and-jets.md](weber-28-35/specs-and-jets.md): full factory tables for the S2A/S2A1 and S2B1, float-level resolution, part numbers.
- [variants.md](weber-28-35/variants.md): timeline, S2A1 vs S2B1, how to identify yours.
- [how-it-works.md](weber-28-35/how-it-works.md), [adjustment-procedures.md](weber-28-35/adjustment-procedures.md).
- [rebuild-kits.md](weber-28-35/rebuild-kits.md):
  - **Best match:** ETER-MOT "Weber 28/35 S2A1 zestaw naprawczy" at about 320 zł. It has gaskets, diaphragms and small parts; confirm the contents with the seller first.
  - **EZ-20 solenoid:** about 320 zł new or 120 zł regenerated.
- **Tuning and setup:**
  - [tuning.md](weber-28-35/tuning.md)
  - [idle-and-mixture.md](weber-28-35/idle-and-mixture.md): the mixture screw turned in is leaner; three sources agree.
  - [cold-start-device.md](weber-28-35/cold-start-device.md)
  - [linkage-and-pump.md](weber-28-35/linkage-and-pump.md): includes adapting the GAZ-69 pedal linkage.
  - Some reference values (idle CO 1.2–2 %, pump output, secondary checks) come from the sister **34 DCHD** carb in the 1982 Fiat 125p book. They are marked RELATED.
- **Overhaul and parts:**
  - [overhaul-guide.md](weber-28-35/overhaul-guide.md)
  - [wear-and-inspection.md](weber-28-35/wear-and-inspection.md): throttle spindle play is the main wear point. The pump is a **piston, not a diaphragm**.
  - [interchangeability.md](weber-28-35/interchangeability.md): the cover and base gaskets share part numbers with the Fiat 125p/Polonez set. It also covers substitute carbs.
- **Background:**
  - [history-and-makers.md](weber-28-35/history-and-makers.md)
  - [ownership-experience.md](weber-28-35/ownership-experience.md): fuel use of 9–11 l/100 km on the road; owner improvements; the Weber can stall on steep tilts.
- [videos.md](weber-28-35/videos.md).
- `images/`: factory parts-catalogue and bulletin pages, manual pages, book figures, kit and solenoid photos. `t-`, `o-`, `u-` and `w-images.md` list the source of each image.
- `sources-technical.md`, `sources-owner.md`, `sources-tuning.md`, `sources-broad.md`: every URL used.

### `s21-engine/`: the engine
- [factory-service-data.md](s21-engine/factory-service-data.md): **factory values with manual and page**, covering torques, timing and advance curve, dwell, compression, plugs, valves, oil, cooling and the fuel pump. It supersedes the older specs file.
- [electrics.md](s21-engine/electrics.md): earths (a painted clutch housing left one engine with no earth), charging, starter, ignition switch, senders, and the factory test-lamp fault-finding procedure.
- [fuel-and-conditions.md](s21-engine/fuel-and-conditions.md): modern unleaded fuel, E10, LPG, factory cold-start procedure.
- [specs-and-service-data.md](s21-engine/specs-and-service-data.md): older collection of forum and club values.
- [diagnosis-guide.md](s21-engine/diagnosis-guide.md): no-start and rough-running order.
- [common-problems.md](s21-engine/common-problems.md) and [owner-reports.md](s21-engine/owner-reports.md): 73 owner cases by symptom, with "Patterns" and "Lessons owners repeat". [owner-reports-2.md](s21-engine/owner-reports-2.md) adds 11 more, mostly electrics and fuel.
- [gaz69-swap.md](s21-engine/gaz69-swap.md) and [gaz69-s21-owner-reports.md](s21-engine/gaz69-s21-owner-reports.md): two S-21 GAZ-69s followed over 2–4 years, with a swap checklist.
- [ignition-and-mods.md](s21-engine/ignition-and-mods.md), [parts-sources.md](s21-engine/parts-sources.md), [videos.md](s21-engine/videos.md), and the `sources*.md` files.
- `images/`: head bolt order, valve adjustment, TDC mark, pumps, owner photos, GAZ-69 swap photos.

### `weber-34s2b1/`: the older carburettor, for reference only
The older 34S2B1 (Nysa 1977, Żuk 1985) has no solenoid, 34/34 bores, a 5–5.5 mm float level and main jets 120/150. Its files are kept because some owner cases and factory pages overlap.

## Notes

- **Polish originals:** the files carry short original-Polish quotes next to the English. Full source page texts were saved outside this repo for personal reference.
- **Images:** factory pages come from archive.org scans. Forum and shop photos belong to their authors and are credited in the images lists; they are here for personal reference only.
- **Gaps:**
  - no factory CO value, and no factory starting turns for the mixture screw;
  - the S2B1 economiser layout is not described anywhere;
  - elektroda.pl was unreachable;
  - no video shows a 28/35 strip-down.
