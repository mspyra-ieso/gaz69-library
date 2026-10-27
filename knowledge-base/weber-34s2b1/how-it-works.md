# How the carburettor works

## Sources

- **Z85:** 1985 FSC Żuk owner's manual, which covers the 34S2B1. https://archive.org/download/fsc-lublin-instrukcja-obslugi-zuk/FSC_LUBLIN-1985-instrukcja_obslugi_Zuk.pdf
- **Z89:** 1989 FSC Żuk owner's manual. Same archive URL with `FSC_LUBLIN-1989-instrukcja_obslugi_Zuk.pdf`.
- **Z94:** 1994 FSC Żuk owner's manual. Same archive URL with `FSC_LUBLIN-1994-instrukcja_obslugi_Zuk.pdf`.
- **WZ:** Wiejak & Zagaja, *Żuk – budowa, eksploatacja, naprawa*, 1992 edition. It describes the **28/35 S2A1 and S2B1**. Read via an unofficial English machine translation: https://archive.org/download/zukowka-zuk-spare-parts-catalog/ZUK-BEN-angielski_djvu.txt

The 34S2B1 has the same layout as the 28/35 types: progressive mechanical secondary, piston-type starter, and the same kind of float and needle valve. Differences:
- The 34S2B1 has equal 34 mm bores and equal 25 mm venturis.
- No idle solenoid or economiser is shown for it in Z85.

The circuit descriptions below are factory or book descriptions of the 28/35 family. They should apply to the 34S2B1 in principle, but this is not confirmed for every detail.

## 1. General layout

- **Type:** downdraught (opadowy), twin-barrel (dwuprzelotowy).
- **Venturis:** each throat has a primary venturi (gardziel wstępna) and a main venturi (gardziel główna). Z85: "z gardzielami wstępną i główną".
- **Throttle control:** the driver's pedal moves only the **primary (I) throttle**.
- **Float chamber and cover:** the float chamber is on one side of the body. The cover (pokrywa) carries:
  - a mesh fuel filter under a hex plug (korek filtru, element filtrujący),
  - the needle valve (zawór iglicowy),
  - the hinged float (pływak).

  Source: Z85 p.49, `images/a-34s2b1-float-level-and-exploded-zuk-manual-1985.jpg`.
- **Removable parts:** from outside you can remove the main jets with their holders (obsady), the idle jets, and the accelerator pump injector. The cover lifts off with the float.
  - Z85 Rys. 4.11 ("dopuszczalny demontaż", i.e. permitted dismantling) shows cover, gasket, idle jets, main jets, float, filter plug, filter element and pump nozzle.
  - The 28/35 version (WZ fig. 2.50) also shows the solenoid valve and a "wtryskiwacz pompy przyspieszającej z zaworem kulkowym" (pump injector with ball valve).

## 2. Progressive secondary: mechanical, not vacuum (factory 34S2B1)

- **Factory wording (Z85):** the secondary throttle is opened mechanically by a lever system from the primary spindle, and starts opening only at 2/3 of primary travel. Polish: "sterowane mechanicznie przez układ dźwigniowy z osi przepustnicy I przelotu".
- **Mechanism (WZ, 28/35):** a stop lever on the primary spindle has a hook that first moves freely in a notch of the **release lever (dźwignia zwalniająca)**. Further rotation picks up the release lever, which drives the lever on the secondary spindle until the secondary is fully open. Total primary-lever rotation is 78°.
- **What this means:** the secondary opens only near full throttle. Its condition does not affect idle or light-throttle running, except through air leaks past a worn secondary spindle or a secondary plate that does not close.
- **Vacuum-secondary claim:** some forum posts say the 34S2A1 has a vacuum-operated secondary. That is unconfirmed; see variants-and-history.md.

## 3. Main metering circuit with air correction

Source: WZ fig. 2.24.

1. Fuel flows from the float chamber through the **main jet (dysza główna paliwa)** into a well (studzienka) holding the **emulsion tube (rurka emulsyjna)**.
2. As speed and load rise, air enters through the **air-correction jet (dysza powietrza hamującego wypływ paliwa, "air braking the fuel outflow")** at the top of the well. It mixes with the fuel in the emulsion tube.
3. The emulsion is drawn through the **nozzle / auxiliary venturi (rozpylacz)** into the primary venturi and then the main venturi.

How the jets act:
- A bigger main jet makes the mixture richer.
- A bigger air jet makes it leaner, mostly at higher airflow.
- The emulsion tube type (F27, F30, F35) shapes how fast the mixture leans out as rpm rises.

Practical warnings:
- **Do not swap jets or tubes between barrels.** Z94 warns: "nie pomylić dysz głównych paliwa z I i II przelotu". (Do not mix up the main jets of throats I and II, which have different sizes.)
  - On the 34S2B1 the two main jets differ: 120 primary, 150 secondary.
  - The air jets and emulsion tubes are the same in both barrels (210 and F30).
- [FORUM] Strucelsw on forum.polskiedostawczaki.pl says tubes are often found swapped ("może rurki emulsyjne masz zamienione miejscami? często sie z tym spotykam"). https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3998

## 4. Idle and progression circuit

Source: WZ fig. 2.27, for the 28/35. The 34S2B1 has idle jets in both barrels (50/50, Z85).

- **At idle (throttles closed):**
  1. Fuel is taken from the primary emulsion well through the **idle fuel jet (dysza paliwa biegu jałowego)**.
  2. It mixes with air from the **idle air jet**.
  3. It flows down a channel to an outlet below the throttle plate.
  4. The **mixture screw (wkręt regulacyjny składu mieszanki)** sits in that outlet. On later carbs it was sealed with a cap after factory setting (WZ; Z94 "zaślepiony").
- **Slightly open throttle:** two 0.8 mm **progression holes (otwory przejściowe / progresywne)** above the primary plate are uncovered and add mixture.
- **When the secondary opens:** its own idle/progression system (fuel jet 100, air jet 80 on the 28/35) feeds through three holes (2 × 1.2 mm and 1 × 1.5 mm). This bridges the gap until the secondary main circuit starts.
- **Idle adjustment:** done on the **primary only**: "regulacja tylko w kanale głównym I przelotu" (Z85).
- **Why this matters after cleaning:** the idle jets are the smallest calibrated orifices (0.45–0.50 mm). A partly blocked idle jet or channel, or a blocked progression hole, gives:
  - stalling at idle,
  - hesitation just off idle.

  Z85's fault table lists "Zatkana dysza paliwa lub kanały wolnych obrotów" (blocked idle jet or idle channels) under rough idle. The fix it gives is to remove the jet and blow out the jet and channels with compressed air.

## 5. Idle cut-off solenoid (28/35 types only)

Source: Z89/Z94.

- **What it is:** the **EZ-20** electromagnetic valve (zawór elektromagnetyczny / elektrozawór). It carries the **primary idle fuel jet**. Shops call this the "elektrodysza".
- **Purpose:** stop run-on (dieseling) after switch-off: "eliminuje możliwość samozapłonu silnika po wyłączeniu stacyjki".
- **Behaviour:** with no 12 V at ignition-on, the needle closes the idle jet. The engine then won't idle, but runs at higher throttle.
- **Factory get-you-home trick (Z89):** if the valve fails, remove its needle, screw in the holder with the idle jet, and carry on driving. Polish: "można wyjąć jego iglicę, wkręcić obsadę z dyszą wolnych obrotów".
- **34S2B1:** Z85 shows no solenoid. If the owner's unit has one, it is a later or modified carb.
- **GAZ-69 swap note:** if a solenoid is fitted, it must get switched 12 V from the ignition.

## 6. Accelerator pump

Source: WZ fig. 2.25, 28/35.

- **Type:** a spring-loaded piston pump (tłoczek).
- **Filling:** it fills from the float chamber through a non-return ball valve when the throttle closes. The lever lifts the piston and compresses the pump spring.
- **Delivery:** on sudden throttle opening, the lever drops away and the **spring** (not the linkage) pushes fuel through a delivery valve to the **injector (wtryskiwacz / dysza pompki przyspieszającej)**, which sprays into the primary throat.
- **28/35 data:** jet 40, valve 80, stroke 10 mm, about 0.5 cm³ per stroke (5 cm³ per 10 strokes).
- **34S2B1 data (Z85):** pump jet 70. Stroke and volume are not given.
- [FORUM] The pump nozzle can siphon fuel and drip into the throat ("podsysanie paliwa przez dyszę pompki przyśpieszającej, paliwo kapie sobie"). Source: forum.polskiedostawczaki.pl t=3998.

## 7. Cold-start device (urządzenie rozruchowe), not a choke flap

Sources: WZ fig. 2.26; Z85/Z89 tables.

- **Type:** a separate **piston-valve starter**. It is worked by a cable from the cab to a lever on the round housing on the side of the carb.
- **Lever positions** (68° of travel):
  - **A:** fully on, for a cold start.
  - **B:** partly on, for a warm start.
  - **C:** off.
- **How it works:**
  1. Fuel goes from the float chamber through the **starter fuel jet (F1/150)**.
  2. It is emulsified with air from the **starter air jet (150)**.
  3. It mixes with more air in the piston chamber.
  4. It is fed below the throttle plate through its own channel.
- **After the engine fires:** manifold vacuum opens a small **air valve** that leans the starter mixture, to prevent flooding.
- **As the engine warms:** the piston gradually closes the outlet channel, until it is fully closed at position C.
- **Cable adjustment (WZ):** with the lever against its stop on the starter cover, the knob should still stand 2–3 mm short of its socket. This guarantees the starter is fully off.
- **Faults (Z85 table):**
  - A cold engine won't start: starter valve stuck, or starter jet blocked.
  - Hot-engine problems: the starter is left on because the piston is stuck ("Urządzenie rozruchowe pozostaje stale włączone ze względu na zacięcie się tłoka urządzenia"). This makes the engine run rich.
- **Pump-pumping is not a substitute for the starter:** Z85 advises starting a **hot** engine with the pedal held half down until it fires.

## 8. Economiser / enricher (28/35 S2B1 only)

Source: Z94.

- **Type:** "gravity type" (typu grawitacyjnego) on the **secondary** throat. It has a fuel jet of 80 and a nozzle of 2.5.
- **What it does:** it adds fuel when the secondary throttle passes **half open**, giving full power while keeping part-load economy.
- Neither Z85 (34S2B1) nor Z89 (28/35 S2A) lists it.

## 9. Float system

- **Needle valve:** 1.75 mm seat (175). It has a **spring-loaded ball damper in the needle** (amortyzator drgań iglicy / kulka) so vibration doesn't open it.
- **Float:** about 18 g, hinged on a spindle in the cover.
- **Adjustment points:**
  - Bend the **hinge arms / tongue (języczek)** to set the float-to-cover distance.
  - Bend the **travel stop (występ, ogranicznik skoku)** to set the maximum drop.
- Values and procedure: see adjustment-procedures.md.
- Typical faults (Z85 table):
  - A leaking needle valve causes flooding.
  - A damaged float (a holed float sinks) causes flooding.
  - A wrong level, or a float that binds, causes poor running.

## 10. Other connections

- **Distributor vacuum-advance port:** "króciec przewodu podciśnieniowego regulatora aparatu zapłonowego" (Z85 item 3). If this pipe is left open or connected to the wrong place in a swap, there is an air leak or wrong timing advance.
- **Crankcase ventilation valve (WZ, S-21):** the PCV piston valve on the inlet manifold is **worked by a lever from the carburettor throttle spindle**.
  - At idle the valve is closed and blow-by goes only to the air filter.
  - At part load it opens to the manifold.
  - In a GAZ-69 conversion, a missing or mis-set link here, or an open PCV port, would cause idle mixture problems.
  - [FORUM] Strucelsw also lists "drożność zaworka odmy w kolektorze" (a clear manifold breather valve) among checks for a rich mixture.
- **Mounting:** four M8 nuts on studs. Between the carb and the manifold flange there are **two gaskets and one insulating spacer** (WZ, 28/35).
  - Z85 lists air leaks at these gaskets or the spacer, and between the manifold and the head, as causes of rough idle.
  - It also says a warped carb flange should be ground flat.
- **Air filter:** dry paper element. It has a summer/winter flap that chooses cold air or exhaust-heated air (Z94; WZ). [FORUM] Strucelsw advises checking that the flap isn't stuck on the warm-air setting ("sprawdz jeszcze czy nie chodzi na ciepłym powietrzu").
