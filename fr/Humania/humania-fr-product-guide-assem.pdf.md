---
# Document Metadata
document_id: "humania-fr-product-guide-assem-v1.0"
document_type: product_guide
schema_version: "2.0"
version: 1.0
document_title: "Guide du Produit ASSEM - Assurance Sans Examen Médical d'Humania"
full_product_name: "ASSEM No Medical Exam Insurance Product Guide (Humania Assurance Inc.)"
total_pages: 28
last_updated: "2024"
effective_date: "2024-01-01"

# Insurer Information
insurer:
  name: "Humania Assurance Inc."
  id: "humania"
  legal_name: "Humania Assurance Inc."

# Product Information
product:
  name: "ASSEM"
  id: "assem"
  owner: "Humania Assurance Inc."
  type: "no_medical_exam_insurance"
  type_fr: "Assurance sans examen médical"
  underwriting_type: "simplified_issue"
  underwriting_type_fr: "Émission simplifiée"

# Classification
language: fr-CA
region: QC
target_audience: 
  - clients
  - representatives
  - agents

# Coverage Limits
coverage:
  min_amount: 5000
  max_amount: 500000
  currency: CAD
  age_range: [18, 70]
  age_groups:
    - "18-55"
    - "56-70"

# Tags for Searchability
tags:
  - assem
  - assurance-sans-examen
  - vie
  - maladies-graves
  - invalidité
  - humania
  - simplifiée
  - produit-guide

# Machine-Readable Features
features:
  mib_verification: false
  fast_decision: true
  full_underwriting: false
  electronic_application: true
  simplified_issue: true
  no_medical_exam: true

# Disclaimer
disclaimer: "Ce guide est à titre indicatif ; les termes complets sont dans la police d'assurance."

# Document Structure Map
sections:
  - id: admissibilite
    name: "Admissibilité"
    type: eligibility
    line_start: 63
  - id: clauses-preexistantes
    name: "Clauses de Conditions Préexistantes"
    type: pre_existing
    line_start: 125
  - id: fin-polices
    name: "Fin des Polices et des Garanties"
    type: termination
    line_start: 148
  - id: sommaire-vie
    name: "Sommaire de l'Assurance Vie"
    type: life_insurance
    line_start: 180
  - id: paiement-vie
    name: "Paiement de l'Indemnité de la Police d'Assurance Vie"
    type: claims
    line_start: 197
  - id: sommaire-maladies-graves
    name: "Sommaire de l'Assurance Maladies Graves"
    type: critical_illness
    line_start: 211
  - id: paiement-maladies-graves
    name: "Paiement de l'Indemnité de la Police d'Assurance Maladies Graves"
    type: claims
    line_start: 229
  - id: liste-maladies-graves
    name: "Liste des Maladies Graves Couvertes et Leur Définition"
    type: definitions
    line_start: 257
  - id: sommaire-invalidite-revenu
    name: "Sommaire de l'Assurance Revenu en Cas d'Invalidité"
    type: disability_revenue
    line_start: 285
  - id: paiement-invalidite-revenu
    name: "Paiement de l'Indemnité de la Police d'Assurance Revenu en Cas d'Invalidité"
    type: claims
    line_start: 306
  - id: sommaire-dettes-invalidite
    name: "Sommaire de l'Assurance Dettes en Cas d'Invalidité"
    type: disability_debts
    line_start: 372
  - id: paiement-dettes-invalidite
    name: "Paiement de l'Indemnité de la Police d'Assurance Dettes en Cas d'Invalidité"
    type: claims
    line_start: 397
  - id: etablissement-montant
    name: "Établissement du Montant Assurable et des Indemnités Payables"
    type: calculations
    line_start: 413
  - id: avenant-option
    name: "Avenant (Option)"
    type: addons
    line_start: 452
  - id: information-generale
    name: "Information Générale"
    type: general
    line_start: 469
  - id: titulaire-payeur
    name: "Titulaire Assuré et Payeur"
    type: policyholders
    line_start: 476
  - id: droit-transformation
    name: "Droit de Transformation"
    type: conversion
    line_start: 490
  - id: modification-vente
    name: "Modification Après la Vente"
    type: modifications
    line_start: 500
  - id: preuve-revenu
    name: "Preuve de Revenu - Police Assurance Invalidité"
    type: income_proof
    line_start: 514

# Document Statistics
statistics:
  total_protections: 4
  total_avenants: 1
  total_exclusions: 8
  total_medical_conditions: 4
  total_tables: 4
  age_range: [18, 70]
  coverage_amount_min: 5000
  coverage_amount_max: 500000
  requirement_types:
    questionnaire: true
    pre_existing_clauses: true
    no_medical_exam: true
    income_proof: true
---
# Guide du Produit ASSEM - Assurance Sans Examen Médical d'Humania
## Or, Argent et Bronze

### Simple et Facile à Souscrire
**Émission Simplifiée**

### Sommaire
- [À qui s'adresse l'assurance sans examen médical d'Humania Assurance?](#à-qui-sadresse-lassurance-sans-examen-médical-dhumania-assurance)
- [Admissibilité](#admissibilité)
- [Clauses de Conditions Préexistantes](#clauses-de-conditions-préexistantes)
- [Fin des Polices et des Garanties](#fin-des-polices-et-des-garanties)
- [Sommaire de l'Assurance Vie](#sommaire-de-lassurance-vie)
- [Paiement de l'Indemnité de la Police d'Assurance Vie](#paiement-de-lindemnité-de-la-police-dassurance-vie)
- [Sommaire de l'Assurance Maladies Graves](#sommaire-de-lassurance-maladies-graves)
- [Paiement de l'Indemnité de la Police d'Assurance Maladies Graves](#paiement-de-lindemnité-de-la-police-dassurance-maladies-graves)
- [Liste des Maladies Graves Couvertes et Leur Définition](#liste-des-maladies-graves-couvertes-et-leur-définition)
- [Sommaire de l'Assurance Revenu en Cas d'Invalidité](#sommaire-de-lassurance-revenu-en-cas-dinvalidité)
- [Paiement de l'Indemnité de la Police d'Assurance Revenu en Cas d'Invalidité](#paiement-de-lindemnité-de-la-police-dassurance-revenu-en-cas-dinvalidité)
- [Sommaire de l'Assurance Dettes en Cas d'Invalidité](#sommaire-de-lassurance-dettes-en-cas-dinvalidité)
- [Paiement de l'Indemnité de la Police d'Assurance Dettes en Cas d'Invalidité](#paiement-de-lindemnité-de-la-police-dassurance-dettes-en-cas-dinvalidité)
- [Établissement du Montant Assurable et des Indemnités Payables](#établissement-du-montant-assurable-et-des-indemnités-payables)
- [Avenant (Option)](#avenant-option)
- [Information Générale](#information-générale)
- [Titulaire Assuré et Payeur](#titulaire-assuré-et-payeur)
- [Droit de Transformation](#droit-de-transformation)
- [Modification Après la Vente](#modification-après-la-vente)
- [Preuve de Revenu - Police Assurance Invalidité](#preuve-de-revenu---police-assurance-invalidité)

## À qui s'adresse l'assurance sans examen médical d'Humania Assurance?

L'assurance sans examen médical d'Humania Assurance est destinée aux personnes qui, pour des raisons médicales ou autres, éprouvent des difficultés à souscrire un contrat :
- d'assurance vie ;
- d'assurance maladies graves ;
- d'assurance invalidité (revenu et dettes).

**Pour souscrire ?** Pas d'examen médical, vous devez simplement répondre à **six questions d'admissibilité.**

Vous êtes **protégé immédiatement** dès la réception de votre demande chez l'assureur.

Ce régime d'assurance vous offre une couverture :
- **À émission instantanée** ;
- **Simple** à comprendre ;
- **Facile** à souscrire.

Recevez jusqu'à **100 000 $** à la suite du diagnostic d'un cancer, d'une crise cardiaque, d'un accident vasculaire cérébral (AVC) ou d'un pontage aortocoronarien.

Un accident ou une maladie vous empêche de travailler, nous vous verserons jusqu'à **2 500 $** par mois pour couvrir votre perte de salaire et/ou **2 500 $** par mois pour vous permettre de payer vos dettes.

Jusqu'à **500 000 $*** versés à vos bénéficiaires à la suite d'un décès.

<sup>*</sup> Le montant total des indemnités payables par l'assureur pour l'ensemble des polices d'assurance vie HUMANIA ASSURANCE – ASSURANCE SANS EXAMEN MÉDICAL, sur la tête d'un assuré ne peut être supérieur à (trois cent mille dollars (300 000 $) ou cinq cent mille dollars (500 000 $) selon la police souscrite par le titulaire).

L'assurance sans examen médical d'Humania Assurance est disponible exclusivement par l'entremise d'un conseiller en sécurité financière dûment autorisé.

L'assurance sans examen médical d'Humania Assurance vous permet de souscrire 5 polices d'assurance distinctes en une seule demande soit :
- ASSEM vie temporaire 10 ans, 20 ans ou 100 ans ;
- ASSEM maladies graves temporaire 10 ans ou 20 ans ;
- ASSEM invalidité revenu temporaire 10 ans ou 20 ans ;
- ASSEM invalidité dettes temporaire 10 ans ou 20 ans.

<sup>*</sup> Le montant total des indemnités mensuelles payables par l'assureur pour l'ensemble des polices invalidité ou pour l'ensemble des polices créance HUMANIA ASSURANCE – ASSURANCE SANS EXAMEN MÉDICAL, sur la tête d'un assuré ne peut être supérieur à deux mille cinq cent dollars (2 500 $).

## Admissibilité

**Pour être admissible ? Pas d'examen médical, vous devez simplement répondre à six questions.**

### Pour Ceux qui Travaillent

| Question | Description | Oui | Non |
|----------|-------------|-----|-----|
| 1. | Travaillez-vous actuellement? (Répondez oui si vous recevez présentement des indemnités d'un régime de congé parental) | Oui | Non |
| 2. | Au cours des 12 derniers mois (ou des 12 mois précédant votre congé parental s'il y a lieu), avez-vous vaqué à toutes vos occupations (28 semaines, 21 heures/semaine) et de façon permanente? | Oui | Non |
| 3. | Au cours des 2 dernières années (ou des 2 années précédant votre congé parental s'il y a lieu), avez-vous été absent du travail pendant plus de 15 jours consécutifs en raison de maladie ou reçu des prestations d'invalidité ou de maladies graves, provenant d'un régime privé, collectif ou public d'assurance? On parle ici de tout régime privé d'assurance que vous pouvez détenir, de protection d'assurance fournie par votre employeur, une association professionnelle ou autre, et de toutes les protections fournies par des organismes gouvernementaux, aussi bien provinciaux que fédéraux. | Oui | Non |
| 4. | Au cours des 2 dernières années, avez-vous reçu un traitement (incluant la participation à une organisation d'entraide ou un groupe de soutien), vous a-t-on conseillé de réduire votre consommation ou d'avoir recours à un traitement pour l'usage de drogues ou d'alcool? | Oui | Non |
| 5. | Au cours des 5 dernières années, avez-vous été incarcéré pour plus de 48 heures? | Oui | Non |
| 6. | Au cours des 6 derniers mois avez-vous eu des malaises ou des symptômes physiques ou mentaux pour lesquels vous n'avez pas encore consulté un professionnel de la santé? | Oui | Non |

**Admissible à quatre protections : Vie, maladies graves, invalidité et dettes** si toutes réponses Non aux 6 questions.

### Pour Ceux qui Ne Travaillent Pas

| Question | Description | Oui | Non |
|----------|-------------|-----|-----|
| 1. | Travaillez-vous actuellement? (Répondez oui si vous recevez présentement des indemnités d'un régime de congé parental) | Oui | Non |
| 2. | Je confirme n'avoir reçu aucun diagnostic de déficience cognitive et confirme effectuer les activités de la vie quotidienne, soit prendre un bain, me vêtir, faire ma toilette, être continent, me mouvoir et me nourrir par moi-même? | Oui | Non |
| 3. | Au cours des 2 dernières années, avez-vous été dans l'incapacité de vaquer à vos occupations régulières, incluant les activités de la vie quotidienne, pendant plus de 15 jours consécutifs en raison de maladie ou reçu des prestations d'invalidité ou de maladies graves, provenant d'un régime privé, collectif ou public d'assurance? On parle ici de tout régime privé d'assurance que vous pouvez détenir, de protection d'assurance fournie par votre employeur, une association professionnelle ou autre, et de toutes les protections fournies par des organismes gouvernementaux, aussi bien provinciaux que fédéraux. | Oui | Non |
| 4. | Au cours des 2 dernières années, avez-vous reçu un traitement ou vous a-t-on conseillé d'avoir recours à un traitement pour l'usage de drogues ou d'alcool? Sans s'y limiter, la participation à une organisation d'entraide ou un groupe de soutien est aussi considérée comme un traitement. | Oui | Non |
| 5. | Au cours des 5 dernières années, avez-vous été incarcéré pour plus de 48 heures? | Oui | Non |
| 6. | Au cours des 6 derniers mois, avez-vous eu des malaises ou des symptômes physiques ou mentaux pour lesquels vous n'avez pas encore consulté un professionnel de la santé? | Oui | Non |

**Admissible à deux protections : Vie et maladies graves** si toutes réponses Non aux 6 questions.

### Questions Supplémentaires pour Couverture Étendue

Si admissible aux protections de base, questions supplémentaires pour déterminer taux et conditions :

| Question | Description | Oui | Non |
|----------|-------------|-----|-----|
| 7. | Au cours des 2 dernières années, avez-vous reçu un traitement ou une thérapie, vous a-t-on prescrit ou avez-vous pris des médicaments sous ordonnance, autre que les anovulants, antibiotiques et anti-inflammatoires non stéroïdiens? | Oui | Non |
| 7.1 | Est-ce que le traitement, la thérapie ou les médicaments sont en lien avec le DIABÈTE seulement? | Oui | Non |

**Questions sur Antécédents Médicaux (5 dernières années) :**

- 8. Trouble du cœur, d'un accident vasculaire cérébral ou des vaisseaux sanguins autre que l'hypertension artérielle traitée et contrôlée?
- 9. Cancer, tumeur, fibrose kystique, maladie de Hodgkin, lymphome, leucémie, emphysème ou bronchite chronique?
- 10. Maladie de Crohn, colite ulcéreuse, hépatite B ou C, ou autres troubles du foie ou du pancréas?
- 11. Diabète, prédiabète ou intolérance au glucose? (Répondre oui pourrait entraîner des questions supplémentaires pour accorder le meilleur taux possible.)
- 12. Sclérose en plaques, dystrophie musculaire, paralysie?
- 13. Convulsions ou maladies du motoneurone?
- 14. Troubles de la prostate, reins polykystiques ou autres troubles des reins?
- 15. Syndrome d'immunodéficience acquise (SIDA) ou virus de l'immunodéficience humaine (VIH)?
- 16. Arthrite rhumatoïde, fibromyalgie ou maladie discale?
- 17. Dépression, psychose, schizophrénie ou troubles bipolaires?

Si oui à 17 :
- 17.1 Au cours des cinq dernières années, avez-vous été hospitalisé, eu des idées suicidaires, envisagé de vous blesser d'une façon ou d'une autre ou vous a-t-on prescrit plus de 2 médicaments pour l'une des conditions énumérées?

- 18. Y a-t-il plus qu'un membre de votre famille (parents, frères, sœurs) qui a déjà eu le cancer, diabète, accident vasculaire cérébral, crise cardiaque, angine, sclérose en plaques, rein polykystique, ou maladie du motoneurone avant l'âge de 60 ans?

**Pour Montant Supérieur à 300 000 $ en Assurance Vie :**
- Selon les réponses, admissible à jusqu'à 500 000 $. Questions supplémentaires : taille, poids, variation de poids >10% dans 12 mois.

La série de questions suivantes permet de déterminer les taux de primes et les conditions applicables à votre police d'assurance.

## Clauses de Conditions Préexistantes

Des clauses de conditions préexistantes s'appliquent à toutes les polices. En fonction de vos réponses au questionnaire de santé, celles-ci peuvent être de **12 ou 24 mois** (selon la police souscrite par le titulaire). La durée est mentionnée dans le sommaire de la police.

### Qu'est-ce qu'une Affection Préexistante ?

L'affection préexistante est une blessure, une maladie ou une affection qui s'est manifestée au cours de la période de 12 ou 24 mois précédant la date d'effet de la police et pour laquelle :
- l'assuré a reçu un diagnostic, a été traité, hospitalisé ou suivi par un médecin ou tout autre professionnel de la santé ; ou
- on a conseillé à l'assuré de se faire traiter ou de consulter un médecin ou tout autre professionnel de la santé ; ou
- l'assuré a reçu une ordonnance ou pris des médicaments, a montré des signes ou des symptômes ou a subi des tests ou des examens.

### Qu'arrive-t-il si j'ai Besoin de Faire une Réclamation Durant la Période de Conditions Préexistantes ?

Aucune indemnité n'est payable durant la période de 12 ou 24 mois suivant la date d'effet de la police si la réclamation résulte ou est reliée directement ou indirectement avec une affection préexistante et que les premiers signes et symptômes apparaissent durant cette période. La responsabilité de l'assureur se limite au remboursement des primes payées et la police prend fin sans valeur.

#### Exemple d'Application d'une Clause de Condition Préexistante 24 Mois

Marie a des problèmes cardiaques et d'hypertension. Durant les 24 derniers mois, elle a pris des médicaments et consulté son médecin. Si dans les 24 mois suivant la souscription, une réclamation liée à ces conditions est faite, aucune prestation n'est payable, mais les affections non reliées sont couvertes. Après 24 mois, toute réclamation couverte est payable.

#### Durée de la Condition Préexistante

La durée (12 ou 24 mois) est établie selon les réponses aux questions de santé (7 à 17) et mentionnée au sommaire de la police.

## Fin des Polices et des Garanties

### Assurance Vie

La police et les garanties prennent fin à la première des dates suivantes :
- réception d'une demande écrite d'annulation ;
- expiration du délai de grâce pour paiement de prime ;
- pour T10 ou T20 : anniversaire où l'assuré atteint 80 ans ;
- pour T10 ou T20 : transformation en totalité ;
- décès de l'assuré.

### Assurance Maladies Graves

La police prend fin à la première des dates suivantes :
- réception d'une demande écrite d'annulation ;
- expiration du délai de grâce ;
- maladie grave liée à affection préexistante dans 12/24 mois ;
- versement d'indemnité maladies graves ;
- anniversaire où l'assuré atteint 65 ans ;
- décès de l'assuré.

### Assurance Invalidité (Dettes et Revenu)

La police prend fin à la première des dates suivantes :
- réception d'une demande écrite d'annulation ;
- expiration du délai de grâce ;
- invalidité liée à condition préexistante dans 12/24 mois ;
- maximum de 24 indemnités mensuelles versées ;
- anniversaire où l'assuré atteint 65 ans ;
- cessation de résidence canadienne ;
- décès de l'assuré.

## Sommaire de l'Assurance Vie {#sommaire-de-lassurance-vie}

| Aspect | Détails |
|--------|---------|
| Indemnités offertes | Temporaire 10/20 ans : min 5 000 $, max 300 000 $ ou 500 000 $*. Temporaire 100 ans : min 5 000 $, max 100 000 $*. |
| Limites d'âge à la souscription | 18 à 70 ans. |
| Type de contrat | Temporaire 10, 20 ou 100 ans. |
| Renouvellement | T10/T20 : garanti jusqu'à 80 ans. |
| Prime | T10/T20 : primes variant par période, ajustées à 10/20 ans. T100 : prime fixe jusqu'à 100 ans. |
| Bénéficiaire | Au choix du titulaire. |
| Clause de conditions préexistantes | 12 ou 24 mois. |
| Exclusions et restrictions | Voir spécimen de police. |

<sup>*</sup> Montant combiné max 300 000 $ pour Bronze, 500 000 $ pour Or/Argent.

L'assurance est disponible via conseiller autorisé.

## Paiement de l'Indemnité de la Police d'Assurance Vie {#paiement-de-lindemnité-de-la-police-dassurance-vie}

Si décès non lié à affection préexistante : paiement de l'indemnité sous réserve des restrictions.

Si décès lié à affection préexistante après 12/24 mois : paiement sous réserve.

Aucune indemnité si dans 12/24 mois et lié : remboursement primes, fin police.

### Montant Total des Indemnités Payables

Max 500 000 $ pour toutes polices vie ASSEM. Excédent : paiement max + remboursement primes excédent.

Pour T100 : max 100 000 $.

## Sommaire de l'Assurance Maladies Graves {#sommaire-de-lassurance-maladies-graves}

| Aspect | Détails |
|--------|---------|
| Indemnités offertes | Min 5 000 $, max 100 000 $. |
| Limites d'âge | 18 à 55 ans. |
| Type de contrat | Temporaire 10/20 ans. |
| Renouvellement | Jusqu'à 65 ans. |
| Prime | Primes variant par 10/20 ans, ajustées. |
| Maladies couvertes | AVC, Cancer, Pontage aortocoronarien, Crise cardiaque. Voir définitions. |
| Période de survie | 30 jours. |
| Période moratoire cancer | 90 jours. |
| Retour de primes au décès | Oui. |
| Bénéficiaire | L'assuré (sauf indication contraire). |
| Clauses préexistantes | 12/24 mois. |
| Avenant (option) | Après 20 ans sans réclamation : 75% primes remboursées. |
| Exclusions | Voir spécimen. |

Disponible via conseiller.

## Paiement de l'Indemnité de la Police d'Assurance Maladies Graves {#paiement-de-lindemnité-de-la-police-dassurance-maladies-graves}

Paiement si maladie grave non liée préexistante, survie 30 jours.

Si liée après 12/24 mois : paiement si survie 30 jours.

Aucune si dans 12/24 mois et liée : remboursement primes, fin police.

Au décès sans indemnité : remboursement primes + frais (max indemnité).

### Restrictions

Indemnité après survie, première manifestation seulement. Non cumulatives.

### Exclusions

- Tentative suicide, auto-mutilation ;
- Actes illégaux, conduite influencée ;
- Consommation intentionnelle non prescrite.

Aucune si préexistante dans période.

### Montant Maximal Payable

Max 100 000 $ pour toutes polices maladies graves ASSEM.

## Liste des Maladies Graves Couvertes et Leur Définition {#liste-des-maladies-graves-couvertes-et-leur-définition}

### L'Accident Vasculaire Cérébral (AVC)

Un AVC causant séquelles neurologiques >30 jours dues à thrombose, hémorragie ou embolie extra-crânienne. Preuve de déficit neurologique. Exclut attaques ischémiques transitoires.

### Le Cancer

Tumeur maligne invasive, diagnostiquée par spécialiste.

#### Cancers Exclus
- Carcinome in situ ;
- Mélanome stade 1A ;
- Cancer peau non mélanome sans métastase ;
- Cancer prostate stade A.

### Période Moratoire

Aucune indemnité pour cancer dans 90 jours de date d'effet (diagnostic, signes, consultations). Divulguer dans 6 mois, sinon refus possible.

### La Chirurgie Coronarienne (Pontage Aortocoronarien)

Chirurgie pour rétrécissement/obstruction artère coronaire. Exclut angioplastie/laser.

### La Crise Cardiaque (Infarctus du Myocarde)

Nécrose muscle cardiaque par insuffisance sanguine, avec ECG et marqueurs biochimiques. Inclut pendant angioplastie avec nouvelles ondes Q. Exclut découverte fortuite sans symptômes.

## Sommaire de l'Assurance Revenu en Cas d'Invalidité {#sommaire-de-lassurance-revenu-en-cas-dinvalidité}

| Aspect | Détails |
|--------|---------|
| Indemnités offertes | Min 400 $, max 2 500 $/mois. |
| Délai de carence | 90 jours. |
| Période d'indemnisation | 24 mois. |
| Limites d'âge | 18-55 ans. |
| Type | Temporaire 10/20 ans. |
| Renouvellement | Jusqu'à 65 ans. |
| Prime | Variant 10/20 ans, possible ajustement. |
| Indemnité rétroactive | Après 6 mois : forfait pour carence. |
| Invalidité couverte | Totale par accident/maladie. |
| Exonération primes | Après 3 mois. |
| Coordination | 100%. |
| Intégration | 1 200 $ non intégré. |
| Bénéficiaire | Assuré. |
| Préexistantes | 12/24 mois. |
| Avenant | 75% primes après 20 ans sans réclamation. |
| Exclusions | Voir spécimen. |

Disponible via conseiller.

## Paiement de l'Indemnité de la Police d'Assurance Revenu en Cas d'Invalidité {#paiement-de-lindemnité-de-la-police-dassurance-revenu-en-cas-dinvalidité}

Paiement mensuel après 90 jours carence, max 24 mois, si invalidité totale non liée préexistante.

Si liée après 12/24 mois : paiement.

Aucune si dans 12/24 mois et liée : remboursement primes.

Premiers 1 200 $/mois non intégrés/coordonnés. Au-delà : intégrés et coordonnés au revenu moyen.

### Définition d'Invalidité Totale

**Emploi rémunéré au début :** Inapte à fonctions emploi, pas autre emploi, soins continus.

**Sans emploi au début :** Incapable d'au moins une activité vie quotidienne, soins continus.

**Activités Vie Quotidienne :**
- Se nourrir : consommer aliments préparés.
- Se vêtir : mettre/retirer vêtements/prothèses.
- Se mouvoir : déplacer hors lit/chaise.
- Prendre bain : se laver.
- Faire toilette : hygiène personnelle.
- Être continent : gérer fonctions avec hygiène.

### Restrictions

Si sans emploi >120 jours au début : max 50% garantie ou 1 200 $, pour protections invalidité.

### Exclusions

Aucune si préexistante dans période.

Aucune si :
- Suicide, auto-mutilation ;
- Actes illégaux, conduite influencée ;
- Toxicomanie, alcoolisme ;
- Service militaire, manifestations ;
- Blessure aérienne (sauf passager) ;
- Sports pro, vitesse motorisée ;
- Activités risque élevé (bungee, etc.) ;
- Chirurgie esthétique ;
- Traitements expérimentaux.

Aucune pour :
- Grossesse/complications sauf pathologiques ;
- Incarcération.

### Exonération des Primes

Après 3 mois continus invalidité totale : exonération tant admissible.

### Indemnité Rétroactive

Après 6 mois : forfait pour carence.

### Présomption d'Invalidité Totale et Permanente

Perte totale/permanente de 2 membres/sens : considérée invalide sans emploi/soins.

- Main/pied : amputation ou perte usage.
- Ouïe : perte irréversible deux oreilles.
- Vue : perte définitive deux yeux.

### Montant Maximal Payable

Max 2 500 $/mois pour toutes polices invalidité/créance ASSEM.

## Sommaire de l'Assurance Dettes en Cas d'Invalidité {#sommaire-de-lassurance-dettes-en-cas-dinvalidité}

| Aspect | Détails |
|--------|---------|
| Indemnités offertes | Min 400 $, max 2 500 $/mois. |
| Délai de carence | 90 jours. |
| Période d'indemnisation | 12 ou 24 mois. |
| Limites d'âge | 18-55 ans. |
| Type | Temporaire 10/20 ans. |
| Renouvellement | Jusqu'à 65 ans. |
| Prime | Variant 10/20 ans, possible ajustement. |
| Indemnité rétroactive | Après 6 mois : forfait pour carence. |
| Invalidité couverte | Totale par accident/maladie. |
| Exonération primes | Après 3 mois. |
| Coordination | Non coordonnée. Créances autres assurances exclues. |
| Bénéficiaire | Assuré. |
| Préexistantes | 12/24 mois. |
| Avenant | 75% primes après 20 ans. |
| Exclusions | Voir spécimen. |

Disponible via conseiller.

## Paiement de l'Indemnité de la Police d'Assurance Dettes en Cas d'Invalidité {#paiement-de-lindemnité-de-la-police-dassurance-dettes-en-cas-dinvalidité}

Similaire à revenu : paiement après 90 jours, max 24 mois, si non liée préexistante.

Définition invalidité totale identique.

Restrictions : si sans emploi >120 jours, max 50% ou 1 200 $.

Exclusions : similaires, plus :
- Congés payés ;
- Incarcération.

Exonération, rétroactive, présomption identiques.

Max 2 500 $/mois total.

## Établissement du Montant Assurable et des Indemnités Payables {#établissement-du-montant-assurable-et-des-indemnités-payables}

ASSEM Dettes couvre créances (dettes, prêts). Basé sur créances admissibles, non revenu. Preuves requises à réclamation.

**Créance Admissible :** Prêt fixe responsable personnellement par institution reconnue : personnel (auto, etc.), carte crédit, marge, bail, hypothécaire.

Sans hypothécaire : loyer mensuel (normes régie, bail 1 an min, non parenté/affaires).

Taxes foncières/scolaires : annuelles /12.

Exclut prêts entre individus.

Augmentations/créances pendant invalidité ou 90 jours avant (sauf 90 jours après effet) non admissibles.

Créances autres assurances exclues.

**Bail de Location :** Location bien, exclut logement résidentiel.

**Montant Mensuel Admissible :** Équivalent mensuel versement périodique (facteur hebdo 52/12, bi-hebdo 26/12).

Spécifiquement :
- Marge/carte crédit : min(3% solde début, min exigible). Admissible 10 ans.
- Marge hypothécaire : versement régulier 6 mois avant, ou min(3% solde, intérêt mensuel).
- Prêt hypothécaire : max(cédule amortissement, versement 6 mois). À renouvellement taux fixe mêmes conditions : ajusté si supérieur. Taxes /12.
- Loyer résidentiel : montant, max 2 ans.
- Prêt levier placement : min(3% solde, min exigible), 10 ans.
- Prêt personnel : versement contrat, jusqu'échéance. À échéance : nouveau pour valeur résiduelle, min(nouveau versement, précédent).
- Autres : versement contrat.

Sauf hypothécaire : fixe au début invalidité jusqu'amortissement original.

Pour co-emprunteurs solidaire : 100% versement.

Remboursé pleinement : 0 $.

Faillite en invalidité : 0 $, fin prestations.

**Pas de paiements anticipés/forfaitaires. Assureur non responsable retards/intérêts/frais.**

## Avenant (Option) {#avenant-option}

**Garantie de Remboursement de Primes Tous les 20 Ans** (optionnelle, non avec vie).

Après 20 ans consécutifs sans indemnité : 75% primes payées remboursées. Nouvelle période commence.

### Restrictions

Réduction >25% capital : prime rétroactive pour période.

### Fin de la Garantie

- Annulation écrite ;
- Délai grâce prime ;
- Indemnité versée <20 ans restants.

## Information Générale {#information-générale}

Produit distribué via conseiller autorisé, souscription via https://assem.humania.ca/accueil. Pas de papier.

Conseiller doit avoir contrat Humania et approbation portail.

[www.humania.ca/conseillers/distribuer-les-produits-humania/](https://www.humania.ca/conseillers/distribuer-les-produits-humania/)

## Titulaire Assuré et Payeur {#titulaire-assuré-et-payeur}

À souscription : même personne. Pas corporations. Post-émission : modifiable.

**Émission :** Une ou plusieurs protections :
- Vie : jusqu'à 500 000 $ ;
- Maladies graves : 100 000 $ ;
- Invalidité revenu : 2 500 $/mois ;
- Dettes : 2 500 $/mois.

Une police par protection. Prime min 10 $/mois/police.

Max payable : 2 500 $/mois total invalidité/créance ; 300/500k $ vie selon police.

## Droit de Transformation {#droit-de-transformation}

Pour vie T10/T20 : transformer en T100 avant 65 ans, sans assurabilité, max 50 000 $.

Nouvelle prime : âge atteint, taux vigoureux, classe risque.

Si surprime/restrictions : appliquées à nouvelle.

Voir police pour détails.

## Modification Après la Vente {#modification-après-la-vente}

### Modifications Autorisées

| Type | En Tout Temps | Annulation et Nouveau Contrat |
|------|---------------|-------------------------------|
| Changement titulaire | ✓ | |
| Changement payeur | ✓ | |
| Fumeur à non-fumeur | ✓ | |
| Augmentation capital | | ✓ |
| Réduction capital | ✓ | |
| Ajout remboursement primes | | ✓ |
| Réduction taux (amélioration santé) | | ✓ |
| Transformation T10/T20 en T100 | Avant 65 ans | ✓ |

## Preuve de Revenu - Police Assurance Invalidité {#preuve-de-revenu---police-assurance-invalidité}

### Aucune Preuve à la Souscription

**À Réclamation :** Déclaration revenu dernière année + avis cotisation, ou 3 meilleures des 5 dernières.

**Revenu Gagné Mensuel Moyen :** Plus élevé entre dernier année et moyenne 3/5 dernières /12.

### Humania Assurance Inc.

1555, rue Girouard Ouest, Saint-Hyacinthe (Québec) J2S 2Z6  
Téléphone : 450 774-3120 • Sans frais : 1 877 569-3120  
**www.humania.ca**

Pour plus d'information, contactez votre conseiller ou info@humania.ca / 1 800 773-8404 (lundi-vendredi 8h-17h ET).

#### Parmi Vous Depuis Plus de 150 Ans

Humania Assurance, mutuelle ancienne et solide, offre solutions innovantes accessibles. Protège centaines de milliers de Canadiens. Vision : tranquillité d'esprit par innovations. Expérience humaine via collaborateurs et partenariats.