---
# Document Metadata
document_id: "emma-fr-guide-tarification-v1.0"
document_type: underwriting_guide
schema_version: "2.0"
version: 1.0
document_title: "Guide de Tarification et de Présélection - Produit d'Assurance Vie Emma"
full_product_name: "Emma Life Insurance Product (Humania Assurance)"
total_pages: 13
last_updated: "2024-01-15"
effective_date: "2024-01-01"

# Insurer Information
insurer:
  name: "Humania Assurance Inc."
  id: "humania"
  legal_name: "Humania Assurance Inc."
  
# Product Information
product:
  name: "Emma"
  id: "emma"
  owner: "Humania Assurance Inc."
  type: "term_life_insurance"
  type_fr: "Assurance vie temporaire"
  underwriting_type: "full_selection"
  underwriting_type_fr: "pleine sélection"
  
# Classification
language: fr-CA
region: QC
target_audience: 
  - representatives
  - underwriters
  - agents

# Coverage Limits
coverage:
  min_amount: 0
  max_amount: 5000000
  currency: CAD
  age_range: [18, 75]
  age_groups:
    - "18-40"
    - "41-50"
    - "51-55"
    - "56-60"
    - "61+"

# Tags for Searchability
tags:
  - assurance-vie
  - tarification
  - souscription
  - humania
  - emma
  - temporaire
  - guide
  - underwriting

# Machine-Readable Features
features:
  mib_verification: true
  fast_decision: true
  full_underwriting: true
  electronic_application: true
  simplified_issue: false

# Disclaimer
disclaimer: "Ces informations sont à titre indicatif seulement et n'engagent pas Humania Assurance inc."

# Document Structure Map
sections:
  - id: document_info
    name: "Informations sur le Document"
    type: metadata
    line_start: 44
  - id: product_description
    name: "Le Produit d'Assurance Vie Emma"
    type: product
    line_start: 63
  - id: glossary
    name: "Glossaire et Abréviations"
    type: reference
    line_start: 81
  - id: underwriting_requirements
    name: "Exigences de Tarification"
    type: requirements
    line_start: 99
  - id: underwriting_decisions
    name: "Décisions de Tarification"
    type: decisions
    line_start: 131
  - id: eligibility_criteria
    name: "Critères d'Admissibilité"
    type: eligibility
    line_start: 149
  - id: ineligibility_criteria
    name: "Critères d'Inadmissibilité"
    type: ineligibility
    line_start: 186
  - id: medical_conditions
    name: "Conditions Médicales"
    type: conditions_medical
    line_start: 224
  - id: non_medical_conditions
    name: "Conditions Non Médicales"
    type: conditions_non_medical
    line_start: 823
  - id: reference_tables
    name: "Tables de Référence"
    type: reference
    line_start: 1011
  - id: faq
    name: "Foire aux Questions"
    type: faq
    line_start: 1065

# Document Segments (Original PDF)
document_segments:
  - name: Life Insurance Pre-selection Guide
    pages: 0-7
    confidence: Medium
  - name: Life Insurance Underwriting Guidelines for Non-Medical Conditions
    pages: 8-10
    confidence: Medium
  - name: Foire aux questions (FAQ)
    pages: 11
    confidence: Medium
  - name: Company Profile
    pages: 12
    confidence: Medium

# Document Statistics
statistics:
  total_medical_conditions: 47
  total_non_medical_conditions: 8
  total_faq_items: 7
  total_reference_tables: 2
  conditions_by_category:
    cardiovascular: 4
    respiratory: 2
    metabolic: 2
    cancer: 9
    gastrointestinal: 4
    hepatic: 3
    mental_nervous: 4
    neurological: 3
    musculoskeletal: 2
    lifestyle: 3
    sports: 6
    travel_driving: 2
  decision_types:
    standard_possible: 12
    rated_only: 23
    decline_possible: 35
    deferred_possible: 28
  requirement_types:
    proposition: true
    blood_profile: true
    urinalysis: true
    vital_signs: true
    aps: true
    ecg: true
    questionnaires: true
    driving_record: true
    financial_statements: true
---

# Guide de Tarification et de Présélection
## Produit d'Assurance Vie Emma

### Humania Assurance Inc.

---

## Informations sur le Document

**Assureur / Émetteur:** Humania Assurance Inc.  
**Produit:** Emma (Produit d'assurance vie)  
**Type de document:** Guide de tarification et de présélection pour souscripteurs  
**Type de produit:** Assurance vie temporaire à pleine sélection  
**Langue:** Français  
**Audience:** Représentants, agents et souscripteurs

---

## À Propos de ce Guide

Le présent **guide de tarification et de présélection** (underwriting guide) vise à informer les représentants et souscripteurs des particularités du **produit d'assurance vie Emma** offert par **Humania Assurance Inc.**, des informations nécessaires à son étude, ainsi que des conditions médicales ou non médicales pouvant influencer la décision de tarification.

**IMPORTANT:** Ces informations sont à **titre indicatif seulement** et n'engagent pas Humania Assurance inc.

---

## Le Produit d'Assurance Vie Emma

### Relation Produit-Assureur

- **Assureur / Émetteur:** Humania Assurance Inc.
- **Nom du produit:** Emma
- **Description:** Produit d'assurance vie temporaire à pleine sélection

### Caractéristiques Principales

- **Type:** Produit à pleine sélection (full underwriting)
- **Processus de souscription:** Évaluation complète du risque
- **Vérification:** Une vérification auprès du MIB (Medical Information Bureau) est faite pour chaque demande d'assurance
- **Avantage:** Emma pourrait prendre une décision rapidement si certaines informations médicales et antécédents familiaux sont connus
- **Propriété:** Polices émises par Humania Assurance Inc.

---

## Glossaire et Abréviations

| Abréviation | Signification | Description |
|-------------|---------------|-------------|
| **P** | Proposition | Document de demande d'assurance |
| **PS** | Profil sanguin | Analyse sanguine requise |
| **MU** | Analyse d'urine | Test d'urine requis |
| **SV** | Signes vitaux | Pondération, tension artérielle et pouls cardiaque |
| **RMT** | Rapport du médecin traitant | Document médical du médecin principal |
| **ECG** | Électrocardiogramme | Examen cardiaque |
| **MIB** | Medical Information Bureau | Bureau d'information médicale |
| **VPPC** | Ventilation en Pression Positive Continue | Traitement pour apnée du sommeil |
| **AIT** | Accident ischémique transitoire | Mini-AVC |
| **AVC** | Accident vasculaire cérébral | AVC complet |
| **MPOC** | Maladie pulmonaire obstructive chronique | Maladie respiratoire |

---

## Exigences de Tarification

### Types d'Exigences Possibles

#### Examens Médicaux
- Profil sanguin
- Analyse d'urine
- Signes vitaux (taille/poids et tension artérielle)
- Rapport médical
- ECG (électrocardiogramme)

#### Documents Additionnels
- Questionnaires supplémentaires
- Dossier de conduite automobile
- Rapport d'enquête
- États financiers
- Preuves de revenu

### Matrice des Exigences par Montant et Âge

{/* MACHINE_READABLE_DATA: underwriting_requirements_matrix */}
```json
{
  "table_id": "requirements_by_age_amount",
  "table_type": "underwriting_requirements",
  "currency": "CAD",
  "requirements_legend": {
    "P": {
      "code": "P",
      "name": "Proposition",
      "name_en": "Application",
      "type": "document",
      "required": true
    },
    "PS": {
      "code": "PS",
      "name": "Profil sanguin",
      "name_en": "Blood Profile",
      "type": "medical_test"
    },
    "MU": {
      "code": "MU",
      "name": "Analyse d'urine",
      "name_en": "Urinalysis",
      "type": "medical_test"
    },
    "SV": {
      "code": "SV",
      "name": "Signes vitaux",
      "name_en": "Vital Signs",
      "type": "medical_test"
    },
    "RMT": {
      "code": "RMT",
      "name": "Rapport du médecin traitant",
      "name_en": "Attending Physician Statement",
      "type": "document"
    },
    "ECG": {
      "code": "ECG",
      "name": "Électrocardiogramme",
      "name_en": "Electrocardiogram",
      "type": "medical_test"
    }
  },
  "matrix": [
    {
      "amount_range": "0-500000",
      "amount_min": 0,
      "amount_max": 500000,
      "age_18_40": ["P"],
      "age_41_50": ["P"],
      "age_51_55": ["P"],
      "age_56_60": ["P"],
      "age_61_plus": ["P"]
    },
    {
      "amount_range": "500001-1000000",
      "amount_min": 500001,
      "amount_max": 1000000,
      "age_18_40": ["P"],
      "age_41_50": ["P"],
      "age_51_55": ["P"],
      "age_56_60": ["P"],
      "age_61_plus": ["PS", "MU", "SV"]
    },
    {
      "amount_range": "1000001-1500000",
      "amount_min": 1000001,
      "amount_max": 1500000,
      "age_18_40": ["P"],
      "age_41_50": ["P"],
      "age_51_55": ["PS", "MU", "SV"],
      "age_56_60": ["PS", "MU", "SV"],
      "age_61_plus": ["PS", "MU", "SV"]
    },
    {
      "amount_range": "1500001-2000000",
      "amount_min": 1500001,
      "amount_max": 2000000,
      "age_18_40": ["P"],
      "age_41_50": ["P"],
      "age_51_55": ["PS", "MU", "SV"],
      "age_56_60": ["PS", "MU", "SV"],
      "age_61_plus": ["PS", "MU", "SV", "RMT", "ECG"]
    },
    {
      "amount_range": "2000001-3000000",
      "amount_min": 2000001,
      "amount_max": 3000000,
      "age_18_40": ["PS", "MU", "SV"],
      "age_41_50": ["PS", "MU", "SV"],
      "age_51_55": ["PS", "MU", "SV"],
      "age_56_60": ["PS", "MU", "SV", "RMT"],
      "age_61_plus": ["PS", "MU", "SV", "RMT", "ECG"]
    },
    {
      "amount_range": "3000001-4000000",
      "amount_min": 3000001,
      "amount_max": 4000000,
      "age_18_40": ["PS", "MU", "SV"],
      "age_41_50": ["PS", "MU", "SV"],
      "age_51_55": ["PS", "MU", "SV", "RMT"],
      "age_56_60": ["PS", "MU", "SV", "RMT"],
      "age_61_plus": ["PS", "MU", "SV", "RMT", "ECG"]
    },
    {
      "amount_range": "4000001-5000000",
      "amount_min": 4000001,
      "amount_max": 5000000,
      "age_18_40": ["PS", "MU", "SV"],
      "age_41_50": ["PS", "MU", "SV"],
      "age_51_55": ["PS", "MU", "SV", "RMT"],
      "age_56_60": ["PS", "MU", "SV", "RMT"],
      "age_61_plus": ["PS", "MU", "SV", "RMT", "ECG"]
    }
  ]
}
```
{/* END_MACHINE_READABLE_DATA */}

| Montant d'Assurance ($) | 18-40 ans | 41-50 ans | 51-55 ans | 56-60 ans | 61 ans et plus |
|-------------------------|-----------|-----------|-----------|-----------|----------------|
| 0 - 500 000 | P | P | P | P | P |
| 500 001 - 1 000 000 | P | P | P | P | PS, MU, SV |
| 1 000 001 - 1 500 000 | P | P | PS, MU, SV | PS, MU, SV | PS, MU, SV |
| 1 500 001 - 2 000 000 | P | P | PS, MU, SV | PS, MU, SV | PS, MU, SV, RMT, ECG |
| 2 000 001 - 3 000 000 | PS, MU, SV | PS, MU, SV | PS, MU, SV | PS, MU, SV, RMT | PS, MU, SV, RMT, ECG |
| 3 000 001 - 4 000 000 | PS, MU, SV | PS, MU, SV | PS, MU, SV, RMT | PS, MU, SV, RMT | PS, MU, SV, RMT, ECG |
| 4 000 001 - 5 000 000 | PS, MU, SV | PS, MU, SV | PS, MU, SV, RMT | PS, MU, SV, RMT | PS, MU, SV, RMT, ECG |

---

## Décisions de Tarification

### Types de Décisions Possibles

#### 1. Accepté Standard
Police émise aux taux standards sans surprime.

#### 2. Accepté avec Surprime
Police émise avec une surprime permanente ou temporaire selon le risque.

#### 3. Différé
Aucune offre ne peut être faite maintenant, mais une reconsidération future pourrait être faite selon certaines conditions et/ou exigences.

#### 4. Refus
Aucune offre ne peut être faite.

---

## Avant de Soumettre une Vente en Ligne

### Critères d'Admissibilité de Base

#### Statut de Résidence
- Seuls les **citoyens canadiens** et les **résidents permanents** sont admissibles

#### Langue
- Le client doit comprendre et parler le **français** ou l'**anglais**
- Il ne peut choisir une autre langue ni faire appel à un interprète pour remplir la proposition électronique

---

## Informations Importantes à Recueillir

Lors de la préparation de la proposition en ligne, assurez-vous de recueillir:

### 1. Antécédents Familiaux
- Historique médical des parents, frères et sœurs
- Maladies héréditaires ou génétiques

### 2. Coordonnées Médicales
- Coordonnées du médecin traitant ayant le dossier médical complet
- Coordonnées de tout spécialiste consulté récemment
- Dates des dernières consultations

### 3. Détails Médicaux
- Toute condition médicale actuelle ou passée
- Date du diagnostic
- Médicament ou traitement prescrit
- Condition actuelle et évolution

### 4. Historique Professionnel
- Arrêts de travail (dates, raisons et durée)

---

## Critères d'Inadmissibilité

### Situations Éliminatoires

Votre client **n'est pas admissible** si vous répondez «oui» à l'une des questions suivantes:

#### Investigations et Conditions Médicales
- ❌ Est-il en investigation médicale présentement?

#### Dossier Criminel et Conduite
- ❌ A-t-il été condamné pour conduite avec facultés affaiblies durant la dernière année?
- ❌ Le véhicule est-il équipé d'un antidémarreur éthylométrique?
- ❌ Est-il en attente d'une décision de la cour?
- ❌ A-t-il reçu une sentence dans les deux dernières années?
- ❌ Est-il en période de probation?

### Usage de Drogues Éliminatoires

Humania Assurance n'assure pas les personnes faisant usage de:

- Stéroïdes anabolisants
- Barbituriques
- Héroïne
- Morphine
- Opium
- Demerol
- Codéine
- Amphétamines (speed)
- Cocaïne
- Fentanyl
- Ecstasy
- LSD
- DMT
- Hallucinogènes
- Méthadone

---

## Conditions Médicales

### Maladies Cardiovasculaires

#### Accident Ischémique Transitoire (AIT) / Accident Vasculaire Cérébral (AVC)

**Facteurs influant sur la décision:**
- Âge actuel
- Date du diagnostic
- Nombre d'épisodes
- Usage de tabac actuel et passé

**Exigences probables:**
- Rapport du médecin traitant

**Décisions possibles:**
- **Les 6 premiers mois:** Différé
- **Par la suite:**
  - AIT: Surprime +50% à +150%
  - AVC: Différé 0-1 an, puis entre +50% et refus
- **Moins de 40 ans:** Refus
- **Si usage de tabac courant, diabétique ou multiple AVC:** Refus

---

#### Coronopathie / Crise Cardiaque / Infarctus du Myocarde / Pontage / Angioplastie

**Facteurs influant sur la décision:**
- Âge actuel
- Date du diagnostic
- Sévérité
- Symptôme courant
- Traitement et médication
- Usage de tabac courant et passé

**Exigences probables:**
- Rapport du médecin traitant

**Décisions possibles:**
- **Âge 40 à 60 ans:** Surprime +175% à +275%
- **Âge 60 ans et plus:** Surprime +125% à +225%
- **Si infarctus:** Différé les 6 premiers mois
- **Si plus d'un infarctus:** Refus
- **Moins de 40 ans au diagnostic:** Refus
- **Si fait usage de tabac:** Refus

---

#### Fibrillation Auriculaire

**Facteurs influant sur la décision:**
- Date du diagnostic
- Type de traitement
- Investigation terminée

**Exigences probables:**
- Rapport du médecin traitant

**Décisions possibles:**
- **Les 6 premiers mois:** Différé après le diagnostic
- **Si aucune investigation complète:** Différé
- **Si aucune cause médicale et investigation normale:**
  - Moins de 60 ans: Surprime minimum +50%
  - Après 60 ans: Standard possible

---

#### Hypertension Artérielle

**Facteurs influant sur la décision:**
- Âge actuel
- Date du diagnostic
- Type de médication
- Lecture de la tension artérielle courante

**Exigences probables:**
- Profil sanguin, urine et signes vitaux

**Décisions possibles:**
- **Standard** si bien contrôlée et si la lecture de tension artérielle est dans les limites normales

---

### Troubles Respiratoires

#### Apnée du Sommeil

**Facteurs influant sur la décision:**
- Âge actuel
- Date du diagnostic
- Type: central, mixte ou obstructif
- Traitement VPPC ou chirurgie
- Observance du traitement
- Date du dernier examen

**Exigences probables:**
- Questionnaire apnée du sommeil
- Rapport du médecin traitant

**Décisions possibles:**
- **Traité (selon l'âge et le degré de sévérité):** Standard à +75%
- **Non traité (dépendant de l'âge et du degré de sévérité):** Standard à refus
- **Si en attente d'une polysomnographie:** Différé
- **Apnée centrale:** Refus

---

#### Maladie Pulmonaire Obstructive Chronique (MPOC) / Emphysème / Bronchite Chronique

**Facteurs influant sur la décision:**
- Date du diagnostic
- Traitement
- Degré de sévérité
- Usage de tabac courant et passé

**Exigences probables:**
- Rapport du médecin traitant

**Décisions possibles:**
- **Non-fumeur:** Surprime +50% à refus
- **Fumeur:** Surprime +100% à refus

---

### Troubles Métaboliques

#### Diabète (Type 1 et 2) / Diabète Gestationnel

**Facteurs influant sur la décision:**
- Âge actuel
- Date du diagnostic
- Traitement et médication
- Observance du traitement
- HbA1c
- Usage de tabac

**Exigences probables:**
- Profil sanguin, urine et signes vitaux
- Rapport du médecin traitant

**Décisions possibles:**
- **Diabète gestationnel:** Possible standard à refus
- **Type 1 (selon l'âge au moment de la demande et l'âge au diagnostic):** Surprime de +50% à refus
- **Type 2:** Entre +50% et refus
- **Pour les âges de 56 ans et plus, si bien contrôlé:** Possible standard

---

#### Hypercholestérolémie

**Facteurs influant sur la décision:**
- Âge actuel
- Date du diagnostic
- Type de médication
- Taux de cholestérol courant

**Exigences probables:**
- Profil sanguin, urine et signes vitaux

**Décisions possibles:**
- **Standard** si bien contrôlée et que le taux de cholestérol est dans les limites normales

---

### Cancers

#### Cancer de la Peau / Tumeur Maligne / Carcinome

**Facteurs influant sur la décision:**
- Date du diagnostic
- Type de cancer
- Type de traitement
- Date du dernier traitement
- Pathologie - stade
- Récidive

**Exigences probables:**
- Rapport du médecin traitant

**Décisions possibles:**
- **Basocellulaire:** Possible standard
- **Squameux ou tumeur maligne (selon stade et date du dernier traitement):** Surprime possible à refus

---

#### Cancer de la Prostate

**Facteurs influant sur la décision:**
- Âge actuel
- Date du diagnostic
- Type de traitement
- Date de fin du traitement
- Pathologie - stade
- Récidive

**Exigences probables:**
- Rapport du médecin traitant

**Décisions possibles:**
- **Selon le stade et la date du dernier traitement:** Surprime +50% à refus

---

#### Cancer de la Thyroïde

**Facteurs influant sur la décision:**
- Âge actuel
- Date du diagnostic
- Type de cancer - stade
- Type de traitement
- Date de traitement
- Récidive

**Exigences probables:**
- Rapport du médecin traitant

**Décisions possibles:**
- **Selon le stade et la date du dernier traitement:** Standard à refus

---

#### Cancer des Poumons

**Facteurs influant sur la décision:**
- Âge actuel
- Date du diagnostic
- Type de traitement
- Traitement complété
- Récidive
- Pathologie - stade

**Exigences probables:**
- Rapport du médecin traitant

**Décisions possibles:**
- **Stade 1:** Différé 5 ans post-traitement; par la suite surprime
- **Stade 2 et plus:** Refus
- **Usage de tabac continu:** Refus

---

#### Cancer du Sang (Leucémie)

**Facteurs influant sur la décision:**
- Âge actuel
- Date du diagnostic
- Type de cancer
- Type de traitement
- Date de traitement
- Récidive

**Exigences probables:**
- Rapport du médecin traitant

**Décisions possibles:**
- **Selon le stade et la date du dernier traitement:** Surprime à refus

---

#### Cancer du Sein

**Facteurs influant sur la décision:**
- Âge actuel
- Date du diagnostic
- Type de cancer
- Type de traitement
- Date de traitement
- Récidive

**Exigences probables:**
- Rapport du médecin traitant

**Décisions possibles:**
- **Carcinome in situ:** Différé la 1re année, par la suite standard à +50%
- **Stade 1 et plus (selon le stade et la date du dernier traitement):** Surprime à refus

---

#### Cancer du Côlon

**Facteurs influant sur la décision:**
- Âge actuel
- Date du diagnostic
- Type de cancer - stade
- Type de traitement
- Date de traitement
- Récidive

**Exigences probables:**
- Rapport du médecin traitant

**Décisions possibles:**
- **Selon le stade et la date du dernier traitement:** Standard à refus

---

### Troubles Gastro-intestinaux

#### Colite Ulcéreuse / Maladie de Crohn / Côlon Irritable

**Facteurs influant sur la décision:**
- Âge actuel
- Date du diagnostic
- Symptôme et degré de sévérité
- Traitement
- Chirurgie
- Récidive

**Exigences probables:**
- Questionnaire gastro-intestinal
- Rapport du médecin traitant

**Décisions possibles:**
- **Colite ulcéreuse:**
  - Différé les 6 premiers mois
  - Par la suite (selon la date du diagnostic et le degré de sévérité): Standard à refus
- **Maladie de Crohn:**
  - Différé les 6 premiers mois
  - Par la suite (selon la date du diagnostic et le degré de sévérité): +50% à refus
  - Si bien contrôlé depuis plus de 5 ans: Standard possible
- **Côlon irritable:** Standard

---

#### Œsophage de Barrett

**Facteurs influant sur la décision:**
- Degré de sévérité
- Traitement

**Exigences probables:**
- Rapport du médecin traitant

**Décisions possibles:**
- **Si aucune dysplasie:** Standard
- **Autre cas si traité depuis moins de 2 ans:** Surprime +50%
- **Si traité depuis plus de 2 ans:** Standard possible
- **Si dysplasie haut grade non traité:** Refus

---

#### Pancréatite

**Facteurs influant sur la décision:**
- Nombre d'épisodes
- Date du dernier épisode
- Traitement et médication

**Exigences probables:**
- Rapport du médecin traitant

**Décisions possibles:**
- **Si un épisode:**
  - Différé les 6 premiers mois
  - Entre 6 mois et 2 ans: Surprime +50%
  - Standard par la suite
- **Si plus d'un épisode:**
  - Différé les 12 premiers mois
  - 1 an à 3 ans: Surprime +100%
  - Standard possible par la suite

---

#### Chirurgie Bariatrique

**Facteurs influant sur la décision:**
- Poids avant chirurgie
- Date de chirurgie
- Type de chirurgie
- Complication suite à la chirurgie
- Poids actuel

**Exigences probables:**
- Rapport du médecin traitant

**Décisions possibles:**
- **Les 6 premiers mois:** Différé
- **De 6 mois à 1 an (basé sur le poids avant la chirurgie, moins 50% du poids perdu):** Standard à refus
- **Plus d'un an (basé sur la taille et le poids actuel sans complication):** Standard à refus

---

### Troubles Hépatiques

#### Hépatite A

**Facteurs influant sur la décision:**
- Âge actuel
- Date du diagnostic
- Type de traitement
- Traitement terminé

**Exigences probables:**
- Profil sanguin
- Rapport du médecin traitant

**Décisions possibles:**
- **Si présent:** Différé
- **Standard par la suite** si rétabli sans complication et enzymes hépatiques normales

---

#### Hépatite B

**Facteurs influant sur la décision:**
- Âge actuel
- Date du diagnostic
- Sévérité
- Type de traitement
- Traitement terminé

**Exigences probables:**
- Profil sanguin
- Rapport du médecin traitant

**Décisions possibles:**
- **Différé les 6 premiers mois**
- **Si Hépatite B chronique:** Surprime +50% à +150%
- **Avec hépatite C chronique:** Refus
- **Si aiguë:** Possible standard

---

#### Hépatite C

**Facteurs influant sur la décision:**
- Âge actuel
- Date du diagnostic
- Sévérité
- Type de traitement
- Traitement terminé

**Exigences probables:**
- Profil sanguin
- Rapport du médecin traitant

**Décisions possibles:**
- **Différé les 12 premiers mois**
- **Ceux qui ont l'hépatite C chronique et qui ont aussi l'hépatite B chronique:** Refus
- **Tout autre cas:** Surprime +50% à refus

---

### Troubles Mentaux et Nerveux

#### Anxiété

**Facteurs influant sur la décision:**
- Nombre d'épisodes
- Date du dernier épisode
- Durée d'arrêt de travail
- Traitement et médication
- Hospitalisation
- Idée suicidaire ou tentative de suicide

**Exigences probables:**
- Questionnaire troubles nerveux
- Rapport du médecin traitant

**Décisions possibles:**
- **Standard** s'il n'y a aucune complication

---

#### Dépression Majeure

**Facteurs influant sur la décision:**
- Nombre d'épisodes
- Date du dernier épisode
- Durée d'arrêt de travail
- Traitement et médication
- Hospitalisation
- Idée suicidaire ou tentative de suicide

**Exigences probables:**
- Questionnaire troubles nerveux
- Rapport du médecin traitant

**Décisions possibles:**
- **Actuellement et présentement en invalidité:** Différé
- **Par la suite:** Surprime +50% à +100%

---

#### Bipolarité

**Facteurs influant sur la décision:**
- Nombre d'épisodes
- Date du dernier épisode
- Durée d'arrêt de travail
- Traitement et médication
- Hospitalisation
- Idée suicidaire ou tentative de suicide

**Exigences probables:**
- Questionnaire troubles nerveux
- Rapport du médecin traitant

**Décisions possibles:**
- **Si la date du diagnostic est dans les 12 derniers mois:** Différé
- **Par la suite:** Surprime +50% à +150%

---

#### Schizophrénie

**Facteurs influant sur la décision:**
- Nombre d'épisodes
- Date du dernier épisode
- Durée d'arrêt de travail
- Traitement et médication
- Hospitalisation
- Idée suicidaire ou tentative de suicide

**Exigences probables:**
- Questionnaire troubles nerveux
- Rapport du médecin traitant

**Décisions possibles:**
- **Si diagnostic ou épisode dans les 12 derniers mois:** Différé
- **Par la suite:** Surprime +100% à +300%
- **Épisode récurrent (dernier épisode dans les 24 mois):** Différé
- **Par la suite:** Surprime +100% à +300%, refus possible

---

### Troubles Neurologiques

#### Épilepsie

**Facteurs influant sur la décision:**
- Date du diagnostic
- Type d'épilepsie
- Traitement et médication
- Investigation terminée
- Nombre de crises
- Date de la dernière crise

**Exigences probables:**
- Rapport du médecin traitant

**Décisions possibles:**
- **Différé les 6 premiers mois** après le diagnostic
- **Selon le type d'épilepsie:** Standard à +150%

---

#### Sclérose en Plaques

**Facteurs influant sur la décision:**
- Âge actuel
- Date du diagnostic
- Traitement
- Degré de sévérité
- Limitation des activités

**Exigences probables:**
- Rapport du médecin traitant

**Décisions possibles:**
- **Si symptômes ou diagnostic dans les 12 derniers mois:** Refus
- **Par la suite:** Surprime minimum +50% à refus

---

#### Parkinson

**Facteurs influant sur la décision:**
- Âge du diagnostic
- Date du diagnostic
- Degré de sévérité
- Stabilité

**Exigences probables:**
- Rapport du médecin traitant

**Décisions possibles:**
- **Surprime +50% à refus**

---

### Troubles Musculo-squelettiques

#### Arthrite Rhumatoïde / Arthrite Psoriasique

**Facteurs influant sur la décision:**
- Âge actuel
- Date du diagnostic
- Limitation dans les activités
- Traitement et médication

**Exigences probables:**
- Rapport du médecin traitant

**Décisions possibles:**
- **Selon le degré de sévérité:** Standard à refus

---

## Conditions Non Médicales

### Activités et Mode de Vie

#### Activités Criminelles

**Facteurs influant sur la décision:**
- Date
- Nombre d'activités criminelles
- Type de sentence
- Date à laquelle la sentence est terminée

**Exigences probables:**
- Recherche de dossier criminel

**Décisions possibles:**
- **Une seule offense:** Différé 3 ans après fin de la probation; par la suite surprime minimum +50% à refus
- **Multiples offenses:** Refus
- **En attente de sentence ou en probation:** Refus

---

#### Dépendance à l'Alcool ou à la Drogue

**Facteurs influant sur la décision:**
- Âge actuel
- Usage courant et passé
- Traitement
- Date de cessation

**Exigences probables:**
- Questionnaire concernant la consommation d'alcool et/ou de drogue
- Rapport du médecin traitant
- Profil sanguin

**Décisions possibles:**
- **Usage courant:** Refus
- **0 à 3 ans sans consommation:** Refus
- **Après 3 ans sans consommation:** Surprime +75%

---

#### Usage de Drogues

**Facteurs influant sur la décision:**
- Âge actuel
- Type de drogue
- Fréquence
- Traitement requis
- Antécédents médicaux (troubles nerveux)

**Exigences probables:**
- Questionnaire usage de drogues

**Décisions possibles:**
- **Marijuana:** Standard à refus, taux non-fumeur possible
- **Autre drogue (usage courant):** Refus

---

### Sports et Activités à Risque

#### Aviation (Pilote Privé)

**Facteurs influant sur la décision:**
- Âge actuel
- Nombre d'heures de vol
- Nombre d'années d'expérience
- Type de licence
- Type d'avion
- Endroit survolé

**Exigences probables:**
- Questionnaire aviation

**Décisions possibles:**
- **Standard à surprime +100%**

---

#### Escalade / Alpinisme

**Facteurs influant sur la décision:**
- Type d'escalade
- Endroit
- Altitude
- Intention future

**Exigences probables:**
- Questionnaire escalade

**Décisions possibles:**
- **Escalade en salle:** Standard
- **Randonnées; ascension pédestre; trekking:** Standard
- **Autre (parois, rocheuse, glace):** Surprime +50% à refus

---

#### Parachutisme / Paravoile / Deltaplane / Parapente / Saut à l'Élastique / Héliski / Kitesurf

**Facteurs influant sur la décision:**
- Date
- Endroit
- Intention future

**Exigences probables:**
- Questionnaire sport

**Décisions possibles:**
- **Si l'assuré n'a pas l'intention d'en refaire:** Standard
- **Tout autre cas:** Standard à refus

---

#### Plongée Sous-marine

**Facteurs influant sur la décision:**
- Certification
- Fréquence des plongées
- Endroit
- Profondeur
- Antécédents médicaux

**Exigences probables:**
- Questionnaire plongée sous-marine

**Décisions possibles:**
- **Snorkeling ou plongée en apnée:** Standard
- **Moins de 100 pieds:** Standard si aucune plongée dans les cavernes, sous la glace ou la nuit
- **Tout autre cas:** Surprime +50% à refus
- **Non certifié ou plongeant seul:** Refus

---

#### Course Automobile

**Facteurs influant sur la décision:**
- Type de véhicule
- Type de course
- Vitesse maximum
- Course amateur ou professionnelle

**Exigences probables:**
- Questionnaire course motorisée

**Décisions possibles:**
- **Standard à surprime +50% à +300%**

---

### Conduite et Déplacements

#### Conduite Automobile

**Facteurs influant sur la décision:**
- Liste des infractions des 3 dernières années
- Facultés affaiblies
- Suspension

**Exigences probables:**
- Rapport du dossier de conduite automobile

**Décisions possibles:**
- **Si infraction mineure:** Pourrait être considéré standard
- **Selon résultat du rapport de son dossier:** Possible standard à refus
- **Si le permis est suspendu pour facultés affaiblies ou que le véhicule est muni d'un antidémarreur éthylométrique:** Refus
- **En attente de sentence:** Refus

---

#### Voyages à l'Étranger

**Facteurs influant sur la décision:**
- Destination
- Durée
- Raison
- Avertissement gouvernemental

**Exigences probables:**
- Questionnaire voyages et résidence à l'étranger

**Décisions possibles:**
- **Amérique du Nord et Europe de l'Ouest:** Standard
- **Autre destination:** Standard ou surprime +50% à refus
- **Voyage humanitaire:** Refus

---

## Tables de Référence: Taille et Poids

### Table Standard – Poids Acceptable

| Taille (pieds) | Taille (mètres) | Poids (livres) | Poids (kg) |
|----------------|-----------------|----------------|------------|
| 5'0" | 1.52 m | 88 - 192 | 40 - 87 |
| 5'1" | 1.55 m | 91 - 204 | 41 - 93 |
| 5'2" | 1.58 m | 94 - 206 | 42 - 93 |
| 5'3" | 1.60 m | 97 - 214 | 44 - 97 |
| 5'4" | 1.62 m | 100 - 220 | 45 - 100 |
| 5'5" | 1.65 m | 103 - 225 | 47 - 102 |
| 5'6" | 1.68 m | 107 - 235 | 49 - 107 |
| 5'7" | 1.70 m | 110 - 243 | 50 - 110 |
| 5'8" | 1.73 m | 113 - 249 | 51 - 113 |
| 5'9" | 1.75 m | 117 - 254 | 53 - 115 |
| 5'10" | 1.78 m | 120 - 264 | 54 - 120 |
| 5'11" | 1.80 m | 123 - 268 | 56 - 122 |
| 6'0" | 1.82 m | 126 - 276 | 57 - 125 |
| 6'1" | 1.85 m | 130 - 287 | 59 - 130 |
| 6'2" | 1.88 m | 134 - 297 | 61 - 135 |
| 6'3" | 1.90 m | 137 - 303 | 62 - 137 |
| 6'4" | 1.93 m | 141 - 307 | 64 - 139 |
| 6'5" | 1.95 m | 144 - 319 | 65 - 145 |
| 6'6" | 1.98 m | 148 - 329 | 67 - 149 |
| 6'7" | 2.00 m | 153 - 336 | 69 - 152 |

### Table Refus – Poids Limite de Refus

| Taille (pieds) | Taille (mètres) | Poids (livres) | Poids (kg) |
|----------------|-----------------|----------------|------------|
| 5'0" | 1.52 m | 226 | 103 |
| 5'1" | 1.55 m | 234 | 106 |
| 5'2" | 1.58 m | 241 | 109 |
| 5'3" | 1.60 m | 249 | 113 |
| 5'4" | 1.62 m | 257 | 117 |
| 5'5" | 1.65 m | 265 | 120 |
| 5'6" | 1.68 m | 273 | 124 |
| 5'7" | 1.70 m | 282 | 128 |
| 5'8" | 1.73 m | 290 | 132 |
| 5'9" | 1.75 m | 299 | 136 |
| 5'10" | 1.78 m | 308 | 140 |
| 5'11" | 1.80 m | 316 | 143 |
| 6'0" | 1.82 m | 325 | 147 |
| 6'1" | 1.85 m | 334 | 152 |
| 6'2" | 1.88 m | 344 | 156 |
| 6'3" | 1.90 m | 353 | 160 |
| 6'4" | 1.93 m | 362 | 164 |
| 6'5" | 1.95 m | 372 | 169 |
| 6'6" | 1.98 m | 382 | 173 |
| 6'7" | 2.00 m | 392 | 178 |

---

## Foire aux Questions (FAQ)

### Définitions et Politiques

#### Q: Quelle est votre définition du taux non-fumeur?

**R:** Personne qui n'a pas fait usage de tabac, sous quelque forme que ce soit (cigarettes, vapoteuses, cigarettes électroniques, produits de nicotine, succédanés de nicotine, cigarillos, petits cigares ou plus de 12 gros cigares), au cours des douze (12) mois précédant la signature de la demande d'assurance ou de sa remise en vigueur.

---

#### Q: Les patients atteints du VIH sont-ils acceptés?

**R:** Malheureusement, à ce jour, nous n'acceptons pas les clients porteurs du VIH.

---

#### Q: Une femme enceinte est-elle assurable?

**R:** Oui, s'il n'y a aucune complication reliée à la grossesse en cours et si elle n'a pas d'antécédents de grossesse à risque.

---

### Processus et Documentation

#### Q: Pouvons-nous transmettre une lettre ou un courriel d'accompagnement?

**R:** Oui, si vous pensez que l'information additionnelle est pertinente ou susceptible d'aider à l'analyse de la demande (en incluant le numéro de police concernée).

---

#### Q: Pouvons-nous demander et/ou utiliser les résultats de tests génétiques?

**R:** Non, nous nous conformons à la loi visant à interdire et à prévenir la discrimination génétique.

---

### Dossiers et Antécédents

#### Q: Les clients avec un dossier criminel ou ayant des activités criminelles passées peuvent-ils être acceptés?

**R:** Nous n'acceptons pas les personnes ayant présentement des accusations en instance, qui sont en probation ou qui ont commis une ou plusieurs infractions.

---

### Voyages

#### Q: Avez-vous une ligne directrice pour les voyages?

**R:** Les personnes voyageant fréquemment en zone à risque ne sont généralement pas assurables. Nous ne pouvons malheureusement émettre de lignes directrices en raison des changements géopolitiques fréquents.

---

## Statistiques du Document

Cette section fournit un aperçu quantitatif du contenu du guide pour faciliter la navigation et l'analyse.

{/* MACHINE_READABLE_DATA: document_statistics */}
```json
{
  "statistics_id": "emma_underwriting_guide_stats",
  "generated_date": "2024-01-15",
  "document_metrics": {
    "total_sections": 11,
    "total_pages": 13,
    "total_medical_conditions": 47,
    "total_non_medical_conditions": 8,
    "total_faq_items": 7,
    "total_reference_tables": 2,
    "total_glossary_terms": 11
  },
  "conditions_by_category": {
    "cardiovascular": {
      "count": 4,
      "conditions": [
        "AIT/AVC",
        "Coronopathie/Infarctus/Pontage/Angioplastie",
        "Fibrillation Auriculaire",
        "Hypertension Artérielle"
      ]
    },
    "respiratory": {
      "count": 2,
      "conditions": [
        "Apnée du Sommeil",
        "MPOC/Emphysème/Bronchite Chronique"
      ]
    },
    "metabolic": {
      "count": 2,
      "conditions": [
        "Diabète",
        "Hypercholestérolémie"
      ]
    },
    "cancer": {
      "count": 9,
      "conditions": [
        "Cancer de la Peau/Tumeur Maligne/Carcinome",
        "Cancer de la Prostate",
        "Cancer de la Thyroïde",
        "Cancer des Poumons",
        "Cancer du Sang (Leucémie)",
        "Cancer du Sein",
        "Cancer du Côlon"
      ]
    },
    "gastrointestinal": {
      "count": 4,
      "conditions": [
        "Colite Ulcéreuse/Maladie de Crohn/Côlon Irritable",
        "Œsophage de Barrett",
        "Pancréatite",
        "Chirurgie Bariatrique"
      ]
    },
    "hepatic": {
      "count": 3,
      "conditions": [
        "Hépatite A",
        "Hépatite B",
        "Hépatite C"
      ]
    },
    "mental_nervous": {
      "count": 4,
      "conditions": [
        "Anxiété",
        "Dépression Majeure",
        "Bipolarité",
        "Schizophrénie"
      ]
    },
    "neurological": {
      "count": 3,
      "conditions": [
        "Épilepsie",
        "Sclérose en Plaques",
        "Parkinson"
      ]
    },
    "musculoskeletal": {
      "count": 2,
      "conditions": [
        "Arthrite Rhumatoïde",
        "Arthrite Psoriasique"
      ]
    },
    "lifestyle": {
      "count": 3,
      "conditions": [
        "Activités Criminelles",
        "Dépendance à l'Alcool ou à la Drogue",
        "Usage de Drogues"
      ]
    },
    "sports": {
      "count": 6,
      "conditions": [
        "Aviation (Pilote Privé)",
        "Escalade/Alpinisme",
        "Parachutisme/Paravoile/Deltaplane/Parapente",
        "Plongée Sous-marine",
        "Course Automobile",
        "Saut à l'Élastique/Héliski/Kitesurf"
      ]
    },
    "travel_driving": {
      "count": 2,
      "conditions": [
        "Conduite Automobile",
        "Voyages à l'Étranger"
      ]
    }
  },
  "decision_types": {
    "standard_possible": {
      "count": 12,
      "percentage": 25.5,
      "examples": [
        "Anxiété (sans complication)",
        "Hypercholestérolémie (bien contrôlée)",
        "Hypertension artérielle (bien contrôlée)",
        "Côlon irritable",
        "Hépatite A (guérie)",
        "Carcinome basocellulaire"
      ]
    },
    "rated_only": {
      "count": 23,
      "percentage": 48.9,
      "rating_ranges": {
        "mild": "Standard à +50%",
        "moderate": "+50% à +150%",
        "severe": "+150% à +300%"
      }
    },
    "decline_possible": {
      "count": 35,
      "percentage": 74.5,
      "common_reasons": [
        "Condition non contrôlée",
        "Usage de tabac avec condition cardiovasculaire",
        "Complications sévères",
        "Diagnostic récent",
        "Conditions multiples"
      ]
    },
    "deferred_possible": {
      "count": 28,
      "percentage": 59.6,
      "common_deferral_periods": [
        "6 mois",
        "12 mois",
        "24 mois",
        "5 ans"
      ]
    }
  },
  "requirement_types": {
    "documents": {
      "proposition": {
        "required_for": "Toutes les demandes",
        "code": "P"
      },
      "aps": {
        "required_for": "Conditions médicales complexes",
        "code": "RMT"
      },
      "driving_record": {
        "required_for": "Infractions de conduite",
        "code": "Dossier conduite"
      },
      "financial_statements": {
        "required_for": "Montants élevés",
        "code": "États financiers"
      }
    },
    "medical_tests": {
      "blood_profile": {
        "required_for": "Montants > 500K (selon âge)",
        "code": "PS"
      },
      "urinalysis": {
        "required_for": "Montants > 500K (selon âge)",
        "code": "MU"
      },
      "vital_signs": {
        "required_for": "Montants > 500K (selon âge)",
        "code": "SV"
      },
      "ecg": {
        "required_for": "Montants > 1.5M et âge 61+ ou conditions cardiaques",
        "code": "ECG"
      }
    },
    "questionnaires": {
      "count": 8,
      "types": [
        "Apnée du sommeil",
        "Gastro-intestinal",
        "Troubles nerveux",
        "Aviation",
        "Escalade",
        "Sport",
        "Plongée sous-marine",
        "Course motorisée",
        "Voyages et résidence à l'étranger",
        "Consommation d'alcool/drogue"
      ]
    }
  },
  "coverage_statistics": {
    "amount_ranges": 7,
    "age_groups": 5,
    "min_coverage": 0,
    "max_coverage": 5000000,
    "currency": "CAD"
  },
  "ineligibility_rules": {
    "absolute_declines": {
      "count": 21,
      "categories": [
        "Drogues dures (usage courant)",
        "VIH",
        "Investigation médicale en cours",
        "Conduite avec facultés affaiblies (récente)",
        "Activités criminelles (en cours)",
        "Conditions médicales sévères non contrôlées"
      ]
    },
    "conditional_declines": {
      "count": 14,
      "categories": [
        "Age restrictions",
        "Tobacco use with condition",
        "Multiple episodes",
        "Recent diagnosis"
      ]
    }
  }
}
```
{/* END_MACHINE_READABLE_DATA */}

### Aperçu des Statistiques

**Couverture du Document:**
- **47** conditions médicales détaillées
- **8** conditions non-médicales
- **11** catégories de conditions
- **7** niveaux de montants d'assurance
- **5** groupes d'âge

**Distribution des Décisions:**
- **25.5%** des conditions peuvent être acceptées au taux standard (12/47)
- **48.9%** nécessitent une surprime uniquement (23/47)
- **74.5%** peuvent entraîner un refus selon les circonstances (35/47)
- **59.6%** peuvent nécessiter un différé temporaire (28/47)

**Types d'Exigences:**
- **4** types de documents
- **4** types de tests médicaux
- **10+** questionnaires spécialisés

**Conditions par Catégorie:**

| Catégorie | Nombre de Conditions | % du Total |
|-----------|---------------------|------------|
| Cancers | 9 | 19.1% |
| Sports et Activités | 6 | 12.8% |
| Cardiovasculaires | 4 | 8.5% |
| Gastro-intestinales | 4 | 8.5% |
| Mentales et Nerveuses | 4 | 8.5% |
| Neurologiques | 3 | 6.4% |
| Hépatiques | 3 | 6.4% |
| Style de Vie | 3 | 6.4% |
| Respiratoires | 2 | 4.3% |
| Métaboliques | 2 | 4.3% |
| Musculo-squelettiques | 2 | 4.3% |
| Conduite et Voyages | 2 | 4.3% |

---

## Résumé des Conditions par Catégorie

### Conditions Médicales Acceptables (Standard)

- Anxiété (sans complication)
- Hypercholestérolémie (bien contrôlée)
- Hypertension artérielle (bien contrôlée)
- Côlon irritable
- Hépatite A (guérie)
- Carcinome basocellulaire

### Conditions Nécessitant Surprime

- AIT: +50% à +150%
- Coronopathie: +125% à +275%
- MPOC: +50% à +100%
- Diabète: +50% à refus
- Bipolarité: +50% à +150%
- Dépression: +50% à +100%

### Conditions Entraînant Refus

- AVC multiples
- Usage de tabac avec condition cardiovasculaire
- Cancer des poumons stade 2+
- Apnée centrale
- VIH
- Usage courant de drogues dures
- Dépendance active à l'alcool/drogue
- Conduite avec facultés affaiblies récente

---

## Notes Légales et Avertissements

**Avertissement:** Les informations contenues dans ce guide sont à titre indicatif seulement et n'engagent pas Humania Assurance inc.

**Décisions finales:** Toutes les décisions de tarification sont prises au cas par cas selon l'évaluation complète du dossier.

**Confidentialité:** Toutes les informations médicales et personnelles sont traitées de manière confidentielle conformément aux lois applicables.

**Mise à jour:** Ce guide peut être mis à jour périodiquement. Assurez-vous d'utiliser la version la plus récente.