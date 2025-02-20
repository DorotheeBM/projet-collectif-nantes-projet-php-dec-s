# Littoral Propre - Backoffice

## 🌍 Contexte
L'association **Littoral Propre** collecte des déchets sur les plages et souhaitait améliorer l'organisation de ses actions. Ce projet consiste à développer un **back-office** permettant de :

- Gérer les bénévoles
- Enregistrer les collectes
- Suivre les types et quantités de déchets récupérés
- Générer des statistiques sur l'impact des actions

Ce projet a été réalisé dans le cadre de l'Ada Tech School par l'équipe **DEC’S** :

- 🕊️ Eloi "La Mouette"
- 💎 Charlotte "La Perle"
- 🐋 Sarra "La Baleine"
- 🐢 Dorothée "La Tortue"

## 🚀 Fonctionnalités
### 🏗️ MVP - Version Initiale
✅ **Gestion des bénévoles** : Ajout, modification, suppression et attribution de rôles (admin/participant).  
✅ **Gestion des collectes** : Création et suivi des collectes de déchets avec les bénévoles associés.  
✅ **Gestion des déchets** : Enregistrement des types et quantités de déchets collectés.  
✅ **Authentification** : Connexion et déconnexion sécurisées.

### 📈 Améliorations prévues
🔜 Génération de **statistiques** sur l'impact des actions.  
🔜 Exportation des données en **CSV**.  
🔜 Messages de confirmation et d’erreur pour améliorer l'**expérience utilisateur**.  
🔜 Accessibilité et éco-conception renforcées (**balises sémantiques, pagination, messages alternatifs, etc.**).  

## 🛠️ Stack Technique
- **Backend** : PHP 8.3
- **Base de données** : MySQL (gestion via PHPMyAdmin)
- **Serveur local** : MAMP / WAMP / LAMP
- **Frontend** : HTML, TailwindCSS
- **Sécurité** : PHP PDO (requêtes SQL sécurisées), gestion des sessions

## ⚙️ Installation et utilisation
### 1️⃣ Installation du serveur local
- **Windows** : Installer WAMP

### 2️⃣ Configuration de la base de données
- Importer le fichier `gestion_collectes.sql` dans **PHPMyAdmin**
- Vérifier la présence des tables après l'importation

### 3️⃣ Lancement du projet
- Accéder au projet via : `http://localhost/association/index.php`

### 4️⃣ Connexion
- Se rendre sur `http://localhost/login.php`
- Créer un compte administrateur en insérant un utilisateur dans la BDD

## 📅 Organisation de l'équipe
- **Approche Agile** : Stand-up meetings, backlog mis à jour à chaque **pull request**
- **Travail collaboratif** : 70% en **MOB programming**, branches dédiées par fonctionnalité
- **Gestion des conflits Git** : Une difficulté mineure surmontée grâce aux bonnes pratiques

## 🏆 Points forts & défis
### ✅ Forces
✔️ Organisation Agile et rigoureuse  
✔️ Esprit d’équipe et partage des connaissances  
✔️ Bonne communication et bienveillance

### ⚠️ Difficultés
❌ Problèmes de **synchronisation Git** entraînant des conflits  
❌ Déploiement et mise en place de la **BDD**

## 🎯 Pour aller plus loin
- 📊 **Améliorer le tableau de bord** avec des statistiques visuelles
- 📁 **Exporter les données en CSV** pour analyse
- 🌱 **Éco-conception** : Réduction des effets visuels lourds, meilleure hiérarchisation du contenu
- 🌍 **Déploiement** du projet sur un serveur distant (ex: Vercel, Raspberry Pi)

---

## 👏 Remerciements
Un grand merci à **Ada Tech School** et aux encadrants, ainsi que ChatGPT et Claude pour leur accompagnement !

📌 _Projet accessible ici_ : [Littoral Propre Backoffice](http://littoral-propre-decx.great-site.net/login.php)

