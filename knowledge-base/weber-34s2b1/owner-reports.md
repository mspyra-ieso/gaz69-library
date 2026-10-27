# Owner reports: symptom → cause → fix (second collection)

This page holds **real owner troubleshooting cases** for the Polish Weber twin-choke carburettor on the FSO S-21 engine, and the sister carburettors owners swapped with it. Owners name the vehicle (Żuk, Nysa, Warszawa, Tarpan), not the carburettor, so each row says "variant not stated" unless the poster named one. Lublin, Polonez and 125p cases are left out unless they concern an S-21 Weber.

None of these cases repeats one in `forum-experiences.md`. That page mostly used pages 1–3 and 13 of the long FMPD thread t=777. This page uses the other pages of t=777 (4–12 and 14–17), other FMPD threads, zlombol.pl (Złombol charity-rally forum) and the Syrena/Warszawa club forum. All text is paraphrased in English. Polish quotes are short originals.

**Status column**
- **confirmed**: the poster says the fix worked on their own vehicle.
- **partly confirmed**: things improved, but the poster reports problems left over.
- **suggested**: advice from other members, with no outcome reported.
- **unresolved**: the thread ends without a cause.

**Factory reference for flags:** the 34S2B1 has main jets 120/150, idle jets 50/50, air correctors 210/210, F30 emulsion tubes, and a float level of 5–5.5 mm. Idle is 600–800 rpm (Żuk 1985 manual) or 550–650 rpm (Nysa 1977 manual). Rows marked ⚠ contain advice that differs from this data or from factory practice. See "Advice that contradicts factory data" below.

FMPD = forum.polskiedostawczaki.pl. "t777 pN" = the thread *Układ zasilania – gaźnik, pompa paliwa – diagnoza, regulacja*, page N.

---

## 1. Won't start (cold)

| # | Vehicle, year | Variant | Symptom | Cause found | Fix | Status | Polish quote | Link |
|---|---|---|---|---|---|---|---|---|
| R1 | Żuk S-21, 2014 (Złombol team) | not stated | Started at once before a fuel-tank repair and valve adjustment. Afterwards it would not fire at all, plugs got wet after long cranking, and the spark came and went. | Not the carburettor. The **new ISKRA spark plugs were poor quality** and died once they had been flooded. Cleaning the distributor and points only helped a little. | Fitted old Bosch plugs (plus starting spray) and the engine ran. Tip: dry flooded plugs on a gas flame. | confirmed | "świece były marnej jakości (ISKRA mimo że nowe)" | https://zlombol.pl/community/technikalia-2/zuk-s21-nie-odpala-2/ |

## 2. Won't start hot

| # | Vehicle, year | Variant | Symptom | Cause found | Fix | Status | Polish quote | Link |
|---|---|---|---|---|---|---|---|---|
| R2 | Nysa (nysanek's own), 2012. Copied by zbyszek99 on a Nysa camper | nysanek: not stated. zbyszek99's carburettor was called "an old Weber, one of the first" (pre-solenoid, so likely the 34 series) | Hot-start trouble, uneven hot idle, petrol smell in the cab. | Heat from the exhaust manifold soaking the float chamber, so the fuel got hot and boiled off. | A 2 mm **aluminium heat shield** between the manifold and the carburettor float chamber, cut to clear the intake. Photo: `images/c-nysa-weber-heat-shield.jpg`. | confirmed by the author for his own Nysa. zbyszek99's result was not reported. | "paliwo o wiele chlodniejsze jest w komorze plywakowej" | https://forum.polskiedostawczaki.pl/viewtopic.php?t=1924 |

## 3. Starts, then dies

| # | Vehicle, year | Variant | Symptom | Cause found | Fix | Status | Polish quote | Link |
|---|---|---|---|---|---|---|---|---|
| R3 | Żuk, 2012 (ekmir) | not stated | Fine in the morning. After about 10 km it started bucking. After a 5-hour rest it started for a moment, then died, and died whenever throttle was added. No fuel smell. | **Blocked inlet strainer (sitko) in the carburettor.** A new coil and condenser and a cleaned fuel pump made no difference. | Unscrewed and cleaned the carburettor strainer. | confirmed | "Po wykręceniu sitka w gaźniku i przeczyszczeniu, silnik pracuje tak jak powinien" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=90 , https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=105 |
| R4 | Żuk S-21 dropside, 2017 (KrzysiekH) | not stated | Ran dry on a hill and the pump sucked in tank sludge. After a new pump it later **stalled at idle**, and hand-priming gave no fuel. | The **tank pickup was blocked by a piece of filter**, and a **corroded spot on the fuel line let air in**. Also: an aftermarket tank had its baffle welded on the wrong side. | Replaced the pump (about 110 zł), fitted a filter before the pump, cleared the pickup, made a new strainer mesh, repaired the line. "Pump spits like in the videos." | confirmed | "smok był zapchany kawałkiem filtra" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=195 , https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=225 |

## 4. No idle or hunting idle

| # | Vehicle, year | Variant | Symptom | Cause found | Fix | Status | Polish quote | Link |
|---|---|---|---|---|---|---|---|---|
| R5 | Żuk (Klamot), 2016 | Weber with idle solenoid (28/35 type) | Idle hard to set. The engine kept running with the solenoid unplugged. The manifold PCV plunger was badly scratched. | Strucelsw: the spring-loaded **crankcase-breather plunger in the intake manifold** can stick open and make idle hard to set. Its spring must be stiff enough that the plunger is not sucked in on overrun. With a good needle valve and solenoid, the engine **should stall when the solenoid is unplugged**. | Plunger cleaned and refitted, spring chosen by feel. No final idle result posted. Photo: `images/c-manifold-pcv-plunger-and-spring.jpg`. | suggested | "jak zacięte w otwartej pozycji to ciężko wolne ustawić" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=165 |
| R6 | Żuk S-21 1987 (Sebafso, 2016) and an S-21 (dedox, 2017) | solenoid-equipped Weber (28/35 S2A type, **not** 34S2B1) | Solenoid ("elektrodysza") found unconnected, or the owner didn't know where to feed it. | Its feed wire was missing. A solenoid without power shuts the idle circuit. | Feed it from the ignition-switched coil terminal ("B", red-black wire, or "15"/"16"). Do not use the terminal D that goes to the points. | confirmed (dedox) | "Pod zacisk B ( przewód czerwono -czarny)" | https://forum.polskiedostawczaki.pl/viewtopic.php?t=3091 , https://forum.polskiedostawczaki.pl/viewtopic.php?t=3732 |
| R7 | Nysa S-21, 2022 (Daniel22) | **Fiat 125p 34 DCMP** (pre-1986 Polonez type, Fiat jets) | Runs on 3 cylinders and limps at idle. Strong spark on all cylinders, 11.5 bar compression on the dead one. | Strucelsw suspected a leaking **intake-manifold gasket**. He added that the DCMP needs S-21 jets and a different breather hook-up. | Check the manifold gasket, rejet ⚠ (his figures are in the flags section), and blank the original breather port by the plunger. | suggested. The "fixed it, thanks" reply came from a different account that looks like spam, so it is not counted as confirmation. | "sprawdz uszczelkę pod kolektorem ssacym." | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=240 |

## 5. Hesitation, flat spot, stalls on throttle

| # | Vehicle, year | Variant | Symptom | Cause found | Fix | Status | Polish quote | Link |
|---|---|---|---|---|---|---|---|---|
| R8 | Nysa 522, 2014 (Robo) | not stated | Idle fine. Stalls pulling away and after every gear change unless the pedal is stamped. Generally weak, worst on uphill starts. | Marian: lean on tip-in, from a blocked jet or channel, so it needs a big accelerator-pump shot to get through. | Clean the carburettor again, or enrich slightly. | suggested | "podczas ruszania gaśnie jak się sporo gazu nie doda" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=150 |
| R9 | Żuk (LumpeksSquad), 2013, used in Norway | **28/35 S2A "ver. 3"** (new) vs the original **ver. 1** | The new carburettor was very weak loaded (200–300 kg) and stumbled from low to high rpm ("kangaroo"). | Carburettor specialist Z. Jabłoński found **preservative left in the float chamber**. Cleaning helped, but it still stumbled. The two versions also had **different emulsion tubes** (ver. 3: 5/3 and 5/4; ver. 1: 6/2 in both barrels). The original ver. 1 had a faulty air-jet seat. | After repair and adjustment, the original ver. 1 ran perfectly ("Żuk jest żwawy"). The new one was only partly cured. | partly confirmed | "w komorze pływakowej było trochę substancji konserwującej" | https://zlombol.pl/community/technikalia-2/gaznik-weber-28-35-s2a-zuk-problem-2/ |
| R10 | Żuk after an engine rebuild (Arendi), 2013 | 28/35 S2A (per thread) | Fuel use around 15.5 l/100 km on the "factory 145" jet. | His own tests with an old mechanic. **135** cut fuel use to about 12 l/100 km but gave small stumbles pulling away. **115** gave very hard pulling away and stalled at idle cold and sometimes hot. | Chose a compromise jet. Changing it takes 5 minutes without removing the carburettor. Another member warned that lean jets overheat valves when loaded. ⚠ | confirmed (as an experiment) | "Wymieniamy dyszę na 135, spalanie spada do 12 l/100km" | https://zlombol.pl/community/technikalia-2/gaznik-weber-28-35-s2a-zuk-problem-2/ |
| R11 | Warszawa (S-21), Syrena/Warszawa club forum | not stated (owner had both a Jikov and a Weber) | Popping in the exhaust and poor revving, right after a plug change. | **The new ISKRA plugs.** | Fitted NGK plugs and it "runs like clockwork". | confirmed | "Znalazłem przyczynę - świece. Kupiłem NGK i chodzi jak zegarek." | https://syrena.nekla.pl/forum/viewtopic.php?t=10451 |
| R12 | Warszawa (S-21), same thread, second owner | not stated | After an engine rebuild with new ISKRA plugs, he could not get it running right despite fiddling with ignition and carburettors. | The plugs. | Old plugs refitted and it started. A later set of new ISKRAs was fine. A third member said he ended up on two old plugs and one new one. | confirmed | "Założyłem stare i odpaliła" | https://syrena.nekla.pl/forum/viewtopic.php?t=10451 |

## 6. Backfire into the carburettor

| # | Vehicle, year | Variant | Symptom | Cause found | Fix | Status | Polish quote | Link |
|---|---|---|---|---|---|---|---|---|
| R13 | Żuk, 2013 (oskarczan) | not stated | Shook from the day he bought it. After new HT leads it would not start and **backfired into the carburettor**, spraying fuel onto the bonnet lining, with about 0.5 l on the floor. Plugs were sooty and dry except one wet. | **Ignition**: a cylinder not firing (a previous owner had swapped the distributor). The vacuum hoses (carburettor to distributor and to manifold) were missing. | Checked spark plug by plug, used firing order 1-2-4-3, set timing by ear and the mixture screw from 1.5 turns. Result: no shaking, revs freely, holds idle. Exhaust still "popped", and nysanek suspected uneven compression or burnt valves. | partly confirmed | "nie pali i strzela w gaźnik" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=105 , https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=120 |

## 7. Flooding, fuel leaks, fuel smell

**Background:** the S-21 Weber intake manifold has **two small drain holes** (with matching holes in the manifold gasket) that dump overflow fuel. On the Weber manifold they drip onto the exhaust manifold. nysanek explains they are a hydraulic-lock safeguard. **Fuel coming out of them means the carburettor is overflowing.** Do not block them.

| # | Vehicle, year | Variant | Symptom | Cause found | Fix | Status | Polish quote | Link |
|---|---|---|---|---|---|---|---|---|
| R14 | Nysa, 2011 (Marian) | **new Weber**, type not stated (the old one did the same) | Choke could come off and it started well hot, but it died on throttle and sometimes after a while. Then fuel streamed out of the manifold drain holes and it would not start at all, although the float level was set "precisely". | Suggested: **fuel pump pressure too high** (diaphragm spring, or the thick insulating spacer under the pump replaced by a thin one, so the lever stroke is too long). Also: check the choke closes fully. The original spacer is about 12 mm and fitted with 2 gaskets. | Fit a new pump (about 70 zł) and an original spacer. | suggested / outcome not posted | "całe paliwo spiernicza przez tajemnicze dziurki" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=60 , https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=75 |
| R15 | Nysa or Żuk (Przypadkowy), 2016 | not stated | After new gaskets and cleaning the manifold and carburettor, fuel **squirted** from the drain holes. Float checked 3 times, needle shuts, float at 6.5 mm "counting the gasket". | Not found in the thread. ⚠ 6.5 mm is a 28/35 figure. On a 34S2B1 the factory float level is 5–5.5 mm. | — | unresolved | "paliwo z tych że dziurek sika !" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=165 |
| R16 | Żuk "Smutek" on LPG (Klamot), 2016 | Weber with solenoid; Jikov tried as well | On the Weber it ran nicely but with **black plugs**, at a correct float level. On the Jikov the fuel level was too high, fuel poured onto the manifold, and on the road it starved. | Fuel pump pressure was low: the **pump outlet passage had never been properly drilled** (a ragged hole of about 2 mm²). The Weber coped, the Jikov did not. Fuel also dripped from the drain holes during choke starts. | Kept the Weber (lower fuel use). Fitted a **fuel-return line** to the tank (Żuk-diesel pickup, 8 mm T-piece after the pump, return about 5 mm), so the carburettor is now dry with no dripping on choke. Routed the drain holes away with copper brake-pipe stubs (photo `images/c-manifold-drain-holes-copper-stubs.jpg`). Black plugs not followed up. | confirmed (leak and supply) | "gażnik suchy z zewnątrz, paliwa nie brakuje" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=165 , https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=195 |
| R17 | Nysa, 2014 (Tomek) | not stated | A pump fitted **with** its bakelite spacer delivered nothing. One Nysa ran with no spacer. | Worn pump lever, or a pump made for a longer lever. | Ran the pump **without** the spacer. ⚠ Marian, Drewniany and nysanek warn this gives higher pressure (flooding risk), more cam wear and loss of heat insulation. The factory stack is bakelite spacer plus two paper gaskets. | workaround (works for him) | "z podkładką założoną nie pompuje w ogóle" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=135 , https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=150 |
| R18 | Warszawa 223 with Weber on an adapter (flisak), 2013, LPG | Weber marked 24/26 in the venturis. Members said it was Fiat-type or pre-1986 | Float "beaten up" from LPG running. | Floats wear when they rattle while the engine runs on gas. Strucelsw notes the Weber float rubs through when its lower stop is set wrong. | Float replaced. Admin's float figures were 28/35 S2A1 6.25–6.75 mm and S2B1 6.75–7.25 mm. nysanek said don't fit that old carburettor, use a 28/35. ⚠ The 28/35 numbers are not 34S2B1 values. | in progress / suggested | "wymieniam plywak(stary wyklepany od gazu)" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=105 , https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=165 |

## 8. Heavy consumption and black smoke

| # | Vehicle, year | Variant | Symptom | Cause found | Fix | Status | Polish quote | Link |
|---|---|---|---|---|---|---|---|---|
| R19 | Żuk 1997, ex-school bus, Weber + LPG (rybamlooda / zukiemprzezswiat.pl), 2013 | not stated | "Up to 30 l/100 km". Hard cold start, then it runs as if on 3 cylinders until fully hot. Black but dry plugs. | Mostly the LPG side: the 20–30 l figure was **gas**, and the **reducer needed regeneration**. Marian's checklist: mixture screw, idle screw, valves 0.20–0.22 mm, plug gap 0.6–0.7 mm, swapped jets. nysanek's checklist: choke not fully closing, pump pressure, holed float, needle. | Regenerated reducer, then an old Żuk mechanic ("Pan Staszek") adjusted the carburettor and valves: livelier, quieter, "starts like clockwork". Later 15–21 l LPG on a trip to Crimea. ⚠ nysanek also advised removing the exhaust heat-riser flap. | confirmed | "Po regeneracji reduktora, żuk zaczął chodzić bardzo ładnie na gazie" | https://forum.polskiedostawczaki.pl/viewtopic.php?t=2222 , https://forum.polskiedostawczaki.pl/viewtopic.php?t=2222&start=15 |
| R20 | Same Żuk, 2014, during his own carburettor clean | Weber, variant not stated | Found the **mixture screw screwed fully in**. The ebonite **insulating spacer** between manifold and carburettor (about 5 mm) was **missing**. The LPG-mixer flange leaked (silicone blew out). | Marian thought the bottomed screw might explain the high consumption. ⚠ He says fully in = richest, which conflicts with Weber practice (see flags). The missing spacer means a hotter carburettor. | Buy the 5 mm insulating spacer (about 5 zł). Seal the LPG flange with fuel-proof rubber or a paper gasket with sealant, not silicone ("dissolved by petrol"). The secondary-throttle stop screw is factory-set and should be left alone. | suggested | "Jak jest wkręcona do końca to jest najbogatsza mieszanka" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=120 , https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=135 |
| R21 | Żuk 1989 S-21 on LPG (Złombol team), 2013 | not stated | Ran perfectly on petrol but used **19–22 l LPG/100 km** on the road after the LPG installer's adjustment. | The LPG reducer and mixer were set rich. Others suggested dragging brakes or the wrong reducer type. | Leaned the reducer and mixer almost to stalling: 14–15 l but no power on hills. Settled at 16–17 l and a steady 90 km/h. (LPG side, not the Weber.) | confirmed | "palił 14-15 litrów gazu! Sukces!" | https://zlombol.pl/community/technikalia-2/zuk-lpg-s-21-problem-ze-spalaniem-pomocy-2/ |
| R22 | Warszawa (lbs5), 2014 | **Jikov** replaced by a Weber from a Nysa | Jikov "ate like hell" and could not be adjusted, despite cleaning and new gaskets. | Worn Jikov. nysanek says Jikovs need constant re-adjustment, smoke black and suck air past a worn throttle spindle. | **Swapped to a Nysa Weber**: "all problems gone". A swap needs the Weber manifold and filter can. Linkage stays the same. | confirmed | "Wpakowałem Webera z Nysy i wszystkie problemy odeszły w niepamięć." | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=135 |

## 9. Runs only on the choke

| # | Vehicle, year | Variant | Symptom | Cause found | Fix | Status | Polish quote | Link |
|---|---|---|---|---|---|---|---|---|
| R23 | Nysa 522, 2010 (just bought) | **Jikov** (sister carburettor) | Ran badly. On choke it didn't stall, off choke it died at idle and choked on throttle. Exhaust smell. | nysanek: Jikovs suck **false air through a worn throttle spindle**. The smell was probably manifold-stud leaks (loose nuts). Note: Jikov engines have an open breather, Weber engines a closed one. | Tighten the manifold nuts. Convert to Weber (needs a different manifold, filter can, breather cover and sump with a breather pipe). | suggested | "bez ssania gaśnie na wolnych` obrotach i się dławi przy dodaniu gazu" | https://forum.polskiedostawczaki.pl/viewtopic.php?t=995 |
| R24 | Żuk S-21 (KrzysiekH), 2017, summer, 20 °C | not stated | Without choke it caught and then lost revs. On choke it started at once. | **Normal.** At 20 °C the engine is cold. Marian: if it starts cold without choke, the mixture is too rich. One member suggested checking the **choke-weakening piston in the carburettor top** between the barrels (the 34-series cold-start piston) in case it is stuck or missing. | None needed. | explained (not a fault) | "20stopni to zimny silnik. Trzeba mu dać ssania." | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=225 |

## 10. Dies when hot / vapour lock

| # | Vehicle, year | Variant | Symptom | Cause found | Fix | Status | Polish quote | Link |
|---|---|---|---|---|---|---|---|---|
| R25 | S-21 (tomek_jaz), 2017 | not stated | Fine while cool. After a longer drive above about 80 °C, fuel "goes back" and the engine starves. He had fitted a new pump, a non-return valve and a filter before the pump. | Suggested causes: the **non-return valve gives too much resistance** (Marian never used one), an air leak or blocked pickup (ShadoVv), or **fuel vaporising on the suction side** because restrictions before the pump lower the pressure (phinek). | Remove the non-return valve, run from a can to isolate the problem, check the tank and pickup. See also R2 (heat shield) and R20 (missing insulating spacer). | suggested | "cofanie się paliwa po rozgrzaniu silnika" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=210 |

## 11. Other

| # | Vehicle, year | Variant | Symptom | Cause found | Fix | Status | Polish quote | Link |
|---|---|---|---|---|---|---|---|---|
| R26 | Żuk S-21, 10,000 km after a rebuild (Złombol team), 2014 | not stated ("carb super") | Cylinder 1 dead: pulling its lead changed nothing. Compression over 11, spark good, plugs swapped, valves adjusted. | Not the carburettor: the **cylinder head** (cause not identified). | Fitted another head and it ran on all four. | confirmed | "Po wymianie głowicy na inną silnik zaczął pracować na wszystkie gary" | https://zlombol.pl/community/technikalia-2/zuk-silnik-s-21-nie-pali-na-jeden-gar-2/ , https://zlombol.pl/community/technikalia-2/zuk-silnik-s-21-nie-pali-na-jeden-gar-2/paged/2/ |
| R27 | Żuk S-21, 2014 (Złombol team) | new Weber, variant not stated | Pedal on the floor opened the **primary only about 3/4 and the secondary barely**: worn throttle rods and linkage. | Wear in the rod linkage. On a mechanically linked secondary such as the 34S2B1's, this costs top-end power. | Convert to a throttle cable using a Polonez pedal-quadrant ("półksiężyc") from a scrapyard. | suggested | "otwiera się tak na 3/4 przepustnica pierwsza a duga ledwo ledwo" | https://zlombol.pl/community/technikalia-2/zuk-s21-regenaeracja-ciegien-gazu-2/ |

**Adjacent, not a fault case:** a Warszawa M-20 owner asked about fitting an S-21. Replies: the S-21 bolts to the M-20 gearbox, but the radiator outlet is in a different place (M-20 centre and angled down, S-21 offset towards the driver and pointing at the bulkhead), so the hose ends up kinked. This is relevant to the GAZ-69 swap. https://syrena.nekla.pl/forum/viewtopic.php?t=13483

---

## Advice that contradicts factory data (flags)

1. **"The Żuk leaves the factory with 145 on the first barrel" (R10).** On the 34S2B1 the factory main jets are **120 primary and 150 secondary**. The 28/35 S2A family runs about 110–125 primary, with 145 on the **secondary**. Do not copy the 135/115 experiments onto a 34S2B1 primary.
2. **DCMP rejet figures (R7):** primary main 115, air 225–230, idle 45. Secondary 145–155 with a 26 mm venturi, or 125–135 with a 24 mm venturi. These are not 34S2B1 values (120/150 mains, 210/210 air, 50/50 idle).
3. **Float 6.5 mm (R15) and 6.25–7.25 mm (R18)** are 28/35 settings. The factory 34S2B1 setting is **5–5.5 mm**.
4. **Mixture-screw direction (R20).** Marian wrote that screwed fully in = richest. On these Webers the idle mixture screw meters the idle emulsion, so **screwing in leans and screwing out richens**. This matches Strucelsw's test in FMPD t=4814 and the note in `forum-experiences.md`. A screw found bottomed out means a lean or dead idle circuit, not a rich one. Treat Marian's statement as an error.
5. **Idle speed "about 800–900 for a Weber"** (Marian, FMPD t=3250, https://forum.polskiedostawczaki.pl/viewtopic.php?t=3250). This is above the 34S2B1 factory range of 600–800 rpm (Żuk 1985) or 550–650 rpm (Nysa 1977). Strucelsw says the raised figure comes from CO rules on the later solenoid carburettors.
6. **Removing the exhaust heat-riser flap (R19)** and **running the fuel pump without its spacer (R17)** depart from factory build. The heat riser helps cold running and against carburettor icing. The spacer insulates the pump and sets its stroke, and leaving it out raises pump pressure, which itself causes flooding.
7. **"Secondary throttle gap 0.05 mm"** (Lubczyński book, quoted for the older 34 type, FMPD t777 p9–10). The gap only stops the plate seizing in the bore. It is not a mixture setting, so leave the stop screw alone if nobody has touched it.

---

## Patterns: most frequently reported causes

This counts the 27 new cases here (R1–R27) plus the 16 entries in `forum-experiences.md` (F1–F16), **43 entries in all**. Each entry is counted once, under its main cause. F3 and F15 report no cause and are left out. Counts are approximate because many threads are suggestion-only. The confirmed count is in brackets.

| Rank | Cause | Count (confirmed) | Entries |
|---|---|---|---|
| 1= | **Needle valve, float level, flooding** (stuck or leaking needle, wrong level, worn float, broken spring) | 7 (2) | F4, F6, F13, F14, F16, R15, R18 |
| 1= | **Fuel supply outside the carburettor** (pump pressure too high or low, pump spacer, blocked pickup, air leak in the line, heat or vapour) | 7 (3) | F7, R2, R4, R14, R16, R17, R25 |
| 3 | **Not the carburettor at all: ignition, plugs, head** (new ISKRA plugs ×3, timing, misfiring cylinder, bad head) | 6 (5) | F10, R1, R11, R12, R13, R26 |
| 4= | **Assembly mistakes after cleaning or disassembly** (jets swapped, missing retainer or pump nozzle, mixture screw bottomed, missing insulating spacer) | 5 (2) | F1, F5, F8, F9, R20 |
| 4= | **Jetting, emulsion tubes, wrong-spec carburettor, basic adjustment** | 5 (3, plus R9 partly) | R7, R9, R10, R19, R22 |
| 6 | Air leaks, crankcase-breather (PCV) plunger, solenoid wiring | 4 (1) | F11, R5, R6, R23 |
| 7 | Dirt in the strainer, jets or channels; preservative left in a new carburettor | 3 (2) | F2, R3, R8 (R9 also had this as a second cause) |
| 8 | Other: LPG system set rich (R21), worn throttle linkage (R27), accelerator-pump diaphragm (F12), normal choke behaviour (R24) | 4 | — |

**What this means for a 34S2B1 that has run badly since a clean:**
- The likeliest culprits are reassembly mistakes and the needle and float. That means jets in the wrong holes, a bottomed mixture screw, a missing pump nozzle or spacer, and a float not reset to 5–5.5 mm. Dirt knocked loose into the strainer or passages comes next.
- Rule out ignition and plugs first, because about one case in seven was not the carburettor at all.
- Fuel coming from the manifold drain holes always means overflow. Check the needle, the float, and the pump pressure (pump spacer).

## Gaps

- elektroda.pl was unreachable (timeouts), and the Wayback Machine had no snapshots of the Żuk threads found by search. Elektroda cases are therefore missing.
- No Tarpan, Russian, Czech or Hungarian owner cases were found. Searches returned Lada, GAZ and Suzuki Weber threads only.
- YouTube titles and descriptions gave no symptom-to-fix stories.
- Almost no case names the 34S2B1 itself. Most owners with a named type had the later 28/35, so the float and jet figures in those threads need translating before use on a 34S2B1.
