# Règles de travail

## Quand l'utilisateur envoie un plan (photo ou fichier de dessin technique)

Sans attendre qu'il le demande, livrer automatiquement :

1. **La pièce en 3D** : une page HTML interactive (three.js) publiée en Artifact,
   avec vues Iso / Face / Profil et animation du plat vers la pièce finie,
   pli par pli.
2. **Schémas « avant pliage » et « après pliage » avec toutes les cotes**
   (section « Avant et après pliage » dans la page) :
   - avant : le développé avec les lignes de pli en pointillé rouge, le numéro
     d'ordre de chaque pli, le sens (UP/DOWN), d'un côté la distance cumulée
     depuis le bord (0, 9, 97…), de l'autre la largeur de chaque bande
     (9, 88, 178…), et la cote hors-tout ;
   - après : le profil / la coupe (et la vue de dessus si besoin) avec toutes
     les cotes finies et le numéro de chaque pli à son angle ;
   - correspondance bande développée → cote finie (ex. 32,53 → 35).
   Donner aussi ces cotes en texte dans la réponse.
3. **Comment elle est fabriquée sur machine** (gamme de fabrication) :
   - débit (laser, cisaille, poinçonneuse…) avec dimensions du flan, trous, crans ;
   - ordre des plis à la presse plieuse : sens (UP/DOWN), longueur de pli,
     cote développé, outillage (V matrice, poinçon droit / col de cygne,
     outillage segmenté), retournements de pièce, risques de collision ;
   - pour CHAQUE pli, dans l'ordre (1er, 2e, 3e…) : position de la pièce,
     valeur de butée, et les cotes à mesurer sur la pièce juste après ce pli
     (longueur de l'aile pliée, angle, largeur restante à plat) ;
   - autres opérations (ébavurage, soudure, perçage, taraudage, finition) ;
   - points de contrôle.
4. **Hypothèses et cotes à confirmer** : épaisseur, matière, K-factor / déduction
   de pli, cotes lues à l'échelle sur la photo. Les signaler clairement, ne
   jamais les présenter comme certaines.

Rangement : un fichier par pièce dans `plans/<nom-piece>.html`.

Sens de pli : toujours en anglais, **UP** / **DOWN**, dans les pages et dans
les réponses, même si le plan écrit BAS / HAUT (BAS → DOWN, HAUT → UP).
Signaler une fois que le plan utilise BAS / HAUT.

Langue : répondre en darija (comme l'utilisateur) ; termes techniques et pages
de fabrication en français, comme sur les plans.
