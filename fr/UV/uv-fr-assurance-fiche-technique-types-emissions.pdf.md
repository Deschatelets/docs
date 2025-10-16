---
# Document Metadata
document_id: "uv-fr-assurance-fiche-technique-types-emissions-v1.0"
document_type: technical_product_guide
schema_version: "2.0"
version: 1.0
document_title: "Guide des Types d'Émission - Assurance UV"
full_product_name: "Technical Guide for Issue Types and Life Insurance Products (UV Assurance)"
total_pages: 8
last_updated: "2024"
effective_date: "2024-01-01"

# Insurer Information
insurer:
  name: "UV Assurance"
  id: "uv"
  legal_name: "L'Union-Vie, compagnie mutuelle d'assurance"
  parent_company: "UV Assurance"

# Product Information
product:
  name: "Gamme Complète d'Assurance Vie"
  id: "life-insurance-portfolio"
  owner: "UV Assurance"
  type: "life_insurance_portfolio"
  type_fr: "Portefeuille d'assurance vie"
  underwriting_type: "mixed_underwriting"
  underwriting_type_fr: "Souscription mixte"
  product_variants:
    - "L'Adaptable"
    - "Vie Entière Valeurs Élevées"
    - "Vie Entière Payable à 100 ans"
    - "Temporaire Supérieur+"
    - "L'AdapSanté"
    - "Juvénile 30/100"

# Classification
language: fr-CA
region: CA
target_audience:
  - insurance_advisors
  - agents
  - brokers
  - underwriters

# Coverage Limits
coverage:
  min_amount: 10000
  max_amount: 5000000
  currency: CAD
  age_range: [0, 80]
  age_groups:
    - "0-15"
    - "16-75"
    - "18-80"

# Tags for Searchability
tags:
  - guide-types-emission
  - assurance-vie
  - emission-simplifiee
  - tarification
  - uv-assurance
  - express
  - immediate
  - reguliere

# Machine-Readable Features
features:
  product_comparison: true
  issue_types: true
  eligibility_criteria: true
  age_amount_matrix: true
  coverage_options: true

# Disclaimer
disclaimer: "Ce guide technique est fourni à titre informatif seulement et est sujet à modifications sans préavis."

# Document Structure Map
sections:
  - id: vue_ensemble
    name: "Vue d'ensemble"
    type: overview
    line_start: 9
  - id: emission_simplifiee
    name: "Émission Simplifiée"
    type: issue_type
    line_start: 15
  - id: selection_tarification
    name: "Sélection avec Tarification"
    type: issue_type
    line_start: 70
  - id: metadonnees_indexation
    name: "Métadonnées pour indexation"
    type: reference
    line_start: 108

# Document Segments (Original PDF)
document_segments:
  - name: "Guide des Types d'Émission"
    pages: 0-8
    confidence: High

# Document Statistics
statistics:
  total_issue_types: 2
  total_products: 6
  total_age_groups: 3
  total_coverage_ranges: 6
  express_products: 6
  immediate_products: 6
  regular_products: 6
  issue_types:
    express: 1
    immediate: 1
    regular: 1
  coverage_amounts:
    min: 10000
    max: 5000000
  age_ranges:
    min: 0
    max: 80
---

## Vue d'ensemble

Ce document présente les différents types d'émission disponibles chez UV Assurance, organisés selon la complexité du processus d'approbation et les montants d'assurance.

---

## 1. Émission Simplifiée

### Caractéristiques générales
- **Taux:** Standards
- **Délai:** Rapide avec approbation immédiate
- **Exigences:** Aucun examen médical, aucun fluide, aucune tarification
- **Questionnaires:** Disponibles sur [uvassurance.ca/simplifie](https://uvassurance.ca/simplifie/)

### 1.1 Émission Express
**Montants:** 150 000 $ et moins

#### Produits pour enfants (9 questions d'admissibilité)

| Produit | Âge | Montant |
|---------|-----|---------|
| **L'Adaptable - Vie entière Valeurs Élevées** | 15 jours à 15 ans | 10 000 $ à 150 000 $ |
| **Juvénile 30/100** | 15 jours à 15 ans | 100 000 $ (vie) + 10 000 $ (maladies graves) |

#### Produits pour adultes (15 questions d'admissibilité)

##### Assurance vie temporaire
| Produit | Âge | Montant | Avenant Assurance dette |
|---------|-----|---------|-------------------------|
| T-10, T-15 | 18 à 65 ans | 25 000 $ à 150 000 $ | 2 ans (18 à 55 ans) |
| T-20 | 18 à 65 ans | 25 000 $ à 150 000 $ | 2 ans (18 à 55 ans) |
| T-25 | 18 à 60 ans | 10 000 $ à 150 000 $ | 2 ans (18 à 55 ans) |
| T-30 | 18 à 55 ans | 10 000 $ à 150 000 $ | 2 ans (18 à 55 ans) |

##### Assurance vie permanente
| Produit | Âge | Montant | Avenant Assurance dette |
|---------|-----|---------|-------------------------|
| **L'Adaptable** | 16 à 75 ans | 10 000 $ à 150 000 $ | 2 ans (18 à 55 ans) |
| **Vie entière Valeurs Élevées** | 18 à 55 ans | 10 000 $ à 150 000 $ | 2 ans (18 à 55 ans) |
| **Vie entière Payable à 100 ans** | 18 à 80 ans | 10 000 $ à 150 000 $ | Non disponible |

### 1.2 Émission Immédiate
**Montants:** 150 001 $ et plus

#### Produits pour adultes (25 questions d'admissibilité)

##### Assurance vie temporaire
| Produit | Âge | Montant | Avenant Assurance dette |
|---------|-----|---------|-------------------------|
| T-10, T-15, T-20, T-25, T-30 | 18 à 45 ans | 150 001 $ à 499 999 $ | 2 et 5 ans (18 à 55 ans) |
| T-10, T-15, T-20, T-25, T-30 | 46 à 55 ans | 150 001 $ à 350 000 $ | 2 et 5 ans (18 à 55 ans) |
| T-10, T-15, T-20 | 56 à 65 ans | 150 001 $ à 250 000 $ | Non disponible |
| T-25 | 56 à 60 ans | 150 001 $ à 250 000 $ | Non disponible |

### Protection combinée
Une protection combinée (assurance vie permanente + avenant vie temporaire) est possible si :
1. Le montant total ne dépasse pas les limites de l'Immédiate
2. Le montant de l'assurance vie permanente est de 150 000 $ maximum

---

## 2. Sélection avec Tarification

### Caractéristiques générales
- **Processus:** Sélection traditionnelle avec l'aide d'un tarificateur
- **Montants:** Excédant les limites de l'émission simplifiée

### 2.1 Produits pour enfants

| Produit | Âge | Montant |
|---------|-----|---------|
| **L'Adaptable** | 15 jours à 15 ans | 150 001 $ et plus |
| **Vie entière Valeurs Élevées** | 15 jours à 15 ans | 150 001 $ et plus |
| **L'AdapSanté Juvénile** | 30 jours à 15 ans | 25 000 $ et plus |

### 2.2 Produits pour adultes

#### Assurance vie temporaire
| Produit | Âge | Montant | Avenant Assurance dette |
|---------|-----|---------|-------------------------|
| T-10, T-15, T-20, T-25, T-30 | 18 à 45 ans | 500 000 $ et plus | 2 et 5 ans (18 à 55 ans) |
| T-10, T-15, T-20, T-25 | 46 à 55 ans | 350 001 $ et plus | 2 et 5 ans (18 à 55 ans) |
| T-10, T-15, T-20, T-25 | 56 à 60 ans | 250 001 $ et plus | Jusqu'à 65 ans (18 à 60 ans) |
| T-10, T-15, T-20 | 61 à 65 ans | 250 001 $ et plus | Non disponible |

#### Assurance vie permanente
| Produit | Âge | Montant | Avenant Assurance dette |
|---------|-----|---------|-------------------------|
| **L'Adaptable** | 16 à 75 ans | 150 001 $ et plus | 2 et 5 ans (18 à 55 ans) |
| **Vie entière Valeurs Élevées** | 18 à 55 ans | 150 001 $ et plus | 2 et 5 ans (18 à 55 ans) |
| **Vie entière Payable à 100 ans** | 18 à 80 ans | 150 001 $ et plus | Jusqu'à 65 ans (18 à 60 ans) |

#### Assurance maladies graves
| Produit | Âge | Montant |
|---------|-----|---------|
| **L'AdapSanté** | 16 à 65 ans | 10 000 $ et plus |

---

## Métadonnées pour indexation

**Mots-clés:** assurance vie, émission simplifiée, tarification, UV Assurance, produits enfants, produits adultes, assurance temporaire, assurance permanente, maladies graves

**Types de produits:** T-10, T-15, T-20, T-25, T-30, L'Adaptable, Vie entière Valeurs Élevées, Vie entière Payable à 100 ans, L'AdapSanté, Juvénile 30/100

**Plages d'âge:** 15 jours à 15 ans, 16 à 75 ans, 18 à 80 ans

**Montants:** 10 000 $ à 500 000 $ et plus