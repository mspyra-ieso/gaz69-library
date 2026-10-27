# Factory adjustment procedures

## Sources

| Key | Source |
|---|---|
| Z85 | FSC Żuk owner's manual 1985 (carburettor 34S2B1), pp.49–52. https://archive.org/download/fsc-lublin-instrukcja-obslugi-zuk/FSC_LUBLIN-1985-instrukcja_obslugi_Zuk.pdf |
| Z89 | FSC Żuk owner's manual 1989 (28/35 S2A). Same archive URL with `FSC_LUBLIN-1989-instrukcja_obslugi_Zuk.pdf` |
| Z94 | FSC Żuk owner's manual 1994 (28/35 S2B1). Same archive URL with `FSC_LUBLIN-1994-instrukcja_obslugi_Zuk.pdf` |
| N77 | Nysa 522 owner's manual 1977. https://archive.org/download/zsd-1977-instrukcja-obslugi-nysa-522/ZSD-1977-instrukcja_obslugi_Nysa_522.pdf |
| WZ | Wiejak & Zagaja, Żuk book 1992 edition (unofficial English translation). https://archive.org/download/zukowka-zuk-spare-parts-catalog/ZUK-BEN-angielski_djvu.txt |
| PD | polskiedostawczaki.pl S-21 adjustment article. https://polskiedostawczaki.pl/podstawowe-regulacje-silnikow-s-21-oraz-m-20/ |

For the 34S2B1, the values come from Z85 unless noted otherwise.

---

## 0. Checks before any carburettor adjustment

Z85 lists these as preconditions:
- Engine above 80 °C ("powinna wynosić powyżej 80°C").
- Ignition advance correct.
  - N77 gives 7° BTDC for 85-octane fuel, for both the Weber and the Jikov.
  - The engine itself is covered by the other agent.
- Compression pressures checked.
- Ignition system sound.
- Carburettor sealed (no air leaks).

Z85 also notes that the idle circuit is set at the factory and should only be readjusted for symptoms such as misfiring, unstable idle, stalling, or idle that is too high.

## 1. Float level (poziom paliwa / ustawienie pływaka), 34S2B1

Reference images:
- `images/a-34s2b1-float-level-and-exploded-zuk-manual-1985.jpg` (Rys. 4.10)
- `images/a-28-35-s2b1-float-level-zuk-manual-1994.jpg` (shows the same method, with the 28/35 S2B1 values)

Steps:
1. Remove the cover with the float attached.
2. Check that the float has **no dents and is not holed**, and that it swings freely on its spindle.
   - PD: "Przed regulacją pływaka należy sprawdzić, czy nie jest dziurawy". A holed float stays sunk and the carb floods.
3. Check that the **needle valve body is screwed tightly into its seat**, and that the **damper ball in the needle is not stuck**.
   - Z89/Z94: "czy kulka … amortyzatora drgań iglicy … nie jest zablokowana".
4. Hold the cover **vertical** so that the float hangs on the needle by its own weight. It must not push the ball into the needle.
   - Z89/Z94: "aby pływak swym ciężarem nie wcisnął kulki".
5. Measure from the **cover's sealing face to the float**:
   - **34S2B1: 5–5.5 mm** (Z85 table and drawing; PD).
   - Gasket: not stated in Z85. For the 28/35 S2B1, Z94 says **without gasket** ("bez uszczelki"). It is safest to measure without the gasket.
6. If needed, adjust by **bending the hinge arms (ramiona zawiasy)**. Keep the **tongue (języczek)** **perpendicular to the needle axis**.
   - Z89: "języczek zawiasy powinien pozostać w położeniu prostopadłym do osi iglicy".
7. Check the **float travel**: **8.5 mm** (Z85 table). Z85 Rys. 4.10 shows this as 13.5 mm from the cover face at full drop. Correct it by bending the **travel stop (występ zawiasy / ogranicznik skoku)**.
8. Refit the cover. Make sure the float moves freely without rubbing the chamber walls.
   - Z89 recommends repeating this check whenever the float or needle valve is replaced, and fitting a new cover gasket at the same time.

### Other variants, for comparison only

Do not use these on a 34S2B1:
- 28/35 S2B1:
  - Z94: 7 ±0.25 mm without gasket, maximum drop 13.5 ±0.5 mm.
  - WZ: 6.75–7.25 mm.
- 28/35 S2A1:
  - WZ text and PD: 6.25–6.75 mm.
  - The figure in the same book: 5–5.5 mm (conflict).
- The full conflict list is in specs-and-jets.md.

### Fuel-level gauge method (Z85), carb on the engine

The factory tool is **17-P-1107**:
1. Unscrew the protective cap from the gauge.
2. Unscrew the **main jet with its holder**. Screw the gauge body in its place **immediately**, to lose as little fuel as possible.
3. Fill the float chamber using the **hand lever on the fuel pump**.
4. Run the engine for **10–15 s**, then switch off.
5. Read the level. It must be **between the MIN and MAX marks**.

WZ (fig. 2.55) shows a similar graduated tube-type instrument for the 28/35 carbs, to be used after any repair.

A home equivalent is a clear tube connected in place of the main jet holder; forums call this the "wężyk" method. The exact MIN and MAX heights were not found.

## 2. Idle speed and mixture, 34S2B1

Reference image: `images/a-34s2b1-general-view-zuk-manual-1985.jpg`. Item 4 is the mixture screw (wkręt regulacyjny składu mieszanki) and item 5 is the throttle stop / idle speed screw (wkręt regulacyjny położenia przepustnicy).

The adjustment is done on the **primary only**: "regulacja tylko w kanale głównym I przelotu".

Z85 procedure:
1. With the engine off, turn **screw 5** in to open the throttle a little extra.
2. **Unscrew the mixture screw 4 by about 3 turns** ("wykręcić o 3 obroty wkręt składu mieszanki").
   - Z85 does not say whether this is counted from lightly seated. Normal practice is to seat it gently first, then back it out.
3. Start the engine. It should run at a medium speed.
4. With the engine running, **back off screw 5** until the speed drops to the slowest it will hold without stalling.
5. Turn **mixture screw 4** to get the **highest and smoothest speed**.
6. If the speed is now too high, repeat steps 4–5 until the idle settles at **600–800 rpm**.
   - The Nysa manual (N77) gives **550–650 rpm** for the Weber.

The PD article (enthusiast version, variant not named) gives the same procedure, but starts with the mixture screw **2 turns** out from fully in. It then adds a test:
- Snap the throttle open and let go. The engine should return to idle without stalling.
- If it stalls, raise the idle slightly with the throttle screw.
- It should not pop back into the carburettor or the exhaust.

### Later 28/35 carbs

- Z94 says the mixture screw is **sealed ("zaślepiony")**. Only the throttle stop screw is used for idle speed.
- Z89/Z94 give 600–800 rpm.

### CO

- **No factory CO value was found.**
- [FORUM] A Nysa owner (28/35 S2A1) reached idle CO 2.4 % with lambda 1.024 after fixing the needle valve and fitting a 110 primary main jet. This is an example result, not a spec. Source: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3998

## 3. Cold-start device (ssanie / urządzenie rozruchowe) cable

Source: WZ, 28/35. The 34S2B1 uses the same type of piston starter.

- The lever has three positions: **A** cold start (fully on), **B** warm start (partly on), **C** off. The lever travel is 68°.
- Adjust the cable length so that, with the carb lever **against its stop on the starter cover**, the cab knob still stops **2–3 mm short** of its housing. This guarantees the starter switches fully off.
- **If the starter does not fully switch off, or its piston sticks, the engine runs rich when hot.** This is listed in the Z85 fault table.

No "fast-idle gap" or choke-flap gap exists on this design, because there is no choke flap. None was found in any source.

## 4. Accelerator pump

- Factory data:
  - 28/35 types: stroke **10 mm**, output **0.5 cm³ per stroke** (Z89), or **5 cm³ per 10 strokes** (Z94); pump jet 40, valve 80.
  - 34S2B1: pump jet **70** (Z85). Stroke and output are not stated.
- No factory adjustment procedure for pump stroke was found in the owner's manuals.
- WZ says that after a repair, "individual devices" should be checked with special test equipment.
- **Simple check:** with the engine off and the float chamber full, look down the primary throat and open the throttle smartly. A crisp jet of fuel should come from the injector. If there is none, or only a dribble, suspect:
  - a blocked injector,
  - a missing or wrong ball valve,
  - a stuck piston.

  This check is common practice, not from a factory source.

## 5. Secondary throttle opening check

- Factory statement (Z85/Z89/Z94): the secondary must start opening at **2/3 of primary opening** and reach full opening together with the primary.
- WZ gives the total primary-lever rotation as **78°**.
- **Check:** open the primary slowly by hand. The secondary should stay closed until about 2/3 travel, then open fully by wide-open throttle. Both plates must close completely when released.
  - Z85 lists "Przepustnice nie domykają się" (throttles not closing) as a rough-idle cause.
  - The fix it gives is to check the throttle linkage and the spindles.
- **Pedal travel (WZ, Żuk):** 56 mm at the pedal end for full throttle. The intermediate spring must still have at least 3 mm of reserve.

## 6. Cleaning (factory guidance)

- **Interval:** first after **1000–1500 km**, then every **10 000 km** (Z94). WZ gives about 9000 km.
- **Z94 method:**
  - Unscrew the main jets, and the idle jet after unscrewing the solenoid valve.
  - Wash them in **unleaded petrol or kerosene (nafta)**.
  - Blow them through with **compressed air**.
  - Put them back **without swapping I and II** ("aby nie pomylić dysz głównych paliwa z I i II przelotu, które mają różne średnice").
- **WZ:** wash all parts in kerosene or clean petrol and blow through with air. **Jets must not be cleaned with steel objects** such as wire or drill bits, because this damages the calibrated bore.
- **Z85, if the main idle passages are blocked:** remove the jet and blow out both the jet and the channels with compressed air.

## 7. Ignition and air-filter items that affect carburettor setup

These belong to the engine domain and are listed here only for completeness.
- **Ignition advance:** 7° BTDC (N77).
- **Air-filter flap:** set to warm air in winter and cold air in summer (N77 il.24; Z94).
