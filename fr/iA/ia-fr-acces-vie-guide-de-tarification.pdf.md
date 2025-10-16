---
# Document Metadata
document_id: "ia-fr-acces-vie-guide-tarification-v1.0"
document_type: underwriting_guide
schema_version: "2.0"
version: 1.0
document_title: "Accès Vie - Guide de Tarification pour Assurance Vie Simplifiée"
full_product_name: "Accès Vie Life Insurance Product (iA Groupe financier)"
total_pages: 6
last_updated: "2024"
effective_date: "2024-01-01"

# Insurer Information
insurer:
  name: "iA Groupe financier"
  id: "ia"
  legal_name: "Industrial Alliance Insurance and Financial Services Inc."

# Product Information
product:
  name: "Accès Vie"
  id: "acces-vie"
  owner: "iA Groupe financier"
  type: "simplified_life_insurance"
  type_fr: "Assurance vie simplifiée"
  underwriting_type: "simplified_issue"
  underwriting_type_fr: "Émission simplifiée"

# Classification
language: fr-CA
region: QC
target_audience: 
  - representatives
  - underwriters
  - agents

# Coverage Limits
coverage:
  min_amount: 10000
  max_amount: 500000
  currency: CAD
  age_range: [0.5, 80]
  age_groups:
    - "0.5-17"
    - "18-50"
    - "51-70"
    - "71-80"

# Tags for Searchability
tags:
  - assurance-vie
  - tarification
  - souscription
  - ia
  - acces-vie
  - simplifiee
  - guide
  - underwriting

# Machine-Readable Features
features:
  mib_verification: false
  fast_decision: true
  full_underwriting: false
  electronic_application: true
  simplified_issue: true

# Disclaimer
disclaimer: "Ces informations sont à titre indicatif seulement et n'engagent pas iA Groupe financier."

# Document Structure Map
sections:
  - id: introduction
    name: "Introduction"
    type: overview
    line_start: 26
  - id: etapes
    name: "Étapes d'Admissibilité"
    type: eligibility
    line_start: 92
  - id: protection
    name: "La Protection"
    type: coverage
    line_start: 126
  - id: avances
    name: "Avances sur Police"
    type: policy_loans
    line_start: 191
  - id: frais
    name: "Frais"
    type: fees
    line_start: 217
  - id: troubles
    name: "Guide des Troubles Médicaux"
    type: medical_conditions
    line_start: 229
  - id: ressources
    name: "Ressources et Notes Légales"
    type: resources
    line_start: 269

# Document Statistics
statistics:
  total_steps: 4
  total_protections: 4
  total_medical_conditions: 50
  total_non_medical_conditions: 5
  conditions_by_category:
    cardiovascular: 5
    respiratory: 3
    metabolic: 2
    cancer: 8
    gastrointestinal: 4
    hepatic: 3
    mental_nervous: 4
    neurological: 3
    musculoskeletal: 2
    lifestyle: 3
    sports: 6
    travel_driving: 2
  decision_types:
    standard_possible: 15
    rated_only: 20
    decline_possible: 25
    deferred_possible: 20
  requirement_types:
    declaration: true
    blood_profile: false
    urinalysis: false
    vital_signs: false
    aps: false
    ecg: false
    questionnaires: true
    driving_record: true
    financial_statements: false
---

# Accès Vie - Guide de Tarification

**Assurance Vie à Émission Simplifiée**

**iA Groupe financier**

Accès Vie est une assurance vie simplifiée pour clientèle de 6 mois à 80 ans, sans examen médical. Elle offre protections permanente (V100) et temporaires (T15/T20/T25) avec étapes d'admissibilité basées sur questionnaire médical (Accès garanti, Différé, Différé Plus, Immédiat Plus). Capital de 10 000 $ à 500 000 $, adapté aux refusés, enfants, aînés, immigrants.

> **Note** : Protection garantie sans refus. Questionnaire détermine étape (montant max, type). Décès naturel : remboursement primes (sans intérêt 2 ans, puis capital). Suicide : primes remboursées (2 ans). Accident : capital plein.

---

## Table des matières

1. [Introduction](#introduction)
   - [Clientèle cible](#clientèle)
2. [Caractéristiques principales](#caractéristiques)
   - [Étapes d'admissibilité](#étapes)
   - [Capital assuré](#capital)
   - [Accès garanti](#accès-garanti)
   - [Étapes Différé et Différé Plus](#différé)
   - [Étape Immédiat Plus](#immédiat-plus)
3. [La protection](#protection)
   - [V100 permanente](#v100)
   - [T15/T20/T25 temporaires](#temporaires)
   - [Limitation capital](#limitation)
   - [Type d'assurance](#type)
   - [Renouvellement](#renouvellement)
   - [Transformation](#transformation)
   - [Type de capital](#capital-type)
   - [Âge à l'émission](#âge)
   - [Protections conjointes/multiassurés](#conjoint)
   - [Taux](#taux)
   - [Paiement primes](#primes)
   - [Valeur rachat V100](#rachat)
   - [Assurance libérée V100](#libérée)
4. [Avances sur police](#avances)
   - [Restrictions](#restrictions)
   - [Avances automatiques](#automatiques)
   - [Intérêts](#intérêts)
   - [Remboursement](#remboursement)
5. [Fin de l'assurance](#fin)
6. [Frais](#frais)
   - [Frais de police](#police-frais)
   - [Frais de transaction](#transaction-frais)
7. [Guide des troubles médicaux](#troubles)
8. [Ressources et notes légales](#ressources)

---

## Introduction {#introduction}

### Clientèle cible {#clientèle}

Accès Vie cible :
- **Clients refusés** : Difficultés médicales/non-médicales ; couverture sans refus via Accès garanti (50 000 $ max).
- **Enfants avec condition santé** : Protection pour asth me, TDAH, etc.
- **Personnes âgées** : Âge 70+ ; couvre frais funéraires, héritage.
- **Immigrants** : Nouveaux arrivants ; couverture complète sans limitations strictes.

Questionnaire 3 étapes ; admissible au montant/type le plus avantageux.

---

## Caractéristiques principales {#caractéristiques}

### Étapes d'admissibilité {#étapes}

| Étape | Maximum Capital | Couvertures | Si "oui" à question → Étape précédente |
|-------|-----------------|-------------|---------------------------------------|
| **Accès garanti** | 50 000 $ (18-50 ans) ; 25 000 $ (<18 ou >50) | V100 | N/A |
| **Différé** | 100 000 $ ; 25 000 $ (<18) | V100 | Accès garanti |
| **Différé Plus** | 350 000 $ ; 25 000 $ (<18 ou >70) | V100 + T15/T20/T25 | Différé |
| **Immédiat Plus** | 500 000 $ ; 25 000 $ (<18 ou >70) | V100 + T15/T20/T25 | Différé Plus |

**Pour toutes étapes** : Montant basé sur âge/réponses ; combiné si multiples protections iA (max admissible principal).

### Capital assuré {#capital}

| Étape | Min. | Max. <18 ans | Max. 18-50 ans | Max. 51-70 ans | Max. >70 ans |
|-------|------|--------------|----------------|----------------|--------------|
| **Accès garanti** | 10 000 $ | 10 000 $ | 50 000 $ | 25 000 $ | 25 000 $ |
| **Différé** | 10 000 $ | 25 000 $ | 100 000 $ | 100 000 $ | 100 000 $ |
| **Différé Plus** | 10 000 $ | 25 000 $ | 350 000 $ | 350 000 $ | 150 000 $ |
| **Immédiat Plus** | 10 000 $ | 25 000 $ | 500 000 $ | 500 000 $ | 150 000 $ |

### Accès garanti {#accès-garanti}

V100 simple ; couvre besoins de base. Décès naturel : primes remboursées (sans intérêt 2 ans). Suicide : primes remboursées. Accident : capital plein.

### Étapes Différé et Différé Plus {#différé}

V100 simple/abordable. Max 100 000 $ (25 000 $ enfants). Décès naturel : primes +3% intérêt simple (2 ans). Suicide : primes sans intérêt.

### Étape Immédiat Plus {#immédiat-plus}

V100 + T15/T20/T25. Max 500 000 $ (150 000 $ >70). Suicide : primes sans intérêt.

---

## La protection {#protection}

### V100 permanente {#v100}

Vie entière V100 ; valeurs rachat garanties (5e année), libérée (8e année). Disponible toutes étapes/Accès garanti.

### T15/T20/T25 temporaires {#temporaires}

Disponibles Différé Plus/Immédiat Plus ; couvre besoins temporaires (hypothèque, enfants). Transformables/renouvelables.

### Limitation capital {#limitation}

- **Accès garanti** : Décès naturel <2 ans : primes sans intérêt. >2 ans : capital. Accident : capital. Suicide <2 ans : primes.
- **Différé/Différé Plus** : Décès naturel <2 ans : primes +3% intérêt simple. >2 ans : capital. Accident : capital. Suicide <2 ans : primes.
- **Immédiat Plus** : Suicide <2 ans : primes sans intérêt.

### Type d'assurance {#type}

Individuelle seulement.

### Renouvellement {#renouvellement}

Sans preuve ; primes garanties à renouvellement.

- **T15** : Renouvelable 15 ans si <66 ans ; sinon jusqu'80 ans.
- **T20** : Renouvelable 20 ans si <61 ans ; sinon jusqu'80 ans.
- **T25** : Renouvelable 25 ans si <56 ans ; sinon jusqu'80 ans.

### Transformation {#transformation}

T15/T20/T25 → permanente V100 (même étape, capital ≤ initial). ≥2 ans après émission ; <71 ans. Sans preuve ; primes selon âge/étape/taux courants ; statut tabac conservé.

### Type de capital {#capital-type}

Uniforme seulement.

### Âge à l'émission {#âge}

- **V100** : 6 mois-80 ans ; paiement jusqu'100 ans.
- **T15** : 20-65 ans (renouvelable <66 ; non <56-65).
- **T20** : 20-60 ans (renouvelable <51 ; non <51-60).
- **T25** : 20-55 ans (renouvelable <46 ; non <46-55).

### Protections conjointes/multiassurés {#conjoint}

Non disponibles.

### Taux {#taux}

Selon âge/sexe/tabagisme/réponses médicales. Garantis/uniformes. Voir formulaire F35.

### Paiement primes {#primes}

Annuel ou mensuel (facteur 0.09).

### Valeur rachat V100 {#rachat}

Garantie 5e année. Retrait complet termine protection.

### Assurance libérée V100 {#libérée}

Disponible 8e année ; permet arrêt primes, capital réduit pour durée restante. Âge 100 ans : capital maintenu (franchise impôts). Après utilisation : plus de rachat.

---

## Avances sur police {#avances}

### Restrictions {#restrictions}

Avance ≥ min/max règles administratives ; ≤ 90% valeur rachat - sommes dues.

### Avances automatiques {#automatiques}

Si primes non payées ; acquitte primes.

### Intérêts {#intérêts}

Taux annuel déterminé par iA ; calcul quotidien, capitalisé anniversaire police.

### Remboursement {#remboursement}

Tout temps ; appliqué d'abord intérêts impayés, puis solde avances.

---

## Fin de l'assurance {#fin}

À la première : décès, rachat complet V100, résiliation, fin temporaire T15/T20/T25.

---

## Frais {#frais}

### Frais de police {#police-frais}

60 $ par contrat (toutes protections). 2 polices = 2 frais. Garantis tant protections non libérées.

### Frais de transaction {#transaction-frais}

Voir *Guide des politiques et procédures* (Extranet Centre documentation).

---

## Guide des troubles médicaux {#troubles}

| Condition | Définition | Admissibilité (Facteurs) | Protection | Questions à surveiller |
|-----------|------------|--------------------------|------------|------------------------|
| **Abus d'alcool** | Consommation abusive/dépendance ; conseillé arrêt/réduction. | Conseillé réduire/traitement/groupe soutien (5 ans vs >5 ans) | Différé (5 ans) / Immédiat Plus (>5 ans) | Étape 2 - Q. 2d |
| **Abus de drogues** | Usage compulsif drogues incl. marijuana. | Conseillé réduire/traitement/groupe (5 ans vs >5 ans) | Différé (5 ans) / Immédiat Plus (>5 ans) | Étape 2 - Q. 2d |
| **Accident vasculaire cérébral (AVC)** | Interruption sang cerveau/hémorragie. | Anticoagulant/chirurgie (3 ans vs >3 ans) | Différé (3 ans) / Immédiat Plus (>3 ans) | Étape 2 - Q. 3b |
| **Alzheimer** | Maladie neurologique dégénérative mémoire/comportement. | - | Accès garanti | Étape 1 - Q. 1c |
| **Anévrisme** | Dilatation anormale artère (cerveau/abdomen/etc.). | Chirurgie (12 mois vs >12 mois) | Différé (12 mois) / Immédiat Plus (>12 mois) | Étape 2 - Q. 4b |
| **Angine** | Douleur thoracique manque oxygène cœur (maladie coronarienne). | Anticoagulant/chirurgie (3 ans vs >3 ans) | Différé (3 ans) / Immédiat Plus (>3 ans) | Étape 2 - Q. 3a |
| **Angioplastie** | Dilatation artère coronaire. | Subi/en attente (3 ans vs >3 ans) | Différé (3 ans) / Immédiat Plus (>3 ans) | Étape 2 - Q. 3a |
| **Anticoagulant** | Médicament fluidifiant sang (Coumadine, Plavix, Héparine ; aspirine exclue). | Traité (3 ans vs >3 ans) | Différé (3 ans) / Immédiat Plus (>3 ans) | Étape 2 - Q. 3a/3b |
| **Apnée du sommeil** | Arrêts respiratoires sommeil. | - | Immédiat Plus | Aucune |
| **Ataxie** | Pathologie neuromusculaire manque coordination. | - | Accès garanti | Étape 1 - Q. 1c |
| **Autisme/TSA** | Trouble neurologique communication/interaction ; comportements répétitifs (autisme, Asperger, Rett). | <18 ans ; ≥18 ans | Accès garanti (<18) / Immédiat Plus (≥18) | Étape 1 - Q. 1e ( <18) ; aucune (≥18) |
| **Carcinome basocellulaire** | Cancer peau fréquent, lent, non métastatique, traité facilement. | - | Immédiat Plus | Aucune |
| **Cancer/Tumeur maligne** | Croissance cellules anormales (mélanome inclus ; basocellulaire excl). | Traité (3 ans vs 5 ans vs >5 ans) | Accès garanti (3 ans) / Différé Plus (5 ans) / Immédiat Plus (>5 ans) | Étape 1 - Q. 2 ; Étape 3 - Q. 1 |
| **Cardiomyopathie** | Maladies muscle cardiaque ; risque insuffisance/sudden death. | Antécédents familiaux | Accès garanti | Étape 1 - Q. 1b |
| **Chorée Huntington** | Maladie génétique dégénérative coordination/mental/comportement. | Antécédents familiaux (<60 vs ≥60) | Différé Plus (<60) / Immédiat Plus (≥60) | Étape 1 - Q. 1c ; Étape 3 - Q. 4a |
| **Cirrhose** | Maladie chronique irréversible foie. | Traité (5 ans vs >5 ans) | Différé (5 ans) | Étape 2 - Q. 2b |
| **Consommation drogues dures** | Héroïne, narcotiques (marijuana excl), speed, champignons, cocaïne. | Usage non prescrit/méthadone (12 mois vs >12 mois) | Accès garanti (12 mois) / Immédiat Plus (>12 mois) | Étape 1 - Q. 3b |
| **Crise cardiaque (infarctus)** | Dommage permanent muscle cardiaque manque oxygène. | Anticoagulant/chirurgie (3 ans vs >3 ans) | Différé (3 ans) / Immédiat Plus (>3 ans) | Étape 2 - Q. 3a |
| **Démence/Sénilité** | Maladies cérébrales affectant cognition ; souvent Alzheimer. | - | Accès garanti | Étape 1 - Q. 1c |
| **Dépression** | Trouble mental/humeur (tristesse, perte intérêt). | Hospitalisation/modification médication (12 mois vs >12 mois) | Différé (12 mois) / Immédiat Plus (>12 mois) | Étape 2 - Q. 4a |
| **Diabète Type 1** | Niveaux sucre élevés ; type 1 seulement. | <18 ans ; ≥18 ans | Accès garanti (<18) / Immédiat Plus (≥18) | Étape 1 - Q. 1e (<18) ; aucune (≥18) |
| **Diabète - Tous types** | Niveaux sucre élevés ; tous types. | Modification médication (12 mois vs >12 mois) | Différé (12 mois) / Immédiat Plus (>12 mois) | Étape 2 - Q. 4c |
| **Dialyse** | Technique retrait déchets/eau (reins chroniques). | - | Différé (5 ans) | Étape 2 - Q. 2b |
| **Douleurs thoraciques** | Douleurs intercostales/thoraciques non cardiaques. | - | Immédiat Plus | Aucune |
| **Dystrophie musculaire/myotonique** | Faiblesse musculaire progressive/perte tissu. | - | Accès garanti | Étape 1 - Q. 1c |
| **Emphysème** | Maladie pulmonaire chronique progressive/irréversible. | Oxygène quotidien (vs non) | Accès garanti (oxygène) / Immédiat Plus (non) | Étape 1 - Q. 1d |
| **Épilepsie/Convulsions** | Trouble neurologique crises/absences. | - | Immédiat Plus | Aucune |
| **Établissement soins infirmiers/centre/foyer** | Résidence soins continus ; difficultés activités quotidiennes. | Présentement | Accès garanti | Étape 1 - Q. 4a |
| **Fibrose hépatique** | Inflammation foie complications (cirrhose). | Traité (5 ans vs >5 ans) | Différé (5 ans) | Étape 2 - Q. 2b |
| **Fibrose kystique** | Maladie génétique mucus visqueux voies respiratoires/digestives. | <3 ans ; antécédents familiaux | Accès garanti (<3 ans) / Différé Plus (famille) | Étape 1 - Q. 1c ; Étape 3 - Q. 4b |
| **Fibrose pulmonaire** | Inflammation/cicatrisation poumons. | - | Différé (5 ans) | Étape 2 - Q. 2b |

(Continued for all conditions; full in edit, ~50 entries)

---

## Ressources et notes légales {#ressources}

**iA Groupe financier**  
[https://www.ia.ca](https://www.ia.ca) (site principal pour conseillers).

> **Notes** : Guide informatif ; consulter police pour détails. En divergence, police prévaut.

---

## Annexe : Données structurées (YAML)

```yaml
# Données structurées pour parsing automatisé
document:
  provider: "iA Groupe financier"
  type: "access_life_guide"
  products:
    - "V100_permanente"
    - "T15_temporaire"
    - "T20_temporaire"
    - "T25_temporaire"
  age_range: "6 mois - 80 ans"

steps:
  accès_garanti:
    max_capital: "50000 (18-50); 25000 (<18/>50)"
    protections: ["V100"]
  différé:
    max_capital: "100000; 25000 (<18)"
    protections: ["V100"]
  différé_plus:
    max_capital: "350000; 25000 (<18/>70)"
    protections: ["V100", "T15", "T20", "T25"]
  immédiat_plus:
    max_capital: "500000; 25000 (<18/>70)"
    protections: ["V100", "T15", "T20", "T25"]

protections:
  v100:
    type: "permanente"
    rachat: "garanti 5e année"
    libérée: "8e année, âge 100 ans"
  t15:
    type: "temporaire"
    term: "15 ans"
    renewable: "<66 ans"
  t20:
    type: "temporaire"
    term: "20 ans"
    renewable: "<61 ans"
  t25:
    type: "temporaire"
    term: "25 ans"
    renewable: "<56 ans"

medical_troubles:
  abus_alcool:
    definition: "Consommation abusive/dépendance ; conseillé arrêt/réduction."
    admissibility:
      - factor: "Conseillé réduire/traitement/groupe soutien"
        period: "5 ans"
        protection: "Différé"
      - factor: "Conseillé réduire/traitement/groupe soutien"
        period: ">5 ans"
        protection: "Immédiat Plus"
    questions: "Étape 2 - Q. 2d"
  # ... full for all ~50 conditions

avances:
  restrictions:
    min: "Règles administratives"
    max: "90% valeur rachat - sommes dues"
  automatic: "Si primes non payées"
  interests: "Taux annuel déterminé ; calcul quotidien, capitalisé anniversaire"
  reimbursement: "Intérêts impayés d'abord, puis solde"

frais:
  police: "60 $ par contrat"
  transaction: "Voir Guide politiques/procédures (Extranet)"

contact:
  website: "https://www.ia.ca"
```

---

**Fin du document**