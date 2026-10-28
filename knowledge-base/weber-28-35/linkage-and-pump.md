# Accelerator pump, secondary throttle and linkage

Tags are as in `tuning.md`. ⚠ marks a departure from factory data.

## 1. Accelerator pump [pompka przyspieszająca]

### How it delivers

- [BOOK] The pump is a **spring-loaded piston**, not a diaphragm ([WZ] Fig. 2.25; `images/t-wz-fig2-25-26-accelerator-pump-and-starter.jpg`).
  - Closing the throttle lifts the piston through a guide rod, compresses the spring and draws fuel in through the suction ball valve.
  - On a quick opening, the lever drops away and the **spring** pushes fuel through the delivery valve (80) to the **jet 40**, which sprays into throat I.
- [RELATED] The 34 DCHD is identical in principle. Lever 61 is turned by a **cam 65** on the primary spindle ([F125] p.65–66, Fig. 2.68; `images/u-related-34dchd-pump-checks-fig2-67-68-fiat125p-book.jpg`).
- **Consequences:**
  - The **squirt strength is set by the spring and the jet**, not by how hard you press the pedal.
  - A slow pedal lets the piston follow gently, so the shot is spread out.
  - Full output needs the throttle opened fast enough for the piston to make **full strokes** ([F125] p.66).

### Factory data and output check

- [FACTORY] Pump jet **40**, valve **80**, stroke **10 mm**, output **5 cm³ per 10 strokes** ([Z94] Table 4-3; [WZ] Table 2.18).
- [RELATED] Factory output test for the 34 DCHD ([F125] p.66):
  1. Keep the float chamber topped up by the fuel pump.
  2. Make **5 full throttle-lever strokes** at a speed that gives full piston strokes.
  3. Collect at least **6 cm³**. That carb has a 0.70 mm jet and the same 10 mm stroke ([F125] Table 2-27).
  4. **Less** output means **leaking pump valves** (the suction or delivery ball) or a **sticking** pump. Clean the valves and remove the cause of sticking.
- **For the 28/35**, apply the same method against the factory figure:
  - Collect over 10 full strokes into a measuring cylinder: expect about **5 cm³**.
  - A visual check on the car: engine off, look down throat I, snap the throttle. A firm, straight jet should hit the venturi area, **not the wall**, and stop sharply.

### Adjustment

- **No stroke-adjustment point is described** in any factory or book source for the 28/35 (Z89, Z94, WZ, CAT88). The 10 mm stroke is fixed by the cam and lever geometry.
- The only tuning variable is the **pump jet**. [GENERAL] A bigger jet gives a shorter, stronger squirt; a smaller jet a longer, weaker one ([ALFA] describes the pump's role in curing the flat spot).
- Change it only if a clean, correctly set carb still stumbles **only on sudden opening**.
- **No source documents an alternative pump-jet size for the 28/35.** **Gap.**

### Pump faults

| Symptom | Cause | Source |
|---|---|---|
| Fuel **drips from the pump nozzle** at idle or just after switching off | The **ball under the pump delivery tube is missing**: "jak kapie z niej paliwo … to nie ma kulki" | Strucelsw, [FPD t=3139] |
| Rich idle, a trickle into throat I | Fuel **siphoning through the pump jet** ("podsysanie paliwa przez dyszę pompki") | Strucelsw, [FPD t=3998] |
| Missing part next to the float chamber | Pump nozzle "fi80 z kulką" (the 80 delivery valve with its ball) missing | [FPD t=5488] (O21) |
| Poor acceleration | Blocked pump channel or jet: blow through | [FACTORY] fault tables ([Z89]; [Z94]) |

## 2. Secondary throttle: opening point and full opening

### Factory design

- [FACTORY] The secondary is **mechanically** linked. It starts opening only at **2/3 of full primary opening** ([Z89]; [Z94]).
- [BOOK] It works through a hooked limiting lever and a **release lever** [dźwignia zwalniająca]. Total primary-lever rotation is **78°** ([WZ] Fig. 2.24; `images/t-wz-fig2-24-main-circuit-and-secondary-linkage.jpg`).
- [RELATED] The 34 DCHD uses the **same release-lever lock**. There the secondary is released only after the primary passes **48°30'**, and is then opened by a **vacuum diaphragm** ([F125] p.65). On the 28/35 the release lever **drives** the secondary mechanically instead. So 34 DCHD vacuum-diaphragm data (table 2-28, 1.5 mm rod setting) does **not** apply.

### Checks

[RELATED] These are the 34 DCHD factory checks, adapted ([F125] p.66–67, Fig. 2.69; `images/u-related-34dchd-throttle-opening-progression-holes-fig2-69-70-fiat125p-book.jpg`):

1. **Full opening.** Hold the throttle lever fully open, with the limiting-lever arm against its stop. **Both plates must be fully open.**
   - The book corrects the primary by **bending the limiting-lever arm** and the secondary by **slightly twisting the release lever**. It gives positions as dimensions on the drawing; those dimensions are for the 34 DCHD only.
   - For the 28/35, check that both plates stand parallel to the bore axis.
2. **Release point.** Open the primary slowly until the limiting-lever arm just touches the wall of the release-lever notch (no force).
   - The primary should then be at its specified angle. On the 34 DCHD it is checked as a dimension on Fig. 2.69b; it is corrected by **bending the arm (2)**.
   - For the 28/35, the factory statement is **about 2/3 of primary travel** ([Z94]).
3. **Secondary closed gap.** With the secondary closed, a **0.05 mm feeler** (13 mm wide) should slide in **with resistance** between the plate and the bore.
   - Set it with the **closing stop**. The gap stops the plate jamming and fuel pooling above it ([F125] p.67).
   - [GENERAL, inference] The 28/35 secondary has a similar stop. Do not close it fully tight, and do not open it so far that air bypasses at idle.
4. **Both plates close fully** when released. "Przepustnice nie domykają się" (throttles not closing) is a factory rough-idle cause ([Z94] Table 4-2).

**Throttle plates and spindles** [RELATED] ([F125] p.67):
- **Never swap plates between carbs**, and never refit the primary plate **rotated 180°**. The closed plates were the reference for drilling the progression holes.
- Factory spindle clearance (34 DCHD): **primary 0.045–0.089 mm, secondary 0.125–0.169 mm**.
- [FACTORY] Oversize spindles exist for the 28/35 (CAT88, see `how-it-works.md` §2).

### Owner experience [FORUM]

- With the pedal floored, the primary opened fully but **the secondary only slightly**. Marian: on the Żuk this is pedal adjustment, since the secondary opens fully only with the pedal "w samej podłodze" (right on the floor). Strucelsw: adjust the rods so that **both open fully when floored** ([FPD t=4581]).
- A Żuk that would not exceed 60 km/h: "check the second throttle opens fully" (Marian, [FPD t=3347]).
- **The PCV plunger in the manifold**, worked by the carb linkage, **seized and blocked the secondary from opening** ([FPD t=4162]).
- **Worn rod linkage** opened the primary only 3/4 and the secondary barely. The fix: convert to a cable with a Polonez quadrant ([ZL-LINK], O28).

## 3. Throttle plate position vs progression holes

- **28/35 holes** [BOOK]: primary **2 × 0.8 mm**; secondary **2 × 1.2 mm + 1 × 1.5 mm** ([WZ] Table 2.18; Fig. 2.27, `images/t-wz-fig2-27-idle-and-progression-circuit.jpg`).
  - [RELATED] These are **exactly the same sizes** as the 34 DCHD ([F125] Table 2-27). The closed-plate geometry is presumably related.
- [RELATED] F125 Fig. 2.70 shows how the factory checked the holes against the **closed plate's upper edge**: remove the blanking plugs above the holes and look ([F125] p.67).
  - If they do not match, the factory **replaced the carburettor**. Hole position cannot be corrected.
  - Whether the 28/35 has removable plugs over its progression holes is **not documented**. **Gap.**
- **Why it matters for tuning** [GENERAL] ([ALFA] on progression holes):
  1. At idle the plate must sit **just below** the first hole, so that hole is in the low-vacuum area above the plate.
  2. As the plate opens it uncovers the holes one by one, and emulsion flows from each. That bridges the gap until the main circuit starts.
  3. **If the idle-speed screw is opened too far** (for example to hide a lean idle or an air leak), the first hole is already uncovered at idle:
     - the mixture screw loses authority;
     - **tip-in goes flat**, because the progression reserve has been used up.
  4. If the plate was refitted off-centre or rotated, the idle and transition can never be set right.
- Rule of thumb: with a healthy engine, the factory **600–800 rpm** should come with the throttle screw only slightly open, about **½–1½ turns** past first contact. [GENERAL, unsourced; check on your carb]

## 4. Throttle stop and pedal linkage

### Factory Żuk linkage

[BOOK] [WZ] §2.1.5, Fig. 2.28; image `images/u-wz-fig2-28-zuk-throttle-and-starter-cable-linkage.jpg`. The chain runs:
1. The **pedal (1)**, pivoted on a bracket on the left footrest.
2. A **longitudinal rod (2)**.
3. An **intermediate shaft (4)** in two plastic bearings on the floor support.
4. A **vertical rod (5)**.
5. An **intermediate lever (6)**, bolted to an M8 hole on the front face of the inlet manifold. It has a **damping spring (10)**.
6. The **throttle rod (11)** to the carb lever.
7. A **pedal return spring (7)**.

**Factory setting:**
- **Pedal stroke 56 mm**, measured at the pedal end, for full throttle.
- Adjust it at the **rod ends (2 and 11)** so that, at full throttle, the **spring (10) is compressed by at least 3 mm**.
- The spring absorbs pedal over-travel instead of straining the carb's stops.

[FACTORY] Fault tables: **"niedostateczny skok pedału gazu"** (insufficient pedal travel) gives poor acceleration and top speed. Remedy: adjust ([Z89]; [Z94]).

### Throttle-stop screw

- [FACTORY] Screw 13 (Z94) or 15 (Z89): in raises idle, out lowers it ([Z94] §4.3.2).
- Set it **only** after the linkage is free, so that the **screw, not the linkage, holds the plate at idle**.
- With the engine off, pull the linkage slightly. There should be a little free play before the carb lever moves.

### Adapting a GAZ-69 pedal to the Weber

[GENERAL, inference, except where cited]. There is no published GAZ-69 + 28/35 linkage description. **Gap.** The S-21 in a GAZ-69 keeps the Żuk carb and manifold, but the pedal, floor and bulkhead are GAZ.

**Requirements:**
1. **Full travel:** pedal on the floor (or its stop) gives **full primary and therefore full secondary** opening (78° at the primary lever, [WZ]). Check by eye, with a helper pressing the pedal.
2. **Over-travel protection:** some compliance at the end of travel. That is the factory's ≥3 mm spring, or a pedal stop set just past full throttle, so the carb's stop does not take the driver's leg force.
3. **Positive return:** the carb lever's own spring **plus** an extra return spring on the linkage or pedal.
   - [FORUM] The GAZ-69 owner needed an **additional return spring** after a sticking throttle ([D2-GAZ2]).
   - [FORUM] Nysanek lists a weak or missing return spring as a cause of hanging revs ([FPD t=2062]).
4. **No side load on the spindle:** pull in the plane of the lever's rotation. A sideways-pulling cable wears the spindle bore, and that wear is an **air leak** at idle (see `idle-and-mixture.md` §6).
5. **Constant leverage:** with a cable, use a **quadrant/sector** so the pull stays tangential. Owners used a **Polonez pedal and quadrant**: "pedał gazu podwieszany z poloneza (bardzo wygodny, polecam)", a suspended Polonez pedal, very comfortable ([FPD t=471]; [ZL-LINK]).
   - A rod linkage like the GAZ original is fine if all its ball joints are tight. [FORUM] Lukpau found the pedal sticking because of play at a linkage joint near the carb ([FPD t=4084] snippet p=53031).
6. **Heat and earth:** keep the cable away from the exhaust manifold, and give the engine a **proper earth strap**. A Żuk's throttle rod and choke cable got hot while cranking until an extra earth lead was fitted ([FPD p=53003]).
7. **The PCV plunger link:** the Żuk manifold's crankcase-ventilation plunger is driven from the primary spindle. If the GAZ installation omits that link, blank the port or fit the plunger correctly. A seized plunger can also **block the throttle** ([FPD t=4162]).

**Check after any linkage work:**
1. Engine off: pedal floored gives both plates fully open; released gives the throttle screw back on its stop.
2. Pump squirt on a quick opening.
3. Starter lever on its off stop.
4. Hot idle re-set (`idle-and-mixture.md`).

## Sources

[Z89]: https://archive.org/download/fsc-lublin-instrukcja-obslugi-zuk/FSC_LUBLIN-1989-instrukcja_obslugi_Zuk.pdf
[Z94]: https://archive.org/download/fsc-lublin-instrukcja-obslugi-zuk/FSC_LUBLIN-1994-instrukcja_obslugi_Zuk.pdf
[WZ]: https://archive.org/download/zukowka-zuk-spare-parts-catalog/ZUK-BEN-angielski.pdf
[F125]: https://archive.org/details/PolskiFiat125pBudowaEksploatacjaNaprawa1982
[FPD t=3139]: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3139
[FPD t=3998]: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3998
[FPD t=5488]: https://forum.polskiedostawczaki.pl/viewtopic.php?f=15&t=5488
[FPD t=4581]: https://forum.polskiedostawczaki.pl/viewtopic.php?t=4581
[FPD t=3347]: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3347
[FPD t=4162]: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4162
[FPD t=2062]: https://forum.polskiedostawczaki.pl/viewtopic.php?p=25822#p25822
[FPD t=471]: https://forum.polskiedostawczaki.pl/viewtopic.php?p=31627#p31627
[FPD t=4084]: https://forum.polskiedostawczaki.pl/viewtopic.php?p=53031#p53031
[FPD p=53003]: https://forum.polskiedostawczaki.pl/viewtopic.php?p=53003#p53003
[ZL-LINK]: https://zlombol.pl/community/technikalia-2/zuk-s21-regenaeracja-ciegien-gazu-2/
[D2-GAZ2]: https://www.drive2.ru/l/584099610411147866/
[ALFA]: https://alfaworkshop.co.uk/alfa_carburettors.shtml
