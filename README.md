# Visualisation des Problèmes de Synchronisation

Cette application web interactive démontre les problèmes classiques de synchronisation en systèmes d'exploitation à travers des animations et des visualisations dynamiques.

## 🎯 Fonctionnalités

### 1. Les 5 Philosophes
- Simulation interactive du problème des philosophes qui dînent
- Visualisation des états : pensée, faim, repas
- Détection automatique des situations de blocage (deadlock)
- Représentation visuelle des ressources partagées (fourchettes)
- Code couleur intuitif pour les différents états

### 2. Exclusion Mutuelle
- Démonstration de l'accès concurrent à une ressource partagée
- Visualisation des conflits d'accès
- Simulation de processus concurrents
- Détection et affichage des violations de l'exclusion mutuelle

### 3. Producteur-Consommateur
- Buffer limité avec visualisation de l'état
- Gestion des conditions de buffer plein/vide
- Indicateurs visuels des erreurs de synchronisation
- Animation des opérations de production/consommation

### 4. Lecteurs-Écrivains
- Gestion prioritaire des accès en lecture/écriture
- Visualisation des conflits de lecture/écriture
- Indicateurs d'état pour la ressource partagée
- Détection des violations de priorité

## 🔧 Technologies Utilisées

- HTML5
- CSS3 avec animations
- JavaScript (Vanilla)
- SVG pour les visualisations
- Pas de dépendances externes

## 🚀 Installation

1. Clonez le repository :
```bash
git clone https://github.com/votre-username/sync-problems-visualization.git
```

2. Ouvrez `index.html` dans votre navigateur web

Aucune installation supplémentaire n'est nécessaire, l'application fonctionne directement dans le navigateur.

## 💡 Utilisation

### Les 5 Philosophes
- Cliquez sur un philosophe pour changer son état
- Observez les changements de couleur des fourchettes
- Surveillez les alertes de blocage

### Exclusion Mutuelle
- Ajoutez des processus avec le bouton dédié
- Cliquez sur les processus pour simuler l'accès à la ressource
- Observez les conflits d'accès

### Producteur-Consommateur
- Utilisez les boutons Producteur/Consommateur
- Surveillez l'état du buffer
- Notez les messages d'erreur en cas de violation

### Lecteurs-Écrivains
- Ajoutez des lecteurs ou des écrivains
- Observez les changements d'état de la ressource
- Notez les conflits d'accès

## 📚 Valeur Pédagogique

Cette application est conçue pour :
- Illustrer visuellement des concepts complexes de synchronisation
- Permettre l'expérimentation interactive
- Démontrer les situations de blocage et de conflit
- Servir de support pédagogique pour l'enseignement des systèmes d'exploitation

## 🤝 Contribution

Les contributions sont les bienvenues ! Pour contribuer :

1. Forkez le projet
2. Créez une branche pour votre fonctionnalité (`git checkout -b feature/nouvelle-fonctionnalite`)
3. Committez vos changements (`git commit -m 'Ajout d'une nouvelle fonctionnalité'`)
4. Poussez vers la branche (`git push origin feature/nouvelle-fonctionnalite`)
5. Ouvrez une Pull Request

## 📝 Licence

Distribué sous la licence MIT. Voir `LICENSE` pour plus d'informations.

## ✨ Futures Améliorations

- [ ] Ajout de nouveaux problèmes de synchronisation
- [ ] Statistiques en temps réel
- [ ] Mode tutoriel guidé
- [ ] Support mobile amélioré
- [ ] Sauvegarde des scénarios
- [ ] Export des simulations

## 📞 Contact

Créez une issue pour toute question ou suggestion.

---
⭐️ Si ce projet vous a aidé, n'hésitez pas à lui donner une étoile sur GitHub !
