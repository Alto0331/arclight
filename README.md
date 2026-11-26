# ARCLIGHT

FPS d'arène nerveux, de nuit, dans une ville cyberpunk : katana, grappin, glissade, dash, revolver à bobine, slam qui laisse un cratère.
Modes : **Chacun pour soi**, **2 contre 2**, **Entraînement** et **Multijoueur en ligne**.

> Bêta de bêta : le jeu change vite. Ce dépôt ne contient **que les téléchargements** (onglet *Releases*), pas le code source.

## Télécharger

1. Va dans l'onglet **[Releases](../../releases/latest)** et télécharge **`ARCLIGHT-Setup.exe`**.
2. Lance-le. Windows peut afficher « Windows a protégé votre ordinateur » (le jeu n'est pas signé) :
   clique sur **Informations complémentaires**, puis **Exécuter quand même**.
3. L'installation se fait dans ton dossier utilisateur : aucun droit administrateur n'est demandé.

## Mises à jour

Quand une nouvelle version sort, le menu du jeu affiche **« MISE À JOUR … DISPONIBLE »** en bas à droite.
Un clic sur **METTRE À JOUR** télécharge la nouvelle version, vérifie son empreinte, l'installe et relance le jeu.
Rien d'autre à faire. Il faut avoir installé le jeu avec `ARCLIGHT-Setup.exe` (et non en lançant un simple zip).

## Jouer en ligne

Le multijoueur passe par [Tailscale](https://tailscale.com/download) : pas de port à ouvrir sur ta box.

1. Installe Tailscale et connecte-toi au même réseau (tailnet) que l'hôte.
2. Au premier lancement, autorise ARCLIGHT dans le pare-feu Windows (réseaux **privés et publics** : Tailscale est souvent classé « public »).
3. Menu **MULTIJOUEUR** : les parties ouvertes apparaissent toutes seules, clique **REJOINDRE**.
   Pour héberger : **CRÉER UN SALON**. Si rien n'apparaît : « Connexion manuelle » et l'adresse `100.x.y.z` de l'hôte.

Tout le monde doit avoir **la même version** du jeu.

## Commandes

Clic gauche : katana · Clic droit : grappin · **A** (AZERTY) / **Q** (QWERTY) : revolver · F : parade · Shift : dash · Ctrl : glissade · Espace : saut · Tab : scores · **Virgule (maintenue) : carte entière** · Échap : pause.

Tout se règle dans **Options > Commandes** : chaque touche se change d'un clic, et l'interrupteur **Disposition du clavier** remet le déplacement sur **ZQSD** (AZERTY) ou **WASD** (QWERTY).
La mini-carte (en haut à gauche) se règle dans **Options > Affichage**.

## Sons de mèmes (facultatif)

Le jeu sait jouer des sons de mèmes selon ce que tu fais, pour le côté troll : un coup **raté**, ta **mort**, un **kill**.
Ces sons ne sont **pas fournis** avec le jeu (ce sont des extraits protégés par des droits d'auteur) : chacun télécharge ceux qu'il veut.

| Quand | Son | Où le télécharger |
|---|---|---|
| Coup raté | *bruh* | [myinstants.com/instant/bruh](https://www.myinstants.com/instant/bruh/) |
| Coup raté | *mi bombo* | [orangefreesounds.com/mi-bombo-sound-effect](https://orangefreesounds.com/mi-bombo-sound-effect/) |
| Tu meurs | *GET OUT* | [myinstants.com/fr/instant/get-out-meme-91882](https://www.myinstants.com/fr/instant/get-out-meme-91882/) |
| Tu meurs | *Enrike !* (version 1) | [myinstants.com/fr/instant/enrice-47938](https://www.myinstants.com/fr/instant/enrice-47938/) |
| Tu meurs | *Enrike !* (version 2) | [myinstants.com/fr/instant/eres-el-enrikque-10204](https://www.myinstants.com/fr/instant/eres-el-enrikque-10204/) |
| Tu tues quelqu'un | *Gotcha bitch* (Dave Chappelle) | [soundinstants.com/sound/gotcha-bit-by-dave-chapelle](https://soundinstants.com/sound/gotcha-bit-by-dave-chapelle) |

**Les ajouter au jeu :**

1. Sur chaque page, télécharge le son (bouton de téléchargement, fichier `.mp3`).
2. Dans le jeu : **Options > Audio > Mèmes > OUVRIR LE DOSSIER**. Un dossier s'ouvre.
3. Glisse-y les fichiers téléchargés. **Pas besoin de les renommer** tant que le nom contient `bruh`, `bombo`, `get out`, `enrike` / `enrique` / `enrice` ou `gotcha`
   (sinon, nomme-les `rate_….mp3`, `mort_….mp3` ou `kill_….mp3`). Formats : `.mp3`, `.ogg`, `.wav`.
4. **Relance le jeu.** Le titre « Tes sons de mèmes (N chargés) » indique combien ont été trouvés.

Plusieurs sons pour un même moment : le jeu en tire un au hasard (jamais le même deux fois de suite). Les sons sont de volume inégal :
règle **Volume des mèmes** (ou coupe tout avec la case **Sons de mèmes**) dans **Options > Audio**.

## Un problème ?

Ouvre une *Issue* (onglet **Issues**) en disant ce que tu vois (écran, message) et à quel moment.
