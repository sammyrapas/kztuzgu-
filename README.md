# SABLE : ta calculatrice est faite de sable

**SABLE remplace l'écran d'accueil de la calculatrice NumWorks (n0110, n0115 ou n0120) par un
désert de nuit où chaque pixel est un grain de matière.** Sable, eau, lave,
feu, fumée, acide, glace, bois, plantes, poudre, or, virus : 160 × 120 grains
qui tombent, coulent, brûlent et explosent en direct. Les applis sont des
**statues de sable**. Pour en ouvrir une, **elle part en poussière**. Et
quand tu reviens… **l'écran de l'appli s'effrite grain par grain et tombe
dans le désert.**

![Le désert de SABLE](docs/apercu.png)

<p align="center"><img src="docs/retour.gif" alt="L'écran du Grapheur s'effrite et tombe dans le désert" width="480"></p>

## Ce que fait SABLE

- **Un vrai simulateur de sable.** Rien n'est une image : 19 200 cellules
  sont calculées à chaque image (un automate « falling sand »). Le sable
  s'empile, l'eau s'étale, la lave brûle le bois et fait de la pierre en
  touchant l'eau, le feu monte et fume, l'acide ronge tout, la poudre
  explose en chaîne, la glace gèle l'eau voisine, les plantes boivent, le
  virus contamine et le feu le soigne.
- **Les applis sont des statues de sable**, sculptées grain par grain à
  partir de leur vraie icône. Le sable s'accumule sur leur tête, la lave les
  lèche, l'eau les contourne. Sélectionne-en une : un projecteur tombe du
  ciel et du sable doré tourne autour.
- **OK : la statue part en poussière.** La moitié des grains s'envole avec
  le vent, l'autre moitié tombe dans le désert, puis le sable recouvre
  l'écran et l'appli s'ouvre.
- **Quand tu reviens, l'appli s'effrite.** SABLE lit le dernier écran de
  l'appli (ou du **jeu**) que tu viens de quitter, et le transforme en
  grains : l'image se désagrège depuis le bas, les zones claires s'évaporent,
  tout ce qui est coloré tombe en sable de sa couleur. La courbe rouge du
  Grapheur fait une couche de sable rouge sur les dunes. Puis les statues se
  reforment grain par grain.
- **Tes résultats tombent du ciel.** Fais des calculs dans Calculs, reviens :
  les résultats tombent en énormes chiffres faits d'une matière qui dépend du
  nombre.

  | Tu calcules… | Il tombe… |
  | --- | --- |
  | `6×7` → 42 | **42 en or massif** (« la réponse à tout ») |
  | `6×111` → 666 | **666 en lave** : il met le feu au désert |
  | `1337` | **un virus** : le désert est piraté |
  | un résultat égal à 0 | **un trou noir** qui aspire tout pendant quelques secondes |
  | `404` | rien : il **s'évapore** en plein vol (« résultat introuvable ») |
  | `1/0`, `undef` | **de la poudre qui explose** |
  | un nombre premier | **de la pierre** : incassable, il reste debout |
  | un carré parfait | **du bois massif** (attention au feu) |
  | un nombre à virgule | **de l'eau** : ça coule |
  | un nombre négatif | **de la glace** |
  | un nombre énorme | **une météorite** |
  | `2026` | un **feu d'artifice** |
  | `1+1` | **un seul grain**. Pour 1+1, ça suffit. |

- **Les touches de fonctions sont des catastrophes naturelles** (voir plus
  bas) : pluie, tempête, tsunami, foudre, volcan, virus, explosion, météorite,
  pluie d'or, séisme, monde imaginaire, et **Ans** : le claquement de doigts
  qui fait disparaître la moitié de la matière de l'univers.
- **Tourne la calculatrice** : `(` et `)` changent le sens de la gravité. Le
  désert entier glisse sur le côté, ou tombe vers le ciel.
- **Le mode Dieu** (`Var`) : un curseur, 12 matières, une taille de pinceau.
  Garde OK appuyé pour verser.
- **Le bouton panique** : `Effacer`. Tout s'effondre d'un coup, le sable
  recouvre l'écran et **Calculs** s'ouvre. Le prof arrive ? Tu calcules.
  Quand tu reviens : « Il est parti ? Le sable n'a rien vu. »
- **Le désert vit tout seul** : quand il déborde, le sol s'ouvre et tout
  s'écoule (« on tire la chasse ») ; quand il est vide, le vent ramène du
  sable. Il y a une oasis, deux cactus, et un trésor caché sous le sable.
- **Le désert t'attend** : il reste en mémoire pendant que tu es dans une
  appli ou un jeu, exactement comme tu l'as laissé.
- **La LED vit avec le désert** : orange qui tremble quand ça brûle, verte
  quand le virus se propage, violette pour le trou noir, éclair blanc pour
  la foudre et les explosions.
- **La batterie est un sablier**, la luminosité est « la lune », et la barre
  de titre des applis devient **couleur sable**.
- **Installateurs en un clic pour Mac et pour Windows** : une page web locale
  (un désert de nuit, elle aussi) qui détecte la calculatrice, gère tes jeux
  et installe tout avec un bouton. Sur Windows, un simple `.exe` : ni Python
  ni pilote à installer.

<p align="center"><img src="docs/boot.gif" alt="Le démarrage : le mot SABLE se remplit de sable puis s'effondre" width="400"> <img src="docs/gravite.gif" alt="La calculatrice tourne : la gravité change" width="400"></p>

## Les catastrophes

| Touche | Catastrophe |
| --- | --- |
| **sin** | la pluie (le désert n'en revient pas) |
| **cos** | tempête de sable |
| **tan** | tsunami : un mur d'eau traverse l'écran |
| **x²** | la foudre tombe (au carré) et met le feu |
| **ln** | le volcan se réveille : fontaine de lave et bombes volcaniques |
| **log** | un virus se propage. Le feu le soigne. |
| **eˣ** | explosion exponentielle au milieu de l'écran |
| **π** | il pleut des décimales de π, en or |
| **√** | une racine géante pousse jusqu'au ciel, avec une fleur en or |
| **^** | une météorite traverse le ciel et s'écrase |
| **×10ˣ** | jackpot : il pleut de l'or |
| **i** | le monde imaginaire : tout devient psychédélique |
| **x,n,t** | séisme : la pierre se fissure en sable |
| **Ans** | le claquement de doigts : la moitié de la matière disparaît, équilibre parfait |
| **(** et **)** | tourner la calculatrice : la gravité change de sens |
| **0** | vider le désert : le sol s'ouvre |

## Le Labo

Ouvre-le avec la touche **Boîte à outils**.

| Outil | Ce que ça fait |
| --- | --- |
| **Sablier du cours** | choisis le nombre de minutes avant la sonnerie : un vrai sablier se vide en temps réel, avec des commentaires (« Plus de la moitié ! Le plus dur est fait. (C'est faux.) »). Il continue pendant que tu travailles, le temps restant reste affiché dans le désert, la LED pulse en rouge la dernière minute, et à la fin : **DRIIING**, confettis et LED arc-en-ciel |
| **Calculatrice menteuse** | **la farce** : prête ta calculatrice à ton voisin. Elle ressemble à l'appli Calculs. Les deux premiers résultats sont justes. Ensuite, elle se trompe d'un, répond en toutes lettres (« quatre-vingt-dix-neuf »), « Demande à ton voisin. », « ≈ 70 (à la louche) », en chiffres romains (MXXIV), « Erreur : flemme », en base 7, « Je refuse. Tu m'as jamais dit merci. »… et Retour ne marche pas. **Retour trois fois vite** : « C'ÉTAIT UNE BLAGUE » |
| **Faux appel** | choisis qui t'appelle, pose la calculatrice : 5 secondes plus tard, **elle sonne** (l'écran vibre, la LED clignote en vert). Décroche : **Mamie** (« Ton cousin a eu 19, lui. »), **le Directeur**, **Pythagore** (il a oublié sa formule), **ta calculatrice** (« Je t'appelle de l'intérieur. Il y a du sable partout ici. »), **le Wi-Fi du lycée** (qui coupe), **toi dans 10 ans**, un numéro inconnu, ou **le sable** lui-même |
| **Désintégrateur** | écris un mot (ou prends une idée : LUNDI, LES MATHS, LE BAC, LES DEVOIRS, LE REVEIL, LA CANTINE, PRONOTE, MON BULLETIN…). Il apparaît en marbre sur un piédestal. OK : **il part en poussière**, lettre par lettre, emporté par le vent. « "LUNDI" n'existe plus. » |
| **Bataille de sable** | **2 joueurs sur une calculatrice** : deux tours en bois, un roi en or sur chacune, des dunes au milieu, du vent. Vise, règle la force, choisis la munition (boulet, bombe à eau, boule de lave, TNT, acide) et tire. Tout se passe dans le simulateur : la lave brûle les tours, l'eau éteint le feu, l'acide ronge le roi, la TNT creuse des cratères. Le premier roi en poussière a perdu |
| **Les catastrophes** | la liste des touches |
| **Réglages** | LED oui/non, remettre le désert à neuf, et les statistiques (applis désintégrées, paniques, catastrophes, explosions, mensonges, appels décrochés, grains désintégrés) |

<p align="center"><img src="docs/desint.gif" alt="LUNDI part en poussière" width="400"></p>

## Les commandes

| Touche | Action |
| --- | --- |
| ◀ ▶ ▲ ▼ | choisir une statue ; au bord, changer de page (les statues s'envolent, les nouvelles se forment) |
| 1 à 9 | aller à la page 1, 2, 3… |
| OK | ouvrir l'appli (sa statue part en poussière) |
| **Effacer** | **BOUTON PANIQUE** : tout s'effondre, Calculs s'ouvre |
| Var | le mode Dieu |
| Boîte à outils | le Labo |
| sin cos tan x² ln log eˣ π √ ^ ×10ˣ i x,n,t Ans 0 | les catastrophes |
| ( ) | tourner la calculatrice (la gravité) |
| Retour | revenir à la première page |
| + − | la luminosité (la lune) |

**En mode Dieu** : flèches pour viser, **OK maintenu** pour verser,
`1` sable · `2` eau · `3` lave · `4` feu · `5` pierre · `6` bois ·
`7` plante · `8` glace · `9` acide · `0` poudre · `.` virus · `×10ˣ` or,
**Effacer maintenu** pour gommer, `+` `−` la taille, `Var` pour sortir.

## Captures

| | |
| --- | --- |
| ![Accueil](docs/accueil.png) | ![Retour](docs/retour_debut.png) |
| Les statues dans le désert | Tu reviens du Grapheur… |
| ![Effritement](docs/retour_milieu.png) | ![Résultats](docs/resultats.png) |
| …son écran s'effrite en sable | Tes résultats tombent du ciel (42 en or, 666 en lave) |
| ![Pluie](docs/pluie.png) | ![Volcan](docs/volcan.png) |
| sin : la pluie | ln : le volcan |
| ![Foudre](docs/foudre.png) | ![Météorite](docs/meteorite.png) |
| x² : la foudre | ^ : la météorite |
| ![Virus](docs/virus.png) | ![Imaginaire](docs/imaginaire.png) |
| log : le virus | i : le monde imaginaire |
| ![Gravité](docs/gravite.png) | ![Claquement](docs/claquement.png) |
| ( : la calculatrice tourne | Ans : le claquement de doigts |
| ![Explosion](docs/explosion.png) | ![Racine](docs/racine.png) |
| eˣ : l'explosion | √ : la racine géante |
| ![Dieu](docs/dieu.png) | ![Chasse](docs/chasse.png) |
| Le mode Dieu (lave et eau) | 0 : on vide le désert |
| ![Labo](docs/labo.png) | ![Aide](docs/aide.png) |
| Le Labo | Les catastrophes |
| ![Sablier](docs/sablier_reglage.png) | ![Sablier](docs/sablier.png) |
| Le sablier du cours | 21 minutes avant la sonnerie |
| ![Sablier](docs/sablier_fin.png) | ![DRIIING](docs/sablier_dring.png) |
| La dernière minute | DRIIING |
| ![Menteuse](docs/menteuse.png) | ![Menteuse](docs/menteuse_pire.png) |
| La calculatrice menteuse : ça commence bien… | …puis ça se gâte |
| ![Blague](docs/menteuse_blague.png) | ![Appel](docs/appel_choix.png) |
| Retour × 3 : la blague | Qui doit t'appeler ? |
| ![Appel](docs/appel_sonne.png) | ![Mamie](docs/appel_mamie.png) |
| Ça sonne | Mamie |
| ![Calculatrice](docs/appel_calculatrice.png) | ![Désintégrateur](docs/desintegrateur.png) |
| Ta calculatrice t'appelle de l'intérieur | Le désintégrateur |
| ![Désintégration](docs/desintegration.png) | ![Désintégré](docs/desintegre.png) |
| LUNDI part en poussière | LUNDI n'existe plus |
| ![Bataille](docs/bataille.png) | ![Bataille](docs/bataille_lave.png) |
| La bataille de sable | Une boule de lave dans la tour de J2 |
| ![Réglages](docs/reglages.png) | ![Sélection](docs/selection.png) |
| Les réglages | La statue choisie |

> Les captures viennent du simulateur, qui ne sait pas charger de jeux ni
> quitter une vraie appli : l'écran du Grapheur qui s'effrite y est
> reconstitué. Sur la calculatrice, c'est le vrai dernier écran de l'appli
> (ou du jeu) qui tombe en sable, et chaque jeu `.nwa` devient une statue
> avec son icône.

## Installation

### 1. Obtenir SABLE

Depuis juillet 2021, le code d'Epsilon (le logiciel de la NumWorks) n'est plus
sous licence libre. SABLE ne publie donc **aucun code ni aucun firmware de
NumWorks** : seulement un **patch** (`patches/sable-epsilon.patch`) et son
propre code. Le firmware se compile à partir des sources officielles de
NumWorks, dans ton compte GitHub ou sur ton Mac.

**Sans rien compiler (Mac ou Windows)**

1. En haut de cette page : **Use this template** > **Create a new repository**,
   coche **Private** (obligatoire : la compilation refuse de tourner dans un
   dépôt public, pour que le firmware ne soit pas téléchargeable par tous).
2. Facultatif : ajoute tes jeux `.nwa` dans le dossier `games/` de ta copie
   privée (*Add file* > *Upload files*). Ils seront préparés et inclus dans
   l'installateur, et deviendront des statues de sable.
3. Dans ta copie : onglet **Actions** > **Build SABLE** > **Run workflow**.
4. Environ 30 minutes plus tard (un firmware par modèle), en bas de la page de la compilation,
   télécharge **SABLE-Mac** ou **SABLE-Windows** et décompresse-le
   (deux fois pour la version Mac : GitHub met le zip dans un zip).

**En compilant sur ton Mac**

```bash
brew install make dfu-util libusb
brew install --cask gcc-arm-embedded
git clone https://github.com/derim00/sable.git && cd sable
./scripts/build-firmware.sh
```

Le script télécharge Epsilon au commit indiqué dans `EPSILON_COMMIT`
(Epsilon 26.1, la dernière version publiée par NumWorks), applique le patch,
compile, prépare les jeux de `games/` et remplit le dossier `installer/`.

### 2. Installer sur la calculatrice

**Sur Mac**

1. Une seule fois : `brew install libusb dfu-util` (et
   `brew install --cask gcc-arm-embedded` pour ajouter d'autres jeux).
2. Double-clique sur **`Installer SABLE.command`** (la première fois :
   clic droit > **Ouvrir**). La page de l'installateur s'ouvre
   (http://127.0.0.1:8772).

**Sur Windows** (rien à installer : ni Python, ni pilote)

1. Décompresse **SABLE-Windows** (clic droit > *Extraire tout*) : ne
   lance pas l'installateur depuis l'intérieur du zip.
2. Dans le dossier `SABLE`, double-clique sur **`Installer SABLE.exe`**
   (si SmartScreen s'affiche : *Informations complémentaires* > *Exécuter
   quand même*). Une fenêtre noire s'ouvre avec la page de l'installateur dans
   ton navigateur : laisse-la ouverte, et ferme-la à la fin pour quitter.

**Ensuite, sur les deux**

3. Branche la calculatrice en USB et appuie sur **Reset** au dos : elle
   redémarre sur le système officiel.
4. Quand le voyant passe au vert, glisse tes jeux `.nwa` dans la page si tu
   veux, puis clique sur **Installer SABLE**.

L'installateur vérifie que le **slot B** est libre avant d'écrire : le système
officiel (slot A) n'est jamais modifié. Il prépare les jeux pour leur place
dans le slot B (comme le fait le site de NumWorks), les copie, les relit pour
les vérifier, puis installe SABLE et le démarre.

## À savoir

- **Calculatrice** : NumWorks **n0110**, **n0115** ou **n0120**, avec le logiciel officiel
  **26.4.0** dans le slot A. SABLE est compilé à partir d'Epsilon 26.1
  (la dernière version publiée) avec le numéro de version 26.4.0.
- **Trois modèles** : la compilation produit un firmware par modèle
  (n0110, n0115, n0120) et l'installateur choisit tout seul celui de la
  calculatrice branchée. Mets d'abord ta calculatrice à jour sur
  numworks.com : le système doit avoir la même version que le logiciel
  officiel du slot A.
- **Jeux trop gros** : un jeu qui ne tient pas dans le slot B (NumPlay,
  par exemple) est ignoré avec un message, au lieu de faire échouer la
  compilation. Retire-le du dossier `games/`.
- **Mémoire** : la calculatrice a très peu de RAM. Le désert (19 200 grains)
  reste en mémoire en permanence, même pendant les jeux ; les couleurs des
  statues et de la poussière, elles, n'existent que pendant que l'accueil est
  ouvert (la poussière d'une ancienne appli prend donc la couleur de la
  suivante). Tout repart de zéro après un Reset.
- **Les résultats** : seuls les résultats calculés depuis le dernier
  démarrage tombent, et seulement les 3 derniers à chaque retour.
- **LED et luminosité** : SABLE ne touche à la LED que sur son écran ; elle
  redevient normale dès que tu ouvres une appli. Tu peux la couper dans
  Labo > Réglages. En mode examen, il n'y touche jamais.
- **Batterie** : le désert est simulé en continu, même quand tu ne touches à rien.
- **Après un Reset**, la calculatrice revient sur le système officiel :
  SABLE reste dans le slot B, il suffit de relancer l'installation.
- **Un seul système dans le slot B** : SABLE remplace
  [BROUILLON](https://github.com/derim00/brouillon),
  [NUM TV](https://github.com/derim00/numtv),
  [GLOUTON](https://github.com/derim00/glouton),
  [NUMVERSE](https://github.com/derim00/numverse),
  [PSP-OS](https://github.com/derim00/psp-os),
  [Switch-OS](https://github.com/derim00/switch-os) ou
  [Windows-OS](https://github.com/derim00/windows-os) s'il était installé,
  et inversement. Les installateurs peuvent tourner en même temps (ports 8765
  à 8772).
- **Touches Home et On/Off** : sur un logiciel non officiel, le système de la
  calculatrice gère lui-même ces deux touches. SABLE efface au démarrage
  le point de retour laissé par le système officiel pour que Home ramène au
  désert ; si la calculatrice revient quand même sur le slot A, utilise
  **Retour** (↩) pour revenir à SABLE depuis une appli.
- **Mode examen** : SABLE garde les règles du mode examen d'Epsilon
  (applis interdites, jeux bloqués : les statues des jeux sont ensablées).
- **La calculatrice menteuse et le faux appel** sont des blagues entre amis :
  la menteuse avoue tout avec Retour trois fois, et le faux appel n'appelle
  personne (la calculatrice n'a ni réseau ni haut-parleur).
- **Jeux** : seulement des applis `.nwa` dont tu as le droit de te servir, et
  uniquement dans ta copie privée : jamais dans ce dépôt public.

## Comment c'est fait

| Fichier | Rôle |
| --- | --- |
| `patches/sable-epsilon.patch` | SABLE (`apps/home/sable`), le branchement des résultats de Calculs, l'animation continue (`escher`), la barre couleur sable des applis, le correctif Home / On-Off |
| `apps/home/sable/world.cpp` (dans le patch) | le simulateur : 16 matières, la gravité dans les 4 sens, le sol qui s'ouvre, les réactions (lave + eau = pierre, feu, acide, virus, poudre…), les explosions, le trou noir, le vent, l'image figée de l'appli qui s'effrite, le rendu du désert |
| `apps/home/sable/shell.cpp` (dans le patch) | l'accueil : les statues sculptées depuis les icônes, la désintégration, le retour (lecture de l'écran de l'appli), les résultats qui tombent, les catastrophes, le mode Dieu, les particules, le démarrage, le bouton panique, la LED |
| `apps/home/sable/labo.cpp` (dans le patch) | le Labo : sablier du cours, calculatrice menteuse (avec un vrai petit moteur de calcul, les nombres en lettres, en chiffres romains, en base 7), faux appel, désintégrateur, bataille de sable, catastrophes, réglages |
| `apps/home/sable/gfx.cpp` (dans le patch) | le dessin par bandes de 6 lignes (hérité de BROUILLON) : formes, texte, icônes |
| `apps/home/sable/food.cpp` (dans le patch) | les derniers résultats de l'appli Calculs, qui tombent du ciel |
| `scripts/build-firmware.sh` | télécharge Epsilon, applique le patch, compile, prépare l'installateur |
| `scripts/photos.py` | transforme la séance photo du simulateur en images de ce README |
| `installer/server.py` | serveur local (127.0.0.1 uniquement) de l'installateur, Mac et Windows |
| `installer/dfu_launch.py` | lance l'outil DFU de NumWorks avec libusb (Homebrew ou `libusb-package`) |
| `installer/link_games.py` | prépare les jeux `.nwa` pour leur adresse dans le slot B |
| `scripts/build-windows-installer.py` | fabrique l'installateur Windows (`.exe`, PyInstaller) |
| `.github/workflows/build.yml` | la compilation dans ta copie privée |

## Licence

Code de SABLE (le patch, les scripts, l'installateur) : CC BY-NC-SA 4.0,
voir [LICENSE](LICENSE). Epsilon appartient à NumWorks et n'est pas inclus.
SABLE est un projet de fan, non affilié à NumWorks.
