# The cold-start device [urządzenie rozruchowe, "ssanie"]

Tags are as in `tuning.md`. The 28/35 has **no choke flap**. Its "choke" is a **piston-valve starter carburettor** in the round housing on the side of the body. It is worked by a cable from the cab knob. The 34 DCHD on the Fiat 125p uses the same design, and its book describes the internals in more detail ([F125] pp.62–64; image `images/u-related-34dchd-piston-starter-fig2-64-fiat125p-book.jpg`). The 28/35 drawing is WZ Fig. 2.26 (`images/t-wz-fig2-25-26-accelerator-pump-and-starter.jpg`).

## 1. How it works

The 28/35 calibration is: starter fuel jet F1/150, air jet 150, air passage 5.75 mm, weakening holes 1.75 / 1.75, reserve-well bush 250 ([WZ] Table 2.18; [Z94] Table 4-3).

**Position A: fully on (cold start), engine cranking** [BOOK] ([WZ] §2.1.5):
1. With the throttle **closed**, fuel flows from the float chamber through the starter fuel jet.
2. Air from the starter air jet mixes with it.
3. The emulsion enters the piston chamber of the starter valve and mixes with more air.
4. Manifold vacuum draws this rich mixture through its own channel into the throat **below the throttle plate**.
5. [RELATED] At first a **reserve well** [studzienka / tulejka rezerwowa] empties, which gives an extra-rich first shot. Then the mixture leans a little as the jet draws air instead of fuel from the well ([F125] p.63).

**Once the engine fires: automatic leaning.**
- [BOOK] The higher vacuum opens a small **air valve**, and extra air through the hole in the cup leans the starter mixture "preventing the engine from flooding" ([WZ] §2.1.5).
- [RELATED] In the 34 DCHD book this is a spring-loaded **piston (29)** that the vacuum pulls down to open an extra air seat ([F125] p.63).

**Position B: half (warming, or starting a not-fully-cold engine).** [RELATED] Pushing the knob in about half-way moves the valve down. This partly closes the outlet and uncovers the first **weakening (air) holes** [otwory zubożające] ([F125] p.63). Further travel uncovers the second set.

**Position C: off.** The valve isolates the starter channel completely ([WZ] §2.1.5; [F125] p.63).
- [RELATED] If the valve does not seal, the vacuum piston ensures that **only air**, not fuel, can be drawn through ([F125] p.64). A leaking valve therefore usually shows as a slightly **lean or high** idle rather than a rich one. Rich running "on the choke" usually means the valve is **not reaching position C**.

**Key consequence** [FACTORY]: "urządzenie rozruchowe działa tylko przy zamkniętej przepustnicy". The device works **only with the throttle closed**, so **do not press the accelerator while cold-starting** ([Z94] §3.11). Pressing it lowers the vacuum at the starter outlet. [RELATED] Pumping the pedal before a cold start also needlessly enriches the mixture and **lowers the float-bowl level** ([F125] p.216).

## 2. Factory instructions for use

[FACTORY] [Z94] §3.11–3.12:

1. **Cold engine** (one at ambient temperature):
   - Pull the knob **fully out**, except in the warm season. Gear in neutral; the clutch pedal pressed helps.
   - Crank for **5–10 s**. Up to **5 attempts** are allowed, at least **60 s apart**.
2. **Flooded engine:** if it has not started after 5 attempts, **push the knob fully in** and crank with the **accelerator floored**.
3. **Warming up:** keep the knob out until the engine runs evenly. Then **push it in half-way**. Push it **fully in** once the engine is sufficiently warm.
   - If it stalls, restart with the knob out.
   - Do not load the engine or rev it hard while warming.
4. **Long driving with the starter on is harmful** and raises consumption ([Z94] §3.11). [FACTORY] Z89 lists it among the causes of high consumption ([Z89]).
5. **Warm engine:** do **not** use the starter; press the accelerator **lightly** while cranking ([Z94] §3.11).
6. **Very cold (about −20 °C)** [FACTORY]: the manual even describes warming the engine with hot water and pouring hot water over the **inlet manifold** before starting ([Z94] §3.12).

[RELATED] The 34 DCHD book adds a practical warm-up method ([F125] p.215):
- Push the knob in **slowly**, as soon as the engine starts to run unevenly from richness.
- If the engine stumbles, pull it out a little again.
- The timing is right when pushing the knob in keeps the engine running evenly.

## 3. Owner practice [FORUM]

- **Summer:** "teraz to max 1/3 rano, albo wcale". In summer pull it at most one-third in the morning, or not at all; pull it fully only in winter. Over-choking and a blipped pedal flood the S-21 (zukostrazak, [FPD t=4084]).
- **20 °C still counts as cold** for the S-21. If it starts and runs without any choke at 20 °C, "można się martwić" ("you can start worrying"): it suggests a rich mixture (Marian, [FPD t=777 p16]).
- **Starting on half-choke** often runs more smoothly than full choke, which is often too rich (Marian, [FPD t=1610]).
- **Short trips:** use the minimum choke that stops the bucking, about 5 minutes, then fully off. A member's advice: pull just a little when it bucks, then push in again (hakin1 and kazik12, [FPD t=4256]).
- **Cold-lean period after the choke goes off:** a sluggish engine for a few minutes is typical S-21 behaviour. "to nie wtryskowiec" ("it's not fuel injection"; Strucelsw, [FPD t=4713]).

## 4. Cable setup and adjustment

**Factory set-up** [BOOK] ([WZ] §2.1.5, Fig. 2.28; image `images/u-wz-fig2-28-zuk-throttle-and-starter-cable-linkage.jpg`):
- The starter is worked by a **cable (8)** from a knob on the cab's engine cover.
- **Adjustment rule:** with the carb lever pressed against its **stop on the starter cover** (position C), clamp the inner wire so that the cab knob stops **2–3 mm short** of its housing when pushed in.
- That reserve guarantees the device always reaches "off". The lever travels 68° from A to C ([WZ] Table 2.18, see `specs-and-jets.md`).

**Where it is clamped** [FACTORY]: Z94 Rys. 4.9 shows item 17 (starter lever), item 18 (cable) and **item 19, "śruba regulacyjna cięgła"**, the clamp screw on the lever that holds the wire ([Z94] Rys. 4.9; image `images/t-28-35-s2b1-view-legend-zuk-manual-1994.jpg`). The outer casing is held in a clip on the carb.

**Procedure** [BOOK + GENERAL]:
1. Knob fully in, with a 2–3 mm gap at the dash.
2. Push the carb lever by hand to its **off stop**.
3. Tighten the clamp screw.
4. Pull the knob fully out and check the lever reaches its **full-on stop (A)**. If it does not, the outer casing is clamped too far back, or the knob travel is too short.
5. Push it back in and check the lever **returns to the off stop** by itself. Nothing should be keeping it off its stop: the lever has a return spring.

**Faults to look for:**
- **Not enough slack**, so the lever never reaches off: "jazda na półssaniu, mimo cięgna wciśniętego". You drive on half-choke with the knob pushed in. The result is black smoke, high consumption and popping in the exhaust (Marian's checklist, [FPD t=2247]).
- **The cable does not push the lever back fully**, so you drive on half-choke. This washes the oil film off the bores and dilutes the oil with petrol ("olej śmierdzi paliwem", the oil smells of fuel) (nysanek, [FPD t=2222]).
- **A kinked cable** held the choke partly on after refitting. Hard starting stopped once found (Lukpau, [FPD t=4084] snippet p=53049).
- **The inner wire slipped out of its clamp** at the carb (Lukpau, [FPD t=3967] snippet p=52970). Tighten screw 19 properly and bend the wire end.
- **Hot cables during cranking:** the throttle rod and the choke cable got hot while starting. Cause: **poor engine earth**, so the starter current found a path through the cables. Fixed with an extra earth strap (Krzysiek-O, [FPD p=53003]). **Very relevant on an engine swap such as the GAZ-69.**

**GAZ-69 adaptation** [GENERAL, inference]:
- The GAZ-69's own choke knob can drive the Weber starter lever if it gives enough travel for the full 68° and returns positively.
- Route the cable without tight bends, and clamp the outer casing on the carb's own clip.
- Set the 2–3 mm reserve as above.
- No source gives the cable stroke in mm. **Gap**; measure lever A–C travel at the clamp hole.

## 5. Faults of the device itself

| Symptom | Cause | Remedy | Source |
|---|---|---|---|
| Cold engine **will not start** | Starter valve stuck; **starter fuel jet blocked** | Remove and check the valve; clean the jet | [FACTORY] fault table ([Z94] Table 4-2; [Z89]) |
| High consumption, rich running | Starter **stays partly on** | Check the cable and the valve return; clean the starter channels | [FACTORY] [Z94]; [Z89] |
| Fuel spraying from the carb onto the exhaust manifold | Starter cover fixed with **2 of its 3 screws**, leaving a gap | Fit all screws and a good gasket | [FORUM] Drewniany, [FPD p=27531] |
| The small piston and spring keep **popping out** after reassembly | Missing **retainer** | A new retainer (about 5 zł) | [FORUM] [FPD t=3995] (O22 in `owner-reports.md`) |
| Runs worse on choke than without; dies on choke | Flooding: float too high, or the needle not sealing; or the choke not releasing | Float level, needle valve | [FORUM] [FPD t=4392] (O9) |
| Choke needed only for seconds, then it chokes | Possibly **I/II main jets swapped** (too rich), or a high float | Check the jets | [FORUM] [FPD t=4814] |

**Bench test for valve leakage** [RELATED] ([F125] p.66; image `images/u-related-34dchd-pump-checks-fig2-67-68-fiat125p-book.jpg`):
1. Starter **off**, carburettor turned **upside down**.
2. Fill the starter **outlet channel** with fuel.
3. It must **not drain in less than 3 minutes**. If it does, clean or replace the valve and seat.

Also check that the valve moves freely without catching ([F125] p.66).

**Cleaning** [FACTORY]: blow the starter channels and jets through with compressed air; never use wire ([Z94]; [WZ]).

## Sources

[Z89]: https://archive.org/download/fsc-lublin-instrukcja-obslugi-zuk/FSC_LUBLIN-1989-instrukcja_obslugi_Zuk.pdf
[Z94]: https://archive.org/download/fsc-lublin-instrukcja-obslugi-zuk/FSC_LUBLIN-1994-instrukcja_obslugi_Zuk.pdf
[WZ]: https://archive.org/download/zukowka-zuk-spare-parts-catalog/ZUK-BEN-angielski.pdf
[F125]: https://archive.org/details/PolskiFiat125pBudowaEksploatacjaNaprawa1982
[FPD t=4084]: https://forum.polskiedostawczaki.pl/viewtopic.php?t=4084
[FPD t=777 p16]: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=225
[FPD t=1610]: https://forum.polskiedostawczaki.pl/viewtopic.php?p=49976#p49976
[FPD t=4256]: https://forum.polskiedostawczaki.pl/viewtopic.php?t=4256
[FPD t=4713]: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4713
[FPD t=2247]: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=2247
[FPD t=2222]: https://forum.polskiedostawczaki.pl/viewtopic.php?t=2222
[FPD t=3967]: https://forum.polskiedostawczaki.pl/viewtopic.php?p=52970#p52970
[FPD p=53003]: https://forum.polskiedostawczaki.pl/viewtopic.php?p=53003#p53003
[FPD p=27531]: https://forum.polskiedostawczaki.pl/viewtopic.php?p=27531#p27531
[FPD t=3995]: https://forum.polskiedostawczaki.pl/viewtopic.php?f=16&t=3995
[FPD t=4392]: https://forum.polskiedostawczaki.pl/viewtopic.php?f=16&t=4392
[FPD t=4814]: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4814
