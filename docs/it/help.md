# Guida

**Lumidepth Player VR** riproduce sul tuo Meta Quest i video VR180, VR360 e 2D salvati sul PC o sul NAS di casa. Un modello di IA stima la profondità di ogni fotogramma, così gli oggetti vicini e lontani si spostano in modo naturale quando muovi la testa.

## Requisiti

- Windows 10 / 11 (64 bit)
- NVIDIA GeForce RTX 3060 o successiva (serie RTX 30 / 40 / 50)
- Visore Meta Quest collegato tramite Meta Quest Link (cavo) o Air Link
- Video: MP4, MKV, MOV, WebM. H.265 (HEVC), H.264 (fino a 4K), AV1, VP9, ProRes
- Da 8 a 12 bit, 4:2:0 / 4:2:2 / 4:4:4, HDR (HDR10, HLG). I video HDR vengono mostrati in SDR
- Sulle serie RTX 30 / 40, i formati 4:2:2 e ProRes vengono decodificati dalla CPU, quindi l'8K a 60 fps potrebbe non essere fluido (la serie RTX 50 li decodifica con la GPU)
- Film 3D: affiancati, 3D sequenziale, video spaziali (MV-HEVC) e Blu-ray 3D (MVC in MKV). Vengono riconosciuti automaticamente e mostrati in 3D su uno schermo davanti a te. Il Blu-ray 3D viene decodificato dalla CPU (serve una CPU con AVX2; altrimenti viene riprodotto in 2D)

## Per iniziare

1. Avvia l'app Meta Quest Link sul PC e collega il Quest con Link o Air Link.
2. Avvia Lumidepth Player VR dalla Libreria del Quest.
3. Nell'elenco compaiono le unità del PC. Per sfogliare una cartella condivisa del NAS, connettila come unità di rete in Windows. Per un server multimediale (DLNA) della tua rete domestica, scegli «Server multimediali (DLNA)» nell'elenco.
4. Seleziona un video con il grilletto destro per avviare la riproduzione. La prima volta che usi il 3D, l'IA viene preparata per il tuo PC: può richiedere qualche minuto (le volte successive è immediato).

## Comandi

| Pulsante | Libreria | Durante la riproduzione |
|---|---|---|
| Grilletto destro | Seleziona / tieni premuto e muovi per scorrere | Mostra la barra di riproduzione / premi un pulsante |
| A | Cartella superiore | Torna alla libreria |
| B | Cartella superiore | Attiva/disattiva il 3D |
| Y | – | Riproduci / pausa |
| X | – | Mostra / nascondi la riga di stato |
| Levetta destra sinistra/destra | – | −10 s / +10 s |
| Levetta sinistra sinistra/destra | – | −60 s / +60 s |
| Pressione della levetta destra | – | Ricentra |
| Tieni premuto il grip destro e muovi | – | Ruota il video |

## Barra di riproduzione e opzioni

Durante la riproduzione, premi il grilletto destro per mostrare la barra di riproduzione nel punto in cui stai puntando. Contiene volume, zoom, 3D sì/no, Ricentra e Opzioni (⚙).

Il pannello Opzioni ha tre pagine:

- **Schermo**: Luminosità, Nitidezza, Antialiasing
- **3D**: Profondità 3D, Allineamento bordi, Bordi, Riempimento vuoti, Stabilizzazione, Frequenza di aggiornamento, Finestra, 3D per 2D/mono
- **Formato**: Proiezione (180°, 360°, Piatto) e Disposizione (Affiancato, Sopra/sotto, Singola). Vengono rilevate automaticamente dal nome del file e dalle proporzioni; scegli manualmente solo se l'immagine non sembra corretta (vale solo per il video corrente).

L'effetto di profondità rende al meglio con i video VR180 affiancati (side by side).

## Risoluzione dei problemi

- **"Il tuo Meta Quest non è collegato"**: collega il Quest con Link o Air Link e riprova.
- **"Nessuna GPU NVIDIA (GeForce RTX serie 30 o successiva) trovata"**: aggiorna il driver NVIDIA. È necessaria una GPU RTX serie 30 o successiva.
- **Il 3D mostra "non disponibile"**: la memoria della GPU potrebbe essere insufficiente. Chiudi le altre app.
- **L'immagine appare doppia o divisa**: scegli Proiezione e Disposizione nella pagina Formato delle Opzioni.

Contatti: [hello@monneural.dev](mailto:hello@monneural.dev)
