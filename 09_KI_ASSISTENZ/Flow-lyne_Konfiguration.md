# KI-Assistenz: Flow-lyne Anrufassistent

Dieses Dokument dient als Referenz für die Konfiguration und Optimierung des persönlichen Anrufassistenten von Familie Adler.

## System-Verhalten & Logik
Der Assistent fungiert als intelligenter Filter für eingehende Anrufe mit folgender Priorisierung:
1. **Positivliste**: Bekannte Kontakte werden sofort durchgestellt.
2. **Negativliste**: Bekannte Spam-Nummern werden sofort abgelehnt.
3. **Intelligenter Filter**: Unbekannte Nummern werden nach Quelle und Grund befragt.

## Kontaktlisten (Referenz für KI)

### Priorisierte Kontakte (Sofort durchstellen)
| Name | Kategorie | Notiz |
| :--- | :--- | :--- |
| **Markus & Natalie** | Familie | Inhaber |
| **Steffen Brenscheidt** | Familie | Schwager |
| **Gaby & Patrick** | Freunde | Enge Freunde |
| **Monika Schimmel** | Nachbarn | Enge Nachbarin |
| **Katharina Bohn** | Nachbarn | Nachbarin & Friseurin |
| **Dr. Weber / Dr. Hücking** | Gesundheit | Hausarzt / Zahnarzt |

### Spam-Schutz (Sofort ablehnen)
Der Assistent erkennt und blockiert Anrufe basierend auf:
- **Schlüsselwörtern**: Gewinnspiel, Versicherung, Microsoft Support, Energie-Wechsel.
- **Quellenprüfung**: "Woher haben Sie unsere Nummer?" (Ablehnung bei Kaltakquise/Datenbanken).

## Optimierungspotenzial
Die aktuelle Eingabemaske für die KI ist eingeschränkt. Zukünftige Optimierungen sollen:
- Die Erkennung von legitimen Quellen verfeinern.
- Die Gesprächsführung (Phase 1-4) natürlicher gestalten.
- Eine separate Wissensdatenbank-Schnittstelle für die KI bereitstellen.
