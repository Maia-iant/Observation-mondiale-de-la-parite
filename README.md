# 🌍 Observation mondiale de la parité – Tableau de bord Power BI

## 📊 Description du projet

Ce projet propose un tableau de bord interactif pour analyser la parité femmes‑hommes à l’échelle mondiale à partir de données internationales. Il permet d’identifier les écarts de genre par pays et par zone géographique, de suivre les évolutions historiques et de mettre en lumière les domaines où les inégalités restent les plus fortes (éducation, emploi, représentation politique, droits et libertés). 

## 🎯 Objectifs

- Mesurer la parité femmes‑hommes à travers plusieurs indicateurs clés.  
- Mettre en évidence les pays et régions en retard ou en progrès. 
- Fournir un outil d’aide à la décision pour les acteurs engagés sur l’égalité de genre.  
- Sensibiliser à l’impact des inégalités de genre sur le développement humain et économique. 

## 🗂️ Données

- Sources : jeux de données publics internationaux (organismes mondiaux, bases statistiques par pays et par année).  
- Thèmes couverts :  
  - 🎓 Alphabétisation et niveau d’éducation  
  - 💼 Emploi vulnérable et salariat par genre  
  - 🏛️ Représentation politique  
  - ⚖️ Droits et libertés (par exemple liberté de voyager, égalité salariale) 
- Clés de structuration :  
  - `codepays`  
  - Année  
  - Clé technique concaténée (`codepays-annee`) pour faciliter les jointures multi‑tables et les analyses temporelles. 

## 🧩 Modèle de données et méthodologie

- Cadrage des objectifs : analyser la parité femmes‑hommes et comparer les écarts entre pays, continents et périodes. 
- Collecte, nettoyage et préparation de plusieurs sources hétérogènes.  
- Modélisation en étoile autour des dimensions géographiques et temporelles, avec une table centrale reliée via `codepays` et la clé technique.  
- Création de mesures et d’indicateurs dérivés dans Power BI pour permettre les comparaisons et les analyses dynamiques.

## 📈 Tableau de bord Power BI

Le tableau de bord se compose de plusieurs vues interactives : 

- 🌐 Carte mondiale permettant de filtrer par indicateur et par zone géographique (monde, continent, pays). 
- 📊 Graphiques comparatifs par genre (alphabétisation, emploi vulnérable, salariat, représentation politique).  
- ⏱️ Analyses d’évolution historique pour observer les progrès ou stagnations dans le temps. 
- 🔎 Filtres interactifs et sélections dynamiques pour explorer les données selon différents axes.

## 💡 Pourquoi Power BI ?

- 💸 Coût économique faible grâce à la version gratuite, sans surcoût logiciel. 
- 🔗 Compatibilité naturelle avec les sources Excel, CSV et plateformes cloud courantes. 
- 🚀 Gestion performante de gros volumes de données. 
- 📉 Richesse des visualisations (nuages de points, cartes, barres empilées, lignes temporelles). 
- 🧭 Interactivité avancée : filtres personnalisés, sélection dynamique, vue multi‑échelle (monde, continent, pays).

## 🛠️ Utilisation

1. Cloner le dépôt ou le télécharger en ZIP.  
2. Ouvrir le fichier `.pbix` dans Power BI Desktop.  
3. Vérifier les chemins d’accès aux fichiers de données (dossier `data/`) et les mettre à jour si nécessaire.  
4. Utiliser les filtres et segments de données pour explorer la parité par pays, par période et par indicateur.

## 🚀 Pistes d’amélioration

- Ajout de nouvelles sources d’indicateurs (santé, violences, accès aux services financiers, etc.).  
- Mise à jour régulière des données pour suivre les progrès récents.  
- Création d’analyses focalisées par région ou type de pays (niveau de revenu, indice de développement).  
- Publication du rapport Power BI en ligne pour un accès web interactif.

## 👩‍💻 À propos

Je suis freelance, spécialisée en **data** / BI, avec un parcours de data analyst et une sensibilité particulière aux enjeux d’égalité, de justice sociale et d’émancipation. À travers ce projet, je souhaite mettre les données au service d’une meilleure compréhension des inégalités de genre et fournir des outils concrets pour orienter l’action et la prise de décision.
