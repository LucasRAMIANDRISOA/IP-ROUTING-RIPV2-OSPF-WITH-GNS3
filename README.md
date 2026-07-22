# Mise en place d'un système de confinement réseau contre la propagation des virus

Ce projet présente la conception et le déploiement d'une solution de sécurisation d'un réseau local permettant de détecter, limiter et contenir la propagation des virus informatiques grâce à la segmentation réseau et au contrôle des communications.

## Présentation
![Topologie du réseau](topology.png)

Ce projet a été réalisé dans le cadre de mon stage en **Administration Systèmes et Réseaux** à la **CENI Madagascar**.

L'objectif est de renforcer la sécurité du réseau local en mettant en œuvre des mécanismes de confinement afin d'isoler les postes potentiellement infectés et de limiter la propagation des menaces vers les autres équipements du réseau.

## Objectifs

- Concevoir une infrastructure réseau sécurisée.
- Segmenter le réseau à l'aide de VLAN.
- Contrôler les communications entre les différents segments.
- Isoler les postes compromis.
- Renforcer la sécurité du réseau local.
- Garantir la continuité des services.

---

## Technologies utilisées

- GNS3
- pfSense
- VMware Workstation
- Windows Server
- Active Directory (AD DS)
- Cisco IOS
- VLAN
- ACL (Listes de contrôle d'accès)
- DHCP
- DNS
- NAT
- Pare-feu (Firewall)

---

## Fonctionnalités

- Segmentation du réseau par VLAN.
- Routage sécurisé entre les réseaux.
- Filtrage des communications à l'aide d'ACL.
- Gestion centralisée des utilisateurs avec Active Directory.
- Distribution automatique des adresses IP.
- Résolution de noms via DNS.
- Isolation des postes suspects.
- Validation du fonctionnement par des tests de connectivité.

---

## Architecture

L'infrastructure est composée de plusieurs VLAN représentant les différents services de l'entreprise.

Le pare-feu **pfSense** assure :
- le routage entre les VLAN ;
- le filtrage des communications ;
- la sécurisation des échanges ;
- le confinement des postes infectés.

---

## Compétences développées

- Administration Systèmes Windows Server
- Administration Réseaux
- Configuration de pfSense
- Active Directory
- VLAN
- ACL
- Routage IP
- Sécurité des réseaux
- Virtualisation avec VMware
- Simulation réseau avec GNS3
- Dépannage et résolution d'incidents

---

## Auteur

**Lucas Ramiandriasoa**

Étudiant en Informatique  
Parcours Administration Systèmes et Réseaux  
École Nationale d'Informatique (ENI) – Madagascar

---

> **Remarque :** Ce dépôt présente uniquement la partie technique du projet. Les configurations, adresses IP et informations internes de la CENI Madagascar ont été anonymisées afin de préserver la confidentialité de l'infrastructure.

