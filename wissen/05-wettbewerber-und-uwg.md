# Wettbewerber und § 6 UWG

Zweck: Wann und wie Wettbewerber in Artikeln genannt werden, wie über sie recherchiert wird und welche Positionierung BOTfriends je Wettbewerber einnimmt.
Grundlage: Master Prompt für die Vergleichsseiten "[Wettbewerber] Alternative".

## 1. Wo Wettbewerber genannt werden dürfen

- **Erlaubt und gewollt:** auf Vergleichsseiten, also Alternative-Seiten und Listicles unter /vergleich/.
- **Nicht erlaubt:** in allen anderen Artikeltypen (Ratgeber, VS-Artikel, Use-Case-Seiten, Daten-Artikel, Glossar, Thought Leadership). Dort ist allgemein von "Single-Prompt-Lösungen" oder "Anbietern mit Integrator-Modell" die Rede, ohne Namen.

## 2. Rechtlicher Rahmen nach § 6 UWG

Vergleichende Werbung ist zulässig, wenn sie sich auf objektiv nachprüfbare, wesentliche und relevante Eigenschaften bezieht und den Wettbewerber nicht herabsetzt. Daraus folgt:

- **Jede Aussage über einen Wettbewerber hat eine öffentliche Quelle** (Website, Dokumentation, Partnerseite, Pressemitteilung) mit URL und Abrufdatum. Ohne Quelle keine Aussage, stattdessen [FEHLT: Quelle].
- **Eigenschaften statt Wertungen.** Nicht "schlechter als", "veraltet", "umständlich", keine Häme, keine Ironie.
- **Gleiche Kriterien für beide Seiten.** In Vergleichstabellen werden BOTfriends und Wettbewerber nach denselben Kriterien bewertet; nur Eigenschaften für denselben Bedarf vergleichen.
- **Zitate des Wettbewerbers wörtlich**, besonders bei Hosting, Datenschutz und EU AI Act: übernehmen, nicht interpretieren.
- **Keine Wettbewerberpreise.** Sind Preise öffentlich, nur die Kostenstruktur beschreiben (Lizenz, Implementierung, Betreuung), nie konkrete Beträge des Wettbewerbers.
- **Keine Wettbewerber-Logos** ohne Erlaubnis.
- **Stand-Datum** unter jeder Vergleichstabelle; Vergleichsseiten werden halbjährlich geprüft.
- **Juristische Abnahme vor Livegang.** Am Ende jedes Entwurfs steht der Hinweis, dass die rechtliche Prüfung aussteht. Claude gibt nie selbst frei.

## 3. Pflicht-Recherche vor dem Schreiben

Pro Punkt 2 bis 4 gezielte Suchen, nicht eine breite Suche. Quelle und Abrufdatum jeder genutzten Aussage festhalten, sie kommen ins Quellenverzeichnis am Ende des Artikels.

| Punkt | Was klären |
|---|---|
| Umsetzungsmodell | intern, über Partner, Reseller oder System-Integratoren; Partnerprogramm vorhanden? |
| Eigentümerstruktur | übernommen, Teil eines Konzerns, Sitz des Mutterunternehmens (EU oder nicht EU); oft entscheidend für die Hosting- und EU-AI-Act-Argumentation |
| Architektur | Multi-Agent-Orchestrierung, Single-Prompt, klassische Flow-Logik oder hybrid |
| Hosting und Datenverarbeitung | Rechenzentren, On-Premise, Zertifizierungen, Aussagen zu DSGVO und EU AI Act (wörtlich) |
| Kanäle und Integrationen | Voice-Fokus oder Omnichannel; ausdrücklich genannte Integrationen |
| Preise | nur ob öffentlich und wie strukturiert, keine Beträge übernehmen |

Wettbewerberwissen veraltet schnell. Auch wenn unten eine Positionierung steht, werden die Fakten für jeden Artikel neu recherchiert.

## 4. Grundpositionierung

- **Kernbotschaft:** Plattform-Souveränität statt Integrator-Abhängigkeit (Guided Sovereignty): Das Team des Kunden baut selbst, Experten von BOTfriends unterstützen bei Komplexität.
- **Zweite Achse:** Multi-Agent-Orchestrierung und Hybride Intelligenz statt Single-Prompt, mit fallabschließenden Prozessen im Fachsystem.
- **Zielgruppe:** gehobener Mittelstand bis Enterprise. Abgrenzung über Prozesstiefe, nicht über Unternehmensgröße.
- **"Für wen BOTfriends nicht die richtige Wahl ist"** gehört auf jede Vergleichsseite, präzise am tatsächlichen Unterschied festgemacht (z. B. Bindung an ein bestehendes Partner-Ökosystem), nie pauschal. Dieser Abschnitt wird von KI-Suchen am ehesten zitiert, weil er neutral ist.

## 5. Positionierungsachsen je Wettbewerber

Die Achse ist der Blickwinkel des Artikels, keine Tatsachenbehauptung. Belegt wird sie jedes Mal mit aktuellen Quellen.

| Wettbewerber | Seite | Positionierungsachse |
|---|---|---|
| Cognigy | /vergleich/cognigy-alternative/ | Umsetzung über System-Integratoren vs. Plattform-Souveränität |
| Parloa | /vergleich/parloa-alternative/ | Fokus auf High-Enterprise und Partnermodell vs. Umsetzung durch das eigene Team ab gehobenem Mittelstand |
| Fonio.ai | /vergleich/fonio-ai-alternative/ | Vom Anrufannehmen zum Vorgangsabschluss; Single-Prompt-Architektur und Self-Service vs. Multi-Agent-Orchestrierung, Contact-Center-Integration und Governance. Primärquelle: Help Center von Fonio |
| moin.ai | /vergleich/moin-ai-alternative/ [PRÜFEN: Slug] | Textkanäle und FAQ-Automatisierung vs. Voice plus fallabschließende Prozesse |
| telli | [PRÜFEN: Slug] | Voice-only mit CRM-Fokus in einzelnen Branchen vs. Omnichannel-Plattform |
| melibo | [PRÜFEN: Slug] | Full-Service-Modell ohne Voice-Kanal vs. Guided Sovereignty mit Voice |
| Placetel AI | [PRÜFEN: Slug] | KI als Zusatz zur Cloud-Telefonanlage mit Single-Prompt vs. eigenständige AI Agent Plattform |

## 6. Bausteine für Vergleichsseiten

- **Preisanker BOTfriends** (nur für den Abschnitt Total Cost of Ownership): Starter ab 2.490 Euro im Monat, Mid-Market 40.000 bis 200.000 Euro im Jahr, Enterprise auf Anfrage [PRÜFEN: aktuell?]
- **Vertrauenssignal:** OMR-Reviews-Profil (https://omr.com/de/reviews/product/botfriends-x) zweimal verlinken: nach der Vergleichstabelle und im Fazit. Gesamtbewertung mit Stand aus wissen/09.
- **Referenzen mit Prozesstiefe** aus wissen/03, bevorzugt passend zur Branche des Wettbewerbers; Zahlen statt Behauptungen.
- **Beispiel für Hybride Intelligenz:** ein Schreibvorgang im Backend (Zählerstand, Adressänderung) passend zur Zielbranche, mit Link auf den Blogartikel zu Halluzinationen [FEHLT: URL].
- **Quellenverzeichnis** am Ende: jede Wettbewerber-Aussage einzeln mit URL und Abrufdatum, dazu der Hinweis auf halbjährliche Prüfung und ausstehende juristische Abnahme.

## 7. Prüfliste für Vergleichsseiten

- [ ] Jede Wettbewerber-Aussage hat Quelle und Abrufdatum
- [ ] Keine Wertung, keine Häme, keine unbelegte Behauptung
- [ ] Keine Preise des Wettbewerbers
- [ ] Vergleichstabelle mit gleichen Kriterien und Stand-Datum
- [ ] Abschnitt "Für wen BOTfriends nicht die richtige Wahl ist" vorhanden und neutral
- [ ] Enterprise-Eignung sichtbar, nicht nur Mittelstand
- [ ] Hinweis auf ausstehende juristische Abnahme am Ende
