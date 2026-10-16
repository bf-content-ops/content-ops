---
# Wird automatisch aus der Cockpit-Zeile befüllt
id:
typ: integrations-artikel
thema:
keyword:
supporting_keywords: []
zielfragen: []
referenz_urls: []    # Pflicht: offizielle Dokumentation oder Produktseite des Systemherstellers
ziel_url:
meta_title:          # max. 60 Zeichen inkl. " | BOTfriends"
meta_description:    # 120 bis 155 Zeichen, Sie-Form, Handlungsaufforderung
interne_links: []    # Pflicht: Hub-Seite des Clusters, /produkt/integrationen/, Branchenseite, passende Use-Case-Artikel
eingehende_links: []    # 2 bis 3 bestehende Seiten, die nach Veröffentlichung hierher verlinken
entscheidung:          # neuer Artikel / Update bestehender Seite / zusammenführen
custom_instructions:
schema: [Article, FAQPage, BreadcrumbList]
# Integrations-spezifisch
system:              # z. B. "Wilken ENER:GY"
hersteller:          # z. B. "Wilken Software Group"
branche:             # z. B. "Stadtwerke"
---

<!--
TEMPLATE-REGELN
- Länge gesamt: 1.200 bis 1.800 Wörter.
- Status und Anbindungsart des Systems NUR aus wissen/10-integrationen.md. Steht das System dort nicht oder mit Status "ungeprüft": Outline anhalten und [FEHLT: Integrationsstatus {system}] melden.
- Unterscheide immer sauber:
  - "im Live-Betrieb bei Kunden angebunden"
  - "technisch über Schnittstelle (API, Middleware) anbindbar"
  Nie eine offizielle Partnerschaft, Zertifizierung oder "native Integration" behaupten, wenn sie nicht in wissen/10 steht.
- Angaben zum System selbst (Funktionen, Schnittstellen) nur aus "referenz_urls", also aus Herstellerquellen, mit Abrufdatum.
- Der Hersteller ist kein Wettbewerber: Name nennen ist erlaubt, Logos nicht. Keine Wertung des Systems.
- Alle Regeln aus wissen/01, wissen/07 und den harten Regeln der Projekt-Anweisung gelten.
-->

# {system} in einen Chatbot oder Voicebot integrieren

## {Hauptfrage, z. B. "Lässt sich {system} mit einem Chatbot oder Voicebot verbinden?"}
<!--
Box "Auf einen Blick", 40 bis 60 Wörter.
Antwort mit Status aus wissen/10 und Bedingung, z. B. "Ja, über … Voraussetzung ist …".
-->

## Was ist {system}?
<!-- 60 bis 100 Wörter, neutral, mit Quelle des Herstellers. Für wen es gedacht ist und welche Rolle es im Kundenservice spielt. -->

## Welche Prozesse sich mit {system} automatisieren lassen
<!--
Tabelle: Prozess | Lesen oder Schreiben im System | Kanal | Status (live / möglich).
4 bis 8 Prozesse, passend zur Branche aus wissen/04.
Prozesse mit eigenem Use-Case-Artikel intern verlinken.
-->

## Wie die Anbindung technisch funktioniert
<!--
150 bis 250 Wörter, verständlich für IT-Leitung und Fachbereich.
Anbindungsart laut wissen/10 (direkte API, Middleware, Webhook), Authentifizierung, welche Daten fließen, wo die Daten verarbeitet werden.
Keine Schnittstellendetails erfinden; was nicht belegt ist: [PRÜFEN: …].
-->

## Projektablauf in fünf Schritten
<!--
Nummerierte Schritte: Schnittstellenzugang klären, Prozesse priorisieren, Daten-Mapping und Dialoge bauen, Test mit echten Fällen, Go-live mit Monitoring.
Je Schritt, wer beteiligt ist: Kunde, Systemhersteller, BOTfriends.
-->

## Was Sie vorab klären sollten
<!-- Checkliste mit 4 bis 6 Punkten, z. B. Lizenz für die Schnittstelle, Ansprechpartner beim Hersteller, Testsystem, Datenschutz, Rollen und Rechte. -->

## Datenschutz und Sicherheit
<!-- 80 bis 150 Wörter, nur Aussagen aus wissen/02 (Hosting, Anonymisierung, Guardrails). -->

## So setzt BOTfriends das um
<!--
PFLICHTABSCHNITT, 100 bis 200 Wörter.
Kunde, der dieses System angebunden hat, aus wissen/03 und wissen/10. Gibt es keinen: ehrlich als "technisch anbindbar" beschreiben und auf vergleichbare Projekte verweisen.
-->

## Häufige Fragen
<!--
4 bis 6 Fragen, darunter "Kann man {system} mit einem Voicebot verbinden?" und "Welche Prozesse lassen sich in {system} automatisieren?".
Format exakt beibehalten (Basis für FAQPage).
-->

### {Frage 1}
{Antwort}

## Fazit
<!-- 2 bis 3 Sätze + CTA, Link auf /produkt/integrationen/ und auf die Hub-Seite des Clusters. -->
