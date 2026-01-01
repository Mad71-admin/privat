# Erkenntnisse zur Kalender-Synchronisation (iPhone & Outlook)

## Problemstellung
Die Synchronisation zwischen dem nativen iPhone-Kalender und Outlook am PC war instabil, insbesondere bei Verwendung von Microsoft-Konten, die auf Drittanbieter-E-Mails (@t-online.de) basieren.

## Lösung: Der Alias-Weg
Um die automatische IMAP-Einrichtung in Outlook zu umgehen (die keine Kalender synchronisiert), wurde ein Outlook-Alias erstellt:
- **Konto:** markus-adler@t-online.de
- **Neuer Alias:** markus.adler.kalender@outlook.de
- **Vorteil:** Durch den Alias erkennt Outlook das Konto sofort als **Exchange-Konto**, was eine bidirektionale Kalender-Synchronisation ermöglicht.

## Einbindung von iCloud-Kalendern in Outlook
Für geteilte Familien-Kalender (iCloud) im "neuen Outlook":
1. Apple-ID (auch wenn es eine t-online Adresse ist) als neues Konto hinzufügen.
2. **App-spezifisches Passwort** von appleid.apple.com verwenden.
3. Dies ermöglicht die Anzeige von iCloud-Kalendern direkt neben den Outlook-Kalendern.

## Konten-Struktur (Stand Jan 2026)
- **Business:** Markus.Adler@sionic.de (Exchange)
- **Privat Sync:** markus.adler.kalender@outlook.de (Exchange-Alias für t-online Abo)
- **E-Mail Archiv:** markusadler-iserlohn@t-online.de (IMAP)
- **Familie:** iCloud-Einbindung über Apple-ID

Datum der Einrichtung: 01.01.2026
