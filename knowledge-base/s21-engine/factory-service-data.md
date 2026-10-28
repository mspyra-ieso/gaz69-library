# S-21: Factory Service Data (from the manuals)

This page fills the gaps in `specs-and-service-data.md`. Every value here comes from a **factory or factory-authorised document**. Forum figures are kept only in the "conflicts" section, for comparison.

**Where this page and `specs-and-service-data.md` disagree, this page wins**, because it quotes the manuals directly.

## Source key

Page images are in `images/` and listed in `images/factory-images.md`. "PDF p." is the page number in the archive.org PDF viewer; "pr. p." is the number printed on the page.

| Key | Document | Where |
|---|---|---|
| **W65** | *Obsługa i bieżące naprawy samochodu FSO-Warszawa, Część 1 i 2: wiadomości ogólne i silnik górnozaworowy* (SIMP/FSO training manual, 1965). Part II covers the **S21 engine**. | Local scan `gaz69_library/Obsługa i bieżące naprawy … Część 1 i 2 ( PL 1965 r.)/`. The file number is given as `000N.jpg`. |
| **W66e** | Same series, *Część 4b i 5* (1966), Part VI "Instalacja elektryczna" | Local scan `… Część 4b i 5 ( PL 1966 r.)/` |
| **Ż74** | FSC Lublin, *Instrukcja obsługi samochodu Żuk*, 1974. It has M-20 and S-21 columns side by side. | https://archive.org/download/fsc-lublin-instrukcja-obslugi-zuk/FSC_LUBLIN-1974-instrukcja_obslugi_Zuk.pdf |
| **Ż85** | FSC Lublin, Żuk owner's manual, 1985 | …/FSC_LUBLIN-1985-instrukcja_obslugi_Zuk.pdf |
| **Ż89** | FSC Lublin, Żuk owner's manual, 1989 | …/FSC_LUBLIN-1989-instrukcja_obslugi_Zuk.pdf |
| **Ż94** | FSC Lublin, Żuk owner's manual, 1994. Covers the S-21 with **contactless ignition** and the Andoria 4C90 diesel. | …/FSC_LUBLIN-1994-instrukcja_obslugi_Zuk.pdf |
| **N77** | ZSD, *Instrukcja obsługi Nysa 522*, 1977 | https://archive.org/download/zsd-1977-instrukcja-obslugi-nysa-522/ZSD-1977-instrukcja_obslugi_Nysa_522.pdf |

Confidence ratings:
- **High**: two or more factory documents agree, or one clear factory table.
- **Medium**: one factory source, or a value that changed over the years.
- **Low**: factory text, but the OCR or units are ambiguous.

Unit conversions used throughout: 1 kGm = 9.81 Nm; 1 kG/cm² ≈ 0.98 bar ≈ 0.1 MPa.

## 1. Master table

| Item | Factory value | Source (page) | Confidence |
|---|---|---|---|
| **Firing order** | **1-2-4-3** | W65 pr. p.6 (file 0010); Ż74 pr. p.12; Ż85 pr. p.61; Ż89 pr. p.11; Ż94 pr. p.30; N77 p.14 | High |
| Cylinder no. 1 | At the radiator end: "przy chłodnicy" | W65 pr. p.6 | High |
| **Head bolt/nut torque** | **11–12 kGm = 110–120 Nm**, tightened **cold** in the spiral sequence. W65: first all to **about 5 kGm (≈50 Nm)**, then finally to 11–12 kGm. Ż89/Ż94: "Moment dokręcania śrub wynosi 110...120 Nm". | W65 Table 7-2 pr. p.88 (file 0094); Ż74 pr. p.36 ("11...12 kGm"); Ż85 §4.1.1 ("11–12 daN·m"); Ż89 pr. p.36; Ż94 PDF p.51 | **High** |
| Head re-torque | Ż: **mandatory at the running-in service OTD (1500 ± 200 km)**, and whenever loose. W65: **after every head removal, re-torque after 500 km**, then readjust the valves. Always re-set the valve clearances after re-torquing. | Ż89 pr. p.36; W65 pr. p.10 Table 2-1, note 1 (file 0014) | High |
| **Head bolt sequence** | 11 fasteners in a spiral from the centre outwards. Bottom row: 9, 5, 1, 4, 8. Top row: 7, 3, 2, 6. End bolts: 11 (left on the drawing) and 10 (right). Same figure in W65 (Rys. 7-5) and Żuk (Rys. 4.4 / 4.3). | W65 pr. p.90 (file 0096); Ż89 pr. p.38; Ż94 PDF p.51 | High |
| Head fastener type | **W65 (Warszawa, 1965): studs with nuts** ("11 śrub dwustronnych głowicy", "Nakrętka śruby dwustronnej"). **Żuk 1985 and later: bolts**, in four lengths: M14×115, M14×119, M14×132 and M14×175, each marked by a symbol on the drawing. Ż74 still says "nakrętki" (nuts). | W65 Table 7-1 pr. p.85 (file 0091); Ż89 Table 4.4 pr. p.38 | High (it changed over time) |
| **Main bearing cap bolts** | **12.3–13.6 kGm = 121–133 Nm** | W65 Table 7-2 pr. p.88 | High (one clear table) |
| **Big-end (con-rod) nuts** | **6.8–7.5 kGm = 67–74 Nm** | W65 Table 7-2 | High |
| Flywheel bolt nuts | 7.6–8.3 kGm = 75–81 Nm | W65 Table 7-2 | High |
| Clutch pressure-plate bolts | 1.5–2.0 kGm = 15–20 Nm | W65 Table 7-2 | High |
| Compression ratio | 7.5 (M-20: 6.8) | Ż74 pr. p.12; W65 pr. p.6 | High |
| **Compression pressure, new** | **10–11 kG/cm² (≈10–11 bar)**. Ż85/Ż89/Ż94 give 1–1.1 MPa. **Ż74 and N77 give 9–10 kG/cm².** | W65 pr. p.6 & Table 11-6 pr. p.99; Ż89 pr. p.11; Ż74 pr. p.12; N77 p.14 | High |
| **Compression limit** | **9 kG/cm² is the minimum acceptable ("dopuszczalna")**. Maximum spread between cylinders is **7 %** of the average. Below that, wear has increased. | W65 Table 11-6 pr. p.99 (file 0105) | High (single source, clear table) |
| Compression test method | Engine at **70 ± 10 °C**, battery charged, **all plugs out**, **throttle fully open**, gauge pressed in with about 20 kG force, crank for **5 s**. Correct the reading for air pressure: p × 760 / B (B = barometer reading in mmHg). Check valve clearances first. | W65 Table 11-5 pr. p.99 | High |
| **Valve clearance, cold (~20 °C)** | **Intake 0.20–0.22 mm, exhaust 0.30–0.32 mm** | W65 pr. p.9 & Table 7-6; Ż74; Ż85; Ż89 pr. p.12 & p.36; Ż94 pr. p.31; N77 p.15 | **High** (every factory document agrees) |
| Valve clearance, hot (~80 °C) | **Intake 0.30–0.38 mm, exhaust 0.40–0.45 mm** | W65 Table 7-6 pr. p.91 (file 0097) | Medium (one source) |
| Valve-adjust order | With cyl 1 at TDC on compression, adjust cyl 1. Turn the crank 180° to the next point opening, adjust cyl 2, then 4, then 3. Two-position shortcut (footnote): at cyl 1 TDC set both cyl 1 valves plus **intake 3 and exhaust 2**. Turn the crank 360° and set both cyl 4 valves plus **intake 2 and exhaust 3**. | W65 Table 7-5 and footnote pr. p.91–92 | High |
| Valve timing (as printed) | Intake opens 48° BTDC, closes 84° ABDC. Exhaust opens 86° BBDC, closes 36° ATDC. The abbreviations differ between books: W65 writes ZW for TDC, Żuk writes ZZ for TDC. Not a field-check value. | W65 pr. p.9; Ż94 pr. p.31–32 | Medium |
| **Ignition timing (static)** | **Depends on fuel octane.** W65: **2–4° BTDC for 70-octane, 6–8° BTDC for 80-octane** (set 3° or 7°). Ż74: **5° ± 30′ BTDC** (table, for "not less than 78" octane), with the note that 85 octane is recommended for the S-21 **at 7°**. Ż85: "factory sets **5° ± 1° BTDC for 78-octane**; for 85-octane advance to **8° ± 1°**". Ż89: **8° ± 1°** at idle, fuel 86. N77: **7° BTDC**. Ż94 (contactless 44-84): **9° ± 1°**, fuel 86. | W65 pr. p.6 & Table 7-4 pr. p.91; W66e Table 93-1 pr. p.112; Ż74 pr. p.12–13; Ż85 pr. p.61; Ż89 pr. p.11 & p.51; N77 p.17; Ż94 pr. p.30 | **High**. See conflicts below. |
| Timing check method | Turn the engine with the crank handle until the rotor faces cyl 1's lead. Connect a 12 V test lamp from the coil's low-tension terminal to earth, ignition on. The **lamp lights as the points open**. Pointer on the flywheel scale at **8° before the mark**. To set: loosen screw 14 and turn the body slowly (left) until the lamp just lights. | Ż89 pr. p.51 (image `factory-zuk1989-timing-test-lamp-8deg-p51.jpg`) | High |
| Timing marks | A **steel ball pressed into the flywheel** marks cyl 1 TDC. It is visible through the window in the clutch housing, with a pointer (trzpień). The scale has **1° divisions up to 12°** on either side. A white-painted warning mark sits ahead of TDC. | W65 Table 7-5 note pr. p.91; Ż89 Rys. 4.16 pr. p.52 | High |
| Road test of timing | Engine warm, top (direct) gear, **55–60 km/h** on level road, then floor the throttle. A **brief, faint knock** means the timing is correct. Strong knock: retard. No knock at all: advance. | Ż89 pr. p.52 | High |
| Octane selector | **One division = 2° at the crankshaft** | W66e pr. p.139 | High |
| Distributor | Zelmot 44-44/II (W65/W66e). Ż74 calls the S-21 unit 44-44/IV. N77: 44-44/IV. Ż85/Ż89: 44-44. Ż94: **44-84 contactless**, with a Zelmot 4226 oil-filled coil and an H161 or GL118 module. The S-21 and M-20 units differ in the centrifugal curve, so do not swap them. | W65 pr. p.6 footnote; W66e Table 96-24; Ż74 pr. p.13; Ż94 pr. p.30 | High |
| **Centrifugal advance curve** (test bench, at **distributor-shaft** rpm) | 600 rpm: 0–2°. 1000 rpm: 4–6.5°. 1500 rpm: 10–12°. 1900 rpm: 10–12°. 2500 rpm: 10–12° (maximum 10–12°). | W66e Table 96-28 pr. p.143 (file 0148); Table 93-1 | Medium. **The units are not stated.** Distributor bench tables normally use *distributor* degrees and rpm, which means about **20–24° crank by about 3000 engine rpm**. That reading is an interpretation. |
| Vacuum advance | Maximum **5–7°**. The diaphragm must hold 250 mmHg, losing at most 25 mmHg in 1 min. | W66e Table 93-1; pr. p.143 | Medium |
| **Dwell angle** | **65° ± 4°**. This corresponds to a points gap of 0.35–0.45 mm. | Ż85 Table 2.1 and the strobe-diagnosis list ("kąt zwarcia styków przerywacza (65° ±4°)"); Ż89 pr. p.11 | Medium. Two Żuk manuals agree. The figure is unusually high for a 4-cylinder (many are about 50–55°), so if your meter disagrees, set the **gap** to 0.35–0.45 and time with a lamp or strobe. |
| Points gap | **0.35–0.45 mm** | all manuals | High |
| Points spring force | 540–650 g | W66e pr. p.143 | Medium |
| **Spark plug** | **M14×1.25, 12.7 mm reach, heat value 225–240 (Polish scale) / 75 (ISO).** Iskra **F75**. Equivalents listed: Bosch **W175T1**, Mogurt V-30, Isolator M14-225, PAL 14-8, USSR **A23**. W66e lists PAL Super 14-7. | Ż85 Table 4.4 pr. p.61; Ż74 pr. p.13 & p.49; W66e Table 93-1; N77 p.17 | **High** |
| Plug gap | Points ignition: **0.5–0.6 mm** (Ż74 text and table, N77), **0.6 mm** (W66e), or **0.6–0.7 mm** (Ż85). **Contactless (Ż94): 0.9 mm.** | as listed | High. The figure changed slightly over the years. |
| Plug replacement | Every **15,000 km**, or when the insulator is cracked or the electrodes are burnt | Ż85 pr. p.61 | High |
| **Idle speed** | **450–500 rpm** (W65, Ż74, N77 with Jikov carb). **N77 with WEBER carb: 550–650 rpm.** Ż85/Ż89/Ż94: **600–800 rpm**. | W65 pr. p.6; N77 p.15 ("550 ÷ 650 obr/min (dla gaźnika WEBER)"); Ż89 pr. p.11 | High |
| Idle adjust conditions | Coolant at **about 80 °C**. Check plugs, points gap and timing first. Mixture screw back 2–3 turns, then set the lowest even idle. A sharp blip must not stall it. | W65 Table 6-89 pr. p.84; Ż74 | High |
| **Oil pressure** | Ż89: **0.1–0.5 MPa** depending on rpm. Ż85: 0.1–0.55 MPa at 80 °C oil. Ż94: **minimum 0.1 MPa at idle**, 0.3–0.5 MPa running. Ż74/N77: **hot engine, minimum 0.8 kG/cm² at idle**, maximum 5.5 kG/cm² driving (oil at 80 °C). W65: **minimum 0.75 kG/cm² at 450–500 rpm**. | as listed; Ż89 pr. p.12; Ż94 pr. p.31; W65 pr. p.7 | High |
| Oil pressure after a rebuild | **At least 1.75 kG/cm² at 1000 rpm**, oil 60–90 °C, during running-in | W65 Ch. 8 pr. p.93 | Medium |
| Oil relief valve opens at | **3.5–4.0 kG/cm²** | W65 pr. p.7 (file 0011) | Medium |
| **Oil capacity** | **6 L** total system (W65 pr. p.7; Ż74 table pr. p.16 "6,0"). **Oil change refill: about 5 L** (Ż85 "about 5 dm³"; Ż89 "5 dm³"; N77 "about 5 l"; N77 table 5.0). | as listed | High. Use about 5 L at a change, then top up to the dipstick. |
| Oil grade (period) | W65: SAE 30 summer, SAE 20 winter, **SAE 20W/30** all-season. Ż94: **Selektol Special SD SAE 20W/40**. Ż74/Ż85/Ż89: Lux 10 (summer), Lux 6 (winter), or multigrade Selektol. Do not mix Selektol with Lux. | W65 pr. p.7 & Table 9-6 pr. p.96; Ż94 pr. p.31; Ż89 | High. Modern equivalent: mineral 15W-40 or 20W-50. That equivalence is an inference. |
| **Coolant capacity** | **10.75 L** (W65). **About 10.5 L** including heater (Ż74 pr. p.16; N77 p.22). The Ż85/Ż89 cold-start text uses **12 dm³** (Ż85 offers 12 dm³ Borygo). | as listed | High (10.5–12 L depending on heater and body) |
| **Thermostat** | W65: **starts opening at 68–74 °C**, at least 9 mm open at 80–86 °C. Ż74: opens 68–74 °C, fully open 77–83 °C (pr. p.49). **Ż85 (TS-3 type): starts opening 71–83 °C, fully open 92–98 °C.** Normal running temperature **80–90 °C** (N77). | W65 pr. p.7; Ż74 pr. p.49; Ż85 PDF p.79 §4.4.3; N77 instrument-panel description ("800 ÷ 90°C" in the OCR, i.e. 80–90 °C) | High. The type changed in the 1980s. |
| Fan belt | 17 × 11 × 1060 mm (W65, Ż74). Later HB 1100 / HB 1105. Deflection **10–15 mm** under a thumb force of about 100 N. | W65 pr. p.7; Ż89 §7.1.2; Ż94 pr. p.31 | High |
| **Fuel pump pressure** | **0.2–0.285 kG/cm² (≈20–28 kPa, 0.2–0.28 bar)** at idle | W65 pr. p.9 (file 0013) and Table 11-7 pr. p.100 | High (one source, two places) |
| Fuel pump delivery / hold | **0.25 L in 18 s or less** at 3600 rpm. After stopping, pressure must **hold for at least 10 s**. | W65 Table 11-7 pr. p.100 | Medium |
| Manifold vacuum at idle (warm) | **430–510 mmHg** at 760–733 mmHg air pressure (lower at altitude: 360–430 at 659–633). On a sharp throttle snap it must rise smoothly by 70 mmHg or more. Uneven drops of up to 20 mmHg are allowed. | W65 Tables 11-1 and 11-2 pr. p.98 | Medium |
| Starter use limit | At most **5 starts in a row**, each **at least 60 s apart**. If it still won't start, the plugs are probably wet: push the choke fully in and crank with the throttle floored. | Ż89 pr. p.29 | High |
| Power / torque | 70 KM DIN (77 SAE) @ 4000. 15 kGm @ 2500 (net 51.5 kW / 147 Nm). | W65; Ż74; Ż89 | High |

### Wear and fit data (W65 pr. p.7–9; useful at teardown)

| Item | Value |
|---|---|
| Main bearing clearance | 0.012–0.057 mm |
| Big-end clearance | 0.012–0.046 mm |
| Crank end float | 0.075–0.175 mm |
| Main journal Ø | 64.00 −0.013 (group I) / 63.75 −0.013 (group II) |
| Crankpin Ø | 51.50 −0.01 / 51.25 −0.01 |
| Piston-to-bore clearance | 0.012–0.024 mm |
| Ring gaps (all rings) | 0.2–0.45 mm |
| Cam lift | 6.68 mm |
| Valve lift | 8.5 mm |
| Valve seat angle | 45° |
| Valve stem-to-guide clearance | Intake 0.030–0.067 mm, exhaust 0.050–0.087 mm |
| Valve head Ø as printed | Intake 45 mm, exhaust 33.5 mm. This conflicts with an owner's 40.5 mm, so check your parts. |
| Valve spring free length | 51 mm |
| Timing gear backlash | 0.025–0.076 mm. At assembly the minimum is 0.025, with at most 0.03 difference around the gear. |
| Cylinder offset from crank axis | 3 mm |
| Oil-pump/distributor drive | Set cyl 1 to **3° BTDC on compression** before fitting the oil pump. The slot is at the angle shown in Rys. 7-3 (15°/35°). Distributor shaft fin: Rys. 7-7. |

Images: `factory-warszawa-S21-oil-cooling-crank-p7.jpg`, `factory-warszawa-S21-valves-fuelpump-p9.jpg`, `factory-warszawa-S21-head-sequence-oilpump-distributor-p90.jpg`.

## 2. Conflicts resolved

1. **Head torque: 120–130 Nm (owners) vs 66–71 Nm (M-20) vs factory.** The factory value is **110–120 Nm (11–12 kGm), cold**, in **every** document: W65, Ż74, Ż85, Ż89 and Ż94.
   - The owners' **120–130 Nm** is above the factory range. It matches the **main-bearing cap** figure (121–133 Nm), and that is probably where it came from.
   - **66–71 Nm** is the side-valve M-20 figure. It does not apply to the S-21.
   - W65 adds an intermediate stage of about 5 kGm (≈50 Nm). Re-torque after 500 km (W65) or 1500 km (Żuk).
2. **Timing: 5° vs 7° vs 8°.** All three are factory figures. They depend on **fuel octane and era**:
   - **5° BTDC** is the as-delivered setting for **78-octane** petrol (Ż74, Ż85).
   - **7°** is Ż74's recommendation for 85-octane, and N77's single figure.
   - **8° ± 1°** is for **85/86-octane** (Ż85, Ż89).
   - The contactless 1994 distributor uses **9° ± 1°**.
   - W65's 2–4° and 6–8° reflect the 70/80-octane fuels of 1965.
   - **On modern 95-octane, start at 8° static and confirm with the 55–60 km/h knock test (Ż89).** The starting point is an inference from the factory rule "higher octane, more advance"; the test is factory.
3. **Firing order 1-2-4-3 vs 1-3-4-2.** **1-2-4-3** is confirmed by every S-21 table.
   - **1-3-4-2** is the firing (injection) order of the **Andoria 4C90 diesel**, printed on the next page of the 1994 Żuk manual (pr. p.32).
   - The same 4C90 has **90 × 95 mm and 2,417 cm³**, exactly the "wrong" bore, stroke and capacity in the pl.wikipedia infobox. Wikipedia mixed up the Żuk's petrol and diesel data.
   - Image: `factory-zuk1994-4C90-diesel-1342-p32.jpg`.
4. **Exhaust valve clearance: 0.25–0.30 vs 0.30–0.32.** The factory figure is **0.30–0.32 mm cold** (intake 0.20–0.22). The polskiedostawczaki "0.25–0.30" figure is not factory. Hot values are 0.30–0.38 intake and 0.40–0.45 exhaust.
5. **Spark plug type.** The factory plug is the **Iskra F75 (M14, 12.7 mm reach, heat value 225–240)**. Bosch equivalent: **W175T1**. USSR: **A23**.
6. **Oil capacity: 5 vs 6 L.** The system holds 6 L. A change takes about 5 L.
7. **Idle speed.** The Nysa manual gives **550–650 rpm specifically for the Weber carburettor**. Late Żuks give 600–800.
8. **Coolant capacity (Żuk).** About 10.5 L (10.75 L on the Warszawa). Up to 12 L is quoted in the later Żuk manuals.

## 3. Still open

- **Units of the centrifugal advance table** (distributor or crank degrees). Check on a strobe: total advance at about 3000 rpm with the vacuum hose off.
- **Dwell of 65° ± 4°.** Two manuals print it, but it is high for this kind of distributor. Not verified on a running engine.
- **Head fasteners (studs vs bolts).** When the change happened is unknown. W65 shows studs; Żuk from at least 1985 shows bolts. Torque is the same either way. Check what your engine has.
- **No torque found** for manifold nuts, rocker shaft pedestals, crank pulley nut, oil pump, sump or rocker cover. These are probably in a Żuk workshop manual (*Naprawa samochodu Żuk*), which is not on archive.org.
- **Modern plug cross-reference** (Bosch W175T1 to a current part number, NGK, etc.) has no factory source. The owner's Denso W20TT is in `specs-and-service-data.md`.
- **Fuel pump pressure** is from the 1965 Warszawa book only. No Żuk-era figure was found.
