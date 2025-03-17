# ActiveDirectoryRecon

## Description
Ce script permet d'analyser passivement un environnement Active Directory à la recherche de vulnérabilités potentielles sans effectuer d'exploitation automatique.

Il inclut également un mode **Assumed Breach**, conçu pour simuler un attaquant ayant déjà un pied dans le réseau, afin d'identifier les failles accessibles après une compromission initiale.

## Fonctionnalités
- **Analyse passive** des services exposés sans exploitation active
- Détection des faiblesses sur plusieurs protocoles clés :
  - SMB (partages accessibles, permissions faibles, vulnérabilités connues)
  - MSSQL (authentification faible, bases accessibles, configurations exposées)
  - RPC (informations sensibles accessibles, comptes exposés)
  - FTP (accès anonymes, fichiers accessibles, fuites d’informations)
  - LDAP, WinRM, RDP et d'autres services critiques
- Vérification des mauvaises configurations et des risques liés aux comptes Active Directory
- Mode **Assumed Breach** permettant une analyse approfondie avec des accès légitimes limités

## Statut du Projet
Le script est actuellement **en cours de développement** et de nouveaux modules sont en train d’être ajoutés. Aucune exploitation automatique n’est implémentée pour l’instant.

## Auteur
Développé par **Elliot Belt** - GitBook : [https://felix-billieres.gitbook.io/v2](https://felix-billieres.gitbook.io/v2)

