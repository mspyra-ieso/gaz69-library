# Idle speed and idle mixture in depth

Tags are as in `tuning.md`: [FACTORY], [BOOK], [RELATED] (the 34 DCHD sister carb, [F125]), [FORUM], [GENERAL]. ⚠ marks a departure from factory data. The short procedure is in `adjustment-procedures.md` §2. This file adds the reasoning, the alternatives and the diagnostics.

## 1. The two screws

| Screw | Polish name | What it does | Direction |
|---|---|---|---|
| Throttle-stop (idle-speed) screw | wkręt regulacji położenia przepustnicy I przelotu (Z94 no. 13; Z89 no. 15; PD drawing no. 1) | Sets how far the **primary** plate stays open at idle | **In = faster idle**, out = slower ([Z94] §4.3.2) |
| Idle-mixture screw | wkręt regulacyjny składu mieszanki wolnych obrotów (Z94 no. 12, "zaślepiony"; Z89 no. 14; PD no. 2) | Tapered needle in the idle-mixture outlet below the plate. It meters **how much idle emulsion** reaches the engine | **In = less emulsion = leaner**, out = richer |

### Settling the direction question

The direction was left "unverified" in `adjustment-procedures.md`. Three sources now agree that screwing in leans the mixture:
- [RELATED] The FOS 34 DCHD book: screw 23 "regulates the quantity of mixture drawn in by the engine" ([F125] p.64). Less opening means less idle emulsion.
- [GENERAL] On Webers, "clockwise weakens the mixture at idle", because the screw's taper closes a drilling ([ALFA]).
- [FORUM] Strucelsw's diagnostic: with the screw **fully in, the engine must stall** after a moment ([FPD t=4814]).

The single contrary forum post (t=4635, in `adjustment-procedures.md`) is outweighed by these three.

**The secondary plays no part at idle.** It is locked shut by the release lever until about 2/3 primary opening ([Z94]). Idle speed is set on the primary only ([WZ] §2.1.5).

## 2. Preconditions

[FACTORY] Z94 says to adjust on a **hot, running engine**, and only if the engine misfires, stalls or idles too fast. First check ([Z94] §4.3.2):
- the **ignition timing**;
- the **ignition system**;
- the **air-tightness** of the fuel system.

In addition:
- Engine at about **80 °C** ([PD]). [RELATED] F125 also says 80 °C ([F125] p.69).
- Clean jets; **no throttle-spindle play**; the float level set ([PD]).
- Choke **fully off**, with 2–3 mm cable reserve (`cold-start-device.md`).
- The air filter fitted. [GENERAL] It changes the depression at the idle air jets.
- Timing set for your fuel first. On modern fuel, owners set it by ear, earlier than the marks ([FPD t=3998]; see `tuning.md` §6 ⚠).

## 3. Methods

### 3a. By ear (enthusiast and factory fallback) [SITE/RELATED]

This is the [PD] procedure, quoted by Marian in [FPD t=2222]:
1. Screw the mixture screw gently fully in, then out **2 turns**.
2. Set the lowest even speed with the throttle screw.
3. Turn the mixture screw for the **highest even speed**.
4. Lower the speed again with the throttle screw.
5. Repeat steps 3–4 until the setting no longer changes.
6. Test with a sharp blip: it must return to idle without stalling, and without popping back or in the exhaust.

[RELATED] F125 gives the same no-instrument fallback for the 34 DCHD ([F125] p.69):
1. Throttle screw to the lowest possible speed.
2. Mixture screw to the highest even speed.
3. Back the throttle screw off and repeat if needed.

**Starting turns.**
- [SITE] 2 turns out ([PD]).
- [FORUM] Strucelsw: "większość żuków optymalnie pracuje na składzie odkręconym o 0,5 do 1 i 1/4 obrotu", meaning most Żuks run best at **0.5–1.25 turns** out ([FPD t=4814]).
- [FORUM] One owner started from 1.5 turns ([FPD t=777 p8], O37).
- If you need **more than about 2 turns** to get an even idle, look for an air leak or a partly blocked 45 jet instead of opening the screw further. [GENERAL, inference from the 0.5–1.25 norm]

**Lean-drop refinement** [GENERAL]: from the best-speed position, screw **in** until the speed just starts to drop, then back **out** until it recovers ([ALFA]). This leaves the leanest setting that still gives full idle speed. It is the usual economy and emissions choice.

### 3b. With a CO analyser [RELATED]

The 34 DCHD factory method ([F125] p.69):
1. Engine at about 80 °C, probe in the tailpipe, tachometer connected.
2. Throttle screw to **850 ±50 rpm** (that is the 34 DCHD idle).
3. Mixture screw to **1.2–2 % CO (maximum 4.5 %)**.
4. If the speed changed, repeat steps 2–3.
5. Final check: about 850 rpm, and no stall on quick blips.

**For the S-21**, use the factory **600–800 rpm** ([Z94]). No 28/35 CO figure exists in Z89, Z94 or WZ. [FORUM] A good S2A1 reading was **CO 2.4 %, λ 1.024** at idle ([FPD t=3998]). [GENERAL] Classic Webers typically run 1.5–3 % CO and about 300 ppm HC ([ALFA]).

### 3c. With a vacuum gauge [GENERAL]

1. Tee the gauge into **manifold** vacuum (the brake-servo hose). **Not** into the carb's distributor-advance port: that port reads about 0 at idle ([FPD t=1007]).
2. Set idle speed as above.
3. Turn the mixture screw slowly to the **highest steady vacuum**. Then turn it in very slightly, just until the needle begins to drop.
4. Reset the speed with the throttle screw and repeat.

What the needle tells you:
- A steady needle means a healthy idle.
- A regular flick means a misfire or a valve fault.
- Slow wandering means mixture or an air leak.

This method is general workshop practice. No S-21 source gives a target vacuum value.

### 3d. With a wideband

Aim for about **λ 0.95–1.0 (AFR ~14–14.7)** at idle, whichever gives the smoothest running ([FT]; Strucelsw's 14.7 stoichiometric figure, [FPD t=3094]). Watch for exhaust leaks, which make the reading look lean (see `tuning.md` §8).

## 4. Emissions-test experience

- **Limits** [GENERAL] (Polish rules as tabulated in [IDZ2013]):
  - idle CO **4.5 %** for vehicles registered up to 30 Sept 1986;
  - **3.5 %** from 1 Oct 1986 to 30 June 1995.
  - Check the current regulation and how it treats historic or re-registered vehicles; a 1960s GAZ-69 body would normally fall in the oldest band.
- [FORUM] **UK MOT, Żuk A151B (hakin1):**
  - It failed on high CO and HC after a carb clean and idle "experiments".
  - Fixes: float set to **6.5 mm without gasket**, idle mixture re-set, new plugs, oil and coil.
  - It **passed the retest** ([FPD t=4329], O40 in `owner-reports.md`).
- ⚠ [FORUM] Strucelsw's trick for a high-CO test: raise idle to about **1000 rpm** ([FPD t=4329]). This is above the factory 600–800 rpm. Use it only to pass a test; restore the speed afterwards. First remove the real cause (flooding, a leaking idle jet).
- [FORUM] The 2018 Nysa owner chased λ at 2500 rpm because of the test ([FPD t=3998]). The idle screw **cannot** fix 2500 rpm readings: there the primary main circuit is working (Strucelsw, same thread).
- [FORUM] Crankcase gases: **"odma daje podwyższone hc"**, the breather raises HC (Strucelsw, [FPD t=3998]). A worn engine or a stuck PCV plunger shows up as HC, not CO.

## 5. Diagnostics hidden in the idle adjustment

| Observation | Meaning | Source |
|---|---|---|
| Engine keeps running with the mixture screw **fully in** | Fuel is bypassing the screw: **holed float or leaking needle valve** (flooding), a **crushed idle jet**, or **too thick an O-ring** under the solenoid or plug (the correct ring is 6×2 mm) | Strucelsw, [FPD t=4814]; [FPD t=4329] |
| Engine keeps running with the **EZ-20 unplugged** | Same bypass, or the **PCV plunger** in the manifold stuck open | [FPD t=777 p12] (O11) |
| Screw has **no effect at all** | As above; or the idle jet is blocked and the engine idles on the progression holes because the throttle screw is opened too far | [FPD t=4814]; [GENERAL] [ALFA] (progression holes) |
| Idle needs the throttle screw opened a lot to keep running | Lean idle or an air leak. ⚠ **Opening the plate too far uncovers the first 0.8 mm progression hole.** Idle then runs partly on the progression circuit and the mixture screw loses authority. Fix the cause | [GENERAL]; [RELATED] hole positions relative to the closed plate, [F125] Fig. 2.70 |
| Idle CO fine, but rich at 2500 rpm | Not an idle problem: primary main or air jet, or float level | [FPD t=3998] |
| Engine **stalls after a snap of the throttle** | Idle too low or too lean. Raise the throttle screw slightly ([PD]); check the pump | [PD] |
| Pops back through the carb at idle and tip-in | Lean, or timing too far advanced | [FPD t=2247]; [PD] |

## 6. Idle hunting (speed rises and falls)

Check in roughly this order:
1. **Air leaks** [FORUM/FACTORY]:
   - the base gaskets and the insulating spacer (cracked or warped; [D2-GAZ]);
   - the manifold gaskets;
   - the brake-servo hose (the 2018 Nysa readings improved after servo work; [FPD t=3998]);
   - throttle-spindle wear. Oversize spindles exist in the catalogue; see `how-it-works.md`.
   - [FACTORY] The Z89/Z94 fault tables list leaks at these joints as a cause of uneven idle.
2. **PCV plunger** [trzpień odmy] in the inlet manifold, driven from the primary spindle. It must move freely. If it sticks open "ciężko wolne ustawić" (idle is hard to set) ([FPD t=777 p12]; [FPD t=4162]).
3. **Throttle not returning to its stop:**
   - binding linkage or a weak return spring. On the GAZ-69 swap a sticking throttle needed an **extra return spring** ([D2-GAZ2]).
   - Plates not closing: "przepustnice nie domykają się" is a factory fault-table entry ([Z94] Table 4-2).
4. **Choke cable not fully off**, or the starter valve leaking (`cold-start-device.md`).
5. **Float level or needle** wrong: rich hunting with sooty plugs ([FPD t=4814]).
6. **Dirty 45 idle jet:** a lean hunt. It can re-block after a poor clean ([FPD t=3998]).
7. **EZ-20 supply:** a weak or intermittent +12 V lets the plunger chatter (`solenoid-ez20.md`).
8. **Ignition:**
   - [FORUM] Timing too far advanced makes the idle high and uneven.
   - Vacuum-advance hose wrongly routed: it must go to the carb's ported spigot, not to manifold vacuum. [GENERAL, inference from [FPD t=1007]]

## 7. The sealed S2B1 mixture screw

- [FACTORY] Z94 marks screw 12 as **"zaślepiony"** (blanked or sealed). It only describes idle-speed adjustment with screw 13 ([Z94] Rys. 4.9 and §4.3.2).
- [BOOK] WZ: the factory seals the screw with a cap after setting it ([WZ] §2.1.5, as summarised in `how-it-works.md` §4).
- [RELATED] F125 explains the purpose. The screw sits in a shroud that "makes unauthorised adjustment difficult" and allows a **plastic plug (plomba)** to be fitted after correct adjustment ([F125] p.64).
- **Practical consequence** [GENERAL, inference]:
  - The seal is a tamper-evident plug in the shroud, not a different screw.
  - On an S2B1 that idles badly after a clean, the plug can be picked or drilled out carefully (do not damage the screw tip). Then set the screw as in §3 and, if you like, fit a new plug.
  - No source describes the removal. **Gap.**
  - On the S2A/S2A1 the screw is normally open.

## Sources

[Z94]: https://archive.org/download/fsc-lublin-instrukcja-obslugi-zuk/FSC_LUBLIN-1994-instrukcja_obslugi_Zuk.pdf
[WZ]: https://archive.org/download/zukowka-zuk-spare-parts-catalog/ZUK-BEN-angielski.pdf
[F125]: https://archive.org/details/PolskiFiat125pBudowaEksploatacjaNaprawa1982
[PD]: https://polskiedostawczaki.pl/podstawowe-regulacje-silnikow-s-21-oraz-m-20/
[FPD t=4814]: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4814
[FPD t=3998]: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3998
[FPD t=2222]: https://forum.polskiedostawczaki.pl/viewtopic.php?t=2222
[FPD t=2247]: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=2247
[FPD t=1007]: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=1007
[FPD t=3094]: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3094
[FPD t=4329]: https://forum.polskiedostawczaki.pl/viewtopic.php?t=4329
[FPD t=4162]: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4162
[FPD t=777 p8]: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=105
[FPD t=777 p12]: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=165
[D2-GAZ]: https://www.drive2.ru/l/590869853259170000/
[D2-GAZ2]: https://www.drive2.ru/l/584099610411147866/
[ALFA]: https://alfaworkshop.co.uk/alfa_carburettors.shtml
[FT]: https://www.ford-trucks.com/forums/1331663-carb-tuning-w-afr-meter.html
[IDZ2013]: https://yadda.icm.edu.pl/baztech/element/bwmeta1.element.baztech-9ca8ccf1-cc2e-4241-bda6-d74a7da9b3ee/c/Idzior_Karpiuk_Czaplinski_Iwanicki_Wybrane_10_2013.pdf
