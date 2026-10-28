# Sources for the tuning track

These sources feed `tuning.md`, `idle-and-mixture.md`, `cold-start-device.md`, `linkage-and-pump.md` and `images/u-images.md`. All were fetched on 2026-10-28.

**Offline copies** live outside the repo, in:
`…/scratch-2026-10-27-538e47/source-archive/weber-28-35-tuning/`
- The first line of each file holds the URL and fetch date.
- Forum copies are the full page text, including forum navigation clutter.
- Book and manual copies are **excerpts** of the chapters used. OCR text is uncorrected.

## Factory and book

| Key | Source | Type | Archive file |
|---|---|---|---|
| Z94 | FSC Żuk owner's manual 1994 (28/35 S2B1): engine data (Etylina 86, CR 7.5, timing, octane corrector), starting and starter use §3.11–3.12, consumption §3.17.1, Rys. 4.9 legend (cable clamp screw 19), idle regulation §4.3.2, air filter §4.3.3. https://archive.org/download/fsc-lublin-instrukcja-obslugi-zuk/FSC_LUBLIN-1994-instrukcja_obslugi_Zuk.pdf (text: …_djvu.txt) | FACTORY | zuk-manual-1994-excerpts.txt |
| Z89 | FSC Żuk owner's manual 1989 (28/35 S2A): factors raising consumption; mixture pre-heater. https://archive.org/download/fsc-lublin-instrukcja-obslugi-zuk/FSC_LUBLIN-1989-instrukcja_obslugi_Zuk.pdf | FACTORY | zuk-manual-1989-excerpts.txt |
| WZ | Wiejak & Zagaja, *Żuk – budowa, eksploatacja, naprawa*, machine-translated English edition (zukowka): §2.1.5 starter function, **Fig. 2.28 control mechanism, 56 mm pedal stroke, ≥3 mm spring, 2–3 mm starter-cable reserve**, mixture heater. https://archive.org/download/zukowka-zuk-spare-parts-catalog/ZUK-BEN-angielski.pdf (text: ZUK-BEN-angielski_djvu.txt) | BOOK | wz-book-en-starter-linkage-excerpt.txt |
| F125 | *Polski Fiat 125p – budowa, eksploatacja, naprawa* (WKŁ, 1982), pp.61–70 (FOS/Weber **34 DCHD**: starter, idle, main, pump, checks, idle CO procedure, float level) and pp.215–216 (cold starting). https://archive.org/details/PolskiFiat125pBudowaEksploatacjaNaprawa1982 (text file: "polski Fiat 125p - budowa, eksploatacja, naprawa 1982_djvu.txt") | RELATED carb, factory-level book | fiat125p-book-1982-carb-excerpt.txt |
| PD | polskiedostawczaki.pl, "Podstawowe regulacje silników S-21 oraz M-20": valve clearances, points, plug gap, timing "7° or more", idle procedure. https://polskiedostawczaki.pl/podstawowe-regulacje-silnikow-s-21-oraz-m-20/ | SITE | pd-podstawowe-regulacje-s21.txt |

## Forum: forum.polskiedostawczaki.pl (FPD)

| Thread | Used for | Archive file |
|---|---|---|
| t=3998 "Gażnik Weber jakie dysze paliwa?" https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3998 | 118→110 primary, CO and λ figures, the 2500 rpm primary-main rule, timing on modern fuel, F27 is thicker, pump-jet siphoning, HC from the breather | fpd-t3998-weber-jets.txt |
| t=4814 "S21 – czarne, okopcone świece…" https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4814 | Mixture 0.5–1.25 turns; screw-fully-in test; O-ring 6×2; jet and air-jet ranges; plug heat range (B7HS too cold, Denso WF20TT) | fpd-t4814-black-plugs.txt |
| t=3094 "Paliwo z domieszką etanolu" https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3094 (+ &start=15) | Ethanol vs jets, altitude, AFR 14.7 / 13 / 16.5, spare-jet list, timing on 95, additives debate | fpd-t3094-ethanol-fuel.txt, fpd-t3094-ethanol-fuel-p2.txt |
| t=5471 "Jakie paliwo lać po wprowadzeniu E10" https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=5471 | E10 views (Marian, Strucelsw), ether vapour, stabiliser | fpd-t5471-e10-fuel.txt |
| t=1007 "Podciśnienie: przewody, podłączenie, wartości" https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=1007 | Vacuum gauge on the ported distributor line reads ~0 at idle; use the manifold or servo line | fpd-t1007-vacuum-gauge.txt |
| t=680 "Ekonomizer" https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=680 | Economy gauge; Nysa about 10 l/100 km on the road | fpd-t680-vacuum-economy.txt |
| t=2222 "Żuk pali jak Rosomak" https://forum.polskiedostawczaki.pl/viewtopic.php?t=2222 | Idle procedure quoted; 11 / 9.8 l/100 km; choke cable return; white plugs = lean; pre-heater removal | fpd-t2222-choke-cable.txt |
| t=2247 "Problem z uruchomieniem silnika" https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=2247 | Marian's rich/lean symptom-cause checklist | fpd-t2247-plugs-mixture-symptoms.txt |
| t=4084 "Żuk A11B 1981" https://forum.polskiedostawczaki.pl/viewtopic.php?t=4084 | Summer choke max 1/3; kinked choke cable; linkage play | fpd-t4084-choke-use-summer.txt |
| t=4581 "Podgrzewacz mieszanki + mały remont" https://forum.polskiedostawczaki.pl/viewtopic.php?t=4581 | Secondary opens only with the pedal floored; pre-heater welded open; float 24 g vs 18 g | fpd-t4581-linkage-secondary.txt |
| t=2030 "…nie wchodzi na obroty" https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=2030 | Hand-over-intake test for a lean mixture | fpd-t2030-mixture-test.txt |
| t=3139 "żuk nierówno wchodzi na obroty" https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3139 | Missing pump ball → dripping pump nozzle (Jikov-owner thread; Strucelsw's remark is general) | fpd-t3139-rich-black-smoke.txt |

### Forum posts cited from search-result snippets only

These are not archived. Search results: https://forum.polskiedostawczaki.pl/search.php?keywords=…&sr=posts

- p=9005 (Weber with dry filter vs Jikov with wet filter): https://forum.polskiedostawczaki.pl/viewtopic.php?p=9005#p9005
- p=53003 (hot cables, earth strap): https://forum.polskiedostawczaki.pl/viewtopic.php?p=53003#p53003
- p=27531 (starter cover on 2 of 3 screws): https://forum.polskiedostawczaki.pl/viewtopic.php?p=27531#p27531
- p=52970 (cable slipped out of the carb): https://forum.polskiedostawczaki.pl/viewtopic.php?p=52970#p52970
- p=49976 (half-choke starts): https://forum.polskiedostawczaki.pl/viewtopic.php?p=49976#p49976
- p=25822 (weak return spring): https://forum.polskiedostawczaki.pl/viewtopic.php?p=25822#p25822
- p=31627 (Polonez pedal and cable conversion): https://forum.polskiedostawczaki.pl/viewtopic.php?p=31627#p31627

### Threads already archived by other tracks, cited again

- t=4329: https://forum.polskiedostawczaki.pl/viewtopic.php?t=4329
- t=4256: https://forum.polskiedostawczaki.pl/viewtopic.php?t=4256
- t=3347: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3347
- t=4713: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4713
- t=4162: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4162
- t=3707: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3707
- t=5488: https://forum.polskiedostawczaki.pl/viewtopic.php?f=15&t=5488
- t=3995: https://forum.polskiedostawczaki.pl/viewtopic.php?f=16&t=3995
- t=4392: https://forum.polskiedostawczaki.pl/viewtopic.php?f=16&t=4392
- t=777 pages: https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=30 (and start=105, 150, 165, 225)

## Other forums

| Key | Source | Archive file |
|---|---|---|
| ZL | zlombol.pl, "Gaźnik Weber 28/35 S2A Żuk problem": the 145 → 135 → 115 experiment, consumption, lean-valve warning. https://zlombol.pl/community/technikalia-2/gaznik-weber-28-35-s2a-zuk-problem-2/ | zlombol-weber-28-35-s2a-jet-experiment.txt |
| ZL-LINK | zlombol.pl, rod-linkage regeneration / Polonez cable. https://zlombol.pl/community/technikalia-2/zuk-s21-regenaeracja-ciegien-gazu-2/ | (archived by the owner track) |
| D2-GAZ2 | drive2.ru GAZ-69 with S-21 and Polish Weber: carb swap, extra return spring. https://www.drive2.ru/l/584099610411147866/ | drive2-gaz69-s21-weber-swap-carb.txt |
| D2-GAZ | Same logbook: cracked phenolic spacer → lean, pinking. https://www.drive2.ru/l/590869853259170000/ | (archived by the owner track) |

## General (non-Polish)

| Key | Source | Archive file |
|---|---|---|
| ALFA | Alfa Workshop (UK), "Carburettors": Weber circuits, clockwise = leaner, progression holes, emulsion-tube hole position, 2.5–3 air-corrector sizes ≈ 1 main jet, CO 1.5–3 %. https://alfaworkshop.co.uk/alfa_carburettors.shtml | gen-alfaworkshop-weber-theory.txt |
| FT | ford-trucks.com, "Carb tuning w/ AFR meter": 12.5:1 WOT target; AFR leans until the secondaries open; tune primaries first. https://www.ford-trucks.com/forums/1331663-carb-tuning-w-afr-meter.html | gen-fordtrucks-carb-tuning-afr-meter.txt |
| IDZ2013 | Idzior, Karpiuk, Czapliński, Iwanicki (2013), paper on CO at periodic inspections, with the Polish idle-CO limit table. https://yadda.icm.edu.pl/baztech/element/bwmeta1.element.baztech-9ca8ccf1-cc2e-4241-bda6-d74a7da9b3ee/c/Idzior_Karpiuk_Czaplinski_Iwanicki_Wybrane_10_2013.pdf | **not archived** (PDF; seen only via search summary, so verify) |

## Tried without useful result

- **elektroda.pl** (topic1523992, wideband for a carb): connection failed once and was not retried, per instructions.
- **J. Kasedorf, *Gaźniki – sprawdzenie i regulacja*** (archive.org item Ganiki.SprawdzenieIRegulacjaJurgenKasedorf): the OCR text is unusable, and the PDF could not be rendered without extra tools. **Worth reading manually.** It is a general Polish carb-tuning book.
- **Borg-Warner 1976 "A Guide to Tuning Weber Carburettors"** (https://www.ramblerlore.com/AMC/Weber-Tuning-Borg-Warner-1976/index.html): scanned images only; not read.
- Web searches on Polonez / 125p tuning, 34 DCHD pump adjustment, and GAZ-69 throttle linkage (in Russian) gave nothing specific.
