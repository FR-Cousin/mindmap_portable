# mindmap_portable

Une carte mentale locale, en français, utilisable hors ligne dans un navigateur.

## Utilisation

Ouvrir `MindMap_Portable.html` dans un navigateur. Aucune installation ni connexion
à Internet n’est nécessaire.

- Créer des étiquettes, les relier et les déplacer librement. Les liens contournent
  les étiquettes pour rendre leurs connexions plus lisibles.
- Ajouter une date et une heure à une étiquette, ou cocher **Période** pour préciser
  une fin. Les périodes apparaissent sous la frise chronologique.
  Toutes les périodes restent accessibles : lorsqu’elles sont nombreuses,
  faire défiler leur zone verticalement avec la molette. **Ctrl + molette** ou
  les boutons **+ / −** permettent de zoomer ; les événements restent visibles
  en haut de la frise pendant le défilement.
  Les repères sont espacés régulièrement dans l’ordre des dates pour éviter les
  superpositions, y compris à date identique. Les distances sur la frise ne sont
  pas proportionnelles aux durées ; les périodes restent alignées sur leurs dates.
- Double-cliquer dans une étiquette et sélectionner du texte pour afficher la
  barre de mise en forme. Le bouton **Aa** propose des tailles et les commandes
  **+ / −** ; dans la colonne de propriétés, ces réglages concernent tout le texte.
- Redimensionner une étiquette avec sa poignée ou utiliser **Ajuster au contenu**.
- Activer **Exploration** pour parcourir les connexions d’une étiquette. Cliquer
  sur le fond pour revenir à la carte entière.
- Utiliser **Réorganiser**, à droite d’Exploration, pour placer les étiquettes
  les plus connectées au centre de chaque groupe et les extrémités autour.
  **Ctrl+Z** annule la réorganisation ; **Ctrl+Y** la rétablit.

## Sauvegarde et partage

La carte est sauvegardée automatiquement dans le navigateur utilisé. Le bouton
**Enregistrer** ou **Ctrl+S** exporte un fichier `.mindmap.json` pour conserver
une copie ou la transférer. **Ouvrir** recharge ce fichier, avec ses images,
ses périodes et sa mise en forme. Le bouton **PNG** exporte une image de la carte.

Le HTML contient l’application ; les fichiers JSON contiennent les cartes.
La version principale conserve la clé de sauvegarde locale des versions
précédentes et démarre avec une carte vide en l’absence de sauvegarde.
