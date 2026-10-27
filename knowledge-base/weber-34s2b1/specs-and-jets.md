# Calibration and jet tables

**Jet numbers:** the number stamped on a jet is its bore in hundredths of a millimetre. The factory manuals say: "Na każdej dyszy jest wybita cecha", e.g. a jet marked 120 has a 1.2 mm hole. Source: [FACTORY] 1985 and 1994 Żuk manuals.

## Source key

| Key | Source | Confidence |
|---|---|---|
| **Z85** | FSC Lublin Żuk owner's manual 1985, Tablica 4.1 "Dane regulacyjne gaźnika", carburettor "34S2B1, produkcji FOS-Łódź". https://archive.org/download/fsc-lublin-instrukcja-obslugi-zuk/FSC_LUBLIN-1985-instrukcja_obslugi_Zuk.pdf (PDF pages 51–53; image `images/a-34s2b1-jet-table-zuk-manual-1985.jpg`) | Factory, high |
| **N77** | ZSD Nysa 522 owner's manual 1977, technical data, "WEBER 34S2B1". https://archive.org/download/zsd-1977-instrukcja-obslugi-nysa-522/ZSD-1977-instrukcja_obslugi_Nysa_522.pdf (image `images/a-nysa522-1977-fuel-system-spec.jpg`) | Factory, high |
| **Z89** | FSC Lublin Żuk owner's manual 1989, Tablica 4.1, carburettor "28/35S2A" with EZ-20. https://archive.org/download/fsc-lublin-instrukcja-obslugi-zuk/FSC_LUBLIN-1989-instrukcja_obslugi_Zuk.pdf (image `images/a-28-35-s2a-jet-table-zuk-manual-1989.jpg`) | Factory, high |
| **Z94** | FSC Lublin Żuk owner's manual 1994, Tablica 4-3, carburettor "28/35S2B1". https://archive.org/download/fsc-lublin-instrukcja-obslugi-zuk/FSC_LUBLIN-1994-instrukcja_obslugi_Zuk.pdf (image `images/a-28-35-s2b1-jet-table-zuk-manual-1994.jpg`) | Factory, high |
| **TRZ** | K. Trzeciak, carburettor booklet, 1989, quoted by user "hobbista" on elektroda.pl: "Fos 34S2A1 - Żuk, Nysa, Tarpan silnik S-21. Gardziel 25//25…". https://www.elektroda.pl/rtvforum/topic3976154.html | Book, second-hand; medium |
| **PD** | polskiedostawczaki.pl article "Podstawowe regulacje silników S-21 oraz M-20". https://polskiedostawczaki.pl/podstawowe-regulacje-silnikow-s-21-oraz-m-20/ | Enthusiast site (book scans); medium |
| **FPD** | forum.polskiedostawczaki.pl t=3998 (Nysa with 28/35 S2A1). https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3998 | Forum, low–medium |
| **ZL** | zlombol.pl thread "Gaźnik Weber 28/35 S2A – Żuk problem". https://zlombol.pl/community/technikalia-2/gaznik-weber-28-35-s2a-zuk-problem-2/ | Forum, low |

## Table 1: 34S2B1 (the owner's type), factory data

Columns:
- **Item:** English name, with the Polish name in brackets.
- **Primary (I)** and **Secondary (II):** values from Z85, the 1985 Żuk manual.
- **Cross-check:** what other sources say for the same item.

| Item [Polish] | Primary (I) | Secondary (II) | Cross-check |
|---|---|---|---|
| Nominal bore [średnica nominalna przelotu] | 34 mm | 34 mm | Z85 text: "Średnica nominalna przelotów gaźnika wynosi 34 mm" |
| Venturi [średnica gardzieli] | 25 mm | 25 mm | N77: 25 mm for I and II. TRZ (34S2A1): "25//25" |
| Main jet [dysza główna paliwa] | **120** | **150** | N77: "I przelot ø 1,20 mm", "II przelot ø 1,50 mm". **TRZ (34S2A1): 125/145.** See conflicts |
| Auxiliary venturi / nozzle [rozpylacz kompletny] | 450 (4.5) | 450 (4.5) | — |
| Idle fuel jet [dysza paliwa wolnych obrotów] | **50** | **50** | N77: "I i II przelot ø 0,50 mm" |
| Main air-correction jet [dysza główna powietrza] | **210** | **210** | TRZ (34S2A1): 210/210 |
| Emulsion tube [rurka emulsyjna] | **F30** | **F30** | TRZ (34S2A1): F30/F30 |
| Accelerator pump jet [dysza paliwa pompki przyspieszającej] | 70 | — | — |
| Cold-start air jet [dysza powietrza urządzenia rozruchowego] | 150 | — | — |
| Cold-start fuel jet [dysza paliwa urządzenia rozruchowego] | F1/150 (one for the carb) | | — |
| Needle valve [zawór iglicowy dopływu paliwa] | 175 (1.75 mm seat), one for the carb | | — |
| Float setting [odległość pływaka od płaszczyzny pokrywy, w położeniu pionowym] | **5–5.5 mm** | | PD: "Weber 34S2A1 oraz 34S2B1 – 5,0mm – 5,5mm". Z85 drawing Rys. 4.10 shows "5–5,5" |
| Float travel [skok pływaka] | **8.5 mm** | | Z85 drawing shows 13.5 mm from the cover plane at full drop. 13.5 − 5 = 8.5, so the two figures agree |
| Float mass [masa pływaka] | 18 g | | — |
| Idle speed [wolne obroty] | **600–800 rpm** | | N77 (Nysa, Weber): "550-650" rpm. See conflicts |
| Idle CO | not given in any factory source found | | — |

### Notes on Table 1

- **Gasket:** Z85 does not say whether the float distance is measured with or without the cover gasket. Z94 (for the 28/35 S2B1) explicitly says "bez uszczelki" (without gasket). Measuring without the gasket is the usual Weber practice, but this is unconfirmed for the 34S2B1.
- **Missing items:** pump stroke and output, progression holes and enrichment are **not listed** for the 34S2B1 in Z85. Those items appear only in Z89 and Z94 for the 28/35 types.

## Table 2: 34S2A1, from a book quoted second-hand (TRZ)

| Item | I | II |
|---|---|---|
| Venturi | 25 | 25 |
| Main jet | 125 | 145 |
| Air-correction jet | 210 | 210 |
| Emulsion tube | F30 | F30 |

The poster added "itp....." (etc.), so the book has more data that was not quoted.

## Table 3: 28/35 S2A (Z89) and 28/35 S2B1 (Z94), factory data

| Circuit | Item [Polish] | 28/35 S2A I | 28/35 S2A II | 28/35 S2B1 I | 28/35 S2B1 II |
|---|---|---|---|---|---|
| Main | venturi [gardziel] | 21 | 26 | 21 | 26 |
| Main | auxiliary venturi [rozpylacz] | 4.5 | 4.5 | 4.5 | 4.5 |
| Main | main jet [dysza paliwa] | 110 | **145** | 110 | **125** |
| Main | air-correction jet [dysza powietrza] | 250 | **225** | 250 | **220** |
| Main | emulsion tube [rurka emulsyjna] | F27 | F35 | F27 | F35 |
| Idle / progression | idle fuel jet [dysza paliwa] | 45 | 100 | 45 | 100 |
| Idle / progression | idle air jet [dysza powietrza] | 175 | 80 | 175 | 80 |
| Idle / progression | mixture jet [dysza mieszanki] | 170 | — | 170 | — |
| Idle / progression | progression holes 1°/2°/3° [otwór przejściowy] | 80 / 80 / — | 120 / 120 / 150 | 80 / 80 / — | 120 / 120 / 150 |
| Idle / progression | idle cut-off solenoid [elektrozawór] | EZ-20 | | EZ-20 | |
| Idle / progression | idle speed | 600–800 rpm | | 600–800 rpm | |
| Accelerator pump | jet [dysza] | 40 | | 40 | |
| Accelerator pump | valve [zawór] | 80 | | 80 | |
| Accelerator pump | stroke [skok] | 10 mm | | 10 mm | |
| Accelerator pump | output [wydatek] | 0.5 cm³ | | 5 cm³ per 10 strokes | |
| Cold start | fuel jet / air jet | F1/150 / 150 | | F1/150 / 150 | |
| Cold start | starter air hole | 5.75 mm | | 5.75 mm | |
| Cold start | weakening holes 1°/2° [otwór zubożający] | 1.75 / 1.75 | | 1.75 / 1.75 | |
| Cold start | reserve bush [tulejka w stud. rezerw.] | 250 | | 250 | |
| Economiser (2nd throat) [oszczędzacz] | fuel jet / nozzle | — | — | — | 80 / 2.5 |
| Float | needle valve | 175 | | 175 | |
| Float | float mass | 18 g | | 18 ±0.5 g | |
| Float | float distance | 5–5.5 mm (text) | | **7 ±0.25 mm, without gasket**; drop to 13.5 ±0.5 mm | |
| Float | float travel | 8.5 mm (text) | | — | |

Notes on Table 3:
- **Order of the idle-jet columns:** the 1989/1994 tables put the idle jet "45" in the primary column and "100" in the secondary column. The secondary "idle" jet is really the secondary **progression (transition)** feed, because the table heading is "Biegu jałowego i przejściowy".
- **1989 OCR caveat:** the 1989 scan's OCR is poor, but the page image (`a-28-35-s2a-jet-table-zuk-manual-1989.jpg`) reads as above.

## Table 4: Wiejak & Zagaja book, Table 2.18 (WZ)

**Source WZ:** A. Wiejak, J. Zagaja, *Żuk – budowa, eksploatacja, naprawa*, WKŁ, 1992 edition.
- Read via an unofficial machine translation into English hosted on archive.org: https://archive.org/download/zukowka-zuk-spare-parts-catalog/ZUK-BEN-angielski_djvu.txt (translation by zukowka.wordpress.com).
- The translator warns: "crosscheck with the original manual for anything critical".
- Medium–high confidence: the numbers are from the book, but the OCR and translation can garble them.

The book gives the S-21 types 28/35 S2A1 and 28/35 S2B1, and the 34S2C16 for the CB (1.6 l) engine. Only differences from Table 3 are noted:

| Item | 28/35 S2A1 I / II | 28/35 S2B1 I / II | 34S2C16 I / II (CB engine, not S-21) |
|---|---|---|---|
| Venturi | 21 / 26 | 21 / 26 | 24 / 26 |
| Main jet | 110 / 145 | 110 / 125 | 115 / 140 |
| Air jet | 250 / 225 | 250 / 220 | 230 / 200 |
| Emulsion tube | F27 / F35 | F27 / F35 | F35 / F30 |
| Idle fuel jet | 45 / 100 | 45 / **50** (Z94 says 100) | 100 / 100 |
| Pump jet / valve / stroke | 40 / 80 / 10 mm | 40 / 80 / 10 mm | 50 / closed / 13 mm |
| Float mass | 17.5–18.5 g | 17.5–18.5 g | 17.5–18.5 g |
| Float distance from cover, **without gasket** | **6.25–6.75 mm** | **6.75–7.25 mm** | 7.75–8.25 mm |
| Full float stroke | 13.5 mm | 13.5 mm | — |

- The book's text says the level is set by bending the hinge tongue, and the stop is set for a full float stroke of 13.5 mm.
- The book's own figure 2.49 (the scan reproduced on polskiedostawczaki.pl, `images/a-float-level-and-exploded-28-35-s2a1-manual.jpg`) is dimensioned **5…5.5 mm**. So the book's text table and its drawing disagree.
- The polskiedostawczaki.pl float figures (PD) clearly come from this table.

## Conflicts and inconsistencies (flagged, not resolved)

1. **34S2B1 main jets, 120/150 (Z85, N77) versus 34S2A1 at 125/145 (TRZ).**
   - These are different variant letters, so both may be correct for their own type.
   - Do not mix them up when buying jets.
2. **Float level for the 28/35 types.**
   - PD gives "28/35 S2A1 – 6,25–6,75 mm" and "28/35 S2B1 – 6,75–7,25 mm".
   - Z94 gives 7 ±0.25 mm for the S2B1, which equals PD's 6.75–7.25 range.
   - Z89's text gives 5–5.5 mm for the "28/35S2A". That may have been copied from the older 34S2B1 manual text.
   - The scan on PD (`images/a-float-level-and-exploded-28-35-s2a1-manual.jpg`, source book "Rysunek 2.49", unidentified) shows **5…5.5** with a 13.5 mm maximum for the "28/35 S2A1".
   - Conclusion: **for the 34S2B1, every source agrees on 5–5.5 mm.** For the 28/35 types, the sources disagree.
3. **Idle speed.**
   - Żuk manuals: 600–800 rpm.
   - Nysa 522 manual (1977): 550–650 rpm with the Weber, and 450–500 rpm with the Jikov.
4. **Forum figures that differ from the factory data, for 28/35 S2A1 on a Nysa (FPD):**
   - Owner "jasio" measured main jets of 118 (I) and 145 (II).
   - User Strucelsw said: "dysza 1 przelot powinna byc 110, wolnych z elektrozaworem 45" and listed the rest as primary tube F27 / air 250 and secondary F35 / air 225 / main 145. This matches Z89 exactly.
   - Strucelsw also said: "125 paliwa w drugim jest dla s2b1". This matches Z94.
   - Strucelsw suggested the 118 was a wrong jet from another car, e.g. a Trabant or Polonez/Maluch jet with a poorly stamped number.
5. **ZL forum claims (variant only "28/35 S2A", ver.1/ver.3):**
   - "Żuk wychodzi z fabryki z dyszą 145" (the Żuk leaves the factory with a 145 jet). This probably refers to the **secondary** main jet. It conflicts with Z85's 150 for the 34S2B1 secondary.
   - The poster ran 135 and 115 in the primary as an economy experiment (consumption 15.5 → about 12 l/100 km, with hesitation). That is opinion, not a spec.
   - The same thread lists emulsion tubes "6/2" (ver.1) and "5/3, 5/4" (ver.3). These are a different marking system from F27/F30/F35, and the thread gives no explanation.

## Measured exhaust values (forum, not a spec)

- FPD (Nysa, 28/35 S2A1, after setting the primary main jet to 110): idle CO 2.4 %, lambda 1.024; at higher rpm CO about 4 %, lambda 0.930.
- That poster's starting point was CO >7 % and lambda 0.76–0.83 at 2500 rpm, which is badly rich, with a leaking needle valve and a 118 jet.

No factory CO specification was found.

## Part numbers seen

- **Rebuild kit [SHOP]**, roda24 kit for 28/35 S2A1 (aftermarket, Art-Mobil). Source: https://sklep.roda24.pl/zestaw-naprawczy-gaznika-28-35-s2a1-zuk-nysa-fso-9354.html

  | Part | OE number |
  |---|---|
  | Needle valve | 9911186 |
  | Adjustment screw | 017547 |
  | Idle jet | 033842 |
  | Primary spindle with plate | GN.17.17 |
  | Secondary spindle | 9914779 |
  | Not identified | 9919731, 9918723, 014139 |

- **Float-level gauge [FACTORY]:** 17-P-1107 (Z85).
- **Body marking [SHOP]:** "GN.1113" on a 28/35 S2A (roda24).
