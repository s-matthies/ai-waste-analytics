# Datenübersicht Basis Daten

| **Spalte**  | **Erläuterung**                                                                                                                                  |
|-------------|--------------------------------------------------------------------------------------------------------------------------------------------------|
| **Monat**   | Monat der Anlieferung                                                                                                                           |
| **KW**      | Kalenderwoche der Anlieferung                                                                                                                    |
| **Jahr**    | Jahr der Anlieferung                                                                                                                            |
| **Datum**   | Datum der Anlieferung. Samstags und Sonntags werden in der Regel keine Bio-, Wertstoff- und Hausmüll-Abfälle gesammelt, außer es ist ein Nachladetag (z.B. nach einem Feiertag oder bei Ausfällen durch Krankheit oder Fahrzeugdefekt). |
| **Hof**     | Hof zu dem die Tour gehört: VMF = Hof Forckenbeckstraße, VMG = Hof Gradestraße, VMN = Hof Nordring, VMM = Hof Malmöer Straße, VMWSF = Spermüll der Forckenbeckstraße, VMWSM = Spermüll der Malmöer Straße, VMWSN = Spermüll des Nordrings |
| **Schicht** | Schicht der Tour                                                                                                                                |
| **Tour**    | Tournummer der anliefernden Tour. Jede Tour hat eine täglich rotierende Route, die sich alle zwei Wochen wiederholt. Spermülltouren haben keine festen Touren, da sie auf Auftragsbasis arbeiten. |
| **Tonnage** | Gelieferte Abfallmenge in Tonnen                                                                                                                 |
| **Abfallart** | Gelieferte Abfallart: BIO = Biomüll, HM = Hausmüll, SPM = Sperrmüll                                                              |

# Datenübersicht Delay & Ferien
- "0" bis "6" -> Montag bis Samstag
- Falls am Samstag abgeholt wurde, dann wird geschaut ob in der Woche ein Feiertag war es wird geschut welcher Feiertag und wie lange er her ist.
- 


# Notizen
- Basisdaten werden gemerget mit:
  - Wetterdaten
  - Inflationsdaten
  - Ausfall Abholung
  - Feiertagen
  - Wahldaten
  - Tourismusdaten (evtl.)(private Key sind die Monate)
- Falls eine Abholung ausfiel, aufgrund eines Feiertags oder eines Ausfalls wird die Ersatzabholung am folgenden Samstag stattfinden
- Die Tour (Basis_Daten) beschreibt vor allem die Teams und das Fahrzeug!
- 