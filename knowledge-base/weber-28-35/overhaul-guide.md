# Weber 28/35 (S2A / S2A1 / S2B1): full overhaul guide

This guide covers a bench overhaul [remont / regeneracja gaźnika]: strip-down, cleaning, inspection and reassembly. Adjustment values (float level, idle, pump, starter cable) are in `adjustment-procedures.md` and `specs-and-jets.md`, and are only referred to here. The after-cleaning checklist is in `after-cleaning-checklist.md`.

**Labels:**
- **[FACTORY]**: Żuk manuals and parts catalogue.
- **[BOOK]**: Wiejak & Zagaja (WZ).
- **[FORUM]**: owner forums.
- **[SHOP]**: sellers.
- **[GENERAL]**: general carburettor practice, not specific to this carb.

**Source keys**, defined fully in `sources-broad.md`:
- **CAT88:** 1988 Żuk parts catalogue, table 11.07. https://archive.org/download/zukowka-zuk-spare-parts-catalog/FSC_LUBLIN-1988-katalog_czesci_zamiennych_samochodu_Zuk.pdf
- **WZ:** Wiejak & Zagaja, *Żuk – budowa, eksploatacja, naprawa*, Figs 2.49–2.50 and 2.55, in the English machine translation. https://archive.org/download/zukowka-zuk-spare-parts-catalog/ZUK-BEN-angielski.pdf
- **Z94:** 1994 Żuk owner's manual. https://archive.org/download/fsc-lublin-instrukcja-obslugi-zuk/FSC_LUBLIN-1994-instrukcja_obslugi_Zuk.pdf

> **No factory workshop manual with a full 28/35 strip procedure was found.** The factory only describes a "permissible dismantling" [dopuszczalny demontaż] (WZ Fig. 2.50). Beyond that, the factory route was a **repair kit plus a test bench**. WZ says that after repair the fuel level must be checked with a gauge (Fig. 2.55), and each device checked "with special control and measurement equipment". So the deeper steps below combine the CAT88 parts breakdown, owner practice and general Weber practice, and each step is labelled with its source.

---

## 0. Decide first: clean, rebuild or exchange?

| Situation | Sensible route | Source |
|---|---|---|
| Ran well, now dirty or stored | **Permissible dismantling** and clean (section 2): cover, jets, solenoid, pump jet, filter. No spindles | [FACTORY/BOOK] WZ Fig. 2.50 |
| Hard to set idle; idle changes when you press on the throttle lever; whistle at the spindle | Check spindle play (`wear-and-inspection.md` §1). If it is worn, either fit **oversize spindles**, or exchange the carb | [FORUM] Strucelsw, FPD t=2916 |
| Cracked or warped body, stripped threads, corroded casting | Buy an exchange regenerated unit (800–950 zł at ETER-MOT / roda24, Oct 2026; see `rebuild-kits.md`) | [SHOP] |

[FORUM] Strucelsw (FPD t=2916, 2015) says re-bushing usually costs **more than a new or good carb**: "tulejowanie raczej drogo wyjdzie, wiecej niż nowy/dobry gaźnik". https://forum.polskiedostawczaki.pl/viewtopic.php?f=16&t=2916&p=38834

---

## 1. Before you start

- **Photograph everything** before removing it, especially:
  - the linkage between the primary and secondary spindles [mechaniczne otwieranie II przelotu];
  - the cold-start cable clamp;
  - the cam on the primary spindle that drives the crankcase-breather plunger in the manifold (§6).

  [FORUM] One owner "wykręcałem i robiłem fotki co do czego" (unscrewed and photographed what goes where) before cleaning (kubamytab, FPD t=2916). https://forum.polskiedostawczaki.pl/viewtopic.php?f=16&t=2916&p=38834
- **Have the gaskets ready.** As a minimum:
  - cover gasket 9914774;
  - needle-valve washers 014129/014130/014131 (0.5 / 0.7 / 1.0 mm);
  - jet-holder washers 9905071 and 9907256;
  - pump-valve washers 9904983;
  - solenoid ring 033844.

  These are the contents of the factory **small kit CZ-37.09** (CAT88 item 70). See `rebuild-kits.md` for current kits.
- **Have the reference numbers on paper:** 110/145 (S2B1: 125), 250/225 (S2B1: 220), F27/F35, 45/100, pump 40/80, starter F1/150 and 150 (`specs-and-jets.md`).
- **Use a jet tray with labelled cells, one per throat.** Throat I (28 mm) and throat II (35 mm) jets look alike.

---

## 2. Factory "permissible dismantling" (WZ Fig. 2.50)

[BOOK/FACTORY] WZ Fig. 2.50, "Gaźnik 28/35 S2A1 – dopuszczalny demontaż", lists exactly these removals:

| Order | Remove | Fig. 2.50 item | Notes |
|---|---|---|---|
| 1 | Fuel-filter plug and mesh filter [korek, filtr paliwa] | 8, 7 | Top of the S2A1 cover. The S2B1 has a horizontal inlet with an in-line filter: see `variants.md` |
| 2 | Cover [pokrywa gaźnika] with float, plus its gasket | 9, 6, 10 | Lift it **straight up**. The float hangs underneath and the emulsion-tube wells sit in the body |
| 3 | Main-jet holders and main jets, I and II [obsady dysz głównych, dysze główne] | 1, 14 / 2, 15 | They screw in from the **outside** of the body. Keep the I and II jets apart |
| 4 | Idle-jet holder II and idle jet II (100) | 3, 13 | Secondary progression feed |
| 5 | **Solenoid** [zawór elektromagnetyczny] with idle jet I (45) on its tip | 11, 5 | The 45 jet **is** the tip. Unscrew it by its hex only, never by the body or the wire. See `solenoid-ez20.md` |
| 6 | Accelerator-pump jet with ball valve [wtryskiwacz pompy z zaworem kulkowym] | 16 | Don't lose the ball |
| — | Sealing rings [pierścienie uszczelniające] | 4, 12 | Renew them |

**Cleaning rule [BOOK]:** "Wash all carburetor and dismantled parts with kerosene or clean gasoline and blow off with compressed air". Jets must not be cleaned with steel objects ("may not be swallowed with steel objects", which is the machine translation of "przetykać", to poke through) (WZ, carburettor-maintenance section).

**Interval [BOOK]:** float level and cleaning "after 9000 km or if necessary" (WZ).

---

## 3. Full strip-down (beyond the factory list)

The order follows the CAT88 exploded view (`images/t-28-35-s2a1-exploded-parts-catalogue-1988-p1.jpg`, `-p2.jpg`). Part numbers are from CAT88.

### 3a. Cover [pokrywa] (CAT88 items 1–18)

1. **Float pivot pin [kołek 9904802] and float [pływak 9911187].**
   - Push the pin out towards the **split side** with a pin punch while supporting the hinge posts. The posts are cast and break easily [GENERAL].
2. **Needle valve [zawór paliwa kpl. 9911186] and its washer.**
   - **Note the washer thickness (0.5, 0.7 or 1.0 mm)**, because the washer sets the base fuel level (CAT88 item 10).
3. **Starter air jet (150) and starter fuel jet (F1/150)** (items 17–18) are in the cover's starter circuit. Unscrew and clean them.
4. **Small piston and spring in the cover [tłoczek 9909233, sprężyna 9909234]** (items 4–5). Remove them only if they are sticky.
   - The same 9909233 is sold by roda24 as the "zaworek podciśnieniowy" (vacuum valve) of the Fiat 125p choke-cover kit; see `interchangeability.md`.
5. **Fuel-inlet filter** (items 6–8).

### 3b. Body: jets and wells

6. **Air-correction jets [dysze powietrza hamujące] (250 / 225) and emulsion tubes [rurki emulsyjne] (F27 / F35).**
   - These come out from the top of the body.
   - [FORUM] Strucelsw's tip: leave each air jet screwed into its tube, so the pairs can't be mixed up. **F35 (throat II) is the tube with six tiers of holes, 24 holes in all**: "rurka emulsyjna f 35 do drugiego przelotu to ta która ma 6 pieter otworków. razem 24 otwory" (FPD t=2916). https://forum.polskiedostawczaki.pl/viewtopic.php?f=16&t=2916&p=38834
7. **Pump piston [tłok pompki kpl. 9911190]** and its return spring, retainer, washer and nut (items 19, 21–23).
   - **The 28/35 has a piston pump, not a diaphragm.** CAT88 lists no diaphragm anywhere in table 11.07. Kit photos showing diaphragms are generic; see `wear-and-inspection.md` §4.
8. **Pump inlet valve (80) [zawór kpl. (80)]** (item 20) at the bottom of the pump well.
9. **Starter (cold-start) valve [zawór rozruchowy 9910631]**, spring and spring cup (items 48–50), and the starter cover S28.02.00 (or S2B.02.00 on the S2B1).
   - Remove them only for cleaning; see `how-it-works.md` §7.
10. **Venturis [gardziele] (21 / 26) and auxiliary venturis [rozpylacze 4.5].**
    - They are held by a screw (M5×8, item 61).
    - [GENERAL] Remove them only if the bores are badly fouled. Mark which side faces up and which throat each came from, because the 21 and 26 must not be swapped.
11. **Idle mixture screw [wkręt regulacyjny 033846] and idle-speed screw.**
    - **Before removing the mixture screw, count the turns to seat it lightly**, and write the number down.
    - On the S2B1 the screw is sealed (Z94).

### 3c. Throttle section: only if you are renewing the spindles

12. **Throttle plates [przepustnice] 28 mm (I) and 35 mm (II), held by 4 screws (9904610).**
    - [GENERAL, Moss Motoring, SU carbs] Mark which way each plate faces and which side is up before removing it. Plate screws are often peened or split-ended and must be eased out. https://mossmotoring.com/rebushing-su-carburetor-bodies/
13. **Spindles [osie przepustnic]: I (4323406602) and II (033851)**, with levers, torsion springs, bush 9914781 and stop lever (items 37–47, 62, 64, 66).
    - Withdraw them only after removing the plates.
    - [FORUM] Owners do this only when fitting new or oversize spindles (`wear-and-inspection.md` §1).

### What NOT to remove or disturb

| Leave alone | Why | Source |
|---|---|---|
| **Pressed-in brass plugs, calibrated drillings and air bleeds in the body** (idle air 175, mixture 170, progression holes 0.8 / 1.2 / 1.5 mm, starter holes 1.75 and 5.75) | They are not parts: CAT88 does not list them. They are calibrated body drillings (WZ Table 2.18). Drilling or broaching them changes the calibration permanently | [FACTORY/BOOK] CAT88, WZ |
| **Any jet, with wire or a drill** | Factory ban on steel objects in jets | [BOOK] WZ |
| **Spindles and plates**, unless you are replacing them | Re-centring plates and staking screws is fiddly. A badly centred plate leaks at idle | [GENERAL] |
| **Solenoid needle and tip** | Snapping the tip loses the 45 jet (case O1 in `owner-reports.md`) | [FORUM] FPD t=4635 |
| **Secondary-throttle stop screw** | Factory secondary setting. See `adjustment-procedures.md` §5 | [FACTORY] |
| **Throttle-plate stop on the S2B1 and sealed mixture screw** | Factory seals | [FACTORY] Z94 |

[FORUM] For the Jikov SEDR, Strucelsw warns never to touch the throttle-opening screw, because it then "bedzie nie do ustawienia" (it can't be set again) (FPD t=5069). That carb is different, but the same caution applies to any factory stop screw on the Weber. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=5069

---

## 4. Cleaning methods

| Method | Who recommends it | Notes |
|---|---|---|
| **Kerosene [nafta] or clean petrol, then compressed air** | [BOOK] WZ (factory-era method) | The baseline. Blow every passage both ways |
| **Kerosene, nitro thinner [rozpuszczalnik nitro], a brush and compressed air.** Then run a fuel-system cleaner additive through the engine (e.g. "Doben organiki", "STP gas treatment") to clean jets and channels in use | [FORUM] Strucelsw, FPD t=3841 (2017): "nafta, nitro pędzel i sprężone powietrze" | Keep nitro thinner **away from the float, the solenoid's internal seals, plastic and rubber**. Nitro attacks many polymers [GENERAL] |
| **Ultrasonic bath** [myjka ultradźwiękowa] | [FORUM] Strucelsw: "jak ktoś jest pedantem to myjka ultradźwiękowa" (for the pedantic) (t=3841). Owners on FPD report using it (matjas, t=5245; hckosmo2, 2019) | See the cautions below |
| **Two rounds of soaking and heating** | [FORUM] juR, FPD t=4635: after a first clean the carb still would not run. A second, deeper clean flushed out "mnóstwo syfu" (lots of muck) | Debris loosened by the first clean often moves deeper. Always blow out **every** passage afterwards |
| **Pressure washer / dishwasher on the outside** | [FORUM] Wydra, t=3841 (half-joking about the dishwasher) | Outside only, and nothing inside afterwards [GENERAL] |

https://forum.polskiedostawczaki.pl/viewtopic.php?f=8&t=3841

### Ultrasonic cleaning: what damages it

These points are [GENERAL] and come from non-Weber sources; no source specific to the 28/35 was found.

- **Body material is not documented.** No factory or forum source found says whether the 28/35 body and cover are aluminium alloy or zinc die-cast (Zamak).
  - Zinc alloys are the more sensitive. Treat the carb as possibly zinc until you know otherwise.
- **Corroded zinc can be weakened.** If the casting already has white corrosion, ultrasonic cleaning can remove the corrosion from inside and weaken the part. Use a mild detergent and a short time in the bath (hobby-machinist.com, "Ultra sonic cleaning of zamak"). https://hobby-machinist.com/threads/ultra-sonic-cleaning-of-zamak.114761
- **Avoid glycol-ether cleaners** ("Simple Green" types): they attack aluminium and yellow metals. Plain dish soap is the safe choice (same thread).
- **Flash corrosion afterwards.** Aggressive cycles can expose porous or damaged zinc, which then corrodes quickly once dry (kzrider.com forum). https://kzrider.com/forum/3-carburetor/621733-what-size-brand-model-ultrasonic-for-entire-bank-of-4-carbs?start=12
- **Practical rules [GENERAL]:**
  - keep the bath warm, not hot;
  - use short cycles (a few minutes) and inspect between them;
  - rinse in clean water, then **dry immediately** with compressed air and a little warm air;
  - put a light film of petrol or WD-40 on the spindles.
- **Never put these in the bath:**
  - **the EZ-20 solenoid** (it has a coil, an internal needle and seals);
  - the **float** (brass floats have soldered seams; plastic ones can absorb fluid);
  - gaskets and rubber parts.

  This is inference plus general practice. For the solenoid, clean only the jet and the needle tip by hand with solvent and air.

---

## 5. Inspection during the strip

Limits and decisions are in `wear-and-inspection.md`. In brief:

1. **Spindle play:** rock each spindle across its bore with the plates fitted.
2. **Flatness:** check the cover face and the base flange with a straightedge on glass.
3. **Float:** weigh it (18 ±0.5 g; Z94, WZ) and shake it to hear whether fuel has got in. Check the hinge-tongue wear.
4. **Needle valve:** check the sealing seat and the damper ball.
5. **Jets:** read the stamped sizes against `specs-and-jets.md`. Check the bores by eye, not with a drill.
6. **Pump:** the piston should slide freely in its well; the inlet ball (80) should rattle; the pump-jet ball should seal.
7. **Starter piston:** it should slide freely; check its seat.
8. **Solenoid:** bench click test with 12 V (`solenoid-ez20.md`).

---

## 6. Reassembly order and gasket notes

1. **Throttle section (if it was dismantled).**
   - Fit the spindles with the springs and levers in the photographed positions.
   - Fit the plates closed and centred, then tighten and stake or lock the plate screws [GENERAL].
   - Check that the primary-to-secondary linkage opens throat II only late in the primary's travel (factory: from about 2/3; `how-it-works.md` §2).
2. **Mixture screw:** back to the counted turns (only on carbs where it is not sealed).
3. **Venturis and auxiliary venturis**, the right way up, in the right throat.
4. **Emulsion tubes + air-correction jets:** F27 + 250 in throat I, F35 + 225 in throat II (S2B1: 220).
5. **Main jets in their holders**, with **new washers** (9905071): 110 in throat I, 145 in throat II (S2B1: 125). The holders screw into the body from outside.
6. **Idle jet II (100)** in its holder with washer 9907256.
7. **Pump:**
   - inlet valve 80 with new washers;
   - piston and spring;
   - pump jet 40 with its ball valve and washers (9904983 ×2).
8. **Starter valve**, spring and cover.
9. **Solenoid with jet 45** and a **new sealing ring 033844**.
   - A leaking ring lets fuel bypass the cut-off (inference, `solenoid-ez20.md`).
   - Snug it only: it is an M8×1 thread in a soft casting ([FORUM] juR measurement, FPD t=4635).
10. **Cover:**
    - needle valve with the **same thickness of washer** as before (unless you are correcting the level);
    - float and pin;
    - **set the float level** to 6.25–6.75 mm without gasket (S2A1) or 7 ±0.25 mm (S2B1), drop 13.5 mm (`adjustment-procedures.md` §1);
    - new **cover gasket**;
    - **tighten the cover screws evenly in a cross pattern.**
11. **Prime and test before fitting:**
    - [BOOK] WZ asks for a float-level check with the gauge after repair (Fig. 2.55).
    - On the bench, work the throttle and look into the throat for the pump jet.

### Torque and fasteners

- **No factory torque figures were found** for the 28/35 cover screws, jet holders or manifold nuts (Z89, Z94, WZ and CAT88 were checked; CAT88 gives only part numbers).
- **[GENERAL]** Brass jets and holders: firm with a correctly fitting screwdriver, no more. They seat on fibre or copper washers.
- **[GENERAL]** Cover screws: snug, in a cross pattern. Overtightening bows the cover.
  - On the Fiat Weber IMB, owners trace warping to cover screws pulling the thin casting (fiatforum, Weber 26/28 IMB thread). https://www.fiatforum.com/threads/weber-26-28-imb.355169/page-3
- **Manifold nuts (4 × nut 12574111 on spacers 4079280, CAT88 table 11.10):**
  - tighten evenly and moderately;
  - re-check them when hot after the first run.
  - [FORUM, GAZ-69 S-21, Kyiv] An owner traced detonation and a lean mixture at about 40 km/h to a **textolite carb spacer cracked in two places, apparently from overtightening**. The spacer was visibly bent: "текстолитовую проставку, которая треснула в 2х местах. Очевидно, перетянул." https://www.drive2.ru/l/590869853259170000/

### The mounting stack under the carb

- **[FACTORY] CAT88 table 11.10:** two gaskets (4127681) with an insulating spacer [przekładka 4127682] between them.
- **[FORUM] FPD admin Marian:** a bakelite insulating spacer between the carb and the manifold "musi być" (must be there), even if you choose a thinner one (FPD t=3357, 2016).
- **[FORUM] zbyszek99** measured his stack: 2 × 0.55 mm textolite + 1.5 mm aluminium heat plate + 2 × 0.55 mm, **3.7 mm in all** (t=3357).
- **Do not build the stack too thick.** On the S-21 a **cam on the primary throttle spindle** pushes a crankcase-breather plunger in the manifold (Marian, FPD t=4279).
  - zbyszek99 found that with a **5 mm plastic spacer** the plunger no longer opened at full throttle, on both his Nysa and his rebuilt engine (t=3357, photos `images/w-fmpd-s21-spindle-cam-pcv-plunger-egr1.jpg`, `-egr3.jpg`).
  - If you add a heat plate, check that the cam still moves the plunger.

Sources: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3357&start=15 and https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4279

---

## 7. After the overhaul

- Follow `adjustment-procedures.md`: float, idle, starter cable, secondary.
- Then `after-cleaning-checklist.md` if it doesn't start.
- [FORUM] A run-in tip on a rebuilt S-21: the owner planned a fixed 40 litres of petrol before final tuning (zbyszek99, t=3357). This is the owner's own practice, not a requirement.
- **Re-check after 500–1000 km** [GENERAL]:
  - manifold nuts;
  - idle;
  - the fuel-inlet filter.

  Disturbed muck from the tank and lines collects there. See `ownership-experience.md` for fuel filtering.
