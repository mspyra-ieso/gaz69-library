# Tuning the Weber 28/35 (S2A / S2A1 / S2B1) on the S-21

This file covers **choosing and changing calibration**: jets, float level, fuel, air filter and measuring tools. The related files are:
- `idle-and-mixture.md`: idle speed and idle mixture in detail.
- `cold-start-device.md`: the piston starter ("ssanie").
- `linkage-and-pump.md`: the accelerator pump, the secondary throttle, and pedal or cable linkage (including the GAZ-69).
- `specs-and-jets.md`: factory values (not repeated here, except as the baseline).

## How claims are marked

| Tag | Meaning |
|---|---|
| **[FACTORY]** | FSC Żuk owner's manuals 1989 / 1994 ([Z89], [Z94]) or the parts catalogue |
| **[BOOK]** | Wiejak & Zagaja, *Żuk – budowa, eksploatacja, naprawa*, read via the zukowka machine translation ([WZ]) |
| **[RELATED]** | The *Polski Fiat 125p – budowa, eksploatacja, naprawa* (1982) book chapter on the **FOS/Weber 34 DCHD** ([F125]). This is a sister carb from the same Łódź/Polmo family. It shares the piston starter, the piston pump, the release-lever secondary lock, the 0.8 / 1.2 / 1.5 mm progression holes, the 1.75 needle valve and the 10 mm pump stroke. Its jets, venturis and **vacuum-operated** secondary differ. **Methods transfer; numbers do not.** |
| **[FORUM]** | forum.polskiedostawczaki.pl ([FPD]), zlombol.pl, drive2.ru. Owner experience, not specification |
| **[GENERAL]** | General Weber or carburettor practice from non-Polish sources ([ALFA], [FT]), or plain engineering reasoning. Labelled where no source covers the 28/35 |

⚠ marks advice that contradicts factory data.

---

## 1. Goals, in order of priority

1. **A smooth, stable idle at 600–800 rpm on a hot engine** [FACTORY] ([Z94] data table; [Z89]). It must return to idle without stalling after a snap of the throttle ([PD]).
2. **A clean transition** from idle to the primary main circuit (pulling away, light throttle) and from primary to secondary (above about 2/3 primary opening, [Z94]).
3. **Economy at cruise.** For reference:
   - [FACTORY] Z94 gives a "control consumption" of **11–13 l/100 km at 70 km/h** with a full load ([Z94] §3.17.1).
   - [FORUM] Marian: a Weber S-21 should manage about **11 l/100 km** on the road, and some owners report **9.8** ([FPD t=2222]).
4. **Full power near full throttle**, with a slightly rich mixture to protect valves.
   - [FORUM] A too-lean mixture "wypali zawory" (burns the valves) and leaves **white plugs** (nysanek, [FPD t=2222]).
   - [FORUM] A lean jet raises exhaust temperature and loads valves and seats thermally ([ZL]).
5. **Running on today's 95 E5 / E10.** The engine was designed for **"Etylina 86"** with a **7.5:1** compression ratio ([Z94] engine data). See §6.

The factory baseline is a good compromise. [FORUM] Most "tuning" problems owners report are really **wrong parts in a used carburettor**:
- a 118 primary main jet ([FPD t=3998]);
- swapped I/II jets ([FPD t=777 p3]);
- swapped emulsion tubes ([FPD t=3998]);
- jets reamed with wire ([FPD t=2247]).

**Always verify every calibrated part against `specs-and-jets.md` before changing anything.**

---

## 2. What each part changes

Weber jet numbers are bores in hundredths of a millimetre: "110" is 1.10 mm [FACTORY] ([Z94]).

| Part [Polish] | S2A1 factory (I / II) | Circuit and rpm range it governs | Bigger number means | Notes |
|---|---|---|---|---|
| **Main fuel jet** [dysza główna paliwa] | 110 / 145 (S2B1 125) | Main circuit, from roughly light-cruise airflow up to full load. [FORUM] Strucelsw: at **~2500 rpm the primary main circuit is already working**, so an oversize primary main jet shows up there ([FPD t=3998]) | **Richer** across the whole main range | [GENERAL] The main jet shifts the whole range; the air corrector mainly the top end ([ALFA]) |
| **Air-correction jet** [dysza powietrza hamująca] | 250 / 225 (S2B1 220) | Air bleed into the emulsion well. Its effect **grows with rpm and airflow** | **Leaner**, mostly at high airflow | [GENERAL] As a rule, **2.5–3 air-corrector sizes ≈ 1 main-jet size** ([ALFA]). [RELATED] The bleed lowers the fuel level in the well as flow rises, which gives economical part-load running ([F125] p.64) |
| **Emulsion tube** [rurka emulsyjna] | F27 / F35 | Shape of the main-circuit curve: where air enters the fuel column | (not a size) | [GENERAL] Holes low on the tube give richer at high rpm; holes high give leaner ([ALFA]). [FORUM] "f27 jest grubsza" (F27 is the thicker one), so the tubes can be told apart ([FPD t=3998]). **Do not swap them**: a swapped pair is a common find ([FPD t=3998]) |
| **Idle fuel jet** [dysza paliwa biegu jałowego] | 45 (on the EZ-20 tip) / 100 (secondary progression) | Idle and the **first part of throttle opening** through the 2 × 0.8 mm progression holes ([WZ] Fig. 2.27) | Richer idle and transition | [FORUM] "dysza oczywiście 45 nie 50" (45, not 50; Strucelsw, [FPD t=4814]). A crushed jet or too-thick O-ring lets fuel bypass it, so the mixture screw loses control ([FPD t=4814]) |
| **Idle air jet** [dysza powietrza b. jałowego] | 175 / 80 (body drilling) | Air bleed for the idle emulsion | Leaner idle and transition | Not replaceable: a calibrated drilling. Keep it clean |
| **Idle mixture screw** [wkręt składu mieszanki] | — | Idle only. It meters the emulsion leaving the outlet below the plate | Screwing **in = less mixture = leaner** | See `idle-and-mixture.md` |
| **Accelerator-pump jet** [dysza pompki] | 40 (valve 80, stroke 10 mm, 5 cm³ / 10 strokes) | Transient enrichment on throttle opening | Bigger = more, shorter squirt | See `linkage-and-pump.md` |
| **Float level** [poziom pływaka] | 6.25–6.75 mm (S2A1), 7 ±0.25 mm (S2B1), measured from the cover face without the gasket | Shifts **every circuit** | A **smaller** distance (float closer to the cover) = **higher** fuel level = richer everywhere | [RELATED] On the 34 DCHD, 5 mm float distance = fuel 23 mm below the chamber top, and 6 mm = 25.5 mm. **6 mm "may be used for excessive consumption"** on a correctly tuned engine ([F125] p.68). So a 1 mm float change moves the fuel about 2.5 mm, and the factory itself used a lower level as an economy measure |
| **Venturi** [gardziel] | 21 / 26 | Signal strength vs. breathing | — | Not an owner adjustment on this carb |

### Symptom → direction

Only change jets **after** the float level, ignition, valve clearances and air leaks are right.

| Symptom (hot engine) | Probable circuit | Direction | Sources |
|---|---|---|---|
| Black smoke after a blip; CO high at 2500 rpm; sooty plugs | Primary main (or float too high / leaking needle) | Check the float and needle first, then a **smaller primary main** or a **bigger primary air corrector** | [FPD t=3998]; [FPD t=4814] |
| Engine keeps running with the mixture screw fully in | Not a jet problem: **flooding** or idle-jet bypass | Fix the float or needle, the idle-jet O-ring or a crushed jet | [FPD t=4814] |
| Stumble pulling away, but fine at steady cruise | Idle/progression (lean), or pump | Clean the 45 jet and progression holes; set the mixture screw; check the pump squirt; a slightly richer idle | [FPD t=777 p11] (O24 in `owner-reports.md`); [GENERAL] [ALFA] |
| Hesitation that disappears if you partly cover the carb intake with your hand | **Lean** in that range | Richer (jet, level, or find the air leak) | Marian's test, [FPD t=2030] |
| Pops back through the carb, misfires, lacks full power | **Lean** (air leaks, low float, dirty jets, weak fuel pump) | Fix the cause; only then go richer | Marian's checklist, [FPD t=2247] |
| Pops in the exhaust, black smoke, chokes, high consumption | **Rich** (dirty or oiled air filter, choke not fully off, reamed jets, dirty air jets, high float, leaking needle) | Fix the cause | [FPD t=2247] |
| Flat or weak near full throttle; will not reach speed | Secondary not opening fully, or a lean top end | Check the linkage first (`linkage-and-pump.md`), then the secondary main or air jet | [FPD t=3347]; [FPD t=4581] |
| Runs well, but pinks under load at low speed | Lean (cracked insulating spacer), or timing too far advanced for the fuel | Air leak first | GAZ-69 case, [D2-GAZ] (O34 in `owner-reports.md`) |
| Cold engine will not rev for a few minutes after the choke is pushed in | Normal cold-lean S-21 behaviour, or dirt | Leave the jets alone; use a little choke longer | [FPD t=4713] (O30) |

---

## 3. Owner re-jets and their outcomes

| Change | Vehicle and carb | Result | Source |
|---|---|---|---|
| **118 → 110 primary main**, new needle valve, float 8.5 → 6.5 mm, new air filter | Nysa S-21, 28/35 S2A1 | Before: CO > 7 %, λ 0.76–0.83 at 2500 rpm, black smoke. After the needle and float: idle fine, but still λ ≈ 0.80 at 2500. After the **110 jet**: idle **CO 2.4 %, λ 1.024**; at raised rpm **CO ≈ 4 %, λ 0.93, HC 450–500 ppm**. Values also improved after the **brake servo and master cylinder** were replaced. The owner suspected the old servo was letting fluid or air into the manifold | [FPD t=3998] |
| "Factory 145" → **135** → **115** (throat not stated; the symptoms fit the **primary**) | Żuk after rebuild, "28/35 S2A ver. 1" | On 145: about **15.5 l/100 km**. On 135: **about 12 l/100 km**, with small stumbles when pulling away. On 115: very hard to pull away and stalling cold or even warm. The owner settled on a compromise | Arendi, [ZL] |

**Reading the second case.** ⚠ The factory S2A1 primary is **110** and its secondary is **145**. A carb running 145 on the primary would be grossly rich. A 115 primary is still **richer** than factory 110, yet it drove badly. Both points suggest that carb had **non-factory air jets or emulsion tubes**: the same thread notes "diametrally different" tube sizes between the owner's two carbs ([ZL]). Treat this case as proof that consumption follows the main jet strongly, **not** as a jet recommendation.

### Alternative jet ranges quoted by a forum mechanic

[FORUM] Strucelsw (who rebuilt carbs commercially, "Strucelserwis"):
- The primary main should be the smaller jet: **110, 120 or 125**.
- The secondary should be **135, 145 or 150**, "depending on the version".
- Air jets: **250 / 220 / 210** on the primary and **225 / 220 / 210 / 200** on the secondary.
- Idle jet: **45**.
- Source: [FPD t=4814].

These ranges cover the whole Polish Weber family (28/35, 34S2B1, 34 DCHD and others). **For an S2A1 the factory pairs are 110/250 and 145/225.**

### Spare jets for unusual fuel or altitude

[FORUM] Strucelsw's kit list for an old-type Weber taken abroad on high-ethanol fuel ([FPD t=3094]):
- Primary: **115, 120, 135**. He says 130 can be made by drilling a 125 to 1.3 mm, because it is not sold.
- Secondary: **145, 150**. Larger sizes (160, 170) can be drilled from 155.
- Or, more generally: steps of **+5, +10 and +15** over the fitted jets.

⚠ Drilling jets is a field expedient. Factory practice was to check jets by **flow testing**, not just with a pin gauge ([F125] p.68).

---

## 4. Economy vs power

| Lever | Economy effect | Power or driveability cost | Sources |
|---|---|---|---|
| Smaller primary main (e.g. 110 → 105) | Lower cruise consumption | Stumbles pulling away, especially loaded; hotter valves | [ZL] (135/115 experiment and the warning about loads and valves) |
| Lower float level (bigger float distance, within tolerance) | The factory 34 DCHD book allows a 6 mm level "for excessive consumption" | Possible lean tip-in and harder cold starts | [RELATED] [F125] p.68 |
| S2B1-type secondary (125 / 220 plus the gravity economiser) | The factory's own "oszczędny" (economical) version | Power is kept near full throttle by the economiser | [FACTORY] see `how-it-works.md` §8 |
| Fix the air filter, choke return and float before touching jets | Large: one owner went from 21 to 16 l/100 km just by re-setting the carb | None | [FPD t=4256] |
| Driving style: a vacuum gauge ("ekonometr") on the dash | Teaches throttle use | None | [FPD t=680] |
| Raising compression at a rebuild (an owner idea) | Better efficiency on modern fuel | Needs a head or piston change. Not a carb tune | [ZL] |

[FACTORY] Z89 lists the **non-carb factors that raise consumption**: high fuel level, driving with the starter on, wrong timing or points gap, faulty distributor advance, plugs of the wrong heat range, a **faulty mixture pre-heater**, low tyre pressure and dragging brakes ([Z89] consumption section).

---

## 5. Altitude and temperature

- [FORUM] Strucelsw ([FPD t=3094]):
  - In high mountains **smaller** jets are indicated, because there is less oxygen.
  - Ethanol-rich fuel needs **bigger** jets, and the two effects partly cancel.
  - Above 10 % alcohol the change is noticeable, and settings (including the idle mixture) need correcting.
- [FORUM] nysanek: a four-stroke Żuk will cope at altitude without re-jetting; it is two-strokes that need jet changes ([FPD t=3094]).
- [GENERAL, unsourced] Air density falls by roughly 10 % per 1000 m, and a fixed-jet carb gets correspondingly richer. For occasional mountain trips, leave the jets alone and lean the idle screw slightly. Re-jet only for sustained use above about 1500 m.
- **Temperature and season** [FACTORY] ([Z94] §4.3.3): the air filter has a **summer/winter intake flap**. The handle goes to the **blue arrow (cold air) in summer** and the **red arrow (warm air from the exhaust) in winter**.
  - A flap left on "warm" in summer makes the engine run richer and hotter.
  - [FORUM] Strucelsw lists a filter flap stuck on warm, or a stuck manifold pre-heater, as causes of rich, smoky running ([FPD t=3998]; [FPD t=3707], O42 in `owner-reports.md`).
- **The manifold pre-heater** [podgrzewacz mieszanki]:
  - [BOOK] It is a bimetal-controlled flap in the exhaust manifold that sends exhaust gas under the inlet manifold when cold ([WZ] §2.1.5).
  - [FACTORY] Z89 says a faulty pre-heater raises consumption and can **overheat** the engine ([Z89]).
  - ⚠ [FORUM] Several owners **weld the flap in the "hot gas to exhaust pipe" (non-heating) position** so it cannot stick ([FPD t=4581], Marian and piotr1eo; nysanek, [FPD t=2222]). This departs from the factory design: expect a longer cold-lean period in winter.

---

## 6. Modern fuel: 95, E5, E10

| Point | Source |
|---|---|
| The S-21 was specified for **Etylina 86** (leaded, 86 RON), compression 7.5:1 | [FACTORY] [Z94] data table |
| 95 E5 has carried up to 5 % ethanol for over 20 years, and delivery notes have shown up to about 12 %. "10% to nic" (10 % is nothing) for mixture; at most a small mixture-screw correction | [FORUM] Strucelsw, [FPD t=5471] |
| Ethanol needs only **~9–10 kg of air per kg** against **14.7** for petrol (13 for full power, **16.5 the economy limit** of a conventional engine). So more fuel by volume is needed: consumption rises in proportion to the lower heating value | [FORUM] Strucelsw, [FPD t=3094] |
| **Expect slightly leaner running on E10 with unchanged jets.** [GENERAL, calculated from the figures above] The stoichiometric ratio of E10 is about 14.1:1 against 14.7, so about 4 % more fuel is needed. That is less than one main-jet step (110 → 115 is +9 % in area). Re-set the idle screw and check the plugs; re-jetting is normally unnecessary | derived from [FPD t=3094] |
| Fuel **boiling in the pump or carb** comes from the **ethers** (anti-knock additives boiling at 30–40 °C), not the alcohol | [FORUM] Strucelsw, [FPD t=5471] |
| E10 effects: replace the **fuel-pump diaphragm and rubber hoses** more often; ethanol is corrosive, takes up water and separates. Use a fuel stabiliser in a vehicle that stands | [FORUM] Marian, Strucelsw, [FPD t=5471]; [FPD t=3094] |
| ⚠ **Ignition on modern fuel.** "Ustawiony na znaki nie będzie chodził poprawnie": set to the marks, it will not run right. Set by ear, earlier than the book. The book angle on 95 "only overheated" the engine | [FORUM] Strucelsw, [FPD t=3998]; [FPD t=3094]. [SITE] [PD] says at least 7° "or more". **Factory: 8° ±1° BTDC** (see `specs-and-jets.md`). Z94 also mentions a **manual octane corrector** on the late electronic distributor ([Z94] data table) |
| ⚠ Lead-replacement additives. nysanek uses them ("fuel less dry", slower evaporation from the float bowl). Strucelsw says they foul plugs and are pointless with the hardened seats of later heads | [FORUM] [FPD t=3094] (conflicting opinions) |

Practical consequence: **set the ignition first on the fuel you will actually use, then the idle mixture, then judge the jets.** A late-timed engine on 95 feels lean and sluggish, and owners then wrongly fit bigger jets.

---

## 7. Air filter type and condition

- [FORUM] The Weber was paired with a **dry paper filter**; the older Jikov with an oil-wetted ("mokry") filter. Dziwny Mag lists "gaźnik jikov i mokry filtr powietrza lub gaźnik weber i suchy filtr" ([FPD p=9005]).
- [FORUM] A clogged filter, or **an oil-wetted filter with too much oil**, restricts air and gives a rich mixture: black exhaust, popping in the exhaust, high consumption (Marian, [FPD t=2247]).
- [RELATED] A clogged paper element raises intake resistance and **fuel consumption** ([F125] p.70). [FACTORY] Z94: change it every 10 000 km, more often on dusty roads ([Z94] §4.3.3).
- [FORUM] A quick test: run briefly **without** the filter. If it improves markedly, the filter was choking it (sukiennik68, [FPD t=3139] p.3 snippet).
- **GAZ-69 note** [GENERAL, inference]: if the GAZ-69's original **oil-bath filter** is adapted to the Weber, keep the oil exactly at its mark and give it an adequate air path. The Weber's calibration assumes the free-flowing Żuk paper filter. A restrictive or over-oiled housing acts like a bigger main jet at high airflow. Also check that the adapter does not mask the air-correction jets or the starter's air hole (5.75 mm, [WZ] Table 2.18).

---

## 8. Measuring instead of guessing

### Spark-plug colour [kolor świec]

- **White** insulator means lean (and burnt valves); **black and sooty** means rich (nysanek, Marian, [FPD t=2222]).
- Use the right heat range first, or plug colour misleads:
  - [FORUM] Strucelsw: NGK **B7HS is too cold** for the S-21 ("za zimne świece"); B6HS or B5HS by NGK's own tables. He recommends **Denso WF20TT** and warns about fake NGKs ([FPD t=4814]).
  - Owners also report bad new ISKRA plugs (O3, O35, O36 in `owner-reports.md`).
  - Gap **0.6–0.7 mm** ([PD]).
- [GENERAL] Read plugs after a steady run at the load you are tuning, then switch off immediately. Idle and choke use colour plugs black on any carburettor.

### CO and HC analyser

There is no factory CO figure for the 28/35. Reference points:

| Value | Source |
|---|---|
| **1.2–2 % CO at 850 ±50 rpm (maximum 4.5 %)** | [RELATED] 34 DCHD factory procedure, [F125] p.69 |
| Idle **CO 2.4 %, λ 1.024**; at raised rpm **CO ≈ 4 %, λ 0.93, HC 450–500 ppm** | [FORUM] S2A1 Nysa after the fixes, [FPD t=3998] |
| CO **1.5–3 %**, ~300 ppm HC typical for a healthy classic Weber | [GENERAL] [ALFA] |
| Polish idle limits: **4.5 % CO** for cars registered up to 30 Sept 1986; **3.5 %** from 1 Oct 1986 to 30 June 1995 | [GENERAL] [IDZ2013] (table cited from the regulations; check the current law) |

### Vacuum gauge [wakuometr / podciśnieniomierz]

- **Connect it to manifold vacuum, not the carb's distributor port.** The port on the carb body is above the closed plate (ported vacuum). [FORUM] An owner who teed into the distributor line read **about 0 kPa at idle**, rising to about −60 kPa off idle: "działa prawidłowo ale na odwrót" ("works correctly but backwards"; [FPD t=1007]). For tuning, tee into the **brake-servo hose from the inlet manifold** (Marian, [FPD t=1007]).
- [FORUM] For economy driving the absolute numbers matter less than **smooth changes**. Note the maximum values so you can avoid them (Leśnowóz, [FPD t=1007]).
- Idle-mixture use: see `idle-and-mixture.md` §4.

### Wideband lambda (AFR) sensor

There are no S-21 owner reports with a wideband. General practice:
- **Targets**:
  - **14.7:1 (λ 1.0)** is chemically correct.
  - **~13:1** is for full power (Strucelsw, [FPD t=3094]); N/A V8 tuners aim for **12.5:1 at WOT** ([FT]).
  - **≤16.5:1** is the lean limit for economical running of a conventional engine (Strucelsw, [FPD t=3094]).
  - Light cruise near stoichiometric ([FT]).
- **On a progressive twin-choke**, the AFR **leans steadily as airflow rises until the secondary opens**. So **tune the primary first** (main jet against the curve just before the secondary opens), then the secondary ([FT]). For the 28/35, that means making runs with the secondary locked shut (pedal short of 2/3) before full-throttle runs.
- **Fitting** [GENERAL, inference]:
  - Weld a bung in the down-pipe ahead of the silencer.
  - Seal exhaust leaks upstream; air drawn in through a leak reads lean.
  - A misfire also reads lean.
  - The sensor needs a hot exhaust; idle readings on a long cold pipe drift.
- The 2018 Nysa case ([FPD t=3998]) shows what a 4-gas analyser can do: λ readings at idle and at 2500 rpm pinpointed a wrong primary jet. A wideband would show the same in driving.

---

## 9. Recommended procedure from the factory baseline

Work in this order. Do not skip steps: each one invalidates the steps after it.

1. **Mechanical base** [FACTORY] ([Z94] idle-regulation preconditions; [PD]):
   - valve clearances 0.20–0.22 mm intake and 0.25–0.30 mm exhaust ([PD]);
   - compression;
   - plugs of the right heat range, gapped 0.6–0.7 mm;
   - points 0.4 mm, or the electronic module;
   - **timing**: start at the factory 8° ±1° and adjust by ear and on the road for your fuel (§6 ⚠);
   - **vacuum advance working** (Strucelsw, [FPD t=3094]).
2. **Air-tightness:**
   - base gaskets and the **insulating spacer** (not cracked or warped; [D2-GAZ]);
   - manifold gaskets;
   - the brake-servo hose ([FPD t=3998]);
   - the **PCV plunger in the manifold** moving freely ([FPD t=4162]);
   - throttle-spindle wear.
3. **Fuel supply:** pump pressure and the spacer (`troubleshooting.md`). Check the needle valve holds when hand-primed ([FPD t=3998]).
4. **Verify every calibrated part** against `specs-and-jets.md`:
   - main 110/145, air 250/225, F27/F35, idle 45 and 100, pump jet 40;
   - right throats;
   - no wire-reamed jets ([FPD t=2247]).
   - Clean everything and **blow the idle jet through properly**. In the 2018 case it re-blocked twice after cleaning ([FPD t=3998]).
5. **Float level** to the factory figure, without the gasket and with the cover vertical (`adjustment-procedures.md` §1).
6. **Cold-start device** fully off when the knob is in (2–3 mm reserve; `cold-start-device.md`). **Air-filter flap** on summer or winter as appropriate.
7. **Idle speed and mixture** on a hot engine (`idle-and-mixture.md`).
8. **Linkage:** both plates reach full opening with the pedal floored; the secondary starts at about 2/3; the pump squirts (`linkage-and-pump.md`).
9. **Road test and read:**
   - plug colour after steady runs at the load in question;
   - or wideband logs;
   - or a 4-gas analyser at idle and at about 2500 rpm (primary main circuit).
10. **Only now consider jets**, one change at a time. Keep the removed jet labelled.
    - **Too rich at cruise** (λ < 0.9 at about 2500 rpm, sooty plugs, high consumption): primary main −5 (110 → 105), or a primary air corrector +10 to +20.
    - **Lean stumble pulling away** with a correct idle: first the pump and the 45 jet's cleanliness; then a slightly richer idle screw. A main jet change is a last resort ([ZL] shows that going too small on the primary main hurts tip-in).
    - **Flat at full throttle** with the linkage confirmed: secondary main +5 to +10, or a secondary air corrector −10.
    - [GENERAL] Remember **2.5–3 air-corrector steps ≈ 1 main-jet step**, with more effect at high rpm ([ALFA]).
11. **Re-check the idle mixture** after any jet or float change: the idle circuit draws from the primary main well ([WZ] Fig. 2.27).

---

## Sources (short keys)

Full list with archive file names: `sources-tuning.md`.

[Z89]: https://archive.org/download/fsc-lublin-instrukcja-obslugi-zuk/FSC_LUBLIN-1989-instrukcja_obslugi_Zuk.pdf
[Z94]: https://archive.org/download/fsc-lublin-instrukcja-obslugi-zuk/FSC_LUBLIN-1994-instrukcja_obslugi_Zuk.pdf
[WZ]: https://archive.org/download/zukowka-zuk-spare-parts-catalog/ZUK-BEN-angielski.pdf
[F125]: https://archive.org/details/PolskiFiat125pBudowaEksploatacjaNaprawa1982
[PD]: https://polskiedostawczaki.pl/podstawowe-regulacje-silnikow-s-21-oraz-m-20/
[FPD t=3998]: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3998
[FPD t=4814]: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4814
[FPD t=3094]: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3094
[FPD t=5471]: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=5471
[FPD t=1007]: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=1007
[FPD t=680]: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=680
[FPD t=2222]: https://forum.polskiedostawczaki.pl/viewtopic.php?t=2222
[FPD t=2247]: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=2247
[FPD t=2030]: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=2030
[FPD t=3139]: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3139
[FPD t=4256]: https://forum.polskiedostawczaki.pl/viewtopic.php?t=4256
[FPD t=4581]: https://forum.polskiedostawczaki.pl/viewtopic.php?t=4581
[FPD t=3347]: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3347
[FPD t=4713]: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4713
[FPD t=4162]: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4162
[FPD t=3707]: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3707
[FPD t=777 p3]: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=30
[FPD t=777 p11]: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=150
[FPD p=9005]: https://forum.polskiedostawczaki.pl/viewtopic.php?p=9005#p9005
[ZL]: https://zlombol.pl/community/technikalia-2/gaznik-weber-28-35-s2a-zuk-problem-2/
[D2-GAZ]: https://www.drive2.ru/l/590869853259170000/
[ALFA]: https://alfaworkshop.co.uk/alfa_carburettors.shtml
[FT]: https://www.ford-trucks.com/forums/1331663-carb-tuning-w-afr-meter.html
[IDZ2013]: https://yadda.icm.edu.pl/baztech/element/bwmeta1.element.baztech-9ca8ccf1-cc2e-4241-bda6-d74a7da9b3ee/c/Idzior_Karpiuk_Czaplinski_Iwanicki_Wybrane_10_2013.pdf
