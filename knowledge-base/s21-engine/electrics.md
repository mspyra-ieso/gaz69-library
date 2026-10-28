# S-21: Electrics That Cause Running Problems

This page covers charging, starting, earth (ground), the ignition switch, the coil and the gauges. Labels:

- **[FACTORY]** comes from the manuals. Source keys (W65, W66e, Ż74, Ż89, Ż94, N77) are defined in `factory-service-data.md`.
- **[FORUM]** comes from owners.

GAZ-69-specific wiring reports are in `gaz69-s21-owner-reports.md` ("Charging, ignition and gauges").

## 1. Check the polarity first

| Vehicle / era | Earth polarity | Charging | Source |
|---|---|---|---|
| Warszawa 203/204 (1965–66) | **Positive earth**: "zacisk dodatni" (the positive terminal goes to earth) | DC generator **P20b** (P20a, P20f), 12 V 18 A, with an **RG15f** regulator | [FACTORY] W66e Table 93-1 pr. p.112 and Ch. 95 |
| Nysa 522 (1977) | **Positive earth**: "plus na masę" | Shunt generator **P2.Ob** 12 V / 300 W. Ambulance version: **A111a** alternator. | [FACTORY] N77 p.17 |
| Żuk (1974) | not stated in the table | Generator 12 V / 300 W | [FACTORY] Ż74 pr. p.13 |
| Żuk (1989) | **Negative earth**: "biegun ujemny (—) akumulatora połączony z masą" | Alternator **A124F2** (14 V, 44 A, 616 W), regulator **RC2/12D** | [FACTORY] Ż89 pr. p.14 |

**What this means for a swap.** An S-21 swapped into a GAZ-69 may carry a dynamo-era or an alternator-era loom, and parts from either.

- A **positive-earth** generator, regulator or coil wired into a **negative-earth** car, or the reverse, gives reverse charging, weak sparks or burnt diodes.
- The Żuk alternator manual warns about this directly: negative to earth always; jump-start in parallel only (+ to +, − to −); disconnect the battery before charging it on the vehicle; **never test the alternator by shorting its terminals to earth** (Ż89 §7.1.2).
- When exactly the Żuk/Nysa went from positive to negative earth was **not found**.

## 2. Factory electrical data

| Item | Value | Source |
|---|---|---|
| Generator (Warszawa, S-21) | P20b, 2 brushes, drive ratio **1:1.9**. Starts charging at **1300 generator rpm**. Gives **18 A at 12 V by 2100 generator rpm** when hot. | [FACTORY] W66e Table 93-1 |
| Regulator RG15f | Cut-in **12.5–13.5 V**. Maximum reverse current **up to 6 A**. No-load voltage **14.5–15.5 V**. | [FACTORY] W66e Table 93-1 |
| Alternator (Żuk 1989) | A124F2, 14 V 44 A. **Starts charging at about 1000 ± 50 rpm**. The ammeter should swing to **+**. Swinging to − as revs rise means an internal fault or an open circuit. | [FACTORY] Ż89 §7.1.1 ("Alternator zaczyna ładować akumulator przy 1000±50 obr/min") |
| Other no-charge causes (Żuk) | Blown **16 A fuse**, worn alternator brushes, loose belt | [FACTORY] Ż89 §7.1.1 |
| Belt | Deflection 10–15 mm under about 100 N. If it slips, tighten it. | [FACTORY] Ż89 §7.1.2 |
| Starter (Warszawa) | **R5c**, pinion to ring gear **9:129**. Minimum cranking torque **2.6 kGm**. Maximum draw **600 A**. 1.8 hp. | [FACTORY] W66e Table 93-1 |
| Starter (Nysa 1977) | Electromagnetic **R5c**, 12 V / 1.8 hp | [FACTORY] N77 p.17 |
| Starter (Żuk 1989) | **R11c**, 1.32 kW | [FACTORY] Ż89 pr. p.14 |
| Cables (Żuk 1989) | **Battery-to-earth: flat braided strap, 17 mm²**. **Battery-to-starter: round, 35 mm²**. Lighting: 1, 1.5 and 2.5 mm². There is a **battery isolator switch** in the battery-to-starter circuit. | [FACTORY] Ż89 pr. p.14 & §7.1.3 |
| Fuses (Żuk 1989) | One 16 A and twelve 8 A. Do not repair a fuse with wire. | [FACTORY] Ż89 pr. p.14 & §7.9 |
| Coil | Warszawa: **42-07/I**. Żuk 1994 contactless: **Zelmot 4226** (oil-filled) with an **H161 or GL118** module. | [FACTORY] W66e; Ż94 pr. p.30 |
| Battery | Warszawa 6SE50 (50 Ah). Nysa 45 Ah. Żuk 1974 51 Ah. Żuk 1989 60 Ah (AR) or 6SC45TM. | [FACTORY] |
| Capacitor | KSA-5b | [FACTORY] W66e Table 96-24 |

Image: `images/factory-warszawa-electrics-data-table-93-1-p112.jpg`.

## 3. Factory fault-finding: no spark or weak spark (W66e Ch. 97, pr. p.159–160)

Start with a charged, properly connected battery.

1. **Check the plug.** Remove it, check and set the gap, reconnect the lead, and lay the plug on the head. Crank. You want a strong, crackling blue spark.
2. **No spark at the plug.** Hold the **centre HT lead about 6 mm from earth** and crank.
   - No spark means a fault in the **coil or the low-tension circuit**.
   - A spark here, but not at the plug, points to a cracked **rotor, distributor cap or HT leads**.
3. **Low-tension check**, ignition on:
   - Look for a small spark at the points as they open.
   - Or connect a test lamp from earth to the distributor LT terminal. It should be **lit with points open** and **out with points closed**.
4. **No lamp and no spark at the points** means a fault in the feed wire, a short in the condenser, or **burnt points** (which also suggests a bad condenser).
5. **Trace the feed.** Put the lamp from **coil terminal 21 (ignition-switch side) to earth**. No light means a break in the **ignition switch-to-coil wire or the switch itself**.
6. **Test the coil primary.** With the points open, an undamaged condenser, and the lamp from **coil terminal 22 to earth**: no light means the **coil primary is open**, so replace the coil.
7. **For any other dead circuit**, use a **sharpened test-lamp probe** that pierces the insulation. Work from the consumer back toward the switch until the lamp lights. The break is between the last dark point and the first lit one.

Image: `images/factory-warszawa-electrics-ignition-fault-finding-p159.jpg`.

## 4. Factory generator and regulator fault table (W66e Table 96-23, pr. p.138)

Engine at about 1300 rpm.

| Symptom | Cause | How to confirm |
|---|---|---|
| No charge | Generator, **cut-out (wyłącznik samoczynny)** or regulator fault | Briefly bridging terminals 19 and 16 on the regulator moves the ammeter. If so, the regulator or cut-out is at fault. **Remove the bridge before stopping the engine**, or the generator windings can burn. |
| Weak charge to a flat battery | Current-limiter misadjusted | At about 2000 rpm (68 km/h in top) the generator does not give 18 A, tapering as the battery charges |
| Overcharge: battery "boils", electrolyte drops | Limiter or voltage set too high | Current does not fall to near zero once the battery is full |

## 5. Owner cases: electrics

Full entries are in `owner-reports-2.md`.

| # | Symptom | Cause / fix | Status | Source |
|---|---|---|---|---|
| E-1 | Starter does two slow turns, pauses and repeats, even after a regenerated starter and new ignition switch. Sparks at the clutch-pedal spring. | **The engine had no earth.** The clutch housing had been painted, so the earth path ran through the clutch spring. Fixed with a lead from battery − to the engine. | CONFIRMED | [FORUM] https://forum.polskiedostawczaki.pl/viewtopic.php?f=7&t=2295 ("Silnik nie miał masy.") |
| E-2 | Starter only clicks | Sticking solenoid: tap it lightly. Clean the battery clamps, cables, starter terminals and frame earth. | CONFIRMED (cleaning) | [FORUM] same thread ("poknij czyms lekko po elektro magnesie") |
| E-3 | Weak cranking, lights die when the key is turned, ignition switch won't hold position 2, no charging | Replace the **ignition switch** first. Check the battery and isolator. Run a **new earth directly to the engine**. | SUGGESTED | [FORUM] https://forum.polskiedostawczaki.pl/viewtopic.php?f=7&t=4257 ("stacyjka jest uszkodzona i zacznij od wymiany.") |
| E-4 | After an alternator swap: fuse blew, no charging, no indicators | The wire to the gauges and regulator fuse had **burnt inside its insulation** | CONFIRMED | [FORUM] t=4257 ("wypalił się w środku przewód idący do bezpiecznika") |
| E-5 | General | **The Żuk has no factory body-to-frame earth, so make one.** On the S-21 the earth strap can go to one of the **two upper clutch-housing bolts**. | SUGGESTED (experienced members) | [FORUM] t=4257 ("żuk nie ma jednej masy- z nadwozia na rame, trzeba ją dorobić.") |
| E-6 | 9-diode alternator: about 12.5 V at idle, lights flickering | Excitation was wired from switched + instead of **through the charge warning lamp**. Rewired to the correct diagram. | CONFIRMED (alternator OK) | [FORUM] https://forum.polskiedostawczaki.pl/viewtopic.php?f=7&t=578&start=90 |
| E-7 | 9-diode alternator does not charge | The **warning lamp must be 12 V / 4 W**. A smaller bulb gives too little excitation, so no charge. | [FORUM] tech note | https://forum.polskiedostawczaki.pl/viewtopic.php?f=7&t=578 ("żarówka koniecznie 12V/4W") |
| E-8 | Temperature gauge pegs at maximum seconds after a cold start | Most likely the **sender**. Otherwise a chafed sender wire shorting to earth, or a rusty or loose sender terminal. | SUGGESTED | [FORUM] https://forum.polskiedostawczaki.pl/viewtopic.php?f=7&t=2888 ("jeśli zwiera domasy to wskazówka od razu idzie na maksa") |
| E-9 | Charge and other gauges wander | The gauges are only about ±10 % accurate. The charge needle swings when the lights are switched on. Nysa used gauges until 1983, then warning lamps. | [FORUM] tech note | t=578 ("te wskazniki w zukach tak sobie dzialaja") |
| E-10 | Alternator bearing or whine | The alternator turns at about **10,000 rpm** on the S-21 (ratio about 2.5). Use **C3 / 2RS** bearings and avoid cheap ones. | [FORUM] tech note (not archived offline) | https://forum.polskiedostawczaki.pl/viewtopic.php?f=7&t=578&start=30 |
| E-11 | Starter part interchange | The S-21 starter is **the same as on the Ursus C-328 tractor**. The 4C90 diesel starter is different. | [FORUM] | t=2295; https://forum.polskiedostawczaki.pl/viewtopic.php?f=7&t=2655 |
| E-12 | Regulator suspected | Bench test: feed + **straight to the brushes**. If the voltage rises above 14 V, the alternator is good and the regulator is bad. If there is voltage across the rotor brushes but still no charge, the fault is in the alternator, not the regulator. | [FORUM] tech note | t=4257; t=578&start=90 |

Already in the knowledge base (not repeated here):
- coil choice (4226 vs Bosch) and ignition modules: `ignition-and-mods.md`;
- alternator bearings and brushes noise: `owner-reports.md` OR-60;
- the swap's ammeter-to-voltmeter conversion: `gaz69-s21-owner-reports.md`.

## 6. Quick electrical checklist for a rough-running or no-start S-21

1. **Battery and voltage.** About 12.6 V at rest. On cranking it should not collapse; the Warszawa starter can draw up to 600 A. Running voltage: about 14 V (alternator) or 14.5 V and below (RG15f dynamo regulator). [FACTORY] W66e, Ż89
2. **Earths.**
   - Battery to body/frame, frame to **engine** (a 17 mm² braid on the Żuk).
   - Clean paint off under the strap.
   - Add the missing body-to-frame earth (E-1, E-5).
   - On a GAZ-69 swap the engine sits on rubber mounts, so the strap is the *only* earth path.
3. **Ignition switch feed.** Use the lamp test from coil terminal 21 to earth (§3, step 5). Check that the switch holds position (E-3).
4. **Points, condenser and coil.** Use the §3 lamp tests. Points gap 0.35–0.45 mm, then time with a lamp ([FACTORY] Ż89 pr. p.51).
5. **Polarity.** Check it matches the generator or alternator, regulator and coil (§1).
6. **Gauges.** Before believing a "hot" or "no oil pressure" reading, check the sender and its wire. A short to earth sends the needle to maximum (E-8). Confirm with a mechanical gauge or infrared thermometer.

## Gaps

- No factory data was found for the **oil-pressure and temperature senders** (resistance values).
- elektroda.pl was unreachable during this research (connection timeouts), so no elektroda electrics threads were added. See `sources-gaps.md`.
- The date of the switch from positive to negative earth on Żuk and Nysa was not found.
