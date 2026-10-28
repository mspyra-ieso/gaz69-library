# Weber 28/35: parts interchangeability and complete-carb alternatives

Labels: [FACTORY], [BOOK], [FORUM], [SHOP], [GENERAL].

**Confidence key:**
- **PN match:** the same factory part number appears for both carbs. Strongest evidence.
- **Seller:** a shop lists the part for both.
- **Owner:** one or more owners did it.
- **Inference:** reasoning only.

## 1. The family: Polish Webers share a body "platform"

- **[FACTORY/FORUM]** phinek, FPD t=2439 (2015), citing a **1982 POLMO catalogue**: the S-21 carb and the Polonez carb "miały te same korpus" (had the same body). He listed how the 34S2B1 differs from the 34 DCMP: same 34 mm bore and 4.5 auxiliary venturi, but a 25 mm venturi that the Polonez never used. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=2439&start=15
- **[SHOP] ETER-MOT** sells **one new cover** listed for "Weber 28/35 S2A, 34 DCHD, 34 DCMP, 34 S2C, 34 S2A, 34 S2B". Application: "Fiat 125p, Żuk (ST i NT)". Price 200 zł. https://eter-mot.abc24.pl/produkt/921305-gaznik-weber-28-35-s2a-34-dchd-34-dcmp-34-s2c-34-s2a-34-s2b-pokrywa (photo `images/w-etermot-shared-cover-28-35-34dchd-34dcmp.jpg`, with cover and base gaskets)
  - ETER-MOT **also** sells a separate "28/35 S2A1 pokrywa (Nysa, Żuk)" at 200 zł, and a "34 DCMP, 34 S2C" cover for the Polonez. So not every cover fits every body. ⚠ **Compare the gasket outline, the starter-circuit drillings and the fuel-inlet position with your own cover before buying.** https://eter-mot.abc24.pl/produkt/511335-gaznik-weber-28-35-s2a-1-pokrywa-nysa-zuk
- **[SHOP] ETER-MOT throttle levers** for spindle I and spindle II are listed for "34 DCHD, 34 DCPM, 34 S2C, 34 S2A1, 34 S2B1, 28/35 S2A1". https://eter-mot.abc24.pl/produkt/935411-gaznik-weber-34-dchd-34-dcpm-34-s2c-34-s2a-b-1-28-35-s2a1-dzwignia-osi (photo `images/w-etermot-shared-throttle-lever-dchd-dcmp-28-35.jpg`)
- **[FORUM] Strucelsw:** on the Polonez DCMP the crankcase-breather connection differs. The thin hose from the air-filter breather goes to the stub by the primary spindle, and the original stub by the piston is blanked (FPD t=777, 2022). So the bodies are close but **not identical**. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&p=59754#p59754

## 2. Part-by-part table

| Part | 28/35 factory PN (CAT88) | Also used on | Evidence | Notes |
|---|---|---|---|---|
| **Cover gasket** | 9914774 | Fiat 125p / Polonez "ST" Weber | **PN match.** roda24 "Uszczelki gaźnika FSO, PN ST kpl." (Ajust FP040) gives "Numery OE: 4127681 (uszczelka podstawy), 9914774 (uszczelka pokrywy)". https://sklep.roda24.pl/uszczelki-gaznika-fso-pn-st-kpl-2865.html (photo `images/w-roda24-fso-pn-gasket-set-4127681-9914774.jpg`) | 16 zł. The best-evidenced cheap source of the two key gaskets |
| **Base gasket (manifold stack)** | 4127681 (×2, table 11.10) | Fiat 125p / Polonez ST | **PN match**, same roda24 set | The insulating spacer 4127682 is not in that set |
| **Cover piston** [tłoczek] | 9909233 (item 5) | Fiat 125p cover "zaworek podciśnieniowy" | **PN match.** roda24 Art-Mobil kit 3441 contains 9909233 + spring **017545**. https://sklep.roda24.pl/zestaw-naprawczy-pokrywy-gaznika-fso-3441.html (photo `images/w-roda24-fso-cover-kit-9909233.jpg`) | ⚠ The spring differs: the 28/35 uses 9909234. Fit the piston, but keep your own spring unless you have checked it |
| **Throttle levers I / II** | 702-1107019 (item 64) | 34 DCHD, DCMP, 34 S2C, 34 S2A1/B1 | Seller (ETER-MOT) | 25 zł each |
| **Cover** | 9914773 (S2A1); 437.28.010.02 (S2B1) | 34 DCHD, 34 DCMP, 34 S2C, 34 S2A/B | Seller (ETER-MOT, see §1) | Check carefully; the S2B1 cover differs (`variants.md`) |
| **EZ-20 solenoid** | 033845 + jet 45 (033842) + ring 033844 | Fiat 126p, Polonez Webers | Seller (roda24: "Elektrozawór gaźnika Fiat 126p, PN" = WSK Poznań EZ-20) and owner (FPD t=4635) | **Fit the 45 jet.** 126p units often carry 50 or other jets. Details in `solenoid-ez20.md` |
| **Plain idle-jet holder** (solenoid substitute) | — | FSO, PN, 126p | Seller: roda24 "Dysza wolnych obrotów 45 FSO, PN, 126p ST kpl." https://sklep.roda24.pl/dysza-wolnych-obrotow-45-fso-pn-126p-st-kpl-387.html | No run-on protection |
| **Main / air / idle jets** | Weber series 738 / 775 / 744 (e.g. 73805110, 77502250) | All Weber-family carbs with the same thread | Inference from Weber numbering (73805xxx = main jet, 77502xxx = air jet) | The thread and length must match. **Only the size number matters** for calibration. Read the stamp |
| **Emulsion tubes F27 / F35** | 61455140 / 021596 (S2B1: 61.455.153) | Weber F-series tubes (Fiat) | Inference | **Do not substitute** a different F number without testing |
| **Float** | 9911187 | — | Not established | The Art-Mobil and ETER-MOT kit photos show brass floats. Weigh before fitting (18 g) |
| **Needle valve 175** | 9911186 | — | roda24 kit names OE 9911186 | Strucelsw's suggestion of a Solex valve with a spring and a 2 mm seat is an **owner mod** (`wear-and-inspection.md` §3) |
| **Oversize primary spindle 8.2 mm** | 4323406702 | — | Seller (roda24 Art-Mobil kit, GN.17.17 / 014139) | The roda24 125p kit carries 125p jets: **check every jet** |
| **Air filter** | — | Fiat 125p type | [FACTORY] 1976 Żuk manual: the Weber version used a "filtr powietrza … typu Fiat 125P, suchy, z wymiennym wkładem". https://archive.org/download/fsc-lublin-instrukcja-obslugi-zuk/FSC_LUBLIN-1976-instrukcja_obslugi_Zuk.pdf | A 125p-style "pan" (patelnia) air filter fits the Weber top. nysanek also mentions putting the 125p "puszka" on a Jikov adapter (FPD t=1250). https://forum.polskiedostawczaki.pl/viewtopic.php?f=1&t=1250 |
| **Repair kits for FSO / Polonez** | — | 125p / Polonez | Seller | ⚠ **Not** for the 28/35 calibration: jets 115/135/210/225 (`rebuild-kits.md`) |
| **Kits for 34S2A1 / 34S2B1** | — | the older Żuk 34 carb | Seller | Different venturis and float level. Not for the 28/35 |

## 3. What does NOT interchange (or needs care)

- **Venturis 21 / 26 and the 28 / 35 mm throttle plates.** These define the carb. The 34-series bodies have 34 mm bores and different venturis (`variants.md`).
- **Jets between throats.** I and II differ in size and in emulsion tube.
- **The S2B1 economiser.** It is only on the S2B1; an S2A1 body has no drillings for it.
- **126p solenoid jets other than 45.** They change the idle mixture.
- **The "zawór hamowania silnikiem" (engine-braking fuel cut-off diaphragm) on Fiat / Polonez carbs.** Marian (FPD t=2439) says it **never existed** on Żuk / Nysa carbs. Strucelsw calls it troublesome and hard to set, saving about 5 %. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=2439&start=15

---

## 4. Complete-carb substitutes owners fitted to the S-21

| Substitute | Fit on the S-21 manifold | Outcome reported | Adaptation needed | Source |
|---|---|---|---|---|
| **Weber 34S2B1** (older factory Żuk carb) | Direct (same manifold family) | [FORUM] Strucelsw rates the 34-series as the best of the Żuk Webers. He prefers the bigger venturis for power; the 28/35 is the economy carb | Its own jets and float level (5–5.5 mm). See `../weber-34s2b1/` | FPD t=2439, t=4279 |
| **Polmo / FOS 34 DCMP** (Polonez 1.5 before 1986) | Fits (same body family) | [FORUM] "będzie chodził, ale wymaga innych dysz" (it will run, but needs other jets). The owner (DenysG) fixed his engine with it after also sealing a manifold leak | Strucelsw's jets: **I: main 115, air 225–230, idle 45. II: with a 26 mm venturi, main 145–155; with 24 mm, 125 or 135.** Re-route the breather hose | FPD t=777 (2022–23). https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&p=59754#p59754 |
| **Fiat 125p 34 DCMP / DCHD** | Fits | [FORUM] Daniel22 ran an S-21 on a 125p 34 DCMP with "fiatowskie" jets and was asking whether to look for a Nysa carb. Strucelsw: re-jet as above | Re-jet. DCHD versions have a **vacuum (pneumatic) secondary** and a different float setting | FPD t=777 (2022) and t=2908 (Strucelsw on the DCHD and DCMP float). https://forum.polskiedostawczaki.pl/viewtopic.php?f=23&t=2908 |
| **Jikov 40 SOP** (single-throat, factory option 1970s) | Factory fitting on its own manifold. ETER-MOT sells a **Jikov 40 SOP → Weber 28/35 S2A1 adapter plate** (100 zł) | Fitted at the factory (1974 / 1976 Żuk manuals). ⚠ Opinions conflict. A Warszawa owner (Jacek B., syrena.nekla.pl t=10451) finds the **Weber gives more power but uses more fuel**, and the Jikov the reverse. Polish Żuk owners mostly say the opposite: "Zostaje Weber. Argument mniejsze spalanie" (the Weber stays; the argument is lower consumption), Klamot, FPD t=777, 2016. https://syrena.nekla.pl/forum/viewtopic.php?t=10451 | Different manifold flange; adapter plate | ETER-MOT https://eter-mot.abc24.pl/produkt/397656-nakladka-redukcja-z-gaznika-jikov-40-sop-na-weber-28-35-s2a1-zuk (photo `images/w-etermot-jikov40sop-to-weber-28-35-adapter.jpg`); 1974 manual https://archive.org/download/fsc-lublin-instrukcja-obslugi-zuk/FSC_LUBLIN-1974-instrukcja_obslugi_Zuk.pdf |
| **Jikov 32 SEDR** (twin-throat) | Same manifold as the Weber (owner Kamael, FPD t=2439) | [FORUM] Strucelsw: SEDR/EDSR carbs are "dość kapryśne" (fairly temperamental), with small bores (except the Tatra 613 version, 2 × 27 mm). Their one advantage is a better idle circuit with a bypass channel. Poncki: consumption similar to the Weber | — | FPD t=2439 https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=2439&start=15 ; t=5069 |
| **Jikov (type not given) on a Żuk** | — | [FORUM] Drewniany, 2021: a regenerated Jikov started and idled well but **choked above 1/3 throttle**. He then waited for the original carb | — | FPD t=3139 https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3139 |
| **Twin motorcycle carbs** (Strucelsw's own Nysa) | Custom manifold | [FORUM] Done to cure **fuel starvation on steep slopes** (central float chamber) | Major conversion | FPD t=2439 (2015) |
| **Pierburg 2E / 2EE** | Not reported on an S-21 | [FORUM] juR went the **other way**: he put a 28/35 S2A on a Mercedes M102 to replace a dead Pierburg 2EE, saying "pierburg 2ee nie ma podejścia" (the Pierburg can't compare). Strucelsw also prefers the Weber to the Pierburg ("pier(d)burg") but says Solex units use less fuel | — | FPD t=4279, t=4635 https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4635&start=15 |
| **Solex 2108 (Lada Samara) parts** on a GAZ-69 S-21 with a Weber | — | [FORUM, drive2] A Kyiv GAZ-69 owner adapted the **2108 throttle sector and cable** to the Weber, shortening the spindle spacer bush so the sector fitted | Linkage only, not the carb | https://www.drive2.ru/l/575155907952902834/ |
| **Chinese "Beijing" (BJ212) twin-throat carb** on a GAZ-69 | — | [FORUM, drive2] Only planned by a Belarusian GAZ-69 owner ("карбюратор из Китая от Пекина", a carb from the Chinese Beijing jeep) on a single-barrel Jikov car. No result was found | Unknown | https://www.drive2.ru/l/548646957485131028/ ; https://www.drive2.ru/l/553391075281076709/ |
| **Russian K-126 / K-151, Solex, Weber 32/36 DGV** | — | **No S-21 owner report found** in Polish or Russian sources searched (FPD searches for "k126" and "solex" returned nothing relevant) | — | Gap |

### Strucelsw's view on sizing (FORUM, worth reading together)
- The 28/35 has "za małe gardziele" (venturis too small) for a 2.0-litre Mercedes engine. It suits about **1.3 l**; for 1.6 he would use the Polonez 1.5 DCMP. FPD t=4279 (2018), https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4279
- On the S-21 the small 21 mm first venturi is deliberate, for economy and mixing at part load. He sees the S-21 as "niewysilony, średnioobrotowy" (an unstressed mid-rpm engine). The 28/35 is a bit more flexible than 2 × 25 but loses at the top end (t=4279, 2019).

### ⚠ Conflict: the 34S2B1 venturi size
- Strucelsw (t=2439, 2015) wrote that the 34S2B1 "ma gardziele 24 i 26mm".
- The **factory** 1985 manual and phinek's 1982 catalogue figures give **25 / 25 mm** (`variants.md`, `../weber-34s2b1/specs-and-jets.md`).
- The 24 / 26 figure matches the Polonez 1.5 DCMP. **Use the factory value.**

## 5. Practical advice for a GAZ-69 owner

1. **Keep the 28/35** unless the body is worn out. It is the factory-matched economy carb for the S-21, and parts are still sold (`rebuild-kits.md`).
2. **The cheapest robust spare** is a second 28/35 or a 34S2B1. A **pre-1986 Polonez 34 DCMP** is the fallback, re-jetted to Strucelsw's figures. All three mount the same way (forum consensus; not tested on a GAZ-69 manifold).
3. **Off-road angles.** Poncki, who drives a "Gazik", reports that the Weber "źle znosi przechyły" (copes badly with tilt): it can stall on climbs. Turning it 180° moves the problem to descents and needs linkage changes. https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=2439&start=15
   - No factory carb in this family has a central float chamber (Strucelsw).
   - Treat a stall on a steep climb as a known limitation, not a fault (see `ownership-experience.md`).
