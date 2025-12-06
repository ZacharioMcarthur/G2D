
#  **G2D**

## Interactions interactions académiques

**Développement Web – Laravel**
G2D 2025-2026

---

##  Nom du Projet

**Application Web Interacadémique**

Cette application permet aux écoles, collèges et universités de publiés différents évenements académiques comme les examens ainsi que les journées portes ouvertes, les formations académmiques, les offres de bourses, les journées de sensibilisation, les panels etc. Elle facilite également aux élèves l'accès aux épreuves d'établissemnt sur l'étendu du territoire national. 

---

##  **Membres de l'équipe **
* **SACRAMENTO Franklin**
* **NASCIMENTO Zachario**
* **CAKPO Frégis**
* **HAZOUME Maeva**



---

##  **Fonctionnalités Principales**


* Interface utilisateur responsive (Web)
* * Gestion CRUD des établissements (pour les moderateurs)
* Connexion avec une FedApi / base de données (si applicable)
* Double authetification google

---

## **Technologies Utilisées**

* Laravel 5.23.1
* VS Code

---

##  **Lancement du Projet**

```bash
composer create-project --prefer-dist laravel/laravel G2D
git init
git add .
git commit -m "Initial commit du projet G2D/Premier commit du projet G2D"
git remote add origin https://github.com/ZacharioMcarthur/G2D.git
git remote -v
git push -u origin main --force
git branch -M main
git branch
git push -u origin main
php artisan storage:link
git lfs install (stockage de medias lourd sur github)
 git lfs track "*.mp4"
>> git lfs track "*.mov"
>> git lfs track "*.png"
>> git lfs track "*.jpg"
>> git lfs track "*.mkv"
>> git lfs track "*.avi"
>> git lfs track "*.pdf"
git add .gitattributes
git lfs track "*.extension"
composer require feedapi/feedapi
composer require pragmarx/google2fa-laravel
php artisan vendor:publish --provider="PragmaRX\Google2FALaravel\ServiceProvider"
php artisan make:migration add_google2fa_secret_to_users_table --table=users
composer require simplesoftwareio/simple-qrcode
composer require guzzlehttp/guzzle
composer require fedapay/fedapay-php
vendor/package 
```

