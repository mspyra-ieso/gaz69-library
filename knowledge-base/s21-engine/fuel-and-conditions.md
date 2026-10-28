# S-21: Modern Fuel, E10, LPG, and Cold- or Hot-Weather Running

Labels used on this page:
- **[FACTORY]**: from the manuals. Source keys are defined in `factory-service-data.md`.
- **[FORUM]**: owner opinion.
- **[INFERENCE]**: my reasoning from the sources, not a sourced fact.

## 1. What fuel the engine was designed for

| Document | Fuel | Timing | Source |
|---|---|---|---|
| Warszawa 1965 | LO 70 or LO 80 (leaded) | 2–4° BTDC for LO 70; 6–8° BTDC for LO 80 | [FACTORY] W65 pr. p.6 |
| Żuk 1974 | Leaded, at least 78 octane. "for S-21 85 octane recommended at 7° advance". | 5° ± 30′ BTDC in the table | [FACTORY] Ż74 pr. p.12–13 |
| Nysa 1977 | LO 85, or a 60:40 mix of LO 78 and LO 94 | 7° BTDC | [FACTORY] N77 p.14 & p.17 |
| Żuk 1985 | "Producent silnika ustawia kąt wyprzedzenia zapłonu na 5° ±1° przed ZZ dla etyliny 78" (the factory sets 5° ± 1° BTDC for 78-octane leaded). For higher octane, e.g. 85, advance to 8° ± 1°. | 5° or 8° | [FACTORY] Ż85 pr. p.61 |
| Żuk 1989 and 1994 | Etylina 86 (86-octane leaded) | 8° ± 1° (points); 9° ± 1° (contactless) | [FACTORY] Ż89 pr. p.11; Ż94 pr. p.30 |

**Today's 95-octane unleaded** (Pb95 in Poland, E10 since 2024) has more knock margin than any of these fuels. The engine does not need 98.

[INFERENCE] Set 8° static on a points distributor and confirm with the factory road test: warm engine, top gear, 55–60 km/h, then floor the throttle. A brief, faint knock is correct ([FACTORY] Ż89 pr. p.52).

- Use the **octane selector** for fine adjustment. One division equals 2° at the crank ([FACTORY] W66e pr. p.139).
- Strucelsw (FORUM) argues that 98 is pointless: "98 to dluzszy czas oddzialywania plonmienia" (98 burns longer, so more heat). https://www.forum.polskiedostawczaki.pl/viewtopic.php?f=13&t=5471

## 2. Unleaded fuel and valve seats

- **Hardened seats.** Owners date the factory switch to hardened exhaust seats somewhere between 1989 and 1993. Already covered in `owner-reports.md` OR-65. Rebuilders fit hardened seats for unleaded (`ignition-and-mods.md`).
- **Recession risk.** [FORUM] Strucelsw says old engines run fine on unleaded and on LPG *as long as valve clearances are kept up*. Recession shows up as **shrinking exhaust clearance**: "chyba ze ktos zaniedbal regulacje zaworów" (unless someone neglected adjusting the valves). Lead-substitute additives exist but are rarely used. t=5471 (above)
- **Check interval.** [FACTORY] Valve clearance is part of every OT service: 0.20–0.22 mm intake and 0.30–0.32 mm exhaust, cold (Ż89 §4.1.2).
  - [INFERENCE] On unleaded, check the exhaust clearance more often than the factory interval, because a closing clearance is the early sign of seat recession.
  - If the clearance closes repeatedly on the same valve, the seat is sinking. Fit a hardened seat.

## 3. E10 (ethanol) effects

| Point | Source |
|---|---|
| Expect to replace the **fuel-pump diaphragm and rubber fuel hoses** more often: "częściej wymieniać membranę pompy paliwa i gumowe przewody" (replace the diaphragm and rubber hoses more often). | [FORUM] https://www.forum.polskiedostawczaki.pl/viewtopic.php?f=13&t=5471 |
| Hot-fuel boiling is a problem, but one member blames the **light ethers** (boiling at about 30–40 °C) rather than the alcohol: "z gotowaniem paliwa jest klopot , ale nie z powodu alkoholu tylko eterów" (boiling is a problem, but from the ethers, not the alcohol). | [FORUM] same thread |
| E10 is more corrosive ("zwiekszenie korozyjnosci"). Use a **stabiliser** for a vehicle that stands unused. Some owners stay on 98 (E5) for that reason. | [FORUM] same thread |

[INFERENCE] Practical steps for the GAZ-69 swap:
- Use **ethanol-rated fuel hose** (marked SAE J30 R9/R14 or "E10/E85").
- Fit a clear **inline filter** and inspect it.
- Keep the **pump diaphragm** as a carried spare. The factory pump test is in `factory-service-data.md`: 0.2–0.28 kG/cm², 0.25 L in 18 s or less, holds pressure 10 s or more.
- For long storage, use E5 (98) or a stabiliser.
- Carb internals are covered in the separate Weber knowledge base.

## 4. LPG on the S-21 (new items only)

LPG basics are already in `owner-reports.md` §14 (OR-61 to OR-65). These are the new items:

| Case | Detail | Status | Source |
|---|---|---|---|
| LPG car won't run on petrol after the tank ran dry | Debris sucked into the mechanical pump; the **suction valve failed** ("padł zaworek ssący"). Fix: replace the valves or the pump, and add a filter. Owners disagree on where: between pump and carb on flexible hose, or before the pump. | SUGGESTED | [FORUM] https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=195 |
| LPG and valve seats | Fine if the clearances are maintained. Owners add 0.05 mm for gas (see OR-65). | [FORUM] | t=5471; `owner-reports.md` OR-65 |

## 5. Cold weather

| Item | Detail | Source |
|---|---|---|
| Normal cold start | Gearbox in neutral. **Pull the choke fully** (except in warm weather). **Do not touch the throttle**: the starting device works only with the throttle closed. **Press the clutch** while cranking to free the thick gearbox oil. Push the choke halfway once it runs evenly, and fully once warm. Do not load or rev the engine while warming. | [FACTORY] Ż89 §3.11 pr. p.29 |
| Flooded | After 5 attempts, push the **choke fully in** and crank with the **throttle floored** | [FACTORY] Ż89 pr. p.29 |
| Starter limits | No more than **5 starts in a row**, each **at least 60 s apart** | [FACTORY] Ż89 pr. p.29 |
| Winter (1 Nov–31 Mar) | **Turn the engine a few times with the crank handle** (clutch pressed) before using the starter. **Close the radiator blind** (zasłona). | [FACTORY] Ż89 §3.12 pr. p.30 |
| Very cold (about −20 °C) | Drain the coolant. Pour **hot water at 80–100 °C, about 12 dm³** through the engine repeatedly until compression resistance is felt on the crank handle. Also pour **about 2 dm³ of hot water slowly over the inlet manifold**, or wrap it in a rag and pour onto that. Refill with antifreeze after the start. | [FACTORY] Ż89 §3.12; Ż85 (same text) |
| Minimum unassisted start temperature | **−15 °C** (1994 S-21) | [FACTORY] Ż94 pr. p.31 |
| Push or tow start | 2nd gear at 15–20 km/h. **Dangerous with frozen oil**: it can break the crankshaft. | [FACTORY] Ż89 §3.13 |
| Winter oil (Warszawa) | Above 0 °C: Extra 8T (SAE 30). Above −12 °C: Extra 5T (SAE 20W). Down to −22 °C: SAE 10W. Below −22 °C: SAE 5W. | [FACTORY] W65 Table 9-6 pr. p.96 |
| Too much oil in the air-filter bath | 350 cm³ is correct. **More can stop a winter start** by blocking the air path ("Większa ilość oleju, zimą może uniemożliwić rozruch silnika"). | [FACTORY] W65 pr. p.96 |
| Mixture pre-heater | The inlet manifold has a **thermostatic heater flap**. It must turn freely under its bimetal spring when cold. A seized or missing flap causes poor cold running and higher fuel use. Ż89 lists a faulty "podgrzewacz mieszanki przewodu ssącego" (mixture pre-heater in the inlet manifold) as a cause of high fuel consumption. | [FACTORY] W65 §10.4.1 pr. p.84; Ż89 §3 "fuel consumption" list |
| Carburettor icing | **No S-21-specific source found.** [INFERENCE] The working manifold heat flap above and a warm-air intake are the factory anti-icing measures. Check them first if the engine stalls in cool, damp weather. | gap |

## 6. Hot weather and vapour lock

| Item | Detail | Source |
|---|---|---|
| Normal coolant temperature | 80–90 °C. Thermostat starts opening at 68–74 °C (early) or 71–83 °C (TS-3, 1980s). | [FACTORY] N77; W65; Ż85 |
| Tropical option | 6-blade fan instead of 4 | [FACTORY] Ż74, Ż89 |
| Hot restart | Warm engine: no choke, **press the throttle lightly** while cranking | [FACTORY] Ż89 pr. p.30 |
| Fuel return line (anti-percolation) | Owner fitted a **tee after the pump with a return to the tank**: 8 mm hose, return restricted to about 5 mm. Result: the carb stays dry outside and **no fuel spills onto the manifold** when starting on choke. Worked with both mechanical and electric pumps. "Powrót paliwa w moim S21 zrobiony i działa to super." (return line done on my S21 and it works great) | [FORUM] CONFIRMED, https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=195 |
| Fuel boiling | Blamed on the volatile ethers in modern petrol | [FORUM] t=5471 |

[INFERENCE] Vapour-lock checklist for the GAZ-69 swap:
- route the fuel line away from the exhaust manifold and downpipe;
- add a heat shield or spacer under the carb if needed;
- consider the return line above;
- if an electric pump is fitted, mount it low and near the tank (pushing, not pulling).

## Gaps

- No Żuk/Nysa owner report of actual **carburettor icing** was found.
- No new **Nysa LPG** sources were found.
- elektroda.pl was unreachable (see `sources-gaps.md`).
