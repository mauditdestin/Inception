# 🏗️ Inception

**Inception** est un projet axé sur la virtualisation et l’orchestration de services en utilisant **Docker** et **Docker Compose**.  
Il a pour but de créer une infrastructure fonctionnelle composée de plusieurs conteneurs interconnectés, chacun représentant un service spécifique.

---

## 🎯 Objectifs

- Comprendre les concepts de base de la conteneurisation avec Docker  
- Mettre en place une infrastructure modulaire avec plusieurs services (ex : NGINX, WordPress, MariaDB)  
- Créer et gérer un réseau Docker dédié pour permettre la communication entre les conteneurs  
- Apprendre à automatiser le déploiement avec `docker-compose`  

---

## 🛠️ Services déployés

- **NGINX** : serveur web sécurisé avec TLS  
- **WordPress** : CMS auto-hébergé  
- **MariaDB** : base de données relationnelle  
- **Docker Network** : réseau isolé permettant la communication entre les services  

*(Les services exacts peuvent varier selon ton implémentation du projet.)*

---

## ⚙️ Compilation et lancement

Assure-toi d’avoir **Docker** et **Docker Compose** installés.

Pour construire et lancer l’infrastructure :

```bash
make
```

---

## 📂 Structure du projet

```
.
├── Makefile
├── srcs/
│   ├── docker-compose.yml
│   ├── requirements/
│   │   ├── mariadb/
│   │   ├── nginx/
│   │   └── wordpress/
└── README.md
```

---

## 📌 Remarques
Ce projet fait partie du cursus de l’École 42.
Il vise à fournir une compréhension pratique de la virtualisation et de la gestion d’infrastructure avec Docker.

