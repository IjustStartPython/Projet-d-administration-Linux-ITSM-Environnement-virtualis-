# GLPI 10 sur Debian 11
 Projet d’administration Linux & ITSM – Environnement virtualisé

##  Présentation
Ce projet a pour objectif de déployer une solution **GLPI (Gestionnaire Libre de Parc Informatique)** sur une machine virtuelle **Debian 11**, dans le cadre d’une **entreprise fictive (Agence Rue25)**.

Le serveur permet :
- la gestion du parc informatique
- la centralisation des tickets de support
- la traçabilité des interventions IT

L’installation repose sur une pile **LAMP** complète et sécurisée.

---

##  Objectifs du projet
- Installer Debian 11 sur une machine virtuelle
- Configurer un réseau avec IP statique
- Déployer une pile LAMP (Apache, MariaDB, PHP)
- Installer et configurer GLPI 10
- Sécuriser la base de données
- Rendre l’installation reproductible et documentée

---

##  Environnement technique
- **Hyperviseur** : Oracle VirtualBox  
- **OS** : Debian 11.6  
- **Interface** : GNOME  
- **Ressources VM** :
  - 1 CPU
  - 2 Go RAM
  - 20 Go disque
- **Services** :
  - Apache2
  - MariaDB
  - PHP + modules requis
  - GLPI 10

---

##  Étapes principales
- Installation non graphique de Debian
- Accès root et mise à jour du système
- Installation et configuration SSH
- Configuration réseau statique (NetworkManager)
- Installation Apache / PHP / MariaDB
- Sécurisation de MariaDB
- Création de la base GLPI et utilisateur dédié
- Déploiement de GLPI
- Configuration d’un VirtualHost Apache
- Installation finale via l’interface web

---

##  Sécurité & bonnes pratiques
- Utilisateur SQL dédié à GLPI
- Encodage UTF8MB4
- Permissions Apache maîtrisées
- Logs dédiés
- IP statique pour serveur

---

##  Reproductibilité
Chaque étape est :
- expliquée
- illustrée
- testée

Le projet peut être reproduit sur n’importe quel environnement Debian compatible.

---

##  Documentation complète
 Documentation technique détaillée avec captures d’écran

---

##  Compétences démontrées
- Administration Linux (Debian)
- Virtualisation
- Réseau (IP statique, SSH)
- Pile LAMP
- GLPI / ITSM
- Sécurisation serveur
- Documentation technique professionnelle

---

##  Remarque
Les fichiers de machines virtuelles ne sont pas fournis.  
Le projet est volontairement basé sur une **reconstruction complète documentée**.

---

📌 *Projet réalisé dans un cadre pédagogique à visée professionnelle.*
Projet : Infrastructure IT – Agence Rue25 (fictive)
Auteur : IJustStartPython
Année : 2025
Usage : Portfolio professionnel
