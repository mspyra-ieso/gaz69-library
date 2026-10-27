# Weber 34S2B1 (Polmo) on FSO S-21: troubleshooting by symptom

These notes cover the Polmo-licensed Weber twin-choke carburettors fitted to the S-21 engine (Żuk, Nysa, Tarpan, Warszawa 223/224). Most owner sources just say "Weber" or "gaźnik" without naming the variant. Where a source is about the sister **28/35 S2A1**, or names no variant, that is stated. The 34S2B1 and 28/35 S2A1 share their basic layout: accelerator pump (pompka przyspieszająca), float bowl, needle valve and idle screws. Per the factory manuals, though, only the 28/35 types have the idle cut-off solenoid (elektrozawór). The 34S2B1 has plain idle jets (50/50) and a piston cold-start device instead of a choke flap. Jet sizes and venturis also differ (see `specs-and-jets.md`). Solenoid-related tips below apply to the 28/35 only.

Labels used below:
- **[DOC]**: a documented fact, a shop listing or a measurement stated by a source.
- **[FORUM]**: an owner or mechanic opinion or experience.
- **[GENERAL]**: general carburettor practice, given without a S-21-specific source.

Main forum: forum.polskiedostawczaki.pl (FMPD). Its regular experts are "Strucelsw" (runs a workshop), "Marian" (admin) and "nysanek".

---

## 0. Always rule out ignition first

- **[FORUM]** A Nysa would not start after unrelated engine work. The plugs were wet, and it gave bangs (wystrzały) into the intake manifold. The cause was ignition timing knocked out during reassembly, not the carburettor. Marian's checklist: firing order 1-2-4-3, valve clearance 0.20–0.22 mm, points gap, coil, HT leads, cap and rotor. Use a conventional coil, not an electronic one, with points. Source: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=2247
- **[FORUM]** Spark plugs: Strucelsw blames counterfeit NGK plugs for misfires and sooting and recommends Denso WF20TT. Marian uses Denso W20FS, and sukiennik68 recommends Iskra F75. Plugs that are too cold, such as NGK B6HS or B5HS, soot up on the S-21. Sources: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4814 and https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3139

## 1. Won't start (nie odpala / nie pali)

Check in this order:

1. **Fuel reaching the bowl.** Remove the fuel line at the carburettor and crank, or use the hand-prime lever on the mechanical pump. Fuel should pulse out.
   - **[FORUM]** A sticky mechanical fuel pump (pompa paliwa) whose lever did not follow the camshaft eccentric made a Żuk start, run a few seconds and die. Fitting another pump fixed it, although stripping the old pump showed nothing visibly wrong. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=5136
   - **[FORUM]** A cracked or worn pump diaphragm gives lean running, flooding and power loss on hills. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=30 and the snippet list at https://forum.polskiedostawczaki.pl/search.php?keywords=membrana+gaźnik&terms=all&sf=all
2. **Pump the throttle a few times and look down the primary throat** with the air filter off. You should see a squirt from the accelerator pump nozzle.
   - No squirt means a missing or blocked pump nozzle, a missing ball, or a split pump diaphragm. See "Hesitation" below.
3. **Idle cut-off solenoid (elektrozawór) powered and clicking.**
   - **[FORUM, Marian]** With no voltage, a spring pushes a tapered needle into the idle jet and the engine will not idle. It also won't start without the throttle open. It must receive +12 V with the ignition on. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4635
   - **[FORUM, sukiennik68]** It is an anti-run-on valve fed from the ignition switch. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4279
   - Test: with the ignition on, unplug and replug the wire. You should hear a click. Alternatively, remove it and apply 12 V on the bench; the needle should retract.
   - The idle jet (dysza biegu jałowego) is carried **on the tip of the solenoid**. One owner snapped the tip off while "cleaning", and with it the idle jet. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4635
4. **Is the passage clean?** **[FORUM]** A Weber 28/35 S2A that would not start after a first clean ran only after a second, thorough clean. It was soaked in cleaner and heated, twice, and a lot of debris came out of the internal channels. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4635&start=15
5. **Flooded?** If the plugs are wet and black, see "Floods" below.
6. **Choke (ssanie).** The choke must close fully when cold and open fully when warm. **[FORUM]** On these units the choke is the small lever worked by a cable. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4279
7. **Crack in the carburettor body.** **[FORUM, Antek123]** Cracked carburettors were a common fault on S-21s run on LPG. It is worth trying a known-good spare to test. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=5136

## 2. Starts, then dies after a few seconds (odpala i gaśnie)

- **Classic sign of no fuel supply.** The engine burns what is in the bowl, or what the accelerator pump squirted, then starves. Check the fuel pump, the filter, the tank pickup and the inlet filter screen (sitko) in the carburettor.
  - **[FORUM]** In the Nysa case above, the owner had already replaced the float, the needle and the pump diaphragms. Pouring fuel down the throat kept it running, and a replacement pump cured a similar Żuk. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=5136
- **Needle valve stuck shut or float jammed** after reassembly, for example with the float rubbing on the bowl wall. **[GENERAL]**
- **Idle circuit dead**, so the engine runs only with the throttle held open. Causes: the solenoid is unpowered, the idle jet is blocked or missing, or the idle passage is blocked. **[FORUM]** The idle jet clogged twice on the same Nysa. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3998
- **Choke released too early, or not working.**
- **[FORUM, Lodowy Żuczek thread]** Engine runs on choke when cold, then dies. Listed causes: flooding (choke not releasing fully, or float too high), ignition, or the elektrozawór. https://forum.polskiedostawczaki.pl/viewtopic.php?f=16&t=4392

## 3. Floods / runs rich / black smoke / sooted plugs (zalewa, kopci na czarno)

1. **Needle valve (zaworek iglicowy) leaking or stuck open.**
   - **[FORUM]** A Żuk A15B had fuel under the manifold and the needle was stuck open. Cleaning it stopped the idle stumble. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4814
   - **[FORUM]** On a Nysa 28/35 S2A1, fuel dripped when hand-pumping. A new needle cured it. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3998
   - **[FORUM, Strucelsw]** Leaking needles are common on these carburettors. Fit a needle with a spring damper (iglica z amortyzatorem). https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3139
2. **Float level too high, or float holed or soaked.** Fuel level should be about **6.5 mm** (Strucelsw). Check that the float is not leaking. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4814
   - **[FORUM, nysanek]** Plastic floats can absorb fuel and develop a hole. https://forum.polskiedostawczaki.pl/viewtopic.php?p=44947
3. **Primary and secondary main jets swapped (dysze zamienione).**
   - **[FORUM]** A Żuk A owner reported black smoke, fouled plugs and fuel spitting into the air filter. The mixture screw was fully in and still too rich. Cause: he had **fitted the jets the wrong way round** after cleaning. Correcting them cured most of it. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=15 and https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=30
   - **[FORUM, sukiennik68]** A swap of the first- and second-barrel main jets explains needing to take the choke off within seconds of starting. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4814
4. **Emulsion tubes swapped (rurki emulsyjne).** **[FORUM, Strucelsw]** On the 28/35 S2A1 they are F27 (the thicker one) in the 1st barrel and F35 in the 2nd. Check they are not swapped. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3998
5. **Fuel leaking around the solenoid.**
   - **[FORUM, Strucelsw]** A damaged solenoid **O-ring (6×2 mm)** or a crushed idle jet lets fuel bypass the jet and enrich the mixture.
   - Test: if the engine keeps running with the mixture screw fully in, there is extra fuel from somewhere (float, needle or O-ring).
   - Source: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4814
6. **Accelerator pump nozzle dribbling.** **[FORUM]** It can drip fuel into the throat. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3998
7. **Choke not fully opening, or air filter clogged or oily.** **[FORUM checklist, nysanek and Marian]** https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777 and https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=2247
   - The same checklist warns against **cleaning jets with wire**, which enlarges them and makes the mixture rich.
8. **Brake servo leak (an unusual case).** **[FORUM]** On a Nysa with poor CO readings, the readings improved after a leaking brake servo and master cylinder were replaced. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3998

Owner-measured data point (Nysa, Weber 28/35 S2A1, 2018): CO was above 7% before the fixes. After fitting a new needle, setting the float and changing to a 110 primary main jet, idle CO was 2.4%. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3998

## 4. No idle / idle won't adjust (nie trzyma wolnych)

- **Solenoid not energised, or idle jet missing or blocked.** See §1.3.
- **Mixture screw has no effect.**
  - **[FORUM]** This means a blocked idle circuit when nothing changes, or a flooding or leak path when it stays rich. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4814
  - **[GENERAL, elektroda]** If turning the screw changes nothing, a jet is likely blocked. https://www.elektroda.pl/rtvforum/topic2853624.html (generic, not about the S-21)
- **Air leaks (lewe powietrze)** at the base gasket, the manifold, loose nuts, vacuum hoses (distributor vacuum advance, breather) or the brake servo hose. **[FORUM checklist]** https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=2247
- **Worn throttle spindle** lets in air, so the mixture is uneven and keeps needing adjustment. **[FORUM, nysanek]** Said of the Jikov, but the same applies to any old carburettor. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777
- **Throttle plates not closing.** This can be a misadjusted idle stop screw, a bent secondary linkage, or a sticking spindle. **[GENERAL]**
  - Check with the air filter off that both plates shut. The secondary plate must also close fully. On the factory 34S2B1 it is opened mechanically from the primary spindle (see `variants-and-history.md`); on a vacuum-secondary unit, by its diaphragm.

## 5. Hesitation / flat spot / stall on throttle (dławi się, przerywa, gaśnie przy dodaniu gazu)

- **Accelerator pump.**
  - **[FORUM]** A Żuk Weber was missing its **accelerator pump nozzle** in the float-chamber area. Strucelsw identified it as "fi 80 with a ball" (fi80 z kulką). https://forum.polskiedostawczaki.pl/viewtopic.php?f=15&t=5488
  - **[FORUM]** On the Jikov the non-return ball sits under the pump tube, and a perished pump diaphragm caused hesitation. Raising the float a little and replacing the diaphragm fixed it. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3139 (Jikov, but the same principle applies)
- **Small plungers and springs** that pop out during disassembly.
  - **[FORUM]** On a 1990 Żuk, a disassembled Weber "didn't work properly" because a small plunger and spring had come out. The owner found the retainer, which cost about 5 zł. https://forum.polskiedostawczaki.pl/viewtopic.php?f=16&t=3995
- **Float level too low**, a blocked main jet or a blocked economiser. **[FORUM, Strucelsw]** https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3139
- **The 34 can briefly stumble when the pedal is pressed at low rpm.** **[FORUM, seller's opinion]** The same seller says the 34 runs better on LPG, while the 28/35 is more economical. https://forum.polskiedostawczaki.pl/viewtopic.php?f=3&t=4733
- **Cold-engine response.** **[FORUM, Strucelsw]** Poor response for a few minutes after a cold start is normal for a lean, carburetted S-21. Marian disagrees and suspects a dirty carburettor. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4713
- **Secondary throat (druga gardziel) not opening.**
  - A split vacuum diaphragm or a disconnected link gives no power at high rpm. Idle and starting are unaffected. **[GENERAL]**
  - No S-21 forum case was found. The 28/35 S2A1 thread describes a mechanically linked secondary that opens later, The factory 34S2B1 is also mechanically linked (1985 Żuk manual). Only the 34S2A1 is said, in one forum post, to have a vacuum secondary. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4279

## 6. Backfire into the carburettor / smoke from the air filter (strzela w gaźnik, dym z filtra)

- **Lean mixture.** Causes: air leaks, low float level, clogged jets, weak pump. **[FORUM checklist]** https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777 and https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=2247
- **Ignition timing wrong, or HT leads crossed.** Firing order is 1-2-4-3. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=2247
- **Sticky soot and acrid puffs from the air filter housing** on a Żuk A15B S-21 Weber: the crankcase breather (odma) feeds gases into the filter housing. Check the breather for blockage.
  - Hose routing: the thin hose from the carburettor side nipple goes to the distributor vacuum unit. The thicker hose goes from the manifold valve to the filter housing, and on to the breather.
  - Source: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4713 (photo: `images/b-forum-zuk-s21-weber-hose-routing.jpg`)

---

## Polish originals for the key tips (short quotes)

| Tip (English) | Polish original | Link |
|---|---|---|
| The solenoid closes the idle jet when unpowered | "Jak nie ma napięcia sprężyna dociska stożek od wewnątrz dyszy" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4635 |
| The solenoid tip *is* the idle jet; don't break it | "To była dokładnie dysza biegu jałowego" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4635 |
| Żuk idle jet size | "żuk ma tam dyszę 45" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4635 |
| Solenoid = shut-off valve fed from the ignition switch | "zawór jest do gaszenia, odcina paliwo, sterowany stacyjką" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4279 |
| Second deep clean freed blocked channels | "z kanałów wyleciało jeszcze mnóstwo syfu" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4635&start=15 |
| Jets fitted the wrong way round after cleaning | "miałem wkręcone odwrotnie dysze" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=30 |
| Primary and secondary main jets swapped | "zamienione dysze I i II przelotu" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4814 |
| Fuel level about 6.5 mm | "poziom paliwa ustaw na ok 6,5mm" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4814 |
| Runs with the mixture screw shut = leak (float or needle) | "na bank dziura w pływaku/nieszczelny zawór" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4814 |
| Mixture screw 0.5–1.25 turns out | "odkręconym o 0,5 do 1 i 1/4 obrotu" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4814 |
| Solenoid O-ring and crushed jet enrich the mixture | "paliwo dostaje się bokiem i mieszanka za bogata" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4814 |
| Needle stuck open → fuel under the manifold | "Zaworek iglicowy był zacięty w pozycji otwartej" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4814 |
| Leaking needle → fuel level too high | "jak jest nieszczelny to będzie za wysoki poziom paliwa" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3998 |
| Emulsion tubes: F27 is the thicker one | "rurki sa opisane. f27 jest grubsza" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3998 |
| Missing accelerator-pump nozzle | "dysza pompki przyspieszenia, fi80 z kulką" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=15&t=5488 |
| Ball under the pump tube; dripping means it is missing | "kulka jest pod rurka od pompki przśpieszającej" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3139 |
| Leaking needles are common; fit a damped one | "załozyć iglicę z amortyzatorkiem sprężynowym" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3139 |
| Sticking fuel pump | "Pompa paliwa sie zawieszala" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=5136 |
| Cracked carburettor (LPG S-21s) | "Jest możliwość, że gaźnik jest pęknięty" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=5136 |
| Lean mixture → backfire into the carburettor | "za uboga mieszanke ... STRZALY W GAZNIK" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777 |
| Check firing order first | "Kolejność zapłonu 1-2-4-3, sprawdź to najpierw" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=2247 |
| 34S2B1 venturis | "34s2b1 tam obie maja po 25mm" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4279 |

## Short section: jet and float values seen in my sources

These come from forum posts and need checking against the other agent's spec tables.
- **Idle jet:** 45 for the Żuk. One owner had a 50, which is too rich. Strucelsw, in https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4635 and t=4814.
- **Idle jet / solenoid thread:** M8×1. The screw-in jet holder is 22 mm overall and the jet part 14 mm. It interchanges with the Fiat 126p solenoid, but only the jet differs. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4635
- **28/35 S2A1 (Nysa, Strucelsw):**
  - Main jets: 110 (1st barrel) and 145 (2nd). "125 is the S2B1 value" for the secondary.
  - Air correctors: 250 / 225.
  - Emulsion tubes: F27 / F35.
  - Source: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3998
- **Ranges by version (Strucelsw):**
  - Main jets: 1st barrel 110/120/125, 2nd barrel 135/145/150.
  - Air correctors: 1st barrel 250/220/210, 2nd barrel 225/220/210/200.
  - Source: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4814
- **Float / fuel level:** about 6.5 mm. One owner measured 8.5 mm and corrected it to 6.5 mm, with 13 mm max float travel. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4814 and t=3998
- **Venturis (Strucelsw):** the 34S2B1 has 25 mm in both barrels, and the Żuk 28/35 has 21/26 mm. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4279
- **Idle mixture screw:** usually 0.5–1.25 turns out on a correctly working Żuk carburettor (Strucelsw). https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4814
