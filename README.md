# Recetti Mobile App

Recetti Mobile App est une application mobile conçue pour aider les utilisateurs à trouver facilement des recettes en fonction des ingrédients qu'ils sélectionnent. Cette application est idéale pour ceux qui souhaitent explorer des recettes créatives à partir des ingrédients qu'ils ont sous la main.

## Fonctionnalités principales

- **Recherche intelligente de recettes** : Trouvez des recettes basées sur les ingrédients que vous avez.
- **Base de données riche** : Accès à une large sélection de recettes variées.
- **Interface utilisateur intuitive** : Une expérience utilisateur fluide et facile à naviguer.
- **Favoris** : Enregistrez vos recettes préférées pour y accéder rapidement.

## Technologies utilisées

### Frontend
- [React Native](https://reactnative.dev/) : Framework utilisé pour développer l'application mobile multi-plateformes (iOS et Android).

### Backend
- [Node.js](https://nodejs.org/) : Environnement d'exécution JavaScript pour le développement côté serveur.
- [Express.js](https://expressjs.com/) : Framework web rapide et minimaliste pour Node.js.
- [MongoDB](https://www.mongodb.com/) : Base de données NoSQL utilisée pour stocker les recettes et les informations des utilisateurs.

## Installation

### Prérequis
- Node.js installé sur votre machine
- MongoDB configuré et en cours d'exécution
- [Expo CLI](https://expo.dev/) (pour exécuter l'application React Native)

### Étapes
1. Clonez le dépôt :
   ```bash
   git clone https://github.com/Chaaamah/Recetti-Mobile-App.git
   cd Recetti-Mobile-App
   ```

2. Installez les dépendances pour le backend :
   ```bash
   cd backend
   npm install
   ```

3. Configurez les variables d'environnement pour le backend :
   - Créez un fichier `.env` dans le répertoire `backend`.
   - Ajoutez les variables nécessaires, par exemple :
     ```env
     PORT=5000
     MONGO_URI=mongodb://localhost:27017/recetti
     JWT_SECRET=your_jwt_secret
     ```

4. Lancez le serveur backend :
   ```bash
   npm start
   ```

5. Installez les dépendances pour le frontend :
   ```bash
   cd ../frontend
   npm install
   ```

6. Lancez l'application mobile :
   ```bash
   expo start
   ```

## Contribution

Les contributions sont les bienvenues ! Si vous souhaitez améliorer cette application, veuillez suivre ces étapes :

1. Forkez le projet.
2. Créez une branche pour vos modifications :
   ```bash
   git checkout -b feature/your-feature
   ```
3. Commitez vos modifications :
   ```bash
   git commit -m "Ajout de ma fonctionnalité"
   ```
4. Poussez vos modifications :
   ```bash
   git push origin feature/your-feature
   ```
5. Créez une Pull Request.
---
