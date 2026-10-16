# Branchen und Use Cases

Zweck: Was Leser je Branche bewegt, welche Prozesse BOTfriends dort automatisiert, welche Systeme beteiligt sind und welche Begriffe die Zielgruppe benutzt.
Grundlage für Use-Case-Seiten, Praxisbeispiele und den Pflichtabschnitt "So setzt BOTfriends das um".
Regeln:
- Use Cases mit "live" sind bei Kunden im Betrieb. Use Cases mit "Demo" gibt es als Vorführung, sie dürfen nicht als Kundenprojekt dargestellt werden.
- Systemnamen nur aus dieser Datei, immer im passenden Kontext.
- Kunden und Zahlen nur nach wissen/03-referenzkunden.md.
- Branchenseiten: Verlinkt werden die Seiten aus der Hauptnavigation unter /loesungen/. Ältere Seiten unter /branchen/ existieren noch, werden aber nicht verlinkt.

## Übergreifende Messaging-Regeln

- **Fallabschließend statt Auskunft:** Wo möglich zeigen, dass ein Anliegen im Fachsystem erledigt wird, nicht nur beantwortet.
- **Keine Multi-Intent-Erkennung behaupten.** Richtig: Der Orchestrator nimmt mehrere Anliegen auf, priorisiert sie und arbeitet sie nacheinander ab.
- **Mensch bleibt eingebunden:** Human Handover mit vollständigem Kontext gehört in jede Prozessbeschreibung.

---

## Energieversorger und Stadtwerke

- **Branchenseite:** /loesungen/stadtwerke-energieversorger/
- **Marktlage:** Fachkräftemangel, steigende Anfragen durch die Energiewende (Wärmepumpen, Smart Meter), veraltete IT-Strukturen.
- **Personas:**
  - **Leitung Kundenservice und Marktprozesse:** fürchtet Bots, die halluzinieren und rechtliche Folgen auslösen. Überzeugt durch Hybride Intelligenz und tiefe Automatisierung.
  - **IT-Leitung (CIO, CDO):** achtet auf KRITIS, Datenhoheit, Datensilos und Vendor Lock-in. Überzeugt durch Integration ohne Systemintegrator und technologische Unabhängigkeit.
  - **Projektleitung Prozessautomatisierung:** will Go-live in Wochen und keine Agentur-Abhängigkeit. Überzeugt durch No-Code und die BOTfriends Academy.
- **Use Cases:**

| Prozess | Status | Hinweis |
|---|---|---|
| Zählerstandsmeldung | live | Süwag (Chatbot), Stadtwerke Troisdorf (Chatbot und Phonebot) |
| Abschlagsanpassung | live | fallabschließend |
| Änderung der Bankverbindung (SEPA) | live | fallabschließend |
| Umzug melden | Demo | |
| Terminvereinbarung | Demo | |
| Tarifberatung | live | Süwag (Chatbot) |
| Anfragespitzen nach der Jahresabrechnung abfangen | [PRÜFEN] | |

- **Systeme:** SAP IS-U, Schleupen (Anbindung über ITC), d.velop (Dokumentenmanagement), Forcont (Archivierung)
- **Fachbegriffe der Zielgruppe:** Abschlag, Jahresverbrauchsabrechnung, Zählerstand, Erstlösungsquote, Netzbetreiber, Lieferantenwechsel, KRITIS
- **Praxiswissen:** Authentifizierung ist der häufigste Stolperstein, wenn Kundennummer und Zählernummer verlangt werden. [PRÜFEN: Freigabe für Artikel, siehe Stadtwerke Troisdorf in wissen/03]
- **Eigene Daten:** Benchmark-Report "Stadtwerke Kundenservice" (Ausgabe 2026, Neuauflage 2027). Zahlen nur aus dem Report.
- **Referenzen:** Stadtwerke Bielefeld (Phonebot), Stadtwerke Fürstenfeldbruck (Phonebot), Stadtwerke Karlsruhe (Chatbot), Süwag (Chatbot), Stadtwerke Troisdorf (Chatbot und Phonebot), TWS (Chatbot); als Name: RWE, SWM, N-ERGIE, Sachsen Energie

## Wohnungswirtschaft

- **Branchenseite:** /loesungen/immobilien-wohnungswirtschaft/
- **Use Cases:**

| Prozess | Status | Hinweis |
|---|---|---|
| Verifizierung der Mieter am Telefon | live | TAG Wohnen |
| Schadensmeldung mit Ticket im Ticketing-Tool | live | TAG Wohnen |
| Havarie: gefährliche Schäden sofort an den Notdienst | live | TAG Wohnen, per fester Regel |
| Routing an den richtigen Fachbereich, z. B. Vermietung | live | TAG Wohnen |
| Terminvereinbarung für Handwerker und Besichtigungen | Demo | |
| Mietbescheinigung anfordern | Demo | Demo auch auf Schwäbisch |
| Adressänderung, Umzug | [PRÜFEN] | |
| Allgemeine Mieteranfragen | [PRÜFEN] | |

- **Systeme:** Für Copy zuerst die primären Systeme nennen, sie decken einen großen Teil des DACH-Markts ab.
  - **Primär:** Aareon (Wodis Yuneo, wowinex, Blue Eagle) als Kern-ERP; PROMOS und SAP als Kern-ERP bei mittleren und großen Wohnungsunternehmen; immo-office für Instandhaltung, Ticketing und Handwerkeranbindung; DATASEC für Dokumentenmanagement und Mieterakten
  - **Erweitert:** Haufe axera, DOMUS (DOMUS ERP, DOMUS 4000); Mieterportale casavi und EASYSQUARE
  - **Formulierung:** Systeme im passenden Kontext nennen, z. B. "Egal ob Mieter-Ticketing oder Kern-ERP".
- **Architektur-Argument:** Die Multi-Agent-Architektur kapselt Systemabfragen als klar getrennte Teilaufgaben. Das macht fallabschließende Prozesse mit mehreren Systemen verlässlich.
- **Fachbegriffe der Zielgruppe:** Mieteranliegen, Schadensmeldung, Instandhaltung, Bestandsverwaltung, Mieterportal, Handwerkersteuerung
- **Referenzen:** TAG Wohnen, VBW Wohnen, Hansa Wohnen (alle Phonebot); Kennzahlen zu TAG Wohnen in wissen/03

## ÖPNV und Verkehr

- **Branchenseite:** /loesungen/oepnv-verkehrswesen/
- **Use Cases (laut Branchenseite):** Fahrplanauskunft, Störungsmeldungen und Anfragespitzen bei Betriebsstörungen, Ticket- und Tariffragen, Fundsachen [PRÜFEN: welche davon live bei Kunden?]
- **Referenzen:** Augsburger Verkehrsbetriebe (Chatbot), VAG Nürnberg (nur als Name)
- [FEHLT: Systeme, Fachbegriffe, live umgesetzte Prozesse]

## E-Commerce und Handel

- **Branchenseite:** /loesungen/e-commerce/
- **Use Cases:**

| Prozess | Status | Hinweis |
|---|---|---|
| Höhere Volumina in saisonalen Spitzen abfangen | live | Frankonia (Chatbot) |
| Bestellstatus und Sendungsverfolgung | Demo | Hörprobe auf der Startseite |
| Produktberatung im Gespräch | [PRÜFEN] | |

- **Referenzen:** Lascana, Frankonia (beide Chatbot)
- [FEHLT: angebundene Shop- und Warenwirtschaftssysteme]

## Tourismus

- **Use Cases:**

| Prozess | Status | Hinweis |
|---|---|---|
| Gästekommunikation an Bord | live | TUI Cruises |
| FAQ-Automatisierung | live | vTours |
| Buchung direkt im System | live | a&o Hostels |

- **Wichtig:** Im Tourismus gibt es bisher keine Voice-Projekte im Live-Betrieb. Keine Voice-Referenz in dieser Branche behaupten.
- **Referenzen:** TUI Cruises, vTours, a&o Hostels
- **Branchenseite:** /loesungen/tourismus/

## Healthcare: Medizinversand und Homecare

- **Fokus:** Medizinversand und Homecare, nicht Praxen und Kliniken.
- **Use Cases:**

| Prozess | Status | Hinweis |
|---|---|---|
| Patientenidentifikation | Demo | |
| Lieferstatus abfragen | Demo | |
| Nachbestellung auslösen | Demo | |
| Rücksendung vereinbaren | Demo | |

- **Referenzen:** Geria+med (Phonebot)
- **Branchenseite:** /loesungen/healthcare/
- [FEHLT: live umgesetzte Prozesse]

## Branchenübergreifend

- **Kundenservice allgemein:** Telefon-, Chat- und E-Mail-Volumen entlasten, mit kontrollierter Übergabe an Mitarbeitende. Seite: /loesungen/kundenservice-automatisieren/
- **Interne Prozesse und HR:** Mitarbeitenden- und Bewerberanfragen. Seite: /loesungen/hr-personalwesen/ [FEHLT: Referenz]
- **Öffentliche Einrichtungen:** FAQ aus der Wissensbasis und Weiterleitung mit Prüfung der Öffnungszeiten (Demo)

## Weitere Branchen mit Referenz

- **Ticketing und Events:** Lastspitzen bei Vorverkaufsstarts abfangen, Ticketbestellung vollständig im Gespräch, Status des Ticketversands, SMS mit Buchungs- und Zahlungslinks. Referenz: Ticket Online (toss), Voicebot.
- **Hersteller und Vertrieb:** Erreichbarkeit außerhalb der Bürozeiten, Leads vorqualifizieren und an Pre-Sales übergeben, Serviceanliegen selbst beantworten. Referenz: ZAPF Garagen, Phonebot.
- **Medien und Verlage:** Serviceanliegen von Abonnenten per Voicebot. Referenz: IPPEN.MEDIA. Seite: /loesungen/presse-verlagswesen/
