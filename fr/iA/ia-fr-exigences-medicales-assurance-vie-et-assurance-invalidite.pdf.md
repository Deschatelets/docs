---
# Document Metadata
document_id: "ia-fr-exigences-medicales-vie-invalidite-v1.0"
document_type: medical_requirements_guide
schema_version: "2.0"
version: 1.0
document_title: "Exigences Médicales - Assurance Vie et Assurance Invalidité iA"
full_product_name: "Medical Requirements for Life and Disability Insurance (iA Groupe financier)"
total_pages: 2
last_updated: "2024"
effective_date: "2024-01-01"

# Insurer Information
insurer:
  name: "iA Groupe financier"
  id: "ia"
  legal_name: "Industrial Alliance Insurance and Financial Services Inc."

# Product Information
product:
  name: "Assurance Vie et Invalidité"
  id: "vie-invalidite"
  owner: "iA Groupe financier"
  type: "life_and_disability_insurance"
  type_fr: "Assurance vie et invalidité"
  underwriting_type: "medical_underwriting"
  underwriting_type_fr: "Souscription médicale"

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
  max_amount: 2000000
  currency: CAD
  age_range: [18, 70]
  age_groups:
    - "18-40"
    - "41-50"
    - "51+"

# Tags for Searchability
tags:
  - exigences-medicales
  - assurance-vie
  - assurance-invalidite
  - ia
  - tarification
  - underwriting
  - medical_tests

# Machine-Readable Features
features:
  mib_verification: true
  fast_decision: false
  full_underwriting: true
  electronic_application: false
  simplified_issue: false

# Disclaimer
disclaimer: "Ces exigences sont indicatives ; iA peut demander des informations supplémentaires pour évaluer le risque."

# Document Structure Map
sections:
  - id: exigences-invalidite
    name: "Exigences pour Assurance Invalidité et Frais Généraux"
    type: requirements
    line_start: 5
  - id: legende-invalidite
    name: "Légende"
    type: legend
    line_start: 18
  - id: exigences-vie
    name: "Exigences pour Assurance Vie"
    type: requirements
    line_start: 36
  - id: legende-vie
    name: "Légende"
    type: legend
    line_start: 49
  - id: notes-immigrants
    name: "Notes pour Immigrants"
    type: notes
    line_start: 61

# Document Statistics
statistics:
  total_tables: 2
  total_requirements_types: 5
  age_groups: 3
  coverage_amount_ranges: 5
  requirement_types:
    declaration: true
    interview: true
    vital_signs: true
    blood_profile: true
    physician_statement: true
    investigation: true
---
# Exigences Médicales - Assurance Vie et Assurance Invalidité iA

Ce document détaille les exigences médicales pour les protections d'assurance invalidité (y compris frais généraux) et d'assurance vie chez iA. Les exigences sont basées sur l'âge et le montant total de couverture (en vigueur et à l'étude au cours des 12 derniers mois). iA se réserve le droit de demander des tests ou rapports supplémentaires selon les besoins de tarification.

## Exigences pour Assurance Invalidité et Frais Généraux {#exigences-invalidite}

- **A** : Pour assurance invalidité (Programme Supérieur ou Assurance Prêt Universelle) : Additionner tous les montants à l'étude et en vigueur au cours des 12 derniers mois.
- **B** : Pour protection frais généraux (Programme Supérieur) : Additionner tous les montants à l'étude et en vigueur au cours des 12 derniers mois.

**Utilisez le montant le plus élevé entre A et B pour déterminer les exigences.**

| Âge       | 0 - 4 000 $ | 4 001 - 5 000 $ | 5 001 - 6 000 $ | 6 001 - 6 999 $ | 7 000 $ et + |
|-----------|-------------|-----------------|-----------------|-----------------|--------------|
| 18-40     | A           | A               | A               | E               | G            |
| 41-50     | A           | A               | E               | E               | G            |
| 51 et +   | A           | F               | F               | F               | H            |

### Légende {#legende-invalidite}

| Code | Exigence |
|------|----------|
| A    | Déclaration d'assurabilité |
| E    | Entrevue téléphonique + Signes vitaux + Profil sanguin |
| F    | Entrevue téléphonique + Signes vitaux + Profil sanguin + Rapport du médecin traitant |
| G    | Entrevue téléphonique + Signes vitaux + Profil sanguin + Enquête |
| H    | Entrevue téléphonique + Signes vitaux + Profil sanguin + Rapport du médecin traitant + Enquête |

### Notes pour Immigrants (Moins d'un An au Canada)

- Âges 18-50 jusqu'à 1 000 $/mois : Déclaration d'assurabilité.
- Âges avancés et/ou montants plus élevés : Entrevue téléphonique, signes vitaux et profil sanguin.

**Profil sanguin** : Inclut VIH et urine.  
**Entrevue téléphonique et signes vitaux** : Peuvent être remplacés par examen paramédical.

## Exigences pour Assurance Vie {#exigences-vie}

Les exigences sont basées sur le **montant total de l'assurance vie** en cours et en vigueur auprès d'iA et d'autres compagnies au cours des 12 derniers mois.

| Âge       | 0 - 99 999 $ | 100 000 - 300 000 $ | 300 001 - 499 999 $ | 500 000 - 1 000 000 $ | 1 000 001 - 2 000 000 $ |
|-----------|--------------|---------------------|---------------------|-----------------------|-------------------------|
| 0-14      | A            | A                   | A                   | A                     | A                       |
| 15-50     | A            | A                   | A                   | A                     | A                       |
| 51-60     | A            | A                   | A                   | A ou C                | E                       |
| 61-65     | C            | E                   | E                   | E                     | E                       |
| 66-69     | E            | E                   | E                   | F                     | F                       |
| 70 et +   | B            | F                   | F                   | F                     | F                       |

### Légende {#legende-vie}

| Code | Exigence |
|------|----------|
| A    | Déclaration d'assurabilité. L'analyse prédictive est effectuée par iA. Pour la plupart des clients, seule la déclaration est nécessaire, mais des exigences supplémentaires peuvent s'appliquer selon les résultats. |
| B    | Déclaration d'assurabilité + Rapport du médecin traitant |
| C    | Entrevue téléphonique |
| E    | Entrevue téléphonique + Signes vitaux + Profil sanguin |
| F    | Entrevue téléphonique + Signes vitaux + Profil sanguin + Rapport du médecin traitant |

**Rapport du médecin traitant** : Commandé par le tarificateur.

### Notes pour Immigrants (Moins d'un An au Canada - Vie Seulement)

- Âges 0-60 jusqu'à 100 000 $ : Déclaration d'assurabilité.
- Âges >60 ans ou >100 000 $ : Entrevue téléphonique, signes vitaux et profil sanguin.

**Profil sanguin** : Inclut VIH et urine.  
**Entrevue téléphonique et signes vitaux** : Peuvent être remplacés par examen paramédical.