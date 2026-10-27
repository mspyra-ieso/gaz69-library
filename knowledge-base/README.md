# S-21 engine and Weber carburettor knowledge base

This knowledge base is for an FSO **S-21** engine (2.12 L OHV, about 70 hp) with a Polish-made **Weber** twin-throat carburettor, fitted in a **GAZ-69**. It was compiled in October 2026 from:
- factory Żuk and Nysa owner's manuals (archive.org),
- the FSO manuals in this repo,
- Polish owner forums, mainly forum.polskiedostawczaki.pl, zlombol.pl, elektroda.pl and drive2.ru,
- shops and videos.

Every fact links to its source. Each file labels its sources as one of:
- **[DOC] / [FACTORY]**: manuals and documented data.
- **[FORUM]**: owner experience.
- **[GENERAL]**: general carburettor practice.

Owners almost never write the carburettor's model code; they just say "Weber" or "gaźnik". A post counts as relevant when the vehicle is a Żuk, Nysa, Tarpan, Warszawa 223/224, or a GAZ-69 with an S-21.

## Start here: "it ran, someone cleaned the carb, now it won't run"

Work top to bottom. Stop when the engine runs.

1. **Identify the carburettor** (next section). Three of the commonest forum tips (solenoid, choke flap, 6.5 mm float) only apply to the later 28/35.
2. **Rule out what the cleaning may have disturbed outside the carb.** In owner reports, about **1 case in 7 blamed on the carb was really ignition or plugs**: brand-new plugs (ISKRA three times), new condensers, or HT leads. **Timing** is often lost after oil-pump or distributor work, because the oil pump drives the distributor. This takes about 10 minutes:
   - **Spark:** a strong blue spark jumping a few mm.
   - **Timing:** was the distributor or fuel pump moved? Firing order is 1-2-4-3.
   - **Fuel delivery:** disconnect the hose at the carb and crank. There should be strong pulses.
   - **Plugs:** dry or wet tells you whether you have no fuel or flooding.
   - See [s21-engine/diagnosis-guide.md](s21-engine/diagnosis-guide.md), sections 0–3.
3. **Quick on-engine carb checks, air filter off:**
   - the accelerator pump squirts when you open the throttle;
   - the cold-start knob moves the starter device through its full travel and fully back;
   - both throttle plates close;
   - no vacuum leaks: base gasket, insulator spacer, vacuum-advance hose, breather hose.
   - See [weber-34s2b1/after-cleaning-checklist.md](weber-34s2b1/after-cleaning-checklist.md), section B.
4. **Lift the top cover and check the reassembly.** These are the commonest post-cleaning faults reported by owners:
   - **Jets in the wrong holes.** On the 34S2B1 the main jets are **120 primary / 150 secondary**; they must not be swapped. Emulsion tubes F30/F30. Idle jets 50/50. Air jets 210/210.
   - **Float setting: 5–5.5 mm**, cover held vertical (factory, 34S2B1). Float moves freely. Needle valve seated and not stuck.
   - **Small parts present:** pump nozzle and its ball, pump valve, springs and retainers, the inlet filter.
   - **Passages truly clear.** Blow through with air; never use wire. One owner only got theirs running after a second deep clean.
   - **Gaskets single, complete, and not blocking passages.**
   - See [weber-34s2b1/after-cleaning-checklist.md](weber-34s2b1/after-cleaning-checklist.md), section C, and [weber-34s2b1/specs-and-jets.md](weber-34s2b1/specs-and-jets.md).
5. **Base settings to get it running:**
   - Idle mixture screw: seat it gently, then back out about **2–3 turns**. The factory gives about 3 turns; a healthy unit usually ends up 0.5–1.25 turns out. **In = leaner.**
   - Open the idle-speed screw enough to keep the engine running.
   - Final adjustment hot, on the **primary only**.
   - See [weber-34s2b1/adjustment-procedures.md](weber-34s2b1/adjustment-procedures.md).
6. **Floods?**
   - Screw the mixture screw fully in. If the engine still runs, fuel is getting past the float or needle.
   - Fuel coming out of the **two small drain holes in the intake manifold** means the carb is overflowing. Don't block them.
   - See [weber-34s2b1/troubleshooting.md](weber-34s2b1/troubleshooting.md).
7. **Still stuck?** Go through the symptom tables in [weber-34s2b1/troubleshooting.md](weber-34s2b1/troubleshooting.md), [weber-34s2b1/forum-experiences.md](weber-34s2b1/forum-experiences.md) and [weber-34s2b1/owner-reports.md](weber-34s2b1/owner-reports.md). For engine-side causes, see [s21-engine/owner-reports.md](s21-engine/owner-reports.md). For GAZ-69-specific swap issues, see [s21-engine/gaz69-s21-owner-reports.md](s21-engine/gaz69-s21-owner-reports.md), which ends with a swap checklist. On the GAZ-69 swap, also check the crankcase breather valve linkage worked from the carb throttle spindle.

## Identify your carburettor

The model code is cast or stamped on the body or the float-chamber cover.

| What you see | Likely type | Notes |
|---|---|---|
| Both throats 34 mm, equal size; **no electrical solenoid** on the body; a round **cold-start (starter) device worked by a cable** on the side; secondary throttle opened by a **lever from the primary spindle** | **34S2B1** (factory type, Nysa 1977 / Żuk 1985) | Factory data in [weber-34s2b1/specs-and-jets.md](weber-34s2b1/specs-and-jets.md), Table 1 |
| As above, but a **diaphragm pot with a hose and rod to the secondary throttle** | Vacuum-secondary variant (forum says **34S2A1**; unconfirmed) | Jets per one book: main 125/145 |
| Throats **unequal** (21/26 mm venturis), **electrical idle cut-off solenoid** (one wire) | **28/35 S2A** (1989) or **28/35 S2B1** (1994, adds an economiser) | Solenoid needs +12 V with the ignition on, or there is no idle |

Earlier on, we believed the 34S2B1 had a vacuum-opened secondary. The factory manuals say its secondary is **mechanically** linked. Check your carburettor to see which you have. Details are in [weber-34s2b1/variants-and-history.md](weber-34s2b1/variants-and-history.md).

## Quick reference

| Item | Value | Source |
|---|---|---|
| **34S2B1 main jets I / II** | 120 / 150 | Factory, Żuk 1985 + Nysa 1977 |
| 34S2B1 venturis, air jets, emulsion tubes | 25/25, 210/210, F30/F30 | Factory |
| 34S2B1 idle jets | 50 / 50 | Factory |
| 34S2B1 pump jet; needle valve | 70; 175 | Factory |
| 34S2B1 float setting | 5–5.5 mm (cover vertical); float travel 8.5 mm | Factory |
| Idle speed | 600–800 rpm (Żuk 1985); 550–650 (Nysa 1977) | Factory |
| Firing order | 1-2-4-3 | Club manual extract + owners |
| Points gap | 0.4 ± 0.05 mm | Club manual extract |
| Plug gap | 0.6–0.7 mm | Club manual extract |
| Valve clearance, cold | Intake 0.20–0.22 / exhaust 0.25–0.30 mm | Club manual extract |
| Static timing | 7° BTDC (5° in another source); TDC ball or hole on the flywheel, seen through the bellhousing window | Conflict; check the FSO manuals |
| Head bolt torque | **No factory S-21 figure found.** Owners use 120–130 Nm; the only published figure, 66–71 Nm, is for the M-20. **Check the FSO repair manual before using either.** | Conflict |
| Dwell, compression | **Not found online.** Check the FSO repair manuals in this repo | — |

## Folder contents

### `weber-34s2b1/`: the carburettor
- [variants-and-history.md](weber-34s2b1/variants-and-history.md): which variant was fitted when; 34S2B1 vs 34S2A1/A2 vs 28/35.
- [specs-and-jets.md](weber-34s2b1/specs-and-jets.md): full jet and calibration tables per variant, with conflicts flagged.
- [how-it-works.md](weber-34s2b1/how-it-works.md): circuits, the starter device, the secondary linkage.
- [adjustment-procedures.md](weber-34s2b1/adjustment-procedures.md): float level, idle, starter device, factory steps.
- [after-cleaning-checklist.md](weber-34s2b1/after-cleaning-checklist.md): a 19-step checklist for your exact situation.
- [troubleshooting.md](weber-34s2b1/troubleshooting.md): by symptom, with a table of short Polish original quotes.
- [forum-experiences.md](weber-34s2b1/forum-experiences.md): real symptom → fix cases, each with a link and a short Polish quote.
- [owner-reports.md](weber-34s2b1/owner-reports.md): 27 more owner cases (Żuk, Nysa, Warszawa) from other threads and forums. Marked confirmed or suggested, with advice that contradicts factory data flagged, and ending in a "Patterns" ranking.
- [rebuild-kits.md](weber-34s2b1/rebuild-kits.md): kits, sellers, prices. Best match found: ETER-MOT 34S2A1/34S2B1 kit, about 320 zł; ask the seller to confirm the type first.
- [videos.md](weber-34s2b1/videos.md).
- `images/`: factory manual pages (jet tables, float drawings, exploded views, fault table), gasket shapes, forum photos. `a-images.md` and `b-images.md` list the source of each image.
- `sources-technical.md`, `sources-troubleshooting.md`: every URL used.

### `s21-engine/`: the engine
- [specs-and-service-data.md](s21-engine/specs-and-service-data.md)
- [diagnosis-guide.md](s21-engine/diagnosis-guide.md): no-start and rough-running order.
- [common-problems.md](s21-engine/common-problems.md): overheating (corroded head water tube), points, timing gear, oil pump, fuel pump.
- [owner-reports.md](s21-engine/owner-reports.md): 73 owner cases by symptom (ignition and timing, cooling, fuel supply, head gasket, oil pressure, noises, LPG), with "Patterns" and "Lessons owners repeat".
- [gaz69-swap.md](s21-engine/gaz69-swap.md): firewall clearance, mounts, bellhousing.
- [gaz69-s21-owner-reports.md](s21-engine/gaz69-s21-owner-reports.md): two GAZ-69s with S-21 swaps followed over 2–4 years (drive2.ru logbooks). Covers the water pump and crank pulley, throttle linkage, air filter, exhaust, breather, electrics and military conversions, and ends with a swap checklist.
- [ignition-and-mods.md](s21-engine/ignition-and-mods.md): electronic ignition options.
- [parts-sources.md](s21-engine/parts-sources.md), [videos.md](s21-engine/videos.md), [sources.md](s21-engine/sources.md).
- `images/`: head bolt order, valve adjustment, TDC mark, points gap, fuel and oil pumps, GAZ-69 swap photos (`images.md` lists the sources).

## Notes

- **Polish originals:** the files carry short original-Polish quotes next to the English. Full source page texts were saved outside this repo for personal reference.
- **Images:** factory manual pages come from scans on archive.org. Forum and shop photos belong to their authors and are credited in the images lists; they are here for personal reference only.
- **Gaps:** no factory data for the 34S2A1/A2 or the 34S2C, and no factory idle CO. No S-21 head bolt torque online. No video specifically on the 34S2B1.
