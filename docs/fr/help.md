# Aide

**Lumidepth Player VR** lit sur votre Meta Quest les vidéos VR180, VR360 et 2D enregistrées sur votre PC ou sur le NAS de votre domicile. Un modèle d'IA estime la profondeur de chaque image : les objets proches et lointains se décalent naturellement lorsque vous bougez la tête.

## Configuration requise

- Windows 10 / 11 (64 bits)
- NVIDIA GeForce RTX 3060 ou plus récent (RTX séries 30 / 40 / 50)
- Casque Meta Quest connecté via Meta Quest Link (câble) ou Air Link
- Vidéo : MP4, MKV, MOV, WebM. H.265 (HEVC), H.264 (jusqu'à 4K), AV1, VP9, ProRes
- 8 à 12 bits, 4:2:0 / 4:2:2 / 4:4:4, HDR (HDR10, HLG). Les vidéos HDR sont affichées en SDR
- Sur les RTX séries 30 / 40, le 4:2:2 et le ProRes sont décodés par le processeur : la lecture en 8K 60 i/s peut ne pas suivre (les RTX série 50 les décodent sur le GPU)

## Premiers pas

1. Lancez l'application Meta Quest Link sur votre PC et connectez votre Quest avec Link ou Air Link.
2. Ouvrez Lumidepth Player VR depuis la Bibliothèque de votre Quest.
3. Les lecteurs de votre PC apparaissent dans la liste. Pour parcourir un dossier partagé sur un NAS, connectez-le comme lecteur réseau dans Windows.
4. Sélectionnez une vidéo avec la gâchette droite pour lancer la lecture. La première fois que vous utilisez la 3D, l'IA est préparée pour votre PC, ce qui peut prendre quelques minutes (c'est ensuite instantané).

## Commandes

| Bouton | Liste | Pendant la lecture |
|---|---|---|
| Gâchette droite | Choisir / maintenir et déplacer pour défiler | Afficher la barre de lecture / appuyer sur un bouton |
| A | Remonter d'un dossier | Revenir à la liste |
| B | Remonter d'un dossier | Activer / désactiver la 3D |
| Y | – | Lecture / pause |
| X | – | Afficher / masquer la ligne d'état |
| Joystick droit gauche/droite | – | −10 s / +10 s |
| Joystick gauche gauche/droite | – | −60 s / +60 s |
| Clic du joystick droit | – | Recentrer |
| Maintenir la poignée droite et déplacer | – | Faire pivoter la vidéo |

## Barre de lecture et réglages

Pendant la lecture, appuyez sur la gâchette droite pour afficher la barre de lecture à l'endroit visé. Elle contient le volume, le zoom, 3D activé/désactivé, Recentrer et Réglages (⚙).

Le panneau Réglages comporte trois pages :

- **Affichage** : Luminosité, Netteté, Anticrénelage
- **3D** : Profondeur 3D (intensité), Alignement des contours, Bords, Remplissage des vides, Stabilisation, Fréquence de mise à jour, Fenêtre, 3D pour 2D/mono
- **Format** : Projection (180°, 360°, Plat) et Disposition (Côte à côte, Haut/bas, Unique). Le format est détecté automatiquement à partir du nom du fichier et du rapport d'aspect ; ne le choisissez manuellement que si l'image semble incorrecte (s'applique uniquement à la vidéo en cours).

L'effet de profondeur fonctionne le mieux avec les vidéos VR180 côte à côte.

## Dépannage

- **« Votre Meta Quest n'est pas connecté. »** : connectez votre Quest avec Link ou Air Link, puis réessayez.
- **« Aucun GPU NVIDIA (GeForce RTX série 30 ou plus récent) détecté. »** : mettez à jour votre pilote NVIDIA. Un GPU RTX série 30 ou plus récent est nécessaire.
- **La 3D affiche « indisponible »** : la mémoire de votre GPU est peut-être insuffisante. Fermez les autres applications.
- **L'image apparaît dédoublée ou coupée en deux** : choisissez la Projection et la Disposition dans la page Format des Réglages.

Contact : [hello@monneural.dev](mailto:hello@monneural.dev)
