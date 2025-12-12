---
title: "Projet 1 : Analyse de la Transition Énergétique (Python & Power BI)"
date: 2025-12-12T12:15:00+01:00
draft: false
tags: ["Python", "Pandas", "Matplotlib", "Seaborn", "Power BI", "Modélisation", "Visualisation"]
---

## 🎯 Problématique Business et Objectif

Ce projet s'inscrit dans la continuité de mon parcours académique et professionnel et visait à **explorer, nettoyer et analyser un vaste ensemble de données énergétiques** afin de comprendre l'évolution des filières de production en France et **d'évaluer si la trajectoire actuelle permet d'atteindre les objectifs fixés pour 2030**. L'objectif principal était de rendre accessibles et compréhensibles des informations complexes à un public non expert.

``
---

## 🛠️ Méthodologie et Compétences Techniques

### 1. Pré-processing et Nettoyage des Données (Python)
* **Source :** Jeu de données Éco2mix régional (RTE / Opendatasoft).
* **Nettoyage (Python/Pandas) :** Travail approfondi pour garantir la fiabilité et la cohérence des résultats. Les données ont été filtrées pour conserver les observations "définitives".
* **Qualité des Données :** Traitement des valeurs manquantes, notamment pour la production éolienne (remplacement par la médiane mensuelle régionale) et gestion des TCO/TCH manquants avant 2020.
* **Feature Engineering :** Conversion des variables temporelles en formats date, heure et datetime pour l'analyse temporelle. Suppression des colonnes non pertinentes pour l'analyse car totalement vides, ne contenant ainsi aucune donnée exploitable.

### 2. Analyse et Visualisation (Power BI)
* **Dashboard :** Conception d'un tableau de bord sous **Power BI** organisé en 8 volets complémentaires.
* **Thématiques Clés :** Analyse du mix énergétique, des dynamiques régionales, de l'autonomie (TCO) et des trajectoires carbone et objectifs.
* **UX/Interactivité :** Intégration de filtres globaux, de cartes thématiques, et d'un bouton "info" redirigeant sur une note de lecture et interprétation pour accompagner le lecteur.
* **Optimisation :** Réduction des relations inutiles dans le modèle de données et création de mesures DAX dédiées.

---

## 📈 Résultats et Conclusion Stratégique

* **Objectif Bas Carbone Dépassé :** L'analyse montre que la France dépasse son objectif bas carbone, principalement grâce au rôle stabilisateur du nucléaire.
* **Potentiel Renouvelable :** Le déploiement des énergies renouvelables progresse, mais leur contribution reste limitée par l'intermittence liée à la dépendance aux conditions météorologiques(notamment pour le solaire et l'éolien). L'étude a mis en évidence un potentiel encore largement mobilisable dans l'éolien, l'hydraulique et le solaire.
* **Compétences Démontrées :** Maîtrise des outils techniques (Python, Power BI) et capacité à transformer des données complexes en une narration simple, cohérente et pédagogique.

---

## 🔗 Liens

* **Analyse/Nettoyage (Python) :** [https://github.com/evacarones15/projet-analyse-energie]
* **Dashboard Power BI** : [Lien vers la version publique du Dashboard]
