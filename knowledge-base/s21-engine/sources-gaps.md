# Sources: gap research (October 2026)

These sources are used in `factory-service-data.md`, `electrics.md`, `fuel-and-conditions.md`, `owner-reports-2.md` and `images/factory-images.md`. All were fetched on 2026-10-28.

Offline copies live outside the repo in `source-archive/s21-gaps/`. Each file has the URL and fetch date on line 1.

## Factory manuals: archive.org

Item **fsc-lublin-instrukcja-obslugi-zuk**: https://archive.org/details/fsc-lublin-instrukcja-obslugi-zuk

| Key | File | Offline OCR text |
|---|---|---|
| Ż65 (M-20 era; not used for S-21 values) | https://archive.org/download/fsc-lublin-instrukcja-obslugi-zuk/FSC_LUBLIN-1965-instrukcja_obslugi_Zuk.pdf | archive-zuk1965-manual-ocr.txt |
| **Ż74** | …/FSC_LUBLIN-1974-instrukcja_obslugi_Zuk.pdf | archive-zuk1974-manual-ocr.txt |
| Ż76 (not examined in detail) | …/FSC_LUBLIN-1976-instrukcja_obslugi_Zuk.pdf | archive-zuk1976-manual-ocr.txt |
| **Ż85** | …/FSC_LUBLIN-1985-instrukcja_obslugi_Zuk.pdf | archive-zuk1985-manual-ocr.txt |
| **Ż89** | …/FSC_LUBLIN-1989-instrukcja_obslugi_Zuk.pdf | archive-zuk1989-manual-ocr.txt |
| **Ż94** | …/FSC_LUBLIN-1994-instrukcja_obslugi_Zuk.pdf | archive-zuk1994-manual-ocr.txt |
| (Andoria 4CT90 engine manual, 2002, in the same item; not used) | …/ANDORIA-2002-instrukcja_obslugi_silnika_4CT90-1MEA.pdf | none |

Item **zsd-1977-instrukcja-obslugi-nysa-522**: https://archive.org/details/zsd-1977-instrukcja-obslugi-nysa-522

| Key | File | Offline OCR text |
|---|---|---|
| **N77** | https://archive.org/download/zsd-1977-instrukcja-obslugi-nysa-522/ZSD-1977-instrukcja_obslugi_Nysa_522.pdf | archive-nysa1977-manual-ocr.txt |

The OCR text came from the matching `*_djvu.txt` files in each item. It is rough. **Always check values against the page images.**

Found but not examined: https://archive.org/details/InstrukcjaObslugiWarszawa2231969, *Instrukcja Obsługi Warszawa 223, 1969*. It is an S-21 car manual, but the item has no PDF or text file listed.

No Żuk **workshop** manual (*Naprawa samochodu Żuk*, Wiejak/Zagaja) was found on archive.org. archive.org search for Żuk, Nysa and Tarpan returned only the items above.

## Factory manuals: local scans (already in the owner's library)

| Key | Folder in `gaz69_library/` | Pages used (JPG file numbers) |
|---|---|---|
| **W65** | `Obsługa i bieżące naprawy samochodu FSO WARSZAWA Część 1 i 2 ( PL 1965 r.)`. FSO / Ośrodek Szkoleniowy SIMP, Part II "Silnik S21". | Contents 0004. Data 0010–0013. Warranty service 0014. Assembly and torques 0091–0097. Running-in 0099. Oil 0102. Noise 0102–0103. Diagnostics 0104–0107. |
| **W66e** | `Obsługa i bieżące naprawy samochodu FSO WARSZAWA Część 4b i 5 ( PL 1966 r.)`, Part VI "Instalacja elektryczna" | Contents 0005. Data 0117. Regulator and distributor 0143–0148. Fault-finding 0164–0165. |
| (checked, not useful) | `Naprawa i obsługa techniczna FSO WARSZAWA M20, 203, 204 ( PL 1968 r.)` | Labour-time norms only, no specs |
| (not checked) | `Część 3 i 4a` (M-20 engine, clutch, gearbox); `Krótka instrukcja … 202 (1962)`; `Katalog części zamiennych FSO WARSZAWA 223` | n/a |

## Forum threads (forum.polskiedostawczaki.pl)

Fetched by a research sub-agent. Every quote was checked against the saved text.

| Topic | URL | Offline file |
|---|---|---|
| Starter, slow cranking, engine earth | https://forum.polskiedostawczaki.pl/viewtopic.php?f=7&t=2295 (and &start=15) | pd-t2295-rozrusznik-masa.txt |
| S-21 starter = Ursus C-328 | https://forum.polskiedostawczaki.pl/viewtopic.php?f=7&t=2655 | pd-t2655-rozrusznik-s21-c328.txt |
| Charging, ignition switch, earths | https://forum.polskiedostawczaki.pl/viewtopic.php?f=7&t=4257 | pd-t4257-ladowanie-stacyjka-masa.txt |
| Alternators: types, warning lamp | https://forum.polskiedostawczaki.pl/viewtopic.php?f=7&t=578 | pd-t578-p1-alternatory-specs.txt |
| Alternators: excitation wiring | https://forum.polskiedostawczaki.pl/viewtopic.php?f=7&t=578&start=90 | pd-t578-p7-alternatory-nysa-zuk.txt |
| Alternator speed and bearings | https://forum.polskiedostawczaki.pl/viewtopic.php?f=7&t=578&start=30 | not saved |
| Temperature gauge pegs | https://forum.polskiedostawczaki.pl/viewtopic.php?f=7&t=2888 | pd-t2888-wskaznik-temperatury.txt |
| E10, unleaded, 98 octane | https://www.forum.polskiedostawczaki.pl/viewtopic.php?f=13&t=5471 | pd-t5471-paliwo-E10.txt |
| Fuel pump, return line, LPG car | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&start=195 | pd-t777-p14-zasilanie-pompa-powrot.txt |
| S-21 power, head skimming | https://forum.polskiedostawczaki.pl/viewtopic.php?p=7002&t=437 | pd-t437-s21-moc-glowica.txt |

## Failed or blocked

- **elektroda.pl.** Every request timed out, both curl with `--max-time 90` and WebFetch, on 2026-10-28.
  - Topics found by search but not read: 576362, 157989, 1069347, 1443225, 976449, 3450596, 3353804, 3309448, 2804243, 1933014, 425673, 721398, 4151545, 845238, 46670, 1585335, 3833232, 3673771, 3376071, 3473633, 597682, 2011122, 1800780, 418313, 1370147.
  - URL format: `https://www.elektroda.pl/rtvforum/topicNNNN.html`. Retry from a normal browser.
- **web.archive.org.** It blocked automated requests ("suspected abusive bot traffic"), so elektroda snapshots could not be used.
- **Not fetched, worth a look:**
  - polskiedostawczaki t=984 (fuel gauge);
  - t=3073 (electric fuel pump instead of mechanical, Andoria);
  - a forums.off-road.com post about a Żuk in Canada with a frozen throttle cable (search-summary only, unverified).
