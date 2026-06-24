# Runbook – Structured JSON Assistant

## Informations générales

* **Nom :** Structured JSON Assistant
* **ID :** Prompt Template-ZC9Zu
* **Owner :** Marouane
* **Version :** 1.1.0
* **Date de création :** 2026-06-10

## Gestion des incidents

Un incident est déclaré lorsque l'agent :

* Ne répond plus.
* Retourne un JSON invalide.
* Ne respecte plus le format attendu.

### Actions

1. Identifier le problème.
2. Vérifier la dernière modification.
3. Décider d'un rollback ou de l'activation du kill switch.

## Kill Switch

### Objectif

Arrêter immédiatement l'agent en cas de problème critique.

### Procédure

1. Désactiver l'agent.
2. Bloquer les nouvelles requêtes.
3. Informer les utilisateurs.

## Rollback

### Objectif

Revenir à la dernière version stable.

### Procédure

1. Identifier la version stable précédente.
2. Restaurer cette version.
3. Vérifier le bon fonctionnement.

## Contact

* **Responsable :** Marouane
