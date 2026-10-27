# Weber/FOS twin-barrel carburettors for the S-21 engine: variants and history

Scope: technical identification of the Polish-built Weber-licence downdraught twin-barrel carburettors used on the FSO S-21 engine (Żuk, Nysa, Tarpan, Warszawa 223/224). Troubleshooting and the engine itself are covered in other files.

Labels used below:
- **[FACTORY]** = vehicle maker's owner/service manual (FSC Lublin, ZSD Nysa).
- **[BOOK]** = period technical book, quoted second-hand.
- **[SHOP]** = parts seller listing.
- **[FORUM]** = forum post (opinion or measurement, not a spec).

Many forum posts and listings just say "gaźnik Weber" or "weber" without the exact type. Those are flagged "variant not named".

---

## 1. Important correction: is the 34S2B1 secondary vacuum-operated?

The brief describes the 34S2B1 as having its secondary throat opened by a vacuum diaphragm. **The factory manual does not say that.** The 1985 FSC Żuk owner's manual describes the 34S2B1 like this:

- It is a downdraught twin-barrel unit with a progressively opening secondary. Polish: "ze stopniowym otwieraniem II przepustnicy".
- The **secondary is opened mechanically** by a lever linkage from the primary throttle spindle. Polish: "sterowane mechanicznie przez układ dźwigniowy z osi przepustnicy I przelotu".
- The secondary only starts to open at **2/3 of full primary opening**. Polish: "zaczyna się otwierać dopiero przy 2/3 pełnego otwarcia".
- Nominal bore of both throats is 34 mm.
- Source: [FACTORY] FSC Lublin 1985 Żuk manual, p.49 – https://archive.org/download/fsc-lublin-instrukcja-obslugi-zuk/FSC_LUBLIN-1985-instrukcja_obslugi_Zuk.pdf (see `images/a-34s2b1-general-view-zuk-manual-1985.jpg`).

The 1989 manual (28/35 S2A) and the 1994 manual (28/35 S2B1) use the same "mechanical, from 2/3" wording.

The round housing on the side of these carburettors is the **cold-start device** (urządzenie rozruchowe), not a vacuum diaphragm. It has a lever (item 11 "dźwignia urządzenia rozruchowego" in the 1985 drawing; items 17/18 lever and cable in the 1994 drawing). The fault table confirms it is a piston-type device ("zacięcie się tłoka urządzenia").

The only vacuum connection the manuals mention is a **port for the distributor vacuum advance** (1985 item 3: "króciec przewodu podciśnieniowego regulatora aparatu zapłonowego").

The vacuum-secondary claim exists only on a forum, and only for the **34S2A1**:
- [FORUM] elektroda.pl user michal_rybka said the 34S2A1 has "drugą gardzielą sterowaną podciśnieniowo, niby oszczędniejszy". Another user, Mateusz_konstruktor, wrote "z pamięci" (from memory) that the difference was "bodajże" (probably) about the vacuum connection. Source: https://www.elektroda.pl/rtvforum/topic3976154.html
- No factory document seen confirms this.

**Practical note for the owner:** look at your carburettor. If it has a separate diaphragm "pot" with a vacuum hose and a rod to the secondary throttle lever, it is a vacuum-secondary unit, and the factory 34S2B1 description below does not fully apply. If the secondary is opened by a slotted lever on the primary spindle (1985 drawing items 8 "dźwignia zwalniająca" and 10 "dźwignia przepustnicy II przelotu"), it matches the factory 34S2B1.

## 2. Maker and naming

- **Maker:**
  - [FACTORY] The 1985 Żuk manual says the S-21 uses "gaźnik typ 34S2B1, produkcji FOS-Łódź" (FOS = Fabryka Osprzętu Samochodowego, Łódź), and labels drawings "Gaźnik FOS". Source: 1985 manual p.49 (URL above).
  - [SHOP] roda24.pl gives the manufacturer of the "28/35 S2A, GN.1113" unit as **Polmo Łomianki S.A.** Source: https://sklep.roda24.pl/gaznik-weber-zuk-nysa-warszawa-regenerowany-2830.html
  - **Conflict / open question:** FOS Łódź versus Polmo Łomianki. Possibly production moved, or the shop is wrong. Not resolved.
- **"FOS" versus "Weber":**
  - [BOOK] The Trzeciak 1989 carburettor book (quoted on elektroda) lists the unit as "Fos 34S2A1". The poster asks "Fos czy Weber. Czy to to samo?" Source: https://www.elektroda.pl/rtvforum/topic3976154.html
  - Both names refer to the same licence-built family.
- **Family relationship to the Fiat 125p:**
  - [SHOP] Eter-Mot sells one new carburettor cover listed for "28/35 S2A, 34 DCHD, 34 DCMP, 34 S2C, 34 S2A, 34 S2B", with application "Fiat 125p, Żuk (ST i NT)". So the cover is shared with the Fiat 125p Weber 34 DCHD/DCMP. Source: http://eter-mot.abc24.pl/default.asp?kat=-3&klucz=S2
  - [FORUM] An elektroda user says the 34S2A1 is "ten sam (budowa) co przy dużym fiacie 125p". Another user says only the general outline is shared and the second throat differs.
- **Meaning of "28/35":** probably the primary/secondary throttle bore sizes (28 mm and 35 mm). The venturis of 21/26 mm (see specs-and-jets.md) fit a smaller primary. This is an inference: no source spells it out.

## 3. Variant list

| Variant (as marked) | Vehicles / period | Key facts | Sources and confidence |
|---|---|---|---|
| **Jikov 40 SOP** (not Weber, for context) | Early Żuk; Nysa 522 alternative (1977) | Single barrel, 32 mm venturi, main jet 1.55 mm, idle jet 0.6 mm; idle 450–500 rpm | [FACTORY] 1974 Żuk manual covers "Obsługa gaźnika Jikov 40 SOP"; Nysa 1977 manual gives the data. High |
| **34S2B1** (FOS / Weber) | Żuk (1985 manual); Nysa 522 (1977 manual: "WEBER 34S2B1, dwuprzelotowy" as alternative to Jikov); shops: Żuk, Nysa, Warszawa, Tarpan | 34/34 mm bores, 25/25 venturis, mechanical progressive secondary from 2/3 primary, piston-type cold-start device, no idle solenoid in the 1985 drawing or table | [FACTORY] 1985 Żuk and 1977 Nysa manuals. High |
| **34S2A1** (FOS) | Żuk, Nysa, Tarpan with S-21 (Trzeciak 1989) | Same venturi/air/emulsion as 34S2B1, but main jets 125/145 instead of 120/150; forum says vacuum-operated secondary (unconfirmed) | [BOOK] via [FORUM] elektroda. Medium |
| **34S2A2** | "w Żuku i Nysie" | Mentioned once by a forum user; no data | [FORUM] elektroda. Low |
| **34S2C / 34S2C1** | Unclear (cover shared with Żuk and Fiat 125p) | A web-search snippet said a supplier lists idle jet "45" for 34S2C1 and 28/35S2A1; not verified on a page | [SHOP] Eter-Mot cover listing. Low |
| **28/35 S2A** (shown as "28/35S2A" in the manual) | Żuk 1989 manual | 21/26 venturis, F27/F35 emulsion tubes, **EZ-20 idle cut-off solenoid** (elektrozawór), mechanical progressive secondary | [FACTORY] 1989 Żuk manual. High |
| **28/35 S2A1**, marked "28/35 S2A, GN.1113" | Żuk, Nysa, Warszawa, Tarpan (shops); Nysa owners | Sold new with "elektrodysza" (idle solenoid jet); kits: needle valve, float spindle, 4 fuel jets, idle jet, 8.2 mm oversize primary spindle | [SHOP] roda24, Eter-Mot; [FORUM] polskiedostawczaki. Medium |
| **28/35 S2B1** | Żuk 1994 manual (petrol S-21) | Like 28/35 S2A but main jets 110/125, secondary air 220, **gravity-type economiser/enricher on 2nd throat**, EZ-20 solenoid, mixture screw sealed, float 7 ±0.25 mm | [FACTORY] 1994 Żuk manual. High |
| **28/35 S2A "ver. 1" / "ver. 3"** | Żuk | Version number stamped on the body ("wersja gaźnika jest wbita po drugiej stronie"); ver.1 has emulsion tubes 6/2 + 6/2, ver.3 has 5/3 + 5/4 | [FORUM] zlombol.pl. Low–medium |

### Chronology

- The factory manuals show this order: **Jikov 40 SOP (1974) → 34S2B1 (1977 Nysa / 1985 Żuk) → 28/35 S2A with solenoid (1989) → 28/35 S2B1 with economiser (1994).**
- [SHOP] Eter-Mot labels the "34 S2B1" as "Żuk (nowy typ)" (new type) and one "28/35 S2A1" as "Żuk (stary typ)" (old type). Its repair-kit listings mix these labels: "34 S2A1, 34 S2B1" is for "Żuk ST", while "28/35 S2A1" is for "Żuk NT".
- **Conflict:** Eter-Mot's ST/NT labels do not match the manual chronology. "NT/ST" may refer to body or chassis generations rather than carburettor age. Treat with caution. Sources: https://eter-mot.abc24.pl/kategoria/43853-zuk-czesci and http://eter-mot.abc24.pl/default.asp?kat=-3&klucz=S2

### Idle cut-off solenoid (elektrozawór / "elektrodysza")

- **Not present** in the 1985 34S2B1 factory description, drawing or jet table.
- **Present** on the 28/35 S2A (1989) and 28/35 S2B1 (1994) as the **EZ-20**. It carries the primary idle jet.
- Its purpose is to stop run-on after the ignition is switched off. Polish: "eliminuje możliwość samozapłonu silnika po wyłączeniu stacyjki".
- [FACTORY] 1989 and 1994 manuals.
- See how-it-works.md for the roadside get-you-home trick.

### Choke type

- All factory-described variants use a **separate cold-start device** ("urządzenie rozruchowe"), operated by a cable from the cab.
- It has its own fuel jet ("F1/150") and air jet (150). It is not a choke flap in the main throats.
- Photos of 34S2B1 and 28/35 units show no choke flap in the throats (`images/a-28-35-s2a-gn1113-top-roda24.jpg`).
- [FACTORY] 1985/1989/1994 tables. See specs-and-jets.md.

## 4. Air filter

- [FACTORY] The Nysa 522 manual (1977) says the Weber version uses a dry air filter with a replaceable element "typu Fiat 125P". The Jikov version uses a mesh/oil-bath type.
- The 1994 Żuk manual describes a summer/winter intake flap (cold air versus air heated from the exhaust area).
- Source: https://archive.org/download/zsd-1977-instrukcja-obslugi-nysa-522/ZSD-1977-instrukcja_obslugi_Nysa_522.pdf

## 5. Gaps

- No factory document seen for the 34S2A1, 34S2A2 or 34S2C variants.
- No source seen for Warszawa 223/224 or Tarpan factory carburettor tables. Only shops say the same unit fits them.
- The FOS Łódź versus Polmo Łomianki question is unresolved.
