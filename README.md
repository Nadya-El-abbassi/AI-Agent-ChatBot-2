

# Chatbot avec Spring Boot et OpenAI

## Description

Ce projet consiste en un chatbot Telegram développé avec **Spring Boot**. Le bot utilise l’**API OpenAI** pour générer des réponses aux questions des utilisateurs en tenant compte du contexte fourni.

Avant d’envoyer la réponse générée, le bot affiche une action de saisie (`typing`) pour simuler une conversation plus naturelle.

## Fonctionnalités

* Envoi et réception de messages via la **Telegram Bot API**.
* Génération de réponses dynamiques grâce à l’**OpenAI Chat API**.
* Gestion des erreurs : si l’API OpenAI renvoie une erreur (par exemple, quota épuisé), le bot répond automatiquement par : *"JE NE SAIS PAS"*.

## Prérequis

* **Java 17** ou supérieur
* **Maven 3.8+**
* Compte Telegram et **Token** du bot
* Compte OpenAI et **clé API**

---

