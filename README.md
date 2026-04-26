![NetLogo](https://img.shields.io/badge/netlogo-%23E15950.svg?style=for-the-badge&logoColor=white)
# Simulation de Pêche en Mer (NetLogo)

## Description

Ce projet est une simulation multi-agents développée avec NetLogo.  
Il modélise une activité de pêche en mer afin d'étudier la gestion d'une ressource naturelle limitée : les poissons.

L’objectif principal est d’illustrer le phénomène de la tragédie des communs, où des comportements individuels peuvent conduire à l’épuisement d’une ressource partagée.

---

## Objectifs

- Simuler un environnement marin avec reproduction des poissons
- Étudier l’impact des stratégies de pêche
- Observer l’évolution du stock de poissons dans le temps
- Mettre en évidence l’effondrement possible du système

---

## Types d'agents (bateaux)

Le modèle comporte trois types de pêcheurs :

- Coopératif : pêche de manière durable et laisse des poissons pour la reproduction
- Égoïste : maximise ses gains en pêchant intensivement
- Aléatoire : se déplace et pêche sans stratégie optimisée

---

## Environnement

- Grille représentant la mer
- Chaque case contient un nombre de poissons
- Les poissons se reproduisent selon une dynamique logistique
- Un port est situé en bas pour décharger les captures

---

## Fonctionnement

À chaque étape (tick) :

1. Les bateaux se déplacent selon leur stratégie
2. Ils pêchent les poissons présents sur leur position
3. Les poissons se reproduisent
4. Le stock total est mis à jour

---

## Résultat attendu

Une exploitation excessive, en particulier par les agents égoïstes, entraîne :
- une diminution rapide du stock de poissons
- puis un effondrement total de la ressource

---

## Concepts utilisés

- Simulation multi-agents
- Tragédie des communs
- Ressource limitée
- Dynamique de population (croissance logistique)

---

## Utilisation

1. Ouvrir le fichier `.nlogo` avec NetLogo
2. Cliquer sur "Setup"
3. Cliquer sur "Go"
4. Observer le comportement des agents et l’évolution des ressources

---

## Paramètres modifiables

- Nombre de bateaux de chaque type
- Taux de reproduction des poissons
- Capacité maximale par zone
- Vitesse de pêche

---

## Auteur

Projet réalisé dans le cadre d’un travail académique sur les systèmes complexes et la simulation.

---

## Conclusion

Ce modèle montre que sans coopération ou régulation, une ressource commune peut être rapidement épuisée, même si chaque agent agit de manière rationnelle individuellement.
