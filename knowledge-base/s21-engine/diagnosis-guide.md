# S-21: No-Start / Rough-Running Diagnosis Order

This order is built from owners' tips; the sources are linked at each step. Work through it in sequence and don't skip ahead to the carb. Several owners swapped carbs or whole engines over what was really an ignition fault. For example, one forum member advised against an engine swap "over a no-spark problem" (https://zlombol.pl/community/technikalia-2/zuk-silnik-s-21-nie-pali-na-jeden-gar-2/).

## 0. Basics (5 min)

1. **Battery voltage at the terminals**: at least 12 V. Check the **engine earth strap** for corrosion. A battery can "look fine" but sag under cranking. [FORUM] https://zlombol.pl/community/technikalia-2/zuk-s21-nie-odpala-2/
2. **Cranking speed**: if slow, sort out the battery, earth and starter first.
3. **Fuel in the tank, tank vent clear.**

## 1. Spark (`iskra`)

1. Pull a plug, leave the HT lead on, earth the plug body, and crank. **Better test:** hold the HT lead (or a screwdriver in the plug cap) a few mm from earth. A healthy spark jumps several mm in air. A spark at a plug in open air alone is not conclusive. [FORUM] Arendi, Gniotsa Nie Łamiotsa, https://zlombol.pl/community/technikalia-2/zuk-silnik-s-21-nie-pali-na-jeden-gar-2/
2. **No spark or weak spark**:
   - Points (`przerywacz`): clean, check that they open, gap **0.4 ± 0.05 mm**. Oil vapour on the points is a classic Żuk fault: wash the distributor in extraction benzine. [FORUM] zlombol t "nie odpala"; [DOC] https://polskiedostawczaki.pl/podstawowe-regulacje-silnikow-s-21-oraz-m-20/
   - **Condenser** (`kondensator`): a known weak point, so replace it on suspicion. [FORUM] marek, https://retrotraktor.pl/forum/viewtopic.php?t=6764
   - **Feed to the coil**: as a test, feed coil + directly from the battery. This bypasses the ignition switch circuit. Inspect the points-to-coil wire. [FORUM] moderator, zlombol "nie odpala"
   - Cap and rotor (`kopułka`, `palec`) for cracks or tracking. Check the HT leads.
   - Coil earth.
3. **Spark present but won't fire, and plugs wet**: plugs are flooded or faulty. Try known-good plugs (cheap new plugs caused one no-start). Dry fouled plugs. [FORUM] zlombol "nie odpala"

## 2. Ignition timing (`zapłon`)

1. Check that the distributor is not 180° out. Set cyl 1 at TDC on compression: flywheel ball or hole lined up with the pointer in the clutch-housing window (`wziernik`), and the rotor pointing at the cyl-1 lead. [DOC] polskiedostawczaki regulations; [FORUM] Marian, https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3243
2. Check the lead order: **1-2-4-3** in the direction of rotor rotation.
3. If the oil pump or distributor has been out, the drive may be a tooth off (see common-problems §2). [blog] https://zukiemprzezswiat.pl/remont-silnika-2/
4. Static timing is 7° BTDC per the club page's "factory" note (5° in another source; the manual is authoritative). Fine-tune with a strobe or by road test. Backfire through the carb means too advanced. Backfire or popping in the exhaust and sluggish response means too retarded. [DOC] polskiedostawczaki regulations
5. Worn textolite timing gear and distributor shaft play make timing drift. [FORUM] retrotraktor t=6764; zlombol "jeden gar"

## 3. Fuel (`paliwo`)

1. Disconnect the pump outlet and crank (or use the hand primer): you should see good spurts. Catch the fuel and keep it away from the coil and distributor.
2. No fuel: check the tank vent and filters. Then the pump: **valves** as well as the diaphragm. After running dry, priming takes a long time; turn the engine so the lever is at the bottom of its stroke. [FORUM] Marian, KrzysiekH, https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=195 ; [club] https://polskiedostawczaki.pl/regeneracja-pompy-paliwa/
3. Fuel reaches the carb but the engine still won't start: check the float level and jets. That is covered in the Weber knowledge base. Owners call the carb simply "Weber" or "gaźnik", so search those terms when you look for related posts.
4. Flooding: return channel in the pump blocked (pressure too high), float or needle valve (`zaworek iglicowy`).

## 4. Compression and valves (`kompresja`, `zawory`)

1. Compression test, warm, throttle open, all plugs out. No factory figure is online; one healthy rebuilt engine showed "over 11" (bar) on every cylinder. Look for **evenness between cylinders** above all. [FORUM] zlombol "jeden gar"
2. Low on one cylinder: do a wet test (oil in the bore). Rising pressure points to rings; unchanged points to a valve or the head gasket.
3. Low on two adjacent cylinders: head gasket between them (S-21 owners link this to the corroded head water tube). [FORUM] https://forum.polskiedostawczaki.pl/viewtopic.php?p=48279
4. **Valve clearances**: too tight burns valves and causes loss of compression when hot. Set cold to 0.20 intake / 0.25 to 0.30 exhaust (owners use 0.30). [DOC] polskiedostawczaki regulations
5. Compression good but cylinder dead: remove the rocker cover and check that every valve actually opens. Look for a bent pushrod, broken rocker or worn cam lobe. [FORUM] Załoga Tarpaniątka, Kantmaszyna, zlombol "jeden gar"

## 5. Rough idle and hunting idle (`wolne obroty falują`)

In this order:
1. Ignition: plugs, points gap, condenser, timing, distributor play, vacuum advance diaphragm (the vacuum hose from carb to distributor). Owners disagree on whether the vacuum advance works on load or on speed, so check it holds vacuum. [FORUM] https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=195
2. Valve clearances.
3. Air leaks: intake manifold to head, carb base (lap the carb flange flat; one owner did), brake servo or PCV hose. [FORUM] https://www.drive2.ru/l/573142427284540104/
4. Idle mixture procedure, done hot at about 80 °C (see specs file). [DOC] polskiedostawczaki regulations
5. Engine earth strap: a bad earth can cause erratic running when hot (seen on other makes). [general] https://www.mazdaspeed.pl/forum/viewtopic.php?p=2436518

## 6. Running hot

See common-problems §1. Check timing first; it is the cheap check. Then thermostat, radiator cap, radiator flow, and finally the head's internal water tube. [FORUM] retrotraktor t=6764; t=48279

## Quick symptom map

| Symptom | First look at |
|---|---|
| Cranks, no fire at all | Spark (points, condenser, coil feed), then distributor 180° out |
| Fires, won't run | Fuel pump valves, float, flooded plugs |
| Runs on 3 cylinders | HT lead or plug swap test, then valve opening, cam lobe, compression |
| Popping in exhaust, sluggish, hot | Retarded timing or worn timing gear |
| Backfire into carb | Advanced timing, lean mixture, tight intake valve |
| Low oil pressure light hot | Relief valve, pump wear, oil grade |
| Blue smoke cold start | Valve stem seals |
| Blue smoke under load | Rings or bores (check air filter sealing) |
