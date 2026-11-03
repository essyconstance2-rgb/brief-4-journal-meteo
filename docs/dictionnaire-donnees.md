# Dictionnaire des données

> Un champ par ligne, d'après `SUJET.md` et le fichier de `donnees/`. La première ligne sert de modèle.

| Champ | Signification | Type | Règle de validation | Unité | Exemple |
| --- | --- | --- | --- | --- | --- |
| `id` | Identifiant unique | texte | non vide, absent des données | — | MO307 |
| Date |   Date du relevé    | texte    | AAAA-MM-jj   |    _    |      2026-10-31
| temp c |temperature d'air  |nombre|valeur positive ou negative  |Degré celsus     |26 |
| pluie Mm |quantité de pluie | nombre|   >= 0         |  mm| |     12
| humid | humidité relative de l'air |nombre |0 à 100 |  %   | 78|

**Listes de valeurs autorisées** : Similaires au régles de validation

**Sources** : releves.json
