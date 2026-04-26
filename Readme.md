# 🏥 CarePulse - Système de Gestion pour Centres de Rééducation

**CarePulse** est une solution logicielle professionnelle "Local-First" conçue spécifiquement pour les cabinets de kinésithérapie, d'orthophonie, de psychomotricité et tous les centres de rééducation fonctionnant par forfaits de séances.

Développé par **Sastouka Digital**, cet outil permet de centraliser le flux de travail médical, administratif et financier dans une interface ultra-moderne et fluide.

![Aperçu CarePulse](img4.png)

## 🌟 Points Forts

- **Gestion par Séances** : Système optimisé pour le suivi des forfaits et le groupement de séances sur une seule facture.
- **Souveraineté des Données** : Architecture 100% locale utilisant SQLite. Aucune donnée médicale ne quitte l'appareil physique du praticien (Zéro Cloud).
- **Rappels WhatsApp** : Réduction de l'absentéisme grâce à l'envoi de messages de rappel pré-remplis directement depuis l'agenda.
- **Portefeuille d'Avances** : Gestion intelligente des paiements anticipés avec déduction automatique lors de la facturation finale.
- **Design Premium** : Interface basée sur le Glassmorphisme pour un confort visuel optimal sur Windows et Android.

## 🛠️ Modules Principaux

### 📅 Agenda Connecté
- Planification dynamique avec créneaux horaires configurables (15, 30, 45 min).
- Statut des rendez-vous en temps réel et transfert direct vers la facturation.

### 👥 Annuaire Patients
- Fiches complètes avec antécédents médicaux, notes et ID unique modifiable.
- Système de cache pour une recherche instantanée par nom, ID ou téléphone.

### 📄 Facturation & PDF
- Génération de factures professionnelles avec calcul automatique de la TVA.
- Numérotation chronologique automatisée par année fiscale.
- Support du papier à en-tête personnalisé (Image A4) pour l'export PDF.

### 📈 Statistiques & KPI
- Analyse du chiffre d'affaires par jour, mois ou année avec graphiques interactifs.
- Répartition des revenus par type de prestation.

## 🔒 Sécurité et Conformité

- **Conformité CNDP/RGPD** : Privacy by Design garantissant le respect de la Loi 09-08 au Maroc.
- **Sauvegardes ZIP** : Système d'export/import complet pour sécuriser les données sur support externe.
- **Authentification** : Accès protégé par identifiant et mot de passe personnalisable.

## 💻 Stack Technique

- **Framework** : Flutter (Multi-plateforme Windows / Android).
- **Base de données** : SQLite / sqflite.
- **Gestion d'état** : Provider.
- **Sécurité** : Chiffrement SHA-256 pour le système de licence.

## 🚀 Installation (Développeurs)

1. Clonez le dépôt :
   ```bash
   git clone [https://github.com/SastoukaDigital/CarePulse.git](https://github.com/SastoukaDigital/CarePulse.git)