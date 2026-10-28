# 28/35 S2A1 / S2B1: adjustment procedures

The source keys are defined in specs-and-jets.md. Each step is marked FACTORY (Z89, Z94, CAT88, BI11), BOOK (WZ) or SITE/FORUM (PD, FPD).

## 0. Before adjusting

[FACTORY] Z89 and Z94 list these checks:
- The engine is **hot**: adjust on a hot, running engine ("na gorącym (pracującym) silniku").
- Ignition advance is correct.
- Ignition system works.
- **Compression is checked** (Z89).
- **The fuel system and carb are air-tight** ("szczelność gaźnika", "szczelność układu zasilania").

Z89 says to adjust only when the engine misfires, idles too slowly (stalls), or idles too fast.

[SITE] PD adds:
- a clean carb with clear jets and no throttle-spindle play;
- engine at about 80 °C;
- a float that is not holed.

## 1. Float level

Images:
- `t-28-35-s2b1-float-level-zuk-manual-1994.jpg` (factory, S2B1)
- `t-wz-table2-18-and-fig2-49-50-float-level.jpg` (book, S2A1)
- `t-28-35-s2a1-float-and-dismantling-book-scan-pd.jpg`

| Variant | Distance a: cover face, **no gasket**, to float | Maximum drop b from cover face | Source |
|---|---|---|---|
| **28/35 S2A / S2A1** | **6.25–6.75 mm** (aim for 6.5) | 13.5 mm | BOOK WZ Table 2.18; SITE PD |
| **28/35 S2B1** | **7 ±0.25 mm** | 13.5 ±0.5 mm | FACTORY Z94; BOOK WZ |
| (34S2B1, for comparison only) | 5–5.5 mm | 13.5 mm (travel 8.5 mm) | FACTORY Z85 |

Do **not** use the 5–5.5 mm printed in the 1989 manual for a 28/35. See specs-and-jets.md for why it is considered a carry-over from the 34S2B1 text.

Steps (Z94, Rys. 4.10; Z89 is the same apart from the value):
1. Remove the cover with the float attached.
2. Check that the **float has no dents** and swings freely on its spindle.
3. Check that the **needle-valve body is screwed tightly** into its seat. Check that the **damper ball in the needle is not stuck** ("kulka … amortyzatora drgań iglicy … nie jest zablokowana").
4. Hold the cover **vertical**, so the float's own weight does **not** push the ball into the needle ("swym ciężarem nie wcisnął kulki").
5. Measure **a** from the cover face **without the gasket** to the float.
6. Correct **a** by **bending the hinge arms** [ramiona zawiasy]. Keep the **tongue** [języczek] **perpendicular to the needle** ("prostopadły do iglicy").
7. Let the float hang down and check **b** = 13.5 mm (S2B1 tolerance ±0.5). Correct it by bending the **stop tab** [występ zawiasy].
8. Refit the cover. Check that the float moves freely without rubbing the chamber walls.
   - Z89 says to repeat this check after replacing the float or needle valve, and to fit a new cover gasket.
9. **Coarse correction** [FACTORY parts list]: needle-valve sealing washers come in 0.5, 0.7 and 1.0 mm (CAT88), or 0.5 and 0.7 mm "wg potrzeb" (BI11). Use them if bending alone cannot get the setting. A thicker washer raises the seat. This is an inference from the parts list; no procedure text was found.

### Fuel-level check on the engine (BOOK WZ Fig. 2.55)

- After any repair, WZ says to check the fuel level in the float chamber with a graduated tube-type gauge.
- The figure legend lists the gauge's parts: fixing screw, graduated body, tube, float chamber, cover. Exactly where it connects is not clear from the translation.
- No MIN/MAX heights for the 28/35 were found.
- The 1985 manual's procedure with gauge 17-P-1107 (34S2B1) is in `../weber-34s2b1/adjustment-procedures.md`.

## 2. Idle speed and mixture

Idle speed: **600–800 rpm** (Z89, Z94, WZ).

### Factory procedure

[FACTORY] Z89 (28/35 S2A), Rys. 4.9:
- Screws: 14 = mixture screw [wkręt regulacyjny składu mieszanki wolnych obrotów]; 15 = throttle-position (idle-speed) screw.
- If the idle is too low, open the throttle more with **screw 15**.
- The engine must run evenly and not stall at 600–800 rpm.
- **Z89 gives no mixture-screw procedure and no starting turns.**

[FACTORY] Z94 (28/35 S2B1):
- The mixture screw 12 is **sealed** ("zaślepiony").
- Idle speed is set only with **screw 13** (throttle position):
  - turn it **in** to raise the idle;
  - turn it **out** to lower it.

### Enthusiast procedure for the Weber 28/35

[SITE] PD, by Marian, with drawings from M. Lubczyński, *Naprawa samochodów Nysa*. Screw 1 is the throttle screw and screw 2 the mixture screw on the 28/35 S2A1 drawing `t-28-35-s2a1-idle-screws-solenoid-book-scan-pd.jpg`.
1. Engine hot, float level set.
2. Turn the **mixture screw (2)** **gently fully in**, then **out 2 turns**.
3. Start the engine. With the **throttle screw (1)**, set the lowest speed at which it still runs evenly.
4. Turn the **mixture screw** to get the **highest even speed**, with no choking or shaking.
5. Lower the speed again with the throttle screw (unscrew it) to the correct idle.
6. **Test:**
   - Snap the throttle open and let go. The engine must return to idle without stalling. If it stalls, turn the throttle screw in slightly.
   - It must not pop back through the carb or the exhaust (with the ignition set correctly).

The older 1985 34S2B1 factory procedure starts at **3 turns** out and is otherwise similar. That is a different carb; see `../weber-34s2b1/adjustment-procedures.md`.

### Which way the mixture screw works

- General Weber practice: the idle mixture screw is a tapered needle in the idle-mixture outlet, so **screwing in = leaner, screwing out = richer**.
- [FORUM] t=4635 contains a contradicting post ("żeby zubożyć … musisz wykręcić", i.e. unscrew to lean).
- Neither source shows a factory statement. Confirm on the engine: if turning the screw in makes the engine slow and stumble, it is going lean.
- **Unverified.**

### CO

- **No factory CO value** for the 28/35 was found in Z89, Z94 or WZ.
- [FORUM] One Nysa owner with an S2A1 (t=3998) measured **idle CO 2.4 %, lambda 1.024** after fixing a leaking needle valve and fitting the correct 110 primary jet. Before that: CO >7 %, λ 0.76–0.83 at 2500 rpm. These are example readings, not a specification.

## 3. Cold-start (starter) cable

[BOOK] WZ, 28/35 S2A1:
- The lever has positions A (cold), B (warm) and C (off). Travel is 68°.
- Adjust the cable so that, with the lever **against its stop on the starter cover** (fully off, C), the cab knob still stands **2–3 mm** short of its housing. This guarantees the starter switches fully off.
- Fault link (Z89 and Z94 fault tables):
  - a starter left partly on gives high consumption and rich running;
  - a stuck starter valve or blocked starter jet gives a cold no-start.
- The fix is to clean the starter channels with compressed air.
- No fast-idle or choke-flap gaps exist on this design.

## 4. Accelerator pump

- Factory data:
  - pump jet **40**, valve **80**, stroke **10 mm**, output **5 cm³ per 10 strokes** (Z94; WZ);
  - Z89 gives "0,5" cm³, i.e. per stroke.
- **No factory stroke-adjustment procedure** was found.
- WZ says that after a repair the operation of "individual devices" must be checked with special test equipment.
- Simple workshop check (common practice, not from a source):
  1. Engine off, float chamber full.
  2. Snap the throttle open while looking into throat I.
  3. A firm jet should come from the injector.
  4. Over 10 full strokes, the output collected should be about 5 cm³.
- Z89 and Z94 fault tables: poor acceleration can come from a blocked pump channel or jet ("kanał lub dysza pompy przyspieszającej"). Remedy: blow through with compressed air.

## 5. Secondary throttle

[FACTORY] Z89 and Z94:
- The secondary starts opening at **2/3** of primary opening.
- It is driven by the release lever from the primary spindle.
- WZ: total primary lever rotation is 78°.

Check:
1. Open the primary slowly by hand. The secondary must stay shut until about 2/3, then reach full open together with the primary.
2. Both plates must **close fully** when released.
   - Fault table: "przepustnice nie domykają się" (throttles not closing) causes rough idle.
   - Remedy: check that the throttles turn freely.

Worn spindles leak air. Oversize spindles exist for both throats (CAT88; BI11).

## 6. Pedal travel and linkage

- Fault tables: an insufficient pedal stroke ("niedostateczny skok pedału gazu") gives poor acceleration and top speed. Remedy: adjust the pedal travel.
- WZ: about 56 mm at the pedal end for full throttle. (See the 34S2B1 adjustment file. The Żuk linkage is common to both carbs.)
- In the GAZ-69, check that the pedal reaches **full primary opening and therefore full secondary opening**.

## 7. Cleaning

[FACTORY] Z94:
- **When:** after the first **1000–1500 km**, then every **10 000 km**.
- **How:**
  1. Unscrew the main jets (10), and the idle jets after unscrewing the solenoid valve (9).
  2. Wash them in **kerosene or unleaded petrol**.
  3. Blow them through with **compressed air**.
- **Do not swap** the I and II main jets.

[BOOK] WZ:
- Remove the cover, the main jets, the idle jets I and II, the solenoid, the pump injector, and the mesh filter (after its plug).
- Wash everything in kerosene or clean petrol and blow through.
- **Never clean jets with steel objects.**

## 8. Mounting

[BOOK] WZ; [FACTORY] CAT88 11.10:
- Four M8 nuts.
- **Two gaskets with an insulating spacer between them** (4127681 ×2, 4127682).
- Z89 and Z94 fault tables: air leaks at these gaskets or the spacer, or between the manifold and head, cause rough idle. Remedy: tighten the carb nuts and check the mounting flange.
