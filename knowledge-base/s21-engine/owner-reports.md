# S-21: Owner Reports (symptom → cause found → fix)

These are real owner cases collected in October 2026. They add to `common-problems.md` and `diagnosis-guide.md` and do not repeat the threads listed there.

**How to read the tags**

- **CONFIRMED**: the owner reported the result after the fix, or found the cause by inspection and said so.
- **SUGGESTED**: advice only, or the owner never reported back.
- **Flag**: the advice disagrees with factory data (see `specs-and-service-data.md`), or it is dubious.
- Quotes are short originals, Polish unless marked. Names are forum usernames.

**Where the cases come from.** Most are from forum.polskiedostawczaki.pl, engine subforum (f=6). These are new threads, not the ones already cited in this knowledge base. The others are from zlombol.pl, retrotraktor.pl and drive2.ru.

**Sources that could not be used**
- elektroda.pl timed out on direct fetch.
- web.archive.org returned HTTP 429 (rate limit).
- The web search tool returned almost no Żuk, Nysa or Tarpan-specific pages from autokacik, wykop or YouTube.

Offline text copies are in `source-archive/s21-owner-reports/` (outside the repo). The URL list is in `sources-owner-reports.md`.

Short forms: PD = forum.polskiedostawczaki.pl; `t=NNNN` = `https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=NNNN`.

---

## 1. Won't start / starts then dies

**OR-01. No start after a frosty night; bent pushrods twice.** Probably a Żuk, S-21 with LPG (user corno27).
- **Symptom:**
  - Ran normally, then would not start the morning after a frost.
  - 3 intake pushrods and 1 exhaust pushrod were bent, and the valves were stuck in their guides.
  - It happened again the morning after the head was rebuilt.
  - Ignition and carb were checked first and were fine.
- **Cause found:** Contaminated fuel. The tank held 3–4 mm of sludge like curdled paint, and the fuel was brown and smelled of solvent. It "glued" the intake valves.
- **Fix:**
  - Freed the valves in place with kerosene and penetrating oil.
  - Cleaned the tank (pressure washer and acetone), the fuel-pump bowl, the filter and the carb passages.
  - Fresh fuel.
  - Result: started first time and passed inspection.
- **Status:** CONFIRMED.
- **Flags:**
  - A helper advised adding two-stroke oil to the petrol (1:75 to 1:100). That is folk practice.
  - Claims that an additive "hardens the seats" are unsupported.
- **Quote:** "Wniosek jest taki że można zabić głowicę złym paliwem"
- **Source:** t=3613 (photo: `images/owner-fuel-tank-sludge-polskiedostawczaki.jpg`)

**OR-02. Starts and runs nicely on petrol, then dies after about 200 m.**
- **Marian's own Żuk:** the fuel pump was "hanging". Its lever was not following the cam properly, although the pump looked fine when stripped. Another pump fixed it. **CONFIRMED.**
- **lbs5's Nysa:** it had stood about 8 years and used to run on LPG. The carb had been cleaned and the pump had new diaphragms; the carb was blamed first. Unresolved: lbs5 doubts the pump because its bowl is full after the stall. Antek123 suggests a cracked carb body, which he says is common on S-21s run on LPG. **SUGGESTED.**
- **Quotes:** "Zapala, chodzi bardzo ładnie na benzynie, ale po chwili gaśnie." and "Pompa paliwa sie zawieszala/dzwigienka od wałka nie pedziła tak jak powinna"
- **Source:** t=5136

**OR-03. Won't start after weeks parked on a slope.** Żuk (Drewniany).
- **Symptom:** He drained the battery cranking, hand-pumped fuel and cleaned the plugs, with no result.
- **Cause:** Too little fuel. The tank pickup could not reach what was left on the slope.
- **Fix:** Added 5 L of fuel and it started.
- **Status:** CONFIRMED.
- **Quote:** "Wlanie 5L paliwa pomogło jak ręką odjął"
- **Source:** t=489

**OR-04. Cranks, won't fire; the carb was suspected first.** Żuk 11B, petrol and LPG, 105,000 km, Jikov carb (ekmir).
- **Symptom:**
  - Won't start after standing overnight, but restarts fine when warm.
  - New NGK B6HS plugs and hand-priming did not help.
  - Petrol poured into the carb throat made it start briefly.
- **Cause:** The fuel pump was not delivering to the carb (nysanek). He also found that the upper starter bolt had sheared, which caused sparking near the starter.
- **Status:** SUGGESTED. The throat-pour test supports the diagnosis, but the repair was settled off-forum.
- **Flag:**
  - The timing given in the thread, "8 stopni przed ZZ", is slightly more advanced than the factory figure of about 7° (another source says 5°).
  - The owner cleaned the points with WD-40 or contact spray. Keep the points free of oil and grease.
- **Quote:** "pompa paliwa niedaje paliwa do gaznika , temat zakonczony"
- **Source:** t=489

**OR-05. A bang with a flash while cranking, then no start on petrol or LPG.** Żuk with LPG (Ryga).
- **Symptom:** After the bang it would not start on either fuel.
- **Fix:** He hand-primed the fuel pump to refill the carb and kept cranking, and it started.
- **Status:** CONFIRMED that it restarted. The cause of the bang was not found; ignition timing or fouled plugs were suggested.
- **Quote:** "musiałem ręcznie napompować paliwo do gaźnika"
- **Source:** t=3909

**OR-06. Hard start and clattering after 7 months laid up.** Żuk (misieks).
- **Symptom:** Hard to start, then ran heavily and clattered like an old diesel. The throttle was slow to respond.
- **Cause:** Rusty throttle linkage and cables around the carb.
- **Fix:** Penetrating oil on the linkage. It freed up gradually, and the engine started easily afterwards.
- **Status:** CONFIRMED.
- **Quote:** "pracował jakby byl starym dieslem, tak klekotal"
- **Source:** t=482

**OR-07. Nysa stalled at a paint shop after 4 years stored and would not restart.** (Tomasz)
- **Advice from Marian:**
  - Check the spark, the fuel in the tank and the fuel pump.
  - Look for dust in the carb if the air filter was off during bodywork.
  - After long storage, change the oil and clean the carb and pump.
- **Status:** SUGGESTED.
- **Quote:** "noga zeszła mu ze sprzęgła i silnik zgasł"
- **Source:** t=489

## 2. Cranks, no fire

**OR-08. Won't start after the breaker plate was replaced.** GAZ-69 with S-21 (zaqoff).
- **Symptom:**
  - With the distributor cap off, the starter spins freely.
  - With the cap on, the engine turns a little and seems to kick back.
- **Suspected cause:** The points gap had not been set on the new plate (nysanek).
- **Fix advised:** Turn the engine until the rubbing block sits on a cam lobe and set the gap to 0.4 mm. Check the HT lead order 1-2-4-3. The owner confirmed his cap reads "1 2 coil 4 3" from the left.
- **Status:** SUGGESTED (no outcome reported).
- **Quote:** "Po założeniu silnik nie chce odpalić w ogóle."
- **Source:** t=1296

See also OR-04 and OR-05.

## 3. Misfire, runs on 3, rough idle

**OR-09. Dull pops into the exhaust at idle; weak when cold, strong when warm.** GAZ-69 with a rebuilt S-21 (zaqoff). This is the same swap type as the owner's.
- **Symptom:** Timing and mixture had been adjusted, and the coil, cap, plugs, leads and fuel pump had all been checked or replaced. None of it helped.
- **Suspected causes:**
  - The ignition harness, or a badly worn distributor (Marian).
  - Loose intake/exhaust manifold nuts letting in false air (nysanek).
- **Fix tried:** Manifolds tightened, then new plugs, leads and breaker plate. Not cured; the thread continues as OR-08.
- **Status:** SUGGESTED.
- **Flag:** nysanek advises "all valves 0.20". The factory exhaust clearance is 0.25–0.30 mm, so that setting is too tight on the exhaust side.
- **Quote:** "słychać co jakiś czas jakby nie przepalał na jakimś cylindrze"
- **Source:** t=1296

**OR-10. Shook badly, running on about 2 cylinders, after new HT leads were fitted.** A friend's Żuk, reported by Marian.
- **Cause:** The new leads were faulty.
- **Fix:** Fitted known-good old leads, and it ran fine.
- **Status:** CONFIRMED (second-hand).
- **Quote:** "okazało sie, że kable byly do bani"
- **Source:** t=1296

**OR-11. Jerks and pops into the exhaust at idle, on both petrol and LPG.** Żuk S-21 with LPG (Kuba11).
- **Already done:**
  - Valves checked repeatedly.
  - New Bosch plugs, leads, cap, rotor and coil.
  - Points cleaned and gapped at 0.4 mm.
- **Cause suspected:** The distributor is seized in its housing, so the timing cannot be set (Strucelsw, Marian). Free it with heat and penetrant, or replace it. Strucelsw also suggests Denso WF20TT plugs.
- **Status:** SUGGESTED.
- **Flag:** The owner tried to adjust timing by rotating the distributor **cap**. That does not change the spark timing; it only misaligns the rotor and the cap terminals.
- **Quote:** "co chwile delikatnie nim szarpie i pierdzi w tłumik"
- **Source:** t=4213

**OR-12. Runs on only 2–3 cylinders after a contactless ignition kit was fitted, and still does with the old distributor.** Nysa S-21 (Daniel22, for a friend).
- **Symptom:** There is spark and there is compression. Ignition was blamed first.
- **Strucelsw's suspects:**
  - A damaged gasket under one inlet-manifold branch (a vacuum leak).
  - Bad NGK plugs.
  - Burned valve seats, since the valves had been sticking earlier.
- **Status:** SUGGESTED.
- **Quote:** "Iskra jest, kompresja jest, ale pali na 2-3 gary."
- **Source:** t=5386

**OR-13. Sudden rough idle; fine on choke; sometimes stalls in neutral.** Żuk 2.1 (Sebafso).
- **Already done:** New plugs, leads, filters and oil, and the cap cleaned. No change.
- **Cause suspected:** The owner had removed the manifold and refitted it without a new gasket, so false air is likely. He had suspected the carb and distributor first.
- **Other advice:**
  - Strucelsw adds the brake-servo hose as another false-air source.
  - nysanek: don't over-tighten the manifold nuts, because the studs strip out of the head.
- **Status:** SUGGESTED.
- **Quote:** "Zdejmowałem kolektor i nie wymieniłem uszczelki, podejrzewam że tam jest nieszczelność"
- **Source:** t=3118

**OR-14. No power, heavy smoke and bad misfiring.** Tarpan with S-21 (Tarpanowiec).
- **Already done:** New HT leads, cleaned cap contacts; the carb cut-off solenoid has power.
- **Non-carb suspects (Strucelsw):**
  - The manifold mixture pre-heater stuck in its "warm" position.
  - The air-cleaner flap left on "warm".
  - A dirty air filter.
- **Others:** check plug colour, or replace the plugs.
- **Status:** SUGGESTED.
- **Quote:** "nie ma mocy i bardzo kopci, silnik strasznie przerywa"
- **Source:** t=3707

## 4. No power

**OR-15. Won't go over 60 km/h although it revs freely.** Żuk A15, 1989, about 25,000 km (adamko11).
- **Already done:**
  - Valves set by the manual; jets cleaned.
  - New fuel-pump diaphragm and valves; new plugs, leads and rotor.
  - Compression measured at about 9.5 warm.
- **Suspects raised:**
  - The throttle not opening fully (Marian).
  - A blocked or rusted silencer, or a wrong speedometer (Strucelsw).
  - The second carb throat not opening (Klamot).
- **Later findings:** The cylinder-2 plug was oily and the oil smelled of petrol. Strucelsw says worn valve guides, because the engine has only stem caps, not real seals.
- **Fix:** Timing set to 8° with a strobe. Top speed rose 8–10 km/h but it was weaker uphill. Marian says 8° was meant for 86-octane fuel and recommends setting it by ear.
- **Status:** Partly CONFIRMED (the timing gain); the root cause was not found.
- **Flag:**
  - 8° is above the ~7° (or 5°) factory figure.
  - The compression readings were written as "kPa", but they are really kg/cm².
- **Quote:** "Pojazd nie jest w stanie osiągnąć prędkości większej niż 60 km/h."
- **Source:** t=3347

**OR-16. After filling up at one station, jerking and no power.** nysanek's Nysa S-21.
- **Symptom:** It felt as if the distributor had slipped by more than ten degrees.
- **Cause attributed:** Bad fuel.
- **Status:** SUGGESTED (anecdote).
- **Quote:** "myslalem ze aparat zaplonowy sie przestawil o kilkanascie stopni"
- **Source:** t=1767

**OR-17. Secondary throttle won't open.** zolwik.
- **Cause:** A small valve in the S-21 inlet manifold, worked by the carb linkage, was seized. Strucelsw says it is part of the crankcase-gas system and must move freely.
- **Fix advised:** Heat it with a torch and pull it out with pliers.
- **Status:** SUGGESTED.
- **Quote:** "był zawarty i blokował otwieranie drugiej przepustnicy"
- **Source:** t=4162

**OR-18. Won't rev for a few minutes after the choke is pushed in.** Żuk 1986, Weber carb (jacek44).
- **Symptom:** Full throttle gives only about +100 rpm, then it suddenly clears after a few minutes.
- **Views:** Strucelsw: a cold engine running lean. Marian: it shouldn't be that bad; suspects a blocked carb.
- **Status:** SUGGESTED.
- **Quote:** "auto po odpaleniu i odpuszczeniu ssania nie chce wejść na obroty"
- **Source:** t=4713

See also OR-35 (65 km/h top speed: the head gasket was suspected).

## 5. Overheating and cooling

**OR-19. Overheating; looking into the coolant tube inside the head.** GAZ-69 with S-21 (Poncki).
- **Findings:**
  - Strucelsw: the tube feeds coolant to the exhaust ports. Without it, the engine "boils immediately under load". It can clog with sludge or rot through.
  - Access is through the heater valve and the plug at the rear of the head. The tube is about 12 mm in diameter.
  - The owner pulled **pieces of silicone** and sludge out of the tube.
- **Status:** SUGGESTED (partial find). This adds detail to the tube fault already in common-problems §1.
- **Flag:** Home descalers are of doubtful benefit:
  - Marian used 7 × 20 g of citric acid and saw no effect.
  - He says baking soda should not be used with an aluminium head.
- **Quote:** "wyciągnąłem z niej kawałki silikonu"
- **Source:** t=4311

**OR-20. Rebuild after the engine boiled: a hidden coolant passage plugged with a stone.** Żuk S-21 (proximo).
- **Finding:** A block passage at the head-gasket hole with the copper ring was plugged. It is the small-circuit coolant feed to the head (confirmed by Tomek on a bare block).
- **Fix:** Cleared it.
- **Status:** CONFIRMED that it was cleared; how the engine ran afterwards was not reported.
- **Quote:** "odkryłem kanał który był wcześniej niewidoczny, zatkany kamyczkiem"
- **Source:** t=2658 (photo: `images/owner-block-hidden-coolant-passage-polskiedostawczaki.jpg`)

**OR-21. Thermostat won't open after a coolant refill.** zukostrazak.
- **Cause:** An air pocket at the thermostat.
- **Fix advised:**
  - Drive a few km at higher revs with the cap off, squeeze the top hose, then top up.
  - Marian's method: fill to about 2 cm below the neck, start the engine, then top up. The system has no bleed screw.
- **Status:** SUGGESTED (owner's experience).
- **Quote:** "zrobiła się bańka powietrza przy termostacie"
- **Source:** t=3613

**OR-22. Lower radiator hose is sucked flat under heavy throttle.** Żuk 1988, 23,000 km, ex-fire-brigade (KarolFrd).
- **Symptom:** The thermostat had been removed. The coolant was neat concentrate, which he later diluted.
- **Suspects:**
  - A clogged radiator (sukiennik68).
  - A radiator cap with too stiff a spring, or a scaled cap whose vacuum valve is stuck (Dziwny Mag).
  - A soft hose.
- **Status:** SUGGESTED (unresolved).
- **Flag:** Running with no thermostat and on undiluted concentrate goes against factory practice. The thermostat should be about 70–80 °C.
- **Quote:** "przewód który łączy chłodnice z silnikiem ten dolny się zasysa"
- **Source:** t=5068

**OR-23. Normally about 80 °C, but jumps above 90 °C within minutes when idling after a run (in winter).** Żuk (Jey).
- **Suspects (nysanek):** Low coolant, a scaled thermostat that only half-opens, or a scaled radiator.
- **Fix:** The workshop replaced hoses and topped up the coolant. No follow-up reading was posted.
- **Status:** SUGGESTED.
- **Quote:** "to od razu skoczyło powyżej 90"
- **Source:** t=885

**OR-24. Off the road for over a week because of one hose.** Żuk owner (retrotraktor).
- **Cause:** The rubber hose from the thermostat housing to the radiator failed. A spare could not be found.
- **Lesson:** Carry spare cooling hoses.
- **Status:** CONFIRMED (experience).
- **Quote:** "unieruchomił na ponad tydzień gumowy wąż łączący obudowę termostatu z chłodnicą"
- **Source:** https://retrotraktor.pl/forum/viewtopic.php?t=4979

See also OR-37 (overheating that turned out to be the head gasket) and OR-57 (fan flew off).

## 6. Knocking and pinging (including fuel)

**OR-25. "Clatters like a diesel", hot and cold.** S-21 (Miszczu). Oil pressure about 5, no oil use.
- **Suspects:**
  - Marian: timing too far advanced. Loosen the distributor and retard slowly while running, until the knock stops but the throttle still responds sharply. Or use a strobe.
  - nysanek: low-octane fuel or a split vacuum-advance diaphragm. Mechanical candidates:
    - excess valve clearance;
    - worn pushrod ball ends or a bent pushrod;
    - worn cam lobes;
    - a weak valve spring;
    - sticking rockers;
    - big-end bearings.
- **Status:** SUGGESTED.
- **Quote:** "Dlaczego S21 chodzi na benzynie jak diesel, tak klekocze."
- **Source:** t=1802

**OR-26. Metallic, vibrating noise from the valve-cover area as revs rise.** Both a Nysa and a Żuk (Tomcur522).
- **Suspects:** Valve clearances (Marian), or detonation from poor fuel (phinek).
- **Status:** SUGGESTED.
- **Quote:** "dzwięk dochodzi z okolic pokrywy zaworów"
- **Source:** t=3556

**OR-27. On LPG the knocks went quiet.** Żuk S-21 with a simple LPG mixer (retrotraktor).
- **Experience:** LPG burns "less explosively", and the knocks and clatter stopped. Consumption was 12–15 L/100 km.
- **Status:** SUGGESTED (experience).
- **Quote:** "Milkły wszystkie stuki i klekotania"
- **Source:** https://retrotraktor.pl/forum/viewtopic.php?t=5113

Unleaded fuel: valve-seat hardening dates and additives are under §14 LPG (OR-65).

## 7. Oil pressure

**OR-28. Erratic oil gauge: off the scale, then into the red at idle.** Żuk S-21, ex-fire-brigade, 50,000 km (zukostrazak).
- **Already done:** He shimmed the relief spring and fitted a new pump. Neither fixed it.
- **Cause found:** A faulty oil-pressure **sender**. After replacing it, the readings were stable.
- **Status:** CONFIRMED for the erratic gauge.
- **Still open:** A steady reading of about 2.1 at all revs remained unexplained (bearings were suggested).
- **Quote:** "po wymianie czujnika ciśnienia skończyło się wariowanie wskazań"
- **Source:** t=3463

**OR-29. About 3 for a few seconds after start, then below 1; noisy rocker gear.** Żuk S-21 (radek83).
- **Advice:**
  - CZESIO1958: an M5 spring washer under the relief spring.
  - Strucelsw: a worn relief plunger or seat; relief springs are often found 2–3 mm short; 2.5–3.5 bar hot is good.
- **Fix:**
  - Two oil changes, one with a flushing product and one with 0.5 L of kerosene in the new oil.
  - Then Orlen Classic 20W-50. Pressure is now OK.
- **Status:** CONFIRMED.
- **Flag:**
  - Kerosene in engine oil is a risky practice.
  - "4–5 bar washes out the bearings" is unproven.
- **Quote:** "ciśnienie jest na poziomie 3 po czym spada poniżej 1"
- **Sources:** t=5308 and t=5319

**OR-30. About 0.1 at hot idle, at the edge of the red; noisy rocker gear.** Azajcew.
- **Fix (Strucelsw's advice):**
  - Lap the pump cover to under 0.05 mm gear clearance.
  - Clean the relief valve, which sticks open more often than shut.
  - Check the pickup for bits of silicone or gasket.
  - Then refit.
- **Result:** Pressure is OK. He suspects the worn rubber-metal bush that joins the rocker shafts for the remaining noise.
- **Status:** CONFIRMED.
- **Quote:** "podejrzewam tulejkę metalowo-gumową łączącą wałki popychaczy zaworów"
- **Source:** t=3101

**OR-31. Reads about 5 at idle and off the scale at high revs.** Żuk S-21 (arti 08).
- **Already done:** 2 other senders, another gauge, relief valve cleaned. No change.
- **Strucelsw:** that much pressure would blow out the filter gasket, so the reading is probably false. Measure with a mechanical gauge.
- **Status:** SUGGESTED (unresolved).
- **Flags:**
  - Marian quotes the book as "0,1-0,54 MPa" (1 to 5.4 bar).
  - Strucelsw's "5 and a bit more at high revs is normal" is above the ~3.5 bar hot figure in this knowledge base.
- **Quote:** "Ciśnienie jest na wolnych obrotach 5 ,a na wysokich wychodzi za skalę"
- **Source:** t=3101

**OR-32. About 0.2 MPa that barely rises with revs.** GAZ-69 with S-21 (Dymek).
- **Advice:**
  - Check with a mechanical gauge in the plug on top of the filter base (Marian).
  - Crack the rocker oil-feed union and see if oil comes out under pressure (nysanek).
- **Status:** SUGGESTED.
- **Flag:** He plugged a leaking gallery hole with a con-rod stud on PTFE tape. That is an improvised repair.
- **Quote:** "Zegar mi pokazuje ok. 0.2MPa."
- **Source:** t=3101

**OR-33. Almost 5 at hot idle.** Miszczu.
- **Suspects:**
  - The relief valve (phinek: just back it off).
  - A faulty gauge or the wrong oil (nysanek).
  - A blockage: check that oil reaches the rockers (Leśnowóz).
- **Status:** SUGGESTED.
- **Flag:**
  - Adjusting the relief valve before checking with a mechanical gauge is dubious.
  - The owner wrote "MPa" but means bar.
- **Quote:** "na wolnych obrotach jest prawie 5 MPa, jakieś 4,8"
- **Source:** t=1689

**OR-34. Ran low on oil, then clattered and seized.** Żuk (sebolekosa).
- **Symptom:** Uphill it clattered and ground, with smoke from under the oil filler cap. After oil was added it knocked harder, then locked up.
- **Cause:** Bearing failure from oil starvation.
- **Status:** CONFIRMED (outcome). Not worth repairing.
- **Quote:** "zaczął drastycznie klekotać(mielić) w silniku"
- **Source:** t=1907

Gauge checks are also covered in OR-49 (both gauges suspect). Fault seen in OR-67: when the oil pump fails, the ignition timing goes with it.

## 8. Head gasket and water in oil

**OR-35. Top speed 65 km/h, 1 L of oil per 1000 km, coolant loss, murky coolant, bubbling after shutdown.** Ex-police S-21 (Robo).
- **Measured:** Compression 10 atm. Marian says the book value is 1–1.1 MPa, so that is OK.
- **Diagnosis:** Head gasket (Marian, nysanek). Bubbling after the engine is switched off was the giveaway.
- **Fix:** Gasket replaced; the valves were sooty. Power after the fix was not reported.
- **Status:** SUGGESTED.
- **Flag:** nysanek says the book gives "exhaust 0.35, intake 0.25" and advises 0.20 on all valves. Both conflict with the factory 0.20–0.22 mm intake and 0.25–0.30 mm exhaust.
- **Quote:** "No chwilkę po zgaszeniu motoru słychać bulgotanie."
- **Source:** t=1432

**OR-36. Gasket failed twice in the same place, between cylinders 2 and 3, with water in the oil.** Żuk rebuilt in 2002 (Juzef).
- **Likely cause:**
  - Uneven torque: no torque wrench was used, and the front bolts came off easier.
  - The gasket had been coated with graphite grease.
- **Advice:**
  - Fit the gasket dry and degrease both faces.
  - Tighten from the centre outwards.
  - Re-torque after about 100 km.
- **Status:** SUGGESTED.
- **Flags:**
  - Another member relays advice to soak the gasket in oil. That contradicts dry fitting.
  - The torque used was 120–130 Nm on M14 bolts. The only figure in this knowledge base is **66–71 Nm, and that is for the M-20 on studs**. No factory S-21 figure has been found, so **check your manual before using 120–130 Nm**.
- **Quote:** "to już drugi raz w tym samym miejscu, między 2 a 3. cylindrem"
- **Source:** t=2352

**OR-37. Overheating, starting only on the 3rd or 4th try, rough idle, "bubbling" from the radiator.** Marian's Nysa.
- **Already done:** Spark, valves and belt checked. A relative checked the carb and found it excellent. Marian also suspected the thermostat and the fuel pump.
- **Found:** Oily spots floating in the coolant.
- **Diagnosis:** Head gasket (nysanek, "101%").
  - Test: open the cap carefully when hot and watch for bubbles.
  - Have the head skimmed.
- **Status:** SUGGESTED (no outcome in this thread).
- **Quote:** "w chodnicy plywaja takie plamki odrozniajace sie od reszty, wyglada na olej"
- **Source:** t=2352

**OR-38. Drops seeping from the gasket minutes after filling the coolant.** nysanek's engine.
- **Fix:** Re-torqued from 120 Nm to 130 Nm, and it holds.
- **Status:** CONFIRMED.
- **Flag:** Same torque warning as OR-36.
- **Quote:** "dowalilem na 130 i trzyma"
- **Source:** t=2352

**OR-39. Newly bought, won't run: milky oil and mayonnaise on the cap. The cooling system held plain water.** lbs5.
- **Diagnosis:** Head gasket expected.
- **Advice:** Do not flush with diesel fuel ("Broń Bosch używać ON jako oleju smarnego!").
- **Status:** SUGGESTED.
- **Quote:** "zauważyłem mleczny kolor oleju"
- **Source:** t=2352 (photos: `images/owner-oil-cap-mayonnaise-polskiedostawczaki.jpg`, `images/owner-oil-emulsion-dipstick-polskiedostawczaki.jpg`)

**OR-40. Looked like a head gasket, but was a core plug.** nimnul, OHV engine with rocker gear (S-21 implied).
- **Symptom:** In hot weather, coolant added ended up in the oil within about 5 km.
- **Cause found:** A **core plug in the head, under the rocker cover**, had blown out completely.
- **Fix:**
  - New 30 mm convex core plug.
  - Pressure-tested the cooling system with a compressor.
  - Three oil and filter changes to clear the emulsion.
- **Status:** CONFIRMED.
- **Quote:** "oczom mym ukazał się wywalony całkiem jeden brok"
- **Source:** t=2904

**OR-41. Gasket leaking a little exhaust into the coolant.** Nysa (zbyszek99).
- **Fix:** Gasket replaced without skimming the head. Fine for about 12,000 km since, running mostly on LPG with lead substitute.
- **Status:** CONFIRMED.
- **Counter-view:** nysanek says even new heads can be warped, so have yours checked.
- **Quote:** "lekko puszczała spaliny do układu chłodzenia"
- **Source:** t=2904

**OR-42. A cracked cylinder liner that appeared only after an LPG conversion.** A Żuk, second-hand anecdote (zlombol).
- **Symptom:** Fine on petrol. After the conversion it showed head-gasket symptoms.
- **Explanation given:** Deposits had sealed the crack; LPG burns clean and removed them.
- **Status:** SUGGESTED (anecdote).
- **Quote:** "kiedyś spotkałem sie z pękniętą tuleją w żuku"
- **Source:** https://zlombol.pl/community/technikalia-2/instalacja-gazowa-do-zuczkow-nysek-itp-2/

## 9. Oil consumption, smoke, breathing

**OR-43. Blue smoke for a few seconds on a warm restart after a 10–15 minute stop.** zukostrazak's Żuk.
- **Suspects:** Worn valve guides (Strucelsw, phinek), or the head gasket (Marian).
- **Status:** SUGGESTED.
- **Quote:** "przez kilka sekund dymi na niebiesko"
- **Source:** t=3463

**OR-44. Heavy blue smoke even when warm.** Żuk (radek83).
- **Advice:**
  - Do a compression test and a wet test.
  - Strucelsw: from the factory, only the **intake** valves have rubber caps, and the exhausts have none. Fit proper seals to all eight, for example the Ford Transit 2.4 diesel seal.
  - New seals and rings only help if the guides are good.
- **Status:** SUGGESTED.
- **Seal part numbers (t=4378):**
  - Corteco CO12012351, 9 mm stem (Mr_Spok).
  - Also suggested: Motive MOTSS265, Elring 467.880.
- **Quote:** "dymi na niebiesko, całkiem sporo"
- **Sources:** t=5319, t=4378

**OR-45. Dark, foul smoke for a few minutes after every cold start.** Ryga.
- **Cause:** Too much choke, giving an over-rich mixture.
- **Fix advised:** Reduce the choke as soon as it will idle.
- **Status:** SUGGESTED.
- **Quote:** "z rury buchają ciemne i b smrodliwe spaliny"
- **Source:** t=4057

**OR-46. Air blowing from the oil filler with the cap off.** Żuk, about 60,000 km after rebuild (Miszczu).
- **Rule of thumb (phinek):** An in-and-out pulse is normal. A steady outward blow means worn rings (blow-by).
- **Status:** SUGGESTED.
- **Quote:** "Czy to normalne, że Żuk dmucha spod korka oleju"
- **Source:** t=1517

**OR-47. Oil level rising and turning lighter; milky with bubbles in winter.** Żuk (Miszczu).
- **Suspects:**
  - Condensation from short trips (a mechanic).
  - A clogged breather (Marian).
  - **The fuel pump leaking petrol into the sump** (nysanek). A rising level points to fuel dilution.
- **Status:** SUGGESTED.
- **Flag:** "Drive without the oil filler cap" was advised. That is dubious.
- **Quote:** "po nawet krótkiej jeździe jest 1.5 stanu i jest sporo jaśniejszy"
- **Source:** t=1564

**OR-48. Mayonnaise under the oil cap that disappears on long runs.** Żuk S-21 (PARZUŚ).
- **Result:** After a 140 km run the mayonnaise was gone. It came back with city driving, so it is condensation, not the gasket.
- **Status:** CONFIRMED behaviour.
- **Still open:** His low oil pressure (about 0.2 cold) was not resolved.
- **Quote:** "wytarłem majonez, a gdy wróciłem to na korku majonezu nie było"
- **Source:** t=2352

**OR-49. Acrid fumes puff from the air-filter housing; sticky soot in the housing and carb.** Żuk 1986 (jacek44).
- **Explanation:** This is the closed crankcase ventilation returning blow-by. The breather may be clogged. Hose routing is given in the thread.
- **Gauges:** The same owner's temperature gauge always reads over 100 °C, and the oil gauge sits near the red.
  - Test the temperature sender in boiling water.
  - Fit a mechanical oil gauge at the sender port or the spare plug on the filter base.
- **Status:** SUGGESTED.
- **Quote:** "z obudowy filtra powietrza wydostają się co jakiś czas gryzące spaliny"
- **Source:** t=4713

## 10. Leaks

**OR-50. Petrol smell after the first start of spring; fuel wetting the exhaust manifold at the heat-riser spindle.** Nysa (zbyszek99).
- **Explanation (Marian):** This is a factory design. Small drain holes from the intake manifold, and through the manifold gasket, drain excess fuel after long cranking. It should evaporate within minutes of running. If it keeps dripping, the mixture is too rich.
- **Status:** SUGGESTED.
- **Quote:** "Przez nieszczelną oś bolca wydobywa sie podejrzany płyn"
- **Source:** t=1886

**OR-51. A "regenerated" water pump leaked after one day.** tomek_jaz.
- **Cause found:** Only the bearings had been replaced. The shaft was badly worn, with 5 grooves instead of 2.
- **Fix:** He rebuilt it himself with a repair kit and a bearing puller.
- **Status:** CONFIRMED.
- **Quote:** "wałek masakra zamiast 2 rowków posiadał 5 i caly zeżarty"
- **Source:** t=2973

**OR-52. Recurring coolant leak from the water pump kept the car off the road for about two years.** Warszawa 223 (Bulgarian owner, drive2).
- **Fix:** Water pump replaced.
- **Status:** CONFIRMED.
- **Quote (Russian):** "Снова появилась утечка охлаждающей жидкости из водяного насоса"
- **Source:** https://www.drive2.ru/r/other/909085/logbook/

## 11. Noises: tappets, timing gear, bearings

**OR-53. Sudden loud metallic knock after about 35 km.** GAZ-69 with S-21, an engine overhauled 25 years earlier and then stored (Dymek).
- **Symptom:**
  - Louder with revs, quieter in a higher gear.
  - Present at cold idle, silent when cranking.
- **Cause found:**
  - With the sump off, the bearings looked fine.
  - With the side tappet cover off: a **cylinder-4 pushrod had dropped off its tappet**, and both cylinder-4 tappets were scuffed and stiff in their bores.
  - Strucelsw is sure the tappets caused the knock.
- **Planned fix:** Free the tappets, new bearings and gaskets, Platinum Classic 15W-40.
- **Status:** Cause found by inspection; the outcome after the fix is not reported.
- **Other advice in the thread:**
  - Avoid Selectol oils, which wear the engine or leave sludge.
  - Marian: always drop the sump before starting a long-stored engine. On another 8-year-stored engine he found sludge, a scored bearing, a broken thrust half-ring and a clogged pickup.
- **Quotes:** "Jeden popychacz 4 cylindra spadł ze szklanki" and "Gnój, bagno, przytarta panewka, urwany półpierścień wału, zapchany smok olejowy"
- **Source:** t=3379 (photos: `images/owner-tappets-pushrods-cyl4-polskiedostawczaki.jpg`, `images/owner-main-bearing-shells-gaz69-s21-polskiedostawczaki.jpg`)

**OR-54. Knocked at idle "like a diesel".** zukostrazak's Żuk.
- **Cause:** The bakelite timing gear had stripped teeth.
- **Fix:** Gear replaced, and the knock stopped.
- **Status:** CONFIRMED.
- **Quote:** "aż do czasu jak się wygryzło bagielitowe koło rozrządu"
- **Source:** t=3556

**OR-55. Knock near the clutch at cylinder 4, also with the clutch pressed.** Warszawa with S-21 (RaDek1985).
- **Background:** It was bought "sneezing". A new distributor, valve adjustment and a Jikov-to-Weber carb swap cured that. Several things were changed at once, so the actual cause is unknown.
- **Cause found:** Engine out: large piston clearance and play at the **cylinder-4 gudgeon pin**.
- **Fix:** Swapped in an overhauled engine.
- **Status:** CONFIRMED.
- **Flag:** He set exhaust valves to 0.2 mm, below the factory 0.25–0.30 mm.
- **Quote:** "przyczyną stukania był luz na sworzniu tłoka na 4 garku"
- **Source:** t=5110

**OR-56. A clunk every time he lifts off the throttle.** Żuk with LPG (Ryga).
- **Views:**
  - The propshaft UJ or splines (phinek, Marian).
  - Engine bearings (Strucelsw).
  - The owner found slight play near the gearbox.
- **Status:** SUGGESTED (unresolved).
- **Quote:** "przy każdym zdjęciu nogi z gazu słyszę jakiś stuk"
- **Source:** t=3909

**OR-57. Fan flew off and wrecked the radiator.** A friend's Nysa (Strucelsw).
- **Cause:** The retaining pin in the water-pump fan hub had fallen out.
- **Lesson:** Always refit that pin; drill it 3.9 mm if needed.
- **Status:** CONFIRMED (anecdote).
- **Quote:** "ten kołek wypadł, smiglo pofruneło i zniszczylo chłodnicę"
- **Source:** t=2973

## 12. Vibration

**OR-58. More vibration after fitting new engine mounts.** Żuk prepared for the Złombol charity rally (maciekz).
- **Measured with a Shore durometer:**
  - original 1995 mounts: 54–55 Shore A;
  - Allegro mounts: 61–62;
  - syrenka.eu mounts: 58–60.
- **Conclusion:** The new mounts are too hard. Good original petrol-engine mounts can be squeezed between finger and thumb (Dziwny Mag).
- **Status:** SUGGESTED (measured, no final fix).
- **Quote:** "stare oryginalne poduszki (95rok) 54-55 w skali Shore'a"
- **Source:** t=1933

**OR-59. So loud and shaky at idle he can't use the phone; howling on the move.** Ex-fire-brigade Żuk, 62,000 km (adrenaline).
- **Already replaced:** Ignition parts and the mounts (hard ones).
- **Suspects:**
  - Body-panel resonance.
  - Mounts that are too hard.
  - A misfire, if the engine itself rocks.
  - Body-to-frame pads.
  - Propshaft or wheel runout.
- **Benchmark (Dziwny Mag):** a healthy S-21 is barely audible 1.5–2 m away at idle.
- **Status:** SUGGESTED.
- **Quote:** "Na wolnych jest glisno nie da sie rozmawiac przez telefon, trzesie się."
- **Source:** t=2935

## 13. Starter and charging

**OR-60. Odd noise near the water pump.** Żuk 1988 (KarolFrd).
- **Cause found:** Alternator bearings and brushes.
- **Fix:** Alternator cleaned and rebuilt. The noise is gone and charging is OK.
- **Status:** CONFIRMED.
- **Quote:** "to alternator a dokładniej łożyska oraz szczotki"
- **Source:** t=5068

Also: a sheared upper starter bolt causing sparking (OR-04). And when cranking after long storage, crank in short bursts so the starter doesn't burn out (Klamot, t=5136: "No i przerwy bo rozrusznik można usmażyć").

## 14. LPG-related

**OR-61. Runs only on LPG; dies on petrol, though the pump delivers fuel.** Żuk S-21 (Miszczu).
- **Cause:** A corroded wire to the petrol cut-off solenoid. The carb was not at fault.
- **Status:** CONFIRMED.
- **Quote:** "Naprawione, zaśniedział przewód dochodzący do elektrozaworu."
- **Source:** t=1608

**OR-62. After switching from petrol to LPG it fires on 2 cylinders; the others join after blips or a few hundred metres.** Miszczu.
- **Suspects:** Worn plugs or HT leads, because LPG needs a stronger spark (maqsz, Marian). Or gas-specific plugs and a mixture adjustment (Leśnowóz).
- **Status:** SUGGESTED.
- **Quote:** "najpierw pali na 2 cylindry, po kilku przegazówkach odzywa się następny cylinder"
- **Source:** t=1701

**OR-63. 19–22 L/100 km of LPG on the road.** Żuk 1989 S-21 (Złombol crew).
- **Fix:**
  - Leaned the reducer and mixer: 14–15 L, but no power on hills.
  - Then slightly richer: 16–17 L, with a steady 90 km/h.
- **Other advice:** Advance the ignition slightly for LPG; check for dragging brakes.
- **Status:** CONFIRMED.
- **Quote:** "pali od 19 do 22 litrów LPG na 100 km w trasie"
- **Source:** https://zlombol.pl/community/technikalia-2/zuk-lpg-s-21-problem-ze-spalaniem-pomocy-2/

**OR-64. How one owner set a simple pipe-type LPG mixer.** Żuk with Jikov carb (retrotraktor).
- **Method:** Close the gas valve while driving until power drops, then open it about half a turn.
- **Maintenance:** Another owner says LPG Żuks need more frequent attention to the cap, rotor, leads, plugs and valve clearances.
- **Status:** SUGGESTED (experience).
- **Quote:** "do momentu aż silnik tracił moc. Potem odkręcałem jakieś pół obrotu"
- **Source:** https://retrotraktor.pl/forum/viewtopic.php?t=5113

**OR-65. Valve seats and LPG or unleaded fuel.**
- **Hardened seats from the factory:** dates disagree, "from June 1989" (Strucelsw), about 1990 (Marian), or 1992–93 (nysanek).
- **On LPG:** owners use valve-seat lubricators or lead-substitute additives, and check clearances every 10,000–15,000 km.
- **Float wear:** one owner says the carb float wears through every 6–8 months on LPG.
- **Status:** SUGGESTED.
- **Flag:** "Pod gaz na zaworach lepiej dać o 5 setek większy luz", i.e. add 0.05 mm on LPG. This is owner practice, not a factory value.
- **Sources:** t=2352; https://zlombol.pl/community/technikalia-2/instalacja-gazowa-do-zuczkow-nysek-itp-2/

See also OR-42 (cracked liner exposed by LPG).

## 15. After a rebuild or part swap

**OR-66. Won't start after an oil-pump change; bangs in the exhaust.** wojtek21.
- **Cause:** Ignition timing lost. The distributor is driven through the oil pump.
- **Fix:** Re-timed.
- **Prevention:** Set cylinder 1 at TDC with the flywheel ball, mark the rotor, and photograph the pump drive slot before removal.
- **Status:** CONFIRMED.
- **Quote:** "Okej poroblem rozwiązany przestawil się zapłon"
- **Source:** t=2980

**OR-67. A failing oil pump took the timing with it, and the backfire split the silencer.** zukostrazak.
- **Status:** CONFIRMED (cause stated by the owner).
- **Quote:** "Mi się przestawił zapłon kompletnie (padła pompa oleju)"
- **Source:** t=3909

**OR-68. A new red Russian timing gear lost 4 teeth after about one minute of running.** Bartorg.
- **Suspects:** Poor material, missing thrust half-rings, gear runout.
- **Final word (Dziwny Mag):** It was an assembly error, not the gear.
- **Note:** The engine is non-interference, so the valves were not damaged.
- **Status:** CONFIRMED (second-hand).
- **Quote:** "po około minucie pracy zerwały się 4 ząbki na kole rozrządu"
- **Source:** t=3227 (photo: `images/owner-russian-red-timing-gear-polskiedostawczaki.jpg`)

**OR-69. Timing gear disintegrated with age; after replacement the rotor was 180° out.** Poncki.
- **Advice (Strucelsw):**
  - Camshaft end float 0.2–0.5 mm, about 0.3 mm with the gear tightened.
  - Zero end float strips teeth.
- **What happened:** He did not know the distributor follows the oil-pump shaft. While re-timing, a big explosion in the silencer destroyed the exhaust. It started after many attempts.
- **Status:** CONFIRMED.
- **Quote:** "Efekt jest taki, że palec obrócony jest o 180 stopni."
- **Source:** t=3227

**OR-70. Pushrods keep falling out while adjusting the valves after a head-gasket job.** Robo.
- **Advice (Marian):** Seat the ball ends properly in the tappet cups (use a torch to see), and check for bent pushrods.
- **Status:** SUGGESTED.
- **Quote:** "zawsze któraś laska wypada"
- **Source:** t=1432

**OR-71. Distributor rebuilt with the mechanism from a Star truck 6-cylinder petrol distributor, to avoid a new one costing about 400 PLN.** Przypadkowy.
- **What it took:** About 8.5 mm adapter washers.
- **Result:** Started first time and runs smoothly.
- **Status:** CONFIRMED.
- **Flag (Strucelsw):** The 6-cylinder cam and the advance weights and springs differ, so the advance curve is unverified.
- **Quote:** "Odpaliła od pierwszego strzału"
- **Source:** t=2914

## 16. Other

**OR-72. Spark plug heat range: owners contradict each other.**
- nysanek recommends NGK B7HS or BR7HS (t=1296).
- Strucelsw says B7HS plugs are too cold ("za zimne świece, to na pewno") and that B6HS or B5HS is right. He recommends Denso WF20TT and warns of fake NGKs (t=4814).
- **Flag:** No factory plug type is online; check your manual.
- **Status:** SUGGESTED.

**OR-73. Idle speed.** Marian: Weber about 800–900 rpm; Jikov down to about 500 rpm. Strucelsw: the Weber idle is set higher only for CO limits.
- **Status:** SUGGESTED.
- **Quote:** "Dla webera to ok. 800-900, jak dobrze pamiętam"
- **Source:** t=3250

---

## Patterns

**How the counts were made.** Each row counts the 73 new cases above (OR-xx), plus the rows in `common-problems.md` and `diagnosis-guide.md` that name the same cause (shown as "+ existing"). A case is counted under the cause found or most strongly suspected. Some cases count in two rows.

| # | Cause family | New cases | Existing KB | Total | Notes |
|---|---|---|---|---|---|
| 1 | **Ignition and timing.** Timing lost or off, points not set, bad leads or plugs, worn or seized distributor. | 14: OR-08, 09, 10, 11, 12, 15, 16, 25, 62, 66, 67, 69, 71, 72 | 8 | **22** | At least 5 are CONFIRMED. The timing is often lost after oil-pump or distributor work (OR-66, 67, 69). |
| 2 | **Cooling system.** Passages, head tube, air locks, thermostat, cap, hoses, water pump. | 9: OR-19, 20, 21, 22, 23, 24, 51, 52, 57 | 8 | **17** | Overheating is still the single most discussed symptom. |
| 3 | **Fuel supply and fuel quality.** Pump, tank pickup, sludge, bad fuel, LPG cut-off wiring. | 8: OR-01, 02, 03, 04, 05, 16, 47, 61 | 5 | **13** | In OR-01, 02, 04 and 61 the carb was blamed first. |
| 4 | **Head gasket and water in oil, including look-alikes.** | 8: OR-35, 36, 37, 38, 39, 40, 41, 42 | 3 | **11** | Two look-alikes: a core plug (OR-40) and a cracked liner (OR-42). Short-trip condensation (OR-47, 48) also mimics it. |
| 5 | **Oil-pressure readings.** | 7: OR-28 to 34 | 3 | **10** | In at least 3 (OR-28, 31, 33) the **gauge or sender** was the problem or the main suspect, not the engine. Real low pressure was fixed by relief-valve and pump-cover work or an oil change (OR-29, 30). |
| 6 | **Valvetrain mechanical.** Stuck tappets or valves, bent or dropped pushrods, clearances. | 4: OR-01, 26, 53, 70 | 2 | 6 | Plus clearance-setting flags in OR-09, 35 and 55. |
| 7 | **False air / vacuum leaks.** Manifold gasket or nuts, servo hose. | 3: OR-09, 12, 13 | 2 | 5 | |
| 8 | **Timing gear.** Bakelite gear stripped, or the replacement failed. | 3: OR-54, 68, 69 | 1 | 4 | |
| 9 | **Crankcase breathing and condensation.** | 4: OR-46, 47, 48, 49 | 1 | 5 | |
| 10 | **Mounts and body resonance.** | 2: OR-58, 59 | 1 | 3 | |

**Top 5 by total:**
1. Ignition and timing: 22.
2. Cooling system: 17.
3. Fuel supply and quality: 13.
4. Head gasket and look-alikes: 11.
5. Oil-pressure readings, where a gauge or sender error is common: 10.

## Lessons owners repeat

1. **Check ignition first and the carb last.** Several "carb problems" turned out to be ignition, the fuel pump, bad fuel, an LPG solenoid wire or false air (OR-01, 02, 04, 12, 13, 61).
2. **The distributor is driven through the oil pump.** Mark the rotor and the pump slot before touching either. A failing pump also moves the timing (OR-66, 67, 69).
3. **Prove an oil-pressure problem with a mechanical gauge before taking the engine apart.** Senders and dash gauges lie (OR-28, 31, 32, 33, 49).
4. **Bubbling in the radiator after shutdown, or oil spots in the coolant, points to the head gasket.** But mayonnaise that clears on long runs is condensation, and water in the oil can come from a head core plug (OR-35, 37, 40, 48).
5. **Fit the head gasket dry, tighten from the centre outwards, and re-torque after about 100 km.** (The torque value is still unconfirmed: see OR-36.)
6. **Before starting an engine that has stood for years,** drop the sump, flush the tank and use fresh fuel. Sludge and stale petrol stick valves and bend pushrods (OR-01, 53).
7. **Don't run without a thermostat. Bleed the air out after a refill. Carry spare hoses** (OR-21, 22, 24).
8. **New is not always better.** New HT leads, hard aftermarket mounts, a "regenerated" water pump and a red Russian timing gear all caused problems (OR-10, 51, 58, 68).
9. **On LPG,** look after the plugs, leads, cap, rotor and valve clearances more often. Advance the timing slightly and do not over-lean the mixture (OR-62, 63, 64, 65).
10. **Common owner advice that disagrees with factory data:**
    - "All valves at 0.20 mm". The factory exhaust clearance is 0.25–0.30 mm.
    - Timing at 8°. The factory figure is about 7° (5° in one source).
    - Kerosene in the oil, two-stroke oil in the petrol, and running without the oil cap.
    - Soaking the head gasket in oil.
    - Treat all of these with caution.
