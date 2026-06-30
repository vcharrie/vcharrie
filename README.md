# À propos de moi

## Présentation courte

Architecte logiciel avec plus de 18 ans d’expérience dans des environnements critiques (énergie, télécom, industrie), j’ai construit ma carrière autour de l’architecture applicative, de la coordination transverse, de la sécurité et de l’industrialisation.

En 2025, j’ai entrepris une mise à jour stratégique de mon socle technique pour intégrer pleinement les pratiques modernes du marché : Spring Boot 3, Docker, CI/CD GitHub Actions, Kubernetes (kind puis EKS), sécurité by design, supply chain security et DevSecOps.

Cette démarche s’est concrétisée par la création du projet **CoreService**, un projet complet construit release par release, démontrant :

- une architecture moderne et documentée,
- une CI/CD sécurisée (analyse statique, SBOM, Trivy, VEX),
- un déploiement Kubernetes local et cloud,
- une documentation professionnelle,
- une démarche Secure by Design transverse,
- une collaboration humain–IA pilotée et maîtrisée.

Aujourd’hui, je me positionne principalement sur un rôle de **Consultant SSI transverse**, en m’appuyant sur mon expérience d’architecte logiciel et mes compétences DevSecOps. Je reste également ouvert à des postes d’architecte orienté sécurité ou de coordinateur transverse, où la qualité, la sécurité et l’industrialisation sont au cœur des enjeux.

---

# Démarche Secure by Design transverse

Le projet CoreService applique une démarche **Secure by Design** couvrant l’ensemble de la chaîne de valeur logicielle :

**Stratégie → GRC → Architecture → Sécurité applicative → CI/CD → Sécurité d’exécution → Sécurité infrastructure**

Cette approche permet d’intégrer la sécurité dès la conception, de manière cohérente, industrialisée et transverse, en reliant les exigences stratégiques aux mécanismes techniques concrets.

## Articulation des domaines

### Stratégie & GRC
- Identification des risques et exigences de sécurité,
- Alignement avec les objectifs DSI,
- Définition des contraintes transverses.

### Architecture logicielle
- Conception d’une architecture moderne (Spring Boot 3, Docker, Kubernetes),
- Définition des patterns de sécurité applicative,
- Structuration des flux, zones de confiance et responsabilités.

### Sécurité applicative

La sécurité applicative est intégrée via un processus en trois niveaux :

1. **Fiches sécurité**  
   - Identification des exigences sécurité par composant,
   - Définition des contrôles applicatifs (authN, authZ, validation, journalisation, secrets, etc.).

2. **Spécifications techniques**  
   - Déclinaison des exigences sécurité en mécanismes concrets,
   - Patterns d’implémentation, contraintes d’architecture, contrôles à intégrer dans le code.

3. **Spécifications fonctionnelles**  
   - Référence aux exigences sécurité comme contraintes transverses,
   - Pas d’implémentation sécurité dans les specs fonctionnelles (centrées sur le métier).

### CI/CD & Supply Chain Security
- Pipeline GitHub Actions sécurisé,
- Analyse statique, SBOM, Trivy, VEX,
- Durcissement des images et gestion des dépendances.

### Sécurité d’exécution
- Déploiement Kubernetes local (kind) puis cloud (EKS),
- NetworkPolicy, RBAC, secrets, observabilité.

### Sécurité infrastructure
- Durcissement des environnements,
- Gestion des identités cloud,
- Séparation des rôles et privilèges.

---

# Collaboration humain–IA (contrôle croisé)

Le projet CoreService intègre une démarche innovante de collaboration humain–IA :

- **Copilot** est utilisé pour générer du code, des architectures, des documents et des propositions techniques.
- **Claude** est utilisé comme IA de contrôle : vérification sécurité, cohérence, conformité, qualité documentaire.
- **L’humain arbitre systématiquement** entre les deux, garantissant la maîtrise, la cohérence et la sécurité des livrables.

Ce principe de **contrôle croisé IA → IA**, supervisé par l’humain, reproduit un modèle de double validation utilisé dans les environnements critiques et renforce la robustesse de la démarche Secure by Design.

---

# Processus professionnel et itératif

Le projet est structuré en **releases successives**, chacune documentée par :

- une spécification d’architecture versionnée,
- une spécification technique,
- une fiche sécurité,
- une release note,
- un schéma d’architecture (logique, applicative, déploiement).

Ce processus reproduit les pratiques d’une DSI moderne et démontre une capacité à industrialiser la sécurité dans les projets.

---

# Publication contrôlée

Le projet **n’est pas encore publié intégralement**.

Pour des raisons de confidentialité et de protection des artefacts :

- les fiches sécurité,
- les spécifications techniques,
- les schémas complets,
- les release notes détaillées,

ne sont pas rendus publics.

Le dépôt public présente uniquement :

- la démarche,
- les objectifs,
- les principes Secure by Design,
- un schéma d’architecture non sensible,
- la structure générale du projet.

Les artefacts internes sont présentés uniquement en entretien.

---

# Documents détaillés

- Présentation professionnelle complète  
  → `presentation.md`

- CV intermédiaire (détaillé)  
  → `cv/CV_intermediaire.md`

- CV court  
  → `cv/CV_court.md`

- Versions PDF  
  → `cv/CV_intermediaire.pdf`

---

# Lien vers le projet

→ https://github.com/vcharrie/coreservice