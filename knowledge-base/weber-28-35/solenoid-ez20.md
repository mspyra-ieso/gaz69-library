# EZ-20 idle cut-off solenoid (elektrozawór / "elektrodysza")

The source keys are defined in specs-and-jets.md. Factory facts are marked [FACTORY]; forum facts are marked [FORUM].

## 1. Identity and parts

- **Factory name:** "Zawór elektromagnetyczny (EZ-20)", part **033845**, one per carb. The kit around it:
  - primary idle fuel jet **45**, part **033842**, screwed into the solenoid tip;
  - **sealing ring** [pierścień uszczelniający], part **033844**.

  Source: [FACTORY] CAT88 table 11.07, items 67–69 (`t-28-35-s2a1-ez20-and-repair-kits-parts-catalogue-1988-p3.jpg`).
- **S2B1 numbering:** the complete valve is 435.28.030.02. It consists of "Elektromagnes /EZ-20/" 033845, idle jet I "45" 435.28.182.04 and sealing ring 033844. Source: [FACTORY] BI11 items 60–63.
- **The same EZ-20 coil is used on the S2A, S2A1 and S2B1.** Z89 and Z94 list "elektrozawór EZ-20" in the idle row of the jet table.
- **Sealing-ring size:** the catalogue gives **no dimensions** for ring 033844. A "6 × 2 mm O-ring" figure **could not be confirmed** in any source found.
- **Ring condition:** the ring is in the factory small repair kit CZ-37.09 (item 68), which shows it is a normal wear item. A leaking ring lets fuel bypass the idle jet, giving a rich idle. That consequence is an inference, not a source statement.

## 2. What it does and how it works

- **Purpose [FACTORY]:** stop run-on (dieseling) after switch-off with poor fuel or a hot engine. Z89: "eliminuje możliwość samozapłonu silnika po wyłączeniu stacyjki". Z94 says the same.
- **Mechanism [FORUM, plausible]:** the solenoid is really a jet that opens when voltage is applied. With no voltage, a spring pushes a cone (needle) inside against the jet and stops the flow. With the ignition on, the needle is pulled back and the idle jet works.
  - Marian, FPD t=4635: "Jak nie ma napięcia sprężyna dociska stożek od wewnątrz dyszy".
  - WZ Fig. 2.27 legend also shows a "zawór elektromagnetyczny" (68) with a valve needle "iglica zaworu" (69) at the primary idle jet.
- **It only cuts the idle circuit.** It closes the primary idle jet and nothing else; the main jets keep flowing.
  - [FORUM] Strucelsw, t=4279: "on odcina tylko dyszę wolnych obrotów".
  - It **cannot** be used to empty the float chamber, for example for LPG.
- **Symptom of no power or a stuck solenoid:**
  - the engine will not idle and stalls when the throttle closes;
  - it runs on throttle, because the main and progression circuits are not cut.

  This follows from the layout above (WZ idle-circuit description).

## 3. Wiring (+12 V switched by the ignition)

- **[FACTORY] Z89, Rys. 4.17 (ignition coil):** item 10 is "przewód do elektrozaworu gaźnika". The wire to the carb solenoid runs **from the ignition coil's low-tension (+) terminal**, which is live with the ignition on. Item 3 in the same drawing feeds that terminal from ignition-switch terminal **15**. Image `t-ez20-wire-at-ignition-coil-zuk-manual-1989.jpg`.
- **[FORUM] buźka, FPD t=3091 (2016):** the wire originally comes from the coil's low-voltage B+ terminal, i.e. "tam, gdzie pojawia się napięcie po kluczyku" (wherever voltage appears after the key).
- **[FORUM] sukiennik68, t=4279:** "sterowany stacyjką" (controlled by the ignition switch).
- **[BOOK] WZ wiring diagrams** list "elektrozawór gaźnika" as its own load next to the coil (items 10, 71 and 18 in the various Żuk diagrams).
- **Earth return:** the solenoid has one spade terminal, so it returns to earth through its thread and the carb body. The carb sits on an **insulating spacer** between two gaskets (CAT88 table 11.10 items 8–9). The earth path is therefore through the studs, nuts and linkage.
  - This is an inference from the parts list: no source discusses solenoid earthing.
  - In a swap, check continuity from the carb body to engine earth.

### GAZ-69 swap notes (inference, not sourced)

- Feed the solenoid from a wire that is live only with the ignition on, for example the coil + terminal as the Żuk does. Use a fused wire if you take it elsewhere.
- A permanent feed would make the engine run normally, but you would lose the anti-run-on function. A missing feed gives no idle.

## 4. Testing

No factory test procedure was found. The following is common practice, not from a factory source:

1. With the ignition on, pull the spade connector off and push it back on. An audible click from the solenoid means it moves.
2. On the bench, apply 12 V between the terminal and the body. The needle should retract.
   - Check that the jet orifice is clear: hold it up to the light, or blow through it with air when energised.
   - Do not push wire or a drill through the jet: WZ forbids cleaning jets with steel objects.
3. Check the voltage at the connector with the ignition on, while cranking and while running.

## 5. Failure work-arounds and substitutes

- **[FACTORY] Z89 get-you-home:** if the solenoid fails, you may "wyjąć jego iglicę, wkręcić obsadę z dyszą wolnych obrotów" and keep driving. That is: take out its needle, screw the holder back in with the idle jet, and continue.
- **[FORUM] Strucelsw, t=4279:** either replace it with a plug-type jet holder [korek-obsada], or cut off the needle pin [bolec zaślepiający].
- **[FORUM] warning (Marian, t=4635):** do not wreck working solenoids, because they are becoming scarce ("coraz bardziej towar deficytowy").
  - One owner tore off the tip and lost the idle jet, which **is** the tip: "To była dokładnie dysza biegu jałowego".
- **Substitutes [FORUM]:**
  - Owners report the body looks like the **Fiat 126p** "elektrodysza", and that the same solenoid type was used on 126p and Polonez carbs, **differing only in the tip jet** (juR, t=4635).
  - **Using a 126p solenoid on a Żuk means fitting jet 45.** Many 126p units carry a different jet, for example 50.
  - Measured by one owner (juR, t=4635, 2019) on a replacement screw-in holder with jet: **thread M8×1**, total length 22.0 mm, jet length 14.0 mm. The jets in both the solenoid and the plain holder are replaceable. He bought 126p jets in sizes 45 and 50.
  - These are single-owner measurements; check them against your own part.

## 6. Where it sits

- **Z94 Rys. 4.9:** item 9 is the "zawór elektromagnetyczny (EZ-20) z dyszą paliwa biegu jałowego", on the body next to the float chamber (`t-28-35-s2b1-view-legend-zuk-manual-1994.jpg`).
- **Z89 Rys. 4.9:** item 10 is "elektrozawór i dysza paliwa wolnych obrotów".
- **Book scan:** the solenoid is item 3 on the 28/35 S2A1 perspective drawing, next to the two idle screws 1 and 2 (`t-28-35-s2a1-idle-screws-solenoid-book-scan-pd.jpg`).
- **Cleaning [FACTORY] Z94:** the idle jet is reached "po wykręceniu zaworu 9", i.e. by unscrewing the solenoid.
