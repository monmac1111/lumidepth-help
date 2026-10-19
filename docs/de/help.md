# Hilfe

**Lumidepth Player VR** spielt VR180-, VR360- und 2D-Videos von deinem PC oder deinem NAS zu Hause auf deiner Meta Quest ab. Ein KI-Modell schätzt für jedes Einzelbild die Tiefe, sodass sich nahe und ferne Objekte natürlich verschieben, wenn du den Kopf bewegst.

## Systemanforderungen

- Windows 10 / 11 (64 Bit)
- NVIDIA GeForce RTX 3060 oder neuer (RTX 30 / 40 / 50 Serie)
- Meta Quest Headset, verbunden über Meta Quest Link (Kabel) oder Air Link
- Video: MP4, MKV, MOV, WebM. H.265 (HEVC), H.264 (bis 4K), AV1, VP9, ProRes
- 8 bis 12 Bit, 4:2:0 / 4:2:2 / 4:4:4, HDR (HDR10, HLG). HDR-Videos werden als SDR angezeigt
- Auf der RTX 30 / 40 Serie werden 4:2:2 und ProRes von der CPU dekodiert, daher kann 8K mit 60 fps ins Stocken geraten (die RTX 50 Serie dekodiert sie auf der GPU)

## Erste Schritte

1. Starte die Meta Quest Link-App auf deinem PC und verbinde deine Quest per Link oder Air Link.
2. Starte Lumidepth Player VR aus der Bibliothek deiner Quest.
3. Die Laufwerke deines PCs erscheinen in der Liste. Um einen freigegebenen NAS-Ordner zu durchsuchen, verbinde ihn in Windows als Netzlaufwerk.
4. Wähle ein Video mit dem rechten Trigger aus, um die Wiedergabe zu starten. Wenn du 3D zum ersten Mal nutzt, wird die KI für deinen PC vorbereitet. Das kann einige Minuten dauern (danach geht es sofort).

## Steuerung

| Taste | Bibliothek | Während der Wiedergabe |
|---|---|---|
| Rechter Trigger | Auswählen / gedrückt halten und bewegen zum Scrollen | Wiedergabeleiste einblenden / Schaltfläche drücken |
| A | Einen Ordner nach oben | Zurück zur Bibliothek |
| B | Einen Ordner nach oben | 3D ein/aus |
| Y | – | Wiedergabe / Pause |
| X | – | Statuszeile ein-/ausblenden |
| Rechter Stick links/rechts | – | −10 s / +10 s |
| Linker Stick links/rechts | – | −60 s / +60 s |
| Rechten Stick drücken | – | Zentrieren |
| Rechte Grifftaste halten und bewegen | – | Video drehen |

## Wiedergabeleiste und Optionen

Drücke während der Wiedergabe den rechten Trigger, um die Wiedergabeleiste dort einzublenden, wohin du zeigst. Sie enthält Lautstärke, Zoom, 3D an/aus, Zentrieren und Optionen (⚙).

Die Optionen haben drei Seiten:

- **Anzeige**: Helligkeit, Schärfe, Kantenglättung
- **3D**: 3D-Tiefe, Kantenausrichtung, Kanten, Lückenfüllung, Stabilisierung, Aktualisierungsrate, Fenster, 3D für 2D/Mono
- **Format**: Projektion (180°, 360°, Flach) und Anordnung (Nebeneinander, Übereinander, Einzeln). Beides wird automatisch anhand des Dateinamens und des Seitenverhältnisses erkannt. Wähle es nur dann manuell, wenn das Bild falsch aussieht (gilt nur für das aktuelle Video).

Der Tiefeneffekt wirkt am besten bei VR180-Videos im Format Nebeneinander.

## Fehlerbehebung

- **„Deine Meta Quest ist nicht verbunden.“**: Verbinde deine Quest per Link oder Air Link und versuche es erneut.
- **„Keine NVIDIA-GPU (GeForce RTX 30 oder neuer) gefunden.“**: Aktualisiere deinen NVIDIA-Treiber. Eine GPU ab der RTX 30 Serie ist erforderlich.
- **3D zeigt „nicht verfügbar“**: Möglicherweise hat deine GPU zu wenig freien Speicher. Schließe andere Apps.
- **Das Bild erscheint doppelt oder geteilt**: Wähle Projektion und Anordnung auf der Seite „Format“ in den Optionen.

Kontakt: [hello@monneural.dev](mailto:hello@monneural.dev)
