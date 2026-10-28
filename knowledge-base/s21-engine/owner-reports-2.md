# S-21: Owner Reports, Part 2 (gap research, October 2026)

This page adds to `owner-reports.md` (OR-01 to OR-65) and `gaz69-s21-owner-reports.md`. Numbering continues as **OR2-xx**.

All cases come from forum.polskiedostawczaki.pl threads not used before. **elektroda.pl could not be reached** (every request timed out), so no elektroda cases are included. See `sources-gaps.md`.

**Status:**
- **CONFIRMED** means the owner reported that the fix worked.
- **SUGGESTED** means other members' advice, not yet verified.

Offline text copies of each thread are in `source-archive/s21-gaps/` (outside the repo).

## Electrics

**OR2-01. Starter turns twice slowly, pauses, repeats. Sparks at the clutch-pedal spring.** Żuk (S-21 era; hand-crank mentioned).
- **Cause:** **The engine had no earth.** A co-owner had painted the clutch housing, so the starter current returned through the clutch-pedal spring.
- **Fix:** Jumper from battery − to the engine. Connectors were replaced.
- **Status:** CONFIRMED.
- **Quote:** "Silnik nie miał masy." / "Problem rozwiązany."
- **Also suggested (SQ1SGB):** The engine's main strap is under the clutch housing. Test in stages with jump leads: battery to frame, then frame to engine.
- **Source:** https://forum.polskiedostawczaki.pl/viewtopic.php?f=7&t=2295

**OR2-02. Starter clicks only ("cyk").** Żuk (general advice; thread includes a 4C90 diesel).
- **Fix:**
  - Tap the solenoid lightly.
  - One owner cured it by cleaning the battery clamps, cables, starter terminals and frame earth.
- **Status:** CONFIRMED (cleaning).
- **Quote:** "u mnie pomogło jak przeczyściłem klemy akumulatora"
- **Source:** t=2295 (above)

**OR2-03. Same owner as OR2-01, later: starter dead. On a push start the engine chokes when revved and backfires in the manifold.**
- **Notes:**
  - Members suspected a worn-out engine.
  - The owner had swapped an electronic-module distributor back to points because of problems with it.
  - The solenoid tested fine off the starter, so the fault was inside the starter.
- **Status:** SUGGESTED / unresolved.
- **Quote:** "Zaplon tak sie nieprzestawi nigdy zeby byla takie objawy." (timing never shifts by itself to give such symptoms)
- **Source:** https://forum.polskiedostawczaki.pl/viewtopic.php?f=7&t=2295&start=15

**OR2-04. Weak cranking; lights die when the key is turned; ignition switch won't stay in position 2; no charging.** Żuk A07D 1996 (diesel, but the wiring is the same).
- **Advice:**
  - Replace the ignition switch first.
  - Check the battery and isolator.
  - Run a new earth straight to the engine. One member had cured a weak earth this way.
- **Status:** SUGGESTED.
- **Quote:** "masa z akumulatora była słaba. Po prowadziłem nowa bezpośrednio do silnika"
- **Source:** https://forum.polskiedostawczaki.pl/viewtopic.php?f=7&t=4257

**OR2-05. After an alternator swap: fuse blew, then no charging and no indicators; only the ammeter worked.** Żuk pickup (2020).
- **Cause:** The wire feeding the gauges and regulator fuse had **burnt out inside its insulation**.
- **Status:** CONFIRMED.
- **Quote:** "wypalił się w środku przewód idący do bezpiecznika zabezpieczającego wskaźniki"
- **Also in the thread:**
  - Strucelsw: the Żuk has **no factory body-to-frame earth**, so add one. Quote: "żuk nie ma jednej masy- z nadwozia na rame, trzeba ją dorobić."
  - buźka: on the S-21 the strap can go to one of the two **upper clutch-housing bolts**. Quote: "w S-21 wystarczy do jednej z dwóch górnych śrub na obudowie sprzęgła"
- **Source:** t=4257 (above)

**OR2-06. Charging fell from over 14 V to about 12.5 V at idle; lights flickered.** Nysa/Żuk with a 9-diode alternator.
- **Cause:** Excitation was fed from switched + after the ignition switch instead of **through the charge warning lamp**.
- **Fix:** Rewired to the correct diagram.
- **Status:** CONFIRMED that the alternator was OK ("temat zamknięty, alternator sprawny"). It is unclear whether the flicker stopped.
- **Quote:** "wzbudzenie nie przez kontrolkę tylko z plusa po stacyjce"
- **Source:** https://forum.polskiedostawczaki.pl/viewtopic.php?f=7&t=578&start=90

**OR2-07. Temperature gauge goes to maximum 2–3 s after a cold start.** Żuk.
- **Suspects:**
  - the sender (most common);
  - a chafed sender wire shorting to earth;
  - a rusty or loose sender terminal.
- **Status:** SUGGESTED.
- **Quote:** "Pewnie czujnik do wymiany,bo to najczęściej pada."
- **Source:** https://forum.polskiedostawczaki.pl/viewtopic.php?f=7&t=2888

## Fuel

**OR2-08. Żuk S-21 on LPG ran the tank dry uphill. Afterwards it starts on LPG but not on petrol, because the pump won't draw.**
- **Cause:** Debris and scale in the pump; the suction valve failed.
- **Fix suggested:** New valves or a new pump, plus a filter. One member puts it between pump and carb on flexible hose; Strucelsw puts it before the pump.
- **Status:** SUGGESTED (owner about to do it).
- **Quote:** "padł zaworek ssący"
- **Source:** https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=195

**OR2-09. Żuk S-21: fuel return line added (cures a wet carb and fuel on the manifold when starting on choke).**
- **Fix:**
  - Tee after the pump.
  - Return to the tank through a diesel-Żuk sender unit.
  - 8 mm hoses, with the return restricted to about 5 mm.
  - Tested with both mechanical and electric pumps.
- **Status:** CONFIRMED.
- **Quote:** "Powrót paliwa w moim S21 zrobiony i działa to super."
- **Source:** same thread as OR2-08

**OR2-10. E10 and older Żuks (discussion).**
- **Advice:**
  - Change the pump diaphragm and rubber hoses more often.
  - Boiling is blamed on ethers.
  - Use a stabiliser if the vehicle stands.
  - Valve seats are fine on unleaded or LPG if the clearances are kept.
- **Status:** SUGGESTED.
- **Quote:** "częściej wymieniać membranę pompy paliwa i gumowe przewody"
- **Source:** https://www.forum.polskiedostawczaki.pl/viewtopic.php?f=13&t=5471

## Engine

**OR2-11. S-21 power and head skimming (discussion).**
- **Advice:** Skimming the head is discouraged. Boring to 88 mm with GAZ pistons is mentioned, with a warning.
- **Status:** SUGGESTED.
- **Quote:** "odradza sie w silnikach S-21 planowania glowicy"
- **Source:** https://forum.polskiedostawczaki.pl/viewtopic.php?p=7002&t=437

## Count and patterns

- **11 new cases or discussions**: 7 electrics, 3 fuel, 1 engine. 5 are CONFIRMED.
- **Pattern:** Bad **earths** (a painted clutch housing, no body-to-frame strap, a weak battery earth) caused slow or intermittent cranking and charging faults. That is the most repeated electrical lesson.
  - It matters even more on a GAZ-69 swap, where the S-21 sits on rubber mounts.
  - See the checklist in `electrics.md` §6.
