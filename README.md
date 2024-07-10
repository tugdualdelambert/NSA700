# NSA700

## Objectif
Le projet vise à automatiser et accélérer le cycle de développement et de déploiement en utilisant les principes DevOps.

## Technologies Utilisées
- **Ansible** : Pour l'installation des services et leurs dépendances.
- **Gitlab CI/CD** : Pour les pipelines de build, test et déploiement.
- **Laravel** : Pour le backend.
- **Angular** : Pour le frontend.
- **Nginx, php-fpm, MySQL** : Pour les services.

## Instructions d'Installation
1. Cloner le dépôt : `git clone https://github.com/tugdualdelambert/NSA700.git`
2. Suivre les instructions dans les fichiers `ansible/` pour configurer l'infrastructure.
3. Utiliser les pipelines Gitlab pour builder, tester et déployer les applications.

## Instructions d'Utilisation
1. Préparer l'infrastructure avec Ansible.
2. Utiliser Gitlab CI pour builder et tester les applications.
3. Déployer les applications avec Ansible via Gitlab CI.

## Bonus
- Tests end-to-end automatisés
- Stratégie de branchement Git Flow ou Github Flow
- Déploiement sur VPS
- Infrastructure en haute disponibilité
