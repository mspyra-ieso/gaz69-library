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

## Start here: "it ran, someone cleaned the carb, now it won't run"

In owner reports, a no-start after cleaning a 28/35 is usually a **reassembly mistake**, not a worn-out carburettor. Work top to bottom and stop when the engine runs. The full version is [weber-28-35/after-cleaning-checklist.md](weber-28-35/after-cleaning-checklist.md).

1. **Rule out what the job may have disturbed outside the carb.** This takes about 10 minutes.
   - In owner reports, about **1 case in 7 blamed on the carb was really ignition or plugs**: brand-new plugs (ISKRA, three times), new condensers or HT leads.
   - **Timing** is easily lost after oil-pump or distributor work, because the oil pump drives the distributor. Firing order is 1-2-4-3.
   - **Fuel delivery:** disconnect the hose at the carb and crank. There should be strong pulses.
   - On the GAZ-69 swap, an **electric pump must be low-pressure**. The S-21 has no return line, and too much pressure floods the carb.
   - See [s21-engine/diagnosis-guide.md](s21-engine/diagnosis-guide.md).
2. **The EZ-20 solenoid comes first** among the carb checks. With no power, a spring-loaded needle shuts the idle jet, so there is **no idle at all**, although the engine may still run on throttle.
   - With the ignition on, it needs **+12 V**. Factory wiring takes it from the coil's + (low-tension) terminal.
   - **Click test:** pull the wire off and touch it back on; you should hear a click.
   - On a swap, the wire may be unconnected, corroded or permanently live. A permanent feed makes the engine run on after switch-off.
   - The **45 idle jet on the solenoid's tip** must be present and not snapped off, and its sealing ring must be intact.
   - **Get-you-home fix (factory, 1989):** remove the needle and refit the holder with the jet. The engine will idle but may run on after switch-off.
   - See [weber-28-35/solenoid-ez20.md](weber-28-35/solenoid-ez20.md).
3. **Quick checks with the air filter off:**
   - the accelerator pump squirts when the throttle is opened;
   - the cold-start lever moves through its full travel and returns fully;
   - both throttle plates close;
   - the secondary opens through its linkage;
   - no vacuum leaks: base gaskets, the **phenolic spacer** (a cracked one caused lean pinking on another S-21 GAZ-69), the vacuum-advance hose and the breather hose.
4. **Lift the top cover and check the reassembly.** Factory 28/35 S2A1 values:

   | Throat | Main jet | Air correction | Emulsion tube | Idle |
   |---|---|---|---|---|
   | **I (28 mm, primary)** | **110** | **250** | **F27** | 45 on the solenoid tip |
   | **II (35 mm, secondary)** | **145** (S2B1: 125) | **225** (S2B1: 220) | **F35** | 100 (progression) |

   - **Jets swapped between throats** is the commonest cleaning error.
   - **Float level:** **6.25–6.75 mm** on the S2A/S2A1, or **7 ±0.25 mm** on the S2B1. Measure with the cover held vertical, **without the gasket**, and without pressing in the needle's damper ball.
   - **Float condition:** a good float weighs about 18 g. A heavier one (24 g was reported) is holed and full of fuel.
   - **Needle valve:** 175, seated and free.
   - **Small parts present:** the accelerator-pump nozzle and its ball, the pump valve, plungers, springs and retainers, the inlet filter.
   - **Passages truly clear.** Blow them through with air; never use wire. One owner needed a second, deep soak before it ran.
   - **Gaskets** single and complete.
   - See [weber-28-35/specs-and-jets.md](weber-28-35/specs-and-jets.md).
5. **Base settings:**
   - Screw the idle mixture screw gently fully in, then back it out **2 turns** (enthusiast-site figure; there is no factory starting value). **Screwing in makes it leaner.** One forum post says the opposite; it is wrong.
   - Set idle hot to **600–800 rpm**.
   - See [weber-28-35/adjustment-procedures.md](weber-28-35/adjustment-procedures.md).
6. **Floods?**
   - Check the float level, then the needle valve, then whether the float is holed.
   - Fuel coming out of the **two small drain holes in the intake manifold** means the carb is overflowing. Don't block them.
   - High fuel-pump pressure also floods the carb. This happens if the pump's insulating spacer is missing, or with an electric pump.
7. **Still stuck?**
   - Go through [weber-28-35/troubleshooting.md](weber-28-35/troubleshooting.md) by symptom.
   - Look for a case like yours among the 51 owner cases in [weber-28-35/owner-reports.md](weber-28-35/owner-reports.md).
   - For engine-side causes, see [s21-engine/owner-reports.md](s21-engine/owner-reports.md).
   - For swap-specific issues, see [s21-engine/gaz69-s21-owner-reports.md](s21-engine/gaz69-s21-owner-reports.md), which ends with a swap checklist.

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
- [after-cleaning-checklist.md](weber-28-35/after-cleaning-checklist.md): step by step for your exact situation.
- [troubleshooting.md](weber-28-35/troubleshooting.md): by symptom (won't start, no idle, dies, runs on, floods, hesitation, backfire, black smoke, dies when hot).
- [owner-reports.md](weber-28-35/owner-reports.md): 51 owner cases (37 carried over, 14 new). Each is marked confirmed or suggested, has a short Polish quote, and contradictions with factory data are flagged. The file ends with a "Patterns" ranking.
- [solenoid-ez20.md](weber-28-35/solenoid-ez20.md): how the solenoid works, wiring, tests, substitutes.
- [specs-and-jets.md](weber-28-35/specs-and-jets.md): full factory tables for the S2A/S2A1 and S2B1, float-level resolution, part numbers.
- [variants.md](weber-28-35/variants.md): timeline, S2A1 vs S2B1, how to identify yours.
- [how-it-works.md](weber-28-35/how-it-works.md), [adjustment-procedures.md](weber-28-35/adjustment-procedures.md).
- [rebuild-kits.md](weber-28-35/rebuild-kits.md):
  - **Best match:** ETER-MOT "Weber 28/35 S2A1 zestaw naprawczy" at about 320 zł. It has gaskets, diaphragms and small parts; confirm the contents with the seller first.
  - **EZ-20 solenoid:** about 320 zł new or 120 zł regenerated.
- [videos.md](weber-28-35/videos.md).
- `images/`: factory parts-catalogue and bulletin pages, manual pages, book figures, kit and solenoid photos. `t-images.md` and `o-images.md` list the source of each image.
- `sources-technical.md`, `sources-owner.md`: every URL used.

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
