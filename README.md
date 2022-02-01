# prediction_risque
Ce dossier est constitué :
* D'un script R.
* Un article de 5 pages sur lequel nous avons restitué nos résultats.
* Des slides à partir desquelles nous avons fait une présentation orale.
## Contexte
Dans ce projet, l'objectif était de construire un modèle qui prédit pour chaque assuré sa probabilité de déposer une réclamation au cours de la prochaine année.
Nous venions de suivre un module d'une vingtaine d'heure sur le machine learning qui était assez générique. L'idée était donc de mobiliser les connaissances que nous venions d'apprendre dans un projet.
## Données à disposition
Les données que nous avons à disposition provenaient d'une société d'assurance et étaient complètement anonymisées.
Nous savions seulement quelle était la variable cible et quelles étaient les variables explicatives mais nous n'avions aucune information sur leur signification métier (nous n'avions ni le nom de la variable ni son unité).
Pour un soucis de confidentialité, la base de données n'est pas partagée. Le code et les conclusions sont par contre disponibles.
## Traitements réalisés
* Beaucoup de valeurs étaient manquantes dans la base de données. Nous avons fini par réaliser une imputation par arbre.  
* Il y avait par ailleurs une forte corrélation entre certaines variables, nous avons donc fait une sélection de variables.
* Les données étaient de plus fortement déséquilibrées : cela aussi nous a posé quelques soucis. Nous avons fini par adopter une stratégie de sous-échantillonnage.
## Comparaison des modèles
Les deux modèles que nous avons entrainés sont : la Random Forest et la régression logistique pénalisée.
Nous avons ensuite comparés les résultats obtenus et choisi le modèle optimal.

# Auteurs
* DURAND-HARDY François
* JOBARD Rémi
* POUSSIER Quentin
