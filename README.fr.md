# KPlayer

**Un lecteur vidéo gratuit et épuré, sans publicité.**

[English](README.md) · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md) · [Português (Brasil)](README.pt-BR.md) · Français

> Ce document est une traduction. En cas de divergence, la [version coréenne](README.ko.md) fait foi.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011%20x64-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
![Source](https://img.shields.io/badge/source-GPL--2.0--or--later-lightgrey)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/kplayer?lang=fr)

![Capture d'écran de KPlayer](images/kplayer-en.webp)

## Présentation

KPlayer est un lecteur vidéo et audio sans publicité ni superflu. Il repose sur le moteur multimédia open source **libmpv** : il lit donc d'emblée 38 formats — 23 formats vidéo, 12 formats audio et 3 formats de liste de lecture — sans installer le moindre codec.

La fenêtre n'affiche que la vidéo ; les commandes n'apparaissent en bas que lorsque vous bougez la souris. Déposez un fichier sur la fenêtre et la lecture commence, et quand vous ouvrez un épisode d'une série, les épisodes suivants du même dossier s'ajoutent à la liste dans l'ordre.

Tous les raccourcis clavier et toutes les actions de la souris sont modifiables, et les sous-titres se personnalisent en détail, jusqu'à la police, la couleur, le contour et la position.

## Fonctionnalités

- **38 formats** — 23 formats vidéo, dont MP4, MKV, AVI, MOV, WMV, WebM, TS, M2TS, VOB et RM/RMVB ; 12 formats audio, dont MP3, FLAC, AAC, M4A, WAV, OGG, Opus, WMA, APE et DSF ; et 3 formats de liste de lecture (M3U, M3U8, PLS).
- **Aucun codec à installer** — tout ce qu'il faut pour la lecture est inclus.
- **Accélération matérielle** — les vidéos haute résolution restent fluides.
- **Glisser-déposer** — déposez sur la fenêtre principale pour remplacer la liste et lancer la lecture aussitôt, ou sur la fenêtre de la liste de lecture pour ajouter à la liste. Déposez un dossier et seuls ses fichiers multimédias sont ajoutés.
- **Épisodes suivants ajoutés automatiquement** — ouvrir un fichier ajoute dans l'ordre les fichiers qui lui font suite dans le même dossier (Épisode 1, Épisode 2…).
- **Liste de lecture** — réorganisation par glisser, répétition (tout ou un seul), lecture aléatoire, et la liste est conservée après la fermeture du programme.
- **Sous-titres** — affichage/masquage, changement de piste, réglage de la police, de la taille, de la couleur, du gras, du contour, de l'ombre, de la position et de l'alignement, et choix automatique de la langue des sous-titres selon la langue d'affichage de Windows.
- **Contrôle de la lecture** — saut de chapitre, avance image par image, vitesse (0.25×–4.0×), captures d'écran (JPG/PNG).
- **Panneau d'informations** — appuyez sur `TAB` pour voir d'un coup d'œil les informations sur le fichier, le codec, la résolution, les images et l'audio.
- **Normalisation du volume** — réduit l'écart entre les sons faibles et forts (intensité réglable).
- **Raccourcis et souris personnalisables** — attribuez les touches de 30 actions et choisissez ce que font le clic, le double-clic, le bouton du milieu et la molette.
- **Associations de fichiers** — enregistrez chaque extension dans les Paramètres et ouvrez directement le sélecteur d'applications par défaut de Windows.
- **Interface épurée** — fenêtre sombre sans bordure, toujours au premier plan, position et taille de la fenêtre mémorisées.

## Téléchargement / Installation

| Paquet | Lien |
|---|---|
| Installateur | [Télécharger](https://down.kilho.net/kplayer?lang=fr) |
| Portable (ZIP) | [Télécharger](https://down.kilho.net/kplayer?lang=fr&nosetup) |

Pour la version portable, décompressez le ZIP où vous voulez et lancez `KPlayer.exe`.

À la fin de l'installation, l'installateur associe à KPlayer les fichiers courants comme MP4, MKV, AVI, MOV, WMV, WebM, TS, MP3, FLAC, M4A et WAV. La version portable ne touche pas aux associations ; si besoin, enregistrez-les vous-même dans Paramètres → **Associations**.

## Utilisation

### Premiers pas

1. Au lancement de KPlayer, l'écran d'accueil affiche le **logo KPlayer** au centre.
2. Faites glisser un fichier vidéo ou audio sur la fenêtre. Vous pouvez aussi cliquer sur le logo ou appuyer sur `Ctrl+O` pour choisir un fichier.
3. La lecture démarre aussitôt. Bougez la souris et les commandes apparaissent en bas ; laissez-la immobile un instant et elles disparaissent.
4. `Space` met en pause, `←` `→` avancent ou reculent de 5 secondes, `↑` `↓` règlent le volume. `Enter` ou un double-clic passe en plein écran, et `ESC` permet d'en sortir.
5. Le bouton de liste de lecture en bas à droite ouvre la fenêtre de la liste, et le bouton en forme d'engrenage à côté ouvre les Paramètres.

### La fenêtre

**Fenêtre de lecture**

| Élément | Rôle |
|---|---|
| Barre du haut | Nom du fichier en cours de lecture. À droite : punaise (toujours au premier plan) · réduire · plein écran · fermer |
| Barre de progression | Cliquez ou faites glisser pour vous déplacer. Survolez-la pour voir le temps à cet endroit dans une info-bulle ; des repères de chapitre apparaissent si le fichier en contient |
| ⏮ ▶ ⏭ | Fichier précédent / lecture-pause / fichier suivant |
| Haut-parleur | Cliquez pour couper le son. Survolez-le pour faire apparaître la barre de volume |
| Temps | Position actuelle / durée totale |
| Sous-titres | Afficher/masquer les sous-titres — n'apparaît que pour les fichiers qui ont des sous-titres |
| Engrenage | Paramètres |
| Liste | Ouvrir/fermer la fenêtre de la liste de lecture |

Faites glisser la fenêtre depuis n'importe quel point pour la déplacer, et tirez un bord pour la redimensionner. Quand vous changez le volume ou la vitesse, la nouvelle valeur s'affiche brièvement au centre de l'écran.

**Menu du clic droit**

| Menu | Rôle |
|---|---|
| Ouvrir un fichier / Ouvrir un dossier | Choisir un fichier ou un dossier, l'ajouter à la liste et le lire |
| Taille de l'écran | 50% · 100% · 150% · 200% de la taille de la vidéo, Plein écran, Plein écran (étiré) |
| Créé par Kilho | Ouvre le site web |

**Fenêtre de la liste de lecture**

| Bouton | Rôle |
|---|---|
| Répétition | À chaque clic : Pas de répétition → Répéter tout → Répéter un |
| Aléatoire | Active/désactive la lecture aléatoire |
| + | Ajouter — Fichier / Dossier |
| − | Supprimer — Fichiers sélectionnés / Fichiers non sélectionnés / Tout / Fichiers manquants |

Double-cliquez sur un élément pour le lire ; la touche `Delete` retire les éléments sélectionnés de la liste (les fichiers eux-mêmes ne sont pas supprimés). L'élément en cours de lecture s'affiche dans une autre couleur.

### Comment…

**Regarder une série dans l'ordre à partir de l'épisode 1**
Il suffit d'ouvrir un épisode. KPlayer cherche dans le même dossier les fichiers dont le nom se poursuit par un numéro (`Épisode 1`·`Épisode 2`, `S01E01`·`S01E02`, etc.) et les ajoute à la liste dans l'ordre numérique — `2` passe avant `10`. Si vous ouvrez l'épisode 3, la liste commence à l'épisode 1, mais la lecture démarre à l'épisode 3.
- Ouvrir une vidéo n'ajoute pas les fichiers audio du même dossier, et ouvrir de la musique n'ajoute pas les vidéos.
- Pour ajouter tous les fichiers du même type présents dans le dossier, réglez Paramètres → **Général → Ajouter les fichiers du dossier** sur **Tous les fichiers** ; pour n'ajouter que le fichier ouvert, réglez-le sur **Désactivé**.

**Repartir d'une nouvelle liste / ajouter à la fin de la liste**
Déposez des fichiers sur la **fenêtre principale** : la liste actuelle est vidée et remplacée par les fichiers déposés, dont la lecture démarre aussitôt. Déposez-les sur la **fenêtre de la liste de lecture** : ils s'ajoutent après la liste existante, et la lecture commence par le premier fichier ajouté. Un fichier déjà présent dans la liste n'est jamais ajouté deux fois.

**Ajouter un dossier entier**
Faites glisser un dossier sur la fenêtre, ou faites un clic droit → **Ouvrir un dossier**. KPlayer parcourt aussi les sous-dossiers et n'ajoute que les fichiers qu'il peut lire ; les images, documents et autres fichiers sont écartés automatiquement.

**Ouvrir plusieurs fichiers depuis l'Explorateur**
Sélectionnez plusieurs fichiers dans l'Explorateur et appuyez sur Entrée : ils sont tous regroupés dans une seule fenêtre KPlayer déjà ouverte, le premier fichier est lu et les autres sont ajoutés à la liste. Le comportement lorsque KPlayer est déjà ouvert se règle dans Paramètres → **Général → Si déjà en cours**.
- **Lire dans l'instance ouverte** (par défaut) — le fichier nouvellement ouvert est lu aussitôt dans la fenêtre déjà ouverte.
- **Ajouter à la liste ouverte** — la vidéo en cours continue et les fichiers sont seulement ajoutés à la liste. Pratique pour rassembler des morceaux pendant l'écoute.
- **Autoriser plusieurs** — ouvre une nouvelle fenêtre pour chaque fichier. Utile pour comparer deux vidéos côte à côte.

**Ouvrir des fichiers de liste de lecture M3U ou PLS**
Ouvrez ou déposez un fichier de liste de lecture : les morceaux qu'il contient sont ajoutés à la liste et la lecture commence par le premier. Les chemins relatifs à l'emplacement du fichier de liste sont pris en charge, tout comme les listes enregistrées dans le Bloc-notes avec des noms accentués ou non latins.

**Écouter de la musique dans le désordre**
Activez le bouton **Aléatoire** de la fenêtre de la liste de lecture. Aucun morceau ne revient tant que toute la liste n'a pas été lue ; après un tour complet, la liste est remélangée et la lecture continue. Le bouton précédent (⏮) revient en arrière dans l'ordre réellement écouté. Survolez le bouton pour voir la description du mode actuel.

**Répéter un morceau / lire la liste en boucle**
Cliquez sur le bouton **Répétition** de la fenêtre de la liste de lecture pour passer à **Répéter un** ou **Répéter tout**. Répéter un a la priorité même si la lecture aléatoire est activée. Avec Pas de répétition, la lecture s'arrête à la fin de la liste en laissant la dernière image à l'écran.

**Changer l'ordre de la liste**
Saisissez un élément et faites-le glisser vers le haut ou le bas. Sélectionnez plusieurs éléments avec `Ctrl` ou `Shift` pour les déplacer ensemble. Faites glisser jusqu'au bord de la liste et elle défile toute seule.

**Garder dans la liste des fichiers d'une clé USB ou d'un lecteur réseau**
Débrancher le lecteur ne retire pas ses fichiers de la liste ; ces éléments s'affichent alors avec leur chemin complet. Quand vient leur tour, une brève notification « Fichier introuvable » s'affiche à l'écran et KPlayer passe au fichier suivant. Rebranchez le lecteur et l'affichage redevient normal tout seul. Pour retirer les fichiers qui ont vraiment disparu, utilisez **− → Fichiers manquants** dans la fenêtre de la liste de lecture.

**Retrouver la liste au prochain lancement**
Si Paramètres → **Général → Enregistrer la liste** est activé (par défaut), la liste présente à la fermeture revient au lancement suivant. Même si vous lancez KPlayer en double-cliquant sur un fichier dans l'Explorateur, c'est ce fichier qui est lu, et non le premier morceau de l'ancienne liste. Pour commencer chaque fois avec une liste vide, réglez-le sur **Désactivé**.

**Activer les sous-titres**
Les sous-titres sont désactivés au départ. Quand vous ouvrez un fichier qui a des sous-titres, un **bouton de sous-titres** apparaît en bas ; cliquez dessus ou appuyez sur `V`. Les fichiers de sous-titres portant le même nom que la vidéo (`film.srt`, `film.fr.srt`, etc.) sont chargés automatiquement.
- Pour toujours afficher les sous-titres, réglez Paramètres → **Sous-titres → Afficher les sous-titres par défaut** sur **Activé**.
- S'il y a plusieurs pistes de sous-titres, changez-en avec `J` / `Shift+J`.
- Pour les fichiers MKV à plusieurs pistes, KPlayer choisit d'abord les sous-titres dans la langue d'affichage de Windows, sinon en anglais. Si vous préférez d'autres langues, indiquez-les dans l'ordre voulu dans **Langues de sous-titres préférées**, par exemple `ja,jpn,en,eng`.

**Rendre les sous-titres plus lisibles, ou changer leur taille et leur position**
Dans Paramètres → **Sous-titres**, modifiez la taille, la police, le gras, la couleur du texte, l'épaisseur et la couleur du contour, l'ombre, la position verticale et l'alignement. Les changements s'appliquent immédiatement à l'écran de lecture : vous pouvez donc ajuster en regardant. Pour descendre les sous-titres dans la bande noire sous la vidéo, réglez la **Position verticale**.
Pour les sous-titres avec effets et styles (ASS), comme les sous-titres de karaoké, réglez **Style du fichier de sous-titres** sur **Activé** pour qu'ils s'affichent comme prévu par le fichier de sous-titres.

**Regarder plus vite des cours ou des réunions**
`C` accélère de 0.1×, `X` ralentit, `]` / `[` changent la vitesse de 10%, et `Z` revient à 1.0×. La plage va de 0.25× à 4×, et la vitesse actuelle s'affiche brièvement au centre de l'écran à chaque changement.

**Trouver précisément la scène voulue**
`Shift+←` / `Shift+→` se déplacent d'exactement 1 seconde, et `,` / `.` reculent ou avancent d'une image. Dans les vidéos à chapitres, `Ctrl+←` / `Ctrl+→` passent d'un chapitre à l'autre, et les chapitres sont repérés sur la barre de progression.

**Enregistrer une scène en image**
Appuyez sur `S` et l'image actuelle est enregistrée sur le **Bureau** avec un numéro ajouté au nom du fichier, par exemple `film.mp4-0001.jpg`. Changez le dossier et le format (JPG/PNG) dans Paramètres → **Général → Dossier des captures d'écran / Format**. Choisissez PNG pour des images sans perte.

**Regarder dans une petite fenêtre en travaillant**
Cliquez sur le bouton **punaise** de la barre du haut : la fenêtre reste au-dessus des autres (la fenêtre de la liste de lecture aussi). Réduisez-la à la taille voulue et placez-la dans un coin de l'écran. Clic droit → **Taille de l'écran → 50%** la ramène d'un coup à la moitié de la taille de la vidéo.

**Choisir la taille de la fenêtre à l'ouverture d'une vidéo**
Faites votre choix dans Paramètres → **Général → Taille de la fenêtre à la lecture**.
- **Conserver la dernière taille** (par défaut) — la taille que vous utilisez toujours.
- **Ajuster à la vidéo** — adapte la fenêtre à la taille d'origine de chaque vidéo. Si elle dépasse l'écran, elle est réduite pour tenir à l'écran en gardant ses proportions.
- **Plein écran** — démarre directement en plein écran dès qu'une vidéo s'ouvre.

La position et la taille de la fenêtre sont mémorisées après la fermeture, et si l'écran concerné a été débranché, la fenêtre s'ouvre sur un écran visible.

**Remplir l'écran avec une vidéo d'un autre format d'image**
Clic droit → **Taille de l'écran → Plein écran (étiré)** étire la vidéo sur tout le moniteur, sans bandes noires. En quittant le plein écran, les proportions d'origine reviennent. Si vous l'utilisez souvent, réglez le double-clic sur **Plein écran étiré / restaurer** dans Paramètres → **Souris**.

**Égaliser un volume qui varie d'une vidéo à l'autre**
La **normalisation du volume** est activée par défaut : elle renforce les dialogues faibles et atténue les effets sonores forts. Pour réduire encore l'écart, réglez Paramètres → **Audio → Intensité de normalisation** sur **Forte** ; pour entendre le son d'origine, réglez **Utiliser la normalisation du volume** sur **Désactivé**. Le volume au démarrage se règle avec **Volume par défaut**.
Monter le volume alors que le son est coupé réactive automatiquement le son.

**Se déplacer avec la molette au lieu de changer le volume (modifier les actions de la souris)**
Dans Paramètres → **Souris**, choisissez une fonction pour Simple clic bouton gauche, Double clic bouton gauche, Clic bouton du milieu, Molette vers le haut et Molette vers le bas. Par exemple, réglez la molette sur **Avancer / Reculer**, le simple clic sur **Lecture/Pause** et le bouton du milieu sur **Lire le fichier suivant**.

**Utiliser les touches auxquelles vous êtes habitué**
Dans Paramètres → **Raccourcis**, choisissez une action, cliquez sur la case en dessous et appuyez sur la touche (ou la combinaison de touches) voulue. **Effacer** retire une touche, et **Raccourcis par défaut** rétablit l'état d'origine. Vous pouvez aussi attribuer des touches à **Liste de lecture**, **Paramètres** et **Toujours au premier plan**, qui n'en ont pas par défaut. Les raccourcis par défaut sont les suivants :

| Touche | Action |
|---|---|
| `Space` | Lecture/Pause |
| `Enter` | Plein écran (`ESC` pour quitter) |
| `←` / `→` | Reculer / Avancer de 5 s |
| `Shift+←` / `Shift+→` | Reculer / Avancer de 1 s (exact) |
| `Ctrl+←` / `Ctrl+→` | Chapitre précédent / suivant |
| `,` / `.` | Image précédente / suivante |
| `↑` / `↓` | Volume +5 / −5 |
| `0` / `9` | Volume +2 / −2 |
| `M` | Muet |
| `Page Up` / `Page Down` | Fichier précédent / suivant |
| `V` | Afficher/masquer les sous-titres |
| `J` / `Shift+J` | Piste de sous-titres suivante / précédente |
| `S` | Capture d'écran |
| `X` / `C` | Vitesse −0.1 / +0.1 |
| `[` / `]` | Vitesse −10% / +10% |
| `Z` | Vitesse 1.0x |
| `Ctrl+O` | Ouvrir un fichier |
| `TAB` | Panneau d'informations (fixe) |

**Voir les informations d'un fichier (codec, résolution, débit)**
Pendant la lecture, appuyez sur `TAB` pour afficher sur un seul écran le nom, le format et la taille du fichier, le codec vidéo, la résolution et la fréquence d'images, l'utilisation ou non du décodage matériel, le codec audio, les canaux et la fréquence d'échantillonnage, la piste de sous-titres et le volume. L'affichage se met à jour chaque seconde ; appuyez de nouveau sur `TAB` pour le fermer.

**Ouvrir les fichiers vidéo avec KPlayer par double-clic**
Dans Paramètres → **Associations**, cochez les extensions voulues. **Types courants** coche les formats les plus utilisés et **Tout sélectionner** coche les 38 ; chaque extension est enregistrée dès que vous la cochez. Les fichiers enregistrés par KPlayer reçoivent une icône propre à leur extension.
Sous Windows 10 et 11, c'est à vous de choisir l'application par défaut : les extensions dont l'application par défaut est un autre programme affichent donc la mention **[Non appliqué]**. Cliquez sur cette mention pour ouvrir directement le sélecteur d'applications par défaut de Windows et choisissez KPlayer. **Ouvrir les paramètres des applications par défaut de Windows** ouvre les Paramètres de Windows pour tout changer d'un coup.
- Si vous déplacez le dossier portable ailleurs, les associations suivent le nouvel emplacement au lancement suivant.
- La désinstallation de la version installée rétablit toutes les associations enregistrées par KPlayer dans leur état d'origine.

**Rétablir les réglages d'origine**
Cliquez sur **Par défaut** en bas des Paramètres pour ramener tous les réglages, raccourcis et actions de la souris à leurs valeurs par défaut. Les associations de fichiers ne sont pas modifiées.

**Adapter la sortie vidéo à votre carte graphique**
Dans Paramètres → **Vidéo**, choisissez **Décodage matériel** (Automatique (sûr) / Automatique / Désactivé (aucun)), **Pilote de sortie**, **API graphique** (Automatique / Direct3D 11 / OpenGL / Vulkan), **Synchronisation d'affichage**, **Rééchantillonneur** et **Désentrelacement**. Dans la plupart des cas, les valeurs par défaut sont les meilleures. Les réglages de cette carte s'appliquent au prochain lancement de KPlayer.

## Configuration

Les réglages se modifient dans les cartes de la fenêtre Paramètres et sont enregistrés immédiatement (la carte **Vidéo** s'applique après un redémarrage).

| Carte | Élément | Par défaut |
|---|---|---|
| Général | Mode de répétition · Lecture aléatoire | Pas de répétition · Désactivé |
| | Enregistrer la liste | Activé |
| | Ajouter les fichiers du dossier | Fichiers associés uniquement |
| | Si déjà en cours | Lire dans l'instance ouverte |
| | Dossier des captures d'écran · Format | Bureau · JPG |
| | Toujours au premier plan | Désactivé |
| | Taille de la fenêtre à la lecture | Conserver la dernière taille |
| Vidéo | Décodage matériel · Pilote de sortie · API graphique · Synchronisation d'affichage · Rééchantillonneur · Désentrelacement | Automatique (sûr) · gpu · Automatique · Rééchantillonnage écran · lanczos · Automatique |
| Audio | Volume par défaut | 100 |
| | Utiliser la normalisation du volume · Intensité de normalisation | Activé · Moyenne |
| Sous-titres | Afficher les sous-titres par défaut | Désactivé |
| | Taille des sous-titres · Langues de sous-titres préférées | 55 · Langue d'affichage de Windows + anglais |
| | Police · Gras · Couleur du texte · Épaisseur du contour · Couleur du contour · Ombre · Position verticale · Alignement | (Par défaut) · Désactivé · Blanc · 3 · Noir · 0 · 100 · Centre |
| | Style du fichier de sous-titres | Désactivé |
| Associations | Enregistrement par extension · Sélecteur d'application par défaut | L'installateur enregistre les types courants |
| Raccourcis | Touches des 30 actions | Tableau ci-dessus |
| Souris | Simple clic · Double clic · Bouton du milieu · Molette vers le haut/bas | Ne rien faire · Plein écran / restaurer · Ne rien faire · Augmenter/Baisser le volume |

Les réglages et la liste de lecture sont enregistrés dans le même dossier que le programme : déplacer le dossier portable en entier les emporte avec lui.

La langue de l'interface suit la langue d'affichage de Windows (coréen, anglais, japonais, chinois, russe, italien, français, espagnol, arabe — anglais pour les autres langues).

## Configuration requise

- Windows 10 ou Windows 11, **64 bits**
- Aucun codec ni composant supplémentaire à installer.
- Internet n'est utilisé que pour signaler les nouvelles versions.

## Mises à jour

KPlayer **ne** se met **pas** à jour tout seul. Au démarrage, il vérifie s'il existe une nouvelle version et affiche un avis ; si vous choisissez de la récupérer, la page de téléchargement s'ouvre et le programme se ferme. Les nouvelles versions sont publiées manuellement après vérification interne et annoncées sur la [page KPlayer](https://kilho.net/kplayer). Consultez l'[avis sur la politique de mise à jour](https://en.kilho.net/archives/notice/2940).

## Compiler depuis les sources

Le code source est public sur [github.com/newkilho/KPlayer](https://github.com/newkilho/KPlayer). Il se compile avec [Lazarus](https://www.lazarus-ide.org/) 4.x (FPC 3.2.2, Win64) et nécessite :

- [LibMPVDelphi](https://github.com/nbuyer/libmpvdelphi) — les unités de liaison avec libmpv
- `laz.virtualtreeview_package` — le paquet Virtual Treeview fourni avec Lazarus
- `libmpv-2.dll` à côté de `KPlayer.exe` à l'exécution

Copiez `Const-sample.inc` en `Const.inc`, puis compilez avec `lazbuild KPlayer.lpi`. Toutefois, une bibliothèque partagée (klib) chargée notamment de la vérification des mises à jour et de la traduction se trouve hors du dépôt : l'exécutable ne peut donc pas être compilé à partir du seul dépôt.

## Contribuer

Les rapports de bugs et les suggestions sont les bienvenus via les issues GitHub ou le [forum](https://kilho.top/forum/qna).

## Licence

Le programme KPlayer est un **freeware**. Utilisez-le gratuitement et sans restriction où vous voulez — au travail, à la maison, dans les administrations et à l'école — et redistribuez-le librement partout.

Le code source est publié sous **GNU GPL v2 ou ultérieure**. Les composants open source utilisés, dont le moteur de lecture libmpv (GPL-2.0-or-later), sont listés dans `THIRD-PARTY-NOTICES.txt` dans le dossier d'installation.

## Liens

- Site web : <https://kilho.net/kplayer>
- Code source : <https://github.com/newkilho/KPlayer>
- Forum : <https://kilho.top/forum/qna>
- X (Twitter) : <https://www.twitter.com/kilhonet>

© KILHO.NET
