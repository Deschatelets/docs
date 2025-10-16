---
# Document Metadata
document_id: "ia-fr-acces-vie-questionnaire-prequalification-v1.0"
document_type: questionnaire
schema_version: "2.0"
version: 1.0
document_title: "Questionnaire de Préqualification - Accès Vie iA"
full_product_name: "Accès Vie Prequalification Questionnaire (iA Groupe financier)"
total_pages: 5
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
  underwriting_type: "prequalification_questionnaire"
  underwriting_type_fr: "Questionnaire de préqualification"

# Classification
language: fr-CA
region: QC
target_audience: 
  - clients
  - representatives
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
  - questionnaire
  - prequalification
  - assurance-vie
  - ia
  - acces-vie
  - medical_history
  - eligibility

# Machine-Readable Features
features:
  mib_verification: false
  fast_decision: true
  full_underwriting: false
  electronic_application: true
  simplified_issue: true
  questionnaire_based: true

# Disclaimer
disclaimer: "Ce questionnaire est à titre indicatif pour évaluer l'admissibilité. Les décisions finales sont prises par iA Groupe financier."

# Document Structure Map
sections:
  - id: etape-1
    name: "Étape 1 : Différé"
    type: questionnaire_step
    line_start: 17
  - id: etape-2
    name: "Étape 2 : Différé Plus"
    type: questionnaire_step
    line_start: 60
  - id: etape-3
    name: "Étape 3 : Immédiat Plus"
    type: questionnaire_step
    line_start: 108
  - id: guide-reference
    name: "Guide de Référence Rapide"
    type: reference
    line_start: 132
  - id: limites
    name: "Limites de la Prestation de Décès"
    type: limitations
    line_start: 173
  - id: avantages
    name: "Avantages du Produit"
    type: benefits
    line_start: 191

# Document Statistics
statistics:
  total_steps: 3
  total_questions: 50
  steps:
    etape_1: 5
    etape_2: 10
    etape_3: 6
  medical_conditions_covered: 50
  decision_types:
    access_garanti: true
    differe: true
    differe_plus: true
    immediat_plus: true
  requirement_types:
    questionnaire: true
    weight_table: true
    family_history: true
    travel_risk: true
---
## Aperçu du Produit

**Accès Garanti** : Si l'état de santé du client ne permet pas l'admissibilité à l'Étape 1 (Différé), l'acceptation est garantie avec une couverture jusqu'à 50 000 $ (25 000 $ pour 50 ans et +, 10 000 $ pour enfants).

Le processus de préqualification est rapide et facile, permettant de qualifier les clients en quelques minutes via EVO. Une fois qualifié, remplissez la proposition et recevez le contrat dans une semaine.

## Structure des Étapes de Qualification {#structure-des-etapes}

Le questionnaire détermine l'admissibilité aux niveaux suivants :

- **Étape 1 : Différé** - Protection permanente (V100), max 100 000 $.
- **Étape 2 : Différé Plus** - Protections permanente (V100) et temporaires (T15, T20, T25), max 350 000 $.
- **Étape 3 : Immédiat Plus** - Protections permanente (V100) et temporaires (T15, T20, T25), max 500 000 $.
- **Accès Garanti** - Couverture limitée pour cas non admissibles.

## Étape 1 : Différé {#etape-1-differe}

**Protection** : Permanente (V100), max 100 000 $.

### Réponses Affirmatives
- Admissible à Accès Garanti.

### Réponses Négatives
- Admissible à 100 000 $ (V100).
- Passer à Étape 2.

### Questions de Qualification {#questions-etape-1}

1. **Au cours de votre vie**, avez-vous reçu un diagnostic et/ou été traité pour l'une des maladies suivantes :
   - **a** Syndrome immunodéficitaire acquis (SIDA) ou subi des tests séropositifs au VIH ?
   - **b** Trouble du rythme cardiaque (arythmies) nécessitant pacemaker, insuffisance cardiaque ou cardiomyopathie ?
   - **c** Fibrose kystique, Alzheimer, démence, chorée de Huntington, Parkinson, SLA (maladie de Lou Gehrig), dystrophie musculaire, myotonique, ou ataxie ?
   - **d** Maladie respiratoire chronique requérant oxygène quotidien (excluant apnée du sommeil) ?
   - **e** (Pour <18 ans) Diabète type 1, paralysie cérébrale, trouble cardiaque congénital, trisomie 21 ou TSA ?

2. **Au cours des 3 dernières années**, avez-vous souffert de ou été traité pour leucémie, lymphome, tumeur maligne ou cancer (sauf carcinome basocellulaire) ?

3. **Au cours des 12 derniers mois** :
   - **a** Reconnu coupable d'infraction criminelle (incl. conduite affaiblie) ou en attente de jugement ?
   - **b** Consommé drogues dures non prescrites, ou méthadone (avec/sans ordonnance) ?

4. **Présentement** :
   - **a** Hospitalisé ou en établissement de soins (incl. centre pour perte d'autonomie) ?
   - **b** Confié au lit ou fauteuil roulant ?
   - **c** Sous investigation diagnostique ?

5. **Pour 15 ans et +**, votre poids dépasse-t-il le tableau ci-dessous ?

| Taille (pieds) | Poids (livres) | Taille (mètres) | Poids (kg) |
|----------------|----------------|-----------------|------------|
| 4'8" – 4'10"  | 230            | 1,42 – 1,49     | 105        |
| 4'11" – 5'1"  | 260            | 1,50 – 1,56     | 118        |
| 5'2" – 5'4"   | 285            | 1,57 – 1,64     | 129        |
| 5'5" – 5'7"   | 310            | 1,65 – 1,72     | 141        |
| 5'8" – 5'10"  | 335            | 1,73 – 1,79     | 152        |
| 5'11" – 6'1"  | 365            | 1,80 – 1,87     | 165        |
| 6'2" – 6'4"   | 390            | 1,88 – 1,95     | 177        |
| 6'5" – 6'7"   | 415            | 1,96 – 2,01     | 188        |

## Étape 2 : Différé Plus {#etape-2-differe-plus}

**Protection** : Permanente (V100) et temporaires (T15, T20, T25), max 350 000 $.

### Réponses Affirmatives
- Admissible à Étape 1 (Différé).

### Réponses Négatives
- Admissible à 350 000 $ (V100, T15/T20/T25).
- Passer à Étape 3.

### Questions de Qualification {#questions-etape-2}

1. **Pour 15 ans et +**, votre poids dépasse-t-il le tableau ci-dessous ?

| Taille (pieds) | Poids (livres) | Taille (mètres) | Poids (kg) |
|----------------|----------------|-----------------|------------|
| 4'8" – 4'10"  | 190            | 1,42 – 1,49     | 86         |
| 4'11" – 5'1"  | 200            | 1,50 – 1,56     | 91         |
| 5'2" – 5'4"   | 220            | 1,57 – 1,64     | 100        |
| 5'5" – 5'7"   | 240            | 1,65 – 1,72     | 109        |
| 5'8" – 5'10"  | 260            | 1,73 – 1,79     | 118        |
| 5'11" – 6'1"  | 280            | 1,80 – 1,87     | 127        |
| 6'2" – 6'4"   | 300            | 1,88 – 1,95     | 136        |
| 6'5" – 6'7"   | 330            | 1,96 – 2,01     | 149        |

2. **Au cours des 5 dernières années** :
   - **a** Amputation suite à maladie ?
   - **b** Maladie reins/föie chronique (cirrhose, fibrose, hépatite C/autre chronique) ?
   - **c** Greffe organe/moelle ou conseillé ?
   - **d** Traité pour drogues/alcool, groupe soutien, recommandé réduction/traitement ?

3. **Au cours des 3 dernières années** :
   - **a** Crise cardiaque/angine/valves cardiaques :
     - i. Diagnostic/traitement anticoagulant ?
     - ii. Chirurgie (pontage, angioplastie, stent, prothèse) ou en attente ?
   - **b** AVC/ICT/maladie vasculaire bras/jambes (sauf varices/phlébite superficielle) :
     - i. Diagnostic/traitement anticoagulant ?
     - ii. Chirurgie ou en attente ?

4. **Au cours des 12 derniers mois** :
   - **a** Dépression/trouble mental :
     - i. Hospitalisé ?
     - ii. Médication modifiée (ajout/remplacement, dosage) ?
     - iii. Cessé médicaments sans avis médecin ?
   - **b** Chirurgie anévrisme ou en attente ?
   - **c** (Diabète) Médication modifiée (ajout/remplacement, dosage) ?

## Étape 3 : Immédiat Plus {#etape-3-immediat-plus}

**Protection** : Permanente (V100) et temporaires (T15, T20, T25), max 500 000 $.

### Réponses Affirmatives
- Admissible à Étape 2 (Différé Plus).

### Réponses Négatives
- Admissible à 500 000 $ (V100, T15/T20/T25) avec protection immédiate décès.

### Questions de Qualification {#questions-etape-3}

1. **Au cours des 5 dernières années**, leucémie, lymphome, tumeur maligne ou cancer (sauf basocellulaire) ?

2. **Au cours des 12 derniers mois**, poids diminué ≥10 % (sauf régime/accouchement) ?

3. **Au cours des 2 prochaines années** :
   - **a** Voyage en régions guerre/conflit/haut risque ? (Réf. avertissements voyage Canada : https://voyage.gc.ca/voyager/avertissements)
   - **b** Intention résidence hors Canada/USA >6 mois consécutifs ?

4. **Antécédents familiaux** : Membre immédiat (père/mère/frère/sœur) diagnostiqué :
   - **a** Huntington ou polykystique reins avant 60 ans ?
   - **b** (Pour <3 ans) Fibrose kystique ?

## Guide de Référence Rapide {#guide-reference}

Information indicative. Consultez questionnaire pour admissibilité complète.

### État de Santé ou Affections

| État de Santé/Affections | Accès Garanti | Différé | Différé Plus | Immédiat Plus |
|--------------------------|---------------|---------|--------------|---------------|
| Amputation suite maladie | ✓ | ✓ | Admissible si >5 ans ✓ | Admissible si >5 ans ✓ |
| Cholestérol élevé | ✓ | ✓ | ✓ | ✓ |
| Cirrhose foie | ✓ | ✓ | ✗ | ✗ |
| Crise cardiaque/angine/pontage/angioplastie | ✓ | ✓ | Admissible si >3 ans (cond. q.3a Étape 2) ✓ | Admissible si >3 ans (cond. q.3a Étape 2) ✓ |
| Dépression | ✓ | ✓ | Admissible (cond. q.4a Étape 2) ✓ | Admissible (cond. q.4a Étape 2) ✓ |
| Diabète (adulte) | ✓ | ✓ | Admissible si pas changement méd. 1 an ✓ | Admissible si pas changement méd. 1 an ✓ |
| En rémission cancer | ✓ | Admissible si >3 ans ✓ | Admissible si >3 ans ✓ | Admissible si >5 ans ✓ |
| Épilepsie | ✓ | ✓ | ✓ | ✓ |
| Greffe organe | ✓ | ✓ | Admissible si >5 ans ou pas attente ✓ | Admissible si >5 ans ou pas attente ✓ |
| Hépatite C/autre chronique | ✓ | ✓ | ✗ | ✗ |
| Insuffisance rénale | ✓ | ✓ | ✗ | ✗ |
| SIDA/VIH | ✓ | ✗ | ✗ | ✗ |
| Tension artérielle élevée | ✓ | ✓ | ✓ | ✓ |
| **Pour Enfants** | | | | |
| TDA/H | ✓ | ✓ | ✓ | ✓ |
| Asthme important | ✓ | ✓ | ✓ | ✓ |
| Malformation congénitale rein | ✓ | ✓ | ✓ | ✓ |
| Diabète type 1 | ✓ | ✗ | ✗ | ✗ |

### Conditions Non Médicales

| Conditions Non Médicales | Accès Garanti | Différé | Différé Plus | Immédiat Plus |
|---------------------------|---------------|---------|--------------|---------------|
| Cure désintoxication drogues/alcool | ✓ | ✓ | Admissible 5 ans après traitement/groupe soutien ✓ | Admissible 5 ans après traitement/groupe soutien ✓ |
| Mauvais dossier conduite | ✓ | Refusé si conduite affaiblie 12 mois ou attente jugement | Refusé si conduite affaiblie 12 mois ou attente jugement | Refusé si conduite affaiblie 12 mois ou attente jugement |
| Refus 2 dernières années | ✓ | ✓ | ✓ | ✓ |
| Sports dangereux | ✓ | ✓ | ✓ | ✓ |
| Usage drogues dures | ✓ | Admissible si cessé >12 mois ✓ | Admissible si cessé >12 mois ✓ | Admissible si cessé >12 mois ✓ |
| Voyage pays dangereux | ✓ | ✓ | ✓ | Risque évaluer (cond. q.3a Étape 3) |
| Immigrants | ✓ | ✓ | ✓ | ✓ |

## Limites de la Prestation de Décès {#limites-prestation-deces}

*** Note : Limites applicables.

### Accès Garanti
- Décès naturel/suicide : Remboursement primes sans intérêt (2 premières années).
- Décès accidentel : Capital assuré dès émission.

### Différé et Différé Plus
- Décès naturel : Remboursement primes + 3% intérêt simple (2 premières années).
- Décès accidentel : Capital assuré dès émission.
- Suicide : Remboursement primes sans intérêt (2 premières années).

### Immédiat Plus
- Décès naturel : Capital assuré dès émission.
- Décès accidentel : Capital assuré dès émission.
- Suicide : Remboursement primes sans intérêt (2 premières années).

## Avantages du Produit {#avantages}

- **Accessible** : Qualification simple sans examen médical.
- **Simple** : Questionnaire rapide.
- **Pratique** : Remplissage proposition en minutes via EVO ; livraison contrat en 1 semaine.

F13-707(19-11)