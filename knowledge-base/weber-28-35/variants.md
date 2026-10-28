# Weber/FOS 28/35: variants S2A, S2A1 and S2B1

The source keys are defined in specs-and-jets.md. The main ones:
- **CAT88:** 1988 Żuk parts catalogue, tables dated 1987-05.
- **BI11** and **BI12:** the 1991 catalogue bulletins.
- **Z89** and **Z94:** the 1989 and 1994 Żuk owner's manuals.
- **WZ:** the Wiejak & Zagaja Żuk book.
- **FPD:** forum.polskiedostawczaki.pl.

Labels: [FACTORY], [BOOK], [SHOP], [FORUM].

## 1. What "28/35" means

- The numbers are the **throttle bores**: **28 mm primary and 35 mm secondary**.
  - [FACTORY] CAT88 items 34–35: "Przepustnica I przelotu (ø 28 mm)" and "Przepustnica II przelotu (ø 35 mm)".
  - [BOOK] WZ gives the nominal mixing-chamber diameters as 28 and 35 mm.
- The venturis inside are smaller: **21 mm and 26 mm**.
- By comparison, the older **34S2B1** has 34/34 mm bores with 25/25 mm venturis (Z85).
- [FORUM] Strucelsw (FPD t=4279) explains why the Żuk got a small 21 mm first venturi: better mixing and lower consumption at part load, at the cost of top-end power.

## 2. Timeline

| Date | Event | Source |
|---|---|---|
| June 1986 | 28/35 S2A1 with solenoid introduced on Nysa and Żuk: "od czerwca 1986 wprowadzony do sam. nysa / zuk" | [FORUM] nysanek, FPD (search snippet, 2009). Medium; consistent with CAT88 |
| 1987-05 | Parts-catalogue tables show "Gaźnik dwuprzelotowy 28/35S2A1 kpl." 702-1107010-2 with EZ-20 | [FACTORY] CAT88 table 11.07 |
| 1987-05 | Engine table 10.00 footnotes some Weber engines "Z gaźnikiem 28/35S2A"; the others are older Weber (34S2B1) engines | [FACTORY] CAT88 table 10.00 (`t-s21-engine-table-28-35s2a-catalogue-1988.jpg`) |
| 1989 | Owner's manual describes the "28/35S2A" with EZ-20, using the S2A1 jets | [FACTORY] Z89 |
| 1991 (Bulletin 11) | "Wprowadzono nowy, oszczędny gaźnik 28/35S2B1 /od 01.01.91./" (a new economical carb) | [FACTORY] BI11 |
| Sept 1991 (Bulletin 12) | S2B1 introduction postponed: "przesunięto termin wprowadzenia". The new date is **1 April 1992** | [FACTORY] BI12 (`t-28-35-s2b1-introduction-dates-bulletins-1991.jpg`) |
| 1992 | WZ book: the S-21 uses "28/35 S2A1 or 28/35 S2B1" | [BOOK] WZ |
| 1994 | Owner's manual describes only the 28/35 S2B1 | [FACTORY] Z94 |

**Practical reading:**
- A Żuk or Nysa S-21 built roughly mid-1986 to early 1992 left the factory with the **S2A1** (the manuals also call it S2A).
- Later petrol S-21 vehicles got the **S2B1**.
- Carbs have been swapped many times since, so look at the carb itself.
- Nysa and Tarpan factory documents for the 28/35 were **not found**. Shops say the same carb fits Żuk, Nysa, Tarpan and Warszawa.

## 3. S2A versus S2A1: no documented difference

- **Factory documents use both names for one carb.**
  - CAT88 (1987-05) calls the complete carb "28/35S2A1" in its carburettor tables, but "28/35S2A" in the engine-table footnote.
  - Z89 calls it "28/35S2A", with the same calibration as CAT88's S2A1: 110/145, 250/225, F27/F35, 45/100, EZ-20.
- [SHOP] roda24 sells units with body marking "28/35 S2A, GN.1113" for Żuk/Nysa/Warszawa/Tarpan, new with "elektrodysza". https://sklep.roda24.pl/en/6796.html and https://sklep.roda24.pl/gaznik-weber-zuk-nysa-warszawa-regenerowany-2830.html
- [FORUM] zlombol.pl claims the 28/35 S2A exists in "ver.1" and "ver.3", with the version number stamped on the other side of the body. It also gives different emulsion-tube marks (6/2 vs 5/3, 5/4). No factory confirmation; low confidence. https://zlombol.pl/community/technikalia-2/gaznik-weber-28-35-s2a-zuk-problem-2/
- **Conclusion:** treat S2A and S2A1 as the same calibration unless your carb has non-factory parts. The trailing "1" may be a sub-version or production code that the documents do not explain. **Unresolved.**

## 4. S2A1 versus S2B1: documented differences

Sources: CAT88 versus BI11 and Z94.

| Feature | S2A1 | S2B1 |
|---|---|---|
| Secondary main jet | 145 | **125** |
| Secondary air-correction jet | 225 | **220** |
| Economiser on throat II [oszczędzacz] | none | **yes**: gravity type, jet 80, nozzle 2.5; adds fuel past half-open secondary |
| Float distance (no gasket) | 6.25–6.75 mm | **7 ±0.25 mm** |
| Mixture screw | adjustable (Z89 item 14) | **sealed** ("zaślepiony", Z94 item 12) |
| Carb body | not listed separately | 437.28.011.02 (not sold as a spare) |
| Cover | 9914773 | **437.28.010.02** |
| Starter cover | S28.02.00 | **S2B.02.00** |
| Throttle plates and spindles | plates 4372810304 (I) and 4372810404 (II); spindle I 4323406602 (oversize 4323406702); spindle II 033851 (oversize 4372800302) | plates 437.28.103.04 (I) and 437.28.104.04 (II); spindle I 432.34.066.02 (oversize .067.02); spindle II 437.28.002.02 (oversize .003.02) |
| Fuel filter / plug in cover | 9915235 / 9907813 | 438.34.120.04 / 438.34.119.04 |
| Solenoid assembly | EZ-20 033845 + jet 033842 (45) + ring 033844 | complete valve 435.28.030.02 = EZ-20 033845 + jet 435.28.182.04 (45) + ring 033844 |
| Same in both | | venturis 21/26, primary 110/250/F27, tubes F27/F35, idle 45/100, pump 40/80, starter F1/150 and 150, needle valve 175, float 9911187, release lever 014137, throttle lever 702-1107019 |

### Choke and linkage

- Both variants have the same **piston-type cold-start device** with a cable, not a choke flap.
- Both have the same **mechanical progressive secondary**, which opens from 2/3 primary travel (Z89, Z94).
- The starter **cover** part number differs; no functional difference is described.
- No vacuum secondary on either.

## 5. How to identify S2A / S2A1 / S2B1 on the carb

1. **Read the cast or stamped marking on the body.**
   - Shops and owners report "28/35 S2A" with "GN.1113" on the body ([SHOP] roda24 photo `t-28-35-s2a-gn1113-top-photo-roda24.jpg`).
   - The zlombol post says a version number is "wbita po drugiej stronie" (stamped on the other side) [FORUM, low].
   - The S2B1 should read 28/35 S2B1. No photo of an S2B1 marking was found.
2. **Check for the solenoid.** A brass cylinder with a spade terminal, screwed into the body on the float-chamber side (EZ-20), is present on **all three**. It does not tell them apart. It does tell them from the older **34S2B1**, which has no solenoid in the factory documents.
3. **Read the secondary main jet:**
   - **145** suggests S2A/S2A1.
   - **125** suggests S2B1.
   - Jets may have been changed, so use this together with the other checks.
4. **Read the secondary air-correction jet** on top of the secondary well: **225** for S2A1, **220** for S2B1.
5. **Look for the economiser (S2B1 only).** Look for an extra jet or nozzle feeding throat II: economiser jet 80 and nozzle 2.5 (Z94).
   - The BI11 exploded drawing shows a **different cover** (item 49) with the fuel inlet as a horizontal tube with an in-line filter (67) and plug (68).
   - The S2A1 cover (CAT88) has a vertical hex filter plug (6) on top.
   - This is read from the two factory drawings (`t-28-35-s2b1-exploded-bulletin-1991.jpg` vs `t-28-35-s2a1-exploded-parts-catalogue-1988-p1.jpg`). It has not been confirmed on a real carb. Medium confidence.
6. **Mixture screw:** if it carries a factory blanking cap, that points to an S2B1 (Z94). Caps are often missing on old carbs.
7. **Starter cover:** S28.02.00 versus S2B.02.00. The number may be cast on the cover; not verified.

## 6. Makers and names

- **FOS Łódź:** the 1985 manual says FOS Łódź made the 34S2B1 (see `../weber-34s2b1/variants-and-history.md`).
- **Polmo Łomianki:** roda24 gives Polmo Łomianki S.A. as the maker of the 28/35 S2A "GN.1113" [SHOP].
- Neither the 28/35 parts catalogue nor the bulletins name the maker, so the FOS / Polmo question is **still open** for the 28/35. Searches for "Polmo Łomianki 28/35" and "FOS Łódź gaźnik 28/35" returned nothing citable.
- The **EZ-20** solenoid carries a cog-wheel logo in shop photos (other agent's image `o-roda24-ez20-solenoid-126p-pn.jpg`). The maker is unidentified.

## 7. Related carbs (context only)

- **34S2B1:** older S-21 carb, 34/34 bores, 25/25 venturis, no solenoid. See `../weber-34s2b1/`.
- **34S2C16:** the 1.6 l CB-engine Żuk carb in WZ Table 2.18. Venturis 24/26, jets 115/140, float 7.75–8.25 mm. Not for the S-21.
- **Polmo 34 DCMP (Polonez 1.5):** 2 × 34 mm bores, 24/26 venturis [FORUM Strucelsw]. Shares a cover family with the 28/35 per an Eter-Mot cover listing [SHOP].
