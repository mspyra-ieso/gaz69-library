# Weber 28/35 (S2A / S2A1 / S2B1) on the S-21: real owner cases

Real troubleshooting cases from Polish owners (plus one Ukrainian GAZ-69 with an S-21 and a Polish Weber), sorted by symptom. Everything is paraphrased in English. Each case has a short original quote (Polish, or Russian for the GAZ-69 logbook).

**Where the cases come from**
- **Carried over (37):** cases from `../weber-34s2b1/forum-experiences.md` (F#) and `../weber-34s2b1/owner-reports.md` (R#). That earlier search targeted the 34S2B1, but nearly all its cases are about the 28/35 or name no variant. Left out because they are about another carburettor: F12 and F13 (Jikov thread), F15 (a seller's opinion, used as a tip in `troubleshooting.md`), R7 (Fiat 34 DCMP), R18 (Fiat-type 24/26 Weber) and R23 (Jikov).
- **New (14):** marked **NEW**. They come from FMPD threads not used before, S-21 engine-track threads re-read for carburettor content, and the GAZ-69 logbook on drive2.ru.

**Variant column.** Owners rarely name the carburettor. "not stated" means no variant was named but the vehicle is an S-21 Żuk, Nysa, Tarpan or Warszawa with a twin-choke Weber, so the case fits the 28/35. Żuks and Nysas built from the mid-1980s carry the 28/35 S2A/S2A1, and late ones the S2B1. Where the poster mentions the idle solenoid, the carburettor must be a 28/35, because the 34S2B1 has none.

**Status**
- **confirmed**: the owner says the fix worked on his vehicle.
- **partly confirmed**: things improved, but problems remained.
- **suggested**: advice from others, no outcome posted.
- **unresolved**: no cause found.

**Factory reference** (see `specs-and-jets.md`). S2A/S2A1 main jets are 110/145, air jets 250/225, tubes F27/F35, idle jet 45 on the solenoid and 100 on the secondary. Float 18 g, set 6.25–6.75 mm without gasket on the S2A1, or 7 ±0.25 mm on the S2B1. Idle 600–800 rpm. ⚠ marks advice that departs from this; the list is at the end.

FMPD = forum.polskiedostawczaki.pl. "t777 pN" = the thread *Układ zasilania – gaźnik, pompa paliwa*, page N.

---

## 1. Won't start

| # | Vehicle | Variant | Symptom | Cause | Fix | Status | Polish quote | Link |
|---|---|---|---|---|---|---|---|---|
| O1 (F2) | 28/35 S2A on another engine, 2019–20 | **28/35 S2A** | After the owner cleaned it, fuel poured from the jets on each throttle press and it would not start. While cleaning he had snapped the "tip" off the solenoid. | The tip was the **idle jet (45)**. Debris was also left in the internal channels. | A new jet on the solenoid, then a **second deep clean**: two rounds of soaking in cleaner and heating. A lot of dirt came out, and it started. | confirmed | "z kanałów wyleciało jeszcze mnóstwo syfu" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4635 , https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4635&start=15 |
| O2 (F3) | zolwik, same thread | 28/35 S2A (same thread) | Cleaned before Christmas, won't start since. | — | — | unresolved | "To jakaś epidemia na gaźniki" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4635 |
| O3 (R1) | Żuk S-21, 2014 (Złombol team) | not stated | Started at once before a tank repair and valve adjustment. Afterwards it would not fire and the plugs got wet. | **New ISKRA plugs** were faulty and died once flooded. Not the carburettor. | Fitted old Bosch plugs and it ran. | confirmed | "świece były marnej jakości (ISKRA mimo że nowe)" | https://zlombol.pl/community/technikalia-2/zuk-s21-nie-odpala-2/ |
| O4 (F10) | Nysa, 2013 | not stated | No start after an engine reseal. Wet plugs, bangs, a silencer blown apart. | **Ignition timing** lost when the fuel pump and its drive were refitted. | Reset the timing. | confirmed | "Kolejność zapłonu 1-2-4-3, sprawdź to najpierw" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=2247 |
| O5 **NEW** | Żuk S-21 with LPG (Miszczu) | not stated | Runs on LPG only. Switched to petrol it dies at once. It runs a few seconds if fuel is squirted into the carburettor. The pump delivers fuel. | A **corroded wire to the electric petrol cut-off valve** in the line between pump and carburettor. That valve belongs to the LPG kit; it is not the EZ-20 on the carburettor. | Wire repaired. | confirmed | "zaśniedział przewód dochodzący do elektrozaworu" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=1608 |

## 2. Starts, then dies

| # | Vehicle | Variant | Symptom | Cause | Fix | Status | Polish quote | Link |
|---|---|---|---|---|---|---|---|---|
| O6 (R3) | Żuk, 2012 (ekmir) | not stated | Bucked after 10 km. After a rest it started briefly, then died, and died on throttle. | **Blocked inlet strainer (sitko)** in the carburettor. A new coil and condenser and a cleaned pump had not helped. | Strainer cleaned. | confirmed | "Po wykręceniu sitka w gaźniku i przeczyszczeniu, silnik pracuje" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=105 |
| O7 (R4) | Żuk S-21 dropside, 2017 | not stated | Stalled at idle after the pump sucked sludge; hand-priming gave nothing. | Tank pickup blocked by a piece of filter; air leak in a corroded line. | New pump, filter before the pump, pickup cleared, line repaired. | confirmed | "smok był zapchany kawałkiem filtra" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=225 |
| O8 (F7) | Nysa, stored 8 years (ex-LPG), 2021 | not stated | Runs about 10 s, then dies. Keeps running if fuel is poured in. Float, needle and pump diaphragms already new. | Suggested: a **sticking mechanical pump** (Marian cured identical symptoms that way on a Żuk) or a **cracked carburettor body** (common on LPG S-21s). | — | suggested | "Pompa paliwa sie zawieszala" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=5136 |
| O9 (F14) | Żuk "Lodowy Żuczek", 2019 | not stated | Runs on choke when cold, then dies. | Suggested: flooding (choke not releasing, float too high), ignition, or the **elektrozawór**. | — | suggested | "ssanie nie odpuszcza do końca lub pływak za wysoko ustawiony" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=16&t=4392 |

## 3. No idle or hunting idle

| # | Vehicle | Variant | Symptom | Cause | Fix | Status | Polish quote | Link |
|---|---|---|---|---|---|---|---|---|
| O10 (R6) | Żuk S-21 1987 (Sebafso, 2016) and an S-21 (dedox, 2017) | 28/35 S2A type (has the solenoid) | Solenoid ("elektrodysza") found unconnected, or the owner didn't know where to feed it. | No power to the solenoid, so the idle circuit stays shut. | Feed it from the ignition-switched coil terminal ("B", red-black wire, or "15"/"16"). Not from terminal D, which goes to the points. | confirmed (dedox) | "Pod zacisk B ( przewód czerwono -czarny)" | https://forum.polskiedostawczaki.pl/viewtopic.php?t=3091 , https://forum.polskiedostawczaki.pl/viewtopic.php?t=3732 |
| O11 (R5) | Żuk (Klamot), 2016 | Weber with idle solenoid | Idle hard to set, and the engine **kept running with the solenoid unplugged**. The PCV plunger in the manifold was scratched. | Strucelsw: the spring-loaded **breather plunger in the intake manifold** sticks open. With a good needle valve and solenoid the engine **must stall when the solenoid is unplugged**. | Plunger cleaned and refitted. No final result posted. Photo: `images/o-manifold-pcv-plunger-and-spring.jpg`. | suggested | "jak zacięte w otwartej pozycji to ciężko wolne ustawić" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=165 |

## 4. Runs on after the ignition is switched off (dieseling)

No owner case was found in which run-on was the main complaint. The two relevant observations:
- O11 above: the engine kept running with the solenoid unplugged. That means fuel or air bypasses the closed idle jet, and the same fault causes run-on.
- Strucelsw (t=4635): a plain jet holder in place of the solenoid works, but the engine will then run on. See `troubleshooting.md` §4.

## 5. Floods, fuel leaks, fuel from the manifold drain holes

| # | Vehicle | Variant | Symptom | Cause | Fix | Status | Polish quote | Link |
|---|---|---|---|---|---|---|---|---|
| O12 **NEW** | Żuk (hckosmo2), 2020 | not stated | First failed start of the season: **fuel ran out from under the carburettor**. | The float weighed **24 g instead of the book's 18 g** and had fuel sloshing inside: holed and sinking. Marian: set the float level by the book, check the needle, and don't over-tighten the base nuts, because the base warps. | New float, new gaskets, float set by the book. Later: "runs like gold". | confirmed | "jest za ciężki ma 24g a wg książki ma mieć 18" | https://forum.polskiedostawczaki.pl/viewtopic.php?t=4581 , https://forum.polskiedostawczaki.pl/viewtopic.php?t=4581&start=15 |
| O13 (F4) | Żuk A15B S-21, 2020 | not stated (the advice given assumes the solenoid type) | Black, sooty plugs, misfire after standing, fuel under the manifold. | **Needle valve stuck open.** | Cleaning it cured the idle stumble, but it still ran rich. Advice: float about 6.5 mm, new idle jet 45 and new **solenoid O-ring 6×2 mm**, mixture screw 0.5–1.25 turns out, Denso plugs. | partly confirmed | "Zaworek iglicowy był zacięty w pozycji otwartej" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4814 |
| O14 (F6) | Nysa S-21, 2018 | **28/35 S2A1** | CO above 7%, black smoke after a blip, fuel dripping when hand-pumping, idle jet blocked twice. | Leaking needle valve, float set too high (8.5 mm), wrong primary main jet (118). | **New needle valve**, float reset to 6.5 mm, primary jet 110, new air filter. Idle CO 2.4%. | confirmed | "na bank zaworek. jak jest nieszczelny to będzie za wysoki poziom paliwa" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3998 |
| O15 (F16) | Żuk, 2021 | **28/35 S2A** | One chamber floods constantly. | A **broken small spring**. | Owner ordered a repair kit. | suggested | "pękła sprężynka i jedna komora jest cały czas zalewana" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=3&t=5058 |
| O16 (R14) | Nysa, 2011 (Marian) | new Weber, type not stated | Died on throttle. Then fuel streamed from the **manifold drain holes** and it would not start, although the float level was set precisely. | Suggested: fuel-pump pressure too high, from the diaphragm spring or a thin spacer in place of the 12 mm insulating one. Also check the choke closes. | New pump (about 70 zł) and the original spacer. | suggested | "całe paliwo spiernicza przez tajemnicze dziurki" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=60 , https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=75 |
| O17 (R15) | Nysa or Żuk (Przypadkowy), 2016 | not stated; his 6.5 mm float figure is a 28/35 one | After new gaskets and a clean, fuel **squirted** from the drain holes. Float checked 3 times, needle shuts, float 6.5 mm "counting the gasket". | Not found. ⚠ The factory figure is measured **without** the gasket, so his float may sit about one gasket thickness too high. | — | unresolved | "paliwo z tych że dziurek sika !" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=165 |
| O18 (R16) | Żuk "Smutek" on LPG (Klamot), 2016 | Weber with solenoid | Black plugs. Fuel dripped from the drain holes on choke starts. | The **pump outlet passage had never been properly drilled**, so pressure was low and erratic. | Fitted a **fuel-return line** to the tank (T-piece after the pump). The carburettor is now dry. Drain holes routed away with copper stubs: `images/o-manifold-drain-holes-copper-stubs.jpg`. | confirmed (leak) | "gażnik suchy z zewnątrz, paliwa nie brakuje" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=195 |
| O19 (R17) | Nysa, 2014 (Tomek) | not stated | A pump fitted with its bakelite spacer delivered nothing. | Worn pump lever, or a pump made for a longer lever. | Ran the pump **without** the spacer. ⚠ Others warn this raises pressure (flooding) and cam wear and loses heat insulation. | workaround | "z podkładką założoną nie pompuje w ogóle" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=135 |
| O20 **NEW** | Nysa camper (zbyszek99) on an electric pump for 2 years | old Weber (his earlier posts) | Once the float stuck and the carburettor overflowed. | The S-21 has no fuel-return line, so an electric pump keeps pushing against the needle. | He had a fire extinguisher at hand. Another member fitted a **return line**, which takes load off the needle and quietens the pump. He mounted the pump below tank level, because it lost its prime. A 58 zł low-pressure pump from Allegro. | confirmed (anecdote) | "raz mi się zaciął pływak , ale gaśnicę miałem pod ręką" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=2950 |

## 6. Hesitation, flat spot, stalls on throttle, no power

| # | Vehicle | Variant | Symptom | Cause | Fix | Status | Polish quote | Link |
|---|---|---|---|---|---|---|---|---|
| O21 (F9) | Żuk A03 (1961) with Weber, 2024 | not stated | A part was missing next to the float chamber. | Missing **accelerator-pump nozzle**, "fi 80 with a ball". Photo: `images/o-forum-zuk-weber-missing-accel-pump-nozzle.jpg`. | Identified by Strucelsw. | suggested | "dysza pompki przyspieszenia, fi80 z kulką" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=15&t=5488 |
| O22 (F8) | Żuk 1990 | not stated (a 1990 Żuk normally has a 28/35) | After disassembly the carburettor didn't work right. A small plunger and spring near the choke kept popping out. | **Missing retainer.** | Retainer found for about 5 zł. | confirmed | "Sprawa załatwiona koszt 5 zł" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=16&t=3995 |
| O23 **NEW** | Żuk A-111B, 1992 (rafalo517) | not stated (1992: 28/35) | **After he replaced a holed float, it chokes unless the choke is pulled.** | Marian: the new float's level was probably never set. | Set the float level from the "Podstawowe regulacje" guide. | suggested | "wymieniłem pływak w gaźniku bo dziurawy był i teraz auto się dławi" | https://forum.polskiedostawczaki.pl/viewtopic.php?t=2466 |
| O24 (R8) | Nysa 522, 2014 | not stated | Idles fine but stalls pulling away unless the pedal is stamped. | Marian: lean on tip-in from a blocked jet or channel. | Clean again, or enrich slightly. | suggested | "podczas ruszania gaśnie jak się sporo gazu nie doda" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=150 |
| O25 (R9) | Żuk (LumpeksSquad), 2013 | **28/35 S2A "ver. 3"** (new) vs the original "ver. 1" | The new carburettor was weak loaded and "kangarooed" from low to high rpm. | **Preservative left in the float chamber** of the new unit. Different emulsion tubes between versions (unverified). | The original ver. 1, repaired, ran perfectly. The new one was only partly cured. | partly confirmed | "w komorze pływakowej było trochę substancji konserwującej" | https://zlombol.pl/community/technikalia-2/gaznik-weber-28-35-s2a-zuk-problem-2/ |
| O26 **NEW** | Żuk (hckosmo2), 2020 | not stated | With the pedal down, the primary opens fully but the secondary only slightly. | Pedal-linkage adjustment. The secondary opens only with the pedal on the floor. | Adjust the rods so that both plates open fully with the pedal floored. | suggested / explained | "Druga sie otwiera zazwyczaj z pedalem w samej podłodze" | https://forum.polskiedostawczaki.pl/viewtopic.php?t=4581 |
| O27 **NEW** | S-21 (zolwik) | not stated | The secondary throttle would not open. | The small **crankcase-gas valve in the intake manifold**, worked by the carburettor linkage, was seized and blocked it. Strucelsw: it must move freely, and it also leans the mixture slightly. | Free it (heat and pliers). | suggested | "był zawarty i blokował otwieranie drugiej przepustnicy" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4162 |
| O28 (R27) | Żuk S-21 (Złombol team), 2014 | new Weber, not stated | Pedal floored opened the primary only 3/4 and the secondary barely. | Worn rod linkage. | Convert to a throttle cable using a Polonez quadrant. | suggested | "otwiera się tak na 3/4 przepustnica pierwsza a duga ledwo ledwo" | https://zlombol.pl/community/technikalia-2/zuk-s21-regenaeracja-ciegien-gazu-2/ |
| O29 **NEW** | Żuk A15, 1989, 25,000 km (adamko11) | not stated | Revs freely but won't exceed 60 km/h. | Suspects included the **second throat not opening** (Klamot) and the throttle not opening fully (Marian). Later an oily plug and worn valve guides were found. | Timing set to 8° with a strobe gave 8–10 km/h more. Root cause not found. ⚠ 8° is above the factory figure. | partly confirmed | "Pojazd nie jest w stanie osiągnąć prędkości większej niż 60 km/h." | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3347 |
| O30 **NEW** | Żuk 1986 (jacek44) | "Weber" | After the choke is pushed in, it won't rev for a few minutes; full throttle gives only about +100 rpm. | Strucelsw: a cold engine running lean, which is normal for the S-21. Marian: it shouldn't be that bad; suspects a dirty carburettor. | — | suggested | "auto po odpaleniu i odpuszczeniu ssania nie chce wejść na obroty" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4713 |
| O31 (R24) | Żuk S-21, 2017, at 20 °C | not stated | Without the choke it catches and loses revs; with the choke it starts at once. | **Normal**: at 20 °C the engine is cold. | None needed. | explained | "20stopni to zimny silnik. Trzeba mu dać ssania." | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=225 |
| O32 **NEW** | **GAZ-69 with S-21**, Ukraine (drive2 "Car B") | Polish Weber with the idle solenoid | Cold engine: revs hang 2–3 s on lift-off, then a stumble with an exhaust pop when snapping the throttle from about 1500 rpm. Goes away when warm. | Cold-engine lean stumble, as in O30. | More carburettor adjustment. He wanted to extend the mixture screw, which is hard to reach on the GAZ. | suggested | "По мере прогрева, провал и пердок в глушитель пропадает" (Russian) | https://www.drive2.ru/l/573928852976304186/ |
| O33 **NEW** | Same GAZ-69 | Weber, later swapped | Throttle sticking, and a small flat spot from mid revs to full throttle. | Wear in the carburettor. | Fitted another used Weber **without the solenoid (ЭПХХ)** and lapped its base flange flat. The sticking was better but it needed an extra return spring. | partly confirmed | "Установил новый старый карбюратор, без клапана ЭПХХ" (Russian) | https://www.drive2.ru/l/584099610411147866/ |
| O34 **NEW** | Same GAZ-69 | Weber | Light **pinking at about 40 km/h in top gear**; timing changes did not cure it. | Lean mixture: the **textolite (phenolic) spacer under the carburettor had cracked** in two places and warped from over-tightening, letting air in. | New spacer ordered. | diagnosed | "виновником текстолитовую прокладку" (Russian, shortened) | https://www.drive2.ru/l/590869853259170000/ |
| O35 (R11) | Warszawa S-21, club forum | not stated | Popping in the exhaust and poor revving, right after a plug change. | The **new ISKRA plugs**. | NGK plugs: "runs like clockwork". | confirmed | "Kupiłem NGK i chodzi jak zegarek." | https://syrena.nekla.pl/forum/viewtopic.php?t=10451 |
| O36 (R12) | Warszawa S-21, same thread | not stated | After an engine rebuild with new ISKRAs it would not run right. | The plugs. | Old plugs refitted, and it started. | confirmed | "Założyłem stare i odpaliła" | https://syrena.nekla.pl/forum/viewtopic.php?t=10451 |

## 7. Backfire into the carburettor

| # | Vehicle | Variant | Symptom | Cause | Fix | Status | Polish quote | Link |
|---|---|---|---|---|---|---|---|---|
| O37 (R13) | Żuk, 2013 (oskarczan) | not stated | After new HT leads it wouldn't start and **backfired into the carburettor**, spraying fuel. | Ignition: a cylinder not firing (the distributor had been swapped). The vacuum hoses were missing. | Checked plugs one by one, firing order 1-2-4-3, timing by ear, mixture screw from 1.5 turns. It ran smoothly, but the exhaust still popped. | partly confirmed | "nie pali i strzela w gaźnik" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=105 |

## 8. Black smoke, rich running, high consumption

| # | Vehicle | Variant | Symptom | Cause | Fix | Status | Polish quote | Link |
|---|---|---|---|---|---|---|---|---|
| O38 (F1) | Żuk A, 2010 | not stated | **After cleaning**: started at once but shook, black smoke, all plugs fouled, fuel spitting into the air filter. Mixture screw fully in. | He had **fitted the jets the wrong way round.** | Jets corrected: smoother and lower consumption. Then a damaged pump diaphragm was replaced. | confirmed | "miałem wkręcone odwrotnie dysze" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=30 |
| O39 (F5) | Żuk, sukiennik68 | not stated | The choke has to come off within seconds of starting. | Suspects primary and secondary main jets swapped. | — | suggested | "zamienione dysze I i II przelotu" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4814 |
| O40 **NEW** | Żuk A151B 1982, in the UK (hakin1) | not stated (Strucelsw's advice assumes the solenoid type) | **Failed the emissions test (CO and HC high)** after he had taken the carburettor off to clean it and then "experimented" with the idle speed. | Strucelsw: "clearly too rich". Flooding from a sunk float or leaking needle, or the **idle jet leaking past its seat**, either because it was once over-tightened or because **too thick an O-ring** sits under the plug or the solenoid. | Float set to 6.5 mm without gasket, idle mixture re-set, new plugs and oil, a Lucas coil. **Passed the retest without trouble**, and the choke can come off after 2–3 minutes. ⚠ Strucelsw also suggested raising idle to about 1000 rpm to cut CO. | confirmed | "za gruby oring tam jest(pod korkiem lub elektozaworem)" | https://forum.polskiedostawczaki.pl/viewtopic.php?t=4329 |
| O41 **NEW** | Same Żuk (hakin1), earlier thread | not stated | About **21 l/100 km** after the carburettor had been "only cleaned, not adjusted", on short trips and half of them on choke. | Short cold trips and too much choke. Members also said: check the **choke cable returns fully**, and check the float level. | New plugs, oil and the carburettor **set up again**: 16 l/100 km. A member reports 11 l/100 km on longer runs. | confirmed | "ustawieniu gaznika na nowo Zuk zszedl do 16l/100" | https://forum.polskiedostawczaki.pl/viewtopic.php?t=4256 |
| O42 **NEW** | Tarpan S-21 (Tarpanowiec) | not stated; the solenoid is powered | No power, heavy smoke, bad misfire. New HT leads and cap contacts cleaned had not helped. | Strucelsw: **the carburettor is overflowing**: holed float, leaking needle, fuel level too high. Or the manifold mixture pre-heater is stuck on "warm", the air-filter flap is on "warm", or the filter is dirty. | — | suggested | "przelewa gaźnik. dziurawy pływak, nieszczelna iglica" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3707 |
| O43 (R10) | Żuk after engine rebuild (Arendi), 2013 | 28/35 S2A (per thread) | About 15.5 l/100 km on the "factory 145" jet. | Own experiment. A 135 cut fuel use to about 12 l/100 km but gave small stumbles; a 115 made pulling away very hard. ⚠ | Chose a compromise jet. Another member warned that lean jets overheat valves under load. | confirmed (experiment) | "Wymieniamy dyszę na 135, spalanie spada do 12 l/100km" | https://zlombol.pl/community/technikalia-2/gaznik-weber-28-35-s2a-zuk-problem-2/ |
| O44 (R20) | Żuk 1997 (rybamlooda), during his own clean, 2014 | not stated (1997: 28/35 S2B1 likely) | Found the **mixture screw screwed fully in** and the ~5 mm **insulating spacer missing**. | ⚠ Marian said fully in = richest. On these Webers screwing in **leans**, so a bottomed screw means a dead or lean idle circuit. A missing spacer means a hotter carburettor. | Buy the spacer (about 5 zł). Seal the LPG flange with fuel-proof material, not silicone. | suggested | "Jak jest wkręcona do końca to jest najbogatsza mieszanka" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=135 |
| O45 (R19) | Same Żuk 1997 ex-school bus, Weber + LPG | not stated | "Up to 30 l/100 km", hard cold start, runs as if on 3 cylinders until hot. | Mostly the LPG side: the **reducer** needed regeneration. | Reducer regenerated, then an old Żuk mechanic set up the carburettor and valves: "starts like clockwork". | confirmed | "Po regeneracji reduktora, żuk zaczął chodzić bardzo ładnie na gazie" | https://forum.polskiedostawczaki.pl/viewtopic.php?t=2222 |
| O46 (R21) | Żuk 1989 S-21 on LPG (Złombol team), 2013 | not stated | 19–22 l LPG/100 km after the installer's setup; perfect on petrol. | LPG reducer and mixer set rich. | Leaned them: settled at 16–17 l. | confirmed | "palił 14-15 litrów gazu! Sukces!" | https://zlombol.pl/community/technikalia-2/zuk-lpg-s-21-problem-ze-spalaniem-pomocy-2/ |
| O47 (R22) | Warszawa (lbs5), 2014 | **Jikov replaced by a Nysa Weber** | The worn Jikov "ate like hell" and could not be adjusted. | Worn Jikov. | Swapped to a Nysa Weber (needs the Weber manifold and filter can): "all problems gone". | confirmed | "Wpakowałem Webera z Nysy i wszystkie problemy odeszły w niepamięć." | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=135 |
| O48 (F11) | Żuk A15B S-21, "WEBER", 2020 | not stated | Acrid puffs and sticky soot from the air-filter housing. | Start with the crankcase breather (odma). Hose-routing photo: `images/o-forum-zuk-s21-weber-hose-routing.jpg`. | — | unresolved | "od tej odmy zaczniemy" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4713 |

## 9. Dies when hot, hot-start trouble, vapour lock

| # | Vehicle | Variant | Symptom | Cause | Fix | Status | Polish quote | Link |
|---|---|---|---|---|---|---|---|---|
| O49 (R2) | Nysa (nysanek), 2012 | not stated | Hot-start trouble, uneven hot idle, petrol smell in the cab. | Exhaust-manifold heat soaking the float chamber. | 2 mm **aluminium heat shield** between manifold and float chamber: `images/o-nysa-weber-heat-shield.jpg`. | confirmed (author) | "paliwo o wiele chlodniejsze jest w komorze plywakowej" | https://forum.polskiedostawczaki.pl/viewtopic.php?t=1924 |
| O50 (R25) | S-21 (tomek_jaz), 2017 | not stated | Fine cool. Above about 80 °C fuel "goes back" and it starves. He had fitted a non-return valve and a filter before the pump. | Suggested: the non-return valve restricts flow, an air leak or blocked pickup, or **fuel vaporising on the suction side**. | Remove the valve, test from a can, check the pickup. | suggested | "cofanie się paliwa po rozgrzaniu silnika" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=210 |

## 10. Other

| # | Vehicle | Variant | Symptom | Cause | Fix | Status | Polish quote | Link |
|---|---|---|---|---|---|---|---|---|
| O51 (R26) | Żuk S-21, 10,000 km after a rebuild, 2014 | not stated ("carb super") | Cylinder 1 dead despite good compression, spark and plugs. | The **cylinder head**. | Another head fitted: all four cylinders work. | confirmed | "Po wymianie głowicy na inną silnik zaczął pracować na wszystkie gary" | https://zlombol.pl/community/technikalia-2/zuk-silnik-s-21-nie-pali-na-jeden-gar-2/paged/2/ |

---

## Advice that contradicts factory data (flags)

1. **Mixture-screw direction (O44; also t=4635).** Marian wrote that fully in is the richest setting. On the 28/35 the screw meters the idle emulsion, so **in = leaner and out = richer**. Strucelsw's "if it still runs with the screw shut, fuel is leaking in from somewhere" (t=4814) only makes sense this way. A screw found bottomed means a dead idle circuit.
2. **Float measured "counting the gasket" (O17).** Every factory figure (S2A1 6.25–6.75 mm, S2B1 7 ±0.25 mm) is measured **without** the cover gasket. Strucelsw's forum figure, 6.5 mm "bez uszczelki" (t=4329), sits inside the S2A1 range. The Z89 manual's 5–5.5 mm is probably a carry-over error from the 34S2B1 manual (see `specs-and-jets.md`).
3. **"Raise idle to about 1000 rpm to pass CO" (O40)** and **"Weber idle 800–900"** (Marian, t=3250). Factory idle is **600–800 rpm**. A higher idle masks a rich idle mixture; it doesn't fix it.
4. **"The factory 145 jet" (O43).** On the S2A/S2A1, 145 is the **secondary** main jet. The primary is 110, and the S2B1 secondary is 125. Do not put 135/115 experiments into the wrong throat.
5. **Primary main jet 118 (O14)** is not a factory size. The factory primary is 110.
6. **Running the fuel pump without its spacer (O19)** raises pump pressure, which itself floods the carburettor, and removes the pump's heat insulation. The factory stack is a bakelite spacer plus two gaskets.
7. **Ignition advance of 8° (O29)** is above the factory figure (see `../s21-engine/`).
8. **Wire pushed into jets to save fuel.** An old fleet trick reported on retrotraktor.pl (https://retrotraktor.pl/forum/viewtopic.php?t=5113). A used carburettor may still have such jets, and cleaning a jet with wire enlarges it. Neither matches the factory calibration.

---

## Patterns: what actually caused the problem

All 51 cases (O1–O51) are counted once each, under their main cause. "Confirmed" includes "partly confirmed".

| Rank | Cause | Count | Confirmed | Cases |
|---|---|---|---|---|
| 1 | **Float, needle valve, fuel level** (holed or heavy float, needle stuck or leaking, level wrong or not reset after a new float, broken spring) | 8 | 4 | O12, O13, O14, O15, O17, O20, O23, O42 |
| 2 | **Fuel supply outside the carburettor** (pump pressure or sticking pump, pump spacer, tank pickup, heat or vapour) | 7 | 3 (+1 workaround) | O7, O8, O16, O18, O19, O49, O50 |
| 3 | **Not the carburettor: ignition, plugs, head** | 6 | 6 | O3, O4, O35, O36, O37, O51 |
| 4= | **Mistakes made during cleaning or disassembly** (jets swapped, pump nozzle or retainer missing, mixture screw bottomed, spacer left out) | 5 | 2 | O21, O22, O38, O39, O44 |
| 4= | **Throttle linkage, secondary not opening** | 5 | 2 | O26, O27, O28, O29, O33 |
| 6= | **Dirt**: strainer, internal channels, preservative in a new unit | 4 | 3 | O1, O6, O24, O25 |
| 6= | **Idle mixture or adjustment** after a clean, plus jetting experiments | 4 | 4 | O40, O41, O43, O47 |
| 8= | **Air leaks** (cracked spacer, breather or PCV plunger, breather hoses) | 3 | 0 | O11, O34, O48 |
| 8= | **Normal cold-engine behaviour** | 3 | — | O30, O31, O32 |
| 10= | **Electrics: solenoid or petrol cut-off valve wiring** | 2 | 2 | O5, O10 |
| 10= | **LPG system set rich** | 2 | 2 | O45, O46 |
| 10= | Unresolved | 2 | — | O2, O9 |

**What this means for a 28/35 that has run badly since someone cleaned it.** Ten cases follow a clean, a strip-down or a part swap by the owner: O1, O2, O17, O21, O22, O23, O38, O40, O41 and O44. In those, the causes in order were:
1. **Jets in the wrong throat, or small parts lost**: the pump nozzle with its ball, a retainer, the solenoid-tip jet (O21, O22, O38, and O1's tip). 3–4 cases.
2. **Idle mixture never re-set, or the screw left bottomed**, sometimes with a leaking idle-jet seal (O40, O41, O44). 3 cases.
3. **Float level not set up again** after reassembly or after a new float, or flooding with no cause found (O17, O23). 2 cases.
4. **Dirt pushed deeper into passages** rather than flushed out, so a second thorough clean was needed (O1; O2 unresolved). 1–2 cases.

The solenoid itself is rarely the culprit once powered. An unpowered or unconnected solenoid (O10), or a snapped or leaking tip jet (O1, O40), are the solenoid-related failures owners actually report.

## Gaps

- **elektroda.pl** still times out from here, and Wayback has no snapshots of its Żuk carburettor threads. Its cases are missing.
- **No dieseling or run-on case** was found. Section 4 relies on mechanics' statements.
- Only one Tarpan case (O42) and no case naming the **S2B1** explicitly.
- Fresh zlombol.pl searches returned only the threads already used; its wpForo search does not filter usefully.
