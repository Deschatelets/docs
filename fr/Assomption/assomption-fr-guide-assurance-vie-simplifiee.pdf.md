---
# Document Metadata
document_id: "assomption-fr-guide-assurance-vie-simplifiee-v1.0"
document_type: quick_reference_guide
schema_version: "2.0"
version: 1.0
document_title: "Guide de Référence Rapide - Solutions d'Assurance à Émission Simplifiée Assomption Vie"
full_product_name: "Quick Reference Guide for Simplified Life Insurance Solutions (Assomption Vie)"
total_pages: 25
last_updated: "2024"
effective_date: "2024-01-01"

# Insurer Information
insurer:
  name: "Assomption Vie"
  id: "assomption"
  legal_name: "Assomption Vie"

# Product Information
product:
  name: "Solutions à Émission Simplifiée"
  id: "simplified-life"
  owner: "Assomption Vie"
  type: "simplified_life_insurance"
  type_fr: "Assurance vie à émission simplifiée"
  underwriting_type: "simplified_underwriting"
  underwriting_type_fr: "Souscription simplifiée"
  product_variants:
    - "Protection Platine Vie Entière"
    - "Protection Platine Temporaire"
    - "Protection Or Vie Entière"
    - "Protection Or Temporaire"
    - "Protection Argent"
    - "Protection Bronze"

# Classification
language: fr-CA
region: CA
target_audience: 
  - insurance_advisors
  - agents
  - underwriters
  - brokers

# Coverage Limits
coverage:
  min_amount: 5000
  max_amount: 750000
  currency: CAD
  age_range: [18, 85]
  age_groups:
    - "18-50"
    - "51-75"
    - "76-80"
    - "81-85"

# Tags for Searchability
tags:
  - guide-reference-rapide
  - assurance-vie-simplifiee
  - eligibilite
  - assomption
  - protection-platine
  - protection-or
  - protection-argent
  - protection-bronze
  - conditions-medicales

# Machine-Readable Features
features:
  eligibility_matrix: true
  medical_conditions: true
  non_medical_conditions: true
  decision_tree: true
  quick_reference: true

# Disclaimer
disclaimer: "Ce guide est fourni à titre informatif seulement et ne constitue pas une garantie d'émission."

# Document Structure Map
sections:
  - id: about_guide
    name: "À Propos de ce Guide"
    type: overview
    line_start: 42
  - id: vue_ensemble
    name: "Vue d'Ensemble des Produits"
    type: comparison
    line_start: 54
  - id: legende_symboles
    name: "Légende et Symboles"
    type: reference
    line_start: 74
  - id: organigramme_decision
    name: "Organigramme de Décision Rapide"
    type: decision_tree
    line_start: 91
  - id: index_alphabetique
    name: "Index Alphabétique des Conditions"
    type: index
    line_start: 115
  - id: conditions_medicales
    name: "Conditions Médicales - Par Système du Corps"
    type: conditions
    line_start: 171
  - id: conditions_non_medicales
    name: "Conditions Non Médicales"
    type: conditions
    line_start: 530
  - id: tableau_recapitulatif
    name: "Tableau Récapitulatif - Vue Matricielle Complète"
    type: summary
    line_start: 630
  - id: glossaire
    name: "Glossaire des Termes"
    type: reference
    line_start: 682
  - id: documents_reference
    name: "Documents de Référence Connexes"
    type: resources
    line_start: 706
  - id: conseils_utilisation
    name: "Conseils pour l'Utilisation du Guide"
    type: guidelines
    line_start: 723
  - id: contact_support
    name: "Contact et Support"
    type: resources
    line_start: 765
  - id: notes_juridiques
    name: "Notes Juridiques"
    type: legal
    line_start: 790

# Document Segments (Original PDF)
document_segments:
  - name: "Guide de Référence Rapide"
    pages: 0-25
    confidence: High

# Document Statistics
statistics:
  total_medical_conditions: 30
  total_non_medical_conditions: 8
  total_products: 6
  underwriting_tiers: 4
  medical_questions_by_tier:
    platine: 19
    or: 13
    argent: 9
    bronze: 0
  coverage_types:
    immediate: 2
    deferred_progressive: 1
    deferred: 1
  conditions_by_system:
    cardiovascular: 8
    respiratory: 4
    endocrine: 2
    gastrointestinal: 2
    genitourinary: 1
    neurological: 5
    oncological: 2
    other: 6
---

# Guide de Référence Rapide
## Solutions d'Assurance à Émission Simplifiée
### Assomption Vie

---

## À Propos de ce Guide

**Objectif:** À l'aide de ce guide, trouvez rapidement la solution d'assurance vie qui répond le mieux aux antécédents de santé de votre client.

**Comment utiliser ce guide:**
1. Identifiez les conditions médicales ou non médicales du client
2. Consultez les tableaux pour voir quels produits sont disponibles
3. Vérifiez les conditions d'éligibilité (délais depuis diagnostic, traitement, etc.)
4. Sélectionnez le produit approprié avec le niveau de couverture correspondant

---

## Vue d'Ensemble des Produits

### Tableau Comparatif des 4 Niveaux de Protection

| Caractéristique | Protection Platine | Protection Or | Protection Argent | Protection Bronze |
|---|---|---|---|---|
| **Type de couverture** | Immédiate | Immédiate | Différée progressive | Différée |
| **Questions médicales** | 19 questions | 13 questions | 9 questions | 0 question (Émission garantie) |
| **Niveau de santé requis** | Excellent à très bon | Bon à moyen | Moyen | Aucune exigence |
| **Prime** | Plus basse | Moyenne | Plus élevée | La plus élevée |
| **Capital assuré - VE** | 10 000 $ - 750 000 $ | 5 000 $ - 250 000 $ | 5 000 $ - 50 000 $ | 5 000 $ - 50 000 $ |
| **Capital assuré - Temp** | 25 000 $ - 750 000 $ | 25 000 $ - 250 000 $ | N/A | N/A |
| **Âge d'émission** | 18-85 ans | 18-85 ans | 18-85 ans | 18-80 ans |
| **Paiement de décès** | Immédiat | Immédiat | Progressive (0-2 ans) | Différée (2 ans) |
| **Exclusions** | Standard | Standard | Standard | Étendue |

**Légende:** VE = Vie Entière, Temp = Temporaire

---

## Légende et Symboles

| Symbole | Signification | Description |
|---|---|---|
| **✓** | **Admissible** | Le client est éligible pour ce produit |
| **X** | **Non admissible** | Le client n'est PAS éligible pour ce produit |
| **»** | **Admissible avec conditions** | Le client est éligible SI les conditions spécifiées sont remplies |
| **-** | **N/A** | Non applicable ou pas de restriction spécifique |

### Interprétation des Conditions Temporelles

Lorsque vous voyez une condition comme "Si plus de X ans depuis...", cela signifie:
- Le client DOIT avoir dépassé cette période depuis le diagnostic/traitement
- Exemple: "Si plus de 5 ans depuis le diagnostic" = Au moins 5 ans doivent s'être écoulés

---

## Organigramme de Décision Rapide

```
Client avec condition médicale/non-médicale
         ↓
Question: Condition présente dans les tableaux ci-dessous?
         ↓
    OUI                          NON
         ↓                           ↓
Vérifier tableau     →     Utiliser Protection Platine
         ↓                      (si aucune autre condition)
Lire les conditions
         ↓
Protection Platine possible? → OUI → Utiliser Protection Platine
         ↓ NON
Protection Or possible? → OUI → Utiliser Protection Or
         ↓ NON
Protection Argent possible? → OUI → Utiliser Protection Argent
         ↓ NON
Protection Bronze (Émission garantie) → Toujours disponible
```

---

## Index Alphabétique des Conditions

**Navigation rapide vers les sections:**

### Conditions Médicales
- [Accident ischémique transitoire (AIT)](#accident-ischémique-transitoire-mini-avc)
- [Accident vasculaire cérébral (AVC)](#accident-vasculaire-cérébral)
- [Angine](#angine-ou-crise-cardiaque)
- [Angioplastie coronaire](#angioplastie-coronaire-ou-pontage)
- [Anxiété](#anxiété-ou-dépression)
- [Apnée du sommeil](#apnée-du-sommeil)
- [Arythmie](#arythmie-ou-souffle-au-cœur)
- [Asthme](#asthme)
- [Cancer](#cancer-leucémie-lymphome-mélanome)
- [Carcinome basocellulaire](#carcinome-basocellulaire)
- [Cardiomyopathie](#cardiomyopathie)
- [Colite ulcéreuse](#maladie-de-crohn-ou-colite-ulcéreuse)
- [Crise cardiaque](#angine-ou-crise-cardiaque)
- [Dépression](#anxiété-ou-dépression)
- [Diabète](#diabète)
- [Épilepsie](#épilepsie)
- [Greffe d'organe](#greffe-dorgane-ou-moelle-osseuse)
- [Hépatite B ou C](#hépatite-b-ou-c)
- [Hypertension artérielle](#hypertension-artérielle)
- [Insuline](#insuline-prescrite)
- [Leucémie](#cancer-leucémie-lymphome-mélanome)
- [Lymphome](#cancer-leucémie-lymphome-mélanome)
- [Maladie de Crohn](#maladie-de-crohn-ou-colite-ulcéreuse)
- [Maladie polykystique des reins](#maladie-rénale-chronique)
- [Maladie rénale chronique](#maladie-rénale-chronique)
- [Mélanome](#cancer-leucémie-lymphome-mélanome)
- [MPOC](#maladie-pulmonaire-obstructive-chronique-mpoc)
- [Oxygène](#oxygène-pour-trouble-respiratoire)
- [Pacemaker](#stimulateur-cardiaque-pacemaker)
- [Pontage aorto-coronarien](#angioplastie-coronaire-ou-pontage)
- [Prednisone](#prednisone-ou-corticostéroïde-oral)
- [Sclérose en plaques](#sclérose-en-plaques)
- [Schizophrénie](#schizophrénie-ou-psychose)
- [Souffle au cœur](#arythmie-ou-souffle-au-cœur)
- [Syndrome de Down](#syndrome-de-down)
- [Troubles bipolaires](#troubles-bipolaires)

### Conditions Non Médicales
- [Alcool - Traitement](#traitement-dalcool-et-de-drogue)
- [Aviation privée](#sports-dangereux-ou-aviation-privée)
- [Conduite avec facultés affaiblies](#infraction-de-conduite-liée-à-lalcool-ou-drogues)
- [Drogue - Consommation](#consommation-de-drogue)
- [Drogue - Traitement](#traitement-dalcool-et-de-drogue)
- [Faillite](#faillite)
- [Nouveaux résidents](#nouveaux-résidents-du-canada)
- [Refus d'assurance](#refusé-dans-le-passé-pour-assurance-vie)
- [Sports dangereux](#sports-dangereux-ou-aviation-privée)
- [Voyage international](#voyage-international)

---

## Conditions Médicales - Par Système du Corps

### Cancer

#### Carcinome Basocellulaire

| Produit | Éligibilité |
|---|---|
| **Protection Platine** | ✓ Admissible |
| **Protection Or** | ✓ Admissible |
| **Protection Argent** | ✓ Admissible |
| **Protection Bronze** | ✓ Admissible |

**Notes:** Le carcinome basocellulaire est accepté pour tous les produits sans condition de délai.

---

#### Cancer, Leucémie, Lymphome ou Mélanome

| Produit | Éligibilité | Conditions |
|---|---|---|
| **Protection Platine** | » Admissible avec conditions | Si plus de **5 ans** depuis le diagnostic, l'hospitalisation ou le traitement (y compris médicaments prescrits) |
| **Protection Or** | » Admissible avec conditions | Si plus de **3 ans** depuis le diagnostic, l'hospitalisation ou le traitement (y compris médicaments prescrits) |
| **Protection Argent** | » Admissible avec conditions | Si plus de **2 ans** depuis le diagnostic, l'hospitalisation ou le traitement (y compris médicaments prescrits) |
| **Protection Bronze** | ✓ Admissible | Aucune condition |

**Notes:** Les mêmes conditions s'appliquent en cas de récidive du cancer ou de métastase.

---

### Système Cardiovasculaire

#### Arythmie ou Souffle au Cœur

| Produit | Éligibilité | Conditions |
|---|---|---|
| **Protection Platine** | » Admissible avec conditions | • Si plus de **5 ans** depuis le diagnostic ou l'hospitalisation<br>• **OU** Si plus de **2 ans** depuis des changements de médicaments |
| **Protection Or** | ✓ Admissible | Aucune condition |
| **Protection Argent** | ✓ Admissible | Aucune condition |
| **Protection Bronze** | ✓ Admissible | Aucune condition |

---

#### Angine ou Crise Cardiaque

| Produit | Éligibilité | Conditions |
|---|---|---|
| **Protection Platine** | » Admissible avec conditions | Si plus de **5 ans** depuis le diagnostic ou l'hospitalisation |
| **Protection Or** | » Admissible avec conditions | Si plus de **3 ans** depuis le diagnostic ou l'hospitalisation |
| **Protection Argent** | » Admissible avec conditions | Si plus de **2 ans** depuis le diagnostic ou l'hospitalisation |
| **Protection Bronze** | ✓ Admissible | Aucune condition |

---

#### Cardiomyopathie

| Produit | Éligibilité | Conditions |
|---|---|---|
| **Protection Platine** | » Admissible avec conditions | Si plus de **10 ans** depuis le diagnostic, l'hospitalisation ou le traitement |
| **Protection Or** | » Admissible avec conditions | Si plus de **5 ans** depuis le diagnostic, l'hospitalisation ou le traitement |
| **Protection Argent** | » Admissible avec conditions | Si plus de **5 ans** depuis le diagnostic ou l'hospitalisation |
| **Protection Bronze** | ✓ Admissible | Aucune condition |

---

#### Angioplastie Coronaire ou Pontage Aorto-Coronarien

| Produit | Éligibilité | Conditions |
|---|---|---|
| **Protection Platine** | » Admissible avec conditions | Si plus de **5 ans** depuis le diagnostic ou l'hospitalisation |
| **Protection Or** | » Admissible avec conditions | Si plus de **3 ans** depuis le diagnostic ou l'hospitalisation |
| **Protection Argent** | » Admissible avec conditions | Si plus de **2 ans** depuis le diagnostic ou l'hospitalisation |
| **Protection Bronze** | ✓ Admissible | Aucune condition |

---

#### Hypertension Artérielle

| Produit | Éligibilité |
|---|---|
| **Protection Platine** | ✓ Admissible |
| **Protection Or** | ✓ Admissible |
| **Protection Argent** | ✓ Admissible |
| **Protection Bronze** | ✓ Admissible |

**Notes:** L'hypertension artérielle contrôlée est acceptée pour tous les produits.

---

#### Stimulateur Cardiaque (Pacemaker)

| Produit | Éligibilité |
|---|---|
| **Protection Platine** | **X** Non admissible |
| **Protection Or** | ✓ Admissible |
| **Protection Argent** | ✓ Admissible |
| **Protection Bronze** | ✓ Admissible |

**Notes:** Seule la Protection Platine n'accepte pas les clients avec pacemaker.

---

#### Accident Vasculaire Cérébral

| Produit | Éligibilité | Conditions |
|---|---|---|
| **Protection Platine** | » Admissible avec conditions | Si plus de **5 ans** depuis le diagnostic ou l'hospitalisation |
| **Protection Or** | » Admissible avec conditions | Si plus de **3 ans** depuis le diagnostic ou l'hospitalisation |
| **Protection Argent** | » Admissible avec conditions | Si plus de **2 ans** depuis le diagnostic ou l'hospitalisation |
| **Protection Bronze** | ✓ Admissible | Aucune condition |

---

#### Accident Ischémique Transitoire (Mini-AVC)

| Produit | Éligibilité | Conditions |
|---|---|---|
| **Protection Platine** | » Admissible avec conditions | Si plus de **5 ans** depuis le diagnostic ou l'hospitalisation |
| **Protection Or** | ✓ Admissible | Aucune condition |
| **Protection Argent** | ✓ Admissible | Aucune condition |
| **Protection Bronze** | ✓ Admissible | Aucune condition |

---

### Système Endocrinien

#### Diabète

| Produit | Éligibilité |
|---|---|
| **Protection Platine** | ✓ Admissible |
| **Protection Or** | ✓ Admissible |
| **Protection Argent** | ✓ Admissible |
| **Protection Bronze** | ✓ Admissible |

**Notes:** Le diabète seul (sans complications) est accepté pour tous les produits.

---

#### Diabète avec Une ou Plusieurs Complications¹

| Produit | Éligibilité | Conditions |
|---|---|---|
| **Protection Platine** | **X** Non admissible | |
| **Protection Or** | » Admissible avec conditions | Si plus de **3 ans** depuis les complications |
| **Protection Argent** | ✓ Admissible | Aucune condition |
| **Protection Bronze** | ✓ Admissible | Aucune condition |

**¹ Les complications comprennent:**
- Crise cardiaque (infarctus du myocarde)
- Angine
- Accident vasculaire cérébral (AVC)
- Maladie vasculaire/artérielle périphérique
- Gangrène
- Amputation liée aux complications du diabète (mauvaise circulation, infection)
- Coma hypoglycémique
- Neuropathie
- Néphropathie

---

#### Insuline Prescrite

| Produit | Éligibilité |
|---|---|
| **Protection Platine** | ✓ Admissible |
| **Protection Or** | ✓ Admissible |
| **Protection Argent** | ✓ Admissible |
| **Protection Bronze** | ✓ Admissible |

**Notes:** L'utilisation d'insuline seule ne constitue pas un obstacle pour aucun produit.

---

### Système Gastro-Intestinal

#### Maladie de Crohn ou Colite Ulcéreuse

| Produit | Éligibilité | Conditions |
|---|---|---|
| **Protection Platine** | » Admissible avec conditions | • Si plus de **5 ans** depuis le diagnostic ou l'hospitalisation<br>• **OU** Si plus de **2 ans** depuis des changements de médicaments |
| **Protection Or** | ✓ Admissible | Aucune condition |
| **Protection Argent** | ✓ Admissible | Aucune condition |
| **Protection Bronze** | ✓ Admissible | Aucune condition |

---

#### Hépatite B ou C

| Produit | Éligibilité | Conditions |
|---|---|---|
| **Protection Platine** | » Admissible avec conditions | Si plus de **10 ans** depuis le diagnostic, l'hospitalisation ou le traitement |
| **Protection Or** | » Admissible avec conditions | Si plus de **5 ans** depuis le diagnostic, l'hospitalisation ou le traitement |
| **Protection Argent** | ✓ Admissible | Aucune condition |
| **Protection Bronze** | ✓ Admissible | Aucune condition |

---

### Système Génito-Urinaire

#### Maladie Rénale Chronique ou Maladie Polykystique des Reins

| Produit | Éligibilité | Conditions |
|---|---|---|
| **Protection Platine** | » Admissible avec conditions | • Si plus de **5 ans** depuis le diagnostic ou l'hospitalisation<br>• **Pour les assurés de 50 ans et moins:** Aucun membre de la famille biologique n'ayant reçu un diagnostic de maladie polykystique des reins sans investigation |
| **Protection Or** | » Admissible avec conditions | Si plus de **3 ans** depuis le diagnostic ou l'hospitalisation |
| **Protection Argent** | » Admissible avec conditions | Si plus de **2 ans** depuis le diagnostic ou l'hospitalisation |
| **Protection Bronze** | ✓ Admissible | Aucune condition |

---

### Système Nerveux et Santé Mentale

#### Anxiété ou Dépression

| Produit | Éligibilité |
|---|---|
| **Protection Platine** | ✓ Admissible |
| **Protection Or** | ✓ Admissible |
| **Protection Argent** | ✓ Admissible |
| **Protection Bronze** | ✓ Admissible |

**Notes:** L'anxiété et la dépression sont acceptées pour tous les produits sans condition.

---

#### Troubles Bipolaires

| Produit | Éligibilité | Conditions |
|---|---|---|
| **Protection Platine** | » Admissible avec conditions | • Si plus de **5 ans** depuis le diagnostic ou l'hospitalisation<br>• **OU** Si plus de **2 ans** depuis des changements de médicaments |
| **Protection Or** | ✓ Admissible | Aucune condition |
| **Protection Argent** | ✓ Admissible | Aucune condition |
| **Protection Bronze** | ✓ Admissible | Aucune condition |

---

#### Syndrome de Down

| Produit | Éligibilité |
|---|---|
| **Protection Platine** | ✓ Admissible |
| **Protection Or** | ✓ Admissible |
| **Protection Argent** | ✓ Admissible |
| **Protection Bronze** | ✓ Admissible |

---

#### Épilepsie

| Produit | Éligibilité | Conditions |
|---|---|---|
| **Protection Platine** | » Admissible avec conditions | • Si plus de **5 ans** depuis le diagnostic ou l'hospitalisation<br>• **OU** Si plus de **2 ans** depuis des changements de médicaments |
| **Protection Or** | ✓ Admissible | Aucune condition |
| **Protection Argent** | ✓ Admissible | Aucune condition |
| **Protection Bronze** | ✓ Admissible | Aucune condition |

---

#### Sclérose en Plaques

| Produit | Éligibilité | Conditions |
|---|---|---|
| **Protection Platine** | » Admissible avec conditions | • Si plus de **5 ans** depuis le diagnostic ou l'hospitalisation<br>• **OU** Si plus de **2 ans** depuis des changements de médicaments |
| **Protection Or** | ✓ Admissible | Aucune condition |
| **Protection Argent** | ✓ Admissible | Aucune condition |
| **Protection Bronze** | ✓ Admissible | Aucune condition |

---

#### Schizophrénie ou Psychose

| Produit | Éligibilité | Conditions |
|---|---|---|
| **Protection Platine** | » Admissible avec conditions | Si plus de **5 ans** depuis le diagnostic, l'hospitalisation ou le traitement |
| **Protection Or** | ✓ Admissible | Aucune condition |
| **Protection Argent** | ✓ Admissible | Aucune condition |
| **Protection Bronze** | ✓ Admissible | Aucune condition |

---

### Greffe d'Organe

#### Greffe d'Organe ou Moelle Osseuse

| Produit | Éligibilité | Conditions |
|---|---|---|
| **Protection Platine** | » Admissible avec conditions | Si plus de **10 ans** depuis la greffe OU n'est pas en attente d'une greffe |
| **Protection Or** | » Admissible avec conditions | Si plus de **5 ans** depuis la greffe OU n'est pas en attente d'une greffe |
| **Protection Argent** | » Admissible avec conditions | Si plus de **5 ans** depuis la greffe OU n'est pas en attente d'une greffe |
| **Protection Bronze** | ✓ Admissible | Aucune condition |

---

### Système Respiratoire

#### Asthme

| Produit | Éligibilité |
|---|---|
| **Protection Platine** | ✓ Admissible |
| **Protection Or** | ✓ Admissible |
| **Protection Argent** | ✓ Admissible |
| **Protection Bronze** | ✓ Admissible |

**Notes:** L'asthme contrôlé est accepté pour tous les produits.

---

#### Maladie Pulmonaire Obstructive Chronique (MPOC)

| Produit | Éligibilité | Conditions |
|---|---|---|
| **Protection Platine** | » Admissible avec conditions | Si plus de **2 ans** depuis l'hospitalisation |
| **Protection Or** | » Admissible avec conditions | Si plus de **12 mois** depuis l'hospitalisation |
| **Protection Argent** | ✓ Admissible | Aucune condition |
| **Protection Bronze** | ✓ Admissible | Aucune condition |

---

#### Prednisone ou Corticostéroïde Oral pour Trouble Respiratoire

| Produit | Éligibilité | Conditions |
|---|---|---|
| **Protection Platine** | » Admissible avec conditions | Si plus de **12 mois** depuis la prescription du traitement |
| **Protection Or** | » Admissible avec conditions | Si plus de **12 mois** depuis la prescription du traitement |
| **Protection Argent** | ✓ Admissible | Aucune condition |
| **Protection Bronze** | ✓ Admissible | Aucune condition |

**Notes:** Les inhalateurs contenant de la prednisone ou corticostéroïdes ne sont pas visés par cette restriction.

---

#### Oxygène pour Trouble Respiratoire Chronique

| Produit | Éligibilité | Conditions |
|---|---|---|
| **Protection Platine** | » Admissible avec conditions | Si plus de **10 ans** depuis l'administration d'oxygène |
| **Protection Or** | » Admissible avec conditions | Si plus de **5 ans** depuis l'administration d'oxygène |
| **Protection Argent** | ✓ Admissible | Aucune condition |
| **Protection Bronze** | ✓ Admissible | Aucune condition |

**Notes:** Ne s'applique pas à l'apnée du sommeil.

---

#### Apnée du Sommeil

| Produit | Éligibilité |
|---|---|
| **Protection Platine** | ✓ Admissible |
| **Protection Or** | ✓ Admissible |
| **Protection Argent** | ✓ Admissible |
| **Protection Bronze** | ✓ Admissible |

**Notes:** L'apnée du sommeil est acceptée pour tous les produits sans restriction.

---

## Conditions Non Médicales

### Consommation de Drogue

| Produit | Éligibilité | Conditions |
|---|---|---|
| **Protection Platine** | » Admissible avec conditions | Si plus de **3 ans** depuis la consommation de drogue |
| **Protection Or** | » Admissible avec conditions | Si plus de **2 ans** depuis la consommation de drogue |
| **Protection Argent** | ✓ Admissible | Aucune condition |
| **Protection Bronze** | ✓ Admissible | Aucune condition |

---

### Traitement d'Alcool et de Drogue

| Produit | Éligibilité | Conditions |
|---|---|---|
| **Protection Platine** | » Admissible avec conditions | Si plus de **3 ans** depuis le traitement ou l'arrêt de la consommation |
| **Protection Or** | » Admissible avec conditions | Si plus de **2 ans** depuis le traitement ou l'arrêt de la consommation |
| **Protection Argent** | » Admissible avec conditions | Si plus de **12 mois** depuis le traitement ou l'arrêt de la consommation |
| **Protection Bronze** | ✓ Admissible | Aucune condition |

---

### Faillite

| Produit | Éligibilité |
|---|---|
| **Protection Platine** | ✓ Admissible |
| **Protection Or** | ✓ Admissible |
| **Protection Argent** | ✓ Admissible |
| **Protection Bronze** | ✓ Admissible |

**Notes:** La faillite n'est pas un obstacle pour aucun produit.

---

### Refusé dans le Passé pour Assurance Vie

| Produit | Éligibilité |
|---|---|
| **Protection Platine** | ✓ Admissible |
| **Protection Or** | ✓ Admissible |
| **Protection Argent** | ✓ Admissible |
| **Protection Bronze** | ✓ Admissible |

**Notes:** Un refus antérieur n'empêche pas l'admissibilité aux produits simplifiés.

---

### Infraction de Conduite Liée à l'Alcool ou Drogues

| Produit | Éligibilité | Conditions |
|---|---|---|
| **Protection Platine** | » Admissible avec conditions | Si plus de **3 ans** depuis être accusé ou condamné |
| **Protection Or** | » Admissible avec conditions | Si plus de **2 ans** depuis être accusé ou condamné |
| **Protection Argent** | ✓ Admissible | Aucune condition |
| **Protection Bronze** | ✓ Admissible | Aucune condition |

**Notes:** Inclut le refus de se soumettre à un alcootest.

---

### Sports Dangereux ou Aviation Privée

| Produit | Éligibilité | Conditions |
|---|---|---|
| **Protection Platine** | » Admissible avec conditions | Si pratiqué dans les **12 prochains mois** |
| **Protection Or** | ✓ Admissible | Aucune condition |
| **Protection Argent** | ✓ Admissible | Aucune condition |
| **Protection Bronze** | ✓ Admissible | Aucune condition |

**Notes:** La Protection Platine exclut certains sports dangereux et l'aviation privée planifiés dans les 12 prochains mois.

---

### Nouveaux Résidents du Canada²

| Produit | Éligibilité |
|---|---|
| **Protection Platine** | ✓ Admissible |
| **Protection Or** | ✓ Admissible |
| **Protection Argent** | ✓ Admissible |
| **Protection Bronze** | ✓ Admissible |

**² Note importante:** Veuillez vous référer au **Guide de tarification pour les nouveaux arrivants au Canada** pour déterminer l'éligibilité spécifique du client selon son statut et sa durée de résidence.

---

### Voyage International

| Produit | Éligibilité | Conditions |
|---|---|---|
| **Protection Platine** | » Admissible avec conditions | Si **moins de 12 semaines consécutives** en dehors de l'Amérique du Nord, de l'Europe de l'Ouest ou des Caraïbes (excluant Haïti) au cours des 12 prochains mois |
| **Protection Or** | ✓ Admissible | Aucune condition |
| **Protection Argent** | ✓ Admissible | Aucune condition |
| **Protection Bronze** | ✓ Admissible | Aucune condition |

---

## Tableau Récapitulatif - Vue Matricielle Complète

### Conditions Médicales

| Condition | Protection Platine | Protection Or | Protection Argent | Protection Bronze |
|---|---|---|---|---|
| **Cancer - Carcinome basocellulaire** | ✓ | ✓ | ✓ | ✓ |
| **Cancer, leucémie, lymphome, mélanome** | » Si > 5 ans | » Si > 3 ans | » Si > 2 ans | ✓ |
| **Arythmie ou souffle au cœur** | » Si > 5 ans OU > 2 ans méd. | ✓ | ✓ | ✓ |
| **Angine ou crise cardiaque** | » Si > 5 ans | » Si > 3 ans | » Si > 2 ans | ✓ |
| **Cardiomyopathie** | » Si > 10 ans | » Si > 5 ans | » Si > 5 ans | ✓ |
| **Angioplastie/Pontage** | » Si > 5 ans | » Si > 3 ans | » Si > 2 ans | ✓ |
| **Hypertension artérielle** | ✓ | ✓ | ✓ | ✓ |
| **Pacemaker** | X | ✓ | ✓ | ✓ |
| **AVC** | » Si > 5 ans | » Si > 3 ans | » Si > 2 ans | ✓ |
| **AIT (mini-AVC)** | » Si > 5 ans | ✓ | ✓ | ✓ |
| **Diabète** | ✓ | ✓ | ✓ | ✓ |
| **Diabète avec complications** | X | » Si > 3 ans | ✓ | ✓ |
| **Insuline prescrite** | ✓ | ✓ | ✓ | ✓ |
| **Crohn ou colite ulcéreuse** | » Si > 5 ans OU > 2 ans méd. | ✓ | ✓ | ✓ |
| **Hépatite B ou C** | » Si > 10 ans | » Si > 5 ans | ✓ | ✓ |
| **Maladie rénale chronique** | » Si > 5 ans | » Si > 3 ans | » Si > 2 ans | ✓ |
| **Anxiété ou dépression** | ✓ | ✓ | ✓ | ✓ |
| **Troubles bipolaires** | » Si > 5 ans OU > 2 ans méd. | ✓ | ✓ | ✓ |
| **Syndrome de Down** | ✓ | ✓ | ✓ | ✓ |
| **Épilepsie** | » Si > 5 ans OU > 2 ans méd. | ✓ | ✓ | ✓ |
| **Sclérose en plaques** | » Si > 5 ans OU > 2 ans méd. | ✓ | ✓ | ✓ |
| **Schizophrénie ou psychose** | » Si > 5 ans | ✓ | ✓ | ✓ |
| **Greffe d'organe ou moelle osseuse** | » Si > 10 ans | » Si > 5 ans | » Si > 5 ans | ✓ |
| **Asthme** | ✓ | ✓ | ✓ | ✓ |
| **MPOC** | » Si > 2 ans hosp. | » Si > 12 mois hosp. | ✓ | ✓ |
| **Prednisone orale pour respiration** | » Si > 12 mois | » Si > 12 mois | ✓ | ✓ |
| **Oxygène pour respiration** | » Si > 10 ans | » Si > 5 ans | ✓ | ✓ |
| **Apnée du sommeil** | ✓ | ✓ | ✓ | ✓ |

### Conditions Non Médicales

| Condition | Protection Platine | Protection Or | Protection Argent | Protection Bronze |
|---|---|---|---|---|
| **Consommation de drogue** | » Si > 3 ans | » Si > 2 ans | ✓ | ✓ |
| **Traitement alcool/drogue** | » Si > 3 ans | » Si > 2 ans | » Si > 12 mois | ✓ |
| **Faillite** | ✓ | ✓ | ✓ | ✓ |
| **Refus d'assurance passé** | ✓ | ✓ | ✓ | ✓ |
| **Infraction conduite alcool/drogue** | » Si > 3 ans | » Si > 2 ans | ✓ | ✓ |
| **Sports dangereux/aviation privée** | » Si 12 proch. mois | ✓ | ✓ | ✓ |
| **Nouveaux résidents Canada** | ✓ (voir guide) | ✓ (voir guide) | ✓ (voir guide) | ✓ (voir guide) |
| **Voyage international** | » Si < 12 sem. consécutives | ✓ | ✓ | ✓ |

**Légende abrégée:** hosp. = hospitalisation, méd. = changements de médicaments, proch. = prochains, sem. = semaines

---

## Glossaire des Termes

| Terme | Définition |
|---|---|
| **Assurance à émission simplifiée** | Assurance vie avec processus de souscription simplifié basé sur un questionnaire médical sans examen physique |
| **Couverture immédiate** | Assurance qui paie le plein montant dès le décès, sans période d'attente ni réduction |
| **Couverture différée** | Assurance où le plein montant n'est payable qu'après une période d'attente (généralement 2 ans) |
| **Couverture différée progressive** | Assurance où le montant payable augmente graduellement pendant les premières années (ex: primes + intérêt année 1, 50% année 2, 100% année 3+) |
| **Émission garantie** | Produit d'assurance accepté sans aucune question médicale ni examen |
| **Protection Platine** | Niveau de protection le plus élevé (19 questions, couverture immédiate, meilleures primes) |
| **Protection Or** | Niveau de protection intermédiaire (13 questions, couverture immédiate) |
| **Protection Argent** | Niveau de protection avec souscription allégée (9 questions, couverture différée progressive) |
| **Protection Bronze** | Produit à émission garantie (0 question, couverture différée) |
| **Diagnostic** | Identification d'une maladie ou condition par un professionnel de la santé |
| **Hospitalisation** | Admission dans un hôpital pour traitement avec séjour d'au moins une nuit |
| **Traitement** | Intervention médicale incluant médicaments prescrits, chirurgie, thérapie |
| **Changements de médicaments** | Nouveau médicament prescrit, augmentation/diminution de dose, ou arrêt d'un médicament |
| **Complications du diabète** | Conditions médicales résultant du diabète (neuropathie, néphropathie, problèmes cardiovasculaires, etc.) |
| **AVC** | Accident vasculaire cérébral |
| **AIT** | Accident ischémique transitoire (mini-AVC) |
| **MPOC** | Maladie pulmonaire obstructive chronique |

---

## Documents de Référence Connexes

### Formulaires d'Application
- **Formulaire de collecte de données** - Assurance vie simplifiée
- **Proposition d'assurance** - Formulaire complet

### Guides de Souscription
- **Guide de tarification complet** - Directives détaillées pour tous les produits
- **Guide pour nouveaux arrivants au Canada** - Critères d'éligibilité spécifiques
- **Questions médicales par produit** - Liste complète des questions d'assurabilité

### Documents Produits
- **Spécimens de polices** - Pour chaque produit (Platine, Or, Argent, Bronze)
- **Tableaux de primes** - Tarification par âge et montant

---

## Conseils pour l'Utilisation du Guide

### Meilleures Pratiques

1. **Commencez toujours par Protection Platine**
   - Offre la meilleure couverture et les meilleures primes
   - Utilisez ce guide pour vérifier l'éligibilité

2. **Posez des questions spécifiques**
   - Ne supposez pas qu'une condition empêche l'assurance
   - Vérifiez les délais depuis le diagnostic/traitement

3. **Documentez soigneusement**
   - Notez les dates exactes des diagnostics, traitements, hospitalisations
   - Confirmez les changements de médicaments avec dates

4. **Utilisez les guides complémentaires**
   - Ce guide est un outil de référence rapide
   - Consultez les guides détaillés pour les cas complexes

5. **Protection Bronze est toujours disponible**
   - Si toutes les autres options sont épuisées
   - Émission garantie = aucune question médicale

### Cas Particuliers

**Multiples conditions:**
- Si le client a plusieurs conditions, vérifiez CHACUNE individuellement
- Le produit final est celui qui satisfait TOUTES les conditions
- Exemple: Si une condition permet Platine mais une autre seulement Or, utilisez Or

**Conditions non listées:**
- Si une condition n'apparaît pas dans ce guide, elle n'empêche généralement pas l'assurance
- Consultez le guide de tarification complet ou contactez la souscription

**Doutes sur les délais:**
- Arrondissez toujours en défaveur du client pour la sécurité
- Exemple: Si c'est "4 ans et 11 mois", considérez comme "moins de 5 ans"
- Contactez la souscription pour clarification

---

## Contact et Support

### Assomption Vie

**Site web:** <https://www.assomption.ca>

**Ligne d'assistance pour conseillers:** 1-800-455-7337

**Adresse:**  
Assomption Vie  
C.P. 160  
770, rue Main  
Moncton (N.-B.) E1C 8L1

**Départements:**
- Assurance individuelle
- Assurance collective  
- Placements et retraite

**Heures d'ouverture:** Lundi au vendredi, 8h00 - 17h00 (HNE)

**Support technique Lia:** Disponible via le Coin du conseiller

---

## Notes Juridiques

Ce guide de référence rapide est fourni à titre informatif seulement et ne constitue pas une garantie d'émission. Toutes les demandes sont sujettes à l'approbation finale de la souscription d'Assomption Vie.

Les critères d'admissibilité peuvent changer sans préavis. Veuillez toujours consulter la version la plus récente de ce guide.

**Dernière mise à jour:** Référez-vous à la version la plus récente disponible sur le Coin du conseiller.

**© Assomption Vie** - Tous droits réservés.
