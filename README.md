# BOOTCAMP_EXCEL

Travaux personnels réalisés pendant un bootcamp Excel , orienté **analyse de données**. Ce dépôt rassemble six classeurs, des bases de la formule jusqu'à un projet complet d'analyse avec tableau de bord.

> Les jeux de données utilisés viennent du bootcamp (données d'exercice). Seuls mes classeurs de travail sont publiés ici.

## Compétences pratiquées

- **Calculs et opérateurs** : priorité des opérations, pourcentages, références de cellules
- **Fonctions logiques** : `SI`, `ET`, `OU`, `SIERREUR`, conditions imbriquées
- **Mise en forme conditionnelle** : surbrillance, jeux d'icônes, barres de données, échelles de couleurs
- **Tableaux structurés** et références structurées (`Ventes[Chiffre_Affaires]`)
- **Graphiques** : barres, courbes, secteurs, nuage de points
- **Tableaux croisés dynamiques** et **segments** (filtres interactifs)
- **Préparation des données** : séparation données brutes / données nettoyées, colonnes calculées (`ANNEE`, `MOIS`)
- **Tableaux de bord** : indicateurs clés et graphiques sur une même feuille

## Contenu du dépôt

| Fichier | Ce qu'il contient |
| --- | --- |
| `Operateur et calcul.xlsx` | Opérateurs arithmétiques (`+ - * /`), priorité des opérations (`=10+5*2` contre `=(10+5)*2`), pourcentages, et un **calculateur de salaire** (prime de performance, heures supplémentaires, salaire brut, retenue, salaire net). |
| `Fonction_logique.xlsx` | Base de 1 000 lignes avec colonnes calculées : résultat « admis / non admis », profil éligible (`SI` + `ET` avec conditions sur les notes et la présence), décision à trois niveaux (admis, admis sous condition, refusé), alerte (`SI` + `OU`), statut par filière. Une feuille utilise `SIERREUR` pour éviter les divisions par zéro. |
| `mise en forme conditionnelle.xlsx` | Quatre feuilles sur la même base de 1 000 lignes : notes colorées selon des seuils (< 10, entre 10 et 14,99, ≥ 15), présence ≥ 80 % mise en évidence, **feux tricolores**, **barres de données** et **échelle de couleurs**. |
| `Tableau.xlsx` | Ventes mises sous forme de **tableaux structurés** (`Ventes`, `tb1Ventes`) : chiffre d'affaires par ligne, montant net après remise, totaux avec références structurées. |
| `dashbords.xlsx` | Base de ventes (date, produit, catégorie, vendeur, quantité, prix, remise, montant net), **5 graphiques** (barres, courbe, secteurs, nuage de points) et une feuille de synthèse avec les indicateurs : CA total, CA net, quantité vendue, nombre de ventes. |
| `projet_complet_analyse_des_données.xlsx` | **Projet complet** sur 10 194 lignes de commandes (2023 à 2026) : données brutes et données nettoyées, colonnes `year` et `month`, **21 tableaux croisés dynamiques**, segments (Segment, Region, Category, année), 5 graphiques et un tableau de bord. Chiffres clés : chiffre d'affaires de 2,33 M, profit de 292 k, 5 111 commandes. |

## Organisation d'un classeur d'analyse

Dans le projet complet, les feuilles suivent un schéma classique :

1. `raw_data` : données brutes, conservées intactes
2. `clean_data` : données préparées, avec les colonnes calculées
3. `tb1sales` : tableaux croisés dynamiques
4. `Dashbord` : graphiques et segments pour la lecture

## Auteure

**Coumba Niang** : formation Développement Data à la Sonatel Academy, étudiante en mathématiques.
Compétences : Python (Pandas, NumPy), SQL/PostgreSQL, Power BI, Excel.
