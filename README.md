# 🏡 SymfonyApp - Application de Location de Villas et Appartements

Bienvenue sur **SymfonyApp**, une plateforme web moderne de mise en location de biens immobiliers (villas, chambres, appartements). Ce projet a été conçu avec le framework **Symfony** et déployé dans un environnement **Dockerisé** prêt pour la production.

---

## 🚀 Fonctionnalités principales

- ✅ Création et gestion d'annonces immobilières
- ✅ Système d’inscription et de connexion des utilisateurs
- ✅ Réservation en ligne
- ✅ Gestion des commentaires et des réactions
- ✅ Interface responsive et intuitive
- ✅ Déploiement Docker multi-conteneurs (PHP-FPM, NGINX, MySQL)
- ✅ Prêt pour la CI/CD avec GitHub Actions

---

## 🛠️ Stack technique

| Technologie | Description |
|-------------|-------------|
| 🧱 Symfony 5/6 | Framework backend PHP moderne |
| 🐳 Docker & Docker Compose | Conteneurisation de l’application |
| 🐘 MySQL 8 | Base de données relationnelle |
| 🌐 NGINX | Serveur HTTP |
| ✍️ Composer | Gestionnaire de dépendances PHP |
| 🐙 GitHub Actions | Déploiement continu (prévu) |

---

## 📦 Installation rapide (en local)

1. Clone ce dépôt :

```bash
git clone git@github.com:Tovokely2424/symfony_project1.git
cd symfony_project1
Lance les conteneurs :

bash
Copier
Modifier
docker-compose up -d --build
Accède à l'application :

http://localhost:8080

⚠️ Assure-toi que le port 8080 est libre sur ta machine.

📁 Structure du projet
bash
Copier
Modifier
.
├── app/                   # Code Symfony
├── docker/                # Fichiers de configuration Docker
│   ├── nginx/
│   └── php/
├── .env                  # Variables d’environnement
├── docker-compose.yml    # Orchestration des conteneurs
└── README.md
💡 Prochaines évolutions
📤 Mise en place du pipeline CI/CD GitHub Actions

📈 Ajout du monitoring et de la sauvegarde automatique

📬 Script d'alerte par e-mail en cas de crash ou surcharge

👨‍💻 Auteur
Pierre RASOLONJATOVO
DevOps & PHP/Symfony enthusiast 🇲🇬 | Passionné par l'automatisation, l'infra et le cloud
📫 tovo.aps.p2@gmail.com
