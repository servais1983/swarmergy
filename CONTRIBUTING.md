# Guide de contribution à Swarmergy

Merci de votre intérêt pour contribuer au projet Swarmergy ! Nous sommes ravis d'accueillir de nouveaux contributeurs dans notre essaim.

## 🐝 Comment contribuer

### 1. Types de contributions

Vous pouvez contribuer de plusieurs façons :

- **Code** : Développement des composants logiciels (Smart Hub, applications, backend)
- **Design** : Interface utilisateur, expérience utilisateur, identité visuelle
- **Documentation** : Tutoriels, guides, documentation technique
- **Tests** : Tests unitaires, tests d'intégration, tests utilisateurs
- **Idées** : Suggestions d'amélioration, nouvelles fonctionnalités
- **Communication** : Traductions, matériel promotionnel, présentations

### 2. Workflow de contribution

1. **Consultez les issues** : Vérifiez les issues existantes pour voir si quelqu'un travaille déjà sur votre idée
2. **Créez une issue** : Si votre idée n'est pas déjà traitée, créez une nouvelle issue
3. **Discutez** : Échangez avec l'équipe sur la meilleure approche
4. **Fork & Clone** : Créez un fork du dépôt et clonez-le localement
5. **Créez une branche** : Créez une branche pour votre contribution
6. **Codez** : Implémentez votre contribution
7. **Testez** : Assurez-vous que votre code fonctionne correctement
8. **Soumettez une PR** : Créez une Pull Request pour proposer vos changements

### 3. Normes de codage

- **Lisibilité** : Écrivez du code lisible et bien commenté
- **Tests** : Incluez des tests pour votre code
- **Documentation** : Documentez vos fonctions et classes
- **Commits** : Utilisez des messages de commit clairs et descriptifs

## 🏗️ Structure du projet

```
swarmergy/
├── assets/            # Ressources graphiques
├── docs/              # Documentation
├── src/               # Code source
│   ├── alvéole/       # Composants pour les unités individuelles
│   ├── ruche/         # Composants pour la coordination locale
│   ├── essaim/        # Composants pour la coordination régionale
│   ├── blockchain/    # Composants blockchain
│   └── ui/            # Interface utilisateur
├── tests/             # Tests
└── tools/             # Outils de développement
```

## 📋 Conventions

### Nommage

- **Branches** : `type/nom-court` (ex: `feature/smart-hub-api`, `fix/battery-monitoring`)
- **Commits** : `type: description concise` (ex: `feat: add energy prediction algorithm`)
- **Issues** : Utilisez les templates fournis et ajoutez des tags appropriés

### Types de commits

- `feat` : Nouvelle fonctionnalité
- `fix` : Correction de bug
- `docs` : Documentation
- `style` : Formatage (pas de changement de code)
- `refactor` : Refactoring du code
- `test` : Ajout de tests
- `chore` : Maintenance

## 🚀 Démarrer

### Pré-requis

- Node.js v16+
- Python 3.8+
- Docker
- Compte GitHub

### Installation

1. Fork le dépôt
2. Clonez votre fork : `git clone https://github.com/VOTRE-USERNAME/swarmergy.git`
3. Installez les dépendances : `npm install` ou `pip install -r requirements.txt`

### Lancer le projet localement

```bash
# Pour le backend
cd src/backend
npm run dev

# Pour le frontend
cd src/frontend
npm start
```

## 📄 Code de conduite

En contribuant à ce projet, vous acceptez de respecter notre [Code de Conduite](CODE_OF_CONDUCT.md).

## 🙏 Remerciements

Un grand merci à tous les contributeurs qui rendent ce projet possible !

---

Si vous avez des questions, n'hésitez pas à les poser dans les issues ou à contacter l'équipe Swarmergy.