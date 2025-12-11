# Brand Vue Ecommerce Website (Front-End)

![Vue.js](https://img.shields.io/badge/Vue.js-3.x-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)

---

## 📖 Contexte du projet

**Brand Vue Ecommerce Website** est un projet de **site e‑commerce front-end** développé avec **Vue.js 3**.  
L’objectif est de créer une interface utilisateur interactive et responsive permettant de :

- Naviguer dans un catalogue de produits
- Ajouter des articles au panier
- Simuler un checkout
- Gérer le compte utilisateur (inscription, connexion)

Le projet peut être connecté à n’importe quelle API backend pour gérer les données réelles (produits, commandes, utilisateurs).

---

## 🚀 Fonctionnalités front-end

- 🔍 Catalogue et recherche de produits
- 🛒 Panier dynamique (ajout / suppression / modification des quantités)
- 👤 Formulaires d’inscription et de connexion
- 💳 Page de checkout (front-end uniquement)
- 🖥️ Interface responsive pour mobile et tablette

### Optionnelles / futures améliorations
- ⭐ Composants pour les avis clients
- 💌 Notifications frontend simulées
- 📊 Statistiques simulées côté UI
- 🎨 Amélioration UX/UI

---

## 🛠️ Technologies utilisées

- **Framework :** Vue.js 3  
- **State Management :** Pinia ou Vuex  
- **Routing :** Vue Router  
- **Styling :** Tailwind CSS / SCSS  
- **Build tool :** Vite  

> ⚠️ Backend simulé ou API externe nécessaire pour les données réelles. Sinon, utiliser des **mock data** JSON.

---

## 🏗️ Structure du projet

```
src/
├── assets/        # Images et styles
├── components/    # Composants réutilisables (Navbar, ProductCard, Cart...)
├── views/         # Pages principales (Home, Product, Checkout, Profile)
├── router/        # Configuration des routes
├── store/         # Gestion de l'état global (Pinia/Vuex)
└── App.vue
```

---

## ⚡ Installation et démarrage

1. **Cloner le dépôt :**
```bash
git clone https://github.com/SadouMohamedAymen/brand-vue-ecommerce-website.git
cd brand-vue-ecommerce-website
```

2. **Installer les dépendances :**
```bash
npm install
```

3. **Démarrer le serveur de développement :**
```bash
npm run dev
```

4. **Accéder à l’application :**
```
http://localhost:5173
```

> 🔹 Les données peuvent être simulées via des fichiers JSON ou connectées à une API externe.

---

## 📝 Roadmap Front-End

| Sprint | Objectifs |
|--------|-----------|
| 1 | Initialisation du projet, structure, router, state management |
| 2 | Catalogue de produits et pages produit |
| 3 | Panier et gestion des quantités |
| 4 | Formulaires utilisateur et page checkout |
| 5 | Composants optionnels et amélioration UX/UI |
| 6 | Responsive design et déploiement front-end |

---

## 🔗 Liens utiles

- [Vue.js](https://vuejs.org/)
- [Vue Router](https://router.vuejs.org/)
- [Pinia](https://pinia.vuejs.org/)
- [Tailwind CSS](https://tailwindcss.com/)

---

## 📜 License

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus d’informations.
