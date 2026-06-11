# 📊 Performance Training Platform

> **🎯 Mission: Mesurer, Analyser, Optimiser**  
> Cette plateforme est conçue pour l'apprentissage de l'optimisation web et de l'éco-conception.

## 🚀 Démarrage Rapide

### Prérequis
- Node.js ≥ 18
- npm ≥ 9

### Installation & Lancement

```bash
# Installation des dépendances
npm install

# Démarrage de l'application complète
npm run dev
```

L'application sera disponible sur :
- Frontend: http://localhost:3000
- Backend: http://localhost:5001

### Scripts Disponibles

- `npm run dev` - Lance frontend et backend simultanément
- `npm run frontend` - Lance uniquement le frontend (Vite)
- `npm run backend` - Lance uniquement le backend (Express)
- `npm run build` - Build de production
- `npm run lint` - Analyse du code

## 📈 Métriques en Temps Réel

La plateforme affiche en continu :

- **Taille du bundle** : Poids total des ressources chargées
- **Poids page** : Poids total de la page (toutes ressources confondues)
- **Objets DOM** : Complexité de la page (nombre de nœuds)
- **Ressources** : Nombre de ressources chargées
- **JS** : Poids total des fichiers JavaScript
- **CSS** : Poids total des fichiers CSS
- **Images** : Poids total des images chargées
- **Cache hit** : Taux d’utilisation du cache navigateur
- **Utilisation mémoire** : Consommation RAM côté serveur
- **CPU** : Charge processeur du serveur
- **Requêtes/seconde** : Fréquence des appels API (RPS)
- **Temps de rendu** : Performance d'affichage (temps de chargement)

## 🎓 Objectifs Pédagogiques

### Phase 1 : Mesure
1. Analyser les métriques de base
2. Identifier les goulots d'étranglement
3. Documenter les problèmes observés

### Phase 2 : Diagnostic
1. Utiliser les outils de développement
2. Analyser les performances réseau
3. Examiner l'utilisation des ressources

### Phase 3 : Optimisation
1. Réduire la taille du bundle
2. Optimiser les requêtes réseau
3. Améliorer la gestion mémoire
4. Implémenter le cache
5. Optimiser les images

## 🛠️ Outils Recommandés

- **Chrome DevTools** (Performance, Network, Memory)
- **Lighthouse** pour l'audit
- **webpack-bundle-analyzer** pour l'analyse du bundle
- **ecoindex-cli** pour l'impact environnemental

## 📁 Structure du Projet

```
├── frontend/           # Application React + TypeScript
├── backend/           # Serveur Express.js
├── data/              # Fichiers de données volumineux
├── assets/            # Images et ressources
├── scripts/           # Scripts utilitaires
└── README.md          # Ce fichier
```

## 🎯 Critères de Réussite

Après optimisation, vous devriez observer :
- Réduction significative de la taille du bundle
- Diminution du nombre de requêtes réseau
- Amélioration des Core Web Vitals
- Stabilisation de l'utilisation mémoire
- Amélioration du score éco-index

## 🌱 Impact Environnemental

Cette plateforme permet d'apprendre :
- L'éco-conception web
- La mesure de l'empreinte carbone
- L'optimisation des ressources
- Les bonnes pratiques environnementales

---

**Bonne formation ! 🚀**

*L'objectif est d'apprendre à identifier et corriger les problèmes de performance.*

## Parcours de l'exercice

Les instructions complètes se trouvent dans [`consigne.md`](./consigne.md) et les
objectifs d'amélioration dans [`backlog.md`](./backlog.md).

1. Réaliser un audit GreenIT initial dans `audit-initial.md`.
2. Étudier le backlog et documenter le plan dans `plan.md`.
3. Implémenter les optimisations retenues.
4. Réaliser le même audit dans `audit-final.md`.
