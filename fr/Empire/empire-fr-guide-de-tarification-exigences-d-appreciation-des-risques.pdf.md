---
# Document Metadata
document_id: "empire-fr-exigences-appreciation-risques-v1.0"
document_type: underwriting_requirements_guide
schema_version: "2.0"
version: 1.0
document_title: "Exigences d'Appréciation des Risques - Assurance Vie et Maladies Graves Empire Vie"
full_product_name: "Risk Assessment Requirements Guide for Life and Critical Illness Insurance (L'Empire, Compagnie d'Assurance-Vie)"
total_pages: 3
last_updated: "2024"
effective_date: "2024-01-01"

# Insurer Information
insurer:
  name: "L'Empire, Compagnie d'Assurance-Vie"
  id: "empire"
  legal_name: "L'Empire, Compagnie d'Assurance-Vie"

# Product Information
product:
  name: "Assurance Vie et Maladies Graves"
  id: "life-critical-illness"
  owner: "L'Empire, Compagnie d'Assurance-Vie"
  type: "life_critical_illness_insurance"
  type_fr: "Assurance vie et maladies graves"
  underwriting_type: "full_underwriting"
  underwriting_type_fr: "Pleine sélection"

# Classification
language: fr-CA
region: QC
target_audience: 
  - underwriters
  - agents

# Coverage Limits
coverage:
  min_amount: 0
  max_amount: 20000000
  currency: CAD
  age_range: [0, 75]
  age_groups:
    - "0-17"
    - "18-40"
    - "41-50"
    - "51-55"
    - "56-60"
    - "61-70"
    - "71-75"

# Tags for Searchability
tags:
  - assurance-vie
  - maladies-graves
  - exigences
  - tarification
  - empire
  - médicales
  - paramédicales

# Machine-Readable Features
features:
  mib_verification: true
  medical_exams: true
  blood_tests: true
  financial_questionnaire: true
  driving_record: true

# Disclaimer
disclaimer: "Ces informations sont à titre indicatif seulement et n'engagent pas L'Empire, Compagnie d'Assurance-Vie."

# Document Structure Map
sections:
  - id: overview
    name: "Aperçu du document"
    type: overview
    line_start: 20
  - id: glossary
    name: "Glossaire des abréviations"
    type: reference
    line_start: 54
  - id: life_insurance_table
    name: "Tableau : Assurance Vie"
    type: table
    line_start: 90
  - id: critical_illness_table
    name: "Tableau : Assurance Maladies Graves"
    type: table
    line_start: 114
  - id: directives
    name: "Directives importantes"
    type: guidelines
    line_start: 139
  - id: resources
    name: "Ressources et contacts"
    type: resources
    line_start: 258

# Document Segments (Original PDF)
document_segments:
  - name: "Exigences Assurance Vie"
    pages: 0-1
    confidence: High
  - name: "Exigences Maladies Graves"
    pages: 1-2
    confidence: High
  - name: "Directives et Ressources"
    pages: 2-3
    confidence: High

# Document Statistics
statistics:
  total_age_groups: 7
  total_coverage_tiers_life: 7
  total_coverage_tiers_ci: 6
  abbreviation_categories: 3
  total_abbreviations: 12
  special_cases: 4
  requirement_types:
    medical_paramedical: 5
    tests: 4
    documents: 4
---

# Exigences d'Appréciation des Risques - Assurance Vie et Maladies Graves

**L'Empire, Compagnie d'Assurance-Vie**

---

## Table des matières

1. [Aperçu du document](#aperçu-du-document)
2. [Glossaire des abréviations](#glossaire-des-abréviations)
3. [Exigences d'appréciation des risques](#exigences-dappréciation-des-risques)
   - [Assurance Vie](#tableau-assurance-vie)
   - [Assurance Maladies Graves](#tableau-assurance-maladies-graves)
4. [Directives importantes](#directives-importantes)
   - [Remarques spécifiques - Assurance Vie](#remarques-spécifiques-assurance-vie)
   - [Directives générales](#directives-générales)
   - [Exigences partagées et réutilisation](#exigences-partagées-et-réutilisation)
   - [Cas spéciaux](#cas-spéciaux)
5. [Ressources et contacts](#ressources-et-contacts)

---

## Aperçu du document

Ce document présente les **exigences d'appréciation des risques** pour les produits d'assurance vie et d'assurance maladies graves de L'Empire Vie. Les exigences varient selon :

- **L'âge tarifié** de la personne assurée
- **Le montant de couverture** demandé
- **Le type de produit** (vie ou maladies graves)

> **Note importante** : Des exigences sans examen médical et sans analyse de fluides s'appliquent dans plusieurs catégories.

---

## Glossaire des abréviations

### Exigences médicales et paramédicales

| Abréviation | Définition complète | Description |
|-------------|---------------------|-------------|
| **EAP** | Entrevue téléphonique sur les Antécédents Personnels | Entrevue structurée sur l'historique médical |
| **ESV** | Examen des Signes Vitaux | Mesure de la tension artérielle, pouls, taille, poids |
| **PM** | Examen Paramédical | Évaluation par un professionnel paramédical |
| **EX** | Examen d'un Médecin | Évaluation complète par un médecin |
| **Qes** | Questionnaire sur l'État de Santé | Pour propositions Rapide & Complet<sup>MD</sup> uniquement |

### Tests et analyses

| Abréviation | Définition complète | Description |
|-------------|---------------------|-------------|
| **PS** | Profil Sanguin | Analyse sanguine complète |
| **UVIH** | Urine VIH | Test de dépistage VIH par analyse d'urine |
| **ECG** | Électrocardiogramme | Test cardiaque au repos |
| **EFF** | Électrocardiogramme à l'Effort sur tapis roulant | Test cardiaque sous effort physique |

### Documents et rapports

| Abréviation | Définition complète | Description |
|-------------|---------------------|-------------|
| **DMT** | Déclaration du Médecin Traitant | Rapport médical du médecin personnel |
| **DC** | Dossier de Conduite | Relevé du permis de conduire |
| **QF** | Questionnaire Financier | Évaluation de la situation financière |
| **RE** | Rapport d'Enquête | Enquête sur le risque financier et l'assurabilité |

> **Substitution possible** : L'entrevue téléphonique (EAP) accompagnée de l'examen des signes vitaux (ESV) peut être remplacée par un examen paramédical (PM).

---

## Exigences d'appréciation des risques

### Tableau : Assurance Vie

**Exigences selon l'âge et le montant de couverture**

Les exigences sont déterminées en fonction du montant total de toute assurance vie établie au cours des six derniers mois par L'Empire Vie.

| Âge tarifié | 0 $ - 99 999 $ | 100 000 $ - 300 000 $ | 300 001 $ - 499 999 $ | 500 000 $ - 2 000 000 $ | 2 000 001 $ - 3 000 000 $ | 3 000 001 $ - 10 000 000 $ | 10 000 001 $ - 20 000 000 $ |
|-------------|----------------|----------------------|----------------------|------------------------|--------------------------|----------------------------|-----------------------------|
| **0-17 ans** | EAP/Qes | EAP/Qes | EAP/Qes | EAP/Qes | EAP/Qes | EAP/Qes/QF | EAP/Qes/QF |
| **18-40 ans** | EAP/Qes | EAP/Qes | EAP/Qes | EAP/Qes | EAP et ESV*, PS | EAP et ESV*, PS, DC, QF | EAP et ESV*, PS, DC, DMT, RE** |
| **41-50 ans** | EAP/Qes | EAP/Qes | EAP/Qes | EAP/Qes | EAP et ESV*, PS | EAP et ESV*, PS, DC, QF | EAP et ESV*, PS, DC, ECG, DMT, RE** |
| **51-55 ans** | EAP/Qes | EAP/Qes | EAP/Qes | EAP et ESV*, PS | EAP et ESV*, PS | EAP et ESV*, PS, DC, QF | EAP et ESV*, PS, DC, EFF, DMT, RE** |
| **56-60 ans** | EAP/Qes | EAP/Qes | EAP et ESV*, PS | EAP et ESV*, PS | EAP et ESV*, PS | EAP et ESV*, PS, DC, QF | EAP et ESV*, PS, DC, EFF, DMT, RE** |
| **61-70 ans** | EAP | EAP et ESV*, PS | EAP et ESV*, PS | EAP et ESV*, PS | EAP et ESV*, PS | EAP et ESV*, PS, DC, QF | EAP et ESV*, PS, DC, EFF, DMT, RE** |
| **71-75 ans** | EAP et ESV*, PS | EAP et ESV*, PS | EAP et ESV*, PS | EAP et ESV*, PS | EAP et ESV*, PS | EAP et ESV*, PS, DC, QF | EAP et ESV*, PS, DC, EFF, DMT, RE** |

**Notes du tableau :**
- `*` L'entrevue téléphonique (EAP) avec examen des signes vitaux (ESV) peut être remplacée par un examen paramédical (PM)
- `**` L'Empire Vie se réserve le droit de demander des pièces justificatives supplémentaires sur une base individuelle
- `/` indique un choix entre les options (ou)
- `,` indique que plusieurs exigences sont requises (et)

---

### Tableau : Assurance Maladies Graves

**Exigences selon l'âge et le montant de couverture**

| Âge tarifié | 0 $ - 99 999 $ | 100 000 $ | 100 001 $ - 250 000 $ | 250 001 $ - 500 000 $ | 500 001 $ - 1 000 000 $ | 1 000 001 $ - 2 000 000 $ |
|-------------|----------------|-----------|----------------------|----------------------|------------------------|---------------------------|
| **18-35 ans** | EAP/Qes | EAP/Qes | EAP/Qes | EAP/UVIH | EAP et ESV*, PS | EAP et ESV*, PS, DMT |
| **36-40 ans** | EAP/Qes | EAP/Qes | EAP/Qes | EAP et ESV*, PS | EAP et ESV*, PS | EAP et ESV*, PS, ECG, DMT, RE |
| **41-50 ans** | EAP/Qes | EAP et ESV*, UVIH | EAP et ESV*, UVIH | EAP et ESV*, PS | EAP et ESV*, PS, ECG, DMT | EX, PS, ECG, DMT, RE |
| **51-55 ans** | EAP et ESV*, UVIH | EAP et ESV*, UVIH | EAP et ESV*, PS | EAP et ESV*, PS, ECG | EAP et ESV*, PS, ECG, DMT | EX, PS, ECG, DMT, RE |
| **56-60 ans** | EAP et ESV*, PS | EAP et ESV*, PS | EAP et ESV*, PS | EAP et ESV*, PS, ECG | EAP et ESV*, PS, ECG, DMT | EX, PS, ECG, DMT, RE |
| **61-65 ans** | EAP et ESV*, PS | EAP et ESV*, PS, ECG, DMT | EAP et ESV*, PS, ECG, DMT | EAP et ESV*, PS, ECG, DMT | EX, PS, ECG, DMT | EX, PS, EFF, DMT, RE |

**Notes du tableau :**
- `*` L'entrevue téléphonique (EAP) avec examen des signes vitaux (ESV) peut être remplacée par un examen paramédical (PM)
- `/` indique un choix entre les options (ou)
- `,` indique que plusieurs exigences sont requises (et)

**Règle de combinaison :** Lorsque vous soumettez une demande à la fois pour une assurance vie et une assurance maladies graves, nous n'additionnons pas les montants de protection, nous utilisons la combinaison d'exigence la plus élevée.

---

## Directives importantes

### Remarques spécifiques - Assurance Vie

#### Assurance temporaire Série Solution<sup>MC</sup>

Pour les catégories de tarification **Privilégié** et **Élite** (capital assuré de 1 000 001 $ et plus) :
- Un **profil sanguin (PS)** et un **examen des signes vitaux (ESV)** sont nécessaires
- Consultez le *Guide des critères pour la tarification privilégiée (INS-2494)* pour plus de détails

**Dispense du rapport d'enquête (RE) :** Nous pourrions renoncer au rapport d'enquête si vous soumettez :

1. Lettre d'accompagnement
2. Questionnaire financier rempli par le ou la comptable du client incluant :
   - Vérification du revenu
   - Vérification de la valeur nette par un tiers
3. Pour l'assurance des entreprises : états financiers de la société sur au moins 2 ans

---

### Directives générales

#### Processus automatisé

- **Commande automatique** : L'Empire Vie commandera automatiquement toutes les exigences selon votre choix de fournisseur :
  - Solutions d'assurance Dynacare
  - ExamOne

- **Suivi de demande** : Pour connaître l'état de la demande, contactez :
  - Centre d'affaires : [www.empire.ca/fr/advisor](https://www.empire.ca/fr/advisor)
  - Service à la clientèle : 1 800 536-7683

#### Dossier de conduite (DC)

**Exigences générales :**
- Un numéro de permis de conduire valide doit être inscrit sur la proposition

**Règles provinciales spécifiques :**

| Province | Procédure |
|----------|-----------|
| **Alberta** | La personne assurée doit obtenir elle-même le rapport et le soumettre à L'Empire Vie |
| **Québec** | Autorisation de divulgation requise - voir formulaire sur le site conseiller |
| **Colombie-Britannique** | Autorisation de divulgation requise - voir formulaire sur le site conseiller |

📄 **Formulaires d'autorisation** : [www.empire.ca/fr/advisor/Support/Underwriting/Questionnaires-forms](https://www.empire.ca/fr/advisor/support/underwriting/questionnaires-forms)

#### Questionnaires financiers (QF)

**Pour les montants de plus de 3 000 000 $ :**
- *Questionnaire financier relatif à une entreprise*, **ou**
- *Questionnaire financier personnel*

⚠️ **Important** : Inscrire le numéro de police sur le questionnaire

📄 **Accès aux questionnaires** : [www.empire.ca/fr/advisor/Support/Underwriting/Questionnaires-forms](https://www.empire.ca/fr/advisor/support/underwriting/questionnaires-forms)

#### Documents supplémentaires recommandés

Il peut être utile de soumettre :
- Lettre d'accompagnement
- États financiers
- Analyse des besoins

📚 **Ressource** : Consultez les *Lignes directrices relatives à l'appréciation des risques financiers* sur [www.empire.ca/fr/advisor/support/underwriting](https://www.empire.ca/fr/advisor/support/underwriting)

#### Information médicale

- **Conseil** : Noter les renseignements sur le médecin ou la clinique sur la page des personnes assurées dans *Rapide & Complet* pour accélérer l'établissement du contrat

---

### Exigences partagées et réutilisation

#### Partage des exigences médicales

Les exigences médicales remplies au cours des **12 derniers mois** sont normalement acceptables, **à condition** d'obtenir une déclaration courante sans examen médical.

**Pour partager des exigences :** Indiquez dans la section « Exigences d'appréciation des risques » de la proposition :
- La société en charge des exigences médicales
- Le numéro de police (si possible)

---

### Cas spéciaux

#### Nouveaux résidents

📚 Consultez le guide *Lignes directrices pour les personnes immigrantes* : [www.empire.ca/fr/advisor/support/underwriting](https://www.empire.ca/fr/advisor/support/underwriting)

#### Assurabilité garantie (AG)

**Calcul des exigences :**
```
Montant pour exigences = Nombre d'unités AG × 2 000 $
```

**Exemple :** 5 unités AG = 5 × 2 000 $ = 10 000 $ (utiliser cette valeur pour déterminer les exigences dans les tableaux)

#### Exonération des primes

**Montant maximal** pour les autres polices d'assurance vie :
- 2 000 $ par mois
- 24 000 $ par année

#### Exigences additionnelles aléatoires

⚠️ **Processus de sélection :** Conformément à notre processus habituel, nous pourrions demander des exigences supplémentaires :

1. **Selon l'information contenue dans la proposition**
2. **Sélection aléatoire ou par algorithmes d'analyses prédictives**
3. **Focus particulier** : Propositions d'assurance vie pour :
   - Protection de 500 000 $ à 2 000 000 $
   - Personne assurée âgée de 18 à 50 ans

Ces propositions pourraient se voir appliquer des exigences supplémentaires (y compris une analyse des fluides).

---

## Ressources et contacts

### Coordonnées de L'Empire Vie

**L'Empire, Compagnie d'Assurance-Vie**

**Adresse :**
```
259, rue King Est
Kingston ON K7L 3A8
Canada
```

**Contacts :**
- **Téléphone sans frais :** 1 877 548-1881
- **Service à la clientèle :** 1 800 536-7683
- **Courriel :** [info@empire.ca](mailto:info@empire.ca)
- **Site web :** [empire.ca](https://empire.ca)

### Portail conseillers

**Accès aux ressources en ligne :**
- **Portail principal :** [www.empire.ca/fr/advisor](https://www.empire.ca/fr/advisor)
- **Souscription et tarification :** [www.empire.ca/fr/advisor/support/underwriting](https://www.empire.ca/fr/advisor/support/underwriting)
- **Formulaires et questionnaires :** [www.empire.ca/fr/advisor/Support/Underwriting/Questionnaires-forms](https://www.empire.ca/fr/advisor/support/underwriting/questionnaires-forms)

### Documents de référence

| Document | Code | Sujet |
|----------|------|-------|
| Guide des critères pour la tarification privilégiée | INS-2494 | Critères Privilégié et Élite |
| Lignes directrices pour les personnes immigrantes | - | Nouveaux résidents |
| Lignes directrices relatives à l'appréciation des risques financiers | - | Souscription financière |

### Fournisseurs d'exigences médicales

L'Empire Vie travaille avec les fournisseurs suivants pour la collecte des exigences médicales :
- **Solutions d'assurance Dynacare**
- **ExamOne**

---

## Notes légales

> **RÉSERVÉ AUX CONSEILLÈRES ET AUX CONSEILLERS**

**Marques de commerce :**
- <sup>MD</sup> Marque déposée de L'Empire, Compagnie d'Assurance-Vie
- Les polices sont établies par L'Empire, Compagnie d'Assurance-Vie
- Toutes les autres marques de commerce sont la propriété de leurs détenteurs respectifs

**Slogan :** *Avancez dans la vie en toute confiance – Assurance et placements*

---

## Annexe : Données structurées (YAML)

```yaml
# Données structurées pour parsing automatisé
document:
  provider: "L'Empire, Compagnie d'Assurance-Vie"
  type: "underwriting_requirements"
  products:
    - "assurance_vie"
    - "assurance_maladies_graves"

age_bands:
  life_insurance:
    - range: [0, 17]
      label: "0-17 ans"
    - range: [18, 40]
      label: "18-40 ans"
    - range: [41, 50]
      label: "41-50 ans"
    - range: [51, 55]
      label: "51-55 ans"
    - range: [56, 60]
      label: "56-60 ans"
    - range: [61, 70]
      label: "61-70 ans"
    - range: [71, 75]
      label: "71-75 ans"
  
  critical_illness:
    - range: [18, 35]
      label: "18-35 ans"
    - range: [36, 40]
      label: "36-40 ans"
    - range: [41, 50]
      label: "41-50 ans"
    - range: [51, 55]
      label: "51-55 ans"
    - range: [56, 60]
      label: "56-60 ans"
    - range: [61, 65]
      label: "61-65 ans"

coverage_tiers:
  life_insurance:
    - min: 0
      max: 99999
      label: "0 $ - 99 999 $"
    - min: 100000
      max: 300000
      label: "100 000 $ - 300 000 $"
    - min: 300001
      max: 499999
      label: "300 001 $ - 499 999 $"
    - min: 500000
      max: 2000000
      label: "500 000 $ - 2 000 000 $"
    - min: 2000001
      max: 3000000
      label: "2 000 001 $ - 3 000 000 $"
    - min: 3000001
      max: 10000000
      label: "3 000 001 $ - 10 000 000 $"
    - min: 10000001
      max: 20000000
      label: "10 000 001 $ - 20 000 000 $"
  
  critical_illness:
    - min: 0
      max: 99999
      label: "0 $ - 99 999 $"
    - min: 100000
      max: 100000
      label: "100 000 $"
    - min: 100001
      max: 250000
      label: "100 001 $ - 250 000 $"
    - min: 250001
      max: 500000
      label: "250 001 $ - 500 000 $"
    - min: 500001
      max: 1000000
      label: "500 001 $ - 1 000 000 $"
    - min: 1000001
      max: 2000000
      label: "1 000 001 $ - 2 000 000 $"

abbreviations:
  EAP:
    full: "Entrevue téléphonique sur les Antécédents Personnels"
    category: "medical_paramedical"
  ESV:
    full: "Examen des Signes Vitaux"
    category: "medical_paramedical"
  PM:
    full: "Examen Paramédical"
    category: "medical_paramedical"
  EX:
    full: "Examen d'un Médecin"
    category: "medical_paramedical"
  Qes:
    full: "Questionnaire sur l'État de Santé"
    category: "medical_paramedical"
    note: "Pour propositions Rapide & Complet seulement"
  PS:
    full: "Profil Sanguin"
    category: "tests_analyses"
  UVIH:
    full: "Urine VIH"
    category: "tests_analyses"
  ECG:
    full: "Électrocardiogramme"
    category: "tests_analyses"
  EFF:
    full: "Électrocardiogramme à l'Effort sur tapis roulant"
    category: "tests_analyses"
  DMT:
    full: "Déclaration du Médecin Traitant"
    category: "documents_reports"
  DC:
    full: "Dossier de Conduite"
    category: "documents_reports"
  QF:
    full: "Questionnaire Financier"
    category: "documents_reports"
  RE:
    full: "Rapport d'Enquête"
    category: "documents_reports"

special_rules:
  guaranteed_insurability:
    calculation: "units × 2000"
    unit: "CAD"
  
  premium_waiver_max:
    monthly: 2000
    annual: 24000
    unit: "CAD"
  
  medical_requirements_sharing:
    validity_period_months: 12
    condition: "Déclaration courante sans examen médical requise"
  
  combined_life_critical_illness:
    rule: "Utiliser la combinaison d'exigence la plus élevée (ne pas additionner)"
  
  financial_questionnaire_threshold:
    amount: 3000000
    unit: "CAD"
    required_documents:
      - "Questionnaire financier relatif à une entreprise"
      - "Questionnaire financier personnel"

contact:
  company: "L'Empire, Compagnie d'Assurance-Vie"
  address:
    street: "259, rue King Est"
    city: "Kingston"
    province: "ON"
    postal_code: "K7L 3A8"
    country: "Canada"
  phone:
    toll_free: "1 877 548-1881"
    customer_service: "1 800 536-7683"
  email: "info@empire.ca"
  website: "empire.ca"
  advisor_portal: "https://www.empire.ca/fr/advisor"
```

---

**Fin du document**