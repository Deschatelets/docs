---
# Document Metadata
document_id: "empire-fr-guide-tarification-elite-privilégie-v1.0"
document_type: pricing_guide
schema_version: "2.0"
version: 1.0
document_title: "Guide de Tarification - Élite et Privilégié Empire Vie"
full_product_name: "Elite and Privilégié Pricing Guide for Term Life Insurance (L'Empire, Compagnie d'Assurance-Vie)"
total_pages: 2
last_updated: "2016-09"
effective_date: "2016-09-01"

# Insurer Information
insurer:
  name: "L'Empire, Compagnie d'Assurance-Vie"
  id: "empire"
  legal_name: "L'Empire, Compagnie d'Assurance-Vie"

# Product Information
product:
  name: "Élite et Privilégié"
  id: "elite-privilégie"
  owner: "L'Empire, Compagnie d'Assurance-Vie"
  type: "term_life_insurance"
  type_fr: "Assurance vie temporaire"
  underwriting_type: "preferred_rating"
  underwriting_type_fr: "Tarification privilégiée"

# Classification
language: fr-CA
region: QC
target_audience:
  - underwriters
  - agents

# Coverage Limits
coverage:
  min_amount: 1000000
  max_amount: 5000000
  currency: CAD
  age_range: [18, 75]
  age_groups:
    - "18-39"
    - "40-55"
    - "56-75"

# Tags for Searchability
tags:
  - assurance-vie
  - tarification
  - élite
  - privilégié
  - empire
  - non-fumeur
  - fumeur
  - critères

# Machine-Readable Features
features:
  mib_verification: true
  preferred_rating: true
  tobacco_free_periods: true
  blood_pressure_limits: true
  cholesterol_limits: true
  family_history_check: true

# Disclaimer
disclaimer: "Ces informations sont à titre indicatif seulement et n'engagent pas L'Empire, Compagnie d'Assurance-Vie."

# Document Structure Map
sections:
  - id: document_info
    name: "Informations sur le Document"
    type: metadata
    line_start: 17
  - id: criteria_overview
    name: "Critères d'Admissibilité par Catégorie"
    type: criteria
    line_start: 36
  - id: tobacco_usage
    name: "Usage de Produits du Tabac ou de la Nicotine"
    type: criteria
    line_start: 38
  - id: blood_pressure
    name: "Tension Artérielle"
    type: criteria
    line_start: 53
  - id: cholesterol
    name: "Cholestérol Total ET Ratio Mauvais/Bon Cholestérol"
    type: criteria
    line_start: 75
  - id: family_history
    name: "Antécédents Familiaux"
    type: criteria
    line_start: 98
  - id: personal_history
    name: "Antécédents Personnels"
    type: criteria
    line_start: 112
  - id: lifestyle_factors
    name: "Sports/Passe-temps/Aviation, Abus d'Alcool et de Drogues, Dossier de Conduite, etc."
    type: criteria
    line_start: 126
  - id: build_table
    name: "Constitution: Tableau Taille et Poids Maximal"
    type: table
    line_start: 186

# Document Segments (Original PDF)
document_segments:
  - name: "Critères Élite et Privilégié"
    pages: 0-1
    confidence: High
  - name: "Tableaux Taille/Poids"
    pages: 1-2
    confidence: High

# Document Statistics
statistics:
  total_criteria_categories: 11
  total_age_groups: 3
  total_risk_classes: 5
  preferred_smoker_classes: 1
  non_smoker_classes: 2
  build_table_entries: 22
  criteria_by_type:
    health: 4
    lifestyle: 5
    family: 1
    driving: 2
  tobacco_free_periods:
    elite: 180
    preferred: 24

---

# Guide de Tarification: Élite et Privilégié

## Informations sur le Document

**Entreprise:** L'Empire, Compagnie d'Assurance-Vie  
**Produit:** Élite et Privilégié  
**Langue:** Français  
**Date d'effet:** Septembre 2016  
**Référence:** FR-09/16

---

## Note Importante

Les critères suivants s'appliquent à la fois aux hommes et aux femmes, à moins d'indication contraire.

---

## Critères d'Admissibilité par Catégorie

### 1. Usage de Produits du Tabac ou de la Nicotine

**Définition:** Comprend l'usage de produits du tabac ou de la nicotine incluant la cigarette, la cigarette électronique, le cigarillo, la pipe, le tabac à chiquer ou à priser, le petit ou le gros cigare, les noix de bétel, ainsi que des produits de remplacement de la nicotine ou d'aide à la cessation du tabagisme.

#### Élite Non-fumeur
- Aucun usage d'un produit du tabac ou de la nicotine au cours des **180 derniers mois** (15 ans)

#### Privilégié Non-fumeur
- Aucun usage d'un produit du tabac ou de la nicotine au cours des **24 derniers mois** (2 ans)

#### Privilégié Fumeur
- Personne qui est considérée comme fumeuse au sens de notre définition de fumeur standard

---

### 2. Tension Artérielle

#### Élite Non-fumeur
**Aucun historique de traitement**

| Groupe d'Âge | Systolique/Diastolique |
|--------------|------------------------|
| 18-39 ans    | 125/75                 |
| 40-55 ans    | 130/80                 |
| 56-75 ans    | 140/85                 |

#### Privilégié Non-fumeur et Fumeur
**Avec ou sans traitement**

| Groupe d'Âge | Systolique/Diastolique |
|--------------|------------------------|
| 18-39 ans    | 135/80                 |
| 40-55 ans    | 140/85                 |
| 56-75 ans    | 145/90                 |

---

### 3. Cholestérol Total ET Ratio Mauvais/Bon Cholestérol

#### Élite Non-fumeur
**Aucun historique de traitement**

| Groupe d'Âge | Homme (Total/Ratio) | Femme (Total/Ratio) |
|--------------|---------------------|---------------------|
| 18-39 ans    | 200/4.5             | 200/4.0             |
| 40-55 ans    | 200/5.0             | 200/4.5             |
| 56-75 ans    | 220/5.5             | 220/5.0             |

#### Privilégié Non-fumeur et Fumeur
**Avec ou sans traitement**

| Groupe d'Âge | Total/Ratio |
|--------------|-------------|
| 18-39 ans    | 210/5.0     |
| 40-55 ans    | 220/5.5     |
| 56-75 ans    | 230/6.0     |

---

### 4. Antécédents Familiaux

**Définition:** Comprennent les antécédents de coronaropathie, d'accident vasculaire cérébral, d'accident ischémique transitoire ou de cancer (à l'exception du carcinome basocellulaire)

#### Élite Non-fumeur
- Aucun diagnostic avant l'âge de **65 ans** de l'un des membres de la famille
- Possibilité de permettre les cancers spécifiques au sexe (sein/prostate)

#### Privilégié Non-fumeur et Fumeur
- Diagnostic d'un (1) membre de la famille avant l'âge de **60 ans** tout au plus
- Possibilité de permettre les cancers spécifiques au sexe (sein/prostate)

---

### 5. Antécédents Personnels

#### Élite Non-fumeur
- Aucun antécédent de cancer (à l'exception du carcinome basocellulaire)
- Aucun antécédent de diabète
- Aucun antécédent de coronaropathie
- Aucun antécédent d'accident vasculaire cérébral
- Aucun antécédent d'accident ischémique transitoire

#### Privilégié Non-fumeur et Fumeur
- Non spécifié dans les critères

---

### 6. Sports/Passe-temps/Aviation

#### Élite Non-fumeur
- Aucune surprime pour la participation dangereuse à un sport, à un passe-temps ou à une activité en lien avec l'aviation

#### Privilégié Non-fumeur et Fumeur
- Non spécifié dans les critères

---

### 7. Abus d'Alcool et de Drogues

#### Élite Non-fumeur
- Aucun antécédent ni traitement au cours des **10 dernières années**

#### Privilégié Non-fumeur et Fumeur
- Aucun antécédent ni traitement au cours des **5 dernières années**

---

### 8. Dossier de Conduite

#### Élite Non-fumeur
- Maximum d'**une (1)** infraction au code de la sécurité routière au cours des **3 dernières années**

#### Privilégié Non-fumeur et Fumeur
- Maximum de **trois (3)** infractions au code de la sécurité routière au cours des **3 dernières années**

---

### 9. Conduite avec Facultés Affaiblies, Conduite Imprudente et Dangereuse

#### Élite Non-fumeur
- Aucune condamnation au cours des **10 dernières années**

#### Privilégié Non-fumeur et Fumeur
- Aucune condamnation au cours des **5 dernières années**

---

### 10. Voyage et Résidence à l'Étranger

#### Élite Non-fumeur
- Doit être un résident permanent du Canada
- Aucune surprime pour les voyages et la résidence à l'étranger

#### Privilégié Non-fumeur et Fumeur
- Non spécifié dans les critères

---

### 11. Profession

#### Élite Non-fumeur
- Aucune surprime pour la profession

#### Privilégié Non-fumeur et Fumeur
- Non spécifié dans les critères

---

## Constitution: Tableau Taille et Poids Maximal

### Élite Non-fumeur

| Taille        | Poids Maximal (lb) |
|---------------|--------------------|
| 4'8"          | 126                |
| 4'9"          | 128                |
| 4'10"         | 131                |
| 4'11"         | 134                |
| 5'0"          | 138                |
| 5'1"          | 140                |
| 5'2"          | 145                |
| 5'3"          | 149                |
| 5'4"          | 154                |
| 5'5"          | 159                |
| 5'6"          | 163                |
| 5'7"          | 169                |
| 5'8"          | 174                |
| 5'9"          | 180                |
| 5'10"         | 185                |
| 5'11"         | 191                |
| 6'0"          | 197                |
| 6'1"          | 201                |
| 6'2"          | 205                |
| 6'3"          | 209                |
| 6'4"          | 215                |
| 6'5"          | 220                |
| 6'6"          | 226                |
| 6'7"          | 232                |
| 6'8"          | 238                |
| 6'9"          | 243                |
| 6'10"         | 249                |

### Privilégié Non-fumeur et Fumeur

| Taille        | Poids Maximal (lb) |
|---------------|--------------------|
| 4'8"          | 135                |
| 4'9"          | 138                |
| 4'10"         | 141                |
| 4'11"         | 144                |
| 5'0"          | 148                |
| 5'1"          | 151                |
| 5'2"          | 155                |
| 5'3"          | 159                |
| 5'4"          | 165                |
| 5'5"          | 170                |
| 5'6"          | 175                |
| 5'7"          | 181                |
| 5'8"          | 187                |
| 5'9"          | 194                |
| 5'10"         | 200                |
| 5'11"         | 206                |
| 6'0"          | 213                |
| 6'1"          | 218                |
| 6'2"          | 222                |
| 6'3"          | 228                |
| 6'4"          | 234                |
| 6'5"          | 240                |
| 6'6"          | 246                |
| 6'7"          | 253                |
| 6'8"          | 259                |
| 6'9"          | 266                |
| 6'10"         | 272                |

---

## Résumé des Critères par Catégorie

### Élite Non-fumeur

| Critère | Exigence |
|---------|----------|
| Tabac/Nicotine | Aucun usage depuis 180 mois |
| Tension artérielle | Aucun traitement; limites par âge |
| Cholestérol | Aucun traitement; limites par âge et sexe |
| Antécédents familiaux | Aucun diagnostic avant 65 ans |
| Antécédents personnels | Aucun cancer, diabète, maladie cardiovasculaire |
| Sports/Aviation | Aucune surprime |
| Alcool/Drogues | Aucun antécédent depuis 10 ans |
| Conduite | Max 1 infraction en 3 ans |
| Conduite dangereuse | Aucune condamnation en 10 ans |
| Voyage/Résidence | Résident permanent Canada; aucune surprime |
| Profession | Aucune surprime |

### Privilégié Non-fumeur et Fumeur

| Critère | Exigence |
|---------|----------|
| Tabac/Nicotine | Non-fumeur: aucun usage 24 mois; Fumeur: standard |
| Tension artérielle | Avec/sans traitement; limites par âge |
| Cholestérol | Avec/sans traitement; limites par âge |
| Antécédents familiaux | Max 1 membre avant 60 ans |
| Alcool/Drogues | Aucun antécédent depuis 5 ans |
| Conduite | Max 3 infractions en 3 ans |
| Conduite dangereuse | Aucune condamnation en 5 ans |

---

## Notes Juridiques

**Marque déposée:** MD Marque déposée de L'Empire, Compagnie d'Assurance-Vie.

**Émetteur:** Les polices sont établies par L'Empire, Compagnie d'Assurance-Vie.

**Référence du document:** FR-09/16
