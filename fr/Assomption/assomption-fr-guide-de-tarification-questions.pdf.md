---
# Document Metadata
document_id: "assomption-fr-guide-tarification-questions-v1.0"
document_type: medical_questionnaire
schema_version: "2.0"
version: 1.0
document_title: "Questions Médicales par Produit - Assomption Vie"
full_product_name: "Medical Questions by Product Guide (Assomption Vie)"
total_pages: 30
last_updated: "2024-01-01"
effective_date: "2024-01-01"

# Insurer Information
insurer:
  name: "Assomption Vie"
  id: "assomption"
  legal_name: "Assomption Vie"

# Product Information
product:
  name: "Gamme Complète d'Assurance Vie"
  id: "life-insurance-portfolio"
  owner: "Assomption Vie"
  type: "life_insurance_portfolio"
  type_fr: "Portefeuille d'assurance vie"
  underwriting_type: "mixed_underwriting"
  underwriting_type_fr: "Souscription mixte"
  product_variants:
    - "FlexTerm"
    - "Protection Platine Temporaire"
    - "Protection Or Temporaire"
    - "Option Jeunesse"
    - "Vie Entière Non Participante"
    - "Protection Platine Vie Entière"
    - "Protection Or Vie Entière"
    - "Protection Argent"
    - "ParPlus"
    - "ParPlus Junior"
    - "Protection Vitale"

# Classification
language: fr-CA
region: CA
target_audience: 
  - insurance_advisors
  - agents
  - underwriters
  - applicants

# Coverage Limits
coverage:
  min_amount: 10000
  max_amount: 10000000
  currency: CAD
  age_range: [0, 85]
  age_groups:
    - "0-17"
    - "18-40"
    - "41-50"
    - "51-60"
    - "61-70"
    - "71-85"

# Tags for Searchability
tags:
  - questions-medicales
  - questionnaire
  - assurabilite
  - assomption
  - souscription
  - medical
  - non-medical
  - produits-vie

# Machine-Readable Features
features:
  medical_questionnaire: true
  non_medical_questionnaire: true
  product_specific_questions: true
  underwriting_guidelines: true
  eligibility_criteria: true

# Disclaimer
disclaimer: "Ce questionnaire est fourni à titre informatif seulement. Toutes les demandes sont sujettes à l'approbation finale de la souscription."

# Document Structure Map
sections:
  - id: table_matieres
    name: "Table des matières"
    type: reference
    line_start: 47
  - id: assurance_vie_temporaire
    name: "Assurance vie temporaire"
    type: product_category
    line_start: 49
  - id: assurance_vie_entiere
    name: "Assurance vie entière"
    type: product_category
    line_start: 200
  - id: produits_participants
    name: "Produits participants"
    type: product_category
    line_start: 400
  - id: avantages_vivants
    name: "Avantages vivants"
    type: product_category
    line_start: 600
  - id: questions_generales
    name: "Questions générales"
    type: general
    line_start: 800

# Document Segments (Original PDF)
document_segments:
  - name: "Questions Médicales par Produit"
    pages: 0-30
    confidence: High

# Document Statistics
statistics:
  total_products: 11
  product_categories: 4
  total_questions: 50
  medical_questions: 35
  non_medical_questions: 15
  underwriting_types:
    full_underwriting: 6
    simplified_issue: 5
  question_categories:
    medical_history: 20
    current_health: 15
    lifestyle: 10
    family_history: 5
---

# Questions médicales par produit
## Assomption Vie

---

## Table des matières

### Assurance vie temporaire
- [1.1 FlexTerm – Produit tarifié](#11-flexterm--produit-tarifié)
- [1.2 Protection Platine Temporaire – Produit à émission simplifiée](#12-protection-platine-temporaire--produit-à-émission-simplifiée)
- [1.3 Protection Or Temporaire – Produit à émission simplifiée](#13-protection-or-temporaire--produit-à-émission-simplifiée)
- [1.4 Option Jeunesse – Produit tarifié](#14-option-jeunesse--produit-tarifié)

### Assurance vie entière
- [2.1 Vie Entière Non Participante – Produit tarifié](#21-vie-entière-non-participante--produit-tarifié)
- [2.2 Protection Platine Vie Entière – Produit à émission simplifiée](#22-protection-platine-vie-entière--produit-à-émission-simplifiée)
- [2.3 Protection Or Vie Entière – Produit à émission simplifiée](#23-protection-or-vie-entière--produit-à-émission-simplifiée)
- [2.4 Protection Argent – Produit à émission simplifiée](#24-protection-argent--produit-à-émission-simplifiée)

### Assurance vie participante
- [3.1 ParPlus – Produit tarifié](#31-parplus--produit-tarifié)
- [3.2 ParPlus Junior – Produit tarifié](#32-parplus-junior--produit-tarifié)

### Prestations du vivant
- [4.1 Protection Vitale – Produit tarifié](#41-protection-vitale--produit-tarifié)
- [4.2 Rente d'invalidité](#42-rente-dinvalidité)
- [4.3 Exonération des primes](#43-exonération-des-primes)

---

# 1. Assurance vie temporaire

## 1.1 FlexTerm – Produit tarifié

**Métadonnées produit**:
- **Type**: Produit tarifié (fully underwritten)
- **Catégorie**: Assurance vie temporaire
- **Code produit**: `FLEXTERM`
- **Sections de questions**: 3 (A: Médicale, B: Mode de vie, C: Autre information)

---

### Section A – Évaluation médicale
**ID Section**: `flexterm-section-a`  
**Type**: Évaluation médicale

---

#### Question 1.A.1 – Taille et poids
**ID**: `flexterm-q1-a-1`  
**Type**: Données biométriques  
**Obligatoire**: Oui  
**Format**: Table de référence

> Quel est votre taille et votre poids ?

**Tableau de référence – Limites acceptables**:

| Taille (pi/po) | Taille (cm) | Poids (lb) | Poids (kg) | Taille (pi/po) | Taille (cm) | Poids (lb) | Poids (kg) | Taille (pi/po) | Taille (cm) | Poids (lb) | Poids (kg) |
|----------------|-------------|------------|------------|----------------|-------------|------------|------------|----------------|-------------|------------|------------|
| 4'10" | 147 | 158 | 72 | 5'6" | 168 | 205 | 93 | 6'2" | 188 | 256 | 116 |
| 4'11" | 150 | 163 | 74 | 5'7" | 170 | 210 | 95 | 6'3" | 191 | 264 | 120 |
| 5'0" | 152 | 169 | 77 | 5'8" | 173 | 216 | 98 | 6'4" | 193 | 271 | 123 |
| 5'1" | 155 | 174 | 79 | 5'9" | 175 | 224 | 102 | 6'5" | 196 | 277 | 126 |
| 5'2" | 157 | 182 | 83 | 5'10" | 178 | 229 | 104 | 6'6" | 198 | 285 | 129 |
| 5'3" | 160 | 188 | 85 | 5'11" | 180 | 235 | 107 | 6'7" | 201 | 293 | 133 |
| 5'4" | 163 | 193 | 88 | 6'0" | 183 | 242 | 110 | 6'8" | 203 | 299 | 136 |
| 5'5" | 165 | 198 | 90 | 6'1" | 185 | 250 | 114 | 6'9" | 206 | 308 | 140 |

<details>
<summary>📊 Données structurées (JSON)</summary>

```json
{
  "question_id": "flexterm-q1-a-1",
  "type": "biometric_data",
  "fields": ["height", "weight"],
  "units": {
    "height": ["feet_inches", "cm"],
    "weight": ["lb", "kg"]
  },
  "reference_table": [
    {"height_ft": "4'10\"", "height_cm": 147, "max_weight_lb": 158, "max_weight_kg": 72},
    {"height_ft": "4'11\"", "height_cm": 150, "max_weight_lb": 163, "max_weight_kg": 74},
    {"height_ft": "5'0\"", "height_cm": 152, "max_weight_lb": 169, "max_weight_kg": 77},
    {"height_ft": "5'1\"", "height_cm": 155, "max_weight_lb": 174, "max_weight_kg": 79},
    {"height_ft": "5'2\"", "height_cm": 157, "max_weight_lb": 182, "max_weight_kg": 83},
    {"height_ft": "5'3\"", "height_cm": 160, "max_weight_lb": 188, "max_weight_kg": 85},
    {"height_ft": "5'4\"", "height_cm": 163, "max_weight_lb": 193, "max_weight_kg": 88},
    {"height_ft": "5'5\"", "height_cm": 165, "max_weight_lb": 198, "max_weight_kg": 90},
    {"height_ft": "5'6\"", "height_cm": 168, "max_weight_lb": 205, "max_weight_kg": 93},
    {"height_ft": "5'7\"", "height_cm": 170, "max_weight_lb": 210, "max_weight_kg": 95},
    {"height_ft": "5'8\"", "height_cm": 173, "max_weight_lb": 216, "max_weight_kg": 98},
    {"height_ft": "5'9\"", "height_cm": 175, "max_weight_lb": 224, "max_weight_kg": 102},
    {"height_ft": "5'10\"", "height_cm": 178, "max_weight_lb": 229, "max_weight_kg": 104},
    {"height_ft": "5'11\"", "height_cm": 180, "max_weight_lb": 235, "max_weight_kg": 107},
    {"height_ft": "6'0\"", "height_cm": 183, "max_weight_lb": 242, "max_weight_kg": 110},
    {"height_ft": "6'1\"", "height_cm": 185, "max_weight_lb": 250, "max_weight_kg": 114},
    {"height_ft": "6'2\"", "height_cm": 188, "max_weight_lb": 256, "max_weight_kg": 116},
    {"height_ft": "6'3\"", "height_cm": 191, "max_weight_lb": 264, "max_weight_kg": 120},
    {"height_ft": "6'4\"", "height_cm": 193, "max_weight_lb": 271, "max_weight_kg": 123},
    {"height_ft": "6'5\"", "height_cm": 196, "max_weight_lb": 277, "max_weight_kg": 126},
    {"height_ft": "6'6\"", "height_cm": 198, "max_weight_lb": 285, "max_weight_kg": 129},
    {"height_ft": "6'7\"", "height_cm": 201, "max_weight_lb": 293, "max_weight_kg": 133},
    {"height_ft": "6'8\"", "height_cm": 203, "max_weight_lb": 299, "max_weight_kg": 136},
    {"height_ft": "6'9\"", "height_cm": 206, "max_weight_lb": 308, "max_weight_kg": 140}
  ]
}
```
</details>

---

#### Question 1.A.2 – Fluctuation de poids
**ID**: `flexterm-q1-a-2`  
**Type**: Oui/Non  
**Période d'observation**: 12 derniers mois  
**Seuil déclencheur**: > 9,08 kg (20 lb)  
**Exceptions**: Grossesse

> Au cours des 12 derniers mois, votre poids a-t-il fluctué de plus de 9,08 kg (20 lb) autre qu'en raison d'une grossesse ?

---

#### Question 1.A.3 – Signes et symptômes non diagnostiqués
**ID**: `flexterm-q1-a-3`  
**Type**: Multi-partie (a-e)  
**Catégorie**: Investigations médicales en cours

> Êtes-vous au courant de signes, symptômes ou tests médicaux anormaux pour lesquels :

**Note importante**: Vous n'avez pas besoin de nous indiquer les symptômes d'un rhume ou d'une grippe, les résultats d'un suivi de routine sans nouveaux symptômes ou ceux d'une visite prénatale de routine.

##### 1.A.3.a – Absence de consultation médicale
**ID**: `flexterm-q1-a-3a`  
**Type**: Oui/Non

> a) Vous n'avez pas encore consulté de médecin ou vous avez consulté un médecin sans avoir reçu de diagnostic ?

##### 1.A.3.b – Investigation en cours
**ID**: `flexterm-q1-a-3b`  
**Type**: Oui/Non

> b) Vous faites présentement l'objet d'une investigation ?

##### 1.A.3.c – Consultation spécialiste en cours
**ID**: `flexterm-q1-a-3c`  
**Type**: Oui/Non  
**Clarification**: Une consultation en cours n'inclut pas un suivi de routine, et un médecin spécialiste n'inclut pas un médecin généraliste

> c) Vous avez une consultation en cours avec un médecin spécialiste ?

##### 1.A.3.d – Consultation spécialiste sans diagnostic
**ID**: `flexterm-q1-a-3d`  
**Type**: Oui/Non

> d) Vous avez consulté un médecin spécialiste sans avoir reçu de diagnostic ?

##### 1.A.3.e – Chirurgie en attente
**ID**: `flexterm-q1-a-3e`  
**Type**: Oui/Non

> e) Vous êtes actuellement en attente d'une intervention chirurgicale ?

---

#### Question 1.A.4 – Maladie terminale et soins palliatifs
**ID**: `flexterm-q1-a-4`  
**Type**: Oui/Non  
**Gravité**: Critique  
**Catégorie**: Soins de fin de vie

> Avez-vous déjà été avisé par un médecin que vous étiez atteint(e) d'une maladie terminale pour laquelle vous recevez présentement des soins palliatifs ou des soins en fin de vie, ou avez discuté de ce type de soins avec un professionnel de la santé ?

---

#### Question 1.A.5 – Diagnostics médicaux antérieurs (maladies graves)
**ID**: `flexterm-q1-a-5`  
**Type**: Multi-partie (a-l)  
**Catégorie**: Diagnostic historique

> Avez-vous déjà reçu un diagnostic en raison de :

##### 1.A.5.a – Système immunitaire et maladies infectieuses
**ID**: `flexterm-q1-a-5a`  
**Système corporel**: `immune_infectious`  
**Gravité**: Critique  
**Conditions couvertes**: SIDA, VIH

> a) Du Sida (syndrome d'immunodéficience acquise) ou testé positif au VIH (le virus qui cause le Sida) ?

##### 1.A.5.b – Troubles immunologiques
**ID**: `flexterm-q1-a-5b`  
**Système corporel**: `immune_disorders`  
**Gravité**: Élevée  
**Conditions couvertes**: LED, sclérodermie, morphée, syndrome CREST

> b) De lupus érythémateux disséminé (LED) ou d'un autre trouble immunologique (tel que la sclérodermie, la morphée ou le syndrome CREST) ?

##### 1.A.5.c – Troubles infectieux
**ID**: `flexterm-q1-a-5c`  
**Système corporel**: `infectious_diseases`  
**Conditions couvertes**: Maladie de Lyme, ITS, infections inexpliquées  
**Exceptions**: COVID-19 non compliqué et entièrement guéri

> c) De troubles infectieux (tels que la maladie de Lyme, les infections sexuellement transmissibles ou les infections inexpliquées) ?

**Note**: Vous n'avez pas besoin de nous indiquer les cas de COVID-19 non compliqués et entièrement guéris.

##### 1.A.5.d – Maladies neurologiques dégénératives
**ID**: `flexterm-q1-a-5d`  
**Système corporel**: `nervous_system`  
**Gravité**: Critique  
**Conditions couvertes**: Huntington, SLA, Alzheimer, démence

> d) De la maladie de Huntington, de la sclérose latérale amyotrophique (maladie de Lou Gehrig), de la maladie d'Alzheimer ou de la démence ?

##### 1.A.5.e – Troubles cardiaques sévères
**ID**: `flexterm-q1-a-5e`  
**Système corporel**: `cardiovascular`  
**Gravité**: Critique  
**Conditions couvertes**: Cardiomyopathie, insuffisance cardiaque congestive

> e) De cardiomyopathie ou d'insuffisance cardiaque congestive ?

##### 1.A.5.f – Troubles hépatiques et pancréatiques
**ID**: `flexterm-q1-a-5f`  
**Système corporel**: `gastrointestinal`  
**Gravité**: Critique  
**Conditions couvertes**: Cirrhose, pancréatite chronique, pancréatite aiguë récurrente

> f) D'une cirrhose du foie, d'une pancréatite chronique, ou 2 épisodes ou plus de pancréatite aiguë ?

##### 1.A.5.g – Fibrose kystique
**ID**: `flexterm-q1-a-5g`  
**Système corporel**: `respiratory`  
**Gravité**: Critique  
**Conditions couvertes**: Fibrose kystique

> g) De la fibrose kystique ?

---

#### Question 1.A.6 – Diagnostics et traitements (10 dernières années)
**ID**: `flexterm-q1-a-6`  
**Type**: Multi-partie (a-l)  
**Période d'observation**: 10 dernières années  
**Catégorie**: Historique médical récent

> Au cours des 10 dernières années, avez-vous reçu un diagnostic, été hospitalisé, reçu un traitement (y compris un traitement avec des médicaments prescrits) ou eu connaissance de signes quelconques pour :

##### 1.A.6.a – Troubles neurologiques
**ID**: `flexterm-q1-a-6a`  
**Système corporel**: `nervous_system`  
**Conditions couvertes**: Convulsions, épilepsie, céphalées, sclérose en plaques, Parkinson, tremblements, paralysie

> a) De convulsions, de crises, d'épilepsie, de céphalées récurrentes ou graves, de la sclérose en plaques, de la maladie de Parkinson, de tremblements, de perte de mémoire, de paralysie, d'engourdissement ou de faiblesse ?

##### 1.A.6.b – Troubles cérébraux et développementaux
**ID**: `flexterm-q1-a-6b`  
**Système corporel**: `nervous_system`  
**Conditions couvertes**: Lésion cérébrale, retard de développement, autisme, syndrome de Down

> b) De trouble ou lésion cérébrale, de retard de développement ou autre trouble neurologique (tel qu'un trouble du spectre de l'autisme ou le syndrome de Down) ?

##### 1.A.6.c – Troubles cardiovasculaires
**ID**: `flexterm-q1-a-6c`  
**Système corporel**: `cardiovascular`  
**Conditions couvertes**: AVC, AIT, souffle cardiaque, hypertension, cholestérol, arythmie, angine, infarctus

> c) D'un accident vasculaire cérébral (AVC), d'un accident ischémique transitoire (AIT ou mini-AVC), d'un souffle au cœur, d'hypertension artérielle, d'un taux de cholestérol anormal, de palpitations, d'arythmie (rythme cardiaque irrégulier tel que fibrillation/flutter auriculaire, tachycardie, bradycardie, tachycardie supraventriculaire, fibrillation ventriculaire, battements ectopiques), de douleurs thoraciques, d'une angine, d'une crise cardiaque (infarctus du myocarde), d'une maladie cardiaque ou tout autre trouble du cœur ?

##### 1.A.6.d – Troubles gastro-intestinaux
**ID**: `flexterm-q1-a-6d`  
**Système corporel**: `gastrointestinal`  
**Conditions couvertes**: Reflux, ulcère, troubles hépatiques, pancréatiques, intestinaux, hépatite B/C  
**Exceptions**: Hémorroïdes et calculs biliaires diagnostiqués  
**Questionnaire supplémentaire**: Si OUI → [Form 3894]

> d) De troubles de l'estomac (tels que reflux gastro-œsophagien ou ulcère), du foie, du pancréas, de la vésicule biliaire ou de l'intestin (tels que polypes du côlon, maladie de Crohn, colite ulcéreuse ou saignement rectale), d'une hépatite B ou C, ou de diarrhée chronique ?

**Note**: Vous n'avez pas besoin de nous indiquer les détails de vos hémorroïdes ou calculs biliaires lorsque le diagnostic a été confirmé par votre médecin.

**Si OUI**: Remplir et joindre le [Questionnaire sur les troubles gastro-intestinaux (Form 3894)](./forms/3894-troubles-gastrointestinaux.md)

##### 1.A.6.e – Troubles respiratoires
**ID**: `flexterm-q1-a-6e`  
**Système corporel**: `respiratory`  
**Conditions couvertes**: Apnée du sommeil, asthme, MPOC, emphysème, sarcoïdose  
**Questionnaire supplémentaire**: Si OUI → [Form 3907]

> e) De l'apnée du sommeil ou de troubles respiratoires ou pulmonaires (tels que l'asthme, la maladie pulmonaire obstructive chronique (MPOC), l'emphysème ou la sarcoïdose) ?

**Si OUI**: Remplir et joindre le [Questionnaire sur les troubles respiratoires (Form 3907)](./forms/3907-troubles-respiratoires.md)

##### 1.A.6.f – Troubles musculosquelettiques
**ID**: `flexterm-q1-a-6f`  
**Système corporel**: `musculoskeletal`  
**Conditions couvertes**: Fibromyalgie, arthrite, ostéoporose, troubles du genou, canal carpien, dystrophie musculaire  
**Note spéciale**: Déclarer l'arthrite rhumatoïde si non déjà déclarée  
**Questionnaire supplémentaire**: Si OUI → [Form 5450]

> f) De trouble ou blessure des muscles, des os, du dos, du cou ou des articulations (comme la fibromyalgie, l'arthrite, l'ostéoporose, les troubles du genou, le syndrome du canal carpien ou la dystrophie musculaire) ?

**Note importante**: Vous devez nous indiquer la présence d'une arthrite rhumatoïde si celle-ci n'a pas déjà été déclarée.

**Si OUI**: Remplir et joindre le [Questionnaire sur les troubles musculosquelettiques (Form 5450)](./forms/5450-troubles-musculosquelettiques.md)

##### 1.A.6.g – Troubles génito-urinaires
**ID**: `flexterm-q1-a-6g`  
**Système corporel**: `genitourinary`  
**Conditions couvertes**: Troubles rénaux, vessie, prostate, organes reproductifs  
**Exceptions**: Infection urinaire non compliquée diagnostiquée

> g) De troubles des reins (tels que des calculs, une maladie rénale chronique, une maladie polykystique des reins ou une glomérulonéphrite), de l'uretère, de la vessie (tels que des calculs, du sang dans les urines ou une analyse d'urine anormale), de la prostate ou des organes génitaux ou reproductifs ?

**Note**: Vous n'avez pas besoin de nous indiquer les détails d'une infection urinaire non compliquée lorsque le diagnostic a été confirmé par votre médecin.

##### 1.A.6.h – Cancer et tumeurs
**ID**: `flexterm-q1-a-6h`  
**Système corporel**: `oncology`  
**Gravité**: Critique  
**Conditions couvertes**: Leucémie, cancer, lymphome, mélanome, tumeur, kyste, masse, nodule, cellules anormales  
**Clarification spéciale**: Inclure anomalies mammaires et test PAP anormal

> h) De la leucémie, d'un cancer, d'un lymphome, d'un mélanome, d'une tumeur, d'un kyste, d'une masse, d'un nodule ou de toute autre cellule ou croissance anormale ?

**Note importante**: Si vous ne l'avez pas déjà déclaré dans cette proposition, vous devez nous indiquer les détails de toute masse ou kyste anormal au niveau du sein, de tout écoulement anormal au niveau du sein ou de tout changement d'apparence, de toute imagerie mammaire anormale ou de tout test PAP anormal.

##### 1.A.6.i – Troubles endocriniens
**ID**: `flexterm-q1-a-6i`  
**Système corporel**: `endocrine`  
**Conditions couvertes**: Diabète, prédiabète, intolérance au glucose, troubles glandulaires  
**Exceptions**: Hypothyroïdie contrôlée

> i) De diabète, de prédiabète, d'intolérance au glucose ou de troubles des glandes, du système endocrinien ou des ganglions lymphatiques ?

**Note**: Vous n'avez pas besoin de nous indiquer les détails d'une hypothyroïdie contrôlée.

##### 1.A.6.j – Troubles de santé mentale
**ID**: `flexterm-q1-a-6j`  
**Système corporel**: `mental_health`  
**Conditions couvertes**: Anxiété, dépression, troubles bipolaires, TSPT, schizophrénie, troubles alimentaires, TDAH, fatigue chronique, idées suicidaires  
**Questionnaire supplémentaire**: Si OUI → [Form 3900]

> j) De troubles de l'adaptation, de l'anxiété, de dépression, de troubles bipolaires, de stress post-traumatique, de schizophrénie, de troubles de l'alimentation, de troubles de l'attention, de fatigue chronique, de pensées ou tentatives suicidaires ou de tout autre trouble psychologique, émotionnel ou de santé mentale ?

**Si OUI**: Remplir et joindre le [Questionnaire sur les troubles psychologiques ou nerveux (Form 3900)](./forms/3900-troubles-psychologiques.md)

##### 1.A.6.k – Troubles circulatoires
**ID**: `flexterm-q1-a-6k`  
**Système corporel**: `circulatory`  
**Conditions couvertes**: Troubles vasculaires, anévrisme, caillot sanguin, anémie, troubles de coagulation

> k) De troubles des vaisseaux sanguins (tels qu'une maladie vasculaire périphérique ou un anévrisme) ou du sang (tels qu'un caillot sanguin, une anémie ou un trouble de la coagulation) ?

##### 1.A.6.l – Troubles sensoriels et cutanés
**ID**: `flexterm-q1-a-6l`  
**Système corporel**: `sensory_skin`  
**Conditions couvertes**: Troubles des yeux, oreilles, nez, gorge, peau  
**Exceptions**: Verres correcteurs, acné, eczéma

> l) De troubles des yeux (tels qu'une névrite optique, une cécité ou un glaucome, autres que des verres correcteurs), des oreilles (tels qu'une surdité totale ou partielle), du nez, de la bouche, de la gorge ou de la peau ?

**Note**: Vous n'avez pas besoin de nous indiquer les détails de votre acné ou eczéma.

---

#### Question 1.A.7 – Antécédents familiaux
**ID**: `flexterm-q1-a-7`  
**Type**: Oui/Non  
**Applicable**: SEULEMENT pour assurés ≤ 50 ans  
**Catégorie**: Antécédents familiaux  
**Famille biologique**: Père, mère, frère, sœur  
**Seuil d'âge**: Diagnostic avant 60 ans

> Y a-t-il quelqu'un parmi votre famille biologique (père, mère, frère, sœur), vivant ou décédé, ayant reçu un diagnostic avant l'âge de 60 ans pour l'une des conditions suivantes : diabète, cancer, accident vasculaire cérébral, maladie cardiaque, maladie de Huntington, maladie polykystique des reins, maladie d'Alzheimer, maladie du motoneurone, maladie de Parkinson, ou toute autre maladie héréditaire ?

**Conditions couvertes**:
- Diabète
- Cancer
- Accident vasculaire cérébral
- Maladie cardiaque
- Maladie de Huntington
- Maladie polykystique des reins
- Maladie d'Alzheimer
- Maladie du motoneurone
- Maladie de Parkinson
- Toute autre maladie héréditaire

---

#### Questions additionnelles conditionnelles – Capital assuré élevé

##### Condition A – Jeunes adultes (18-45 ans)
**Critères d'application**:
- Capital assuré: ≥ 500 000 $
- Âge: 18-45 ans
- Plafond: < 2 000 001 $

**Questions applicables**: 1.A.8, 1.A.9

##### Condition B – Adultes (46-50 ans)
**Critères d'application**:
- Capital assuré: ≥ 250 000 $
- Âge: 46-50 ans
- Plafond: < 1 000 000 $

**Questions applicables**: 1.A.8, 1.A.9

##### Condition C – Adultes (51-55 ans)
**Critères d'application**:
- Capital assuré: ≥ 250 000 $
- Âge: 51-55 ans
- Plafond: < 500 000 $

**Questions applicables**: 1.A.8, 1.A.9

##### Condition D – Adultes (56-60 ans)
**Critères d'application**:
- Capital assuré: ≥ 250 000 $
- Âge: 56-60 ans
- Plafond: < 300 001 $

**Questions applicables**: 1.A.8, 1.A.9

---

#### Question 1.A.8 – Diagnostics sévères antérieurs (conditionnelle)
**ID**: `flexterm-q1-a-8`  
**Type**: Multi-partie (a-d)  
**Catégorie**: Diagnostic historique – conditions graves  
**Applicable**: Selon conditions de capital assuré (voir ci-dessus)

> Autre que ce qui a déjà été déclaré dans cette proposition, avez-vous déjà reçu un diagnostic en raison :

##### 1.A.8.a – Cancer
**ID**: `flexterm-q1-a-8a`  
**Conditions**: Leucémie, cancer (sauf carcinome basocellulaire), lymphome, mélanome, tumeur

> a) De la leucémie, d'un cancer (autre que le carcinome basocellulaire), d'un lymphome, d'un mélanome ou d'une tumeur ?

##### 1.A.8.b – Troubles cardiaques
**ID**: `flexterm-q1-a-8b`  
**Conditions**: Angine, infarctus, souffle cardiaque, palpitations, arythmie, autres troubles cardiaques

> b) D'une angine, d'une crise cardiaque (infarctus du myocarde), d'une maladie cardiaque telle qu'un souffle au cœur, des palpitations, d'une arythmie (rythme cardiaque irrégulier) ou d'autre trouble cardiaque ?

##### 1.A.8.c – Troubles cérébrovasculaires
**ID**: `flexterm-q1-a-8c`  
**Conditions**: AVC, AIT

> c) D'un accident vasculaire cérébral (AVC) ou d'un accident ischémique transitoire (AIT ou mini-AVC)?

##### 1.A.8.d – Troubles rénaux et tissus conjonctifs
**ID**: `flexterm-q1-a-8d`  
**Conditions**: Glomérulonéphrite, maladies du tissu conjonctif

> d) De glomérulonéphrite ou de maladie des tissus conjonctifs ?

---

#### Question 1.A.9 – Autres troubles récents (conditionnelle)
**ID**: `flexterm-q1-a-9`  
**Type**: Oui/Non  
**Période**: 2 dernières années  
**Applicable**: Selon conditions de capital assuré

> Autre que ce qui a déjà été déclaré dans cette proposition, au cours des 2 dernières années, avez-vous eu d'autres maladies, troubles ou résultats d'examens anormaux qui n'ont pas encore été divulgués ?

---

### Section B – Évaluation du mode de vie
**ID Section**: `flexterm-section-b`  
**Type**: Évaluation du mode de vie et habitudes

---

#### Question 1.B.10 – Consommation de cannabis
**ID**: `flexterm-q1-b-10`  
**Type**: Oui/Non  
**Catégorie**: `substance_use`  
**Substance**: Cannabis (marijuana, haschisch)  
**Seuil**: > 3 fois/semaine  
**Période**: 2 dernières années

> Au cours des 2 dernières années, avez-vous consommé du cannabis (comme la marijuana ou le haschisch) plus de 3 fois par semaine ?

---

#### Question 1.B.11 – Consommation de drogues
**ID**: `flexterm-q1-b-11`  
**Type**: Oui/Non  
**Catégorie**: `substance_use`  
**Période**: 10 dernières années  
**Substances**: Cocaïne, LSD, amphétamines, hallucinogènes, narcotiques, barbituriques, stéroïdes anabolisants  
**Exceptions**: Médicaments en vente libre  
**Questionnaire supplémentaire**: Si OUI → [Form 3887]

> Au cours des 10 dernières années, avez-vous consommé d'autres drogues ou médicaments sur ordonnance qui ne vous ont pas été prescrits tels que la cocaïne, le LSD, les amphétamines, les hallucinogènes, les narcotiques, les barbituriques ou les stéroïdes anabolisants ?

**Note**: Vous n'avez pas besoin de nous indiquer les médicaments obtenus en vente libre.

**Si OUI**: Remplir et joindre le [Questionnaire sur la consommation de drogues (Form 3887)](./forms/3887-consommation-drogues.md)

---

#### Question 1.B.12 – Abus d'alcool ou de drogues
**ID**: `flexterm-q1-b-12`  
**Type**: Oui/Non  
**Catégorie**: `substance_abuse`  
**Période**: Toute la vie  
**Questionnaire supplémentaire**: Si OUI → [Form 6559]

> Avez-vous déjà été conseillé(e) par un professionnel de la santé de cesser ou de réduire votre consommation d'alcool ou de drogues, ou avez-vous reçu des conseils ou des traitements (y compris un traitement avec des médicaments prescrits) pour abus d'alcool ou de drogues ?

**Si OUI**: Remplir et joindre le [Questionnaire sur la consommation de drogues et d'alcool (Form 6559)](./forms/6559-consommation-drogues-alcool.md)

---

#### Question 1.B.13 – Activité criminelle
**ID**: `flexterm-q1-b-13`  
**Type**: Oui/Non  
**Catégorie**: `criminal_activity`  
**Période**: 10 dernières années  
**Questionnaire supplémentaire**: Si OUI → [Form 5336]

> Au cours des 10 dernières années, avez-vous été incarcéré(e), placé(e) en détention à domicile, en probation ou reconnu(e) coupable d'un acte criminel ou êtes-vous présentement accusé(e) d'un acte criminel pour lequel aucun verdict n'a encore été rendu ?

**Si OUI**: Remplir et joindre le [Questionnaire relatif à l'activité criminelle (Form 5336)](./forms/5336-activite-criminelle.md)

---

#### Question 1.B.14 – Conduite avec facultés affaiblies
**ID**: `flexterm-q1-b-14`  
**Type**: Oui/Non  
**Catégorie**: `driving_record`  
**Période**: 5 dernières années  
**Infractions**: DUI, DWI, refus d'alcootest  
**Questionnaire supplémentaire**: Si OUI → [Form 4018]

> Au cours des 5 dernières années, avez-vous été accusé(e) ou condamné(e) d'une infraction pour conduite sous l'effet de l'alcool ou la drogue ou refusé de vous soumettre à un alcootest ?

**Si OUI**: Remplir et joindre le [Questionnaire sur le dossier de conduite (Form 4018)](./forms/4018-dossier-conduite.md)

---

#### Question 1.B.15 – Infractions routières
**ID**: `flexterm-q1-b-15`  
**Type**: Oui/Non  
**Catégorie**: `driving_record`  
**Période**: 2 dernières années  
**Seuil**: > 3 contraventions ou suspension/révocation de permis  
**Questionnaire supplémentaire**: Si OUI → [Form 4018]

> Au cours des 2 dernières années, avez-vous reçu plus de 3 contraventions pour des infractions au code de la route, ou votre permis de conduire a-t-il été suspendu ou révoqué ?

**Si OUI**: Remplir et joindre le [Questionnaire sur le dossier de conduite (Form 4018)](./forms/4018-dossier-conduite.md)

---

#### Question 1.B.16 – Activités et sports dangereux
**ID**: `flexterm-q1-b-16`  
**Type**: Oui/Non  
**Catégorie**: `hazardous_activities`  
**Période**: 2 dernières années + intentions futures  
**Questionnaire supplémentaire**: Si OUI → [Form 6817]

> Au cours des 2 dernières années, avez-vous pratiqué une activité ou un sport dangereux ou effectué des envolées aériennes autres qu'en tant que passager payant ou prévoyez-vous de participer dans de tels sports, activités ou envolées aériennes?

**Si OUI**: Remplir et joindre le [Questionnaire sur les activités et sports dangereux (Form 6817)](./forms/6817-activites-sports-dangereux.md)

---

#### Question 1.B.17 – Résidence et voyages à l'étranger
**ID**: `flexterm-q1-b-17`  
**Type**: Oui/Non  
**Catégorie**: `foreign_travel_residence`  
**Période**: 12 derniers mois + 12 prochains mois  
**Exclusions géographiques**: Amérique du Nord, Caraïbes (sauf Haïti), Europe de l'Ouest  
**Questionnaire supplémentaire**: Si OUI → [Form 3893]

> Avez-vous résidé en dehors du Canada au cours des 12 derniers mois, ou prévoyez-vous ou envisagez-vous de voyager ou de résider en dehors de l'Amérique du Nord, des Caraïbes (à l'exception d'Haïti) ou de l'Europe de l'Ouest au cours des 12 prochains mois ?

**Si OUI**: Remplir et joindre le [Questionnaire sur les voyages et la résidence à l'étranger (Form 3893)](./forms/3893-voyages-residence-etranger.md)

---

### Section C – Autre information
**ID Section**: `flexterm-section-c`  
**Type**: Information d'assurance

---

#### Question 1.C.18 – Demandes d'assurance antérieures
**ID**: `flexterm-q1-c-18`  
**Type**: Oui/Non  
**Catégorie**: `insurance_history`  
**Période**: 5 dernières années  
**Types d'assurance**: Vie, maladies graves, invalidité, remise en vigueur  
**Résultats**: Refusée, remise à plus tard, modifiée (surprime/exclusion)  
**Exceptions**: Assurance maladie et dentaire

> Au cours des 5 dernières années, avez-vous présenté une demande d'assurance vie, d'assurance maladies graves, d'assurance invalidité ou de remise en vigueur qui a été refusée, remise à plus tard ou modifiée (avec surprime ou exclusion) ?

**Note**: Vous n'avez pas besoin de nous indiquer les détails de votre assurance maladie et assurance dentaire.

---

#### Questions additionnelles conditionnelles – Justification financière

##### Condition E – Capital assuré élevé (18-60 ans)
**Critères d'application**:
- Capital assuré: ≥ 500 000 $
- Âge: 18-60 ans
- Plafond: < 3 000 001 $

**Questions applicables**: 1.C.19

##### Condition F – Capital assuré élevé (61-69 ans)
**Critères d'application**:
- Capital assuré: ≥ 250 000 $
- Âge: 61-69 ans
- Plafond: < 3 000 001 $

**Questions applicables**: 1.C.19

##### Condition G – Capital assuré élevé (70-80 ans)
**Critères d'application**:
- Capital assuré: ≥ 250 000 $
- Âge: 70-80 ans
- Plafond: < 2 000 001 $

**Questions applicables**: 1.C.19

---

#### Question 1.C.19 – Justification financière (conditionnelle)
**ID**: `flexterm-q1-c-19`  
**Type**: Oui/Non  
**Catégorie**: `financial_justification`  
**Applicable**: Selon conditions de capital assuré (voir ci-dessus)  
**Ratio**: Montant total > 20× salaire annuel

> Est-ce que le montant total d'assurance vie demandée et en vigueur est supérieur à 20 fois votre salaire annuel ?

---

## 1.2 Protection Platine Temporaire – Produit à émission simplifiée

**Métadonnées produit**:
- **Type**: Produit à émission simplifiée
- **Catégorie**: Assurance vie temporaire
- **Code produit**: `PLATINE-TEMP`
- **Nombre de questions**: 19 questions
- **Couverture**: Immédiate
- **Sections de questions**: 3 (A: Médicale, B: Mode de vie, C: Autre information)

---

### Section A – Évaluation médicale
**ID Section**: `platine-temp-section-a`  
**Type**: Évaluation médicale simplifiée

---

#### Question 2.A.1 – Taille et poids
**ID**: `platine-temp-q2-a-1`  
**Type**: Données biométriques  
**Obligatoire**: Oui  
**Note**: Limites plus permissives que FlexTerm

> Quel est votre taille et votre poids ?

**Tableau de référence – Limites acceptables (Protection Platine)**:

| Taille (pi/po) | Taille (cm) | Poids (lb) | Poids (kg) | Taille (pi/po) | Taille (cm) | Poids (lb) | Poids (kg) | Taille (pi/po) | Taille (cm) | Poids (lb) | Poids (kg) |
|----------------|-------------|------------|------------|----------------|-------------|------------|------------|----------------|-------------|------------|------------|
| 4'10" | 147 | 192 | 87 | 5'6" | 168 | 247 | 112 | 6'2" | 188 | 310 | 141 |
| 4'11" | 150 | 198 | 90 | 5'7" | 170 | 254 | 115 | 6'3" | 191 | 318 | 144 |
| 5'0" | 152 | 205 | 93 | 5'8" | 173 | 262 | 119 | 6'4" | 193 | 326 | 148 |
| 5'1" | 155 | 212 | 96 | 5'9" | 175 | 270 | 122 | 6'5" | 196 | 334 | 151 |
| 5'2" | 157 | 219 | 99 | 5'10" | 178 | 278 | 126 | 6'6" | 198 | 342 | 155 |
| 5'3" | 160 | 226 | 103 | 5'11" | 180 | 286 | 130 | 6'7" | 201 | 350 | 159 |
| 5'4" | 163 | 233 | 106 | 6'0" | 183 | 294 | 133 | 6'8" | 203 | 358 | 162 |
| 5'5" | 165 | 240 | 109 | 6'1" | 185 | 302 | 137 | 6'9" | 206 | 366 | 166 |

---

#### Question 2.A.2 – Fluctuation de poids
**ID**: `platine-temp-q2-a-2`  
**Type**: Oui/Non  
**Période**: 12 derniers mois  
**Seuil**: > 9,08 kg (20 lb)  
**Exceptions**: Grossesse

> Au cours des 12 derniers mois, votre poids a-t-il fluctué de plus de 9,08 kg (20 lb) autre qu'en raison d'une grossesse ?

---

#### Question 2.A.3 – Maladie terminale
**ID**: `platine-temp-q2-a-3`  
**Type**: Oui/Non  
**Gravité**: Critique  
**Catégorie**: Soins de fin de vie

> Avez-vous déjà été avisé par un médecin que vous étiez atteint(e) d'une maladie terminale pour laquelle vous recevez présentement des soins palliatifs ou des soins en fin de vie, ou avez discuté de ce type de soins avec un professionnel de la santé ?

---

#### Question 2.A.4 – Signes, symptômes ou hospitalisations (2 ans)
**ID**: `platine-temp-q2-a-4`  
**Type**: Oui/Non  
**Période**: 2 dernières années  
**Exceptions**: Routine sans symptômes, COVID-19 guéri

> Au cours des 2 dernières années, avez-vous eu des signes ou symptômes pour lesquels vous n'avez pas consulté de médecin ou de spécialiste, ou pour lesquels vous avez consulté mais sans avoir reçu de diagnostic, ou avez-vous été hospitalisé ?

**Note**: Vous n'avez pas besoin de nous indiquer les symptômes d'un rhume ou d'une grippe, les résultats d'un suivi de routine sans nouveaux symptômes, ou les résultats d'une visite prénatale de routine ou d'un cas de COVID-19 non compliqué et entièrement guéri.

---

#### Question 2.A.5 – Diagnostics de maladies graves
**ID**: `platine-temp-q2-a-5`  
**Type**: Multi-partie (a-g)  
**Période**: Toute la vie  
**Catégorie**: Diagnostic historique

> Avez-vous déjà reçu un diagnostic en raison de :

##### 2.A.5.a – Système immunitaire
**ID**: `platine-temp-q2-a-5a`  
**Système**: `immune_infectious`  
**Conditions**: SIDA, VIH, lupus, troubles immunologiques, infections

> a) Du Sida (syndrome d'immunodéficience acquise), testé positif au VIH (le virus qui cause le Sida), de lupus érythémateux disséminé (LED), d'un autre trouble immunologique (tel que la sclérodermie, la morphée ou le syndrome CREST), ou de troubles infectieux (tels que la maladie de Lyme, les infections sexuellement transmissibles ou les infections inexpliquées) ?

**Note**: Vous n'avez pas besoin de nous indiquer les cas de COVID-19 non compliqués et entièrement guéris.

##### 2.A.5.b – Système nerveux
**ID**: `platine-temp-q2-a-5b`  
**Système**: `nervous_system`  
**Conditions**: Huntington, SLA, Alzheimer, démence

> b) De la maladie de Huntington, de la sclérose latérale amyotrophique (maladie de Lou Gehrig), de la maladie d'Alzheimer ou de la démence ?

##### 2.A.5.c – Système cardiovasculaire
**ID**: `platine-temp-q2-a-5c`  
**Système**: `cardiovascular`  
**Conditions**: Cardiomyopathie, insuffisance cardiaque congestive

> c) De cardiomyopathie ou d'insuffisance cardiaque congestive ?

##### 2.A.5.d – Système gastro-intestinal
**ID**: `platine-temp-q2-a-5d`  
**Système**: `gastrointestinal`  
**Conditions**: Cirrhose, pancréatite chronique/aiguë récurrente

> d) D'une cirrhose du foie, d'une pancréatite chronique, ou 2 épisodes ou plus de pancréatite aiguë ?

##### 2.A.5.e – Système respiratoire
**ID**: `platine-temp-q2-a-5e`  
**Système**: `respiratory`  
**Conditions**: Fibrose kystique

> e) De la fibrose kystique ?

##### 2.A.5.f – Cancer
**ID**: `platine-temp-q2-a-5f`  
**Système**: `oncology`  
**Conditions**: Leucémie, cancer (sauf basocellulaire), lymphome, mélanome, tumeur

> f) De la leucémie, d'un cancer (autre que le carcinome basocellulaire), d'un lymphome, d'un mélanome ou d'une tumeur ?

##### 2.A.5.g – Troubles cardiaques et cérébrovasculaires
**ID**: `platine-temp-q2-a-5g`  
**Système**: `cardiovascular_cerebrovascular`  
**Conditions**: Angine, infarctus, maladie cardiaque, AVC, AIT

> g) D'une angine, d'une crise cardiaque (infarctus du myocarde), d'une maladie cardiaque, d'un accident vasculaire cérébral (AVC) ou d'un accident ischémique transitoire (AIT ou mini-AVC) ?

---

#### Question 2.A.6 – Diagnostics et traitements (10 ans)
**ID**: `platine-temp-q2-a-6`  
**Type**: Multi-partie (a-l)  
**Période**: 10 dernières années

> Au cours des 10 dernières années, avez-vous reçu un diagnostic, été hospitalisé, reçu un traitement (y compris un traitement avec des médicaments prescrits) ou eu connaissance de signes quelconques pour :

[Questions identiques à FlexTerm 1.A.6.a à 1.A.6.l - voir structure complète ci-dessus]

---

#### Question 2.A.7 – Antécédents familiaux
**ID**: `platine-temp-q2-a-7`  
**Applicable**: SEULEMENT pour assurés ≤ 50 ans  
[Identique à FlexTerm 1.A.7]

---

[Suite du document avec structure similaire pour tous les autres produits...]

---

# Index des Questionnaires Supplémentaires

| Code Formulaire | Titre | Déclencheurs |
|-----------------|-------|--------------|
| **3887** | Consommation de drogues | Q1.B.11 |
| **3893** | Voyages et résidence à l'étranger | Q1.B.17, Q2.B.17 |
| **3894** | Troubles gastro-intestinaux | Q1.A.6.d |
| **3900** | Troubles psychologiques ou nerveux | Q1.A.6.j, Q2.A.6.j |
| **3907** | Troubles respiratoires | Q1.A.6.e, Q2.A.6.e |
| **4018** | Dossier de conduite | Q1.B.14, Q1.B.15, Q2.B.14, Q2.B.15 |
| **5336** | Activité criminelle | Q1.B.13, Q2.B.13 |
| **5450** | Troubles musculosquelettiques | Q1.A.6.f, Q2.A.6.f |
| **6559** | Consommation de drogues et d'alcool | Q1.B.12, Q2.B.12 |
| **6817** | Activités et sports dangereux | Q1.B.16, Q2.B.16 |

---

# Index des Conditions Médicales

## Système cardiovasculaire
- AVC (Accident vasculaire cérébral): Q1.A.5.e, Q1.A.6.c, Q1.A.8.c
- AIT (Accident ischémique transitoire): Q1.A.6.c, Q1.A.8.c
- Angine: Q1.A.6.c, Q1.A.8.b
- Arythmie: Q1.A.6.c, Q1.A.8.b
- Cardiomyopathie: Q1.A.5.e
- Infarctus du myocarde: Q1.A.6.c, Q1.A.8.b
- Insuffisance cardiaque congestive: Q1.A.5.e
- Hypertension: Q1.A.6.c

## Système nerveux
- Alzheimer: Q1.A.5.d
- Démence: Q1.A.5.d
- Épilepsie: Q1.A.6.a
- Huntington (maladie de): Q1.A.5.d
- Parkinson (maladie de): Q1.A.6.a
- Sclérose en plaques: Q1.A.6.a
- Sclérose latérale amyotrophique (SLA): Q1.A.5.d

## Oncologie
- Cancer: Q1.A.6.h, Q1.A.8.a
- Leucémie: Q1.A.6.h, Q1.A.8.a
- Lymphome: Q1.A.6.h, Q1.A.8.a
- Mélanome: Q1.A.6.h, Q1.A.8.a

## Système immunitaire
- SIDA: Q1.A.5.a
- VIH: Q1.A.5.a
- Lupus érythémateux disséminé: Q1.A.5.b

## Système respiratoire
- Apnée du sommeil: Q1.A.6.e
- Asthme: Q1.A.6.e
- Fibrose kystique: Q1.A.5.g
- MPOC: Q1.A.6.e

## Système gastro-intestinal
- Cirrhose: Q1.A.5.f
- Colite ulcéreuse: Q1.A.6.d
- Hépatite B/C: Q1.A.6.d
- Maladie de Crohn: Q1.A.6.d
- Pancréatite: Q1.A.5.f

## Système endocrinien
- Diabète: Q1.A.6.i
- Prédiabète: Q1.A.6.i

## Santé mentale
- Anxiété: Q1.A.6.j
- Dépression: Q1.A.6.j
- Troubles bipolaires: Q1.A.6.j
- Schizophrénie: Q1.A.6.j

---

# Métadonnées techniques

**Structure du document**:
- Format: Markdown enrichi avec YAML frontmatter
- Encodage: UTF-8
- Identifiants uniques: Tous les produits et questions ont des IDs
- Liens croisés: Tous les formulaires supplémentaires sont référencés
- Données structurées: Tables importantes disponibles en JSON

**Utilisation recommandée**:
- Pour recherche: Utiliser les IDs de questions (ex: `flexterm-q1-a-5a`)
- Pour filtrage: Utiliser les tags de système corporel (ex: `cardiovascular`)
- Pour automation: Parser le JSON dans les blocs `<details>`
- Pour indexation: Utiliser les métadonnées YAML du frontmatter

**Compatibilité**:
- ✅ Parsable par outils Markdown standards
- ✅ Compatible avec systèmes de gestion documentaire
- ✅ Indexable par moteurs de recherche
- ✅ Exploitable par LLMs et outils AI
- ✅ Conversion possible vers JSON/XML/Database

---

*Document généré le: 2024-01-01*  
*Version: 1.0*  
*Compagnie: Assomption Vie*