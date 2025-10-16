---
# Document Metadata
document_id: "emma-fr-sommaire-produit-v1.0"
document_type: product_summary
schema_version: "2.0"
version: 1.0
document_title: "Sommaire des Produits d'Assurance Vie Emma"
document_purpose: "Résumé des produits d'assurance vie Emma avec termes, couvertures et conditions"
last_updated: "2024-01-15"
effective_date: "2024-01-01"

# Insurer Information
insurer:
  name: "Humania Assurances Inc."
  id: "humania"
  legal_name: "Humania Assurances Inc."
  address: "1555 Rue Girouard O, Saint-Hyacinthe, QC J2S 7C8"
  amf_number: "2000737703"
  complaints_url: "https://www.humania.ca/formuler-plainte"
  
# Distributor Information
distributor:
  name: "Emma Services financiers Inc."
  id: "emma"
  legal_name: "Emma Services financiers Inc."
  address: "7900-300, Boul Pierre-Bertrand, Québec (QC) G2J 0C5"
  amf_number: "603236"
  specimen_url: "https://emma.ca/specimen-de-police"

# Product Family
product_family: 
  name: "Emma Life Insurance Products"
  name_fr: "Produits d'Assurance Vie Emma"
  id: "emma_life"
  
# Classification
language: fr-CA
region: QC
target_audience:
  - potential_clients
  - insurance_advisors
  - financial_planners
  - distributors

# Products Included
products_included:
  - id: "emma_t100"
    name: "Emma T100"
    name_fr: "Assurance vie temporaire 100 ans"
    type: "permanent_life"
    age_range: [18, 80]
    min_coverage: 1000
    max_coverage: 5000000
  - id: "emma_term"
    name: "Emma Term"
    name_fr: "Assurance vie temporaire 10-35 ans"
    type: "term_life"
    age_range: [18, 80]
    min_coverage: 50000
    max_coverage: 5000000
  - id: "dependent_life_rider"
    name: "Dependent Life Insurance Rider"
    name_fr: "Avenant assurance vie pour personne à charge"
    type: "rider"
    coverage_amounts: [15000, 20000, 25000]
  - id: "cancer_rider"
    name: "Cancer Insurance Rider"
    name_fr: "Avenant assurance cancer"
    type: "rider"
    age_range: [18, 70]
    min_coverage: 10000
    max_coverage: 75000
  - id: "disability_rider"
    name: "Total Disability Insurance Rider"
    name_fr: "Avenant assurance invalidité totale"
    type: "rider"
    age_range: [18, 60]
    min_monthly_benefit: 500
    max_monthly_benefit: 3000

# Regulatory Compliance
regulatory_compliance:
  - authority: "AMF"
    full_name: "Autorité des marchés financiers"
    url: "https://www.lautorite.qc.ca"
    phone: "1-877-525-0337"
  - act: "Quebec Insurance Act"
    jurisdiction: "QC"

# Tags for Searchability
tags:
  - assurance-vie
  - emma
  - humania
  - t100
  - temporaire
  - permanent
  - riders
  - product-summary
  - consumer-rights

# Coverage Summary
coverage_summary:
  currency: CAD
  main_products: 2
  riders: 3
  total_products: 5

# Document Structure Map
sections:
  - id: organization_info
    name: "Informations sur les Organisations"
    type: metadata
    line_start: 33
  - id: product_comparison
    name: "Tableau Comparatif des Produits Principaux"
    type: comparison
    line_start: 51
  - id: main_products
    name: "Produits Principaux"
    type: products
    line_start: 66
  - id: exclusions
    name: "Exclusions et Limitations Communes"
    type: exclusions
    line_start: 166
  - id: riders
    name: "Garanties Optionnelles (Avenants)"
    type: riders
    line_start: 214
  - id: glossary
    name: "Glossaire et Définitions"
    type: reference
    line_start: 351
  - id: rider_summary
    name: "Résumé des Garanties Optionnelles"
    type: summary
    line_start: 370
  - id: consumer_rights
    name: "Fiche de Renseignements - Droits du Consommateur"
    type: legal
    line_start: 380
  - id: resources
    name: "Ressources et Information"
    type: resources
    line_start: 438
  - id: legal_notes
    name: "Notes Juridiques"
    type: legal
    line_start: 457

# Document Statistics
statistics:
  total_main_products: 2
  total_riders: 3
  total_exclusions: 5
  total_dangerous_activities: 13
  total_glossary_terms: 11
  product_types:
    permanent_life: 1
    term_life: 1
    riders: 3
  age_ranges:
    min_age: 18
    max_age: 80
  coverage_limits:
    min_coverage: 1000
    max_coverage: 5000000
    currency: "CAD"
---

# Sommaire des Produits d'Assurance Vie Emma
## Humania Assurances Inc.

---

## Informations sur les Organisations

### Assureur

**Humania Assurances Inc.**
- **Adresse:** 1555 Rue Girouard O, Saint-Hyacinthe, QC J2S 7C8
- **Inscription AMF:** [Numéro 2000737703](https://lautorite.qc.ca/grand-public/registres/registre-assureurs-institutions-de-depots-et-societe-de-fiducie)
- **Plaintes:** <https://www.humania.ca/formuler-plainte>

### Distributeur

**Emma Services financiers Inc.**
- **Adresse:** 7900-300, Boul Pierre-Bertrand, Québec (QC) G2J 0C5
- **Inscription AMF:** [Numéro 603236](https://lautorite.qc.ca/grand-public/registres/registre-des-entreprises-et-des-individus-autorises-a-exercer)
- **Spécimen de police:** <https://emma.ca/specimen-de-police>

---

## Tableau Comparatif des Produits Principaux

<!-- MACHINE_READABLE_DATA: product_comparison_matrix -->
```json
{
  "table_id": "main_products_comparison",
  "table_type": "product_features",
  "currency": "CAD",
  "products": [
    {
      "product_id": "emma_t100",
      "product_name": "Emma T100",
      "product_name_fr": "Assurance vie temporaire 100 ans Emma",
      "type": "permanent_life",
      "type_fr": "Assurance vie permanente T100",
      "coverage_description": "Assurance vie permanente T100",
      "age_establishment": {
        "min": 18,
        "max": 80,
        "display": "18 à 80 ans"
      },
      "coverage_amount": {
        "min": 1000,
        "max": 5000000,
        "currency": "CAD",
        "min_display": "1 000 $",
        "max_display": "5 000 000 $"
      },
      "premium_duration": {
        "options": ["to_age_100", "to_age_65", "20_years"],
        "display": "Jusqu'à 100 ans, 65 ans ou 20 ans"
      },
      "renewable": false,
      "convertible": false,
      "eligibility": {
        "citizenship": ["canadian_citizen", "permanent_resident"],
        "display": "Résident permanent ou citoyen canadien"
      }
    },
    {
      "product_id": "emma_term",
      "product_name": "Emma Temporaire",
      "product_name_fr": "Emma Assurance vie temporaire",
      "type": "term_life",
      "type_fr": "Assurance vie temporaire",
      "coverage_description": "Assurance vie temporaire 10-35 ans renouvelable et transformable",
      "term_options": [10, 15, 20, 25, 30, 35],
      "age_establishment": {
        "min": 18,
        "max": 80,
        "display": "18 à 80 ans"
      },
      "coverage_amount": {
        "min": 50000,
        "max": 5000000,
        "currency": "CAD",
        "min_display": "50 000 $",
        "max_display": "5 000 000 $"
      },
      "premium_duration": {
        "type": "term_duration",
        "display": "Durée du terme initial"
      },
      "renewable": {
        "available": true,
        "frequency": "annual",
        "until_age": 80,
        "display": "Annuel jusqu'à 80 ans après terme initial"
      },
      "convertible": {
        "available": true,
        "until_age": 65,
        "min_amount": 1000,
        "display": "Disponible jusqu'à 65 ans (min. 1 000 $)"
      },
      "eligibility": {
        "citizenship": ["canadian_citizen", "permanent_resident"],
        "display": "Résident permanent ou citoyen canadien"
      }
    }
  ],
  "comparison_features": [
    "type_coverage",
    "age_establishment",
    "min_coverage",
    "max_coverage",
    "premium_duration",
    "renewable",
    "convertible",
    "eligibility"
  ]
}
```
<!-- END_MACHINE_READABLE_DATA -->

| Caractéristique | Emma T100 | Emma Temporaire |
|---|---|---|
| **Type de couverture** | Assurance vie permanente T100 | Assurance vie temporaire 10-35 ans renouvelable et transformable |
| **Âge d'établissement** | 18 à 80 ans | 18 à 80 ans |
| **Capital assuré minimum** | 1 000 $ | 50 000 $ |
| **Capital assuré maximum** | 5 000 000 $ | 5 000 000 $ |
| **Durée des primes fixes** | Jusqu'à 100 ans, 65 ans ou 20 ans | Durée du terme initial |
| **Renouvellement** | N/A | Annuel jusqu'à 80 ans après terme initial |
| **Transformation** | N/A | Disponible jusqu'à 65 ans (min. 1 000 $) |
| **Admissibilité** | Résident permanent ou citoyen canadien | Résident permanent ou citoyen canadien |

---

## Produits Principaux

### 1. Assurance Vie Temporaire 100 Ans Emma (T100)

#### Type de Couverture

Assurance vie permanente T100

#### Primes

Les primes sont fixes pour la durée du contrat et payables selon l'une des options suivantes:
- **Jusqu'à 100 ans** (paiement viager)
- **Jusqu'à 65 ans** (paiement limité à 65 ans)
- **Durant 20 ans** (paiement limité à 20 ans)

#### Critères d'Admissibilité

| Critère | Exigence |
|---|---|
| **Âge d'établissement** | 18 à 80 ans |
| **Statut de résidence** | Résident permanent ou citoyen canadien |

#### Indemnités Offertes

| Type | Montant |
|---|---|
| **Minimum** | 1 000 $ en assurance vie |
| **Maximum** | 5 000 000 $ en assurance vie |

#### Réclamation

**Délai pour soumettre l'avis:**
- Avis écrit requis dans les **30 jours** suivant la date du décès

**Documents requis:**
- À fournir dans les **90 jours** suivant la date du décès
- Pour plus de détails, consulter le spécimen de police

#### Droit de Résiliation

**Délai d'annulation sans pénalité:**
- **15 jours** après la date de réception du contrat, OU
- **60 jours** suivant la date d'émission de la police

**Titulaire autorisé:**
- Seul le titulaire peut demander l'annulation

**Après le délai:**
- Annulation possible en tout temps
- Des pénalités pourraient s'appliquer

**Modalités:**
- Contacter Humania Assurances Inc. ou Emma Services financiers Inc.
- Signer une lettre d'annulation

---

### 2. Assurance Vie Temporaire Emma (10-35 Ans)

#### Type de Couverture

Assurance vie temporaire renouvelable et transformable
- **Termes disponibles:** 10 ans à 35 ans

#### Renouvellement

- **Modalité:** Renouvellement annuel
- **Période:** Jusqu'à 80 ans à partir de la fin du terme initial

#### Primes

Les primes sont:
- Fixes et garanties pour la durée du terme du contrat
- Renouvelables annuellement à partir de la fin du terme initial

#### Critères d'Admissibilité

| Critère | Exigence |
|---|---|
| **Âge d'établissement** | 18 à 80 ans |
| **Statut de résidence** | Résident permanent ou citoyen canadien |

#### Indemnités Offertes

| Type | Montant |
|---|---|
| **Minimum** | 50 000 $ en assurance vie |
| **Maximum** | 5 000 000 $ en assurance vie |

#### Droit de Transformation

| Caractéristique | Détails |
|---|---|
| **Disponibilité** | Jusqu'à 65 ans |
| **Minimum** | 1 000 $ en assurance vie |

**Note:** Cette assurance est également offerte en garantie optionnelle.

---

## Exclusions et Limitations Communes

Les exclusions et limitations suivantes s'appliquent à tous les produits Emma (T100 et Temporaire):

### Suicide

- Le décès par suicide de l'assuré (qu'il soit sain d'esprit ou non) n'est **pas couvert** dans les **deux premières années** du contrat ou de sa remise en vigueur

### Fausse Déclaration

- Une fausse déclaration peut entraîner la **nullité du contrat**

### Acte Criminel

- Tout décès résultant d'une **participation à un acte criminel** ne sera **pas couvert**

### Limite de Capital Assuré

- Si, par erreur, la somme des montants d'assurance choisis dépasse **5 000 000 $**:
  - Humania Assurance paie un capital assuré maximal de 5 000 000 $
  - Annule les contrats en excédent de ce montant
  - Rembourse la portion des paiements effectués en trop

### Exclusion pour Activités et Sports Dangereux

Aucune prestation ne sera payable si la réclamation découle **directement ou indirectement** de la participation de l'assuré à l'une des activités ou sports suivants:

| Activités Exclues |
|---|
| Alpinisme |
| Escalade de glace |
| Plongée sous-marine (autre que dans un centre de vacances) |
| Parapente |
| Paravoile |
| Deltaplane |
| Parachutisme |
| Saut à l'élastique |
| Héli-ski |
| Ski hors-piste |
| Motoneige hors-piste |
| Aviation (à l'exception des pilotes commerciaux sur des vols réguliers) |
| Course automobile |
| Kitesurf |

**Important:** Cette exclusion s'applique même si les activités mentionnées sont pratiquées de façon récréative, encadrée, ou avec un instructeur.

---

## Garanties Optionnelles (Avenants)

### 1. Avenant d'Assurance Vie pour Personne à Charge

#### Fonctionnement

- Offre un montant d'assurance vie à **tous les enfants à charge** nés à la date d'effet de la garantie
- **Couverture automatique** pour tout nouvel enfant né ou adopté légalement après l'entrée en vigueur
- Couverture débute dès l'**âge de 15 jours** pourvu que l'enfant ait obtenu son congé de l'hôpital après sa naissance

#### Indemnités Offertes

| Montant d'Assurance |
|---|
| 15 000 $ |
| 20 000 $ |
| 25 000 $ |

#### Option de Transformation

- **Montant transformable:** 5 fois le montant de l'indemnité
- **Moment:** À l'échéance de la garantie

#### Limitations

- **Clause préexistante:** 12 mois pour les enfants nés à la date d'effet de la garantie

#### Critères d'Admissibilité - Définition d'Enfant à Charge

Est un enfant à charge, un enfant sur lequel vous exercez l'autorité parentale (ou l'exerceriez s'il était mineur), dont vous assumez le soutien et qui répond à **l'un** des critères suivants:

**Critères d'âge:**
- Être âgé de **moins de 21 ans**, OU
- Être âgé **entre 21 et 25 ans** tout en étant étudiant à temps plein, OU
- Être atteint d'une **déficience fonctionnelle importante** survenue avant son 21ème anniversaire

**Conditions additionnelles (toutes obligatoires):**
- Ne doit **pas** être marié ou conjoint de fait
- Doit être **sans emploi à temps plein**
- Maintenir une **adresse permanente au Canada**
- Être couvert par le **régime public d'assurance maladie** de sa province de résidence

**Note importante - Études à l'étranger:**
Un enfant à charge allant étudier à l'extérieur du pays doit, au préalable, entreprendre les démarches nécessaires pour maintenir sa couverture d'assurance maladie provinciale. Si celle-ci n'est pas maintenue, ce dernier ne sera plus couvert par la présente garantie.

---

### 2. Avenant d'Assurance Cancer

#### Type de Couverture

Assurance cancer temporaire jusqu'à 80 ans

#### Primes

Les primes sont fixes et garanties pour la durée du terme du contrat

#### Critères d'Admissibilité

| Critère | Exigence |
|---|---|
| **Âge d'établissement** | 18 à 70 ans |
| **Statut de résidence** | Résident permanent ou citoyen canadien |

#### Indemnités Offertes

| Type | Montant |
|---|---|
| **Minimum** | 10 000 $ |
| **Maximum** | 75 000 $ |

#### Limitations et Exclusions

**Affection préexistante:**
Aucune indemnité ne sera versée en cas d'affection préexistante, soit une maladie ou une affection pour laquelle, au cours de la période de **12 mois** précédant la date de début du contrat ou de sa remise en vigueur.

#### Période de Survie

Pour que l'indemnité soit versée, l'assuré doit:
- Être toujours vivant **30 jours** après la date du diagnostic
- **Exclusion:** Nombre de jours pendant lesquels l'assuré est maintenu en vie artificiellement

#### Période Moratoire

Aucune indemnité ne sera versée si, au cours des **90 jours** suivant la date de début du contrat:

1. L'assuré a présenté des signes ou des symptômes, ou s'est soumis à des investigations qui ont mené à l'établissement d'un diagnostic de cancer (couvert ou non par ce contrat), peu importe la date d'établissement du diagnostic

2. L'assuré a reçu un diagnostic de cancer (couvert ou non par ce contrat)

---

### 3. Avenant d'Assurance Invalidité Totale

#### Type de Couverture

Assurance invalidité totale temporaire jusqu'à 65 ans

#### Primes

Les primes sont fixes et garanties pour la durée du terme du contrat

#### Critères d'Admissibilité

| Critère | Exigence |
|---|---|
| **Âge d'établissement** | 18 à 60 ans |
| **Statut de résidence** | Résident permanent ou citoyen canadien |

#### Indemnités Mensuelles Offertes

| Type | Montant |
|---|---|
| **Minimum** | 500 $ |
| **Maximum** | Minimum entre 1,5% du montant d'assurance vie OU jusqu'à 3 000 $ selon la catégorie d'emploi |

**Utilisation des indemnités:**
- Les indemnités sont payables **exclusivement** pour le remboursement de créances admissibles
- Toute indemnité d'invalidité de régimes gouvernementaux **n'affecte aucunement** le montant payable sous cette garantie

#### Nombre de Versements Maximum

| Période de Couverture | Nombre de Versements |
|---|---|
| **2 ans** | 60 versements |
| **5 ans** | 84 versements |

#### Délai de Carence

- **90 jours**, rétroactif au 30e jour

#### Restriction

Si la personne assurée fait **faillite en cours d'invalidité**, plus aucune prestation n'est payable pendant ladite invalidité.

---

## Glossaire et Définitions

| Terme | Définition |
|---|---|
| **Assurance vie temporaire 100 ans (T100)** | Assurance vie permanente avec couverture jusqu'à 100 ans, primes fixes |
| **Assurance vie temporaire** | Assurance vie pour une période déterminée (10, 15, 20, 25, 30, 35 ans) |
| **Renouvelable** | Possibilité de renouveler la police sans preuve d'assurabilité |
| **Transformable** | Droit de convertir une police temporaire en police permanente sans preuve d'assurabilité |
| **Avenant** | Garantie additionnelle ajoutée à une police d'assurance principale |
| **Personne à charge** | Enfant sur lequel on exerce l'autorité parentale et dont on assume le soutien |
| **Capital assuré** | Montant payable au décès de l'assuré |
| **Prime** | Paiement périodique pour maintenir la couverture d'assurance |
| **Délai de carence** | Période d'attente avant que les prestations d'invalidité commencent |
| **Période de survie** | Période pendant laquelle l'assuré doit demeurer vivant après le diagnostic pour que l'indemnité soit versée |
| **Période moratoire** | Période initiale pendant laquelle certaines conditions ne sont pas couvertes |
| **Affection préexistante** | Condition médicale existante avant la date d'effet de la police |

---

## Résumé des Garanties Optionnelles

<!-- MACHINE_READABLE_DATA: riders_summary_matrix -->
```json
{
  "table_id": "riders_summary",
  "table_type": "optional_coverage",
  "currency": "CAD",
  "riders": [
    {
      "rider_id": "dependent_life",
      "name": "Assurance vie pour personne à charge",
      "name_en": "Dependent Life Insurance",
      "age_establishment": {
        "type": "dependent",
        "display": "N/A (enfants à charge)",
        "covered_ages": {
          "min": 0.041,
          "max": 25,
          "note": "15 jours à 25 ans selon critères"
        }
      },
      "coverage_amounts": {
        "options": [15000, 20000, 25000],
        "currency": "CAD",
        "display": "15 000 $ à 25 000 $"
      },
      "duration": {
        "type": "dependent_age_based",
        "display": "Selon âge de l'enfant"
      },
      "special_features": {
        "convertible": true,
        "conversion_multiplier": 5,
        "display": "Transformation possible: 5x l'indemnité"
      }
    },
    {
      "rider_id": "cancer",
      "name": "Assurance cancer",
      "name_en": "Cancer Insurance",
      "age_establishment": {
        "min": 18,
        "max": 70,
        "display": "18 à 70 ans"
      },
      "coverage_amounts": {
        "min": 10000,
        "max": 75000,
        "currency": "CAD",
        "display": "10 000 $ à 75 000 $"
      },
      "duration": {
        "type": "to_age",
        "until_age": 80,
        "display": "Jusqu'à 80 ans"
      },
      "special_features": {
        "waiting_period": {
          "days": 90,
          "type": "moratorium",
          "display": "Période moratoire: 90 jours"
        },
        "survival_period": {
          "days": 30,
          "note": "Must survive 30 days after diagnosis"
        },
        "pre_existing_condition_period": {
          "months": 12
        }
      }
    },
    {
      "rider_id": "total_disability",
      "name": "Assurance invalidité totale",
      "name_en": "Total Disability Insurance",
      "age_establishment": {
        "min": 18,
        "max": 60,
        "display": "18 à 60 ans"
      },
      "coverage_amounts": {
        "min": 500,
        "max": 3000,
        "unit": "monthly",
        "currency": "CAD",
        "display": "500 $ à 3 000 $ /mois",
        "calculation": "Min between 1.5% of life coverage OR up to 3000 based on occupation"
      },
      "duration": {
        "type": "to_age",
        "until_age": 65,
        "display": "Jusqu'à 65 ans"
      },
      "special_features": {
        "elimination_period": {
          "days": 90,
          "retroactive_to_day": 30,
          "display": "Délai de carence: 90 jours"
        },
        "max_payments": {
          "2_year_coverage": 60,
          "5_year_coverage": 84
        },
        "use_restriction": "debt_repayment_only"
      }
    }
  ]
}
```
<!-- END_MACHINE_READABLE_DATA -->

| Avenant | Âge d'établissement | Montants | Durée | Particularités |
|---|---|---|---|---|
| **Assurance vie pour personne à charge** | N/A (enfants à charge) | 15 000 $ à 25 000 $ | Selon âge de l'enfant | Transformation possible: 5x l'indemnité |
| **Assurance cancer** | 18 à 70 ans | 10 000 $ à 75 000 $ | Jusqu'à 80 ans | Période moratoire: 90 jours |
| **Assurance invalidité totale** | 18 à 60 ans | 500 $ à 3 000 $ /mois | Jusqu'à 65 ans | Délai de carence: 90 jours |

---

## Fiche de Renseignements - Droits du Consommateur

### Informations Générales

| Élément | Détails |
|---|---|
| **Nom du distributeur** | Emma Services Financiers Inc. |
| **Nom de l'assureur** | Humania Assurances Inc. |
| **Nom du produit** | Assurance vie temporaire 100 ans Emma |

---

### Liberté de Choisir

**Vous n'êtes jamais obligé d'acheter une assurance:**

- Qui vous est offerte chez votre distributeur
- Auprès d'une personne que l'on vous désigne
- Pour obtenir un meilleur taux d'intérêt ou tout autre avantage

**Important:** Même si vous êtes tenus d'être assuré, vous n'êtes pas obligé d'acheter l'assurance que l'on vous offre présentement. **C'est à vous de choisir** votre produit d'assurance et votre assureur.

---

### Comment Choisir

Pour bien choisir le produit d'assurance qui vous convient, nous vous recommandons de lire le **sommaire qui décrit le produit d'assurance** et que l'on doit vous remettre.

---

### Rémunération du Distributeur

- Une partie de ce que vous payez pour l'assurance sera versée en rémunération au distributeur
- Lorsque cette rémunération est **supérieure à 30 %**, le distributeur a l'obligation de vous le dire

---

### Droit d'Annuler

**Délai légal minimal:**
- La Loi vous permet de mettre fin à votre assurance, **sans frais**, dans les **10 jours** suivant l'achat de votre assurance

**Délai accordé par l'assureur:**
- L'assureur peut vous accorder un délai plus long
- Informez-vous auprès de votre distributeur du délai d'annulation sans frais qui vous est accordé

**Après le délai:**
- Vous avez la faculté d'annuler l'assurance en tout temps
- Des frais pourraient s'appliquer

**Note importante - Financement:**
Lorsque le coût de l'assurance est ajouté au montant du financement et que vous annulez l'assurance:
- Il est possible que les versements mensuels de votre financement ne changent pas
- Le montant du remboursement pourrait plutôt servir à diminuer la durée du financement
- Informez-vous auprès de votre distributeur

---

## Ressources et Information

### Autorité des Marchés Financiers (AMF)

L'Autorité des marchés financiers peut vous fournir de l'information **neutre et objective**.

- **Site web:** <https://www.lautorite.qc.ca>
- **Téléphone:** 1 877 525-0337

### Documents de Référence

- **Spécimen de police Emma:** <https://emma.ca/specimen-de-police>

### Formuler une Plainte

- **Humania Assurances:** <https://www.humania.ca/formuler-plainte>

---

## Statistiques du Document

Cette section fournit un aperçu quantitatif du contenu du sommaire pour faciliter la navigation et l'analyse.

<!-- MACHINE_READABLE_DATA: document_statistics -->
```json
{
  "statistics_id": "emma_product_summary_stats",
  "generated_date": "2024-01-15",
  "document_type": "product_summary",
  "document_metrics": {
    "total_sections": 10,
    "total_main_products": 2,
    "total_riders": 3,
    "total_products": 5,
    "total_exclusions": 5,
    "total_dangerous_activities": 13,
    "total_glossary_terms": 11,
    "total_consumer_rights_sections": 5
  },
  "products_breakdown": {
    "main_products": {
      "count": 2,
      "products": [
        {
          "id": "emma_t100",
          "name": "Emma T100",
          "type": "permanent_life",
          "age_range": "18-80",
          "min_coverage": 1000,
          "max_coverage": 5000000,
          "renewable": false,
          "convertible": false
        },
        {
          "id": "emma_term",
          "name": "Emma Temporaire",
          "type": "term_life",
          "age_range": "18-80",
          "min_coverage": 50000,
          "max_coverage": 5000000,
          "renewable": true,
          "convertible": true,
          "term_options": [10, 15, 20, 25, 30, 35]
        }
      ]
    },
    "riders": {
      "count": 3,
      "riders": [
        {
          "id": "dependent_life",
          "name": "Assurance vie pour personne à charge",
          "age_range": "dependent",
          "coverage_amounts": [15000, 20000, 25000],
          "convertible": true
        },
        {
          "id": "cancer",
          "name": "Assurance cancer",
          "age_range": "18-70",
          "min_coverage": 10000,
          "max_coverage": 75000,
          "duration": "to_age_80"
        },
        {
          "id": "total_disability",
          "name": "Assurance invalidité totale",
          "age_range": "18-60",
          "min_monthly": 500,
          "max_monthly": 3000,
          "duration": "to_age_65"
        }
      ]
    }
  },
  "coverage_statistics": {
    "age_ranges": {
      "min_age_all_products": 18,
      "max_age_all_products": 80,
      "unique_age_ranges": [
        "18-80 (main products)",
        "18-70 (cancer rider)",
        "18-60 (disability rider)",
        "dependent (child rider)"
      ]
    },
    "coverage_amounts": {
      "currency": "CAD",
      "min_life_coverage": 1000,
      "max_life_coverage": 5000000,
      "min_monthly_disability": 500,
      "max_monthly_disability": 3000,
      "rider_amounts": {
        "dependent_life": [15000, 20000, 25000],
        "cancer": [10000, 75000]
      }
    }
  },
  "exclusions_and_limitations": {
    "common_exclusions": {
      "count": 5,
      "types": [
        {
          "type": "suicide",
          "period": "2_years",
          "applies_to": "all_products"
        },
        {
          "type": "false_declaration",
          "consequence": "contract_nullity",
          "applies_to": "all_products"
        },
        {
          "type": "criminal_act",
          "consequence": "no_coverage",
          "applies_to": "all_products"
        },
        {
          "type": "coverage_limit",
          "max_amount": 5000000,
          "applies_to": "all_products"
        },
        {
          "type": "dangerous_activities",
          "activity_count": 13,
          "applies_to": "all_products"
        }
      ]
    },
    "dangerous_activities": {
      "count": 13,
      "activities": [
        "Alpinisme",
        "Escalade de glace",
        "Plongée sous-marine (hors centre vacances)",
        "Parapente",
        "Paravoile",
        "Deltaplane",
        "Parachutisme",
        "Saut à l'élastique",
        "Héli-ski",
        "Ski hors-piste",
        "Motoneige hors-piste",
        "Aviation (except commercial pilots on regular flights)",
        "Course automobile",
        "Kitesurf"
      ]
    },
    "rider_specific_limitations": {
      "dependent_life": {
        "pre_existing_condition_period": "12_months"
      },
      "cancer": {
        "moratorium_period": "90_days",
        "survival_period": "30_days",
        "pre_existing_condition_period": "12_months"
      },
      "disability": {
        "elimination_period": "90_days",
        "retroactive_to_day": 30,
        "bankruptcy_restriction": true
      }
    }
  },
  "regulatory_information": {
    "insurer": {
      "name": "Humania Assurances Inc.",
      "amf_number": "2000737703",
      "address": "1555 Rue Girouard O, Saint-Hyacinthe, QC J2S 7C8"
    },
    "distributor": {
      "name": "Emma Services financiers Inc.",
      "amf_number": "603236",
      "address": "7900-300, Boul Pierre-Bertrand, Québec (QC) G2J 0C5"
    },
    "regulatory_bodies": [
      {
        "name": "AMF",
        "full_name": "Autorité des marchés financiers",
        "phone": "1-877-525-0337",
        "website": "https://www.lautorite.qc.ca"
      }
    ]
  },
  "consumer_rights": {
    "cancellation_periods": {
      "legal_minimum": "10_days",
      "t100_option_1": "15_days_after_receipt",
      "t100_option_2": "60_days_after_issue",
      "can_cancel_anytime": true,
      "fees_may_apply_after_period": true
    },
    "freedom_of_choice": {
      "not_obligated_to_buy": true,
      "can_choose_provider": true,
      "can_choose_product": true
    },
    "distributor_compensation_disclosure": {
      "threshold": "30_percent",
      "disclosure_required": true
    }
  },
  "claim_requirements": {
    "death_claim": {
      "notice_period": "30_days",
      "documents_deadline": "90_days"
    }
  }
}
```
<!-- END_MACHINE_READABLE_DATA -->

### Aperçu des Statistiques

**Couverture des Produits:**
- **2** produits principaux (T100 et Temporaire)
- **3** garanties optionnelles (avenants)
- **5** produits au total
- **11** termes définis au glossaire

**Montants de Couverture:**
- **Minimum:** 1 000 $ (T100)
- **Maximum:** 5 000 000 $ (tous produits vie)
- **Invalidité mensuelle:** 500 $ à 3 000 $
- **Cancer:** 10 000 $ à 75 000 $

**Groupes d'Âge:**
- **Produits principaux:** 18 à 80 ans
- **Avenant cancer:** 18 à 70 ans
- **Avenant invalidité:** 18 à 60 ans
- **Enfants à charge:** 15 jours à 25 ans

**Exclusions et Limitations:**
- **5** types d'exclusions communes
- **13** activités dangereuses exclues
- **3** périodes spéciales (moratoire, carence, survie)

**Distribution par Type:**

| Type de Produit | Nombre | % du Total |
|-----------------|--------|------------|
| Assurance vie permanente | 1 | 20% |
| Assurance vie temporaire | 1 | 20% |
| Avenants (riders) | 3 | 60% |

**Caractéristiques Spéciales:**

| Caractéristique | T100 | Temporaire | Avenants |
|-----------------|------|------------|----------|
| Renouvelable | Non | Oui | Variable |
| Transformable | Non | Oui | Oui (enfants) |
| Options de paiement | 3 | 1 | Variable |
| Délais spéciaux | Non | Non | Oui |

**Droits du Consommateur:**
- **5** sections de droits documentées
- **2** périodes d'annulation (15 ou 60 jours pour T100)
- **10 jours** minimum légal
- Divulgation obligatoire si rémunération > 30%

**Organismes de Réglementation:**
- **AMF** (Autorité des marchés financiers)
- **Loi sur les assurances du Québec**
- **2** numéros AMF (assureur et distributeur)

---

## Notes Juridiques

Ce document constitue un sommaire des produits d'assurance vie Emma offerts par Humania Assurances Inc. et distribués par Emma Services financiers Inc. Pour les termes et conditions complets, veuillez consulter le spécimen de police.

**Marques de commerce:** Les noms et logos Emma sont des marques de commerce d'Emma Services financiers Inc.

**Dernière mise à jour:** Référez-vous à la version la plus récente de ce document pour les informations les plus actuelles.
