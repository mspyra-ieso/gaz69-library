# FSO S-21: Specs and Service Data

> **Superseded:** factory values (head torque 110–120 Nm, dwell 65°, timing 8° ± 1° on 85/86-octane fuel, exhaust valve clearance 0.30–0.32 mm cold, compression, Iskra F75 plug) are now in [factory-service-data.md](factory-service-data.md). Where this page disagrees, use that one.

Use this alongside the factory manuals you already have. **Where the manual disagrees with this page, trust the manual.** Each value below gives its source and is tagged:

- **[DOC]**: from a factory or manual-derived source (a scan of a manual drawing, or a club "basic adjustments" page built from the manuals).
- **[SPEC-SITE]**: from a spec database or encyclopedia. These sites often make mistakes.
- **[FORUM]**: an owner's opinion or measurement.

## Core identity

| Item | Value | Source |
|---|---|---|
| Layout | Inline 4-cylinder, OHV, pushrods and rockers, 8 valves (a development of the side-valve M-20) | [SPEC-SITE] https://pl.wikipedia.org/wiki/S-21_(silnik) |
| Bore × stroke | 82 × 100 mm, the same as the M-20 / GAZ-69 2.1 | [FORUM] https://www.drive2.ru/l/573142427284540104/ and [SPEC-SITE] https://fastcarcheck.uk/specs/make/fso/warszawa/268795. **Conflict:** the pl.wikipedia infobox says 90 × 95 mm / 2417 cc, which contradicts its own lead text (2120 cc). That is a table error. |
| Displacement | 2120 cc | multiple sources (above) |
| Compression ratio | 7.5:1 (M-20: 6.2 to 6.8) | [SPEC-SITE] pl.wikipedia (above) |
| Power | 70 hp (51 kW) @ 4000 rpm | pl.wikipedia, https://www.autocentrum.pl/dane-techniczne/fso/warszawa/223-224/silnik-benzynowy-2.1-70km-1964-1973/ |
| Torque | 147 / 150 / 167 Nm @ ~2500 rpm, depending on the source | autocentrum (147), pl.wikipedia and motoklub.pl (150). **Conflict noted.** |
| Dry weight | 188 kg | [SPEC-SITE] pl.wikipedia, https://motoklub.pl/silnik-s-21/ |
| Production | 1962 to 9 April 1993, 1,188,520 units | [SPEC-SITE] pl.wikipedia |
| Timing drive | Gear-driven. A small steel crank gear (28 teeth) drives a large **textolite/bakelite** cam gear (`koło rozrządu tekstolitowe`, 56 teeth, Ø162 mm, OE 11-6256) | shop listings: https://sklep.regmot.com.pl/kolo-rozrzadu-duze-tekstolitowe-zuk-nysa-silnik,3,14996,17115 , https://sklep.regmot.com.pl/kolo-rozrzadu-male-zuk-nysa-warszawa-silnik-s21,3,14996,12579 |
| Head fixing | Bolts, not studs (the M-20 uses studs) | [FORUM] Duplet59 on https://www.drive2.ru/l/509669270280470698/. The same post also claims the head is a "Renault" design. This is unverified and probably myth. |

## Ignition

| Item | Value | Source / notes |
|---|---|---|
| **Firing order** (`kolejność zapłonu`) | **1-2-4-3** | [DOC] https://polskiedostawczaki.pl/podstawowe-regulacje-silnikow-s-21-oraz-m-20/ ; also the GAZ-69/M-20 spec, https://www.gaz69.org/gaz/SpecPL.html ; owners on https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3243. **Conflict:** pl.wikipedia says 1-3-4-2. Treat that as an error, because the S-21 keeps the M-20 crank and cam layout and every owner/club source says 1-2-4-3. Verify against your manual. |
| Cylinder 1 | At the front (radiator end). This is standard for the family, but no source states it explicitly. | the manual is authoritative |
| Points gap (`przerywacz`) | **0.4 ± 0.05 mm** (0.35 to 0.45) | [DOC] polskiedostawczaki regulations page. The manual drawing "Rys. 16.16" shows 0.35 to 0.45 (image `distributor-points-gap-0.35-0.45-polskiedostawczaki.jpg`). GAZ-69 spec gives the same 0.35 to 0.45. |
| Dwell angle | **Not found** in any source. | GAP: check the manual |
| Static timing | **Conflict:** a factory figure of **7° BTDC** is quoted, with the author's view that modern fuel takes 7° or more ([DOC/opinion] polskiedostawczaki regulations page). **5° BTDC** is quoted by an aggregator (via search snippet, autocentrum). The GAZ-69 M-20 figure is 4° BTDC (gaz69.org). | Use the manual. In practice owners finish by ear or with a strobe and a road test. |
| TDC / timing mark | A **ball or hole in the flywheel**, seen through the **inspection window in the clutch housing** (`wziernik obudowy sprzęgła`), lined up with a pointer. Rotor points to the cyl-1 lead. | [DOC] polskiedostawczaki regulations page; image `distributor-rotor-and-flywheel-tdc-mark-polskiedostawczaki.jpg` |
| Spark plug gap | **0.6 to 0.7 mm** (GAZ-69 M-20: 0.7 to 0.85) | [DOC] polskiedostawczaki regulations page; gaz69.org |
| Spark plug type | Factory type not found online. Owner recommendation: **Denso W20TT** | [FORUM] Strucelsw, https://www.forum.polskiedostawczaki.pl/viewtopic.php?t=4718&p=57033 . GAP: factory plug type not found online. |
| Distributor | Zelmot (cap marked "Z"). GAZ/ZMZ (M-20, GAZ-69, GAZ-21) distributors fit and run, though their advance curves differ. Nysa needs an angled cap. | [FORUM] https://www.drive2.ru/l/4680224/ ; https://forum.polskiedostawczaki.pl/viewtopic.php?f=7&t=3936 ; https://www.drive2.ru/l/573142427284540104/ |
| Distributor / oil-pump drive | Oil pump and distributor share a drive. On reassembly, line up the ball/mark on the pump gear with the cyl-1 arrow at TDC, or the timing will be off. | [FORUM/blog] https://zukiemprzezswiat.pl/remont-silnika-2/ |

## Valves

| Item | Value | Source |
|---|---|---|
| **Valve clearance** (`luz zaworowy`), cold | **Intake 0.20 to 0.22 mm, exhaust 0.25 to 0.30 mm** | [DOC] polskiedostawczaki regulations page (says S-21 and M-20 values are the same) |
| Alternative quoted | Intake 0.20 to 0.22, exhaust **0.30 to 0.32** mm, cold (about 20 °C), citing "Vademecum elektrotechnika samochodowego" | [FORUM, citing a book] elektroda topic274136 (via search summary): https://www.elektroda.pl/rtvforum/topic274136.html |
| What owners actually set | **0.20 intake / 0.30 exhaust** | [FORUM] https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3243 ; https://zlombol.pl/community/technikalia-2/zuk-s21-nie-odpala-2/ |
| GAZ-69 M-20 (for comparison) | 0.23 intake / 0.28 exhaust | gaz69.org |
| Procedure | Set cold. Loosen all locknuts. Put cyl 1 at TDC on compression (flywheel mark plus rotor at cyl-1 lead). Set both valves on cyl 1, then turn the crank 180° and do the next cylinder **in firing order 1-2-4-3**. Rocking-valve shortcut: when cyl 4's valves are "rocking" (overlap), adjust cyl 1, and the same pairing applies to 3 and 2. | [DOC] polskiedostawczaki regulations; [FORUM] Strucelsw in t=3243 |
| Intake valve head Ø | 40.5 mm stock (a tuner fitted 43 mm). Stem 9 mm. | [FORUM] https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3357 |

## Cylinder head

| Item | Value | Source |
|---|---|---|
| **Head bolt sequence** | 11 bolts, tightened in a **spiral from the centre outwards**. The manual drawing numbers them: 1 = centre bottom row, 2/3 = centre top row, 4/5 bottom, 6/7 top, 8/9 bottom ends, 10/11 short ends. | [DOC] manual drawing reproduced at https://zukiemprzezswiat.pl/remont-silnika-2/ (image `head-bolt-tightening-order-zukiemprzezswiat.jpg`) |
| **Head bolt torque** | **NOT FOUND for the S-21.** The only figure online is **6.7 to 7.2 kGm (66 to 71 Nm) for the M-20**, from a GAZ-69 document page. | [FORUM] PPAS, https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=5255. **GAP: take this from your factory manual.** One rebuilder says his head torque procedure took 3 days, which suggests stages and re-torquing (t=3357). |
| Head gasket | Caring 04-00 / Regmot S21-10030302 | see parts-sources.md |

## Lubrication

| Item | Value | Source |
|---|---|---|
| Oil grade | Mineral **15W-40 or 20W-50**. The manual-era recommendation was Selectol Special 15W-40. Owners warn against modern thin synthetics and ester oils (crank rope seal, low-pressure pump). | [FORUM] Marian, Strucelsw et al., https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=2737 ; [web guide] https://selected.pl/jaki-olej-do-zuk-a03-1959-1998-ile-oleju-silnikowego-wlac-rodzaj-pojemnosc-i-specyfikacja-poradnik/ |
| Oil capacity | **About 5 to 6 L.** A guide gives 5.0 L, or 5.5 L with the filter. A forum member says 6 L. GAZ-69 M-20: 5.5 L. | selected.pl; [FORUM] phinek, t=2737; gaz69.org. **Conflict, so use the dipstick.** |
| Oil pressure | Gauge range **0.1 to 0.5 MPa** (1 to 5 bar) depending on rpm. Cold up to about 5 bar is OK. Hot at speed should be no more than about 3.5 bar. About 2 bar at cold idle is acceptable on a worn engine. GAZ-69 M-20 spec: 2 to 4 kgf/cm² at 45 km/h, 0.5 kgf/cm² at idle. | [FORUM] t=2737; Strucelsw in https://www.forum.polskiedostawczaki.pl/viewtopic.php?t=4718&p=57033 ; gaz69.org |
| Relief valve | Spring-and-plunger valve on the oil pump. A shim (about 3 mm) under the spring raised pressure for one owner. | [FORUM] https://www.forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3231 |
| Oil filter | Full-flow filter on an adapter (the M-20 had a bypass filter). Adapters exist with short or long sender ports. | [FORUM] drive2 search summary; gaz69.eu adapter listing |
| Service interval (historic) | Every 3,000 km is best; 6,000 km was common in practice. | https://motoklub.pl/silnik-s-21/ |

## Cooling

| Item | Value | Source |
|---|---|---|
| Thermostat | Factory-type units are unreliable. Owners use **72 °C** (Mery, non-bellows), **70 °C** (Volga), or 80 °C (Tavria). The engine runs at about 78 to 80 °C. | [FORUM] https://forum.polskiedostawczaki.pl/viewtopic.php?p=48279 ; https://oldpolbus.com/viewtopic.php?f=37&t=101 |
| Radiator cap | Owners report overheating with **stiff aftermarket caps**. Soft caps (Master Sport, original) cured it. | [FORUM] t=48279 thread |
| Coolant capacity | GAZ-69 system: **12 L** | gaz69.org. GAP: Żuk figure not found. |
| Fan belt tension | **10 to 15 mm** deflection under thumb pressure | [DOC] manual drawing, polskiedostawczaki regulations (image `fan-belt-tension-10-15mm-polskiedostawczaki.jpg`) |

## Fuel

| Item | Value | Source |
|---|---|---|
| Fuel pump | Mechanical diaphragm pump driven by a camshaft eccentric, with a hand primer, glass bowl and sieve | https://polskiedostawczaki.pl/regeneracja-pompy-paliwa/ |
| Fuel pump pressure | **NOT FOUND.** The article gives no figure. | GAP. Manual value expected. |
| Idle speed | **NOT FOUND for the S-21.** GAZ-69 M-20: 400 to 450 rpm. One GAZ-69 S-21 owner idles at 550 (stable 500). Duplet59 says a well-tuned S-21 will idle down to about 300 rpm. | gaz69.org; [FORUM] https://oldpolbus.com/viewtopic.php?f=37&t=101 ; drive2 509669270280470698 |
| Idle mixture procedure | At about 80 °C: screw the mixture screw fully in, then back it out 2 turns. Set the lowest even idle on the stop screw. Turn the mixture screw for maximum even speed, then reduce rpm on the stop screw. Blip test: the engine must not stall. | [DOC] polskiedostawczaki regulations |
| Carb float levels | G-35 13.7 to 15.3, SOP-40 14.5 to 16.5, Weber 28/35 S2A1 6.25 to 6.75, S2B1 6.75 to 7.25, **Weber 34S2A1/S2B1 5.0 to 5.5 mm** | [DOC] polskiedostawczaki regulations (see the Weber knowledge base for detail) |

## Compression

| Item | Value | Source |
|---|---|---|
| Compression pressure | **Factory figure NOT FOUND.** One owner measured "over 11" (likely bar) on every cylinder 10,000 km after a rebuild. A rule-of-thumb formula (0.125 MPa × ε) gives about 9.4 bar for ε 7.5; this is derived, not factory. | [FORUM] https://zlombol.pl/community/technikalia-2/zuk-silnik-s-21-nie-pali-na-jeden-gar-2/ ; formula from http://www.zssplus.pl/publikacje/publikacje37.htm |
| Last bore oversize | 83.50 mm | [blog] https://zukiemprzezswiat.pl/remont-silnika-2/ |
| Crank journal clearance measured on a good engine | 0.02 to 0.03 mm | [FORUM] t=3357 |

## Not found online (take these from your manual)

Head bolt torque for the S-21, dwell angle, factory compression pressures and wear limit, idle rpm, fuel pump pressure, factory spark plug type, Żuk coolant capacity, main and rod bearing torques.
