# 🛡️ Mise en place d’un VPN Itinérant 🛡️

Ce projet a pour objectif de permettre à un utilisateur distant d'accéder à ses fichiers depuis chez lui en utilisant un VPN. Pour cela, un serveur VPN Wireguard est configuré sur Debian 11, assurant une connexion sécurisée et fiable pour les utilisateurs à distance.

## 📑 Table des matières 📑

- [🔍 Aperçu du Projet 🔍](#-aperçu-du-projet)
- [🌟 Fonctionnalités Principales 🌟](#-fonctionnalités-principales)
- [🛠️ Technologies Utilisées 🛠️](#-technologies-utilisées)
- [⚙️ Configuration ⚙️](#-configuration)
- [🔧 Problèmes Rencontrés et Solutions 🔧](#-problèmes-rencontrés-et-solutions)
- [🙏 Remerciements 🙏](#-remerciements)

## 🔍 Aperçu du Projet 🔍

Le projet s'articule autour de plusieurs étapes pour la mise en place d'un VPN itinérant :

1. **Installation et configuration du serveur Wireguard** : Mise en place d'un serveur VPN sur Debian 11 avec génération de clés et configuration réseau.
2. **Configuration du client Wireguard** : Paramétrage du client pour se connecter au serveur VPN avec les paramètres de sécurité adéquats.
3. **Tests de performance** : Vérification de la connexion VPN et comparaison des performances avec d'autres solutions VPN, comme OpenVPN.

## 🌟 Fonctionnalités Principales 🌟

- **Connexion sécurisée** : Accès sécurisé aux fichiers d'entreprise depuis n'importe quel emplacement.
- **Performances optimisées** : Utilisation de Wireguard pour des performances accrues par rapport aux autres solutions VPN.
- **Accès distant simplifié** : Connexion facile et rapide pour les utilisateurs avec un minimum de configuration.

## 🛠️ Technologies Utilisées 🛠️

- **Debian 11** : Système d'exploitation pour héberger le serveur Wireguard.
- **Wireguard** : Solution VPN moderne, rapide et sécurisée.
- **Pfsense** : Pare-feu utilisé pour gérer les règles NAT et assurer la sécurité du VPN.

## ⚙️ Configuration ⚙️

- **Serveur Wireguard** : Installation et configuration du serveur VPN avec génération de clés et paramétrage des interfaces.
- **Client Wireguard** : Configuration du client avec les clés de sécurité et les adresses IP pour un accès sécurisé au réseau.
- **Pfsense** : Configuration des règles NAT pour rediriger le trafic du VPN et assurer la continuité de la connexion.

## 🔧 Problèmes Rencontrés et Solutions 🔧

Certains défis, comme la configuration des règles NAT et la gestion des permissions d'accès, ont été surmontés grâce à des ajustements dans les configurations réseau et les paramètres de sécurité.

## 🙏 Remerciements 🙏

Merci à mes enseignants et collègues du lycée Pergaud pour leur soutien et leurs conseils dans la réalisation de ce projet.
![Image](https://www.logo.wine/a/logo/WireGuard/WireGuard-Logo.wine.svg)
