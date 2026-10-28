# Checklist: "It ran before, someone cleaned the carburettor, now it won't run"

> **Reference only.** This file is about the older **34S2B1**. For the owner's **Weber 28/35**, use [../weber-28-35/](../weber-28-35/after-cleaning-checklist.md).

Situation: the engine is an S-21 with a Polmo Weber 34S2B1, fitted to a GAZ-69. The engine ran before the carburettor was cleaned. Afterwards it won't start or won't keep running.

> **Check which carburettor you have first** (see `../README.md`, "Identify your carburettor"). Most forum tips below come from owners of the later **28/35 S2A / S2B1**. Per the factory manuals, the **34S2B1** differs in three ways that change these checks:
> - It has **no idle cut-off solenoid** (items 5 and 12 apply only to the 28/35).
> - It has **no choke flap**. Cold start uses a cable-operated piston starter device (item 6).
> - Its **secondary throttle is opened mechanically** from the primary, not by a vacuum diaphragm (item 7).
>
> Its factory float setting is **5–5.5 mm**, not the forum's 6.5 mm (item 10). See `specs-and-jets.md`, Table 1.

That pattern points to **reassembly errors or damage done during cleaning**, ahead of wear. Owners on the S-21 forums report exactly this ("an epidemic of carburettors that won't start after a pre-Christmas clean").
Source: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4635

The original Polish wording for each forum tip used here is in the "Polish originals" table in `troubleshooting.md` and in `forum-experiences.md`.

Key Polish phrases to search for:
- "dysze wkręcone odwrotnie" (jets fitted the wrong way round)
- "zaworek iglicowy zacięty" (needle valve stuck)
- "dysza wolnych 45" (idle jet 45)
- "oring elektrozaworu 6x2mm" (solenoid O-ring 6×2 mm)
- "poziom paliwa ok 6,5mm" (fuel level about 6.5 mm)

Work through the checks in order. The cheapest and most likely come first. [DOC] marks a source fact, [FORUM] an owner or mechanic report, and [GENERAL] general carburettor practice.

## A. Before touching the carburettor (10 minutes)

1. **Fresh fuel and supply.** Disconnect the hose at the carburettor inlet and work the hand-primer lever on the mechanical pump, or crank the engine. Fuel should come out in strong pulses. If it doesn't, check the pump, filter, tank tap and pickup before the carburettor.
   - [FORUM] A sticking S-21 fuel pump caused start-then-die even though the pump looked fine. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=5136
   - A GAZ-69 swap may have a non-standard pump or electric pump. Check its pressure is low. Carburettor needle valves are designed for a mechanical pump; this is a general rule, and the exact S-21 figure is unknown.
2. **Spark and timing were not disturbed.** If the distributor or fuel pump was removed during the job, re-check timing.
   - [FORUM] A Nysa had "carburettor problems" that turned out to be timing knocked out while the pump was refitted. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=2247
3. **Plugs.** Pull one after a start attempt:
   - **Wet with fuel**: flooding (go to D).
   - **Dry**: no fuel (go to B/C).
   - Fit clean plugs before each new test. [FORUM] recommends Denso W20FS or WF20TT and warns of counterfeit NGK. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4814

## B. Quick on-engine carburettor checks (air filter off)

4. **Accelerator pump squirt.** Open the throttle by hand with the engine off. A clear jet should spray into the primary throat.
   - **No squirt**: the pump nozzle, ball or diaphragm is missing or wrong.
   - [FORUM] One Żuk carburettor came back from cleaning without its accelerator pump nozzle, which is "fi 80 with a ball". https://forum.polskiedostawczaki.pl/viewtopic.php?f=15&t=5488
   - See photo `images/b-forum-zuk-weber-missing-accel-pump-nozzle.jpg`.
5. **(28/35 only. The 34S2B1 has no solenoid.) Idle cut-off solenoid (elektrozawór) clicks.** Switch the ignition on and pull the wire off and on again. You should hear a click.
   - Check it actually has +12 V with the ignition on. On a GAZ-69 swap the wire may not even be connected.
   - [FORUM] With no power, a spring holds a needle in the idle jet, and there is no idle at all. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4635
   - **Temporary test only:** a short jumper from battery + to the solenoid terminal.
6. **Choke / cold-start device.** On the 34S2B1 there is no flap. Pulling the knob must move the starter-device lever through its full travel, and pushing it in must return it fully, or the engine runs rich (see `how-it-works.md`). On carburettors that do have a flap, it must close fully with the knob out and open fully with it in.
   - Linkage misassembly is common after a strip-down. On these units the choke is the small cable-operated lever. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4279
7. **Throttle plates.** Both primary and secondary plates must close fully and must not stick.
   - Check the idle-speed (stop) screw has not been backed right off. If the primary plate is fully shut, the engine gets too little air to idle.
   - Check it is also not wound in so far that the plate sits well open. The progression holes then feed fuel, and idle speed is high. [GENERAL]
   - Per the 1985 factory manual, the 34S2B1 secondary is opened mechanically by a lever from the primary spindle, from about 2/3 primary travel. Check that the linkage is reconnected and the secondary plate rests closed. If your carburettor has a diaphragm pot with a hose to the secondary, it is a vacuum-secondary variant: check that the rod is connected and the diaphragm holds vacuum.
8. **Vacuum leaks.** Look for:
   - Base gasket missing, doubled, or with the insulator spacer left out.
   - Base nuts loose.
   - Distributor vacuum hose and breather (odma) hose not reconnected.
   - Brake-servo hose.
   - [FORUM] Hose routing on a Żuk S-21 Weber: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4713 (photo `images/b-forum-zuk-s21-weber-hose-routing.jpg`).
   - Gasket shapes: `images/b-gaz69-weber-s21-gasket-set-1.jpg`, `images/b-gaz69-weber-s21-base-gaskets-1.jpg`.

## C. Lift the top cover (keep the gasket intact) and inspect

9. **Float (pływak) and needle valve (zaworek iglicowy).**
   - The float must move freely and not rub the bowl wall.
   - The needle must be fitted point-down in its seat, with any spring-damper clip correctly hooked.
   - Shake the float and listen for fuel inside: a sound means it is holed.
   - [FORUM] A needle was found stuck open after storage, which caused flooding. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4814
10. **Fuel level / float setting.** **34S2B1 factory setting: 5–5.5 mm** from the cover face, with the cover held vertical (1985 Żuk manual; see `specs-and-jets.md` and `adjustment-procedures.md`). The forum figure of **about 6.5 mm** below is for the 28/35 types. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4814
    - An owner who found 8.5 mm reset it to 6.5 mm. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3998
11. **Jets in the right holes.** Main jets, air correctors and emulsion tubes are often swapped between primary and secondary.
    - Read the stamped numbers and compare them with the spec table. The primary main jet is the smaller one, about 110–125. The secondary is larger, about 125–150 depending on the variant (see the jet-table files).
    - [FORUM] A Żuk A ran black-smoke rich, with the mixture screw fully in, because the jets had been **swapped during cleaning**. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=30
    - [FORUM] On the 28/35 S2A1, the F27 tube is primary and F35 is secondary. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3998
12. **Idle jets.** **34S2B1:** two plain idle jets, **50** each for primary and secondary (factory). **28/35 only:** the idle jet sits on the solenoid tip. It should be about 45, and present, not snapped off.
    - The jet screws onto or into the solenoid's end, and its 6×2 mm O-ring must be intact.
    - [FORUM] A user broke the solenoid tip off and with it the idle jet. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4635
    - [FORUM] A crushed jet or bad O-ring causes rich running. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4814
    - Fallback: a plain M8×1 jet holder with a 45 jet can replace a dead solenoid. The engine will then run on after the ignition is switched off. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4635
13. **Small parts: check that all of these are present.**
    - Accelerator pump nozzle and its ball.
    - Pump inlet valve.
    - Small plungers and their springs and retainers.
    - Inlet filter screen (sitko).
    - [FORUM] A Żuk carburettor lost a plunger and spring retainer during disassembly; the replacement part cost about 5 zł. https://forum.polskiedostawczaki.pl/viewtopic.php?f=16&t=3995
14. **Passages really clean.** Blow every passage with compressed air through a rubber tip, and spray cleaner through the idle and progression holes.
    - Do **not** use wire in jets, as it enlarges them. [FORUM checklist] https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777
    - [FORUM] One owner's no-start was cured only by a second, much more thorough clean that dislodged debris from the internal channels. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4635&start=15
15. **Gaskets.** Every gasket should be present and single, with nothing blocking a passage hole. Check the cover gasket, the base gasket(s) and the jet and O-ring seals.
    - [DOC] Kits with matching gasket shapes: see `rebuild-kits.md`.

## D. If it now floods

16. Recheck items 9–12. Then do the **mixture-screw test**: screw the idle mixture screw gently all the way in.
    - [FORUM, Strucelsw] If the engine still runs, extra fuel is coming from the float, needle or solenoid O-ring. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4814

## E. Basic setting to get it running

17. **Idle mixture screw (śruba składu mieszanki).** Turn it in gently until it seats, then back it out.
    - A forum guide used **2 turns out** as a start.
    - Strucelsw says a healthy Żuk carburettor ends up **0.5–1.25 turns out**. Sources: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4814
    - Screwing it **in** makes the mixture leaner. One admin post in t=4635 says the opposite; treat that as an error, since Strucelsw's test in t=4814 implies in = leaner.
18. **Idle speed screw.** Open it enough to keep the engine running. Warm the engine up, then set the mixture for the highest smooth idle and drop the speed again. See videos.md and "tuning" below.
19. **Sanity check.** With a warm engine and the choke off, the engine should idle evenly. The plugs should be light brown after a short run, not black and sooty.

## Tuning tips owners use

- **Adjust only when hot.**
  - Use the plug colour, not your ear alone (general elektroda advice): https://www.elektroda.pl/rtvforum/topic2853624.html
- **CO meter.** An owner reached about 2.4% CO at idle (λ 1.024) on a Nysa after the fixes. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3998
- **Vacuum gauge.** No S-21-specific source was found.
  - [GENERAL] Set the mixture for the highest steady manifold vacuum at idle, then reset the idle speed.
- **Order Strucelsw recommends** (t=3139): ignition, plugs and intake first. Then a sealed needle valve, then the float level, and only then the idle mixture. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3139
- **Prerequisites.** Fuel-level setting needs a tool, and the needle valve and accelerator-pump diaphragm must seal, or adjustment is pointless (Strucelsw). https://forum.polskiedostawczaki.pl/viewtopic.php?p=44947
