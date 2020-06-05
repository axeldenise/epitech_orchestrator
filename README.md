# Epitech Orchestrator

## Description

L'objectif de ce projet était d'apprendre à déployer plusieurs services sur un cluster en utilisant Kubernetes et Traefik en tant que reverse proxy et load balancer.

## Services

* Poll: Il s'agit d'une application web en flask permettant à un utilisateur de voter
* Worker: C'est une application Java qui récupère les votes stockés dans la file d'attente Redis, puis les insère dans la base de données PostgreSQL
* Result: Cette application web en NodeJS permet de récupèrer les votes dans la base de données et d'afficher les résultats

## Schéma

![schema](./assets/schema.png)