# S-21: Common Problems from Owners (symptom → cause → fix)

Tags: **[FORUM]** means owner opinion or experience. **[DOC]** means a manual or club guide. Names are the forum users who made the claim.

## 1. Overheating (`przegrzewa się`)

This is the most-discussed S-21 fault. Owners' usual order of suspects:

| Symptom | Likely cause | Fix | Source |
|---|---|---|---|
| Engine hot, radiator cold or lukewarm | Thermostat stuck or clogged. Owners say original-type thermostats are unreliable. | Replace with a 70 to 72 °C unit (Mery 72 °C non-bellows, or Volga 70 °C trimmed). Some owners run without a thermostat and use the radiator blind (`żaluzja`) in winter. Another workaround is to drill a 1 mm bleed hole. | [FORUM] Strucelsw, nysanek, OLO: https://forum.polskiedostawczaki.pl/viewtopic.php?p=48279 ; Volga thermostat: https://oldpolbus.com/viewtopic.php?f=37&t=101 |
| Overheats on the highway, cools down in town; rear cylinders hottest; head gasket blown between cylinders | **Corroded coolant distribution tube inside the head** (`rurka rozprowadzająca wodę w głowicy`) starves cylinders 3 and 4 and the exhaust seats | Pull the head. Make a new tube from ½" copper pipe. Straighten the channel and skim the head. | [FORUM] Sebas88, Strucelsw, nysanek, t=48279 thread |
| Overheats, thermostat won't open properly | Small bypass hole at the **front of the head gasket** clogged | Clean it when the head is off | [FORUM] Klamot, Strucelsw, t=48279 |
| Overheats after fitting a new radiator cap; upper hose collapses | **Cap too stiff.** Gas pocket forms and thermostat can't open. | Soft-spring cap (Master Sport or original) | [FORUM] Strucelsw, nysanek, Dziwny Mag, zukostrazak, t=48279 |
| Temperature climbs slowly over weeks; popping in exhaust | **Ignition slightly too early or too late.** Also a lean mixture, or worn points. | Set timing (in one case it was slightly advanced and setting it fixed the fault), check points and condenser | [FORUM] SEBRIGHT outcome, chrapek3011, marek: https://retrotraktor.pl/forum/viewtopic.php?t=6764 |
| Overheating plus steam smell, coolant loss | Cracked heater hose, clogged expansion-tank hose, low coolant | Replace hoses, flush radiator (citric acid preferred over descaler) | [FORUM] ja_tej, Marian, phinek: https://www.forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=1708 |
| Gauge reads normal while engine is actually hot | Gauge or sender unreliable | Verify with an IR thermometer | [FORUM] OLO, Strucelsw, t=48279 |
| Externally clean radiator still overheats | Internally scaled radiator | Clean or replace | [FORUM] grzegorz 1969, retrotraktor t=6764 |

## 2. Low oil pressure (`niskie ciśnienie oleju`)

| Symptom | Cause | Fix | Source |
|---|---|---|---|
| Pressure about 0.2 regardless of rpm, drops when hot | Weak relief-valve spring or worn plunger; worn pump gears; scored pump cover | Clean the relief valve. Shim the spring (3 mm worked for one owner; **do not stretch the spring**). New gear set (about 35 zł) or "rich" repair kit. | [FORUM] https://www.forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3231 ; https://zukiemprzezswiat.pl/remont-silnika-2/ |
| About 2 bar cold idle | Normal for a worn engine (Strucelsw); "fairly worn" (atom1) | Accept. Do not push above about 3.5 bar hot (risk of washing the bearings). | [FORUM] https://www.forum.polskiedostawczaki.pl/viewtopic.php?t=4718&p=57033 |
| Pump removed, then ignition timing lost | The oil pump drives the distributor | Line up the pump-gear ball with the cyl-1 arrow at TDC before refitting. Don't crank with the pump out. | [FORUM] t=3231; [blog] zukiemprzezswiat |

## 3. Oil leaks and consumption (`wycieki`, `bierze olej`)

- **Rear main seal** is a known leak point. One rebuilder enlarged the drain hole in the lower bearing shell from 3.5 to 6 mm to reduce pressure at the seal. This is experimental, and the admin questioned it. [FORUM] https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3357
- **Sump leaks all round**: fit and tighten the lower clutch cover (`dolna pokrywa sprzęgła`) **before** the oil pan. A crooked cover makes the pan leak. [FORUM] zbyszek99, t=3357
- **Sump bolts**: retighten gradually and evenly in sequence. Loose bolts are a rare cause. [FORUM] moderator, https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3744
- **Some seepage is "normal for this design"**. A thin film of high-temp silicone on gaskets and PTFE tape on drain plugs helps. [blog] https://zukiemprzezswiat.pl/remont-silnika-2/
- **Ester synthetic oils** are said to attack the crank seal. Stay on mineral 15W-40 or 20W-50. [FORUM] Strucelsw, https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=2737
- **Heavy oil consumption plus scoring and 0.5 mm piston play**: one owner blamed a leaking or missing air-filter element (dust ingestion). [FORUM] Klamot, Strucelsw, t=48279
- **Seals or rings?** Smoke on cold start and after idling or overrun points to valve-stem seals. Smoke under load plus low compression points to rings. Do a wet test. [general guide] https://perfectauto.pl/awarie/uszczelniacze-zaworowe-objawy-uszkodzenia/
- **Crankcase ventilation hose** must go to the correct carb fitting (below the idle valve) on conversions. [FORUM] Duplet59 comment, https://www.drive2.ru/l/573142427284540104/

## 4. Head gasket (`uszczelka pod głowicą`)

- Blown between cylinders, linked to the corroded internal water tube (see 1). [FORUM] Sebas88, t=48279
- Blow-by or seepage at the head gasket suspected as a cause of misfire. [FORUM] jacek44, t=4718
- Replacement: follow the centre-out 11-bolt sequence (image `head-bolt-tightening-order-zukiemprzezswiat.jpg`). Torque value comes from the manual; it was not found online. Check the head and block for flatness, and skim if needed.

## 5. Ignition problems (`zapłon`)

| Symptom | Cause | Fix | Source |
|---|---|---|---|
| No spark or intermittent spark | **Oil vapour on the points** | Wash the distributor in extraction benzine, clean the points, re-gap to 0.4 mm, then re-time | [FORUM] moderator, https://zlombol.pl/community/technikalia-2/zuk-s21-nie-odpala-2/ |
| Floods, won't fire, plugs wet | **Bad new spark plugs** (cheap brand) | Swap for known-good plugs. Dry fouled plugs on a gas flame. | [FORUM] same thread (final cause) |
| Misfires, weak spark | Condenser (`kondensator`), "a weak point in the Żuk" | Replace the condenser | [FORUM] marek, retrotraktor t=6764 |
| Weak spark | Coil earth, condenser | Screwdriver gap test: spark should jump several mm | [FORUM] Gniotsa Nie Łamiotsa, https://zlombol.pl/community/technikalia-2/zuk-silnik-s-21-nie-pali-na-jeden-gar-2/ |
| Erratic timing, misfire | **Distributor shaft side play**, worn distributor (common at high mileage) | Recondition or replace the distributor; GAZ/ZMZ units fit | [FORUM] Bahama Yellow (zlombol); https://www.drive2.ru/l/4680224/ |
| Misfire after electronic conversion | Coil 4226 "scatters" | Use a Bosch VW 0 221 122 349 coil | [FORUM] Strucelsw, https://forum.polskiedostawczaki.pl/viewtopic.php?f=7&t=3936 |
| Backfire through carb / exhaust | Timing too early / too late | Re-time | [DOC] https://polskiedostawczaki.pl/podstawowe-regulacje-silnikow-s-21-oraz-m-20/ |

## 6. Dead cylinder (`nie pali na jeden gar`)

Owners' checklist from one case where the cause was not found ([FORUM] https://zlombol.pl/community/technikalia-2/zuk-silnik-s-21-nie-pali-na-jeden-gar-2/):

1. Swap the HT lead and plug between cylinders.
2. Check whether the plug comes out wet (fuel arriving) or dry (intake valve not opening).
3. A compression test **does not prove the intake valve opens**. Remove the rocker cover and watch the rocker, pushrod and valve move. Look for a bent or broken pushrod, a broken rocker, or a **worn cam lobe**.
4. Check distributor shaft play and the cam lobes on the breaker.

## 7. Timing gear (`koło rozrządu`)

- The large cam gear is **textolite/bakelite**. Worn gears retard the cam and ignition, which causes loss of power and running hot. Replace the large gear (and often the small steel gear) at rebuild. [FORUM] marek, retrotraktor t=6764; [blog] https://zukiemprzezswiat.pl/remont-silnika-2/ ; parts: https://sklep.regmot.com.pl/kolo-rozrzadu-duze-tekstolitowe-zuk-nysa-silnik,3,14996,17115
- Russian-made copies of the large gear (56 teeth) are on sale. Check the OE number. [shop] regmot listing (search snippet)

## 8. Fuel pump (`pompa paliwa`)

| Symptom | Cause | Fix | Source |
|---|---|---|---|
| No fuel after running the tank dry uphill | Debris sucked into the pump; **failed suction valve** (a new diaphragm alone didn't fix it) | Clean the pump and replace **both valves** (cardboard gaskets are OK in an emergency). Hand-prime with the engine positioned so the lever is down. | [FORUM] KrzysiekH, Marian: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=195 |
| Low or no delivery | Cracked diaphragm (most common), leaky valves, worn lever, clogged bowl | Rebuild kit | [DOC/club] https://polskiedostawczaki.pl/regeneracja-pompy-paliwa/ |
| Flooding | Blocked return channel, so pressure too high | Clean | same |
| Oil leak at the pump | Gasket or spacer | Spacer of the correct thickness plus high-temp silicone | same |
| Fuel starvation | Clogged tank vent | Clear the vent | [general] search summary |

Owner tips: fit an inline filter. Owners disagree on placement: Marian puts it after the pump, Strucelsw before. A return line (5 to 6 mm) back to the tank steadies supply. An electric pump works and is quieter. [FORUM] t=777

## 9. Vibration and rough running

- Previous owner reported vibration and bought polyurethane mounts. The rebuild found con-rod caps differing by about 30 g. Rods were balanced and straightened. [FORUM] https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3357
- Design limits: the crank is weakly supported, the stroke is long, and valve springs and pushrods are weak, so treat about 4500 to 4800 rpm as a practical ceiling. [FORUM opinion] https://forum.autokacik.pl/topic/156409-s%C5%82awny-silnik-s-21-z-samochod%C3%B3w-%C5%BCuk-nysa-warszawa-tarpan/ ; Strucelsw t=3357
- One GAZ-69 S-21 owner advises keeping it under about 2100 rpm for economy and longevity. This is an individual opinion. [FORUM] Duplet59, https://www.drive2.ru/l/573142427284540104/

## 10. Other rebuild findings

- A seized **spigot bearing in the crank** (supports the gearbox input shaft) drags the input shaft and causes gear grinding. Use a 2RS **C3** bearing. [blog] https://zukiemprzezswiat.pl/remont-silnika-2/
- Aluminium sump half-ring damaged by over-tightening. [blog] same
- Exhaust manifold cracks. The exhaust heat-riser flap (`zawór grzewczy`) can rattle loose. [FORUM] https://www.drive2.ru/l/573142427284540104/ ; marek, t=6764
- Fan belt tore after looking worn: carry a spare. [FORUM] https://oldpolbus.com/viewtopic.php?f=37&t=101
- Charging lost after a regulator swap (mechanical regulator replaced with a Jezpol 2 electronic one). Check alternator brush wires. [FORUM] jacek44, t=4718
