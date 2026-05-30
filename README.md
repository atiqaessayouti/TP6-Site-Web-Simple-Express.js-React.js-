# 📋 Gestion des utilisateurs - Application CRUD

## 🎯 Description
Application web simple de gestion des utilisateurs permettant d'effectuer les opérations **CRUD** :
- **C**réer un utilisateur
- **R**écupérer la liste des utilisateurs
- **U**pdater (modifier) un utilisateur
- **D**étruire (supprimer) un utilisateur

## 🛠️ Technologies utilisées
| Technologie | Version | Rôle |
|-------------|---------|------|
| React.js | 18.x | Front-end (interface utilisateur) |
| Express.js | 4.x | Back-end (API REST) |
| Node.js | 24.x | Environnement d'exécution |
| Axios | 1.x | Communication HTTP |
| Cors | 2.x | Gestion des requêtes cross-origin |

## 📁 Structure du projet
crud-users/
├── backend/
│ ├── server.js # Serveur Express avec API CRUD
│ ├── package.json # Dépendances back-end
│ └── node_modules/
└── frontend/
├── src/
│ ├── components/
│ │ ├── UserList.js # Affiche la liste des utilisateurs
│ │ └── UserForm.js # Formulaire d'ajout/modification
│ ├── services/
│ │ └── api.js # Appels API vers le back-end
│ ├── App.js # Composant principal
│ ├── App.css # Styles CSS
│ └── index.js
├── package.json
└── node_modules/

text

## 🚀 Installation et lancement

### Prérequis
- Node.js installé (version 14+)
- npm installé

### 1️⃣ Cloner le projet
```bash
git clone https://github.com/atiqaessayouti/TP6-Site-Web-Simple-Express.js-React.js-.git
cd TP6-Site-Web-Simple-Express.js-React.js-
2️⃣ Back-end (Express.js)
bash
cd backend
npm install
npm start
Le serveur tourne sur : http://localhost:5000

3️⃣ Front-end (React.js)
Ouvrir un nouveau terminal :

bash
cd frontend
npm install
npm start
L'application tourne sur : http://localhost:3000

📡 API Endpoints
Méthode	Endpoint	Description
GET	/api/users	Récupérer tous les utilisateurs
GET	/api/users/:id	Récupérer un utilisateur par ID
POST	/api/users	Créer un nouvel utilisateur
PUT	/api/users/:id	Modifier un utilisateur
DELETE	/api/users/:id	Supprimer un utilisateur
🎨 Fonctionnalités
✅ Afficher la liste des utilisateurs

✅ Ajouter un nouvel utilisateur (Nom + Email)

✅ Modifier un utilisateur existant

✅ Supprimer un utilisateur avec confirmation

✅ Interface moderne avec CSS gradient

✅ Design responsive (adapté mobile)

✅ Messages de confirmation (alertes)

✅ Indicateur de chargement

🧪 Tester l'application
Ajouter : Remplir le formulaire → cliquer "Ajouter"

Modifier : Cliquer "Modifier" → modifier les champs → "Mettre à jour"

Supprimer : Cliquer "Supprimer" → confirmer

🐛 Problèmes connus et solutions
Problème	Solution
Port 5000 déjà utilisé	Modifier le PORT dans server.js
Port 3000 déjà utilisé	React propose automatiquement 3001
CORS error	Vérifier que app.use(cors()) est présent
Page blanche	Vider le cache navigateur (Ctrl+F5)
📦 Dépendances
Back-end
json
{
  "express": "^4.18.2",
  "cors": "^2.8.5",
  "nodemon": "^3.0.1"
}
Front-end
json
{
  "react": "^18.2.0",
  "react-dom": "^18.2.0",
  "axios": "^1.6.0"
}
📝 Améliorations possibles
Utiliser une vraie base de données (MongoDB, MySQL)

Ajouter l'authentification (login/mot de passe)

Pagination pour la liste

Recherche en temps réel

Notifications toast (react-toastify)

Validation des emails

Déploiement sur Vercel / Heroku

👤 Auteur
Nom : [Votre Nom]

Encadrant : [Nom du professeur]

Date : 31 mai 2026

📄 Licence
Projet réalisé dans le cadre d'un TP de développement web.

🙏 Remerciements
Merci à l'équipe pédagogique pour l'accompagnement dans la réalisation de ce projet.

✅ Application fonctionnelle et prête à être étendue !

text

---

## Comment créer le fichier README.md

### Méthode 1 – Avec VS Code
```bash
cd C:\Users\Octinz\crud-users
code README.md
Puis copiez-collez le code ci-dessus et sauvegardez.

Méthode 2 – Avec le Bloc-notes
bash
cd C:\Users\Octinz\crud-users
notepad README.md
Copiez-collez le code, sauvegardez (Ctrl+S), fermez.

Méthode 3 – Avec PowerShell (commande directe)
bash
cd C:\Users\Octinz\crud-users
@"
[collez tout le code README ici]
"@ | Out-File -FilePath README.md -Encoding UTF8
📁 Structure finale avec README
text
C:\Users\Octinz\crud-users\
├── README.md          ← Fichier à créer
├── backend\
│   ├── server.js
│   └── package.json
└── frontend\
    ├── src\
    │   ├── components\
    │   ├── services\
    │   ├── App.js
    │   └── App.css
    └── package.json
