# Weber 28/35 S2A / S2A1 / S2B1 on the S-21: troubleshooting by symptom

For the FOS/Polmo Weber 28/35 with the **EZ-20 idle cut-off solenoid (elektrozawór, "elektrodysza")**. The solenoid carries the **primary idle jet (45)** on its tip. Factory values are in `specs-and-jets.md`, and the solenoid itself is described in `solenoid-ez20.md`. Real cases (O1–O51) are in `owner-reports.md`.

**Labels**
- **[DOC]**: a factory or shop fact.
- **[FORUM]**: owner or mechanic experience, with "(confirmed)" when the owner reported that the fix worked.
- **[GENERAL]**: general carburettor practice, given without an S-21 source.

Main forum: forum.polskiedostawczaki.pl (FMPD). Its regular experts are Strucelsw (ran a carburettor workshop), Marian (admin) and nysanek.

## How the 28/35 idle circuit works (what the solenoid does)

- **[DOC]** The EZ-20 screws into the body in place of a plain idle-jet holder, and the **idle jet 45 sits on its tip**, sealed by an O-ring. Part numbers: solenoid 033845, jet 033842, ring 033844 (`specs-and-jets.md`). As sold, the EZ-20 kit is the switch, the jet and the ring (OE 5200625 / 5200623 / 5200624). https://sklep.roda24.pl/elektrozaw-243-r-gaznika-126p-pn.html
- **[FORUM, Marian]** With no voltage, a spring pushes a cone into the idle jet and the idle circuit is shut. With +12 V on the ignition, the cone retracts. "Jak nie ma napięcia sprężyna dociska stożek od wewnątrz dyszy". https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4635
- **[FORUM, sukiennik68]** Its job is to stop the engine: it cuts fuel and is switched by the ignition key. "zawór jest do gaszenia, odcina paliwo, sterowany stacyjką". https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4279
- **Consequence.** With the solenoid dead, unpowered, or with its tip jet blocked or broken, the engine **will not idle**, and it will start only with the throttle held open. If fuel leaks past the jet's seal, it runs **rich** and may **run on** after switch-off.

## 0. Before blaming the carburettor

Six of 51 owner cases were not the carburettor at all (`owner-reports.md`, Patterns).
- **Plugs.** New ISKRA plugs failed in three cases (O3, O35, O36). Strucelsw recommends Denso WF20TT or W20FS, or Bosch WR78G, and warns of counterfeit NGK. https://forum.polskiedostawczaki.pl/viewtopic.php?t=4329 , https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4814
- **Timing and firing order (1-2-4-3)**, especially if the fuel pump or distributor was removed. (O4) https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=2247
- **LPG cars.** The LPG kit adds a **second solenoid**: a petrol cut-off valve in the line between pump and carburettor. If its wire corrodes, the engine runs on gas but dies on petrol (O5, confirmed). https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=1608

## 1. Won't start (nie odpala)

Check in this order:
1. **Is fuel reaching the carburettor?** Pull the hose at the carburettor and use the hand-primer lever on the pump. Fuel should come in strong pulses.
   - [FORUM] After standing, the pump's valves let the fuel run back; give 5–6 hand strokes before cranking (nysanek). https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=489
   - [FORUM] A blocked tank pickup or an air leak in the line (O7, confirmed). A sticking pump (O8).
2. **Wet or dry plug?** After 10 s of cranking with the choke out:
   - **Dry**: no fuel. Go to step 3.
   - **Wet**: flooding or ignition. Go to §5 and §0.
3. **Accelerator-pump squirt.** Air filter off, work the throttle. A clear jet should spray into throat I (pump jet 40, valve 80; `specs-and-jets.md`).
   - No squirt: the pump nozzle (fi 80, with its ball) is missing, or the diaphragm is split. (O21) https://forum.polskiedostawczaki.pl/viewtopic.php?f=15&t=5488
4. **Solenoid power and click.** Ignition on: pull the spade connector off and push it back. You should hear a click.
   - Check for +12 V at the connector with the ignition on. The feed comes from the ignition-switched side of the coil (terminal "B" / "15", red-black wire), **not** from terminal D on the points side. (O10, confirmed) https://forum.polskiedostawczaki.pl/viewtopic.php?t=3091
   - **GAZ-69 swap:** the GAZ loom has no wire for this, so check one was added and that it is switched by the ignition.
   - Bench test: unscrew the solenoid, apply 12 V, and watch the cone retract. [GENERAL] Same principle as https://www.youtube.com/watch?v=asisdHfTpNs (a small-engine solenoid).
   - Emergency test: if it starts and runs with the throttle held slightly open but dies on release, suspect the solenoid circuit or the idle jet.
5. **Is the tip jet there and clear?** The 45 jet on the solenoid tip is tiny and is easily snapped off while "cleaning" (O1). https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4635
6. **Choke.** On the 28/35 the cold-start device is cable-operated. The cable must give full travel and return fully (O41). https://forum.polskiedostawczaki.pl/viewtopic.php?t=4256
7. **Passages still blocked.** A first clean can loosen dirt into the passages. [FORUM, confirmed] A second deep clean, soaked and heated twice, cured O1. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4635&start=15
8. **Prime test.** Pour a little fuel into the throats. If it fires and dies when that is used up, fuel is not getting from the bowl to the engine: pump, strainer, needle stuck shut, or blocked jets (nysanek, t=489). https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=489

## 2. Starts, then dies (odpala i gaśnie)

1. **Fuel supply.** Check the inlet strainer (sitko) in the carburettor (O6, confirmed), the pump (O8), the pickup (O7) and the hoses.
2. **Idle circuit dead.** It dies as the throttle closes. Check solenoid power, the tip jet, and the 6×2 mm O-ring (see §3).
3. **Choke released too early, or the float set too high** (O9). https://forum.polskiedostawczaki.pl/viewtopic.php?f=16&t=4392
4. **Needle stuck shut, or the float jammed** against the bowl wall after reassembly. [GENERAL]
5. **Cracked body** on ex-LPG engines. [FORUM] https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=5136

## 3. No idle, or idle won't hold or adjust (nie trzyma wolnych)

In order:
1. **Solenoid**: powered, clicking, tip jet present (see §1.4–1.5).
2. **Idle jet 45 blocked.** It clogged twice on one Nysa (O14). Clean it with solvent and air, never with wire.
3. **Idle-jet seal.** A crushed jet, or an O-ring that is damaged or **too thick** under the solenoid or the plug, lets fuel past the jet. The engine then runs rich and the mixture screw has little effect. Strucelsw gives the O-ring as 6×2 mm. (O13, O40) https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4814 , https://forum.polskiedostawczaki.pl/viewtopic.php?t=4329
4. **Mixture screw.** A healthy Żuk carburettor ends up 0.5–1.25 turns out (Strucelsw). If it was found screwed fully in, the idle circuit was shut off (O44). **In = leaner.**
5. **Air leaks.** Look at:
   - The base gasket and the phenolic insulating spacer. A cracked spacer gave a lean mixture and pinking on a GAZ-69 (O34).
   - Loose manifold nuts.
   - The vacuum and breather hoses (photo `images/o-forum-zuk-s21-weber-hose-routing.jpg`).
   - The brake-servo hose.
   - The **spring-loaded breather plunger in the intake manifold**, which can stick open (O11).
6. **Throttle plate not closing**, or a worn spindle. The Art-Mobil kit includes an oversize 8.2 mm primary spindle for this reason (`rebuild-kits.md`).
7. **Idle speed.** Factory 600–800 rpm (`specs-and-jets.md`). ⚠ Forum figures of 800–1000 rpm only mask a rich idle (owner-reports flag 3).

## 4. Runs on after the ignition is switched off (dieseling)

The EZ-20 exists to stop this. Checks:
1. **Is the solenoid really switched off with the key?** On a swapped engine (GAZ-69) it may have been wired to a permanent +12 V, or to a circuit that stays live, such as the generator warning light. Ignition off: the solenoid must lose power and click. [GENERAL, from the function described by sukiennik68, t=4279]
2. **Has the solenoid been replaced by a plain jet holder?** That works for driving, but the engine will run on after switch-off (Strucelsw, t=4635). Kits and shops sell the plain holder with a 45 jet; see `rebuild-kits.md`.
3. **Cone not sealing**: a worn cone, or dirt on its seat. Test: engine idling, pull the solenoid wire. It **must stall within a few seconds** (Strucelsw, O11). If it keeps running:
   - Fuel is getting past the jet (bad O-ring or crushed jet seat; §3.3).
   - Or the throttle is held too far open, so the progression holes feed the engine. This happens when the idle-speed screw is wound in to "make it hold idle".
   - Or air and fuel bypass through the breather plunger (O11).
4. **Engine causes** [GENERAL]: timing too far advanced, carbon hot spots, plugs too hot, or running hot. The S-21's tendency to pink is covered in `../s21-engine/`.

## 5. Floods, fuel leaks, fuel from the manifold drain holes (zalewa, przelewa)

**Background.** The S-21 Weber intake manifold has **two drain holes** that dump overflow fuel. Fuel from them **always means the carburettor is overflowing**. Do not block them. (O16–O18) https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=165

1. **Float.**
   - [DOC] It should weigh **18 g** (17.5–18.5). A float of 24 g with liquid inside is holed (O12, confirmed). https://forum.polskiedostawczaki.pl/viewtopic.php?t=4581
   - On LPG, a float that rattles wears through when its **lower stop** is not set (Strucelsw). https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4717
2. **Needle valve (175)** stuck open or leaking (O13, O14). Fit a needle with a spring damper. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3998
3. **Float level.** S2A1: 6.25–6.75 mm. S2B1: 7 ±0.25 mm. Both measured **without the gasket**, cover vertical, with the float drop limited to 13.5 mm (`specs-and-jets.md`). Measuring "with the gasket" (O17) or never resetting after a new float (O23) leaves it wrong.
4. **A broken small spring** made one chamber flood (O15, 28/35 S2A). https://forum.polskiedostawczaki.pl/viewtopic.php?f=3&t=5058
5. **Pump pressure too high.**
   - The mechanical pump fitted without its bakelite spacer, or with a thin one (O16, O19).
   - An **electric pump without a return line** (O20). The S-21 has no return line, so add one, or use a low-pressure pump made for carburettors.
6. **Mixture-screw test** (Strucelsw, t=4814). Hot, at idle, screw the mixture screw gently in. If the engine **keeps running with it shut**, fuel is coming from the float, the needle or the solenoid O-ring.

## 6. Hesitation, flat spot, no power (dławi się, przerywa, nie wchodzi na obroty)

1. **Accelerator pump.** Missing nozzle or ball (O21), split diaphragm, or the pump jet blocked. Check for a squirt.
2. **Small parts after disassembly.** A plunger and spring with its retainer in the cover (O22). Photos: `../weber-34s2b1/images/b-forum-weber-plunger-spring-1.jpg`.
3. **Float level too low or not set** (O23), or a blocked primary main jet or emulsion tube (O24).
4. **Main jets and emulsion tubes in the wrong throat.**
   - S2A/S2A1: 110 + F27 + 250 in throat I; 145 + F35 + 225 in throat II.
   - S2B1: 125 + 220 in throat II.
   - F27 is the thicker tube. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3998
5. **Secondary throat (druga gardziel) not opening.** On the 28/35 the secondary is opened mechanically and late in the pedal travel. It opens only with the pedal near the floor.
   - Adjust the rods (O26).
   - Check that the manifold's crankcase-gas valve, which is worked by the linkage, isn't seized and blocking it (O27).
   - Worn rod joints (O28).
   - Symptom: no power at the top end, idle normal (O29).
   - https://forum.polskiedostawczaki.pl/viewtopic.php?t=4581 , https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4162
6. **Preservative or dirt in a new or regenerated unit** (O25). https://zlombol.pl/community/technikalia-2/gaznik-weber-28-35-s2a-zuk-problem-2/
7. **Cold engine.** A lean stumble for a few minutes after the choke is pushed in is typical of the S-21 (O30, O31, O32). It should go once the engine is warm.

## 7. Backfire into the carburettor (strzela w gaźnik)

1. **Ignition first:** a dead cylinder, crossed leads, or wrong timing (O37).
2. **Lean mixture:**
   - Air leaks (§3.5).
   - Float level low.
   - Main or idle jet blocked.
   - Pump not squirting.
   - [FORUM] Marian's checklist: lean causes "STRZAŁY W GAŹNIK". https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777
3. **Secondary jets swapped** (110 in throat II) gives a lean flat spot at full throttle. [GENERAL]

## 8. Black smoke, sooty plugs, high consumption (kopci, pali dużo)

1. **Overflow**: float, needle, level (§5). Example: a Tarpan with heavy smoke and no power (O42).
2. **Jets swapped after cleaning**: confirmed in O38. A big secondary jet in the primary throat makes it rich at all times.
3. **Idle-jet seal leaking** (§3.3), as in O40 (failed emissions test, confirmed).
4. **Choke not returning fully** (O41), or the choke used for too long on short trips. 21 l/100 km fell to 16 after re-adjustment.
5. **Clogged air filter**; manifold pre-heater or air-filter flap stuck on "warm" (O42).
6. **LPG side** on dual-fuel cars: the reducer or mixer is set rich (O45, O46).
7. Realistic consumption: an S-21 Żuk in good order uses about 11–16 l/100 km, depending on trips (O41, O43).

## 9. Dies when hot, hard hot start (gaśnie na ciepłym)

1. **Percolation.** Fuel boils in the float chamber when hot, and vapour bubbles form. Hot-start trick: hold the throttle part-open, or wait (nysanek). https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=489
2. **Insulating spacer** under the carburettor missing (O44) or cracked (O34). Fit a new phenolic spacer.
3. **Heat shield** between the exhaust manifold and the float chamber (O49, confirmed): `images/o-nysa-weber-heat-shield.jpg`.
4. **Vapour lock on the suction side** of the pump (O50). Remove extra restrictions before the pump, such as non-return valves, and keep fuel lines away from the exhaust. Relevant on a GAZ-69 swap, where the lines are re-routed.
5. **Pump insulating spacer** missing (O19).

---

## Polish key phrases (for searching)

| English | Polish | Source |
|---|---|---|
| idle cut-off solenoid | elektrozawór, elektrodysza, wyłącznik biegu jałowego | https://sklep.roda24.pl/elektrozaw-243-r-gaznika-126p-pn.html |
| solenoid closes the jet when unpowered | "Jak nie ma napięcia sprężyna dociska stożek" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4635 |
| idle jet leaks past its seat | "za gruby oring tam jest(pod korkiem lub elektozaworem)" | https://forum.polskiedostawczaki.pl/viewtopic.php?t=4329 |
| float set 6.5 mm without gasket | "Wysokość pływaka ustaw na 6,5mm (bez uszczelki)" | https://forum.polskiedostawczaki.pl/viewtopic.php?t=4329 |
| float too heavy (holed) | "jest za ciężki ma 24g a wg książki ma mieć 18" | https://forum.polskiedostawczaki.pl/viewtopic.php?t=4581 |
| carburettor overflowing | "przelewa gaźnik. dziurawy pływak, nieszczelna iglica" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3707 |
| secondary opens only at the floor | "Druga sie otwiera zazwyczaj z pedalem w samej podłodze" | https://forum.polskiedostawczaki.pl/viewtopic.php?t=4581 |
| jets fitted the wrong way round | "miałem wkręcone odwrotnie dysze" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=30 |
