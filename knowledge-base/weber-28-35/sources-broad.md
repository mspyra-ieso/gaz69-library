# Sources: broad track (overhaul, wear, interchangeability, history, ownership)

These sources were compiled on 2026-10-28.
- **Archive folder (outside the repo):** `source-archive/weber-28-35-broad/`. Each file has the URL and fetch date on line 1.
- **"existing archive"** means a file already saved by an earlier track, in `source-archive/<folder>/`.
- **FPD** = forum.polskiedostawczaki.pl.

## Factory documents and book

| Key | Source | Used for | Archive file |
|---|---|---|---|
| CAT88 | FSC Lublin, Żuk parts catalogue 1988, tables 11.07 and 11.10. https://archive.org/download/zukowka-zuk-spare-parts-catalog/FSC_LUBLIN-1988-katalog_czesci_zamiennych_samochodu_Zuk.pdf | Part numbers, oversize spindles, CZ-37 kits, mounting stack | existing: `weber-28-35-technical/zuk-katalog-1988-tablica-11-07-gaznik-28-35-s2a1.txt` |
| BI11 | Biuletyn 11 (1991). https://archive.org/download/zukowka-zuk-spare-parts-catalog_202204/FSC_LUBLIN-1991-biuletyn_informacyjny_nr1_do_katalogu_Zuk_1988.pdf | S2B1 oversize spindles; "nowy, oszczędny" | existing: `weber-28-35-technical/zuk-biuletyn-nr11-1991-*.txt` |
| WZ | Wiejak & Zagaja, *Żuk – budowa, eksploatacja, naprawa*, English machine translation. https://archive.org/download/zukowka-zuk-spare-parts-catalog/ZUK-BEN-angielski.pdf | Permissible dismantling (Fig. 2.50), cleaning rule, 9000 km interval, repair with kits and test bench | existing: `weber-28-35-technical/wiejak-zagaja-zuk-ben-english-carb-sections.txt` |
| Z65 | Żuk manual 1965 (OCR). https://archive.org/download/fsc-lublin-instrukcja-obslugi-zuk/FSC_LUBLIN-1965-instrukcja_obslugi_Zuk_djvu.txt | G 35 carb | existing: `s21-gaps/archive-zuk1965-manual-ocr.txt` |
| Z74 | Żuk manual 1974. https://archive.org/download/fsc-lublin-instrukcja-obslugi-zuk/FSC_LUBLIN-1974-instrukcja_obslugi_Zuk.pdf | Jikov 40 SOP, G35 | existing: `s21-gaps/archive-zuk1974-manual-ocr.txt` |
| Z76 | Żuk manual 1976. https://archive.org/download/fsc-lublin-instrukcja-obslugi-zuk/FSC_LUBLIN-1976-instrukcja_obslugi_Zuk.pdf | Weber 34S2B1 or Jikov 40 SOP; Fiat 125p-type air filter | existing: `s21-gaps/archive-zuk1976-manual-ocr.txt` |
| N77 | Nysa 522 manual 1977 (OCR). https://archive.org/download/zsd-1977-instrukcja-obslugi-nysa-522/ZSD-1977-instrukcja_obslugi_Nysa_522_djvu.txt | Weber or Jikov on the Nysa | existing: `s21-gaps/archive-nysa1977-manual-ocr.txt` |
| Z85 | Żuk manual 1985. https://archive.org/download/fsc-lublin-instrukcja-obslugi-zuk/FSC_LUBLIN-1985-instrukcja_obslugi_Zuk.pdf | "34S2B1, produkcji FOS-Łódź" | existing: `s21-gaps/archive-zuk1985-manual-ocr.txt` |
| Z89 / Z94 | Żuk manuals 1989 and 1994 (URLs in `specs-and-jets.md`) | Float weight, pump output, solenoid | existing |

## Forum threads (FPD unless stated)

| Thread | URL | Used for | Archive file |
|---|---|---|---|
| t=2916 "Zielony" (2015) | https://forum.polskiedostawczaki.pl/viewtopic.php?f=16&t=2916&p=38834 | Spindle wear, oversize vs bushing, F35 tube identification, jet deposits | `fmpd-t2916-zielony-tulejowanie.txt` |
| t=2439 "Jikov SEDR vs. Weber" (2014–15) | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=2439 (&start=15, 30, 45) | Polonez / S-21 same body (1982 POLMO catalogue), engine-braking valve, tilt on a GAZ, Jikov SEDR opinions, Weber since '86 | `fmpd-t2439-jikov-vs-weber-p1.txt`, `-s15`, `-s30`, `-s45` |
| t=1472 "Spalanie silników s-21 i 4c90" (2011) | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=1472 (&start=15, 30, 45) | Consumption figures | `fmpd-t1472-spalanie-s21*.txt` |
| t=4256 "Żuk chleje jak smok" (2018–23) | https://forum.polskiedostawczaki.pl/viewtopic.php?f=15&t=4256 (&start=15) | 21 → 16 l/100; overrun cut-off module | `fmpd-t4256-zuk-chleje*.txt` |
| t=3357 "Silnik S-21 Remont i Tuning" (2016–17) | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3357 (&start=15, 30) | Spacer stack, breather plunger, heat plate, run-in | `fmpd-t3357-s21-remont-tuning*.txt` |
| t=3841 "Czyszczenie gaźników" (2017) | https://forum.polskiedostawczaki.pl/viewtopic.php?f=8&t=3841 | Cleaning methods | `fmpd-t3841-czyszczenie-gaznikow.txt` |
| t=3613 (old fuel and tank sludge, 2017) | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3613&p=48192 | Tank sludge after purchase | `fmpd-t3613-stare-paliwo-szlam.txt` |
| t=777 "Układ zasilania" | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=777&p=59754#p59754 ; …&p=43092 | DCMP jets for the S-21, breather routing, Solex needle suggestion | existing: `weber-28-35-owner/fmpd-t777-uklad-zasilania-p17.txt` and others |
| t=4279, t=4635 (28/35 S2A on an M102) | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4279 ; https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4635&start=15 | Venturi rationale, DCMP for 1.6, Pierburg comparison | existing: `weber-28-35-owner/fmpd-t4279-elektrozawor.txt`, `fmpd-t4635-*.txt` |
| t=4733 "[K] Gaźnik Weber" (2020) | https://forum.polskiedostawczaki.pl/viewtopic.php?f=3&t=4733 | Prices; Strucelsw doesn't repair spindle play | existing: `weber-28-35-owner/fmpd-t4733-k-gaznik-weber.txt` |
| t=4717 | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=4717 | Float wear | existing: `weber-28-35-owner/fmpd-t4717.txt` |
| t=1924 heat plate | https://forum.polskiedostawczaki.pl/viewtopic.php?f=8&t=1924 | Heat plate | existing: `weber-28-35-owner/fmpd-t1924-blacha-pod-gaznik.txt` |
| t=3139 | https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=3139 | Jikov on a Żuk, poor above 1/3 throttle | existing: `weber-28-35-owner/fmpd-t3139-nierowno-obroty.txt` |
| t=995, t=27, t=5069, t=5490, t=2908, t=1250, t=733, t=2094, t=5471, t=5245 | e.g. https://forum.polskiedostawczaki.pl/viewtopic.php?f=5&t=995 , https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=27 , https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=5069 , https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=5490 , https://forum.polskiedostawczaki.pl/viewtopic.php?f=23&t=2908 , https://forum.polskiedostawczaki.pl/viewtopic.php?f=1&t=1250 , https://forum.polskiedostawczaki.pl/viewtopic.php?f=32&t=733&p=10621 , https://forum.polskiedostawczaki.pl/viewtopic.php?f=6&t=2094 , https://forum.polskiedostawczaki.pl/viewtopic.php?f=13&t=5471 | Short points, read from the **search snippets** below (threads not opened in full) | search files below; t=5471 existing: `s21-gaps/pd-t5471-paliwo-E10.txt` |
| syrena.nekla.pl t=10451 "Weber czy Jikov?" (2010) | https://syrena.nekla.pl/forum/viewtopic.php?t=10451 | Weber vs Jikov opinion; plugs | existing: `weber-owner-reports/syrena-t10451-weber-czy-jikov.txt` |

### FPD search pages (snippets)

All are in `source-archive/weber-28-35-broad/`.
- `fmpd-search-os-przepustnicy.txt`: https://forum.polskiedostawczaki.pl/search.php?keywords=o%C5%9B+przepustnicy&sr=posts
- `fmpd-search-luz-przepustnicy.txt`: https://forum.polskiedostawczaki.pl/search.php?keywords=luz+przepustnicy&sr=posts
- `fmpd-search-jikov.txt`, `fmpd-search-pierburg.txt`, `fmpd-search-polonez-gaznik.txt`, `fmpd-search-regeneracja.txt`: the same pattern, with keywords jikov, pierburg, "polonez gaźnik" and "regeneracja gaźnika".
- `fmpd-s-*.txt`: keywords 28/35, dcmp, dchd, "125p gaźnik", solex, ultradźwięk*, myjk*, "membran* pomp*", planowa*, tulejow*, "spalanie weber", k126, polonezowy, 34s2c. The URL pattern is https://forum.polskiedostawczaki.pl/search.php?sr=posts&keywords=… .
  - The 28/35, 34s2c, dchd and k126 searches returned **no result count**, probably because of the minimum word length or the slash. That is a null result, not evidence.

## drive2.ru (GAZ-69 with S-21)

All are in the existing archive `source-archive/gaz69-s21/` or `weber-28-35-owner/` (file names `d2-car*-<id>.txt`).
- https://www.drive2.ru/l/590869853259170000/ : cracked textolite spacer, lean, detonation
- https://www.drive2.ru/l/584099610411147866/ : replacement carb without solenoid, lapped face, extra return spring
- https://www.drive2.ru/l/573142427284540104/ : lapped carb face
- https://www.drive2.ru/l/575155907952902834/ : 2108 throttle sector and cable on the Weber
- https://www.drive2.ru/l/582315103039499779/ : sediment bowl and dismountable filter
- https://www.drive2.ru/l/548646957485131028/ and https://www.drive2.ru/l/553391075281076709/ : electric pump with no return; planned Chinese "Beijing" carb

## Shops

| Page | URL | Archive file |
|---|---|---|
| ETER-MOT shared cover | https://eter-mot.abc24.pl/produkt/921305-gaznik-weber-28-35-s2a-34-dchd-34-dcmp-34-s2c-34-s2a-34-s2b-pokrywa | `etermot-921305-pokrywa-wspolna.txt` |
| ETER-MOT shared lever | https://eter-mot.abc24.pl/produkt/935411-gaznik-weber-34-dchd-34-dcpm-34-s2c-34-s2a-b-1-28-35-s2a1-dzwignia-osi | `etermot-935411-dzwignia.txt` |
| ETER-MOT Jikov → Weber adapter | https://eter-mot.abc24.pl/produkt/397656-nakladka-redukcja-z-gaznika-jikov-40-sop-na-weber-28-35-s2a1-zuk | `etermot-397656-redukcja-jikov.txt` |
| ETER-MOT "S2" search | https://eter-mot.abc24.pl/default.asp?kat=-3&klucz=S2 | existing: `weber-28-35-technical/etermot-search-s2.txt` |
| roda24 FSO / PN gasket set (OE 4127681, 9914774) | https://sklep.roda24.pl/uszczelki-gaznika-fso-pn-st-kpl-2865.html | `roda24-2865-uszczelki-fso-pn.txt` |
| roda24 FSO cover kit (9909233) | https://sklep.roda24.pl/zestaw-naprawczy-pokrywy-gaznika-fso-3441.html | `roda24-3441-pokrywa-fso-kit.txt` |
| roda24 Art-Mobil 28/35 kit (8.2 mm spindle) | https://sklep.roda24.pl/zestaw-naprawczy-gaznika-28-35-s2a1-zuk-nysa-fso-9354.html | existing: `weber-28-35-technical/roda24-9354-kit-28-35-s2a1.txt` |
| Mecatechnic 34 DCHD replacing the Polmo 34 DCMP | https://www.mecatechnic.com/en-GB/p/weber-34-dchd-carburettor-for-fso-pick-up-1980-86-with-1481-cm3_CAR0199 | not archived (search result only) |
| sprzedajemy.pl G35 / "lic. weber" listings | https://sprzedajemy.pl/motoryzacja/czesci-samochodowe/uklad-paliwowy/gazniki/temat/gara%C5%BC | not archived (search result only) |
| Polmo Łomianki profile | https://www.aplikuj.pl/pracodawca/389762/polmo-lomianki-s-a | not archived (search result only) |
| Polski Fiat 125p (Wikipedia) | https://en.wikipedia.org/wiki/Polski_Fiat_125p | not archived (search result only) |

## General carburettor practice (not 28/35-specific)

| Page | URL | Archive file |
|---|---|---|
| Moss Motoring, rebushing SU bodies (spindle wear, 0.005 in, spray test) | https://mossmotoring.com/rebushing-su-carburetor-bodies/ | `gen-moss-rebushing-carb-bodies.txt` |
| fiatforum, Weber 26/28 IMB (lapping on glass, cover warp) | https://www.fiatforum.com/threads/weber-26-28-imb.355169/page-3 | `gen-fiatforum-weber-lapping.txt` |
| hobby-machinist, ultrasonic cleaning of Zamak | https://hobby-machinist.com/threads/ultra-sonic-cleaning-of-zamak.114761 | `gen-hobbymachinist-zamak-ultrasonic.txt` |
| kzrider, ultrasonic for carb banks | https://kzrider.com/forum/3-carburetor/621733-what-size-brand-model-ultrasonic-for-entire-bank-of-4-carbs?start=12 | `gen-kzrider-ultrasonic.txt` |
| Mike's Carb Technical, worn Stromberg spindle (bearings) | https://mikescarbtechnical.notion.site/Worn-throttle-shaft-Stromberg-WW-1ec1c97f2e2a801eaa0dc5d12a2800af | not archived (search result only) |

## Not tried or failed
- **elektroda.pl:** not fetched. The search results showed only Skoda / Favorit threads.
- **Russian and Czech sources** on Weber 28/35 swaps: nothing beyond the drive2 GAZ-69 logbooks.
