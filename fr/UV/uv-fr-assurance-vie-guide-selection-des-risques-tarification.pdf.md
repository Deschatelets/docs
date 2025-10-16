---
# Document Metadata
document_id: "uv-fr-assurance-vie-guide-selection-risques-tarification-v1.0"
document_type: risk_selection_underwriting_guide
schema_version: "2.0"
version: 1.0
document_title: "Guide de Sélection des Risques et Tarification - Assurance Vie UV Assurance"
full_product_name: "Risk Selection and Underwriting Guide for Life Insurance (UV Assurance)"
total_pages: 18
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
  name: "Guide de Tarification Médicale"
  id: "medical-underwriting-guide"
  owner: "UV Assurance"
  type: "underwriting_guide"
  type_fr: "Guide de souscription"
  underwriting_type: "medical_underwriting"
  underwriting_type_fr: "Souscription médicale"
  product_variants:
    - "Assurance Vie"
    - "Assurance Dette"
    - "Assurance Maladies Graves"

# Classification
language: fr-CA
region: CA
target_audience:
  - underwriters
  - insurance_advisors
  - agents
  - medical_professionals

# Coverage Limits
coverage:
  min_amount: 10000
  max_amount: 5000000
  currency: CAD
  age_range: [0, 80]
  age_groups:
    - "0-18"
    - "18-40"
    - "40-60"
    - "60-80"

# Tags for Searchability
tags:
  - selection-risques
  - tarification-medicale
  - assurance-vie
  - conditions-medicales
  - uv-assurance
  - surprime
  - exclusion
  - differe
  - refus

# Machine-Readable Features
features:
  medical_conditions: true
  underwriting_decisions: true
  height_weight_tables: true
  rating_guidelines: true
  exclusion_criteria: true

# Disclaimer
disclaimer: "Ce guide de tarification est fourni à titre indicatif seulement et ne constitue pas une garantie d'émission."

# Document Structure Map
sections:
  - id: vue_ensemble
    name: "Vue d'ensemble"
    type: overview
    line_start: 9
  - id: avis_important
    name: "Avis important"
    type: notice
    line_start: 26
  - id: conditions_medicales
    name: "Conditions médicales"
    type: medical_conditions
    line_start: 36
  - id: tableau_poids_taille
    name: "Tableau de poids et taille"
    type: reference_tables
    line_start: 259
  - id: criteres_tarification_supplementaires
    name: "Critères de tarification supplémentaires"
    type: additional_criteria
    line_start: 279
  - id: guide_reference_rapide
    name: "Guide de référence rapide"
    type: quick_reference
    line_start: 323
  - id: metadonnees_indexation
    name: "Métadonnées pour indexation"
    type: reference
    line_start: 350

# Document Segments (Original PDF)
document_segments:
  - name: "Guide Sélection Risques et Tarification"
    pages: 0-18
    confidence: High

# Document Statistics
statistics:
  total_medical_conditions: 10
  total_underwriting_decisions: 5
  total_height_weight_entries: 23
  total_additional_criteria: 4
  condition_categories:
    cardiovascular: 2
    respiratory: 1
    neurological: 1
    musculoskeletal: 1
    oncological: 3
    metabolic: 1
    developmental: 1
  underwriting_decisions:
    - "standard"
    - "surprime"
    - "exclusion"
    - "differe"
    - "refus"
  coverage_amounts:
    min: 10000
    max: 5000000
  age_ranges:
    min: 0
    max: 80
---

## Vue d'ensemble

Ce guide présente les critères de sélection des risques et les attentes en matière de tarification pour les produits d'assurance vie de UV Assurance. Il sert de référence pour les conseillers et les tarificateurs dans l'évaluation des risques médicaux.

---

## Table des matières

1. [Vue d'ensemble](#vue-densemble)
2. [Avis important](#avis-important)
3. [Conditions médicales](#conditions-médicales)
4. [Tableau de poids et taille](#tableau-de-poids-et-taille)
5. [Critères de tarification supplémentaires](#critères-de-tarification-supplémentaires)
6. [Guide de référence rapide](#guide-de-référence-rapide)

---

## Avis important

### Limitations du guide
- **Estimations préliminaires:** Les décisions possibles qui apparaissent dans ce guide ne sont que des estimations préliminaires et n'engagent en rien UV Assurance
- **Évaluation individuelle:** Chaque dossier sera évalué selon les exigences reçues durant l'étude
- **Restrictions:** Nous n'étudierons pas les dossiers qui ont été surprimés ou refusés dans les six derniers mois
- **Modifications:** Ce guide est sujet à modifications sans préavis

---

## Conditions médicales

### Guide de tarification par condition

#### Accident vasculaire cérébral (AVC) / Accident ischémique transitoire (AIT) / Hémorragie cérébrale

**Renseignements utiles:**
- Coordonnées du médecin qui a le dossier complet
- Capacité fonctionnelle actuelle
- Séquelles
- Précisions sur les tests et suivis
- Médicaments prescrits

**Exigences:** Rapport du médecin traitant (RMT)

**Tarification:**

| Condition | Assurance Vie | Assurance Dette | Maladie Grave |
|-----------|---------------|-----------------|---------------|
| **AVC et hémorragie cérébrale** | Différé 12 mois suite à l'événement<br>Par la suite : Entre +75 et +300 | Refus | Refus |
| **AIT** | Différé 6 mois suite à l'événement<br>Par la suite, si séquelles mineures : Entre standard et +125 | Refus | Refus |
| **Hémorragie cérébrale sans chirurgie** | Entre +75 et +150 | Refus | Refus |
| **Hémorragie cérébrale avec chirurgie** | Entre standard et +100 | Refus | Refus |
| **Événements multiples** | Refus | Refus | Refus |

#### Apnée du sommeil

**Renseignements utiles:**
- Coordonnées du médecin qui a le dossier complet
- Date du diagnostic, sévérité, traitement
- Degré de contrôle/conformité avec le traitement (CPAP nombre d'heures utilisées par nuit)
- Date de la dernière évaluation du sommeil
- État depuis le traitement
- Précisions sur les suivis

**Exigences:** Rapport du médecin traitant (RMT) à la discrétion du tarificateur

**Tarification:**

| Condition | Assurance Vie | Assurance Dette | Maladie Grave |
|-----------|---------------|-----------------|---------------|
| **Traité avec bonne réponse** | Entre standard et +150 | Standard | Standard |
| **Sans traitement (selon sévérité)** | Entre +50 et refus | Entre standard et refus | +50 à +150 |
| **Cas sévère sans traitement** | Refus | Refus | Refus |
| **Apnée du sommeil centrale** | Refus | Refus | Refus |

#### Arthrite rhumatoïde / Arthrite juvénile

**Renseignements utiles:**
- Coordonnées du médecin qui a le dossier complet
- Limitation dans les activités et/ou arrêt de travail
- Traitements et médicaments prescrits
- Fréquence des crises
- Rapport du médecin

**Exigences:** Rapport du médecin traitant (RMT)

**Tarification:**

| Condition | Assurance Vie | Assurance Dette | Maladie Grave |
|-----------|---------------|-----------------|---------------|
| **Rhumatoïde selon sévérité** | Entre standard, surprime et refus | Entre exclusion, surprime et +25 à +50 | Entre standard et refus |
| **Juvénile en rémission sans complication** | +150 | Refus | Refus |
| **Juvénile en rémission sans complications** | +50 ou refus | Voir rhumatoïde | Voir rhumatoïde |
| **Juvénile moins de 25 ans** | +150 | +100 | Refus |
| **Juvénile 25 ans et plus** | +50 ou refus | Voir rhumatoïde | Voir rhumatoïde |

#### Asthme

**Renseignements utiles:**
- Coordonnées du médecin qui a le dossier complet
- Médicaments prescrits
- Questionnaire sur les troubles respiratoires (FOC066) à la discrétion du tarificateur

**Exigences:** Rapport du médecin traitant (RMT)

**Tarification:**

| Condition | Assurance Vie | Assurance Dette | Maladie Grave |
|-----------|---------------|-----------------|---------------|
| **Non-fumeur symptomatique** | Entre standard et +50 | Entre standard et exclusion | Entre standard et +50 |
| **Non-fumeur symptomatique sévère** | Entre +75 et refus | Entre standard et exclusion | Entre standard et +50 |
| **Fumeur symptomatique** | Entre +125 et refus | Entre standard, exclusion et +100 | Entre standard et +100 |
| **Fumeur symptomatique sévère** | Entre +200 et refus | Refus | Refus |
| **Asymptomatique depuis plus de 2 ans** | Standard | Standard | Standard |

#### Autisme

**Renseignements utiles:**
- Coordonnées du médecin qui a le rapport complet
- Médicaments prescrits

**Exigences:** Rapport du médecin traitant (RMT)

**Tarification:**

| Condition | Assurance Vie | Assurance Dette | Maladie Grave |
|-----------|---------------|-----------------|---------------|
| **Moins de 18 ans** | Refus | Refus | Refus |
| **18 ans et plus (autisme léger)** | Possibilité d'offre selon le degré d'autonomie | Refus | Standard selon le degré d'autonomie |
| **Autres** | Refus | Refus | Refus |

#### Cancers

##### Cancer colorectal

**Renseignements utiles:**
- Coordonnées du médecin qui a le dossier complet incluant le rapport de pathologie
- Date du diagnostic
- Type de traitement
- Date de la fin des traitements
- Récidives
- Précisions sur la régularité des suivis (coloscopie)

**Exigences:** Rapport du médecin traitant (RMT)

**Tarification:**

| Stade | Assurance Vie | Assurance Dette | Maladie Grave |
|-------|---------------|-----------------|---------------|
| **Stade 0** | Entre 3,00 $ et 7,50 $/mille | Différé entre 2 ans et 10 ans<br>Par la suite : Exclusion | Jusqu'à 5 ans : Refus<br>Par la suite : Possibilité d'exclusion |
| **Stade 1** | Différé entre 1 an et 5 ans<br>Par la suite : Entre 6,00 $ et 15,00 $/mille x 5 ans | Différé entre 2 ans et 10 ans<br>Par la suite : Exclusion | Jusqu'à 7 ans : Refus<br>Par la suite : Possibilité d'exclusion |
| **Stade 2A** | Différé entre 1 an et 5 ans<br>Par la suite : Entre 6,00 $ et 15,00 $/mille x 5 ans | Différé entre 2 ans et 10 ans<br>Par la suite : Exclusion | Refus |
| **Stade plus haut que 2A** | Refus | Refus | Refus |

##### Cancer de la prostate

**Renseignements utiles:**
- Coordonnées du médecin qui a le rapport complet incluant le rapport de pathologie
- Date du diagnostic
- Type de traitement
- Date de la fin des traitements
- Mesure la plus récente de l'antigène prostatique spécifique (APS)

**Exigences:** Rapport du médecin traitant (RMT)

**Tarification:**

| Stade | Assurance Vie | Assurance Dette | Maladie Grave |
|-------|---------------|-----------------|---------------|
| **Selon le stade** | Différé entre 1 an et 3 ans<br>Par la suite : 5,00 $/mille x 5 ans ou moins | Différé entre 1 an et 10 ans<br>Par la suite : Exclusion ou refus | Stade 1 avec prostatectomie totale<br>Différé jusqu'à 10 ans<br>Par la suite : Exclusion |
| **Stade 3 ou plus** | Refus | Refus | Stade plus haut que 1 : Refus |

##### Cancer du sein

**Renseignements utiles:**
- Coordonnées du médecin qui a le dossier complet incluant le rapport de pathologie
- Date du diagnostic
- Type de traitement
- Date de la fin des traitements
- Récidives
- Précisions sur la régularité des suivis (mammographie)

**Exigences:** Rapport du médecin traitant (RMT)

**Tarification:**

| Type | Assurance Vie | Assurance Dette | Maladie Grave |
|------|---------------|-----------------|---------------|
| **Carcinome in situ** | Entre 1,50 $ et 6,00 $/mille x 4 ans | Différé 1 an<br>Entre 2 ans et 4 ans : Exclusion<br>Après 4 ans : Possibilité de standard | Refus |
| **Autres tumeurs selon stade** | Différé entre 1 an et 5 ans<br>Par la suite : Entre 5,00 $ et 20,00 $/mille | Différé entre 4 ans et 10 ans<br>Par la suite : Entre +50 et exclusion | Refus |
| **Stade 3 et 4** | Possibilité de refus | - | - |

#### Diabète Type 1 et 2 / Intolérance au glucose

**Renseignements utiles:**
- Coordonnées du médecin qui a le dossier complet
- Type de diabète
- Date du diagnostic
- Médicaments prescrits
- Complications (rétinopathie, néphropathie, etc.)
- Date et résultats de la dernière analyse sanguine

**Exigences:** Rapport du médecin traitant (RMT)

**Tarification:**

| Type | Assurance Vie | Assurance Dette | Maladie Grave |
|------|---------------|-----------------|---------------|
| **Diabète Type 1** | Selon l'âge et la durée avec bon contrôle, sans complication : Entre standard et +300 | Refus | Refus |
| **Diabète Type 2** | Selon l'âge et la durée avec bon contrôle, sans complication : Entre standard et +250 | Moins de 40 ans : Refus<br>40 ans et plus : Selon l'âge et la durée | Moins de 40 ans : Refus<br>40 ans et plus : Selon l'âge et la durée |
| **Intolérance au glucose** | Selon l'âge : Entre standard et +75 | Moins de 40 ans : Refus<br>40 ans et plus : Selon l'âge | Moins de 30 ans : Refus<br>30 ans et plus : Entre +50 et +100 |

#### Épilepsie

**Renseignements utiles:**
- Coordonnées du médecin qui a le dossier complet
- Médicaments prescrits
- Fréquence des crises
- Date de la dernière crise
- Genre de crise (partielle, généralisée, grand mal, petit mal, etc.)
- Tests faits et résultats

**Exigences:** Rapport du médecin traitant (RMT)

**Tarification:**

| Condition | Assurance Vie | Assurance Dette | Maladie Grave |
|-----------|---------------|-----------------|---------------|
| **Moins de 6 mois depuis diagnostic** | Différé | Moins de 12 mois : Différé | Moins de 12 mois : Différé |
| **Crises généralisées** | Selon le temps écoulé, la sévérité et la fréquence : Entre différé, standard et +200 | Selon le temps écoulé et la fréquence : Entre +50 et refus | Selon le temps écoulé, la sévérité et la fréquence : Entre +50 et refus |
| **Crises partielles** | Selon le temps écoulé, la sévérité et la fréquence : Entre différé, standard et +100 | Selon le temps écoulé et la fréquence : Entre +50 et refus | Selon le temps écoulé, la sévérité et la fréquence : Entre +50 et refus |
| **État de mal épileptique** | Depuis moins de 1 an : Différé | Depuis moins de 2 ans : Différé | Depuis moins de 1 an : Différé |

#### Hypertension artérielle

**Renseignements utiles:**
- Coordonnées du médecin qui a le dossier complet
- Médicaments prescrits
- Contrôle de la tension artérielle

**Exigences:** Rapport du médecin traitant (RMT)

**Tarification:**

| Condition | Assurance Vie | Assurance Dette | Maladie Grave |
|-----------|---------------|-----------------|---------------|
| **Bien contrôlée** | Standard | Standard | Standard |
| **Modérément contrôlée** | Entre standard et +50 | Entre standard et +50 | Entre standard et +50 |
| **Mal contrôlée** | Entre +50 et +150 | Entre +50 et +150 | Entre +50 et +150 |

---

## Tableau de poids et taille

### Limites de poids pour les classifications Super Privilégiés et Privilégiés

| Taille | 4'8'' | 4'9'' | 4'10'' | 4'11'' | 5'0'' | 5'1'' | 5'2'' | 5'3'' | 5'4'' | 5'5'' | 5'6'' | 5'7'' | 5'8'' | 5'9'' | 5'10'' | 5'11'' | 6'0'' | 6'1'' | 6'2'' | 6'3'' | 6'4'' | 6'5'' | 6'6'' |
|--------|-------|-------|--------|--------|-------|-------|-------|-------|-------|-------|-------|-------|-------|-------|--------|--------|-------|-------|-------|-------|-------|-------|-------|
| **Poids maximum Super Privilégiés (lbs)** | 138 | 141 | 144 | 147 | 150 | 153 | 156 | 159 | 162 | 165 | 171 | 178 | 184 | 191 | 197 | 204 | 210 | 214 | 218 | 222 | 226 | 230 | 234 |
| **Poids maximum Privilégiés (lbs)** | 148 | 151 | 154 | 157 | 160 | 163 | 166 | 169 | 172 | 175 | 182 | 189 | 196 | 204 | 211 | 218 | 225 | 230 | 235 | 240 | 245 | 250 | 255 |
| **Taille (cm)** | 142 | 145 | 147 | 149 | 152 | 155 | 158 | 160 | 163 | 165 | 168 | 170 | 173 | 175 | 178 | 181 | 183 | 186 | 188 | 191 | 193 | 196 | 198 |
| **Poids maximum Super Privilégiés (kg)** | 63 | 64 | 65 | 67 | 68 | 69 | 71 | 72 | 74 | 75 | 78 | 81 | 84 | 87 | 89 | 93 | 95 | 97 | 99 | 101 | 103 | 104 | 106 |
| **Poids maximum Privilégiés (kg)** | 67 | 69 | 70 | 71 | 73 | 74 | 75 | 76 | 78 | 79 | 82 | 86 | 89 | 92 | 96 | 99 | 102 | 104 | 107 | 109 | 111 | 113 | 116 |

### Notes importantes
- **Super Privilégiés:** Poids maximum selon la taille pour obtenir la classification Super Privilégiés
- **Privilégiés:** Poids maximum selon la taille pour obtenir la classification Privilégiés
- **Conversion:** 1 livre = 0,453592 kg
- **Mesure:** Les mesures doivent être prises selon les standards médicaux

---

## Critères de tarification supplémentaires

### Assurance pour conjoint sans emploi

#### Assurance vie
- **Calcul:** Revenu familial total × 50% × facteur d'âge
- **Montant plus élevé:** Traité sur la base d'une considération individuelle avec justification à l'appui

#### Assurance maladie grave
- **Calcul:** 4× le revenu familial annuel gagné
- **Maximum:** 250 000 $

### Assurance enfant

#### Assurance vie
- **Limite:** Ne devrait pas dépasser 50% du capital assuré d'un parent
- **Restriction:** Nous ne combinerons pas le capital assuré des deux parents pour offrir un montant supérieur à l'enfant

#### Assurance maladie grave
- **Calcul:** 50% du montant détenu par les parents
- **Maximum:** 250 000 $
- **Justification:** Au-delà de 100 000 $, une justification du montant doit être fournie

### Assurance affaires

#### Exigences
- **Questionnaire:** Toutes les questions de la partie 3, section B de la proposition doivent être répondues en tout temps
- **Justification:** Le montant doit être justifié
- **Couverture:** Tous les associés devraient être assurés selon le prorata de leur pourcentage de parts dans l'entreprise
- **États financiers:** Il est possible que les états financiers soient demandés selon l'information au dossier

### Personne clé

#### Assurance vie
- **Calcul:** 5 à 10× le revenu annuel

#### Assurance maladie grave
- **Calcul:** 3 à 7× le revenu annuel

#### Convention achat-vente
- **Calcul:** Selon les états financiers et le pourcentage des parts de chacun des actionnaires

---

## Guide de référence rapide

### Conditions avec refus automatique
- Apnée du sommeil centrale
- Autisme (moins de 18 ans)
- Cancer du sang (leucémie) - Assurance Dette et Maladie Grave
- Cancer des poumons - Assurance Maladie Grave
- Diabète Type 1 - Assurance Dette et Maladie Grave
- Épilepsie sévère non contrôlée
- Sclérose en plaques
- Troubles nerveux sévères

### Conditions avec tarification standard possible
- Asthme asymptomatique depuis plus de 2 ans
- Côlon irritable
- Hypertension bien contrôlée
- Intolérance au glucose (selon l'âge)
- Troubles nerveux légers

### Conditions nécessitant un différé
- Chirurgie bariatrique (0-6 mois)
- Épilepsie (moins de 6 mois depuis diagnostic)
- Cancer colorectal (selon stade)
- Cancer de la prostate (selon stade)

---

## Métadonnées pour indexation

**Mots-clés:** sélection des risques, tarification médicale, assurance vie, conditions médicales, UV Assurance, rapport médecin traitant, surprime, exclusion, différé

**Types de conditions:** Accident vasculaire cérébral, Apnée du sommeil, Arthrite, Asthme, Autisme, Cancers, Diabète, Épilepsie, Hypertension, Troubles nerveux

**Types de tarification:** Standard, Surprime, Exclusion, Différé, Refus

**Produits concernés:** Assurance vie, Assurance Dette, Assurance Maladie Grave

**Exigences:** Rapport médecin traitant, Questionnaire spécialisé, Profil sanguin, Signes vitaux

**Critères supplémentaires:** Assurance conjoint sans emploi, Assurance enfant, Assurance affaires, Personne clé