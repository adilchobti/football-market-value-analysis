[Open in Google Colab](https://colab.research.google.com/github/TON_PSEUDO/football-market-value-analysis/blob/main/notebooks/01_market_value_vs_age.ipynb)
# Football Market Value Analysis (French Version Below)

## Objective
This project analyzes the relationship between **player age** and **market value** in elite football transfers (2025 summer window).

To reduce noise from low-fee deals, the study focuses on the **Top 500 most expensive transfers**, providing a clearer view of high-value market dynamics.

---

## Methodology
- Data cleaning and normalization of market values
- Selection of the Top 500 transfers by transfer fee
- Comparison of:
  - raw vs smoothed average market value by age
  - market value distributions by tactical role group (**Defense / Midfield / Attack**)
- Visualization of the **Top 10 most expensive transfers (Summer 2025)** using an external curated source

---

## Key Insights
- Market value peaks early, around **19–21 years old**, for elite transfers
- Attacking players show higher upside, while midfielders and defenders display more stable value distributions
- Market value gradually declines after the mid-20s

---

## Tools
Python, pandas, numpy, matplotlib  
Google Colab

---

## Notes
The dataset is not included in this repository.  
Data is uploaded manually in the notebook for reproducibility.

-----------------------------------
# VERSION FRANÇAISE : Analyse de la Valeur Marchande des Joueurs de Football

## Objectif
Ce projet analyse la relation entre **l’âge des joueurs** et leur **valeur marchande** lors des transferts de football de haut niveau (mercato été 2025).

Afin de limiter le bruit lié aux transferts à faible montant, l’analyse se concentre sur les **500 transferts les plus chers**, ce qui permet une lecture plus pertinente des dynamiques du marché d’élite.

---

## Méthodologie
- Nettoyage et normalisation des valeurs marchandes
- Sélection des 500 transferts les plus élevés en montant
- Comparaison :
  - de la valeur marchande moyenne par âge (brute et lissée)
  - des distributions de valeur par groupe tactique (**Défense / Milieu / Attaque**)
- Visualisation du **Top 10 des transferts les plus chers (été 2025)** à partir d’une source externe

---

## Résultats clés
- La valeur marchande atteint un pic précoce, autour de **19–21 ans**, pour les transferts d’élite
- Les joueurs offensifs présentent un potentiel de valorisation plus élevé, tandis que les milieux et défenseurs affichent des distributions plus stables
- La valeur marchande décroît progressivement après le milieu de la vingtaine

---

## Outils
Python, pandas, numpy  
matplotlib, Google Colab

---

## Remarque
Le jeu de données n’est pas inclus dans ce dépôt.  
Les données sont importées manuellement dans le notebook afin de garantir la reproductibilité.
