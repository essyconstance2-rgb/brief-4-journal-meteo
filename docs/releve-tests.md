# Relevé des tests

> Écrivez le résultat attendu avant d'essayer. Un écart n'est pas une faute : notez-le, corrigez, refaites le test.

**Calculs à la main** : refaites à la main les résultats de référence de `SUJET.md`, puis comparez avec votre programme. 
Moyenne de temperature = (27+28+26+29+27+30+28+26+29+30)/10
Total =28°C
Temperature minimum = 26°C ;ID :"MO3" ; ID:"M08"
temperature maximale = 30° C ;ID: "M06" ; ID: "M10"
cumul de pluie + (0+ 5+ 12+10 +0 +3 +8 +15 +0 +2 ) = 45mm
Journée avec au moins 10 mm = "M03"(12mm );"M08"(15mm)

**Essais dans le menu** : un ajout valide (encore là après redémarrage), chaque règle refusée, une recherche introuvable, chaque tri, la synthèse, un choix inconnu.

| Action | Attendu | Obtenu | Testeur |
| --- | --- | --- | --- |
| Ajouter un relevé |relevé ajouté M11| Le reslutat comptient 12 relevés  | moi
|  Ajouter un relevé existant |relevé refusé | identifiant deja utilisé | |Moi
| Rechercher inexistant| relevé non retrouvé | | |
| Trier par temperature |afficher par ordre  |afficher par ordre croissant| |Moi
| Trier par pluie |afficher par ordre croissant | les pluies sont affichés par par ordre croissant | Moi
| synthése de la série | affichage synthése| de la synthése|Quelques jours de relevés forment une courte série météo : ils ne décrivent pas le climat de la région.
  - Le seuil de 10 mm est une catégorie d'exercice : il ne prévoit ni inondation ni stress hydrique.
  - L'humidité relative de l'air (en %) n'est pas l'humidité du sol. |Moi

**Sur un autre poste** (`git clone`, `node app.js`, `npm test`, en suivant le README) : ✏️
