# Fähigkeiten & Expertise - Markus Adler

## Status
✅ Vollständig

## Zusammenfassung
Übersicht über alle Fähigkeiten, Kompetenzen und technische Expertise von Markus Adler. Besonderer Fokus auf Smart Home/Home Automation als Wettbewerbsvorteil für Sionic.

---

## 💼 Kernkompetenzen

### Vertrieb & Sales
- Lead-Generierung & Qualifizierung
- Pipeline-Management (150+ Leads bei Sionic)
- Kundenakquise (B2B-Fokus: Architekten, Bauherren, Wohnungsunternehmen)
- Verhandlungsgeschick & Überzeugungskraft
- Multi-Channel-Strategie (LinkedIn, E-Mail, Telefon)
- Kundenbeziehungsmanagement (CRM: Weclapp)

### Business Development
- Geschäftsentwicklung & Marktanalysen
- Wettbewerbsbeobachtung
- Partnerschaften & Kooperationen aufbauen
- Multiplikatoren-Netzwerk (Energieberater, Architekten)
- Neue Geschäftsfelder identifizieren
- Förderungen & Finanzierungen (KfW, BAFA)

### E-Commerce & Digital
- **250% Umsatzsteigerung** bei Loevenich Fashion (2021-2024)
- Multi-Channel-Strategie (40+ Marktplätze)
- Shopify, Amazon, eBay, Zalando, Aboutyou
- PPC-Strategien (Google Ads, Facebook Ads)
- 200.000+ SKUs, 50.000+ Kunden verwaltet

### Projektmanagement
- **"From Lab to Fab" Expertise:** Skalierung von ISO 5 Cleanroom zur 1,5-Meter-Produktion
- Strategische Planung & Umsetzung
- Prozessoptimierung
- Teamführung & Schulung
- Stakeholder-Management

### Datenanalyse & Reporting
- KPI-Tracking & Dashboards
- Datenvisualisierung
- Reporting an Geschäftsleitung
- Prozessoptimierung durch Datenanalyse
- EDI-Schnittstellen (EDIFACT seit 2007)

---

## 🏠 Smart Home & Home Automation ⭐ WETTBEWERBSVORTEIL!

### Umfang & Expertise

**Eigenes Smart Home System:**
- **100+ Geräte** integriert (Zigbee, WLAN, Bluetooth Mesh)
- **Home Assistant Green** (Core 2025.12.3, OS 16.3)
- **Netzwerk:** 2x Unifi AP AC Pro, Speedport Pro Router, 3 SSIDs
- **Zigbee:** SkyConnect Coordinator, Zigbee2MQTT
- **Vollständige Dokumentation:** https://github.com/Mad71-admin/home-assistant-knowledge

**Integrierte Geräte:**
- **Kameras:** 2x Reolink Argus PT Ultra + Hub (ersetzt Arlo)
- **Heizung:** Homematic IP (HmIP-HAP + 5 Thermostate, RaspberryMatic)
- **Energie:** Growatt PV-Anlage (4x 410W), ShineWiFi-X Data Logger
- **Wallbox:** Heidelberg Energy Control Plus (geplant)
- **WLAN-Geräte:** Shelly 1 Mini Gen3 (Wechselschaltung)
- **Bluetooth:** AwoX Mesh (EGLO-Lichter)
- **ESP32:** Integration (Status: in Arbeit)

**Automationen:**
- Badlüftung (Feuchtigkeitssensor-gesteuert)
- Türbenachrichtigungen
- PV-Energie-Optimierung
- Heizungssteuerung
- Energiemonitoring

**Netzwerk-Expertise:**
- **ADLERHORST_MAIN** (Hauptnetzwerk, 2.4 + 5 GHz)
- **ADLERHORST_IOT** (Smart-Home, nur 2.4 GHz)
- **ADLERHORST_GUEST** (Gäste, isoliert)
- **Zigbee-Netzwerk** (SkyConnect, Zigbee2MQTT)

### Relevanz für Sionic & PDLC-Folien

**Technische Glaubwürdigkeit:**
- Spreche aus eigener Erfahrung über Home Automation
- Verstehe Integration von Smart-Geräten in Gebäudeautomation
- Kann technische Herausforderungen einschätzen
- Kenne verschiedene Protokolle (Zigbee, WLAN, KNX, Modbus)

**Produktdifferenzierung:**
- Nicht nur PDLC-Folien verkaufen, sondern **intelligente Lösungen**
- Integration in bestehende Smart-Building-Systeme
- Automationen für Komfort & Energieeffizienz
- Energieeinsparung durch intelligente Steuerung

**Wettbewerbsvorteil:**
- Viele Vertriebsmitarbeiter kennen nur das Produkt
- Ich verstehe die **gesamte Integration**
- Kann Kunden bei Implementierung beraten
- Authentischer Botschafter für Smart Building

**Use Cases für PDLC-Folien:**

1. **Büro-Besprechungsraum:** Automatische Privatsphäre während Meetings
   - Trigger: Kalender-Event "Meeting"
   - Aktion: PDLC-Folien → milchig
   - Ende: Meeting vorbei → transparent

2. **Wohnung-Badezimmer:** Privatsphäre beim Betreten
   - Trigger: Tür geschlossen + Licht an
   - Aktion: PDLC-Folien → milchig
   - Ende: Tür geöffnet → transparent

3. **Hotel-Energieeffizienz:** Sonnenschutz & Privatsphäre kombiniert
   - Trigger: Hohe Sonneneinstrahlung
   - Aktion: PDLC-Folien → milchig (Hitzeschutz)
   - Vorteil: Klimaanlage sparen

**Beispiel Home Assistant Automation (YAML):**
```yaml
automation:
  - alias: "PDLC Badezimmer Privatsphäre"
    trigger:
      - platform: state
        entity_id: binary_sensor.badezimmer_tuer
        to: 'off'  # Tür geschlossen
    condition:
      - condition: state
        entity_id: light.badezimmer
        state: 'on'  # Licht an
    action:
      - service: switch.turn_on
        entity_id: switch.pdlc_badezimmer  # PDLC milchig
```

---

## 💻 Technische Fähigkeiten

### ERP & CRM-Systeme
- **Weclapp** (CRM/ERP bei Sionic, 150+ Leads)
- **WAWI** (Warenwirtschaft)
- **IT-Waren-Einzelhandel**
- **CleverReach** (E-Mail-Marketing-Integration)

### E-Commerce-Plattformen
- **Shopify** (BASIC, PLUS, ADVANCED)
- **Amazon** (Seller Central, FBA)
- **eBay** (Verkäufer-Account)
- **Marktplätze:** Aboutyou, Zalando, Otto, Check24, Hood, Kaufland, Limango, etc. (40+ Channels)
- **JTL-Webshop**

### Marketing & Advertising
- **Google Ads** (PPC-Strategien)
- **Facebook Ads** (Social Media Marketing)
- **LinkedIn** (Sales Navigator, < 500 Zeichen, Subject Line)
- **SEO/SEM**

### Design & Kreativ-Tools
- **Adobe Creative Cloud:**
  - Photoshop (Bildbearbeitung)
  - Illustrator (Vektorgrafik)
  - InDesign (Layout)

### Projektmanagement & Kollaboration
- **MS Teams** (Kommunikation, Meetings)
- **Slack** (Team-Kommunikation)

### Bürosoftware
- **MS Office:**
  - Excel (Datenanalyse, Pivot-Tabellen)
  - Word (Dokumentation)
  - PowerPoint (Präsentationen)
  - Outlook (E-Mail, Kalender)

### Weitere technische Fähigkeiten
- **EDI-Schnittstellen** (EDIFACT-Standard seit 2007)
- **Dashboards** (Datenvisualisierung, Reporting)
- **Supply-Chain-Management**
- **Prozessoptimierung**
- **Datenanalyse** (KPIs, Trends, Muster)

---

## 🌍 Branchen-Expertise

### Smart Glass Technologie (Sionic, seit 2025)
- ClimaVision® Produktfamilie
- Mikro- und Nanotechnologie
- Energieeffizienz & CO₂-Reduktion
- Gebäudetechnik & Smart Buildings
- PDLC-Folien (schaltbare Privatsphäre)

### Fashion & Textil
- **Loevenich Fashion GmbH** (2017-2024) - Unternehmen wurde aufgekauft, existiert nicht mehr
  - Executive Assistant
  - E-Commerce-Entwicklung (250% Umsatzsteigerung)
  - Multi-Channel-Strategie (40+ Marktplätze)
  - 200.000+ SKUs, 50.000+ Kunden
- **Hänsel Textil GmbH, Iserlohn** (1993-1995)
  - Kaufmännischer Angestellter
  - Stellvertretender Abteilungsleiter Wickelei
  - Sachbearbeiter Einkauf
  - Disponent Arbeitsvorbereitung

### Einkauf & Assistenz
- **Fiebig GmbH & Co. KG, Iserlohn** (1996-2017)
  - Einkaufsassistent
  - Assistent der Geschäftsleitung
  - EDI-Schnittstellen (EDIFACT seit 2007)

### Gebäudetechnik & Energieeffizienz
- **Smart Home** (eigenes Projekt, seit Jahren)
  - 100+ Geräte integriert
  - Energie-Monitoring (PV-Anlage, Wallbox)
  - Heizungssteuerung (Homematic IP)
  - Automationen (Badlüftung, PV-Optimierung)

---

## 🗣️ Sprachkenntnisse

### Deutsch
- **Niveau:** Muttersprache
- **Verwendung:** Alle Geschäftskommunikation, Präsentationen, Verhandlungen

### Englisch
- **Niveau:** Fließend/Verhandlungssicher
- **Verwendung:** Internationale Geschäftskommunikation, technische Dokumentation



---

## 🎓 Soft Skills

### Kommunikation
- **Präsentationsfähigkeiten:** Pitch-Decks, Kundenpräsentationen
- **Verhandlungsgeschick:** B2B-Verhandlungen, Vertragsabschlüsse
- **Überzeugungskraft:** Authentische Botschafter-Rolle
- **Aktives Zuhören:** Bedarfsanalyse, Kundenverständnis

### Führung & Teamwork
- **Teamführung:** Schulung und Begleitung von Mitarbeitenden
- **Kollaboration:** Abteilungsübergreifende Zusammenarbeit
- **Mentoring:** Unterstützung bei Einführung neuer Tools
- **Motivation:** Spirit and drive für Teams

### Persönliche Eigenschaften
- **Analytisches Denken:** Datenanalyse, KPI-Tracking
- **Problemlösung:** Prozessoptimierung, Fehlersuche
- **Anpassungsfähigkeit:** Schnelles Erfassen neuer Technologien
- **Begeisterungsfähigkeit:** Technologie, Innovation, Daten
- **Authentizität:** "Trust, Trust, Trust" Prinzip
- **Kontinuierliches Lernen:** Zertifikate, Weiterbildung

---

## 🏆 Besondere Stärken

### "From Lab to Fab" Expertise
- **Erfahrung:** Skalierung von ISO 5 Cleanroom zur 1,5-Meter-Produktion bei Loevenich
- **Relevanz für Sionic:** Markteinführung von ClimaVision®, Skalierung der Produktion
- **Fähigkeit:** Innovative Konzepte in skalierbare Marktlösungen transformieren

### Smart Home Journey als Authentizitäts-Fundament
- **Erfahrung:** Mehrfamilienhaus schrittweise transformiert (Alexa → Home Assistant)
- **Relevanz für Sionic:** PDLC-Folien-Automationen, Smart Building Integration
- **Fähigkeit:** Praktische Expertise macht mich zum authentischen Botschafter

### Multi-Channel-Strategie
- **Erfahrung:** 40+ Marktplätze bei Loevenich, LinkedIn-Strategie bei Sionic
- **Relevanz:** Kundenakquise über verschiedene Kanäle
- **Fähigkeit:** Personalisierte Ansprache (< 500 Zeichen), Follow-up-Strategie

### Technische Glaubwürdigkeit
- **Erfahrung:** ERP-Systeme, EDI-Schnittstellen, Smart Home Technologien
- **Relevanz:** Verständnis für Sionic's Mikro- und Nanotechnologie
- **Fähigkeit:** Komplexe Technologien verständlich kommunizieren

---

## 🔗 Externe Ressourcen

### GitHub-Repositories
- **Home Assistant Knowledge:** https://github.com/Mad71-admin/home-assistant-knowledge
  - 100+ Geräte dokumentiert
  - Automationen, Netzwerk, Energie-Monitoring
  - Referenz für PDLC-Folien-Integration

### Zertifikate
- **2024:** E-Commerce Checkliste (D-SHOP.NRW, TH OWL)
- **2023:** E-Commerce Verkaufstechnik (alle Abschnitte erfolgreich)
- **2007:** EDIFACT-Standard (Fieberg GmbH & Co. KG)

---

## Letzter Update
**Datum:** 2025-01-15  
**Quelle:** Lebenslauf, Bewerbung, E-Commerce Entwicklung Loevenich

## Notizen für zukünftige Tasks
- **Smart Home Expertise:** Immer als Wettbewerbsvorteil hervorheben!
- **"From Lab to Fab":** Erfahrung mit Skalierung nutzen
- **Multi-Channel:** LinkedIn (< 500 Zeichen, Subject Line), E-Mail, Telefon
- **Technische Glaubwürdigkeit:** 100+ Geräte, komplexe Automationen
- **Authentizität:** "Trust, Trust, Trust" Prinzip
