# Projet Stat-Math : Étude des Théorèmes Statistiques avec le Jeu de Données Wine Quality

## Description du Projet
Ce projet explore les fondements mathématiques des statistiques, en particulier la **Loi Forte des Grands Nombres (LFGN)** et le **Théorème Central Limite (TCL)**, à travers l'analyse du jeu de données **Wine Quality**. Ce dataset contient des informations sur les propriétés physico-chimiques de différents types de vins (rouge et blanc) ainsi que leurs notes de qualité. L'objectif est de valider ces théorèmes fondamentaux et d'analyser la convergence des estimateurs, le biais, la variance, et les intervalles de confiance.

---

## Objectifs
1. **Loi Forte des Grands Nombres (LFGN)** : Étudier la convergence de la moyenne empirique vers la moyenne théorique.
2. **Théorème Central Limite (TCL)** : Vérifier si la distribution des moyennes empiriques tend vers une loi normale.
3. **Convergence des Estimateurs** : Analyser la robustesse des estimateurs de la moyenne et de la variance.
4. **Biais et Variance** : Évaluer l'équilibre entre précision et stabilité des estimations.
5. **Intervalles de Confiance** : Construire et interpréter des intervalles de confiance pour quantifier l'incertitude des estimations.

---

## Jeu de Données
Le jeu de données **Wine Quality** comprend 6497 échantillons de vins, caractérisés par 11 propriétés physico-chimiques :
- `fixed_acidity`, `volatile_acidity`, `citric_acid`, `residual_sugar`, `chlorides`
- `free_sulfur_dioxide`, `total_sulfur_dioxide`, `density`, `pH`, `sulphates`, `alcohol`


---

## Fondements Théoriques
### 1. **Loi Forte des Grands Nombres (LFGN)**
La LFGN stipule que la moyenne empirique d'un échantillon converge vers la moyenne théorique lorsque la taille de l'échantillon tend vers l'infini.  
Formellement :  

$\lim_{n \to \infty} \frac{1}{n} \sum_{i=1}^{n} X_i = \mu \quad \text{presque sûrement.}$

### 2. **Théorème Central Limite (TCL)**
Le TCL affirme que la distribution des moyennes empiriques suit une loi normale pour des échantillons suffisamment grands, quelle que soit la distribution initiale.  
Formellement :  
$\frac{\sqrt{n}(\bar{X}_n - \mu)}{\sigma} \xrightarrow{d} \mathcal{N}(0, 1).$

### 3. **Biais et Variance**
- **Biais** : Écart entre l'estimation et la vraie valeur.
- **Variance** : Dispersion des estimations autour de la moyenne.

---

## Structure du Projet
1. **Introduction** : Contexte et objectifs.
2. **Exploration des Données** : Analyse descriptive et visualisations.
3. **Validation des Théorèmes** :
   - LFGN : Convergence de la moyenne empirique.
   - TCL : Distribution des moyennes et comparaison avec la loi normale.
4. **Analyse des Estimateurs** : Biais, variance et intervalles de confiance.
5. **Conclusion** : Synthèse des résultats et implications.

---

##  Outils et Technologies
- **Langage** : Python
- **Bibliothèques** : Pandas, NumPy, Matplotlib, Seaborn, SciPy
- **Environnement** : Jupyter Notebook

---

## Résultats Clés
- **Convergence de la Moyenne** : La moyenne empirique converge vers la moyenne théorique, confirmant la LFGN.
- **Distribution Normale** : La distribution des moyennes suit une loi normale, validant le TCL.
- **Intervalles de Confiance** : Les intervalles se resserrent avec l'augmentation de la taille de l'échantillon.

---



---

<div align="center">
  <img src="https://thumbs.dreamstime.com/b/graphique-de-gestion-17998087.jpg" alt="Wine Quality" width="200"/>
</div>


