# Wedding Collection ERP - Cahiers des Charges

Ce dépôt contient les 22 cahiers des charges séquentiels pour le développement de l'ERP Wedding Collection, un système de gestion pour événements de mariage.

## Structure du Projet

- `/specifications` : Contient les cahiers des charges numérotés
- `/assets` : Resources supplémentaires (images, diagrammes, etc.)

## Architecture Globale

L'ERP Wedding Collection est basé sur :
- Architecture monorepo multi-applications (backoffice, clients, presta, site)
- Next.js 14 avec architecture app/
- Supabase pour backend, authentication et stockage
- TailwindCSS + ShadCN UI + Lucide Icons
- TypeScript strict

## Comment Ajouter un Cahier des Charges

Chaque cahier des charges doit être numéroté et placé dans le dossier `/specifications`, par exemple :
- `01-initialisation-projet.md`
- `02-structure-base-de-donnees.md`
- etc.

## Conventions

Les cahiers des charges suivent les conventions techniques du projet :
- Schémas Supabase : bo, clients, presta, public, shared
- Conventions de nommage : snake_case pour les tables, kebab-case pour les dossiers
- Structure claire des spécifications