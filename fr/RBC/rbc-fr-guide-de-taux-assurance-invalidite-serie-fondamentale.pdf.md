---
# Document Metadata
document_id: "rbc-fr-guide-taux-assurance-invalidite-fondamentale-v1.0"
document_type: rate_guide
schema_version: "2.0"
version: 1.0
document_title: "Guide des Taux - Série Fondamentale® RBC Assurance"
full_product_name: "Rate Guide for Disability Insurance Fundamental Series (RBC Insurance)"
total_pages: 420
last_updated: "2024"
effective_date: "2024-01-01"

# Insurer Information
insurer:
  name: "RBC Assurances"
  id: "rbc"
  legal_name: "RBC Assurances®"

# Product Information
product:
  name: "Assurance Invalidité Série Fondamentale®"
  id: "disability-fundamental-series"
  owner: "RBC Assurances"
  type: "disability_insurance"
  type_fr: "Assurance invalidité"
  underwriting_type: "simplified_underwriting"
  underwriting_type_fr: "Souscription simplifiée"
  product_variants:
    - "Perte de revenu"
    - "Frais généraux d'entreprise"
    - "Couverture Blessure"
    - "Couverture Maladie"
    - "Protection non liée à la profession"
    - "Couverture 24 heures sur 24"

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
  min_amount: 500
  max_amount: 6000
  currency: CAD
  age_range: [18, 75]
  age_groups:
    - "18-50"
    - "51-64"
    - "65-75"

# Tags for Searchability
tags:
  - guide-taux
  - serie-fondamentale
  - assurance-invalidite
  - rbc-assurance
  - protection-revenu
  - tarification-simplifiee
  - categories-professionnelles
  - tableaux-primes

# Machine-Readable Features
features:
  rate_tables: true
  professional_categories: true
  benefit_calculations: true
  medical_requirements: true
  height_weight_tables: true

# Disclaimer
disclaimer: "L'assurance invalidité Série Fondamentale® est un produit simplifié, tant dans sa structure que dans le processus d'établissement de la police."

# Document Structure Map
sections:
  - id: vue_ensemble
    name: "Vue d'ensemble"
    type: overview
    line_start: 8
  - id: ce_que_nous_offrons
    name: "Ce que nous offrons"
    type: product_features
    line_start: 33
  - id: exigences_medicales
    name: "Exigences médicales systématiques"
    type: medical_requirements
    line_start: 74
  - id: tableau_taille_poids
    name: "Tableau taille / poids"
    type: height_weight_table
    line_start: 90
  - id: determination_prime
    name: "Détermination de la prime mensuelle"
    type: premium_calculation
    line_start: 110
  - id: synthese_exemples
    name: "Synthèse - Quelques exemples"
    type: examples
    line_start: 197
  - id: tableau_prestations
    name: "Tableau de détermination des prestations"
    type: benefit_table
    line_start: 213
  - id: tableau_prestations_imposables
    name: "Tableau de détermination des prestations imposables"
    type: taxable_benefit_table
    line_start: 426
  - id: ajout_couverture_maladie
    name: "Ajout de la couverture en cas de maladie"
    type: illness_coverage
    line_start: 451
  - id: avenant_deces_mutilation
    name: "Avenant d'assurance décès et mutilation accidentels"
    type: accidental_death_rider
    line_start: 463
  - id: frais_generaux_entreprise
    name: "Frais généraux d'entreprise"
    type: business_expenses
    line_start: 475
  - id: tableaux_primes_revenu
    name: "Perte de revenu - Tableaux des primes"
    type: income_loss_rate_tables
    line_start: 487
  - id: tableaux_primes_frais
    name: "Tableaux des primes Frais généraux d'entreprise"
    type: business_expense_rate_tables
    line_start: 495
  - id: categories_professionnelles
    name: "Catégories professionnelles"
    type: professional_categories
    line_start: 503

# Document Segments (Original PDF)
document_segments:
  - name: "Guide des Taux Assurance Invalidité Série Fondamentale"
    pages: 0-420
    confidence: High

# Document Statistics
statistics:
  total_professional_categories: 6
  coverage_types: 6
  benefit_calculation_methods: 3
  premium_payment_periods: 2
  elimination_periods: 4
  benefit_periods: 2
  medical_requirement_age_groups: 2
  height_weight_ranges: 10
---

# Guide des Taux - Série Fondamentale® RBC Assurance

> **Document Type:** Guide des taux assurance invalidité  
> **Company:** RBC Assurances  
> **Language:** Français  
> **Categories:** Guide des taux, Série Fondamentale, Assurance invalidité, RBC Assurance

## Vue d'ensemble

L'assurance invalidité Série Fondamentale® est un produit simplifié, tant dans sa structure que dans le processus d'établissement de la police. Elle a été conçue pour protéger le revenu des employés et des travailleurs autonomes en cas d'invalidité en calculant les prestations en fonction du revenu d'emploi, du revenu d'entreprise ou du revenu brut.

---

## Table des matières

1. [Vue d'ensemble](#vue-densemble)
2. [Ce que nous offrons](#ce-que-nous-offrons)
3. [Exigences médicales systématiques](#exigences-médicales-systématiques)
4. [Tableau taille / poids](#tableau-taille--poids)
5. [Détermination de la prime mensuelle](#détermination-de-la-prime-mensuelle)
6. [Synthèse - Quelques exemples](#synthèse---quelques-exemples)
7. [Tableau de détermination des prestations](#tableau-de-détermination-des-prestations)
8. [Tableau de détermination des prestations imposables](#tableau-de-détermination-des-prestations-imposables)
9. [Ajout de la couverture en cas de maladie](#ajout-de-la-couverture-en-cas-de-maladie)
10. [Avenant d'assurance décès et mutilation accidentels](#avenant-dassurance-décès-et-mutilation-accidentels)
11. [Frais généraux d'entreprise](#frais-généraux-dentreprise)
12. [Perte de revenu - Tableaux des primes](#perte-de-revenu---tableaux-des-primes)
13. [Tableaux des primes Frais généraux d'entreprise](#tableaux-des-primes-frais-généraux-dentreprise)
14. [Catégories professionnelles](#catégories-professionnelles)

---

## Ce que nous offrons

### Avantages clés du régime

#### Perte de revenu
- **Couverture en cas de blessure** : Protection contre l'invalidité due à une blessure
- **Couverture en cas de maladie** : Protection contre l'invalidité due à une maladie

#### Frais généraux d'entreprise
- **Couverture des frais d'exploitation fixes** : Protection des coûts fixes d'une entreprise

#### Tarification simplifiée
- **Couverture en cas de blessure** : Quelques questions d'admissibilité seulement
- **Couverture en cas de maladie** : Proposition simple avec évaluation médicale du risque

#### Renouvellement garanti
- **Couverture en cas de blessure** : Jusqu'à l'âge de 75 ans
- **Couverture en cas de maladie** : Jusqu'à l'âge de 70 ans

#### Garanties spéciales
- **Garantie d'aide au retour au travail** : Paiements pour services de réadaptation, aménagement du lieu de travail
- **Garantie Remboursement des frais médicaux d'urgence en cas d'accident** : Remboursement jusqu'à 10 000$ de frais médicaux non couverts
- **Avenant d'assurance décès et mutilation accidentels** : Protection supplémentaire

### Limites de souscription et de participation

| Type de limite | Catégories 1 et 2 | Catégories 3, 4, 5 et 6 |
|----------------|-------------------|-------------------------|
| **Limite de souscription minimale** | 500$ | 500$ |
| **Limite de souscription maximale** | 6 000$ | 5 000$ |
| **Limite de souscription imposable maximale (RIPS)** | 8 500$ | 6 500$ |
| **Limite de participation** | 20 000$ | 8 000$ |
| **Limite de participation imposable** | 36 000$ | 12 000$ |

### Notes importantes
- Ces limites se rapportent aux assurances Perte de revenu et Frais généraux d'entreprise
- Un assuré peut obtenir jusqu'à 6 000$ d'assurance individuelle et 6 000$ d'assurance Frais généraux d'entreprise dans les catégories 1 et 2
- Les clients qui souhaitent ajouter la couverture en cas de maladie doivent répondre aux critères de tarification

---

## Exigences médicales systématiques

### Pour la couverture en cas de maladie

Pour déterminer les exigences systématiques en matière de tarification, prenez le montant mensuel courant d'assurance maladie (Perte de revenu et Frais généraux d'entreprise) demandé au titre de la Série Fondamentale, plus le total mensuel de toutes les autres assurances maladies établies, à l'étude ou demandées au cours des 12 derniers mois auprès de RBC Vie.

| Âge | Montant total de la couverture | Exigences |
|-----|--------------------------------|-----------|
| **De 18 à 50 ans** | S.O. | Non médical |
| **De 51 à 64 ans** | Plus de 3 000$ par mois | Test sanguin, test d'urine et examen paramédical |

### Note importante
D'autres exigences pourraient s'appliquer, à la discrétion de RBC Vie, en fonction des particularités du dossier. Il pourrait s'agir de questionnaires, d'un entretien sur les antécédents personnels du proposant ou d'un rapport du médecin (déclaration du médecin traitant).

---

## Tableau taille / poids

Pour être admissible à l'assurance, le poids du proposant doit se situer entre le poids minimal et maximal du tableau ci-dessous.

| Taille | | Poids minimal | | Poids maximal | |
|--------|---|---------------|---|---------------|---|
| **Pieds / pouces** | **cm** | **lb** | **kg** | **lb** | **kg** |
| 4 pi 10 po – 4 pi 11 po | 147 à 151 | 90 | 40 | 195 | 88 |
| 5 pi – 5 pi 2 po | 152 à 158 | 97 | 44 | 205 | 93 |
| 5 pi 3 po – 5 pi 4 po | 159 à 163 | 105 | 48 | 225 | 102 |
| 5 pi 5 po – 5 pi 6 po | 164 à 168 | 108 | 49 | 230 | 104 |
| 5 pi 7 po – 5 pi 8 po | 169 à 173 | 114 | 51 | 245 | 111 |
| 5 pi 9 po – 5 pi 10 po | 174 à 179 | 120 | 54 | 250 | 113 |
| 5 pi 11 po – 6 pi | 180 à 184 | 128 | 58 | 270 | 122 |
| 6 pi 1 po – 6 pi 2 po | 185 à 189 | 135 | 61 | 280 | 127 |
| 6 pi 3 po – 6 pi 4 po | 190 à 194 | 143 | 64 | 300 | 136 |
| 6 pi 5 po – 6 pi 7 po | 195 à 201 | 150 | 68 | 310 | 140 |

---

## Détermination de la prime mensuelle

### Pour la couverture en cas de blessure

#### Étapes de calcul

1. **Déterminez la catégorie professionnelle** du client en consultant le tableau des catégories professionnelles du présent guide
2. **Déterminez le revenu annuel assurable** de votre client
3. **Déterminez la prestation mensuelle maximale admissible** au moyen du Tableau de détermination des prestations
4. **Déterminez le type de couverture** qui convient le mieux au client
5. **Sélectionnez la période d'indemnisation** désirée
6. **Sélectionnez le délai de carence** désiré
7. **Déterminez le montant d'assurance** désiré et la prime qui s'y applique

### Définitions des revenus

#### Revenu annuel assurable
Désigne :
- **Si vous êtes salarié** : Votre revenu d'emploi annuel
- **Si vous touchez des revenus en tant que travailleur autonome** : Le montant le plus élevé entre :
  - Votre revenu d'entreprise annuel plus votre revenu d'emploi annuel provenant de l'entreprise
  - 50% de votre chiffre d'affaires brut annuel

#### Revenu d'emploi
Désigne votre salaire, votre traitement, vos commissions, vos honoraires et tout boni annuel ou périodique habituel provenant d'un emploi, moins les dépenses d'emploi déductibles du revenu en application de la Loi de l'impôt sur le revenu du Canada.

#### Revenu d'entreprise
La part qui vous revient :
- Des bénéfices ou des pertes d'une entreprise constituée en société par actions dont vous êtes partiellement ou en totalité propriétaire, et pour laquelle vous travailliez à plein temps ou à temps partiel
- Du revenu d'une entreprise non constituée en société par actions dont vous êtes partiellement ou en totalité propriétaire et pour laquelle vous travailliez à plein temps ou à temps partiel, moins votre part des frais d'exploitation qui sont déductibles de l'impôt fédéral

#### Cinquante pour cent du chiffre d'affaires brut
La part du chiffre d'affaires qui vous revient, avant les frais d'exploitation et l'impôt, d'une entreprise constituée en société par actions ou non, et dont vous étiez partiellement ou en totalité propriétaire, et pour laquelle vous travailliez à plein temps ou à temps partiel.

Le revenu brut est réduit des montants suivants :
- Le coût des marchandises vendues
- Tout salaire, traitement ou boni versé à titre de rémunération aux employés de l'entreprise, sauf les montants qui vous sont versés

### Exclusions du revenu annuel assurable
Le revenu annuel assurable ne comprend pas les revenus de placement, les dividendes, les retraits des propriétaires, les revenus d'intérêt, les revenus reçus de régimes gouvernementaux, les loyers, les redevances, les revenus de pension, les rentes, les rémunérations différées ou toute autre forme de revenus qui ne dépendent pas de votre capacité à exercer une profession ou à occuper un emploi.

### Types de couverture

#### Protection non liée à la profession
- Couverture pour les blessures non liées au travail

#### Couverture 24 heures sur 24
- Couverture pour les blessures liées et non liées au travail

### Périodes d'indemnisation

#### Options disponibles
- **5 ans** : Couverture pour une période déterminée
- **Jusqu'à 70 ans** : Couverture jusqu'à l'âge de 70 ans

#### Fin de la période d'indemnisation
La période d'indemnisation maximale prend fin à la plus rapprochée des dates suivantes :
- La date à laquelle vous n'êtes plus considéré comme invalide aux termes de cette police
- La date à laquelle les prestations cessent d'être versées conformément aux limitations ou exclusions de garantie de cette police
- Votre 70e anniversaire de naissance, si votre invalidité commence le jour de votre 68e anniversaire de naissance ou avant cette date
- Le dernier jour de la période d'indemnisation indiquée dans les conditions particulières de la police, si votre invalidité commence le jour de votre 68e anniversaire de naissance ou avant cette date
- La date à laquelle les prestations pour perte de revenu vous ont été versées pendant 24 mois, si votre invalidité commence après votre 68e anniversaire de naissance
- La date à laquelle vous omettez de fournir une preuve de sinistre conformément aux dispositions visant la preuve de sinistre

### Délais de carence

#### Options disponibles
- **Aucun** : Prestations immédiates
- **30 jours** : Délai de carence de 30 jours
- **90 jours** : Délai de carence de 90 jours
- **120 jours** : Délai de carence de 120 jours

### Montant d'assurance

#### Sélection du montant
Vous pouvez sélectionner un montant dans les tableaux de taux suivants, ou tout autre montant par tranche de 100$, soit de 500$ à 6 000$, jusqu'à concurrence de la prestation mensuelle maximale admissible du client.

#### Calcul de la prime
Pour ce faire, additionnez le montant de la colonne « Tranche de 100$ » à chaque tranche supplémentaire de 100$. 

**Exemple** : Pour une couverture de 700$ par mois, ajoutez à la prime d'une couverture de 500$ deux fois le montant d'une tranche supplémentaire de 100$.

### Garantie automatique
La garantie Remboursement des frais médicaux d'urgence en cas d'accident est automatiquement incluse dans la couverture en cas de blessure. Aucune prime supplémentaire n'est exigée.

---

## Synthèse - Quelques exemples

### Calcul des revenus

Les tableaux ci-dessous sont des exemples de la manière de déterminer le revenu d'emploi, le revenu d'entreprise et le chiffre d'affaires brut. Ces revenus servent à mesurer les revenus annuels assurables et à déterminer la prestation mensuelle maximale admissible dans le Tableau de détermination des prestations.

### Règle de calcul des prestations
Au moment de présenter une demande de règlement, le montant de l'indemnisation du client sera égal au montant le moins élevé entre :
- Le montant de la prestation souscrite
- La prestation mensuelle maximale à laquelle le client est admissible lorsqu'il devient invalide

### Preuve de revenu
Nous exigeons une preuve écrite du revenu annuel assurable, notamment des renseignements provenant de tiers, une copie certifiée conforme des déclarations de revenus (T1), les états des revenus et dépenses vérifiés ou les bulletins de salaire de l'employeur (T4).

---

## Tableau de détermination des prestations

### Tableau des revenus

*La limite de souscription maximale des personnes des catégories 3, 4, 5 et 6 s'élève à 5 000$ et la limite de participation pour ces classes est de 8 000$. La limite de souscription maximale des personnes des catégories 1 et 2 s'élève à 6 000$ et la limite de participation pour ces classes est de 20 000$.*

| Revenu annuel assurable | | Prestation mensuelle maximale admissible | Revenu de la profession jugée raisonnable (annuel) |
|-------------------------|---|-------------------------------------------|-----------------------------------------------------|
| **De** | **À** | | |
| – | 7 400$ | 0$ | – |
| 7 401$ | 8 800$ | 500$ | 5 280$ |
| 8 801$ | 10 400$ | 600$ | 6 240$ |
| 10 401$ | 12 000$ | 700$ | 7 200$ |
| 12 001$ | 13 600$ | 800$ | 8 160$ |
| 13 601$ | 15 200$ | 900$ | 9 120$ |
| 15 201$ | 16 800$ | 1 000$ | 10 080$ |
| 16 801$ | 18 400$ | 1 100$ | 11 040$ |
| 18 401$ | 20 000$ | 1 200$ | 12 000$ |
| 20 001$ | 21 600$ | 1 300$ | 12 960$ |
| 21 601$ | 23 200$ | 1 400$ | 13 920$ |
| 23 201$ | 24 800$ | 1 500$ | 14 880$ |
| 24 801$ | 26 400$ | 1 600$ | 15 840$ |
| 26 401$ | 28 000$ | 1 700$ | 16 800$ |
| 28 001$ | 29 600$ | 1 800$ | 17 760$ |
| 29 601$ | 31 200$ | 1 900$ | 18 720$ |
| 31 201$ | 32 800$ | 2 000$ | 19 680$ |
| 32 801$ | 34 400$ | 2 100$ | 20 640$ |
| 34 401$ | 36 000$ | 2 200$ | 21 600$ |
| 36 001$ | 37 600$ | 2 300$ | 22 560$ |
| 37 601$ | 39 200$ | 2 400$ | 23 520$ |
| 39 201$ | 40 800$ | 2 500$ | 24 480$ |
| 40 801$ | 42 400$ | 2 600$ | 25 440$ |
| 42 401$ | 44 000$ | 2 700$ | 26 400$ |
| 44 001$ | 45 600$ | 2 800$ | 27 360$ |
| 45 601$ | 47 200$ | 2 900$ | 28 320$ |
| 47 201$ | 48 800$ | 3 000$ | 29 280$ |
| 48 801$ | 50 400$ | 3 100$ | 30 200$ |
| 50 401$ | 52 000$ | 3 200$ | 31 000$ |
| 52 001$ | 53 600$ | 3 300$ | 31 800$ |
| 53 601$ | 55 200$ | 3 400$ | 32 600$ |
| 55 201$ | 56 800$ | 3 500$ | 33 400$ |
| 56 801$ | 58 400$ | 3 600$ | 34 200$ |
| 58 401$ | 60 000$ | 3 700$ | 35 000$ |
| 60 001$ | 61 600$ | 3 800$ | 35 800$ |
| 61 601$ | 63 200$ | 3 900$ | 36 600$ |
| 63 201$ | 64 800$ | 4 000$ | 37 400$ |
| 64 801$ | 67 800$ | 4 100$ | 38 900$ |
| 67 801$ | 70 800$ | 4 200$ | 40 400$ |
| 70 801$ | 73 800$ | 4 300$ | 41 900$ |
| 73 801$ | 76 800$ | 4 400$ | 43 400$ |
| 76 801$ | 79 800$ | 4 500$ | 44 900$ |
| 79 801$ | 82 800$ | 4 600$ | 46 400$ |
| 82 801$ | 85 800$ | 4 700$ | 47 900$ |
| 85 801$ | 88 800$ | 4 800$ | 49 400$ |
| 88 801$ | 91 800$ | 4 900$ | 50 900$ |
| 91 801$ | 94 800$ | 5 000$ | 52 400$ |
| 94 801$ | 97 800$ | 5 100$ | 53 900$ |
| 97 801$ | 100 800$ | 5 200$ | 55 400$ |
| 100 801$ | 103 800$ | 5 300$ | 56 900$ |
| 103 801$ | 106 800$ | 5 400$ | 58 400$ |
| 106 801$ | 109 800$ | 5 500$ | 59 900$ |
| 109 801$ | 112 800$ | 5 600$ | 61 400$ |
| 112 801$ | 115 800$ | 5 700$ | 62 900$ |
| 115 801$ | 118 800$ | 5 800$ | 64 400$ |
| 118 801$ | 121 800$ | 5 900$ | 65 900$ |
| 121 801$ | 124 800$ | 6 000$ | 67 400$ |
| 124 801$ | 127 800$ | 6 100$ | 68 900$ |
| 127 801$ | 130 800$ | 6 200$ | 70 400$ |
| 130 801$ | 133 800$ | 6 300$ | 71 900$ |
| 133 801$ | 136 800$ | 6 400$ | 73 400$ |
| 136 801$ | 139 800$ | 6 500$ | 74 900$ |
| 139 801$ | 142 800$ | 6 600$ | 76 400$ |
| 142 801$ | 145 800$ | 6 700$ | 77 900$ |
| 145 801$ | 148 800$ | 6 800$ | 79 400$ |
| 148 801$ | 151 800$ | 6 900$ | 80 900$ |
| 151 801$ | 154 800$ | 7 000$ | 82 400$ |
| 154 801$ | 157 800$ | 7 100$ | 83 900$ |
| 157 801$ | 160 800$ | 7 200$ | 85 400$ |
| 160 801$ | 163 800$ | 7 300$ | 86 900$ |
| 163 801$ | 166 800$ | 7 400$ | 88 400$ |
| 166 801$ | 174 231$ | 7 500$ | 92 100$ |
| 174 232$ | 176 538$ | 7 600$ | 93 250$ |
| 176 539$ | 178 846$ | 7 700$ | 94 400$ |
| 178 847$ | 181 154$ | 7 800$ | 95 600$ |
| 181 155$ | 183 461$ | 7 900$ | 96 750$ |
| 183 462$ | 185 769$ | 8 000$ | 97 900$ |
| 185 770$ | 195 600$ | 8 100$ | 102 800$ |
| 195 601$ | 198 000$ | 8 200$ | 104 000$ |
| 198 001$ | 200 400$ | 8 300$ | 105 200$ |
| 200 401$ | 202 800$ | 8 400$ | 106 400$ |
| 202 801$ | 205 200$ | 8 500$ | 107 600$ |
| 205 201$ | 216 250$ | 8 600$ | 113 100$ |
| 216 251$ | 218 750$ | 8 700$ | 114 350$ |
| 218 751$ | 221 250$ | 8 800$ | 115 600$ |
| 221 251$ | 223 750$ | 8 900$ | 116 850$ |
| 223 751$ | 226 250$ | 9 000$ | 118 100$ |
| 226 251$ | 238 695$ | 9 100$ | 124 350$ |
| 238 696$ | 241 304$ | 9 200$ | 125 650$ |
| 241 305$ | 243 913$ | 9 300$ | 126 950$ |
| 243 914$ | 246 521$ | 9 400$ | 128 250$ |
| 246 522$ | 249 130$ | 9 500$ | 129 550$ |
| 249 131$ | 251 739$ | 9 600$ | 130 850$ |
| 251 740$ | 254 348$ | 9 700$ | 132 150$ |
| 254 349$ | 256 956$ | 9 800$ | 133 500$ |
| 256 957$ | 271 363$ | 9 900$ | 140 700$ |
| 271 364$ | 274 091$ | 10 000$ | 142 050$ |
| 274 092$ | 276 818$ | 10 100$ | 143 400$ |
| 276 819$ | 279 545$ | 10 200$ | 144 750$ |
| 279 546$ | 282 272$ | 10 300$ | 146 150$ |
| 282 273$ | 285 000$ | 10 400$ | 147 500$ |
| 285 001$ | 301 428$ | 10 500$ | 155 700$ |
| 301 429$ | 304 285$ | 10 600$ | 157 150$ |
| 304 286$ | 307 143$ | 10 700$ | 158 550$ |
| 307 144$ | 310 000$ | 10 800$ | 160 000$ |
| 310 001$ | 312 857$ | 10 900$ | 161 450$ |
| 312 858$ | 315 714$ | 11 000$ | 162 850$ |
| 315 715$ | 326 341$ | 11 100$ | 168 150$ |
| 326 342$ | 329 268$ | 11 200$ | 169 650$ |
| 329 269$ | 332 195$ | 11 300$ | 171 100$ |
| 332 196$ | 335 122$ | 11 400$ | 172 550$ |
| 335 123$ | 338 048$ | 11 500$ | 174 000$ |
| 338 049$ | 349 500$ | 11 600$ | 179 750$ |
| 349 501$ | 352 500$ | 11 700$ | 181 250$ |
| 352 501$ | 355 500$ | 11 800$ | 182 750$ |
| 355 501$ | 358 500$ | 11 900$ | 184 250$ |
| 358 501$ | 370 769$ | 12 000$ | 190 400$ |
| 370 770$ | 373 846$ | 12 100$ | 191 900$ |
| 373 847$ | 376 923$ | 12 200$ | 193 450$ |
| 376 924$ | 380 000$ | 12 300$ | 195 000$ |
| 380 001$ | 383 077$ | 12 400$ | 196 550$ |
| 383 078$ | 396 315$ | 12 500$ | 203 150$ |
| 396 316$ | 410 270$ | 12 600$ | 210 150$ |
| 410 271$ | 413 513$ | 12 700$ | 211 750$ |
| 413 514$ | 416 756$ | 12 800$ | 213 400$ |
| 416 757$ | 420 000$ | 12 900$ | 215 000$ |
| 420 001$ | 423 243$ | 13 000$ | 216 600$ |
| 423 244$ | 426 486$ | 13 100$ | 218 250$ |
| 426 487$ | 429 729$ | 13 200$ | 219 850$ |
| 429 730$ | 432 973$ | 13 300$ | 221 500$ |
| 432 974$ | 436 216$ | 13 400$ | 223 100$ |
| 436 217$ | 439 459$ | 13 500$ | 224 750$ |
| 439 460$ | 455 000$ | 13 600$ | 232 500$ |
| 455 001$ | 458 333$ | 13 700$ | 234 150$ |
| 458 334$ | 461 666$ | 13 800$ | 235 850$ |
| 461 667$ | 465 000$ | 13 900$ | 237 500$ |
| 465 001$ | 468 333$ | 14 000$ | 239 150$ |
| 468 334$ | 471 666$ | 14 100$ | 240 850$ |
| 471 667$ | 475 000$ | 14 200$ | 242 500$ |
| 475 001$ | 478 333$ | 14 300$ | 244 150$ |
| 478 334$ | 481 666$ | 14 400$ | 245 850$ |
| 481 667$ | 485 000$ | 14 500$ | 247 500$ |
| 485 001$ | 502 285$ | 14 600$ | 256 150$ |
| 502 286$ | 505 714$ | 14 700$ | 257 850$ |
| 505 715$ | 509 143$ | 14 800$ | 259 550$ |
| 509 144$ | 512 571$ | 14 900$ | 261 300$ |
| 512 572$ | 516 000$ | 15 000$ | 263 000$ |
| 516 001$ | 519 428$ | 15 100$ | 264 700$ |
| 519 429$ | 538 235$ | 15 200$ | 274 100$ |
| 538 236$ | 541 764$ | 15 300$ | 275 900$ |
| 541 765$ | 545 294$ | 15 400$ | 277 650$ |
| 545 295$ | 565 454$ | 15 500$ | 287 750$ |
| 565 455$ | 569 091$ | 15 600$ | 289 550$ |
| 569 092$ | 572 727$ | 15 700$ | 291 350$ |
| 572 728$ | 576 363$ | 15 800$ | 293 200$ |
| 576 364$ | 580 000$ | 15 900$ | 295 000$ |
| 580 001$ | 583 636$ | 16 000$ | 296 800$ |
| 583 637$ | 587 272$ | 16 100$ | 298 650$ |
| 587 273$ | 590 909$ | 16 200$ | 300 450$ |
| 590 910$ | 594 545$ | 16 300$ | 302 250$ |
| 594 546$ | 598 181$ | 16 400$ | 304 100$ |
| 598 182$ | 601 818$ | 16 500$ | 305 900$ |
| 601 819$ | 605 454$ | 16 600$ | 307 750$ |
| 605 455$ | 609 091$ | 16 700$ | 309 550$ |
| 609 092$ | 612 727$ | 16 800$ | 311 350$ |
| 612 728$ | 616 363$ | 16 900$ | 313 200$ |
| 616 364$ | 620 000$ | 17 000$ | 315 000$ |
| 620 001$ | 623 636$ | 17 100$ | 316 800$ |
| 623 637$ | 627 272$ | 17 200$ | 318 650$ |
| 627 273$ | 630 909$ | 17 300$ | 320 450$ |
| 630 910$ | 634 545$ | 17 400$ | 322 250$ |
| 634 546$ | 638 181$ | 17 500$ | 324 100$ |
| 638 182$ | 641 818$ | 17 600$ | 325 900$ |
| 641 819$ | 645 454$ | 17 700$ | 327 750$ |
| 645 455$ | 649 091$ | 17 800$ | 329 550$ |
| 649 092$ | 652 727$ | 17 900$ | 331 350$ |
| 652 728$ | 656 363$ | 18 000$ | 333 200$ |
| 656 364$ | 660 000$ | 18 100$ | 335 000$ |
| 660 001$ | 663 636$ | 18 200$ | 336 800$ |
| 663 637$ | 667 272$ | 18 300$ | 338 650$ |
| 667 273$ | 670 909$ | 18 400$ | 340 450$ |
| 670 910$ | 674 545$ | 18 500$ | 342 250$ |
| 674 546$ | 678 181$ | 18 600$ | 344 100$ |
| 678 182$ | 681 818$ | 18 700$ | 345 900$ |
| 681 819$ | 685 454$ | 18 800$ | 347 750$ |
| 685 455$ | 689 091$ | 18 900$ | 349 550$ |
| 689 092$ | 692 727$ | 19 000$ | 351 350$ |
| 692 728$ | 696 363$ | 19 100$ | 353 200$ |
| 696 364$ | 700 000$ | 19 200$ | 355 000$ |
| 700 001$ | 703 636$ | 19 300$ | 356 800$ |
| 703 637$ | 707 272$ | 19 400$ | 358 650$ |
| 707 273$ | 710 909$ | 19 500$ | 360 450$ |
| 710 910$ | 714 545$ | 19 600$ | 362 250$ |
| 714 546$ | 718 181$ | 19 700$ | 364 100$ |
| 718 182$ | 721 818$ | 19 800$ | 365 900$ |
| 721 819$ | 725 454$ | 19 900$ | 367 750$ |
| 725 455$ | 729 091$ | 20 000$ | 369 550$ |
| 729 092$ | 732 727$ | 20 000$ | 371 350$ |

### Note importante
La définition d'invalidité totale est remplacée par celle visant la profession jugée raisonnable lorsque des prestations ont été versées pendant 36 mois. Une profession jugée raisonnable en est une qui permettrait au client de gagner, de façon raisonnable, un revenu annuel égal ou supérieur au revenu de la profession jugée raisonnable comme il est indiqué ci-dessus.

---

## Tableau de détermination des prestations imposables

### Pour les régimes d'indemnités pour perte de salaire (RIPS)

*La limite de souscription imposable maximale des personnes des catégories 3, 4, 5 et 6 s'élève à 6 500$ et la limite de participation imposable pour ces classes est de 12 000$.*

*La limite de souscription imposable maximale des personnes des catégories 1 et 2 s'élève à 8 500$ et la limite de participation imposable pour ces classes est de 36 000$.*

| Revenu annuel assurable | | Prestation mensuelle maximale admissible | Revenu de la profession jugée raisonnable (annuel) |
|-------------------------|---|-------------------------------------------|-----------------------------------------------------|
| **De** | **À** | | |
| – | 7 400$ | – | |
| 7 401$ | 8 800$ | 500$ | 5 280$ |
| 8 801$ | 10 400$ | 600$ | 6 240$ |
| 10 401$ | 12 000$ | 700$ | 7 200$ |
| 12 001$ | 13 600$ | 800$ | 8 160$ |
| 13 601$ | 15 200$ | 900$ | 9 120$ |
| 15 201$ | 16 800$ | 1 100$ | 10 080$ |
| 16 801$ | 18 400$ | 1 200$ | 11 040$ |
| 18 401$ | 20 000$ | 1 300$ | 12 000$ |
| 20 001$ | 21 600$ | 1 400$ | 12 960$ |
| 21 601$ | 23 200$ | 1 600$ | 13 920$ |

---

## Ajout de la couverture en cas de maladie

### À la couverture en cas de blessure

Les clients qui souhaitent ajouter la couverture en cas de maladie à la couverture en cas de blessure doivent répondre aux critères en matière de tarification.

### Détermination de la prime mensuelle

La prime mensuelle pour la couverture en cas de maladie est déterminée en fonction de l'âge du client et du montant de couverture demandé.

---

## Avenant d'assurance décès et mutilation accidentels

### Couverture supplémentaire

Cet avenant offre une protection supplémentaire en cas de décès ou de mutilation accidentels.

### Prime supplémentaire

Cette option est offerte moyennant le paiement d'une prime supplémentaire.

---

## Frais généraux d'entreprise

### Couverture des frais d'exploitation

Cette couverture protège les frais d'exploitation fixes d'une entreprise en cas d'invalidité du propriétaire.

### Détermination de la couverture mensuelle

La couverture mensuelle pour les frais généraux d'entreprise est déterminée en fonction des frais d'exploitation fixes de l'entreprise.

---

## Perte de revenu - Tableaux des primes

### Couvertures en cas de blessure et de maladie

Les tableaux des primes pour la perte de revenu sont organisés par catégorie professionnelle, type de couverture, période d'indemnisation et délai de carence.

---

## Tableaux des primes Frais généraux d'entreprise

### Couverture des frais d'exploitation

Les tableaux des primes pour les frais généraux d'entreprise sont organisés par catégorie professionnelle et montant de couverture.

---

## Catégories professionnelles

### Classification des professions

Les professions sont classées en catégories selon le niveau de risque associé à chaque profession.

#### Catégories 1 et 2
- Professions à faible risque
- Limite de souscription maximale : 6 000$
- Limite de participation : 20 000$

#### Catégories 3, 4, 5 et 6
- Professions à risque plus élevé
- Limite de souscription maximale : 5 000$
- Limite de participation : 8 000$

### Consultation des catégories

Pour déterminer la catégorie professionnelle d'un client, consultez le tableau des catégories professionnelles du présent guide. Si vous ne trouvez pas sa catégorie professionnelle dans la liste, veuillez communiquer avec le premier conseiller à la vente de RBC®.

---

## Points clés à retenir

### Caractéristiques du produit
- **Produit simplifié** : Structure et processus d'établissement simplifiés
- **Protection du revenu** : Calcul basé sur le revenu d'emploi, d'entreprise ou brut
- **Renouvellement garanti** : Blessure jusqu'à 75 ans, maladie jusqu'à 70 ans
- **Garanties spéciales** : Aide au retour au travail, remboursement frais médicaux

### Types de couverture
- **Perte de revenu** : Blessure et maladie
- **Frais généraux d'entreprise** : Frais d'exploitation fixes
- **Protection non liée à la profession** : Blessures non liées au travail
- **Couverture 24 heures sur 24** : Blessures liées et non liées au travail

### Limites de souscription
- **Catégories 1 et 2** : 6 000$ maximum, participation 20 000$
- **Catégories 3, 4, 5 et 6** : 5 000$ maximum, participation 8 000$
- **RIPS** : Limites imposables plus élevées

### Calcul des revenus
- **Revenu d'emploi** : Salaire, traitement, commissions, honoraires, bonis
- **Revenu d'entreprise** : Bénéfices ou pertes d'entreprise
- **Chiffre d'affaires brut** : 50% du chiffre d'affaires brut
- **Exclusions** : Revenus de placement, dividendes, intérêts, etc.

### Périodes d'indemnisation
- **5 ans** : Période déterminée
- **Jusqu'à 70 ans** : Période indéterminée
- **Fin de période** : Plus rapprochée des dates spécifiées

### Délais de carence
- **Aucun** : Prestations immédiates
- **30 jours** : Délai de carence court
- **90 jours** : Délai de carence moyen
- **120 jours** : Délai de carence long

### Exigences médicales
- **18-50 ans** : Non médical pour couverture maladie
- **51-64 ans** : Test sanguin, test d'urine et examen paramédical si > 3 000$/mois
- **Tableau taille/poids** : Admissibilité selon poids et taille

### Preuve de revenu
- **Documents requis** : T1, états vérifiés, T4, renseignements de tiers
- **Calcul des prestations** : Moindre entre prestation souscrite et prestation maximale admissible

---

## Métadonnées pour indexation

**Mots-clés:** guide des taux, Série Fondamentale, assurance invalidité, RBC Assurance, protection du revenu, tarification simplifiée

**Types de couverture:** Perte de revenu, Frais généraux d'entreprise, Blessure, Maladie, Non liée à la profession, 24 heures sur 24

**Limites de souscription:** Catégories 1-2 (6 000$), Catégories 3-6 (5 000$), RIPS (8 500$), Participation (20 000$, 8 000$)

**Calcul des revenus:** Revenu d'emploi, Revenu d'entreprise, Chiffre d'affaires brut, 50% du chiffre d'affaires

**Périodes d'indemnisation:** 5 ans, Jusqu'à 70 ans, Fin de période, Plus rapprochée des dates

**Délais de carence:** Aucun, 30 jours, 90 jours, 120 jours, Prestations immédiates

**Exigences médicales:** Non médical (18-50 ans), Test sanguin (51-64 ans), Examen paramédical, Tableau taille/poids

**Garanties spéciales:** Aide au retour au travail, Remboursement frais médicaux, Décès et mutilation accidentels

**Catégories professionnelles:** Catégories 1-2, Catégories 3-6, Classification des professions, Niveau de risque

**Preuve de revenu:** T1, États vérifiés, T4, Renseignements de tiers, Documents requis

**Renouvellement:** Garanti, Blessure 75 ans, Maladie 70 ans, Modification par catégorie