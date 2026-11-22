# Audit de sécurité web : portail Serval Habitat

Rapport d'audit de sécurité (pentest web) réalisé dans le cadre du cours de pentest web du Master Cybersécurité à OTERIA. La cible est une application pédagogique fictive, hébergée dans un environnement de laboratoire prévu à cet effet.

## Contenu

**[⬇️ Télécharger le PDF](https://github.com/malicexyz/web-audit01/raw/main/Rapport_Serval_Habitat_Ilias_public.pdf)**

**[📄 Consulter le rapport (PDF, 53 pages)](Rapport_Serval_Habitat_Ilias_public.pdf)**

## Contexte

Serval Habitat est un bailleur social fictif qui met à disposition de ses locataires un portail de gestion de leur logement (documents, quittances, mouvements, messagerie, assistant). L'audit couvre l'ensemble des services exposés par le portail.

## Méthode

- Test d'intrusion en boîte noire, puis en boîte grise
- Référentiel OWASP
- Scoring CVSS v4.0 et classification CWE

## Structure du rapport

1. Introduction : contexte, périmètre, méthode
2. Vulnérabilités observées : 22 fiches (composant, point d'entrée, vecteur CVSS, CWE, preuves, impact, recommandations)
3. Points positifs observés : mécanismes de défense correctement implémentés, avec lecture de la couverture OWASP

## Anonymisation

Les noms de famille, l'adresse IP de la cible, les données personnelles visibles dans les captures (noms, adresses, emails), ainsi que les cookies de session, mots de passe et jetons ont été masqués.

## Cadre légal et éthique

Tous les tests ont été menés sur une cible autorisée, dans un cadre pédagogique. Ce document est publié à des fins éducatives. N'utilisez jamais ces techniques sur un système sans autorisation écrite de son propriétaire.

## Auteur

Ilias H., étudiant en Master Cybersécurité
