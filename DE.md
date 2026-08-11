# Fares Boulahmi

**Backend-Entwickler / Software-Ingenieur**

📍 Tunis, Tunesien · ✉️ [boulahmifares@gmail.com](mailto:boulahmifares@gmail.com) · 📱 +216 96 520 768 [LinkedIn](https://www.linkedin.com/in/fares-boulahmi-342b61268/) · [GitHub](https://github.com/fares-boulahmi) · [Portfolio](https://fares-boulahmi.github.io/Portfolio/)

---

## Profil

Backend-fokussierter Full-Stack-Entwickler mit 13 Monaten Praxiserfahrung auf 7 Kundenplattformen, basierend auf einem proprietären Framework ohne öffentliche Dokumentation. Übernimmt konsequent die schwierigsten, am wenigsten definierten Probleme im Team – undokumentierte APIs, produktive Finanzsysteme, Framework-Interna, die sonst niemand verstanden hat – und dokumentiert die Lösung anschließend für die Wiederverwendung. Startete mit reiner MERN-Stack-Erfahrung ohne Framework-Schulung und wurde zur Ansprechperson, von der das restliche Team und spätere neue Mitarbeiter das Framework lernten.

**Kernstärken:**

- Entwickelt und repariert Backend-Systeme (APIs, Auth, Zahlungen, Datenmodelle) in undokumentierten, unkonventionellen Frameworks ohne vorherige Erfahrung mit dem jeweiligen Stack.
- Übernimmt Verantwortung für die risikoreichsten, am wenigsten definierten Probleme im Team – Live-Finanzdaten, undokumentierte Drittanbieter-APIs, nicht erfasste Framework-Interna.
- Verwandelt undokumentierte Systeme in wiederverwendbares Wissen – durch Dokumentation und Schulung anderer Entwickler, statt Fachwissen für sich zu behalten.

**Nachgewiesene Wirkung (Beispiele):**

- Ladezeit einer zeitüberschreitenden Suchseite auf **unter 1 Sekunde** reduziert, durch Entfernen unbegrenzter Pro-Request-Abfragen und Einführung von Pagination.
- Ein **abgestürztes produktives Finanz-Dashboard** auf einer 4 Jahre alten Live-Datenbank repariert – **ohne riskante Schreibvorgänge**, mittels selbstheilender Datenzugriffe statt einer Massenmigration.
- Eine Codebasis zu einem Multi-Tenant-Plugin-System umstrukturiert und das Onboarding neuer Kunden von individueller Entwicklungsarbeit auf **Zero-Code-Konfiguration** über **5 Live-Deployments** skaliert.
- Diagnosezeit eines stillen Konfigurationsfehlers von **einem ganzen Tag auf unter 30 Sekunden** reduziert, durch Überarbeitung der Onboarding-Checkliste zur Kennzeichnung jedes stillen Fehlerschritts.
- Die **einzige je existierende Dokumentation** für ein undokumentiertes proprietäres Framework verfasst – detailliert genug, um KI-gestützte Backend-Codegenerierung dafür erstmals zu ermöglichen.

---

## Technische Fähigkeiten

| Kategorie | Fähigkeiten |
|---|---|
| Programmiersprachen | JavaScript (Node.js), Python |
| Backend | Node.js, REST-API-Design, JWT-Authentifizierung & rollenbasierte Zugriffskontrolle, WebSocket, Server-Sent Events, Webhooks |
| Datenbank | MongoDB (Schemadesign, selbstheilende Migrationsmuster) |
| Frontend | Vue.js 2, Vuex, Vuetify, Tailwind CSS, Liquid (serverseitiges Templating), Tiptap |
| Integrationen | Zahlungs-Gateways (Konnect), Drittanbieter-REST-APIs (isHosting), SMTP, Scrapy |
| Sonstiges | Framework-Reverse-Engineering, technische Dokumentation, Git |
| Sprachen | Arabisch (Muttersprache), Englisch (verhandlungssicher), Deutsch (B1) |

---

## Berufserfahrung

### CyberOcean — Full-Stack-Entwickler (Backend-Schwerpunkt)

**Aug. 2024 – Sep. 2025 · Tunis, Tunesien**

CyberOcean ([cyberocean.net](https://cyberocean.net/w/)) betreibt ein proprietäres, hausinternes Framework – Vue 2 für authentifizierte Dashboard-Seiten, Liquid für öffentliche Seiten ohne Authentifizierung, Node.js, MongoDB mit einem eigenen ORM sowie eine eigene API-/Endpoint-Schicht – eingesetzt auf 7 Kundenplattformen in den Bereichen E-Learning, E-Commerce und Hosting. Einstieg mit Vorerfahrung ausschließlich im MERN-Stack, ohne Framework-Schulung oder vorhandene Dokumentation.

- Von null Erfahrung mit Vue 2, Liquid oder dem hauseigenen ORM/API-Layer zu produktiven Features auf 7 Kundenplattformen – durch Reverse-Engineering bestehender interner Projekte, da keine Schulung oder Dokumentation existierte.
- Vollständige Nutzungsdokumentation für jede Vue-2-Komponente des Frameworks verfasst, mit jedem real vorkommenden Anwendungsmuster (jeweils durch 2+ Live-Implementierungen oder Debugging-Sessions verifiziert) – die Referenz, auf die neue Entwickler und ich selbst weiterhin zurückgreifen.
- Die einzige je existierende interne Dokumentation für CyberOcean Engine v2 verfasst, detailliert genug, um KI-gestützte Backend-Codegenerierung dafür erstmals zu ermöglichen.
- 2 Entwickler vollständig im Framework-Workflow geschult, darunter einen ohne Vorerfahrung in der Entwicklung, bis zur eigenständigen produktiven Arbeit.

#### ComparePlus — Plattform zum Vergleich medizinischer Preise

_[compareplus.tn](https://compareplus.tn/p/web/) · Seite nicht mehr öffentlich verfügbar (Produkt eingestellt); Screenshots auf Anfrage_

Aggregiert Angebote medizinischer Produkte über Apotheken-E-Commerce-Seiten, nach Preis sortiert, mit einem Pay-per-Click-Modell für Partnerseiten.

- Ladezeit einer zeitüberschreitenden Suchseite auf unter 1 Sekunde reduziert, durch Entfernen unbegrenzter Pro-Request-Abfragen und Einführung von Pagination. _Geschäftlicher Nutzen:_ Kernsuchfunktion der Plattform für alle Nutzer wiederhergestellt.
- Zwei Kernfunktionen, die durch einen still fehlschlagenden Cache-Aufruf blockiert waren, durch einen Timeout-Fallback auf direkte Datenbankabfragen entsperrt – ohne das fehlerhafte Subsystem anzufassen.
- Die Token-Logik des Dashboards per Reverse-Engineering erschlossen, um den ersten öffentlichen Auth-Flow der Plattform (Login, Registrierung, Profil) zu bauen, da das Framework außerhalb des Dashboards keine native Authentifizierung unterstützte.
- Ein verschachteltes Analyse-Superdashboard (Partnerausgaben, CPC-Bereiche, Budget, Umsatz) mit clientseitigem Caching und Hintergrundaktualisierung entwickelt. _Geschäftlicher Nutzen:_ dem Unternehmen erstmals Echtzeit-Einblick in Partnerausgaben und Plattformumsatz verschafft.

#### Elios Academy — Online-Lernplattform

_[eliosacademy.com](https://www.eliosacademy.com/)_

Lernplattform für ein Nachhilfezentrum (~80 Lehrkräfte; der Inhaber allein hat über 1.000 Kurse und 200.000+ Follower), die spontane Google-Meet-Sitzungen durch strukturierte Live-Kurs-Terminierung ersetzte.

- Einen Layout-Fehler auf der öffentlichen Startseite für mobile Geräte behoben – dem meistbesuchten Einstiegspunkt der Plattform. _Geschäftlicher Nutzen:_ eine auf Smartphones unbrauchbare Seite in eine funktionierende Erstkontaktseite für den mobilen Traffic des Zentrums verwandelt.
- Den undokumentierten Profil-Update-Flow des Frameworks per Reverse-Engineering erschlossen (der sichtbare API-Endpunkt entsprach nicht dem tatsächlich ausgeführten Code), um die erste funktionierende individuelle Profilseite des Frameworks zu liefern.
- Ein vollständiges Ticketsystem von Grund auf gebaut (Prioritätsstufen, Anhänge, verschachtelte Kommentare), das zum primären Kanal des Teams für die Protokollierung und Behebung von Produktionsproblemen wurde.
- Dashboard-UI pixelgenau nach Kundendesigns umgesetzt, in einem Framework ohne zugängliche Styling-Ebene, durch elementweisen Abgleich des generierten CSS – eine Genauigkeit, die der Kunde explizit lobte.

#### You Learn — E-Learning-Plattform

_[you-learn.tn](https://you-learn.tn/p/home) · Dashboard: [app.you-learn.tn](https://app.you-learn.tn/)_

Kommerzielle E-Learning-Plattform für ein tunesisches Design-/3D-Bildungszentrum zum Online-Verkauf seines Kurskatalogs.

- 9 Kern-Datenmodelle sowie den kompletten Backend-/Dashboard-/Public-Stack allein in ca. 6 Monaten konzipiert und ausgeliefert, auf einem Framework ohne jegliche Dokumentation.
- Die vollständige Zahlungspipeline (Katalog → Gateway → Einschreibung) inklusive Webhook-Verarbeitung und Transaktions-Audit-Trail gebaut. _Geschäftlicher Nutzen:_ ersten Online-Verkaufskanal für Kurse des Zentrums ermöglicht.
- Liquids Unfähigkeit zu rekursivem/verschachteltem Rendering gelöst, indem bedingte Logik in die Controller-Ebene verlagert wurde, wodurch Templates auch bei komplexer Seitenlogik flach blieben.
- Ein Testimonial-System von Grund auf konzipiert und gebaut (Backend-Modell, Admin-UI, öffentliche Darstellung), wo zuvor keines existierte, und der Startseite damit erste Social-Proof-Inhalte verschafft.

#### White-Label-Multi-Tenant-E-Learning-Plattform

_svtghdiri.tn · smart-academy.tn · makeduc.tn · podiumeco.tn · formaticacademy.com_

Produktisierte Multi-Tenant-Version einer bestehenden E-Learning-Codebasis, unter separaten Domains für Schulungszentren bereitgestellt.

- Eine Single-Client-Codebasis zu einem Multi-Tenant-Plugin-System umstrukturiert und das Onboarding neuer Kunden von individueller Entwicklungsarbeit auf Zero-Code-Konfiguration über 5 Live-Deployments reduziert.
- Einen stillen Konfigurationsfehler diagnostiziert, der ein Kundenteam zuvor einen vollen Tag zur Nachverfolgung gekostet hatte, und die künftige Diagnosezeit durch Kennzeichnung jedes stillen Fehlerschritts in der Onboarding-Checkliste auf unter 30 Sekunden reduziert.
- Vollständige Integrations-/Deployment-Dokumentation verfasst, detailliert genug, dass ein Teammitglied ohne Entwicklungshintergrund ein komplettes Kunden-Onboarding ohne Code-Eingriff durchführen konnte.
- Ein vollständiges Plugin zur Sitzungsplanung gebaut (Rollen für Lehrer/Schüler/Admin, kursverknüpfte Sitzungen) als eigenständiges Add-on, das in jedem Kunden-Deployment wiederverwendet wird.

#### Alyis — Cloud-Hosting-Reseller-Plattform

_[alyis.ee](https://alyis.ee/p/en/home) · Admin: cloud.alyis.ee · funktional vollständig, vor öffentlichem Launch bei Projektende_

Storefront und Admin-Dashboard für einen Cloud-Hosting-Reseller, der VPS/Dedicated Server im Großhandel von isHosting bezieht und weiterverkauft.

- Die gesamte Anwendung allein aus einem leeren Repository heraus gebaut – Datenmodelle, API-Schicht, Admin-Dashboard, Storefront – mit Ausnahme des gekauften Frontend-Templates.
- Eine undokumentierte, ratenbegrenzte Hosting-API per Reverse-Engineering erschlossen, deren Produktdaten nicht mit den Anforderungen des eigenen Kaufendpunkts übereinstimmten, indem jeder Kauf als eigenständiger Validierungs-/Token-Refresh-Schritt behandelt wurde. _Geschäftlicher Nutzen:_ einen unzuverlässigen Drittanbieter-Vertrag in einen funktionierenden Checkout-Flow verwandelt.
- Ein datenbankgestütztes Übersetzungssystem mit Standardsprachen-Fallback entworfen, nachdem jede fertige Lokalisierungsbibliothek das Framework-Kernsystem zu beschädigen drohte – vollständige Mehrsprachigkeit ohne Änderungen am Framework-Kern.
- Die gesamte bedingte Desktop-Navigationslogik der Website in Liquid ohne verfügbare Skriptebene von Hand gebaut – der umfangreichste und logisch dichteste Code der öffentlichen Website.

#### EliClass — Plattform für Bildungsfinanzen & Anwesenheit

_Intern, Single-Account-System – keine öffentliche URL verfügbar_

Interne Plattform zur Verwaltung von Lehrergehältern, Schülerzahlungen und Anwesenheit für ein tunesisches Bac-Prüfungsvorbereitungszentrum, 4 Jahre im produktiven Einsatz.

- Ein abgestürztes Lehrer-Verdienst-Dashboard repariert, verursacht durch fehlende Felder in Datensätzen aus der Zeit vor einer Schemaänderung, mittels selbstheilender defensiver Lesevorgänge statt einer Massenmigration auf einer 4 Jahre alten produktiven Finanzdatenbank. _Geschäftlicher Nutzen:_ Dashboard ohne jegliche Schreibvorgänge auf historische Zahlungsdaten wiederhergestellt.
- Einen druckbaren Anwesenheitslisten-Generator von Grund auf gebaut (Auswahl nach Lehrer/Gruppe/Schüler, flexible Terminierung, PDF-Export).
- Ein Feature zur Umsatz-/Gewinnberichterstattung von Grund auf gebaut (datumsgefilterte Einnahmen + vollständiges Transaktionsprotokoll), als Ersatz für die zuvor manuelle Erfassung durch das Zentrum.
- Beide Features größtenteils allein in ca. 1 Monat geliefert, während der Rest des Teams an einem separaten, größeren Projekt gebunden war.

#### Yasso Design — Marketingplattform für Bildungseinrichtung

_[yassodesign.tn](https://yassodesign.tn/p/home) · allein, ca. 2 Wochen_

Portfolio-/Marketing-Website für ein CAD-/Figma-/3D-Design-Bildungszentrum.

- 4 zentrale, dashboard-gesteuerte Bereiche von nicht funktionsfähigen Template-Demos in eine vollständig admin-editierbare Startseite umgebaut, ohne funktionierende Basis.
- Den kompletten Umbau allein in ca. 2 Wochen als einziger verfügbarer Entwickler geliefert, während der andere Entwickler des Teams am primären Umsatzprojekt des Unternehmens gebunden war. _Geschäftlicher Nutzen:_ Kunde konnte ausliefern, ohne Ressourcen von höher priorisierter Arbeit abzuziehen.
- Echtzeit-Kontaktformular- und Lead-Erfassungs-Flows gebaut, die als Live-Benachrichtigungen im Admin-Dashboard erscheinen.

---

## Ausbildung

### BTS Informatique et Gestion — Höheres technisches Diplom, IT & Management

**IPSET (Institut Pilote des Sciences Économiques et de Technologie), Tunesien** Sep. 2021 – Dez. 2023 (Abschluss verliehen 2024)

**Abschlussprojekt — Interne Job-Mobilitätsplattform für La Poste Tunisienne**

- Eine interne Plattform mit SSO-integrierter Authentifizierung gebaut, über die das Management interne Stellenausschreibungen veröffentlichen und Mitarbeiter sich direkt mit Lebenslauf-Upload bewerben können – ein zweiseitiges Dashboard mit Echtzeit-Statusbenachrichtigungen für Bewerber und vollständiger Bewerberverwaltung für Manager. _Ergebnis:_ vollständig funktionsfähig ausgeliefert, entsprechend den internen Anforderungen von La Poste für staatlich regulierte Projekte – Arbeit, die La Poste angesichts ihrer Größe und Compliance-Anforderungen sonst extern vergibt – mit lediglich Design-Feinschliff und formalen Sicherheitstests als verbleibenden Schritten vor der Bereitstellung.
