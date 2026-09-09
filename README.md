# Wargame Palette 🎨

Petite app mobile (une seule page HTML, sans build) pour aider à peindre des figurines
de wargame. Basée sur la théorie des couleurs (roue chromatique) et associée aux
gammes de peintures Citadel, Vallejo et Army Painter.

## Trois usages

1. **Couleurs** — tu choisis une ou plusieurs couleurs (ex. l'armure), l'app
   propose les palettes harmonieuses associées : Complémentaire, Analogue,
   Monochromatique, Split, Triadique, Carré. Chaque couleur de base se choisit
   au **nuancier** (color picker) **ou en cherchant une peinture par son nom**
   parmi les 3 marques.
2. **Hasard** — l'app tire une couleur au hasard mais construit une palette qui
   respecte la règle d'harmonie choisie.
3. **Créer** — tu assembles **librement** ta propre palette (nuancier ou peinture
   par nom), sans aucune règle d'harmonie : c'est toi qui décides.
4. **Inventaire** — tu listes les peintures que tu possèdes (sauvegardées dans le
   navigateur) et l'app génère des color schemes **uniquement** avec tes
   couleurs : chaque couleur cible est remplacée par ta peinture la plus proche.
   Tu peux aussi **enregistrer une palette** (générée ou créée à la main) dans
   l'inventaire via le bouton **💾 Enregistrer**, puis la retrouver, la
   supprimer, ou ajouter ses peintures à ta liste de peintures possédées.

Chaque couleur proposée est reliée à la **peinture la plus proche** de la marque
choisie. Marques supportées : **Citadel**, **Vallejo**, **Army Painter**, ou
**Toutes** (dans ce cas les trois équivalents sont affichés à la suite). Au sein
d'une même palette, une peinture n'est jamais proposée deux fois.

## Tester

Ouvre simplement `index.html` dans un navigateur (mobile ou desktop), ou via ce lien
qui rend le fichier directement depuis le repo :

👉 https://htmlpreview.github.io/?https://raw.githubusercontent.com/Ottoreg/wh_color_scheme/main/index.html

Une fois GitHub Pages activé : https://ottoreg.github.io/wh_color_scheme/

> Les valeurs hex des peintures sont approximatives. Les noms de gammes et de
> peintures (Citadel, Vallejo, Army Painter) appartiennent à leurs propriétaires
> respectifs. App non officielle, sans affiliation.
