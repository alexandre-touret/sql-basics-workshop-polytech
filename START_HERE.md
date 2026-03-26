# 🚀 WORKSHOP ZEVENT

Bienvenue dans le workshop SQL **ZEvent** ! 

Ce fichier vous guide pour débuter correctement. Lisez-le en entier avant de commencer.

## 👨‍🎓 Pour les Étudiants

### 1️⃣ Avant de commencer

Assurez-vous que vous avez :

- ✅ Un compte **GitHub** (gratuit)

### 2️⃣ Lire les Documents 

Lisez dans cet ordre :

| Document | Durée | Objectif |
|----------|-------|----------|
| **WORKSHOP.md** (entier) | 10 min | Comprendre l'énoncé |
| **README_WORKSHOP.md** | 3 min | Vue d'ensemble rapide |


### 3️⃣ Se connecter sur Portainer


Se connecter au portail https://pedagogie.sandbox.univ-tours.fr:9443/#!/home .

1. Cliquer sur la l'instance Docker courante
![stacks](./img/Screenshot%202025-04-12%20at%2021-31-26%20Portainer%2010.172.44.23%20-%20Docker%20CPU%201%20-%20docker1.pedagogie.sandbox.univ-tours.fr.png)

2. Cliquer sur "Stacks"
![stack](./img/Screenshot%202025-04-12%20at%2021-31-36%20Portainer%2010.172.44.23%20-%20Docker%20CPU%201%20-%20docker1.pedagogie.sandbox.univ-tours.fr.png)

3. Cliquer sur la stack courante
![stack](./img/Screenshot%202025-04-12%20at%2021-32-00%20Portainer%2010.172.44.23%20-%20Docker%20CPU%201%20-%20docker1.pedagogie.sandbox.univ-tours.fr.png)

4. Cliquer sur le port correspondant à PgAdmin ou VS Code
![ports](./img/Screenshot%202025-04-12%20at%2021-32-21%20Portainer%2010.172.44.23%20-%20Docker%20CPU%201%20-%20docker1.pedagogie.sandbox.univ-tours.fr.png)

## Connexion à PgAdmin

Connectez vous sur le port correspondant à PgAdmin.

L'utilisateur est : ``user-name@domaine-name.com``

Le mot de passe est : ``strong-password``.

Une fois connecté, vous aurez à vous connecter à la base.

Le mot de passe est ``polytech``.

## Exécuter des requêtes SQL

Pour exécuter des requêtes SQL, cliquez sur Tools>Query Tool.

### 3️⃣ Créer un Repository Git

Sur le poste de travail (dans Portainer ou un PC)

```bash
# 1. Créer un repo sur GitHub
# 2. Cloner localement et forker sur un repository github personnel
git clone https://github.com/alexandre-touret/sql-basics-workshop-polytech

cd sql-basics-workshop-polytech

#Configurer les infos utilisateur
git config --global user.name "Alexandre Touret"
git config --global user.email "alexandre-touret@users.noreply.github.com"

git status
# Lister les upstreams
git remote -vv

# Créer un repository dans github sans aucun fichier
#Ajouter un upstream
git remote add upstream https/github.com/%MON_USER_GITHUB%/sql-basics-workshop-polytech
#Ajouter un fichier
git add modelisation
# Valider une modification
git commit -a -m "Modelisation" 
# Uploader une modification
git push upstream main
```

### 5️⃣ Commencer le Workshop

Suivre la timeline du `workshop.md` 

## ✅ Checklist Rapide

### Étudiants

- [ ] PostgreSQL installé + testé
- [ ] Repo git créé
- [ ] `WORKSHOP.md` lu
- [ ] Prêt pour Phase 1

---

## 🚀 Workshop

Ouvrez `WORKSHOP.md` → Phase 1 → Ex1

