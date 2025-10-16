---
# Document Metadata
document_id: "uv-fr-questionnaire-admissibilite-emission-simplifiee-v1.0"
document_type: eligibility_questionnaire
schema_version: "2.0"
version: 1.0
document_title: "Questionnaire d'Admissibilité - Émission Simplifiée Express UV Assurance"
full_product_name: "Eligibility Questionnaire for Simplified Issue Express (UV Assurance)"
total_pages: 21
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
  name: "Émission Simplifiée Express"
  id: "simplified-issue-express"
  owner: "UV Assurance"
  type: "simplified_life_insurance"
  type_fr: "Assurance vie à émission simplifiée"
  underwriting_type: "simplified_underwriting"
  underwriting_type_fr: "Souscription simplifiée"
  product_variants:
    - "Vie Entière Valeurs Élevées"
    - "L'Adaptable"
    - "Vie Entière Payable à 100 ans"
    - "Temporaire Supérieur+"

# Classification
language: fr-CA
region: CA
target_audience:
  - applicants
  - insurance_advisors
  - agents
  - brokers

# Coverage Limits
coverage:
  min_amount: 10000
  max_amount: 150000
  currency: CAD
  age_range: [16, 80]
  age_groups:
    - "16-75"
    - "18-80"
    - "18-65"
    - "18-60"
    - "18-55"

# Tags for Searchability
tags:
  - questionnaire-admissibilite
  - emission-simplifiee
  - express
  - assurance-vie-temporaire
  - assurance-vie-permanente
  - uv-assurance
  - avenant-assurance-dette

# Machine-Readable Features
features:
  eligibility_criteria: true
  medical_questions: true
  lifestyle_questions: true
  debt_insurance_rider: true
  signature_sections: true

# Disclaimer
disclaimer: "Ce questionnaire d'admissibilité est soumis à l'approbation finale de la souscription."

# Document Structure Map
sections:
  - id: vue_ensemble
    name: "Vue d'ensemble"
    type: overview
    line_start: 9
  - id: criteres_admissibilite
    name: "Critères d'admissibilité"
    type: eligibility
    line_start: 26
  - id: section_a_informations_assure
    name: "Section A - Informations sur l'assuré"
    type: personal_info
    line_start: 52
  - id: section_b_assurance_vie_express
    name: "Section B - Assurance vie Express"
    type: questions
    line_start: 128
  - id: section_c_avenant_assurance_dette
    name: "Section C - Avenant Assurance dette"
    type: rider_questions
    line_start: 350
  - id: section_d_signatures
    name: "Section D - Signatures"
    type: signatures
    line_start: 380

# Document Segments (Original PDF)
document_segments:
  - name: "Questionnaire Admissibilité Émission Simplifiée Express"
    pages: 0-21
    confidence: High

# Document Statistics
statistics:
  total_question_sections: 4
  total_questions: 25
  max_coverage_amount: 150000
  total_age_groups: 5
  questionnaire_sections:
    - "personal_information"
    - "life_insurance_express"
    - "debt_insurance_rider"
    - "signatures"
  coverage_amounts:
    min: 10000
    max: 150000
  age_ranges:
    min: 16
    max: 80
---

## Vue d'ensemble

Ce questionnaire d'admissibilité est utilisé pour toute demande d'assurance vie temporaire ou permanente en émission simplifiée Express qui respecte les conditions de montant et d'âge spécifiées.

---

## Table des matières

1. [Vue d'ensemble](#vue-densemble)
2. [Critères d'admissibilité](#critères-dadmissibilité)
3. [Section A - Informations sur l'assuré](#section-a---informations-sur-lassuré)
4. [Section B - Assurance vie Express](#section-b---assurance-vie-express)
5. [Section C - Avenant Assurance dette](#section-c---avenant-assurance-dette)
6. [Section D - Signatures](#section-d---signatures)

---

## Critères d'admissibilité

### Utilisation du questionnaire
Répondre à ce questionnaire pour toute demande d'assurance vie temporaire ou permanente qui respecte les conditions suivantes :

### Montant d'assurance
- **Maximum:** 150 000 $ et moins

### Âges d'admissibilité par produit
- **Vie entière Valeurs Élevées et L'Adaptable:** 16 à 75 ans
- **Vie entière Payable à 100 ans:** 18 à 80 ans
- **T-10, T-15 et T-20:** 18 à 65 ans
- **T-25:** 18 à 60 ans
- **T-30:** 18 à 55 ans

### Conditions d'admissibilité Express
- **NON à toutes les questions:** Admissible pour 150 000 $ et moins
- **OUI à la question 1 de la section B:** Admissible et le taux fumeur s'appliquera au contrat
- **OUI aux questions 7-A, 7-B ou 7-C de la section B:** Doit répondre NON aux sous-questions pour être admissible
- **OUI à la question 9 de la section B:** Doit répondre NON aux sous-questions pour être admissible
- **OUI à toute autre question:** Non-admissible à l'Express

### Combinaison de protections
Une protection de base et un avenant temporaire peuvent être demandés avec le questionnaire Express pourvu que le montant d'assurance total soit de 150 000 $ et moins.

### Autres questionnaires disponibles
- **[Questionnaire Express pour enfant](https://uvassurance.ca/fr-1055A-questionnaire-admissibilite4-emission-simplifiee-enfants.pdf):** 15 jours à 15 ans | 10 000 $ à 150 000 $
- **[Questionnaire Immédiate](https://uvassurance.ca/fr-1053A-questionnaire-admissibilite2-avenant-assurance-dette.pdf):** 18 à 45 ans | 150 001 $ à 499 999 $, 46 à 55 ans | 150 001 $ à 350 000 $, 56 à 65 ans | 150 001 $ à 250 000 $

### Tarification régulière
Pour tout autre montant d'assurance, veuillez vous référer aux exigences de la tarification régulière : **Tableau des exigences d'assurabilité**

---

## Section A - Informations sur l'assuré

### Informations de base
- **1. Nº de proposition:** - 
- **2. Prénom:** - **Nom:** - 
- **3. Date de naissance:** JJ/MM/AAAA

---

## Section B - Assurance vie Express

### Questions d'admissibilité de base

#### 1. Tabagisme
Au cours des douze (12) derniers mois, avez-vous fait usage de cigarettes, cigarillos, cigarettes électroniques (avec ou sans nicotine), petits cigares, pipe, tabac à mâcher, shisha, noix de bétel, timbres nicotiniques, produits de désaccoutumance du tabac ou tabac sous n'importe quelle autre forme ?
- ☐ Oui
- ☐ Non

#### 2. Perte d'autonomie
Êtes-vous hospitalisé ou résidez-vous présentement dans une maison ou un centre de soins infirmiers pour personnes en perte d'autonomie ou vous déplacez-vous en fauteuil roulant ou avez-vous besoin d'aide ou d'assistance pour faire deux ou plusieurs des activités de la vie quotidienne qui sont les suivantes: se laver, se vêtir, se servir des toilettes, être continent, se mouvoir, se nourrir ?
- ☐ Oui
- ☐ Non

#### 3. VIH/SIDA
Avez-vous déjà reçu des soins, consulté ou été diagnostiqué du syndrome d'immunodéficience acquise (SIDA), une affection reliée au SIDA ou avez-vous subi une investigation indiquant la présence du virus de l'immunodéficience humaine (VIH) ou d'anticorps au VIH ?
- ☐ Oui
- ☐ Non

#### 4. Hospitalisation récente (60 derniers jours)
- **a) Hospitalisation ou chirurgie:** Avez-vous été hospitalisé (excluant les hospitalisations reliées à la grossesse) ou avez-vous subi une chirurgie ?
  - ☐ Oui
  - ☐ Non
- **b) Résultats anormaux:** Vous a-t-on informé de résultats anormaux à des tests quels qu'ils soient ?
  - ☐ Oui
  - ☐ Non
- **c) Conseils médicaux:** Un professionnel de la santé vous a-t-il conseillé de passer un test quel qu'il soit, une investigation médicale ou de subir une chirurgie ?
  - ☐ Oui
  - ☐ Non

#### 5. Symptômes non consultés
Avez-vous des symptômes ou avez-vous reçu des résultats anormaux pour lesquels :
- **a) Non consultation:** Vous n'avez pas encore consulté de professionnel de la santé ?
  - ☐ Oui
  - ☐ Non
- **b) En investigation:** Vous êtes présentement en investigation ou en attente d'un diagnostic ?
  - ☐ Oui
  - ☐ Non
- **c) Tests recommandés:** Un professionnel de la santé vous a conseillé de subir un test quel qu'il soit et/ou une chirurgie qui n'auraient pas encore été faits ?
  - ☐ Oui
  - ☐ Non
- **d) Suivis rapprochés:** Un médecin ou un médecin spécialiste vous a recommandé d'avoir des suivis médicaux plus rapprochés qu'à l'habitude ?
  - ☐ Oui
  - ☐ Non

#### 6. Troubles graves (10 dernières années)
Au cours des dix (10) dernières années, avez-vous consulté, reçu des soins, été traité, été diagnostiqué, eu des symptômes ou êtes-vous présentement sous traitement pour les troubles suivants :
- **a) Cancer avancé:** Un cancer avec métastase(s) et/ou ganglion(s) atteint(s), deux (2) types de cancer différents ou une récidive d'un cancer (excluant un carcinome basocellulaire) ?
  - ☐ Oui
  - ☐ Non
- **b) Maladies chroniques:** La fibrose kystique ou une maladie respiratoire chronique qui requiert l'administration quotidienne d'oxygène (excluant l'apnée du sommeil), une maladie rénale chronique ou la maladie polykystique des reins ?
  - ☐ Oui
  - ☐ Non
- **c) Maladies neurologiques:** La démence, la maladie d'Alzheimer, la dystrophie musculaire, la chorée de Huntington, la sclérose latérale amyotrophique (SLA) ou la maladie de Parkinson ?
  - ☐ Oui
  - ☐ Non
- **d) Problèmes cardiaques:** Une insuffisance cardiaque chronique, une cardiomyopathie ou un remplacement de valve cardiaque ?
  - ☐ Oui
  - ☐ Non
- **e) Greffes:** Avez-vous été sur une liste d'attente de dons d'organes ou de moelle osseuse ou avez-vous reçu un don d'organe ou de moelle osseuse (excluant les greffes cornéennes) ?
  - ☐ Oui
  - ☐ Non

#### 7. Troubles cardiovasculaires
Avez-vous déjà consulté, reçu des soins, été traité, été diagnostiqué ou eu des symptômes pour les troubles suivants :

##### a) AVC, AIT, Anévrisme, Maladie coronarienne
- **Diagnostic:** Un accident vasculaire cérébral (AVC), un accident ischémique transitoire (AIT), un anévrisme ou une maladie coronarienne ?
  - ☐ Oui
  - ☐ Non
- **Si oui, répondre aux questions i et ii:**
  - **i. Avant l'âge de 40 ans ?**
    - ☐ Oui
    - ☐ Non
  - **ii. Au cours des trois (3) dernières années ?**
    - ☐ Oui
    - ☐ Non

##### b) Pontage, Angioplastie, Maladie rénale, Stent, Pacemaker, Défibrillateur
- **Diagnostic:** Un pontage coronarien, une angioplastie, une maladie rénale chronique, l'insertion d'un tuteur (stent), d'un stimulateur cardiaque (pacemaker) ou d'un défibrillateur implantable ?
  - ☐ Oui
  - ☐ Non
- **Si oui, répondre aux questions i et ii:**
  - **i. Avant l'âge de 40 ans ?**
    - ☐ Oui
    - ☐ Non
  - **ii. Au cours des trois (3) dernières années ?**
    - ☐ Oui
    - ☐ Non

##### c) Angine de poitrine, Crise cardiaque
- **Diagnostic:** Une angine de poitrine ou une crise cardiaque (infarctus du myocarde) ?
  - ☐ Oui
  - ☐ Non
- **Si oui, répondre aux questions i et ii:**
  - **i. Avant l'âge de 40 ans ?**
    - ☐ Oui
    - ☐ Non
  - **ii. Au cours des trois (3) dernières années ?**
    - ☐ Oui
    - ☐ Non

#### 8. Troubles spécifiques (5 dernières années)
Au cours des cinq (5) dernières années, avez-vous consulté, reçu des soins, été traité, été diagnostiqué, eu des symptômes, ou êtes-vous présentement sous traitement pour les troubles suivants :
- **a) Maladie du foie:** Une maladie du foie chronique (incluant, mais ne se limitant pas à, une cirrhose, une fibrose, une hépatite B ou C) ?
  - ☐ Oui
  - ☐ Non
- **b) Maladie vasculaire:** Une maladie artérielle périphérique ou une maladie vasculaire périphérique ?
  - ☐ Oui
  - ☐ Non
- **c) Cancers spécifiques:** Une leucémie, un lymphome de tout type, un cancer du sein, des ovaires, du col de l'utérus, du poumon, colorectal ou un mélanome malin ?
  - ☐ Oui
  - ☐ Non

#### 9. Diabète insulinodépendant
Souffrez-vous de diabète qui exige la prise d'insuline ?
- ☐ Oui
- ☐ Non
- **Si oui, répondre aux questions a) et b):**
  - **a) Diagnostic ancien:** Avez-vous reçu un diagnostic de diabète de n'importe quel type, il y a plus de 20 ans ?
    - ☐ Oui
    - ☐ Non
  - **b) Modification médication:** Au cours des six (6) derniers mois, votre médication en relation avec le diabète a-t-elle été ajustée ou modifiée (ajout ou remplacement d'un médicament, hausse ou baisse du dosage prescrit) ?
    - ☐ Oui
    - ☐ Non

#### 10. Troubles psychiatriques (24 derniers mois)
Au cours des vingt-quatre (24) derniers mois, avez-vous consulté, reçu des soins, été traité, été diagnostiqué, eu des symptômes, ou êtes-vous présentement sous traitement pour un trouble bipolaire, la schizophrénie, une psychose, un trouble de personnalité limite (borderline) ou avez-vous fait une tentative de suicide ?
- ☐ Oui
- ☐ Non

#### 11. Perte de poids (12 derniers mois)
Au cours des douze (12) derniers mois, en excluant une diète intentionnelle, un changement de style de vie, une chirurgie bariatrique ou une grossesse, votre poids a-t-il diminué de 10 % ou plus ?
- ☐ Oui
- ☐ Non

#### 12. Chirurgie bariatrique (6 derniers mois)
Au cours des six (6) derniers mois, avez-vous subi une chirurgie bariatrique ?
- ☐ Oui
- ☐ Non

#### 13. Voyages à l'étranger (12 prochains mois)
Au cours des douze (12) prochains mois, prévoyez-vous voyager à l'extérieur de l'Amérique du Nord, des Caraïbes (excluant Haïti), du Royaume-Uni ou de l'Union européenne pour un total de plus de douze (12) semaines ?
- ☐ Oui
- ☐ Non

#### 14. Antécédents criminels (3 dernières années)
Au cours des trois (3) dernières années, avez-vous été reconnu coupable d'une infraction criminelle ou d'un acte criminel (incluant la conduite avec facultés affaiblies), ou des accusations d'infraction criminelle ou d'acte criminel (incluant la conduite avec facultés affaiblies) ont-elles été portées contre vous ?
- ☐ Oui
- ☐ Non

#### 15. Usage de drogues (24 derniers mois)
Au cours des vingt-quatre (24) derniers mois :
- **a) Drogues illégales:** Avez-vous fait usage de barbituriques, narcotiques ou opioïdes non prescrits par un professionnel de la santé, héroïne, cocaïne, amphétamines, hallucinogènes, stéroïdes ou autres drogues illégales ou narcotiques analogues ?
  - ☐ Oui
  - ☐ Non
- **b) Conseils de diminution:** Un professionnel de la santé vous a-t-il conseillé de diminuer votre consommation de drogues quelle qu'elle soit (incluant le cannabis) et/ou d'alcool ?
  - ☐ Oui
  - ☐ Non
- **c) Traitement en résidence:** Avez-vous séjourné dans une résidence pour le traitement de l'abus de drogues et/ou d'alcool ?
  - ☐ Oui
  - ☐ Non

---

## Section C - Avenant Assurance dette

### Instructions
Répondez à ce questionnaire uniquement si vous demandez un avenant Assurance dette (invalidité – crédit).

### Critères d'admissibilité
- **Si NON à toutes les questions:** Vous êtes admissible à l'avenant Assurance dette en Express
- **Si OUI à certaines questions:** L'avenant pourrait être transféré en sélection des risques
- **Si OUI aux questions spécifiques:** Vous n'êtes PAS admissible à l'avenant Assurance dette en Express

### Questions d'admissibilité

#### 1. Emploi
Travaillez-vous présentement moins de 20 heures par semaine et 9 mois par année ? Pour être admissible à l'Avenant Assurance dette, vous devez être à l'emploi ou travailleur autonome et au travail à temps plein (ou au minimum 20 heures par semaine et 9 mois par année) ou être en congé parental de ce même emploi.
- ☐ Oui
- ☐ Non

#### 2. Profession non admissible
Pratiquez-vous une profession non admissible ?
- ☐ Oui
- ☐ Non

#### 3. Troubles cardiovasculaires
Avez-vous déjà consulté, reçu des soins, été traité, été diagnostiqué, eu des symptômes ou êtes-vous présentement sous traitement pour les troubles suivants: angine de poitrine, crise cardiaque (infarctus du myocarde), accident vasculaire cérébral (AVC), accident ischémique transitoire (AIT), anévrisme, maladie coronarienne, pontage coronarien, angioplastie, insertion d'un tuteur (stent), pacemaker ?
- ☐ Oui
- ☐ Non

#### 4. Cancer
Avez-vous déjà consulté, reçu des soins, été traité, été diagnostiqué, eu des symptômes ou êtes-vous présentement sous traitement pour tout type de cancer (excluant un carcinome basocellulaire) ?
- ☐ Oui
- ☐ Non

#### 5. Troubles spécifiques (5 dernières années)
Au cours des cinq (5) dernières années, avez-vous déjà consulté, reçu des soins, été traité, été diagnostiqué, eu des symptômes ou êtes-vous présentement sous traitement pour les troubles suivants :

##### a) Troubles nerveux
Anxiété, dépression, trouble d'adaptation, fatigue chronique, angoisse, trouble de déficit de l'attention avec ou sans hyperactivité, trouble du choc post-traumatique, épuisement professionnel, trouble de panique, trouble de l'alimentation (anorexie, boulimie) ?
- ☐ Oui
- ☐ Non

##### b) Troubles psychiatriques graves
Schizophrénie, psychose, idées suicidaires ou tentative de suicide ou tous autres troubles nerveux ou psychiatriques ?
- ☐ Oui
- ☐ Non

##### c) Troubles dorsaux
- **Troubles dorsaux (colonne cervicale, dorsale, lombaire, lombo-sacrée):** ☐ Oui ☐ Non
- **Discopathie dégénérative:** ☐ Oui ☐ Non
- **Entorse:** ☐ Oui ☐ Non
- **Hernie discale:** ☐ Oui ☐ Non
- **Coup de fouet (whiplash):** ☐ Oui ☐ Non
- **Fracture d'une vertèbre:** ☐ Oui ☐ Non
- **Déplacement de vertèbre(s):** ☐ Oui ☐ Non
- **Autres troubles dorsaux:** ☐ Oui ☐ Non (Précisez: _________________)

##### d) Troubles musculosquelettiques
- **Troubles des muscles:** ☐ Oui ☐ Non
- **Troubles des os:** ☐ Oui ☐ Non
- **Troubles des articulations:** ☐ Oui ☐ Non
- **Fracture:** ☐ Oui ☐ Non
- **Ligament:** ☐ Oui ☐ Non
- **Rhumatisme:** ☐ Oui ☐ Non
- **Arthrite:** ☐ Oui ☐ Non
- **Ostéo-arthrite:** ☐ Oui ☐ Non
- **Goutte:** ☐ Oui ☐ Non
- **Ostéoporose:** ☐ Oui ☐ Non
- **Fibromyalgie:** ☐ Oui ☐ Non
- **Syndrome de douleur chronique:** ☐ Oui ☐ Non
- **Amputation:** ☐ Oui ☐ Non
- **Myasthénie grave:** ☐ Oui ☐ Non
- **Syndrome post-polio:** ☐ Oui ☐ Non
- **Autres troubles musculosquelettiques:** ☐ Oui ☐ Non (Précisez: _______________)

##### e) Maladies chroniques
Diabète de type 1 ou de type 2, colite ulcéreuse, maladie de Crohn, sclérose en plaques, maladie pulmonaire obstructive chronique (MPOC), épilepsie, paralysie ?
- ☐ Oui
- ☐ Non

##### f) Maladie de coagulation
Maladie de coagulation et/ou prise d'anticoagulant ?
- ☐ Oui
- ☐ Non

#### 6. Prestations d'invalidité
Avez-vous fait une demande de prestation ou reçu des prestations d'invalidité ou une compensation ou encore demandé un supplément d'aide à la suite de blessure, de maladie ou d'un handicap ?
- ☐ Oui
- ☐ Non
- **Si oui, répondre aux questions a) et b):**
  - **a) Quand cela a-t-il eu lieu ?** ☐ 0-12 mois ☐ 13-24 mois ☐ 25-36 mois ☐ Plus de 36 mois
  - **b) Durée de l'invalidité ?** ☐ 0-30 jours ☐ 31-90 jours ☐ 91-120 jours ☐ Plus de 120 jours

#### 7. Médication récente (6 derniers mois)
Dans les six (6) derniers mois :
- **a) Modification médication:** Est-ce qu'un ou plusieurs médicaments ont été modifiés (ajout ou remplacement, hausse ou baisse du dosage) ?
  - ☐ Oui
  - ☐ Non
  - **Si oui, répondre à la question:**
    - **Veuillez indiquer la ou les modification(s):**
      - ☐ Ajout de médicament
      - ☐ Remplacement de médicament
      - ☐ Hausse de dosage
      - ☐ Baisse du dosage
    - **Si baisse de dosage, répondre à ces questions:**
      - **Est-ce que la baisse du dosage a été recommandée par un professionnel de la santé en raison d'un mauvais contrôle de la condition médicale ou d'effets secondaires ?** ☐ Oui ☐ Non
      - **Est-ce que la baisse du dosage a été recommandée par un professionnel de la santé en raison d'un excellent contrôle de la condition médicale ?** ☐ Oui ☐ Non
- **b) Cessation médication:** Avez-vous cessé un ou plusieurs médicament(s) sans qu'un professionnel de la santé vous ait conseillé de le faire ?
  - ☐ Oui
  - ☐ Non
- **c) Consultation médicale:** Avez-vous consulté ou avez-vous été hospitalisé dans un centre de soins de santé ?
  - ☐ Oui
  - ☐ Non

---

## Section D - Signatures

### Déclaration
J'atteste que les réponses contenues dans le présent questionnaire sont complètes et véridiques et font partie intégrante de la proposition d'assurance auprès de UV Assurance et ne peuvent en être dissociées.

### Signatures requises
- **Signature de la personne à assurer:** X
- **Signature du propriétaire 1 (si personne morale, signataire autorisé):** X
- **Signature du propriétaire 2 (si personne morale, signataire autorisé):** X
- **Signature du conseiller:** X

### Instructions importantes
Le présent questionnaire doit être daté du jour où il a été rempli et doit être reçu au siège social de UV Assurance dans les **14 jours suivant la date de signature**.

---

## Instructions de soumission

### Assurance vie seulement
Si vous demandez seulement une assurance vie et que vous respectez tous les critères énoncés en page 1, vous pouvez soumettre une proposition PDF ou papier disponible sur notre site uvassurance.ca en ajoutant ce questionnaire dûment complété incluant la **Section D**.

### Avec avenant Assurance dette
Si vous demandez aussi un avenant Assurance dette, veuillez poursuivre au prochain questionnaire.

---

## Points clés à retenir

### Critères d'admissibilité Express
- **NON à toutes les questions:** Admissible pour 150 000 $ et moins
- **OUI à certaines questions:** Conditions spéciales applicables
- **OUI à d'autres questions:** Non-admissible à l'Express

### Conditions spéciales
- **Question 1:** Taux fumeur applicable
- **Questions 7-A, 7-B, 7-C:** Sous-questions déterminantes
- **Question 9:** Sous-questions déterminantes

### Avenant Assurance dette
- **Admissible:** NON à toutes les questions de la section C
- **Sélection des risques:** OUI à certaines questions spécifiques
- **Non-admissible:** OUI aux questions d'exclusion

### Instructions de soumission
- **Assurance vie seulement:** Proposition PDF ou papier avec questionnaire complété
- **Avec avenant Assurance dette:** Poursuivre au questionnaire suivant
- **Délai de soumission:** 14 jours suivant la date de signature

---

## Métadonnées pour indexation

**Mots-clés:** questionnaire d'admissibilité, émission simplifiée, Express, assurance vie temporaire, assurance vie permanente, avenant Assurance dette, UV Assurance

**Types d'émission:** Express

**Plages d'âge:** 16 à 80 ans (selon le produit)

**Montants:** 150 000 $ et moins

**Produits:** Vie entière Valeurs Élevées, L'Adaptable, Vie entière Payable à 100 ans, T-10, T-15, T-20, T-25, T-30

**Sections du questionnaire:** Section A (Informations), Section B (Express), Section C (Avenant dette), Section D (Signatures)

**Types de primes:** Standard, Fumeur, Non-fumeur

**Conditions médicales:** Troubles cardiovasculaires, Cancer, Diabète, Troubles psychiatriques, Troubles musculosquelettiques, Maladies chroniques

**Critères d'admissibilité:** Admissible, Non-admissible, Sélection des risques, Conditions spéciales

**Instructions spéciales:** Délai de soumission 14 jours, Proposition PDF ou papier, Questionnaire suivant pour avenant dette