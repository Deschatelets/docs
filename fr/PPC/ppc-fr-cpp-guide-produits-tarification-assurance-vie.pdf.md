---
# Document Metadata
document_id: "ppc-fr-cpp-guide-produits-tarification-v1.0"
document_type: product_and_pricing_guide
schema_version: "2.0"
version: 1.0
document_title: "Guide de Produits et de Tarification - Plan de Protection du Canada"
full_product_name: "Product and Pricing Guide for Simplified Life Insurance (Plan de Protection du Canada)"
total_pages: 30
last_updated: "2024-04"
effective_date: "2024-04-01"

# Insurer Information
insurer:
  name: "Plan de Protection du Canada"
  id: "ppc"
  legal_name: "Plan de Protection du Canada"
  parent_company: "Financière Foresters"
  underwriter: "Ordre indépendant des Foresters"

# Product Information
product:
  name: "Assurance Vie Sans Exigence Médicale"
  id: "simplified-life-insurance"
  owner: "Plan de Protection du Canada"
  type: "simplified_life_insurance"
  type_fr: "Assurance vie à émission simplifiée"
  underwriting_type: "simplified_underwriting"
  underwriting_type_fr: "Souscription simplifiée"
  product_variants:
    - "Vie Acceptance Garantie"
    - "Vie Différée"
    - "Élite Différée"
    - "Élite Simplifiée"
    - "Préférentielle"
    - "Élite Préférentielle"

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
  min_amount: 5000
  max_amount: 1000000
  currency: CAD
  age_range: [18, 80]
  age_groups:
    - "18-60"
    - "61-70"
    - "71-75"
    - "76-80"

# Tags for Searchability
tags:
  - guide-produits-tarification
  - assurance-vie-simplifiee
  - sans-exigence-medicale
  - ppc
  - plan-protection-canada
  - foresters
  - vie-acceptance-garantie
  - elite-preferentielle

# Machine-Readable Features
features:
  product_comparison: true
  medical_conditions: true
  pricing_guidelines: true
  underwriting_criteria: true
  modification_process: true

# Disclaimer
disclaimer: "Ce guide est fourni à titre informatif seulement et est sous réserve de modifications sans préavis."

# Document Structure Map
sections:
  - id: resume_executif
    name: "Résumé Exécutif"
    type: overview
    line_start: 12
  - id: apercu_produit
    name: "Aperçu du Produit"
    type: product_overview
    line_start: 37
  - id: regimes_base
    name: "Régimes de Base Disponibles"
    type: products
    line_start: 72
  - id: avenants_regimes_temporaires
    name: "Avenants et Régimes Temporaires"
    type: riders
    line_start: 139
  - id: modifications_certificat
    name: "Modifications de Certificat"
    type: modifications
    line_start: 186
  - id: exigences_age_montant
    name: "Exigences d'Âge et de Montant"
    type: requirements
    line_start: 241
  - id: lignes_directrices_tarification
    name: "Lignes Directrices de Tarification"
    type: pricing
    line_start: 347
  - id: statut_fumeur
    name: "Statut de Fumeur"
    type: underwriting
    line_start: 433
  - id: age_assurance
    name: "Âge d'Assurance"
    type: underwriting
    line_start: 458
  - id: residents_permanents
    name: "Résidents Permanents"
    type: eligibility
    line_start: 464
  - id: validite_documents
    name: "Validité des Documents"
    type: procedures
    line_start: 478
  - id: troubles_medicaux
    name: "Troubles Médicaux et Conditions"
    type: medical_conditions
    line_start: 492
  - id: informations_contact
    name: "Informations de Contact"
    type: contact
    line_start: 537

# Document Segments (Original PDF)
document_segments:
  - name: "Guide de Produits et de Tarification"
    pages: 0-30
    confidence: High

# Document Statistics
statistics:
  total_products: 6
  total_riders: 3
  total_medical_conditions: 50
  total_sections: 13
  coverage_amounts:
    min: 5000
    max: 1000000
  age_ranges:
    min: 18
    max: 80
  product_categories:
    guaranteed_issue: 1
    deferred: 2
    simplified: 2
    preferred: 2
  modification_types: 5
  underwriting_criteria: 8
---

## Résumé Exécutif

Plan de Protection du Canada offre des produits d'assurance vie sans exigence médicale pour diverses catégories de clients, avec des protections allant jusqu'à 1 000 000 $ selon le régime choisi.

### Points Clés du Document

**Produits principaux**:
- Vie Acceptance Garantie (10K-50K $)
- Vie Différée (5K-75K $)
- Élite Différée (5K-350K $)
- Élite Simplifiée (5K-500K $)
- Préférentielle (50K-1M $)
- Élite Préférentielle (500K-1M $)

**Caractéristiques uniques**:
- Aucune question sur l'historique de refus
- Processus de souscription simplifié
- Protection immédiate pour décès accidentel
- Avenants disponibles (temporaire, enfant, hospitalisation)

**Exigences médicales**:
- Sans exigence médicale pour la plupart des régimes
- Examen paramédical requis pour montants élevés
- Profil sanguin pour Élite Préférentielle

## 1. Aperçu du Produit

### 1.1 Profil des Clients Potentiels

#### 1.1.1 Clients avec Historique de Refus

**Profil**: Clients ayant eu des demandes refusées, acceptées moyennant surprime ou reportées
- **Avantage**: Aucune question sur l'historique de refus
- **Protection maximale**: 500 000 $ sans exigence médicale

#### 1.1.2 Clients Évitant la Souscription Traditionnelle

**Profil**: Clients en bonne santé préférant éviter le processus de souscription traditionnel
- **Avantage**: Protection fiable rapide sans examen médical
- **Processus**: Simplifié et accéléré

#### 1.1.3 Clients Cherchant Couverture Dépenses Finales

**Profil**: Clients cherchant à couvrir frais funéraires et dettes impayées
- **Solution**: Protection abordable pour frais funéraires
- **Focus**: Couverture des dépenses finales

#### 1.1.4 Génération Y (Jeunes Professionnels)

**Profil**: Jeunes professionnels avec mode de vie actif
- **Contexte**: Fondation de famille, achat de maison
- **Protection maximale**: 1 000 000 $
- **Processus**: Simple et rapide

#### 1.1.5 Personnes avec Maladies Graves

**Profil**: Clients non assurés en raison de maladies graves ou facteurs de risque
- **Protection maximale**: 50 000 $ garantie
- **Condition**: Sans exigence médicale

### 1.2 Régimes de Base Disponibles

#### 1.2.1 Vie Acceptance Garantie

**Profil client**: Garantie d'assurabilité, peu importe l'état de santé
**Protection**:
- **Montant**: 10 000 $ - 50 000 $
- **Âge d'émission**: 18-60 ans (min 10 000 $), 61-75 ans (min 5 000 $)
- **Maximum**: 50 000 $

**Conditions de paiement**:
- Capital total payable après 2 ans de la date d'entrée en vigueur
- Paiement immédiat si décès accidentel

#### 1.2.2 Vie Différée

**Profil client**: Problèmes de santé graves
**Protection**:
- **Montant**: 10 000 $ - 75 000 $ (18-60 ans), 5 000 $ - 50 000 $ (61-80 ans)
- **Âge d'émission**: 18-60 ans, 61-80 ans

**Conditions de paiement**:
- Capital total payable après 2 ans de la date d'entrée en vigueur
- Paiement immédiat si décès accidentel

#### 1.2.3 Élite Différée

**Profil client**: Problèmes de santé moins graves
**Protection**:
- **Montant**: 10 000 $ - 350 000 $ (18-60 ans), 5 000 $ - 350 000 $ (61-80 ans)
- **Âge d'émission**: 18-60 ans, 61-80 ans

**Conditions de paiement**:
- 50% du capital assuré si décès non-accidentel en 2e année
- Capital total payable après 2 ans de la date d'entrée en vigueur
- Paiement immédiat si décès accidentel

#### 1.2.4 Élite Simplifiée

**Profil client**: Assez bonne santé ou pratique de sports extrêmes
**Protection**:
- **Montant**: 10 000 $ - 500 000 $ (18-60 ans), 5 000 $ - 350 000 $ (61-80 ans)
- **Âge d'émission**: 18-60 ans, 61-80 ans

**Conditions de paiement**:
- Capital total payable à n'importe quel moment

#### 1.2.5 Préférentielle

**Profil client**: Bonne santé et besoin d'une protection rapide
**Protection**:
- **Montant**: 50 000 $ - 1 000 000 $
- **Âge d'émission**: 18-80 ans
- **Particularité**: Sans exigence médicale jusqu'à 500 000 $

**Conditions de paiement**:
- Capital total payable à n'importe quel moment

#### 1.2.6 Élite Préférentielle

**Profil client**: Bonne santé et besoin d'une protection rapide aux taux les plus bas
**Protection**:
- **Montant**: 500 000 $ - 1 000 000 $
- **Âge d'émission**: 18-80 ans

**Conditions de paiement**:
- Capital total payable à n'importe quel moment
### 1.3 Avenants et Régimes Temporaires

#### 1.3.1 Assurance Temporaire (Disponible avec Élite Différée, Élite Simplifiée, Préférentielle et Élite Préférentielle)

**Temporaire 10 ans**:
- **Âge d'émission**: 18-70 ans
- **Montant minimum**: 25 000 $

**Temporaire 20 ans**:
- **Âge d'émission**: 18-60 ans
- **Montant minimum**: 25 000 $
- **Maximum**: Dépend de l'âge et du régime de base

**Temporaire 25 ans**:
- **Âge d'émission**: 18-55 ans
- **Montant minimum**: 25 000 $

**Assurance temporaire à capital décroissant de 25 ans**:
- **Âge d'émission**: 18-60 ans
- **Montant minimum**: 25 000 $

#### 1.3.2 Avenants Supplémentaires

**Prestation de décès accidentel**:
- **Âge d'émission**: 18-65 ans
- **Montant minimum**: Une fois le montant de la protection ou 10 000 $ (le moins élevé)
- **Montant maximum**: Cinq fois le montant de la protection ou 250 000 $ (le moins élevé)

**Assurance temporaire pour enfant**:
- **Âge d'émission**: 18-60 ans (parent)
- **Montants disponibles**: 5 000 $, 10 000 $ ou 15 000 $

**Prestation hospitalière**:
- **Âge d'émission**: 18-65 ans
- **Montants disponibles**: 25 $/jour, 50 $/jour ou 100 $/jour

### 1.4 Notes Importantes

**Tarification**:
- Sans exigence médicale
- Peut être soumise à la tarification supplémentaire
- Soumise à la tarification supplémentaire

**Notes**:
1. Les maximums indiqués s'appliquent aux protections combinées de tout certificat d'assurance vie et d'assurance temporaire sous une même catégorie de régime.
2. Le minimum est de 50 000 $ pour un régime ou avenant d'assurance temporaire Préférentielle ou un avenant d'assurance temporaire Élite Préférentielle, et 500 000 $ pour un régime temporaire Élite Préférentielle.

## 2. Modifications de Certificat

### 2.1 Exigences pour Modifications

#### 2.1.1 Ajout d'Avenants

**Ajout d'un nouvel avenant** (Prestation de décès accidentel et Prestation hospitalière):
- **Exigence**: Demande de modification du certificat d'assurance vie en vigueur
- **Applicabilité**: Tous les âges et tous les montants

#### 2.1.2 Assurance Temporaire pour Enfant

**Modification d'une assurance temporaire pour enfant** (l'enfant de l'assuré doit avoir entre 30 jours et 18 ans):
- **Exigence**: Demande de modification du certificat d'assurance vie en vigueur
- **Applicabilité**: Tous les âges et tous les montants

**Opérations disponibles**:
- Ajouter une assurance temporaire pour enfant
- Ajouter un enfant à une assurance temporaire pour enfant en vigueur
- Augmenter la prestation temporaire pour enfant
- **Exigence supplémentaire**: Questionnaire applicable à l'assurance temporaire pour enfant

**Transformation d'une assurance temporaire pour enfant**:
- **Exigence**: Formulaire de demande de transformation d'une assurance temporaire pour enfant
- **Timing**: Peut avoir lieu en tout temps après le 20e anniversaire de naissance de l'enfant assuré, mais au plus tard avant son 21e anniversaire de naissance

#### 2.1.3 Remise en Vigueur

**Certificat échu au cours des trois (3) derniers mois**:
- **Exigence**: Proposition de remise en vigueur – version courte

**Certificat échu depuis plus de trois (3) mois**:
- **Exigence**: Proposition de remise en vigueur – version longue

#### 2.1.4 Changement de Statut

**Changement au statut de non-fumeur**:
- **Exigence**: Demande de modification pour bénéficier des taux de non-fumeur
- **Condition générale**: L'assuré doit avoir cessé de faire usage de toute substance ou de tout produit contenant du tabac et de la nicotine, à l'exclusion de 12 cigares par année, au cours des douze (12) derniers mois
- **Condition marijuana**: Les proposants qui ont fait usage de marijuana autrement que par voie orale plus de six (6) fois par semaine ne seront pas pris en considération pour les taux de non-fumeurs
- **Condition taux préférentiels élite**: L'assuré doit avoir cessé de faire usage de toute substance contenant du tabac, de la nicotine, y compris les cigares, ou de la marijuana sous toutes ses formes au cours des vingt-quatre (24) derniers mois
- **Documentation**: Demande de modification du certificat d'assurance vie en vigueur

**Capital assuré réduit**:
- **Exigence**: Demande de modification du certificat d'assurance vie en vigueur

#### 2.1.5 Transformation de Certificat

**Transformation du certificat ou d'un avenant d'assurance vie temporaire**:
- **Exigence**: Formulaire de demande de transformation d'une assurance vie temporaire
- **Timing**: Au plus tôt, 60 jours avant le 2e anniversaire du certificat
- **Limite**: La transformation doit avoir lieu avant l'anniversaire du certificat le plus proche du soixante-dixième (70e) anniversaire de l'assuré
- **Restriction**: Ne s'applique pas à l'assurance temporaire à capital décroissant de 25 ans
- **Condition**: Sous réserve du minimum prévu par le régime et des limites d'âge à l'émission

## 3. Exigences d'Âge et de Montant

### 3.1 Régimes Préférentielle et Élite Préférentielle

**Responsabilité du conseiller**: Il revient au conseiller d'établir les exigences habituelles liées à l'âge et au montant d'assurance en se basant sur le tableau.

**Réserve de l'assureur**: Pour déterminer l'admissibilité à l'assurance, Financière Foresters se réserve le droit de tenir compte des caractéristiques de risque autres que celles mentionnées dans les questions de la proposition.

#### 3.1.1 Proposition et Montant d'Assurance

**Calcul du total**: Le total de tous les certificats d'assurance vie simplifiée et sans exigence médicale de Plan de protection du Canada, en suspens ou émis au cours des 12 derniers mois, doit être pris en compte pour déterminer les exigences relatives à l'âge et au montant d'assurance décrites.

#### 3.1.2 Lignes Directrices Médicales

**Rapport du médecin traitant (RMT)**:
- Nous nous réservons le droit de demander un RMT

**Test diagnostique**:
- Cela exclut tout résultat de tests génétiques

#### 3.1.3 Tableau des Exigences par Régime

**Régime Préférentielle**:

| Montant d'assurance | Âge 18-70 | Âge 71-80 |
|---------------------|-----------|-----------|
| 50 001 $ à 500 000 $ | SEM | EP + PS |
| 500 001 $ à 1 000 000 $ | EP + PS | EP + PS |

**Régime Élite Préférentielle**:

| Montant d'assurance | Âge 18-70 | Âge 71-80 |
|---------------------|-----------|-----------|
| 500 000 $ à 1 000 000 $ | EP + PS | EP + PS |

**Légende**:
- **SEM**: Sans exigence médicale
- **EP**: Examen paramédical
- **PS**: Profil sanguin

**Note importante**: Pour l'assurance Élite Préférentielle, un examen paramédical et un profil sanguin sont exigés dans tous les cas.

#### 3.1.4 Critères de Tarification Élite Préférentielle

**Tabac**:

| Statut | Critères |
|--------|----------|
| **Non-fumeur** | Aucun usage de tabac au cours des 24 derniers mois (y compris les produits contenant de la nicotine, la marijuana et les produits de sevrage tabagique, le vapotage et les cigarettes électroniques) |
| **Fumeur** | Tabac à chiquer, cigarettes, pipes, cigares, marijuana sous toutes ses formes |

**Pression artérielle** (égale ou inférieure à):

| Âge | Non-fumeur | Fumeur |
|-----|------------|--------|
| ≤ 45 ans | 140/90 | 140/90 |
| 46-80 ans | 150/90 | 150/90 |

**Cholestérol** (égal ou inférieur à):

| Âge | Non-fumeur | Fumeur |
|-----|------------|--------|
| ≤ 45 ans | 220/5,5 C ou 5,7/5,5 UI | 220/5,5 C ou 5,7/5,5 UI |
| 46-80 ans | 240/6,0 C ou 6,2/6,0 UI | 240/6,0 C ou 6,2/6,0 UI |

**Antécédents familiaux**:
- **Critère commun**: Maximum d'un diagnostic de maladie cardiaque, de cancer ou d'accident vasculaire cérébral ou de décès par maladie cardiaque, cancer ou accident vasculaire cérébral chez les parents ou les frères et sœurs avant l'âge de 60 ans
- **Applicable à**: Non-fumeurs et fumeurs

#### 3.1.5 Tableau de Constitution (Poids Maximal selon la Taille)

**Poids maximal autorisé selon la taille**:

| Taille | Poids Max (lb) |
|--------|----------------|
| 4'8" | 126 |
| 4'9" | 130 |
| 4'10" | 135 |
| 4'11" | 140 |
| 5'0" | 147 |
| 5'1" | 152 |
| 5'2" | 157 |
| 5'3" | 163 |
| 5'4" | 168 |
| 5'5" | 173 |
| 5'6" | 178 |
| 5'7" | 183 |
| 5'8" | 183 |
| 5'9" | 190 |
| 5'10" | 196 |
| 5'11" | 201 |
| 6'0" | 212 |
| 6'1" | 219 |
| 6'2" | 225 |
| 6'3" | 232 |
| 6'4" | 232 |
| 6'5" | 238 |
| 6'6" | 244 |
| 6'7" | 251 |

**Notes importantes**:
- Les poids sont exprimés en livres (lb)
- Ces limites s'appliquent à tous les régimes d'assurance
- Pour les personnes dépassant ces limites, consultez l'équipe de tarification
- Les tailles sont arrondies au pouce le plus proche

## 4. Lignes Directrices de Tarification

### 4.1 Fournisseurs de Services Autorisés

#### 4.1.1 Laboratoires - Examen Paramédical

**Fournisseurs autorisés**:
- ExamOne
- Medifast
- Dynacare

### 4.2 Politiques Spéciales

#### 4.2.1 Voyage à l'Étranger

**Durée de voyage**:
- **Moins de 12 semaines consécutives**: Assurable dans tous les régimes, sauf Élite Préférentielle
- **Plus de 12 semaines consécutives**: Consulter l'équipe de tarification

#### 4.2.2 Vérification par Téléphone

**Processus**:
- Un tiers peut téléphoner à l'assuré ou au titulaire du certificat pour vérifier les renseignements
- La conversation téléphonique est enregistrée

**Exception**: Pour les régimes Préférentielle et Élite Préférentielle, la vérification par téléphone sera supprimée si un examen paramédical est exigé

#### 4.2.3 Vérification des Dossiers Médicaux

**Critères**:
- Les dossiers médicaux seront demandés pour au moins 10% de toutes les affaires collectivement reçues
- **Applicable à**: Assurance vie différée, Élite Différée, Élite Simplifiée
- **Timing**: Après l'approbation et l'établissement aux fins de vérification des antécédents médicaux

#### 4.2.4 Codes Plan F

**Définition**: Les codes MIB Plan F sont des codes d'autres assureurs associés au titulaire du certificat actif auprès de Plan de protection du Canada

**Processus**:
- MIB fournira les codes Plan F, le cas échéant, pendant une période de deux ans après l'établissement du certificat
- Les dossiers médicaux seront examinés plus en profondeur

### 4.3 Assurance Temporaire pour Enfant

#### 4.3.1 Admissibilité

**Critères d'admissibilité**:
Chaque enfant naturel ou adopté de l'assuré proposé qui :
- est âgé d'au moins 30 jours, mais de moins de 18 ans et qui est spécifiquement désigné dans la proposition d'assurance, et
- est âgé d'au moins 30 jours, mais de moins de 18 ans et qui est né ou adopté après la date d'entrée en vigueur du présent avenant

#### 4.3.2 Couverture Automatique

**Enfant né ou adopté pendant la durée de l'avenant**:
- Automatiquement couvert à compter de l'âge de trente (30) jours
- **Exigence**: Demande par écrit indiquant le nom et la date de naissance de l'enfant
- **Condition**: L'enfant doit être vivant
- **Prime**: Ne change pas si des enfants supplémentaires sont assurés

### 4.4 Règles Générales

#### 4.4.1 Âge Réel

**Utilisation**: L'âge réel des proposants est utilisé pour répondre aux questions du formulaire du proposant

#### 4.4.2 Remplacements

**Processus**: Pour les remplacements internes ou externes, veuillez remplir un formulaire de remplacement lors de la demande

#### 4.4.3 Antidatation

**Régimes sans antidatation**:
- Vie Acceptance Garantie
- Vie Différée
- Élite Différée

**Régimes avec antidatation possible**:
- Élite Simplifiée
- Préférentielle
- Élite Préférentielle

**Conditions d'antidatation**:
- **Période maximale**: Jusqu'à 6 mois à partir de la date de l'approbation de la tarification
- **Primes additionnelles**: Requises au moment de l'émission pour couvrir les primes exigibles au cours de la période antidatée
- **Restriction**: Aucune antidatation si la personne est plus âgée que l'âge à l'émission maximal (ex: personne de 81 ans ne peut pas être antidatée à 80 ans si l'âge maximal d'émission est 80 ans)

## 5. Statut de Fumeur

### 5.1 Tous les Régimes (Sauf Élite Préférentielle)

#### 5.1.1 Définition de Fumeur

**Substances contenant du tabac ou de la nicotine**:
- Usage au cours des douze (12) derniers mois
- **Exception**: 12 cigares ou moins par année

**Marijuana**:
- Usage plus de six (6) fois par semaine au cours des 12 derniers mois
- **Formes incluses**: Toutes les formes
- **Exclusions**: Huile de CBD ou produits comestibles
- **Définition voie orale**: Usage de marijuana autrement que par inhalation

### 5.2 Assurance Élite Préférentielle

#### 5.2.1 Définition de Fumeur

**Critères**:
- Usage par quelque moyen que ce soit (y compris vaporisateur électronique ou « vapotage »)
- **Substances**: Tabac, nicotine (y compris cigares), marijuana
- **Période**: Au cours des 24 derniers mois

## 6. Âge d'Assurance

### 6.1 Calcul des Primes

**Méthode**: Tous les produits utilisent l'âge de l'anniversaire le plus proche afin de déterminer les primes

## 7. Résidents Permanents

### 7.1 Critères d'Admissibilité

**Citoyens canadiens et immigrants reçus**:
- Admissibles à tous les régimes

**Demandeurs de statut de résident permanent**:
- Non admissibles (demande présentée mais documents non reçus)

**Permis de travail ou d'études**:
- Admissibles avec limitation
- **Capital assuré maximum**: 250 000 $

## 8. Validité des Documents

### 8.1 Régimes Préférentielle et Élite Préférentielle

#### 8.1.1 Période de Validité

**Examen paramédical**:
- **Validité**: Jusqu'à 6 mois aux fins de tarification
- **Condition**: Le certificat doit avoir été émis et la première prime reçue au cours de cette période
- **Si > 90 jours**: Déclaration de bonne santé exigée à la remise du certificat

**Profil sanguin**:
- **Validité**: Maximum 6 mois aux fins de tarification

## 9. Troubles Médicaux et Conditions

### 9.1 Admissibilité Élite Simplifiée

**Note générale**: Les personnes ayant une affection mise en évidence peuvent être admissibles à l'assurance Élite Simplifiée selon l'échéancier, les facteurs et les détails.

### 9.2 Conditions Médicales Détaillées

> **Note**: Cette section contient des informations détaillées sur les conditions médicales et leurs critères d'admissibilité. Pour des informations complètes, consultez le document original.

**Format des entrées**:
- **Condition**: Nom de la condition médicale
- **Définition**: Description médicale
- **Critères**: Période, facteurs et détails d'évaluation
- **Admissibilité**: Régimes d'assurance disponibles
- **Référence**: Section du formulaire de proposition

#### 9.2.1 Exemples de Conditions

**Abus de drogues**:
- **Définition**: Héroïne, narcotiques, barbituriques, médicaments psychotropes (excluant marijuana), cocaïne
- **Critères**: Médicaments non prescrits dans les 12 derniers mois
- **Admissibilité**: Vie Acceptance Garantie, Élite Différée, Élite Simplifiée, possiblement préférentielle

**Accident ischémique transitoire (AIT)**:
- **Définition**: Interruption temporaire de la circulation sanguine cérébrale
- **Critères**: Avant 40 ans, dans les 2 dernières années, dans les 4 dernières années
- **Admissibilité**: Vie Acceptance Garantie, Vie Différée, Élite Différée, Élite Simplifiée

**Accident vasculaire cérébral (AVC)**:
- **Définition**: Interruption de la circulation sanguine dans une partie du cerveau
- **Critères**: Avant 40 ans, dans les 2 dernières années, en combinaison avec diabète
- **Admissibilité**: Vie Acceptance Garantie, Vie Différée, Élite Différée, Élite Simplifiée
**Alcoolisme**:
- **Définition**: Consommation compulsive et incontrôlée d'alcool entraînant des problèmes de santé
- **Critères**: Admission en hôpital ou centre de traitement dans les 12 derniers mois, 5 dernières années, ou plus de 5 ans
- **Admissibilité**: Vie Acceptance Garantie, Élite Différée, Élite Simplifiée, possiblement préférentielle

**Anévrisme**:
- **Définition**: Dilatation anormale d'une partie d'une artère (aorte, cerveau, intestins, jambe, thorax, rate)
- **Critères**: Avant 40 ans, dans les 2 dernières années, dans les 4 dernières années, ou plus de 5 ans
- **Admissibilité**: Vie Acceptance Garantie, Vie Différée, Élite Différée, Élite Simplifiée

> **Note**: Le document original contient une liste complète de conditions médicales avec leurs critères détaillés. Cette section résumée présente les principales conditions pour faciliter la compréhension générale.

## 10. Informations de Contact

### 10.1 Coordonnées

**Plan de Protection du Canada**
- **Adresse**: 789, chemin Don Mills, Toronto, ON, Canada M3C 1T9
- **Téléphone**: 877 796-9090
- **Courriel**: tarification@ppcqc.ca ou ventesqc@cpp.ca
- **Site web**: ppcquebec.ca

### 10.2 Mentions Légales

**Droits d'auteur**: © 2024 Plan de Protection du Canada

**Marques de commerce**: PLAN DE PROTECTION DU CANADA et le logo sont des marques de commerce de Plan de protection du Canada, une société de la Financière Foresters.

**Assureur**: L'assurance vie sans exigence médicale et à émission simplifiée sont souscrites par l'Ordre indépendant des Foresters.

**Référence**: CP113

---

## Mots-Clés pour Indexation

**Produits**: Assurance vie, Vie Acceptance Garantie, Vie Différée, Élite Différée, Élite Simplifiée, Préférentielle, Élite Préférentielle

**Caractéristiques**: Sans exigence médicale, souscription simplifiée, protection immédiate, décès accidentel

**Avenants**: Assurance temporaire, assurance enfant, prestation hospitalière, décès accidentel

**Critères**: Âge d'émission, montants minimum/maximum, statut fumeur, conditions médicales

**Processus**: Modification certificat, antidatation, remise en vigueur, transformation

---

## Conclusion

Ce document restructuré présente les informations essentielles du Guide de produits et de tarification de Plan de Protection du Canada de manière organisée et accessible. La structure hiérarchique facilite la navigation et l'indexation par les systèmes de recherche et d'IA.

**Principales améliorations apportées**:
- Structure hiérarchique claire avec numérotation cohérente
- Métadonnées documentaires pour l'indexation
- Résumé exécutif avec points clés
- Formatage standardisé des tableaux et listes
- Mots-clés pour l'optimisation RAG
- Sections bien délimitées pour la recherche sémantique

**Utilisation recommandée**:
- Consultation rapide des produits et critères
- Recherche par mots-clés spécifiques
- Indexation automatique par systèmes IA
- Référence pour conseillers en assurance
