#  IchtyoScope

[ Voir la vitrine IchtyoScope](https://charles-t-sys.github.io/IchtyoScope/)

IchtyoScope est une **plateforme analytique et de visualisation multi-années** dédiée aux statistiques de pêche (1994–aujourd’hui).  
Elle appuie la **gestion intégrée des territoires fauniques** grâce à l’analyse des captures, de l’effort, de la biomasse, des tendances long terme et des effets réglementaires.

---

##  Caractéristiques principales

- **Analyse multi-indicateurs** : captures, effort, biomasse, succès, poids moyen, kg/ha, taux de remise, nombre de groupes.  
- **Modules avancés** :  
  -  Statistiques inférentielles (tests, ANOVA multifactorielle).  
  -  Effets des changements réglementaires (quotas, règlements « mouche seule »).  
  -  Détection des seuils critiques et alertes (succès, biomasse, effort, taux de remise).  
  -  Comparatif multi-lacs et vision par bassins versants.  
  -  Suivi des ensemencements et taux de retour.  
- **Exports interactifs** : rapports en PDF/Excel et graphiques exportables.  
- **Intégration fluide des données** :  
  - Historiques (1994–2017).  
  - Récentes (2018+).  
- **Tableaux et graphiques dynamiques** avec filtres latéraux, zoom et interactions.

---

## Aperçu visuel

Exemples d’analyses générées par IchtyoScope :

<p align="center">
  <img src="docs/sc1.png" alt="Capture IchtyoScope 1" width="45%">
  <img src="docs/sc2.png" alt="Capture IchtyoScope 2" width="45%"><br>
  <img src="docs/sc3.png" alt="Capture IchtyoScope 3" width="45%">
  <img src="docs/sc4.png" alt="Capture IchtyoScope 4" width="45%"><br>
  <img src="docs/sc5.png" alt="Capture IchtyoScope 5" width="70%">
</p>

---

## Structure

- `app.py` → Application Streamlit principale  
- `modules/` → Modules analytiques (résumé annuel, variabilité journalière, corrélations, alertes, effets réglementaires, etc.)  
- `data/` → Fichiers de statistiques (historiques et récents)  
- `docs/` → Site vitrine GitHub Pages  

---

##  Auteur

Développement : **Charles Tremblay, biologiste**  
[🔗 Profil GitHub](https://github.com/Charles-T-sys)  
