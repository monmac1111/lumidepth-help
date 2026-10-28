# Datenschutzerklärung

**Lumidepth Player VR**

- Gültig ab: 19. Oktober 2026
- Zuletzt geändert: 28. Oktober 2026 (Server im Heimnetz ergänzt)
- Anbieter: mon neural
- Kontakt: [hello@monneural.dev](mailto:hello@monneural.dev)

Dies ist eine Übersetzung. Bei Abweichungen ist die [englische Fassung](../en/privacy.md) maßgeblich.

## 1. Welche Daten wir erheben

Wir erheben keine personenbezogenen Daten, keine Nutzungsdaten und keine Videoinhalte. Die App kommuniziert nicht mit unseren Servern und enthält weder Werbung noch Analysefunktionen.

## 2. Auf deinem PC gespeicherte Daten

Die folgenden Daten werden ausschließlich auf deinem PC gespeichert und niemals übertragen:

- Einstellungen (Anzeige- und 3D-Optionen sowie die Adressen der Freigaben und Server, die du einträgst)
- Diagnoseprotokolle (diese enthalten keine Namen oder Speicherorte von Videodateien)
- Für deine GPU optimierte Daten des KI-Tiefenmodells
- Vorschaubilder, die in der Videobibliothek angezeigt werden

Wenn du die App deinstallierst und den Ordner `%LOCALAPPDATA%\LumidepthPlayerVR` löschst, werden alle diese Daten entfernt.

## 3. Meta-Plattform

Die App wird über den Meta Store vertrieben und nutzt die Meta-Plattform, um deinen Kauf zu bestätigen. Die dabei verarbeiteten Informationen werden von Meta gemäß der [Meta-Datenschutzrichtlinie](https://www.meta.com/legal/privacy-policy/) behandelt. Wir erhalten sie nicht.

## 4. Netzwerk

Außer für die Kaufprüfung verbindet sich die App nur mit:

- Laufwerken und freigegebenen Ordnern, die du selbst öffnest (zum Beispiel ein NAS in deinem Heimnetz)
- Servern, die du selbst einträgst (WebDAV, Jellyfin)
- Medienservern (DLNA) in deinem Heimnetz. Um sie zu finden, sendet die App eine Suchanfrage (SSDP) in dein Heimnetz.

Benutzernamen und Passwörter für Server werden aus der Windows-Anmeldeinformationsverwaltung gelesen, in der du sie gespeichert hast. Die App speichert sie nicht und schreibt sie nie in Protokolle.

Gegenüber Jellyfin-Servern weist sich die App mit einer Kennung für diesen PC aus, damit der Server nicht jedes Mal ein neues Gerät anzeigt. Die Kennung ist ein Hashwert, der aus der Windows-Computer-ID gebildet wird; die Computer-ID selbst wird nicht gesendet.

## 5. Kinder

Die App erhebt keine Daten von Kindern.

## 6. Änderungen

Änderungen an dieser Datenschutzerklärung veröffentlichen wir auf dieser Seite.
