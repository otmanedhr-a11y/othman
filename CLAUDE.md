# Règles de travail

## Quand l'utilisateur envoie un plan (photo ou fichier de dessin technique)

Sans attendre qu'il le demande, livrer automatiquement :

1. **La pièce en 3D** : une page HTML interactive (three.js) publiée en Artifact,
   avec vues Iso / Face / Profil et animation du plat vers la pièce finie,
   pli par pli.
2. **Comment elle est fabriquée sur machine** (gamme de fabrication) :
   - débit (laser, cisaille, poinçonneuse…) avec dimensions du flan, trous, crans ;
   - ordre des plis à la presse plieuse : sens (UP/DOWN), longueur de pli,
     cote développé, outillage (V matrice, poinçon droit / col de cygne,
     outillage segmenté), retournements de pièce, risques de collision ;
   - autres opérations (ébavurage, soudure, perçage, taraudage, finition) ;
   - points de contrôle.
3. **Hypothèses et cotes à confirmer** : épaisseur, matière, K-factor / déduction
   de pli, cotes lues à l'échelle sur la photo. Les signaler clairement, ne
   jamais les présenter comme certaines.

Rangement : un fichier par pièce dans `plans/<nom-piece>.html`.

Langue : répondre en darija (comme l'utilisateur) ; termes techniques et pages
de fabrication en français, comme sur les plans.
