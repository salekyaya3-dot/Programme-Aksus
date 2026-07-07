# Guide de Contribution - AKSUS 1

Merci d'intéresser à la contribution à AKSUS 1! Ce guide vous aidera à contribuer efficacement.

## Code de Conduite

Nous nous engageons à maintenir un environnement de travail inclusif et respectueux.

## Comment Contribuer

### 1. Fork le Projet

```bash
git clone https://github.com/votre-username/aksus-programe.git
cd aksus-programe
```

### 2. Créer une Branche

```bash
git checkout -b feature/AK-XXX-description
```

### 3. Faire des Commits

```bash
git commit -m "feat: description de la fonctionnalité"
```

**Format des commits:**
- `feat:` Nouvelle fonctionnalité
- `fix:` Correction de bug
- `docs:` Documentation
- `style:` Style de code
- `refactor:` Refactorisation
- `test:` Tests
- `chore:` Maintenance

### 4. Push et Pull Request

```bash
git push origin feature/AK-XXX-description
```

Créez une Pull Request sur GitHub avec une description détaillée.

## Standards de Code

### Backend (NestJS)
- TypeScript strict mode
- Utiliser les décorateurs NestJS appropriés
- Tester avec Jest
- Respecter la structure des modules

### Frontend (Next.js)
- React Hooks et functional components
- TypeScript pour la sécurité des types
- Tailwind CSS pour le styling
- Tests avec Jest et React Testing Library

## Tests

Avant de soumettre un PR:

```bash
# Backend
cd backend
npm run test
npm run lint

# Frontend
cd frontend
npm run test
npm run lint
```

## Documentation

Mettez à jour la documentation si vous changez:
- Les APIs
- Les configurations
- Les processus

## Questions?

Créez une issue ou contactez l'équipe AKSUS.

Merci pour votre contribution! 🙏
