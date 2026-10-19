# Coûts d'assurance santé aux États-Unis — analyse exploratoire

> Quels facteurs font varier la prime d'assurance santé ? Le tabagisme d'abord : un fumeur paie en moyenne 32 050 $ par an, contre 8 434 $ pour un non-fumeur. Viennent ensuite l'âge et l'IMC.

**Projet personnel d'apprentissage · mai 2025** · Python · pandas · plotly · Jupyter

---

## Question
Mesurer l'effet de l'âge, du sexe, de l'IMC, du nombre d'enfants, du tabagisme et de la région sur les primes d'assurance santé.

## Données
- **Volume :** 1 338 assurés, 7 variables (`insurance.csv`).
- **Limite :** c'est un jeu d'exemple. Les écarts observés sont des moyennes brutes, non contrôlées pour les autres variables.

## Démarche
1. Charger et contrôler le jeu de données (pandas).
2. Calculer des moyennes par groupe et des comparaisons croisées, puis les visualiser (plotly).
3. Analyser par variable : IMC, primes, région, tabagisme.

## Résultats
| Facteur | Constat |
|---|---|
| Tabagisme | 32 050 $ en moyenne pour un fumeur, contre 8 434 $ pour un non-fumeur (×3,8) |
| Âge | ≈ 7 000 $ à 18 ans, 12 000 $ à 36 ans, 22 000 $ à 60 ans |
| Région | Le Sud-Est a les primes les plus élevées (14 740 $), l'IMC moyen le plus haut (33,4) et 25 % de fumeurs |
| Sexe | Les hommes paient un peu plus (13 957 $ contre 12 570 $) |

## Limites et pistes
- Les comparaisons sont descriptives : l'effet du sexe s'explique peut-être par une proportion de fumeurs différente.
- **Pistes :** une régression multiple pour isoler l'effet de chaque facteur.

## Compétences mobilisées
`Python` · `pandas` · `plotly` · `Analyse exploratoire`

## Contenu
```
us-medical-insurance-costs.ipynb
insurance.csv
```

---
Leo Cabart · Data Analyst · [Portfolio](https://lcabart21.github.io) · [GitHub](https://github.com/lcabart21)
