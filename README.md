# Journal météorologique de la ferme

> Projet individuel du SAS DFS, brief 4 (sujet : [SUJET.md](SUJET.md)). Remplacez chaque ✏️ par votre texte, puis supprimez cette ligne.

## Contexte

 L'outil est utlisé par le chef d'exploitation ,l'agriculeur ,les techniciens agricoles ,l'outil permet de centralisé des données,dipose d'un historique traçable et ce qu'il ne peut pas faire ,ce sont les previsions futures de la méteo ,de decider à la place de l'agriculteur.

## Prérequis et lancement

- Node.js 20 ou plus récent, Git ; aucune bibliothèque à installer.

```bash
git clone https://github.com/VOTRE-COMPTE/brief-4-journal-meteo.git
cd brief-4-journal-meteo
node app.js
npm test
```

Sous PowerShell, si `npm` est bloqué : `npm.cmd test`.

## Fonctionnalités

✏️ *Cochez seulement ce qui marche : `- [x]`.*

- [X] Données lues et enregistrées dans `donnees/releves.json`
- [X] Ajouter un relevé, saisies invalides refusées sans arrêter le programme
- [X ] Lister les relevés, message si le journal est vide
- [X] Rechercher par identifiant ou par date ; journées pluvieuses (au moins 10 mm)
- [X] Trier par température ou par pluie
- [x] Synthèse : température moyenne, minimale et maximale de la série, cumul de pluie, journées pluvieuses
- [ ] Bonus : supprimer et modifier un relevé (choix 6 et 7)
- [ ] Bonus : tri par température décroissante, journée la plus chaude

## Données00

✏️ *Le fichier, le nombre de relevés, les champs (voir [docs/dictionnaire-donnees.md](docs/dictionnaire-donnees.md)), les unités. Rappelez qu'ils sont fictifs.*
Nous avons dix relevés qui comprennent des champs et des unités
Le Champ ID n' a aucune unité ,le champ date n'aucune unité, le champ temperature à pour unité (°C),le champ Pluie unité en (Mm) et le champ Humidité de l'air en (%)
## Limites

*Au moins trois. Par exemple : dix jours de relevés forment une courte série, ils ne décrivent pas le climat de la région.*
Les limites presentées :
-Données d'une seule station ne sont pas representatif d'une ville ou d'une region entière.
-La gestion des valeurs peut être aberrantes et des données manquantes
-Les 10 jours de relevés répresentent une courte serie et ne permet pas de décrire le climat.
## Documents

[Dictionnaire des données](docs/dictionnaire-donnees.md) · [Tâches](docs/taches.md) · [Relevé des tests](docs/releve-tests.md) · [Journal de recherche](docs/journal-recherche.md) · [Fiche agronomique](docs/fiche-agronomique.md) · [Fiche individuelle](docs/fiche-individuelle.md)

## Auteur

✏️ *Prénom NOM, compte GitHub. Entraide : avec qui, sur quoi.*

