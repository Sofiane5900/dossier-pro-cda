# 🕋 Wasiyah – Application sécurisée de gestion testamentaire

**Wasiyah** est une application web de gestion de testament islamique, conçue pour garantir la conformité aux principes successoraux tout en assurant une confidentialité maximale grâce au chiffrement de bout en bout (E2EE).

## 🧩 Fonctions principales

- Création de compte avec vérification email (token JWT)
- Stockage chiffré localement (E2EE) avec phrase mnémonique (BIP39)
- Hachage sécurisé des mots de passe (Argon2)
- Désignation de wakils (mandataires) et gestion des actifs
- Déclenchement post-mortem avec audit cryptographiquement signé

## 🛠️ Stack & sécurité

- Backend : NestJS, Fastify, PostgreSQL, TypeORM
- Sécurité : JWT, Argon2, 2FA, cookies HttpOnly, Zéro connaissance
- Tests : Vitest (unitaires/intégration), Playwright (E2E en CLI)

## 🎯 Intérêt métier

Ce projet m’a permis d’approfondir l’implémentation de mécanismes avancés de sécurité, la modélisation de règles métiers complexes (droit successoral islamique) et la conception d’une architecture modulaire sécurisée.

---

**Remarque** : Ce projet respecte les bonnes pratiques de développement sécurisé. Aucune donnée réelle n’a été utilisée.
