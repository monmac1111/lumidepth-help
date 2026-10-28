# Informativa sulla privacy

**Lumidepth Player VR**

- Data di entrata in vigore: 19 ottobre 2026
- Ultimo aggiornamento: 28 ottobre 2026 (aggiunti i server della rete domestica)
- Fornitore: mon neural
- Contatti: [hello@monneural.dev](mailto:hello@monneural.dev)

Questa è una traduzione. In caso di discrepanze, prevale la [versione inglese](../en/privacy.md).

## 1. Informazioni raccolte

Non raccogliamo alcuna informazione personale, dato di utilizzo o contenuto video. L'app non comunica con i nostri server e non contiene pubblicità né strumenti di analisi.

## 2. Dati salvati sul tuo PC

I seguenti dati vengono salvati solo sul tuo PC e non vengono mai inviati altrove:

- Impostazioni (opzioni di visualizzazione e 3D, e indirizzi delle cartelle condivise e dei server che registri)
- Log diagnostici (non contengono nomi né percorsi dei file video)
- Dati del modello di profondità IA ottimizzati per la tua GPU
- Immagini di anteprima mostrate nella libreria video

Disinstallando l'app ed eliminando la cartella `%LOCALAPPDATA%\LumidepthPlayerVR` vengono rimossi tutti questi dati.

## 3. Piattaforma Meta

L'app è distribuita tramite lo store Meta e utilizza la piattaforma Meta per verificare l'acquisto. Le eventuali informazioni coinvolte sono gestite da Meta secondo l'[Informativa sulla privacy di Meta](https://www.meta.com/legal/privacy-policy/). Noi non le riceviamo.

## 4. Rete

Oltre alla verifica dell'acquisto, l'app si collega solo a:

- Unità e cartelle condivise che apri tu stesso (ad esempio un NAS nella tua rete domestica)
- Server che registri tu stesso (WebDAV, Jellyfin)
- Server multimediali (DLNA) trovati nella tua rete domestica. Per trovarli, l'app invia una richiesta di rilevamento (SSDP) nella tua rete domestica.

I nomi utente e le password dei server vengono letti da quanto hai salvato in Gestione credenziali di Windows. L'app non li memorizza e non li scrive mai nei log.

L'app si identifica presso i server Jellyfin con un ID di questo PC, così il server non mostra ogni volta un nuovo dispositivo. L'ID è un hash ricavato dall'ID del computer Windows; l'ID del computer non viene inviato.

## 5. Minori

L'app non raccoglie informazioni dai minori.

## 6. Modifiche

Eventuali modifiche a questa informativa verranno pubblicate su questa pagina.
