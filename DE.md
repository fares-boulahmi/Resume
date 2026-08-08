# Fares Boulahmi

**Backend Developer / Software Engineer**

📍 Tunis, Tunesien · ✉️ [boulahmifares@gmail.com](mailto:boulahmifares@gmail.com) · 📱 +216 96 520 768 [LinkedIn](https://www.linkedin.com/in/fares-boulahmi-342b61268/) · [GitHub](https://github.com/fares-boulahmi) · [Portfolio](https://fares-boulahmi.github.io/Portfolio/)

---

## Profil

Backend-orientierter Full-Stack Developer mit über einem Jahr Berufserfahrung in der Entwicklung von 7 Kundenplattformen — E-Learning-Systeme, ein Preisvergleichsportal für medizinische Produkte und eine Cloud-Hosting-Reseller-Plattform — auf einem firmeneigenen Framework ohne öffentliche Dokumentation. Übernahm regelmäßig die schwierigsten und am wenigsten definierten Probleme im Team: undokumentierte Drittanbieter-APIs, produktive Finanzsysteme mit echten Kundendaten und interne Framework-Strukturen, die niemand sonst verstanden hatte — und dokumentierte die Lösungen anschließend, damit das restliche Team sie weiterverwenden konnte. Wurde zum internen Framework-Experten und schrieb die einzige existierende interne Dokumentation für das Unternehmens-Framework; bildete außerdem zwei Entwickler aus, darunter einen ohne vorherige Erfahrung in der Softwareentwicklung, bis zur eigenständigen Produktionsreife.

---

## Kenntnisse & Fähigkeiten

- **Programmiersprachen:** JavaScript (Node.js), Python
- **Backend:** Node.js, REST-API-Design, JWT-basierte Authentifizierung & rollenbasierte Zugriffskontrolle, WebSocket, Server-Sent Events, Webhook-Verarbeitung
- **Datenbank:** MongoDB (Schemadesign, selbstheilende Migrationsmuster)
- **Frontend:** Vue.js 2, Vuex, Vuetify, Tailwind CSS, Liquid (serverseitiges Templating), Tiptap
- **Integrationen:** Zahlungsanbieter (Konnect), Drittanbieter-APIs (isHosting), SMTP/E-Mail-Systeme, Scrapy
- **Sonstiges:** Reverse Engineering von Framework-Internas, technische Dokumentation, Git
- **Sprachen:** Arabisch (Muttersprache), Französisch (fließend), Englisch (berufliches Arbeitsniveau), Deutsch (B1)

---

## Berufserfahrung

### CyberOcean — Full-Stack Developer (Schwerpunkt Backend)

**Aug 2024 – Sep 2025 · Tunis, Tunesien**

CyberOcean ([cyberocean.net](https://cyberocean.net/w/)) ist ein Softwareunternehmen, das ein firmeneigenes Web-Framework (CyberOcean Engine v2 — Vue 2 + Liquid + Node.js + MongoDB) entwickelt und pflegt, das in mehreren Kundenprojekten aus den Bereichen E-Learning, E-Commerce und Cloud-Hosting eingesetzt wird. Als alleiniger oder leitender Entwickler an 7 Kundenplattformen über  13 Monate beteiligt.

- Verfasste die einzige jemals geschriebene interne Dokumentation für CyberOcean Engine v2 — ein Framework ohne öffentliche Dokumentation, Community oder Support-Kanal — mit ausreichend technischer Tiefe, um erstmals KI-gestützte Backend-Codegenerierung für dieses Framework möglich zu machen.
- Bildete zwei Entwickler im gesamten Framework-Entwicklungsablauf aus, darunter einen ohne vorherige berufliche Entwicklungserfahrung, bis beide eigenständig produktiv arbeiten konnten.

#### ComparePlus — Preisvergleichsplattform für medizinische Produkte

_[compareplus.tn](https://compareplus.tn/p/web/) · Seite aktuell nicht mehr öffentlich (Produkt eingestellt); Screenshots auf Anfrage_

Aggregiert Angebote medizinischer Produkte über mehrere Apotheken-Websites, sortiert nach Preis, mit Pay-per-Click-Modell für Partnerseiten.

- Diagnostizierte eine Suchergebnisseite mit Timeout unter realer Last, indem unbegrenzte Datenbankabfragen pro Anfrage identifiziert wurden; führte Pagination ein und senkte die Ladezeit auf unter 1 Sekunde — stellte die Kernsuchfunktion für alle Nutzer wieder her.
- Behob zwei zentrale Funktionen (Preisalarme, Produktseiten), die durch einen stillschweigend fehlschlagenden Cache-Aufruf in einem Bereich ohne Schreibzugriff vollständig blockiert waren, durch Einführung eines Timeout-Mechanismus mit Fallback auf direkte Datenbankabfragen und Entkopplung des UI-Renderings vom Cache-Status — ohne Änderungen am fehlerhaften Subsystem selbst.
- Rekonstruierte die Token-Verifizierungslogik des Dashboards, um den ersten öffentlichen Authentifizierungsflow der Plattform (Login, Registrierung, Profil) zu entwickeln, da das Framework außerhalb des Dashboards keine native Unterstützung dafür bot — ermöglichte Login, Profilverwaltung und Kontaktformular auf der gesamten öffentlichen Seite.
- Entwickelte ein verschachteltes Analytics-Superdashboard (Partnerausgaben, CPC-Preisspannen, Budgetverbrauch, Umsatztrends, Klick- und Besucherzahlen) mit clientseitigem Caching und Hintergrundaktualisierung — verschaffte dem Unternehmen erstmals Echtzeit-Einblick in Partnerausgaben und Plattformumsatz.
- Migrierte öffentliche Seiten von Liquid zu Vue 2 und löste dabei einen fußzeilenbezogenen Scroll-/Höhenfehler durch manuelle geometrische Berechnung der Auslösepunkte, nachdem die Standard-Scroll-Erkennung vollständig versagt hatte.

#### Elios Academy — Online-Lernplattform

_[eliosacademy.com](https://www.eliosacademy.com/) ·_

Lernplattform für ein etabliertes Nachhilfezentrum (ca. 80 Lehrkräfte; der Inhaber allein hat über 1.000 Kurse und über 200.000 Follower), die improvisierte Google-Meet-Sitzungen durch strukturierte, nachverfolgbare Live-Kursplanung ersetzte.

- Behob einen Layoutfehler auf der öffentlichen Startseite — dem wichtigsten Einstiegspunkt der Plattform für Interessenten auf Mobilgeräten — und verwandelte eine zuvor auf Smartphones unbenutzbare Seite in eine funktionierende Erstkontaktseite für den mobilen Traffic des Zentrums.
- Rekonstruierte den undokumentierten internen Profil-Update-Ablauf des Frameworks, dessen sichtbarer API-Endpunkt nicht mit der tatsächlich ausgeführten Logik übereinstimmte, und lieferte damit die erste funktionierende individuelle Profilseite des Frameworks, inklusive fest gesperrtem E-Mail-Feld (Frontend und Backend).
- Entwickelte ein vollständiges Ticketsystem von Grund auf (Prioritätsstufen, Dateianhänge, verschachtelte Kommentare mit beidseitiger Löschberechtigung), das zum Hauptkanal des Teams für die Erfassung und Lösung von Produktionsproblemen wurde.
- Baute das Dashboard-UI passgenau nach kundenspezifischen Designs innerhalb eines Frameworks ohne zugängliche Styling-Ebene um und glich generiertes CSS Element für Element mit dem Zieldesign ab — eine UI-Präzision, die der Kunde ausdrücklich lobte.
- Entwickelte das Live-Session-Planungssystem (Sitzungserstellung durch Admins und Lehrkräfte, Ziel gruppen- oder einzelschülerbasiert, personalisierte automatische E-Mails), das Google-Meet-Links als Sitzungsmethode für die rund 80 Lehrkräfte des Zentrums ersetzte.

#### You Learn — E-Learning-Plattform

_[you-learn.tn](https://you-learn.tn/p/home) · Dashboard: [app.you-learn.tn](https://app.you-learn.tn/) ·_

Kommerzielle E-Learning-Plattform für ein tunesisches Design-/3D-Bildungszentrum zum Onlineverkauf des bestehenden Kurskatalogs.

- Entwarf und lieferte 9 zentrale Datenmodelle (Course, Category, Element, Purchase, Certificate, Student, OnlinePayment, Transaction, Review) sowie den kompletten Backend-, Dashboard- und Frontend-Stack allein in  6 Monaten, auf einem vollständig undokumentierten Framework.
- Entwickelte die komplette Zahlungspipeline — Katalog → Zahlungsanbieter → Kursfreischaltung — inklusive Webhook-Verarbeitung und Transaktionsprotokoll, und ermöglichte damit den ersten Online-Verkaufskanal des Kunden.
- Löste die fehlende Unterstützung rekursiver/verschachtelter Darstellung in Liquid (dynamische Werbeformate, verschachtelte Kursstrukturen, gefilterte Karussells), indem die Bedingungslogik in die Controller-Ebene statt in die Template-Ebene verlagert wurde — Templates blieben dadurch flach, trotz komplexer Seitenlogik.
- Entwarf und entwickelte ein Testimonial-System von Grund auf (Backend-Modell, Admin-UI, öffentliche Darstellung), obwohl kein Bewertungssystem existierte, und verschaffte der Startseite des Kunden damit erstmals Social-Proof-Inhalte.

#### White-Label Multi-Tenant E-Learning-Plattform

_[svtghdiri.tn](https://svtghdiri.tn/p/home) · [smart-academy.tn](https://smart-academy.tn/p/home) · [makeduc.tn](https://makeduc.tn/p/home) · [podiumeco.tn](https://podiumeco.tn/p/home) · [formaticacademy.com](https://www.formaticacademy.com/p/home) _

Produktisierte, mandantenfähige Version einer bestehenden E-Learning-Codebasis, unter separaten Domains für mehrere Bildungszentren bereitgestellt.

- Baute eine Single-Client-Codebasis zu einem Multi-Tenant-Plugin-System um und reduzierte das Onboarding neuer Kunden von individueller Entwicklung auf codefreie Dashboard-Konfiguration — im Einsatz bei 4+ zahlenden Kunden auf 5 aktiven Domains.
- Verfasste die vollständige Integrations- und Deployment-Dokumentation (Installation, Konfiguration, Pre-Launch-Checkliste, Testplan) so detailliert, dass ein Teammitglied ohne Entwicklungshintergrund ein komplettes Kunden-Onboarding ohne Code-Änderungen durchführen konnte.
- Identifizierte einen stillen Konfigurationsfehler, den ein Kundenteam zuvor einen ganzen Tag zur Diagnose brauchte, und reduzierte die Lösungszeit auf unter 30 Sekunden; überarbeitete danach die Onboarding-Checkliste, um alle Schritte ohne sichtbare Fehlermeldung explizit zu kennzeichnen — beseitigte diese Fehlerquelle dauerhaft.
- Entwickelte ein vollständiges Session-Planungs-Plugin (Rollen für Lehrkraft, Schüler, Admin; kursverknüpfte Sitzungen; Filterung nach Lehrkraft, Datum und Archivstatus) als eigenständiges Zusatzmodul, das bei allen Kundeninstallationen wiederverwendet wird.
- Lieferte die Konnect-Zahlungsintegration, einen mehrstufigen Registrierungs-/Aktivierungsablauf sowie rollenbasierte Authentifizierung (Student, Lehrkraft, Admin, Root) für alle Mandanten.

#### Alyis — Cloud-Hosting-Reseller-Plattform

_[alyis.ee](https://alyis.ee/p/en/home) · Admin: cloud.alyis.ee · funktionsfertig, vor öffentlichem Launch zum Ende des Projekts_

Cloud-Hosting-Reseller-Shop mit Admin-Dashboard für den Weiterverkauf von VPS-/dedizierten Servern, die im Großhandel von isHosting bezogen werden.

- Entwickelte die gesamte Anwendung allein aus einem leeren Repository heraus — Datenmodelle, API-Schicht, Admin-Dashboard, öffentlicher Shop — mit Ausnahme des gekauften Frontend-Templates.
- Rekonstruierte eine undokumentierte, ratenlimitierte Drittanbieter-Hosting-API, deren Produktdaten nicht mit den Anforderungen des eigenen Kauf-Endpunkts übereinstimmten, indem jeder Kaufvorgang als eigenständiger Validierungs-/Token-Refresh-Schritt behandelt wurde — machte aus einem instabilen API-Vertrag einen funktionierenden Checkout-Prozess.
- Entwarf ein datenbankgestütztes Übersetzungssystem mit Standard-Sprach-Fallback, nachdem jede vorgefertigte Lokalisierungsbibliothek den Framework-Kern zu beschädigen drohte, und lieferte damit vollständige Mehrsprachigkeit für den öffentlichen Katalog ohne jegliche Änderung am Framework selbst.
- Baute die gesamte bedingte Desktop-Navigationslogik der Seite manuell in Liquid, ohne Skriptebene zur Verfügung — der umfangreichste und logisch dichteste Code-Abschnitt der gesamten öffentlichen Seite.
- Entwickelte Echtzeit-Bestellstatus-Updates über WebSocket sowie eine vollständige Bestell-, Zahlungs- und Support-Ticket-Pipeline mit Retry-Logik für fehlgeschlagene Transaktionen.

#### EliClass — Finanz- und Anwesenheitsplattform für Bildungseinrichtungen

_Internes System mit Einzelzugang — keine öffentliche URL verfügbar · _

Internes Verwaltungssystem für Lehrergehälter, Schülerzahlungen und Anwesenheit eines tunesischen Baccalauréat-Prüfungsvorbereitungszentrums, seit 4 Jahren im Produktivbetrieb.

- Reparierte ein komplett abstürzendes Lehrergehalts-Dashboard, dessen Absturz durch fehlende berechnete Felder in Datensätzen verursacht wurde, die vor einer Schemaänderung angelegt worden waren — statt einer riskanten Massenmigration auf einer 4 Jahre alten produktiven Finanzdatenbank wurden selbstheilende Fallback-Lesevorgänge implementiert; stellte die Funktionalität ohne einen einzigen Schreibvorgang auf historische Zahlungsdaten wieder her.
- Entwickelte einen druckbaren Anwesenheitslisten-Generator von Grund auf (Auswahl von Lehrkraft/Gruppe/Schülern, flexible Terminplanung nach Wochentag oder monatlicher Anzahl, PDF-Export).
- Entwickelte eine Umsatz- und Ertragsberichtsfunktion von Grund auf (datumsgefilterte, kategorisierte Einnahmen plus vollständiges Transaktionsprotokoll nach Zahlungsart, Lehrkraft, Schüler und Status) — verschaffte dem Zentrum eine Finanzberichterstattung, die zuvor manuell erfolgen musste.
- Lieferte beide neuen Funktionen größtenteils allein in  1 Monat, während der Rest des Teams vollständig in einem separaten, größeren Projekt gebunden war.

#### Yasso Design — Marketing-Plattform für Design-Bildungszentrum

_[yassodesign.tn](https://yassodesign.tn/p/home) ·_

Portfolio-/Marketingwebsite für ein CAD-/Figma-/3D-Design-Bildungszentrum.

- Baute 4 zentrale, dashboardgesteuerte Bereiche (Themenauswahl, Aktionsverwaltung, animiertes Bewertungskarussell, Aktion des Monats) von nicht funktionierenden Template-Demos zu einer vollständig admin-editierbaren Startseite um — ohne funktionierende Vorarbeit.
- Lieferte den gesamten Umbau allein in  2 Wochen als einziger verfügbarer Entwickler, während der zweite Entwickler des Teams vollständig im umsatzstärksten Projekt des Unternehmens gebunden war — der Kunde konnte liefern, ohne Ressourcen von wichtigeren Projekten abzuziehen.
- Entwickelte Echtzeit-Kontaktformular- und Lead-Erfassungsabläufe, die als Live-Benachrichtigungen im Admin-Dashboard zur Nachverfolgung erscheinen.

---

## Ausbildung

### BTS Informatique et Gestion — Staatlich anerkannter Abschluss, IT & Management

**IPSET (Institut Pilote des Sciences Économiques et de Technologie), Tunesien** Sep 2021 – Dez 2023 (Abschluss verliehen 2024)

Zweijähriges, praxisorientiertes Studium in angewandter Informatik und IT-Management nach dem Baccalauréat.

**Abschlussprojekt — Internes Job-Mobilitätsportal für La Poste Tunisienne** Entwarf und entwickelte eine interne Webplattform, über die das Management der La Poste interne Stellenausschreibungen (Anforderungen, Vorteile, Standort) veröffentlichen kann und Mitarbeitende sich direkt über ihr bestehendes Firmenkonto (SSO-integrierte Authentifizierung) mit Lebenslauf-Upload bewerben können. Lieferte ein zweiseitiges Dashboard: Bewerbende verfolgen ihren Bewerbungsstatus (ausstehend/abgelehnt/angenommen) mit Echtzeit-Benachrichtigungen bei Entscheidungen, während Führungskräfte alle Bewerbungen pro Ausschreibung prüfen, filtern und verwalten können. Vollständig funktionsfähig geliefert und erfüllte die internen Präsentationsanforderungen von La Poste für staatlich regulierte Projekte — ein Projektumfang, den La Poste aufgrund der Größe und der staatlich verbundenen Compliance-Anforderungen sonst extern vergibt — es fehlten lediglich Design-Feinschliff und formale Sicherheitstests vor dem Rollout.

