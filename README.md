# Projet Power BI - Comparaison du département de la Meuse (55) & de la Moselle (57)
## Auteurs : Mathias Janin & Azad Lucas

Ce README est composé de:
1. Rappel du projet
2. Structure des fichiers du repository


## Rappel du projet
Dans le cadre du projet Power BI réalisé à l'IUT par les SD2 (années 2024-25), nous avons choisi de travailler sur les départements de la Meuse (55) et de la Moselle (57), respectivement le département le moins peuplé et le plus peuplé de la région Grand Est (France). Pour rappel, le projet consiste à développer des rapports Power BI permettant de visualiser des données énergétiques (logements neufs et existants) pour un lieu choisi.  Notre objectif est d'offrir à l'utilisateur des outils pour explorer les données via des graphiques, tableaux et cartographies interactives, afin de mieux cerner les différences au niveau des performances énergétiques entre un département à faible et à forte densité de population. En complément de ce travail, d'autres fichiers ont été implémenté dans ce repository afin de détailler davantage les analyses statistiques réalisées sur ces données. Ce projet s'inscrit dans le cadre d'une étude visant à explorer l'impact du Diagnostic de Performance Energétique (DPE) sur les consommations énergétiques des logements grâce à des données provenant de plusieurs sources, notamment la [Base Adresse Nationale](https://adresse.data.gouv.fr/data/ban/adresses/latest/csv) (BAN) et deux API fournies par l'[ADEME](https://data.ademe.fr/datasets?topics=BR8GjsXga) (logements neufs et existants).
<br>
</br>

## Structure des fichiers du repository
Voici la liste des fichiers disponibles dans ce repository et leur utilité dans le projet :
<br>
</br>
### **`df_final_Meuse.csv`**: 
Ce fichier contient la base de données nécessaire pour obtenir des informations liées au département de la Meuse sur PowerBI.
<br>
</br>
### **`df_final_Moselle.csv`**: 
Ce fichier contient la base de données nécessaire pour obtenir des informations liées au département de la Moselle sur PowerBI.
<br>
</br>
### **`Documentation fonctionnelle & technique.pdf`** : 
Documentation est le fichier regroupant la doc technique et fonctionnelle de l'application. La première est regroupe principalement les notions de modèle de données, règles RLS, diagnostique de l'analyse de performance du rapport PowerBI, ainsi que la maquette de l'application. 
La seconde sera plutôt orientée utilisateur. Vous y retrouverez tout ce qui est important pour la bonne utilisation de l'application, l'intérêt des visualisations choisies, ou encore les différentes fonctionnalités majeures de celle-ci.
<br>
</br>
### **`Rapport_Meuse_et_Moselle.pbix`** : 
Ce fichier est notre fichier final Power BI. Il regroupe l'intégralité de nos analyses, sous forme de visualisations et KPIs, permettant de comparer les différences de performances énergétiques entre les deux départements du Grand Est ayant un grand écart en terme de densité de population.
<br>
</br>
### **`README.md`** : 
Ce fichier que vous lisez actuellement. Il présente une vue d'ensemble du projet, sa structure, ainsi que les fichiers présents dans le repository.
