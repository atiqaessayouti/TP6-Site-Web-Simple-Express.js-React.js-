# 📋 Gestion des utilisateurs - Application CRUD

## 🎯 Description

Application web simple de gestion des utilisateurs permettant d'effectuer les opérations **CRUD** :

* **C**réer un utilisateur
* **R**écupérer la liste des utilisateurs
* **U**pdater (modifier) un utilisateur
* **D**étruire (supprimer) un utilisateur

---

## 🛠️ Technologies utilisées

| Technologie | Version | Rôle                              |
| ----------- | ------- | --------------------------------- |
| React.js    | 18.x    | Front-end (interface utilisateur) |
| Express.js  | 4.x     | Back-end (API REST)               |
| Node.js     | 24.x    | Environnement d'exécution         |
| Axios       | 1.x     | Communication HTTP                |
| Cors        | 2.x     | Gestion des requêtes cross-origin |

---

## 📁 Structure du projet

```text
crud-users/
├── backend/
│   ├── server.js
│   ├── package.json
│   └── node_modules/
│
└── frontend/
    ├── src/
    │   ├── components/
    │   │   ├── UserList.js
    │   │   └── UserForm.js
    │   ├── services/
    │   │   └── api.js
    │   ├── App.js
    │   ├── App.css
    │   └── index.js
    │
    ├── package.json
    └── node_modules/
```

---

## 🚀 Installation et lancement

### Prérequis

* Node.js installé (version 14+)
* npm installé

### 1️⃣ Cloner le projet

```bash
git clone https://github.com/atiqaessayouti/TP6-Site-Web-Simple-Express.js-React.js-.git
cd TP6-Site-Web-Simple-Express.js-React.js-
```

### 2️⃣ Back-end (Express.js)

```bash
cd backend
npm install
npm start
```

Le serveur tourne sur :

```text
http://localhost:5000
```

### 3️⃣ Front-end (React.js)

Ouvrir un nouveau terminal :

```bash
cd frontend
npm install
npm start
```

L'application tourne sur :

```text
http://localhost:3000
```

---

## 📡 API Endpoints

| Méthode | Endpoint       | Description                     |
| ------- | -------------- | ------------------------------- |
| GET     | /api/users     | Récupérer tous les utilisateurs |
| GET     | /api/users/:id | Récupérer un utilisateur par ID |
| POST    | /api/users     | Créer un nouvel utilisateur     |
| PUT     | /api/users/:id | Modifier un utilisateur         |
| DELETE  | /api/users/:id | Supprimer un utilisateur        |

---

## 🎨 Fonctionnalités

✅ Afficher la liste des utilisateurs

✅ Ajouter un nouvel utilisateur (Nom + Email)

✅ Modifier un utilisateur existant

✅ Supprimer un utilisateur avec confirmation

✅ Interface moderne avec CSS Gradient

✅ Design Responsive

✅ Messages de confirmation

✅ Indicateur de chargement

---

## 🧪 Tester l'application

### Ajouter un utilisateur

1. Remplir le formulaire
2. Cliquer sur **Ajouter**

### Modifier un utilisateur

1. Cliquer sur **Modifier**
2. Modifier les informations
3. Cliquer sur **Mettre à jour**

### Supprimer un utilisateur

1. Cliquer sur **Supprimer**
2. Confirmer la suppression

---

## 🐛 Problèmes connus et solutions

| Problème               | Solution                              |
| ---------------------- | ------------------------------------- |
| Port 5000 déjà utilisé | Modifier le PORT dans server.js       |
| Port 3000 déjà utilisé | React propose automatiquement 3001    |
| Erreur CORS            | Vérifier `app.use(cors())`            |
| Page blanche           | Vider le cache navigateur (Ctrl + F5) |

---

## 📦 Dépendances

### Back-end

```json
{
  "express": "^4.18.2",
  "cors": "^2.8.5",
  "nodemon": "^3.0.1"
}
```

### Front-end

```json
{
  "react": "^18.2.0",
  "react-dom": "^18.2.0",
  "axios": "^1.6.0"
}
```

---

## 📝 Améliorations possibles

* Utiliser MongoDB ou MySQL
* Ajouter l'authentification
* Ajouter la pagination
* Recherche en temps réel
* Notifications Toast
* Validation des emails
* Déploiement sur Vercel ou Render

---

## 👤 Auteur

**Nom : Atiqa Essayouti**

**Filière : Master SDIA**

**Date : 31 Mai 2026**

