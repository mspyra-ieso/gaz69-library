# Weber/FOS 28/35 S2A, S2A1, S2B1: calibration tables

Jet numbers are the bore in hundredths of a millimetre. The factory wording is: "dysza z cechą 110 ma średnicę otworka 1,1 mm" (Z89, Z94).

## Source keys and confidence

| Key | Source | Type | Confidence |
|---|---|---|---|
| **CAT88** | FSC Lublin, *Katalog części zamiennych samochodu Żuk*, 1988 edition. Tables 10.00, 11.07 "Gaźnik Webera" and 11.10, all dated **1987-05**. https://archive.org/download/zukowka-zuk-spare-parts-catalog/FSC_LUBLIN-1988-katalog_czesci_zamiennych_samochodu_Zuk.pdf (PDF pages 35–37 and 40). Images `t-28-35-s2a1-exploded-parts-catalogue-1988-p1/p2/p3.jpg` | FACTORY parts catalogue | High. Jet sizes are printed in the part names |
| **BI11** | FSC Lublin, *Biuletyn Informacyjny Nr 11* to the 1988 catalogue (1991). Table 11.07 "Gaźnik 28/35S2B1", drawing dated 1991-01. https://archive.org/download/zukowka-zuk-spare-parts-catalog_202204/FSC_LUBLIN-1991-biuletyn_informacyjny_nr1_do_katalogu_Zuk_1988.pdf. Images `t-28-35-s2b1-exploded-bulletin-1991.jpg` and `t-28-35-s2b1-parts-list-bulletin-1991.jpg` | FACTORY | High |
| **BI12** | *Biuletyn Informacyjny Nr 12*, September 1991. https://archive.org/download/zukowka-zuk-spare-parts-catalog/FSC_LUBLIN-1991-biuletyn_informacyjny_nr2_do_katalogu_Zuk_1988.pdf | FACTORY | High |
| **Z89** | FSC Żuk owner's manual 1989, Tablica 4.1, for the "28/35S2A". https://archive.org/download/fsc-lublin-instrukcja-obslugi-zuk/FSC_LUBLIN-1989-instrukcja_obslugi_Zuk.pdf (printed pp. 43–45). Image `t-28-35-s2a-float-and-jet-table-zuk-manual-1989.jpg` | FACTORY owner's manual | High for jets. The float text is suspect: see the float section |
| **Z94** | FSC Żuk owner's manual 1994, Tablica 4-3, for the "28/35S2B1". https://archive.org/download/fsc-lublin-instrukcja-obslugi-zuk/FSC_LUBLIN-1994-instrukcja_obslugi_Zuk.pdf (printed pp. 59–63). Images `t-28-35-s2b1-*-zuk-manual-1994.jpg` | FACTORY | High |
| **WZ** | A. Wiejak, J. Zagaja, *Żuk – budowa, eksploatacja, naprawa*, WKŁ, 1992 edition. Table 2.18 and Figs 2.23–2.27 and 2.49–2.50, read in the zukowka.wordpress.com machine translation (Polish figure captions included): https://archive.org/download/zukowka-zuk-spare-parts-catalog/ZUK-BEN-angielski.pdf (PDF pages 55–58 and 77–78) | BOOK | Medium–high. There is one confirmed typo; see the conflicts section |
| **PD** | polskiedostawczaki.pl, "Podstawowe regulacje silników S-21 oraz M-20". https://polskiedostawczaki.pl/podstawowe-regulacje-silnikow-s-21-oraz-m-20/ | SITE (copies WZ) | Medium |
| **FPD** | forum.polskiedostawczaki.pl: t=3998 (jets), t=4279 and t=4635 (solenoid), and forum search snippets | FORUM | Low–medium |
| **Z85** | FSC Żuk owner's manual 1985 (the older **34S2B1**), included only for comparison. https://archive.org/download/fsc-lublin-instrukcja-obslugi-zuk/FSC_LUBLIN-1985-instrukcja_obslugi_Zuk.pdf | FACTORY | High |

## Master table: S2A / S2A1 / S2B1

In the table, "=" means the same as the column to its left.

| Circuit | Item [Polish] | 28/35 S2A (Z89) I / II | 28/35 S2A1 (CAT88, WZ) I / II | 28/35 S2B1 (Z94, BI11, WZ) I / II | Notes |
|---|---|---|---|---|---|
| Body | throttle bore [przepustnica] | — | **Ø28 / Ø35 mm** (CAT88 items 34, 35) | = (WZ: "28 and 35 mm") | This is the meaning of "28/35". FACTORY, high |
| Main | venturi [gardziel] | 21 / 26 | 21.0 / 26.0 (CAT88 items 58, 59) | 21 / 26 (BI11 lists "Gardziel 210 / 260") | All agree |
| Main | auxiliary venturi [rozpylacz] | 4.5 / 4.5 | 4.50 ×2 (CAT88 item 60) | 4.5 / 4.5 | All agree |
| Main | main fuel jet [dysza główna paliwa] | **110 / 145** | **110 / 145** (CAT88 items 28, 29) | **110 / 125** (Z94; BI11 items 64, 6; WZ) | The secondary jet is the main jet difference |
| Main | air-correction jet [dysza powietrza hamująca] | 250 / 225 | **250 / 225** (CAT88 items 55, 54) | 250 / **220** (Z94; BI11 items 42, 44) | |
| Main | emulsion tube [rurka emulsyjna] | F27 / F35 | **F27 / F35** (CAT88 items 57, 56) | F27 / F35 (BI11 items 43, 38) | Do not swap the tubes between throats |
| Idle (I) / progression (II) | fuel jet [dysza paliwa b. jałowego] | 45 / 100 | **45** (on the solenoid, CAT88 item 67) / **100** (CAT88 item 24) | 45 / 100 (Z94; BI11 items 61, 3). **WZ prints 50 for II: a typo** | |
| Idle / progression | idle air jet [dysza powietrza] | 175 / 80 | 175 / 80 (WZ) | 175 / 80 | Calibrated drillings in the body; not listed as parts in CAT88 |
| Idle / progression | mixture jet [dysza mieszanki] | 170 / — | 170 / — (WZ) | 170 / — | Body drilling |
| Idle / progression | progression holes 1°, 2°, 3° [otwór przejściowy] | 80, 80, — / 120, 120, 150 | = (WZ) | = | WZ text: "two 0,8 mm" holes in I; "2 x 1,2 mm and 1,5 mm" in II |
| Idle / progression | progression hole 4° and stabilising hole [otwór stabilizujący] | — / — | — / — | — | Rows exist in the table but are empty. They are used only on the 34S2C16 (80 / 80) |
| Idle | idle cut-off solenoid [elektrozawór] | EZ-20 | EZ-20 (CAT88 item 69, part 033845) | EZ-20 (BI11 item 63) | See solenoid-ez20.md |
| Idle | idle speed | 600–800 rpm | 600–800 rpm (WZ data table) | 600–800 rpm | |
| Pump | pump jet [dysza pompki] | 40 | 40 (CAT88 item 53) | 40 (BI11 item 27) | Injects into throat I |
| Pump | pump valve [zawór] | 80 | 80 (CAT88 item 20) | 80 (BI11 item 58) | |
| Pump | stroke [skok] | 10 mm | 10 mm (WZ) | 10 mm | |
| Pump | output [wydatek] | 0.5 cm³ (per stroke) | 5 cm³ per 10 strokes (WZ) | 5 cm³ per 10 strokes (Z94) | These are the same value |
| Cold start | starter fuel jet [dysza paliwa rozruchu] | F1/150 | F1/150 (CAT88 item 18) | F1/150 (BI11 item 56) | |
| Cold start | starter air jet [dysza powietrza rozruchu] | 150 | 150 (CAT88 item 17) | 150 (BI11 item 55) | |
| Cold start | starter air hole [otwór pow. rozruchu] | 5.75 mm | 5.75 | 5.75 | |
| Cold start | weakening holes 1°, 2° [otwór zubożający] | 1.75, 1.75 | 1.75, 1.75 | 1.75, 1.75 | |
| Cold start | reserve-well bush [tulejka w studzience rezerwowej] | 250 | 250 | 250 | |
| Cold start | starter cover assembly [pokrywa rozruchowa kpl.] | — | S28.02.00 | **S2B.02.00** | A different part, so the starter covers differ |
| Economiser (II) | fuel jet / nozzle [oszczędzacz: dysza paliwa / rozpylacz] | — | — | **80 / 2.5** (Z94; WZ) | Only on the S2B1. Gravity type; acts above half-open secondary |
| Float | needle valve [zawór iglicowy] | 175 | 175 (CAT88 item 11, 9911186) | 175 (BI11 item 70, same part) | 1.75 mm seat |
| Float | needle-valve sealing washers [uszczelka] | — | 0.5 / 0.7 / 1.0 mm (CAT88 item 10) | 0.5 / 0.7 mm, "wg potrzeb" (as needed) (BI11 item 69) | Washer thickness raises or lowers the seat and so changes the level |
| Float | float [pływak] | 18 g | 17.5–18.5 g (WZ); part 9911187 | 18 ±0.5 g (Z94); same part 9911187 | Same float in both |
| Float | float distance from cover face, cover vertical, **without gasket** | "5…5.5 mm" (Z89 text, suspect) | **6.25–6.75 mm** (WZ table) | **7 ±0.25 mm** (Z94); 6.75–7.25 (WZ) | See the float section |
| Float | maximum float drop from cover face | "travel 8.5 mm" (Z89 text) | 13.5 mm (WZ) | **13.5 ±0.5 mm** (Z94) | |
| Assembly | complete carburettor part number | — | 702-1107010-2 (table 11.07); 702-1107010-1 (table 11.10) | 437.28.905.00 | |

### Full S2A1 calibration (the owner's probable type)

| | Primary I | Secondary II |
|---|---|---|
| Throttle bore | 28 mm | 35 mm |
| Venturi / auxiliary venturi | 21 / 4.5 | 26 / 4.5 |
| Main jet | 110 | 145 |
| Air-correction jet | 250 | 225 |
| Emulsion tube | F27 | F35 |
| Idle fuel jet | 45 (on the EZ-20 solenoid) | 100 (secondary progression feed, in a holder) |
| Idle air jet / mixture jet | 175 / 170 | 80 / — |
| Progression holes | 2 × 0.80 mm | 2 × 1.20 + 1 × 1.50 mm |
| Accelerator pump | jet 40, valve 80, 10 mm stroke, 5 cm³ per 10 strokes | — |
| Cold start | fuel jet F1/150, air jet 150, air hole 5.75 mm, weakening holes 1.75 / 1.75, bush 250 | — |
| Float | needle valve 175, float about 18 g, 6.25–6.75 mm without gasket, drop to 13.5 mm | — |
| Idle speed | 600–800 rpm | — |

Sources: CAT88 for the parts that carry a size in their names; WZ Table 2.18 for the body drillings, pump, starter and float; Z89 confirms every jet value.

## Float level: the 5–5.5 / 6.25–6.75 / 7 ±0.25 mm conflict

### Resolution

| Value | Applies to | Evidence | Confidence |
|---|---|---|---|
| **5–5.5 mm** (travel 8.5 mm, drop 13.5 mm) | The older **34S2B1** (34/34 mm, 25/25 venturis) | Z85 table and drawing, for the 34S2B1 | High for the 34S2B1 |
| 5–5.5 mm, as printed in Z89 for the "28/35S2A" | Probably **a carry-over error** | Z89 changed the jet table to the 28/35 values. Its float paragraph, however, matches the 1985 34S2B1 text word for word, including "8,5 mm". Its table has **no** float-distance row, unlike Z94 | Medium (an inference) |
| 5…5.5 mm on WZ Fig. 2.49 (scan on PD) | Same suspect origin | The same book's Table 2.18 says 6.25–6.75 for the S2A1, so the book's drawing and its own table disagree | — |
| **6.25–6.75 mm** without gasket, drop to 13.5 mm | **28/35 S2A1** (and the S2A, which has the same parts) | WZ Table 2.18 (column headed "bez uszczelki"). PD and the FPD admin Marian (2013) quote the same values | Medium–high |
| **7 ±0.25 mm** (6.75–7.25) without gasket, drop to 13.5 ±0.5 mm | **28/35 S2B1** | Z94 (factory text, Tablica 4-3 and Rys. 4.10) and WZ Table 2.18. Z94: "odległość… bez uszczelki… 7 ±0,25 mm (wymiar a)" | High |

The WZ running text says "6,25...6,75 or 6,25...7,25 mm". That is a typo for 6.75…7.25; the book's own table gives 6.75–7.25.

### How it is measured (Z94; WZ Fig. 2.49)

- Hold the cover **vertical**, so the float hangs on the needle under its own weight without pushing in the damper ball.
- Measure from the **cover face with the gasket removed** to the float.
- The float and needle valve are the **same parts** (9911187 and 9911186) on the S2A1 and the S2B1. The S2B1 simply asks for the float about 0.5 mm lower, which means less fuel in the bowl.

### Owner practice (forum, not a spec)

A Nysa owner with an S2A1 set the float to **6.5 mm with a 13 mm maximum drop**: "pływak wyregulowany na 6,5mm i 13mm max wychylenia" (FPD t=3998, 2018).

## Conflicts and errors flagged

1. **WZ secondary idle jet of 50 for the S2B1.** Wrong: the factory parts list BI11 names "Dysza 100 paliwa b. jałowego II przel." and Z94 also gives 100. Use 100.
2. **Primary main jet 118 found in a Nysa S2A1** (FPD t=3998). Not a factory size. The forum view is that it was a stray jet, possibly a mis-stamped 113 or 115. The factory value is 110 (CAT88, Z89).
3. **Primary idle jet of 50.** One forum seller said the tip jet is "50". The factory value is **45** (CAT88 item 67; BI11 item 61), and Strucelsw writes "żuk ma tam dyszę 45" (FPD t=4635). The 126p-type solenoids carry other jet sizes.
4. **Z89 pump output "0,5 cm³" versus Z94 "5 cm³/10 strokes".** These agree (0.5 cm³ per stroke).
5. **zlombol.pl emulsion tube marks "6/2", "5/3", "5/4" (ver.1 / ver.3).** These cannot be reconciled with the factory F27/F35. They are unverified forum claims; see variants.md.

## Factory part numbers for calibrated parts (CAT88 S2A1 / BI11 S2B1)

| Part | S2A1 (CAT88) | S2B1 (BI11) |
|---|---|---|
| Main jet I, 110 | 73805110 | 73.805.110 |
| Main jet II | 73805145 (145) | 73.805.125 (125) |
| Air-correction jet I, 250 | 77502250 | 77.502.250 |
| Air-correction jet II | 77502225 (225) | 77.502.220 (220) |
| Emulsion tube I, F27 | 61455140 | 61.455.140 |
| Emulsion tube II, F35 | 021596 | 61.455.153 |
| Idle jet I, 45 (solenoid tip) | 033842 | 435.28.182.04 |
| Idle/progression jet II, 100 | 7445100 | 74.405.100 |
| Pump jet 40 | 76408040 | 76.408.040 |
| Pump valve 80 | 008523 | 79.701.080 |
| Starter jets | air 9909137 (150); fuel 9912195 (F1/150) | same |
| Needle valve 175 | 9911186 | 9911186 |
| Float | 9911187 | 9911187 |
| EZ-20 solenoid | 033845 | 033845 ("Elektromagnes"); complete valve 435.28.030.02 |
| Solenoid sealing ring | 033844 | 033844 |
| Idle screw | 033846 "wkręt regulacyjny wolnych obrotów" | 033846 |

Full transcriptions of both tables are in the archive folder (see sources-technical.md).
