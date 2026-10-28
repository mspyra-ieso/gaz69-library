# "It ran before, someone cleaned the carburettor, now it runs badly": Weber 28/35 checklist

The engine is an S-21 in a GAZ-69, with a Weber 28/35 (probably the S2A1) and the EZ-20 idle solenoid. It ran before the carburettor was cleaned and has run badly since. Owners of these carburettors report exactly this pattern; one called it "an epidemic" ("To jakaś epidemia na gaźniki", https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4635).

In the 10 owner cases that follow a clean or strip-down (`owner-reports.md`), the causes were, in order:
1. jets in the wrong throat or small parts lost;
2. idle mixture not re-set, or the idle-jet seal leaking;
3. float level not reset;
4. dirt pushed further into the passages.

The solenoid failed only by being unpowered or by losing its tip jet.

**Values used below.** These are factory figures from `specs-and-jets.md`, the master table compiled by the specs track. They agree with the Z89 Żuk 1989 manual table already in `../weber-34s2b1/specs-and-jets.md` Table 3, **except the float level**: Z89's "5–5.5 mm" is probably copied from the 34S2B1 manual. Use 6.25–6.75 mm (S2A1) or 7 ±0.25 mm (S2B1), without gasket.

| Part | Throat I (primary, 28 mm) | Throat II (secondary, 35 mm) |
|---|---|---|
| Main jet | **110** | **145** (S2A/S2A1) · **125** (S2B1) |
| Air-correction jet | **250** | **225** (S2A/S2A1) · **220** (S2B1) |
| Emulsion tube | **F27** (the thicker one) | **F35** |
| Idle / progression jet | **45 on the solenoid tip** | **100** in a plain holder |
| Pump jet / pump valve | 40 / 80 | — |
| Needle valve | 175 | — |
| Float | 18 g; 6.25–6.75 mm (S2A1) or 7 ±0.25 mm (S2B1), without gasket; drop to 13.5 mm | — |
| Idle speed | 600–800 rpm | — |

Labels:
- **[DOC]**: factory or shop data.
- **[FORUM]**: owner experience; "(Oxx)" is a case number in `owner-reports.md`.
- **[GENERAL]**: general practice.

---

## A. Ten minutes, before touching the carburettor

1. **Spark and timing.** Was the distributor, the coil or the fuel pump disturbed during the job? The pump drive can knock the timing out (O4). Firing order is 1-2-4-3. Fit **known-good plugs**: new ISKRAs failed in three cases (O3, O35, O36).
2. **Fuel to the carburettor.** Pull the inlet hose and use the pump's hand lever. You should get strong pulses.
   - On a GAZ-69 with an **electric pump**: the S-21 has no return line, and a pump that is too strong floods the carburettor (O20). Use a low-pressure carburettor pump, ideally with a return line.
3. **Plug after cranking.** A **dry** plug means no fuel (sections B–C). A **wet** plug means flooding (section D) or ignition.

## B. Solenoid (elektrozawór) and idle jet: do these first on a 28/35

4. **Power.** Ignition on: is there +12 V at the solenoid's spade terminal?
   - The feed must come from an **ignition-switched** source: on the Żuk, coil terminal "B" / "15", red-black wire. Not terminal D, which goes to the points (O10). https://forum.polskiedostawczaki.pl/viewtopic.php?t=3091
   - After a swap into a GAZ-69, check the wire exists, is not corroded (compare O5), and is **not** on a permanently live circuit, which would cause run-on.
5. **Click.** Ignition on, pull and refit the spade: you should hear a click. Or unscrew the solenoid and give it 12 V on the bench; the cone must pull back fully. [FORUM, Marian, t=4635]
6. **Tip jet present and intact.** The jet sits on the end of the solenoid.
   - It should be stamped **45**. A "50" is too rich (`specs-and-jets.md`, flag 3).
   - Owners snap it off while cleaning (O1).
   - Blow it clear with air or solvent. **Never use wire**: it enlarges the jet (t=777 checklist). https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777
7. **O-ring and seat.**
   - The jet's sealing O-ring is **6×2 mm** (Strucelsw), factory ring 033844. It must be present and undamaged, and **not too thick**.
   - The jet must not be crushed from over-tightening.
   - A bad seal lets fuel past the jet: rich idle, the mixture screw has little effect, emissions fail (O13, O40). https://forum.polskiedostawczaki.pl/viewtopic.php?t=4329
   - Do **not** over-tighten the solenoid on reassembly.
8. **Stall test** (once it runs). At idle, pull the solenoid wire: the engine **must stall** (O11). If it doesn't, fuel or air is bypassing (steps 7, 13, 18).
9. **No solenoid to hand?** [DOC, FORUM] A plain holder with a 45 jet works as a temporary fix, but the engine will then run on after switch-off (Strucelsw, t=4635). Shops sell the holder kit for about 40 zł, and EZ-20 solenoids new or regenerated (`rebuild-kits.md`). A 126p/Polonez solenoid **may carry a different jet**, so move your 45 across.

## C. Quick checks with the air filter off

10. **Pump squirt.**
    - Work the throttle: a jet must spray into throat I. If not, the **pump nozzle "fi 80 with a ball"** is missing (O21; photo `images/o-forum-zuk-weber-missing-accel-pump-nozzle.jpg`), the ball under it is missing, or the diaphragm is split.
    - A dribble that continues after the throttle is released means a leaking pump valve. [GENERAL]
11. **Choke (cold-start device).**
    - Full travel with the knob out, full return with it in.
    - The cable outer must be clamped.
    - A choke that does not return makes the engine rich all the time (O41).
12. **Throttle plates.**
    - Throat I must close to its idle stop. Throat II must close fully and open **only near the floor** (O26).
    - The idle-speed screw must not have been backed right off, or wound in so far that the engine idles on the progression holes.
    - Check the linkage is reconnected, and that the **crankcase-gas valve in the manifold** moves freely, because it can block the secondary (O27).
13. **Air leaks.**
    - Base gaskets present and single.
    - The **phenolic insulating spacer** fitted, not cracked or warped (O34, O44). Do not over-tighten the base nuts, because the base warps (Marian, t=4581).
    - Vacuum and breather hoses back on (photo `images/o-forum-zuk-s21-weber-hose-routing.jpg`).
    - The breather plunger in the manifold not stuck open (O11).

## D. Lift the cover (keep its gasket intact) and inspect

14. **Float.**
    - Shake it; any sloshing means it is holed.
    - Weigh it if you can: **18 g**. 24 g means it is full of fuel (O12).
    - It must swing freely and not rub the bowl.
15. **Needle valve (175).**
    - Fitted point-down, its damper ball free, sealing (O13, O14).
    - Hold the cover upside down and blow into the inlet. It must shut off as the float lifts. [GENERAL]
    - The washer under the seat sets the height. The factory washers are 0.5 / 0.7 / 1.0 mm (`specs-and-jets.md`), so keep the original.
16. **Float level.**
    - Cover held **vertical**, **gasket removed**, measure from the cover face to the float: **6.25–6.75 mm (S2A1)** or **7 ±0.25 mm (S2B1)**. Full drop 13.5 mm.
    - The forum value is 6.5 mm "without gasket" (Strucelsw, t=4329).
    - Measuring with the gasket on, or not resetting after a new float, causes trouble (O17, O23).
17. **Jets in the right throats.** Read the stamped numbers against the table above.
    - The swap owners report is the two **main jets** (O38, O39).
    - Also check the **emulsion tubes**: F27, the thicker one, goes in throat I. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3998
    - The **air jets** are 250 in I and 225 (or 220) in II.
    - A primary main jet of 118 or similar is not factory (O14).
18. **Secondary idle/progression jet (100)** present and clear. [DOC]
19. **Small parts present:**
    - pump nozzle and ball;
    - pump inlet valve;
    - inlet strainer (sitko), clean (O6);
    - the plunger, spring and retainer in the cover near the starter (O22);
    - any small springs. A broken one flooded a 28/35 S2A (O15).
20. **Passages really clear.** If it still won't idle or pick up, do a **second, thorough clean**:
    - Soak and warm the body.
    - Blow out every drilling: idle air, mixture, progression holes 2 × 0.8 mm in I.
    - It cured O1. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4635&start=15
21. **Gaskets.** Cover gasket, base gaskets and spacer stack all new and single, with no gasket covering a passage. Kits: `rebuild-kits.md`; gasket photos `images/o-gaz69-weber-s21-gasket-set.jpg`.

## E. If it now floods or fuel comes from the manifold drain holes

22. Fuel from the two drain holes in the intake manifold means **overflow** (O16–O18). Recheck steps 14–16.
    - Then check the pump pressure: the mechanical pump must have its **bakelite spacer and two gaskets** (O16, O19).
    - An electric pump must be a low-pressure type (O20).
23. **Mixture-screw test** (Strucelsw, t=4814). Hot, at idle, screw the mixture screw gently fully in. If the engine still runs, fuel is leaking in from the float, the needle or the solenoid O-ring (step 7).

## F. Basic setting to get it running

24. **Mixture screw (śruba składu).**
    - Turn it gently in until it seats. Do not force it, or the tip and seat are damaged.
    - Then back it out about **1.5–2 turns** for the first start. Owners start from 1.5 (O37); the earlier guide used 2.
    - Strucelsw says a healthy Żuk carburettor ends up **0.5–1.25 turns out**. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4814
    - **In = leaner.** ⚠ An admin post says the opposite (O44); treat it as an error.
25. **Idle-speed screw.** Enough to keep it running while it warms up.
26. **Warm engine, choke fully in.**
    - Set the mixture screw for the highest, smoothest idle.
    - Bring the speed back to **600–800 rpm**.
    - Repeat once.
    - ⚠ Don't "fix" a rough idle by raising it to 900–1000 rpm (owner-reports flag 3).
27. **Checks.**
    - Pulling the solenoid wire stalls it (step 8).
    - Pump squirt on a blip.
    - Plugs light brown after a run.
    - The secondary opens with the pedal floored.
    - Expected consumption is about 11–16 l/100 km in a Żuk (O41). A GAZ-69 is heavier, so expect more.

## G. Still bad?

- Swap in a **known-good or regenerated 28/35** to split carburettor from engine (`rebuild-kits.md`: about 800–950 zł exchange).
- Consider the S-21 engine causes in `../s21-engine/diagnosis-guide.md`: valve clearances 0.20–0.22 mm, compression, head.
