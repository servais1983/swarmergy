# Structure du Code Source Swarmergy

## Vue d'ensemble

Ce dossier contient le code source du projet Swarmergy. La structure est organisée en modules correspondant aux différents niveaux du système alvéolaire (alvéole, ruche, essaim) et aux composants transversaux.

## Organisation des dossiers

```
src/
├── alveole/             # Code pour les nœuds individuels
│   ├── smart_hub/       # Logiciel du Smart Hub
│   ├── monitoring/      # Outils de surveillance énergétique
│   └── ui/              # Interface utilisateur locale
│
├── ruche/               # Code pour la coordination de quartier
│   ├── coordinator/     # Algorithmes de coordination locale
│   ├── storage/         # Gestion du stockage communautaire
│   └── mesh/            # Réseau maillé local
│
├── essaim/              # Code pour la coordination régionale
│   ├── swarm_brain/     # IA centrale et algorithmes d'optimisation
│   ├── forecast/        # Modèles de prévision (météo, consommation)
│   └── analytics/       # Analyses et rapports
│
├── blockchain/          # Composants blockchain
│   ├── contracts/       # Smart contracts
│   ├── nrgcoin/         # Implémentation du token
│   └── ledger/          # Registre distribué
│
├── common/              # Composants partagés
│   ├── utils/           # Utilitaires génériques
│   ├── config/          # Configuration
│   ├── security/        # Sécurité et authentification
│   └── api/             # Définitions d'API
│
└── ui/                  # Interfaces utilisateur
    ├── web/             # Application web
    ├── mobile/          # Applications mobiles
    └── dashboard/       # Tableaux de bord
```

## Conventions de codage

### Langages de programmation

- **Smart Hub** : Python/C++ pour les performances et la proximité matérielle
- **Backend** : Python, Node.js
- **Frontend** : React.js, Vue.js
- **Mobile** : React Native
- **Blockchain** : Solidity (smart contracts), Go (nœuds)

### Style de code

- Suivez les guides de style standard pour chaque langage :
  - [PEP 8](https://www.python.org/dev/peps/pep-0008/) pour Python
  - [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript) pour JavaScript
  - [Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html) pour C++
  - [Solidity Style Guide](https://docs.soliditylang.org/en/latest/style-guide.html) pour Solidity

### Documentation

- Docstrings pour toutes les fonctions et classes
- README.md dans chaque dossier principal
- Commentaires pour le code complexe

## Premiers composants à développer

1. **Smart Hub Basic** : Version minimaliste pour le pilote initial
2. **Monitoring API** : API pour collecter les données de production/consommation
3. **Web UI Prototype** : Interface web simple pour les participants au pilote
4. **NRGcoin Basic** : Implémentation initiale du token pour les échanges d'énergie

## Contribuer

Avant de commencer à développer, consultez le [guide de contribution](../CONTRIBUTING.md) pour plus d'informations sur le processus de développement et les normes de qualité.

---

⚡ **Swarmergy** - *Le réseau alvéolaire belge pour une énergie partagée* ⚡