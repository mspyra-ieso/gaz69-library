# How the 28/35 S2A1 / S2B1 works

The source keys are defined in specs-and-jets.md. The circuit descriptions come mainly from **WZ** (Wiejak & Zagaja, 1992). That book describes the **28/35 S2A1** in Figs 2.23–2.27. It is read through an unofficial machine translation, so the wording is paraphrased here. Factory owner's manuals (Z89, Z94) and the parts catalogue (CAT88, BI11) confirm the layout.

Drawings:
- `t-wz-fig2-23-28-35-s2a1-general-view.jpg`
- `t-wz-fig2-24-main-circuit-and-secondary-linkage.jpg`
- `t-wz-fig2-25-26-accelerator-pump-and-starter.jpg`
- `t-wz-fig2-27-idle-and-progression-circuit.jpg`

## 1. Layout

- **Type:** downdraught [opadowy], twin-throat [dwuprzelotowy].
- **Venturis:** each throat has a primary (auxiliary) venturi [gardziel wstępna] and a main venturi [gardziel główna]. Z89: "z gardzielami wstępną i główną, ze stopniowym otwieraniem II przepustnicy".
- **Bores and venturis:** 28 mm and 35 mm throttle bores; 21 mm and 26 mm venturis; 4.5 mm auxiliary venturis (CAT88).
- **Cover:** carries the mesh fuel filter under a plug, the 1.75 mm needle valve with a spring-ball damper, and the hinged float (Z89, Z94).
- **Body:** carries:
  - the jets;
  - the piston accelerator pump;
  - the side-mounted round **piston starter** [urządzenie rozruchowe];
  - the **EZ-20 solenoid** with the primary idle jet;
  - a port for the distributor vacuum advance [króciec przewodu podciśnieniowego regulatora aparatu zapłonowego] (Z94 item 11).

## 2. Mechanical progressive secondary (no vacuum diaphragm)

- **[FACTORY] Z89 and Z94:** the secondary throttle is opened **mechanically** through levers from the primary spindle. It "zaczyna się otwierać dopiero przy 2/3 pełnego otwarcia" of the primary (only starts to open at 2/3 of full primary opening).
- **Mechanism (WZ Fig. 2.24):**
  1. The stop lever [dźwignia ograniczająca] on the primary spindle has a hook.
  2. At first the hook moves freely in a notch of the **release lever** [dźwignia zwalniająca].
  3. Further rotation picks up the release lever.
  4. The release lever drives the lever on the secondary spindle until the secondary is fully open.
  5. Total primary-lever rotation is **78°**.
- **Parts:** release lever assembly 014137 and torsion springs 9911201 and 9914788 (CAT88). The same release lever is used on the S2B1 (BI11 item 13).
- **[FORUM] description (Marian, FPD t=4279):** both throttles are worked by one lever, the second opening later. The only other lever is the small choke-cable lever.
- **Consequence:** the secondary plays no part at idle or light throttle, except through air leaks past a worn secondary spindle.
  - Oversize spindles were catalogued for both throats: "oś przepustnicy nadwymiarowa" (CAT88 items 39 and 62).
  - That shows spindle wear was an expected repair.

## 3. Main circuit with air correction

Source: WZ Fig. 2.24.

1. Fuel goes from the float chamber through the **main jet** (110 for I; 145 for S2A1 II or 125 for S2B1 II), held in a screw-in holder [obsada dyszy].
2. It enters a well with the **emulsion tube** (F27 for I, F35 for II).
3. Air enters through the **air-correction jet** [dysza powietrza hamująca, "air that brakes fuel outflow"]: 250 for I; 225 for S2A1 II or 220 for S2B1 II.
4. The emulsion leaves through the **auxiliary venturi nozzle** [rozpylacz 4.5] into the venturis.

Z94 warns not to swap the main jets of throats I and II: "nie pomylić dysz głównych paliwa z I i II przelotu".

## 4. Idle and progression

Source: WZ Fig. 2.27.

**Primary idle:**
1. Fuel is taken from the **primary emulsion well**.
2. It passes the **idle fuel jet 45** at the tip of the EZ-20 solenoid.
3. It mixes with air from the **idle air jet 175**.
4. The emulsion passes the **mixture jet 170**.
5. It goes down a channel to an outlet below the throttle plate.
6. The adjusting screw sits in that outlet. WZ says the factory seals it with a cap after setting.

**Progression:**
- As the primary plate opens, **two 0.8 mm progression holes** are uncovered.

**Secondary progression:**
- When the secondary starts to open, fuel from the secondary well passes the **100 jet**, mixes with air from the **80 air jet**, and leaves through **three holes: 2 × 1.2 mm and 1 × 1.5 mm**.
- This prevents a lean stumble before the secondary main circuit picks up.

**Idle speed:** set on the primary only, with the throttle-position screw. WZ refers to "screw (19, Fig. 2.24) of the throttle (12)"; in Z89 it is screw 15; in Z94, screw 13.

**Screw names:** the names in the documents vary.

| Source | Idle screws |
|---|---|
| Z89 Rys. 4.9 | 14 "wkręt regulacyjny składu mieszanki wolnych obrotów" (mixture); 15 "wkręt regulacyjny położenia przepustnicy" (throttle stop) |
| Z94 Rys. 4.9 | 12 mixture screw "(zaślepiony)" (sealed); 13 throttle-position screw |
| CAT88 | part 033846 is "wkręt regulacyjny wolnych obrotów" (the screw in the idle outlet) |

## 5. Idle cut-off solenoid

- The EZ-20 closes the primary idle jet when the ignition is switched off, to stop run-on.
- See solenoid-ez20.md.

## 6. Accelerator pump

Source: WZ Fig. 2.25.

- **Type:** a spring-loaded piston pump [tłok pompy].
- **Filling:**
  1. Each time the throttle closes, the linkage lifts the piston through a guide rod [drążek prowadzący].
  2. This compresses the pump spring.
  3. Fuel is drawn from the float chamber through a suction ball valve [zawór kulkowy ssania].
- **Delivery:**
  1. On sudden opening, the control lever drops away from the guide rod.
  2. The **spring** pushes the fuel through the delivery ball valve [zawór kulkowy tłoczenia, 80].
  3. The fuel goes to the **injector 40** [wtryskiwacz / dysza pompy], which sprays into **throat I**.
- **Data:** stroke **10 mm**; output **5 cm³ per 10 strokes** (Z94, WZ).
- **Parts (CAT88):** piston 9911190; ball valve 9905100; valve "(80)" 008523; jet "(40)" 76408040.

## 7. Cold-start device (starter), not a choke flap

Source: WZ Fig. 2.26.

- **Type:** a piston valve [tłoczek urządzenia rozruchowego] in the round side housing. It is worked by a cable to lever 70.
- **Lever positions** (68° of travel):
  - **A:** fully on (cold start);
  - **B:** partly on (warm start);
  - **C:** off.
- **How it works:**
  1. Fuel goes from the float chamber through the **starter fuel jet F1/150**.
  2. Air comes through the **starter air jet 150**.
  3. They form an emulsion, which mixes with more air in the piston chamber.
  4. The mixture is drawn into the manifold through its own channel below the throttle plate.
- **After the engine fires:** manifold vacuum opens a small **air valve** through a vacuum channel. Extra air enters through the cup and leans the starter mixture to avoid flooding.
- **As the engine warms:** the piston progressively closes the outlet until it is fully closed at C.
- **Calibrations:** 5.75 mm starter air hole; weakening holes 1.75 / 1.75; reserve-well bush 250 (Z89, Z94).
- **Covers:** S28.02.00 (S2A1) and S2B.02.00 (S2B1).
- **Fault link (Z89, Z94 fault tables):** a starter left partly on because the piston sticks causes rich running and high consumption. The tables say "urządzenie rozruchowe pozostaje częściowo włączone".

## 8. Economiser on the secondary (S2B1 only)

- **[FACTORY] Z94:**
  - The S2B1 has a **gravity-type economiser on throat II** [układ oszczędzacza … typu grawitacyjnego].
  - It gives full power while keeping economical consumption.
  - It adds fuel once the **secondary main throttle passes half its opening**: "gdy wychylenie przepustnicy głównej II przelotu przekroczy połowę jej otwarcia".
- **Calibration:** economiser fuel jet **80**, nozzle **2.5** (Z94; WZ).
- **Why it exists:** it lets the secondary run a leaner main jet (125 instead of 145) and air jet (220) at part load, with the enrichment returning near full throttle. BI11 calls the S2B1 "oszczędny" (economical).
- **Physical layout:** not described in any source found.
  - The BI11 exploded drawing shows a different cover (437.28.010.02) and an extra blanking plug [zaślepka] 438.34.113.04 (item 59).
  - Where the economiser tube and jet sit has not been confirmed. **Gap.**

## 9. Float system

- **Needle valve:** 175 (1.75 mm seat). The **needle has a spring-ball damper** [amortyzator drgań iglicy / kulka] to resist vibration.
- **Float:** about 18 g, on a hinge with two adjustment points:
  - the **arms / tongue** [ramiona zawiasy, języczek] set the float distance;
  - the **stop tab** [występ zawiasy, ogranicznik skoku] sets the maximum drop.
- **Seat height:** sealing washers 0.5 / 0.7 / 1.0 mm under the needle-valve body (CAT88 item 10; BI11 item 69 "wg potrzeb") also change the seat height.
- Values and procedure: see adjustment-procedures.md and specs-and-jets.md.

## 10. Connections relevant to an engine swap (GAZ-69)

- **Mounting:** four M8 nuts. From the bottom up, the stack is: gasket 4127681, insulating spacer 4127682, gasket 4127681, carb (CAT88 table 11.10, `t-28-35-s2a1-intake-stack-gaskets-spacer-catalogue-1988.jpg`; WZ "two gaskets and one insulating spacer").
- **Air filter:** above the carb, with plate, gasket and spacer tubes. A **flame arrester** [wygaszacz płomienia] 4114060 sits in the rubber breather hose (CAT88 11.10 items 10–11).
- **Crankcase ventilation [FACTORY/BOOK]:**
  - WZ says the PCV piston valve in the inlet manifold is "controlled by a lever mounted on the throttle" spindle.
  - At idle, blow-by goes only to the air filter.
  - [FORUM] Marian, t=4279: an eccentric on the primary spindle "sterował trzpieniem w kolektorze" (worked a plunger in the manifold).
  - In a swap with a different manifold or a missing link, check that this port is not an open air leak.
- **Distributor vacuum-advance port** on the body (Z94 item 11).
- **Solenoid wire:** switched +12 V; see solenoid-ez20.md.
