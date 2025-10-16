---
# Document Metadata
document_id: "rbc-fr-directives-tarification-invalidite-maladies-graves-v1.0"
document_type: underwriting_manual
schema_version: "2.0"
version: 1.0
document_title: "Directives de Tarification - Assurance Invalidité et Maladies Graves RBC"
full_product_name: "Underwriting Manual for Disability and Critical Illness Insurance (RBC Insurance)"
total_pages: 544
last_updated: "2025-07"
effective_date: "2025-07-01"

# Insurer Information
insurer:
  name: "RBC Assurances"
  id: "rbc"
  legal_name: "RBC Assurances®"

# Product Information
product:
  name: "Portefeuille d'Assurance Individuelle à Prestations du Vivant"
  id: "individual-living-benefits-portfolio"
  owner: "RBC Assurances"
  type: "insurance_portfolio"
  type_fr: "Portefeuille d'assurance"
  underwriting_type: "mixed_underwriting"
  underwriting_type_fr: "Souscription mixte"
  product_variants:
    - "Série Avant-garde"
    - "Série Fondations"
    - "Série Fondamentale"
    - "Série Professions"
    - "Quantum"
    - "Maladie Grave"
    - "Protection Retraite"
    - "Protection Prêt commercial"
    - "Frais généraux d'entreprise"
    - "Rachat en cas d'invalidité"
    - "Protection Personne clé"

# Classification
language: fr-CA
region: CA
target_audience:
  - insurance_advisors
  - underwriters
  - agents
  - brokers

# Coverage Limits
coverage:
  min_amount: 450
  max_amount: 5000000
  currency: CAD
  age_range: [18, 80]
  age_groups:
    - "18-40"
    - "41-50"
    - "51-60"
    - "61-70"
    - "71-80"

# Tags for Searchability
tags:
  - directives-tarification
  - assurance-invalidite
  - assurance-maladies-graves
  - rbc-assurance
  - proposition-assurance
  - note-couverture
  - exigences-medicales
  - tarification-financiere

# Machine-Readable Features
features:
  proposal_guidelines: true
  coverage_notes: true
  medical_requirements: true
  financial_underwriting: true
  policy_delivery: true

# Disclaimer
disclaimer: "Ce manuel sert de référence pour les directives, les limites et les exigences clés de tarification. Tous les aspects du cas sont considérés au cours de l'évaluation de chacune des propositions."

# Document Structure Map
sections:
  - id: vue_ensemble
    name: "Vue d'ensemble"
    type: overview
    line_start: 9
  - id: introduction_directives
    name: "Introduction aux directives de tarification"
    type: introduction
    line_start: 31
  - id: renseignements_produits
    name: "Renseignements sur les produits"
    type: product_info
    line_start: 47
  - id: redaction_proposition
    name: "Rédaction de la proposition et directives concernant la délivrance de la police"
    type: proposal_guidelines
    line_start: 88
  - id: exigences_medicales
    name: "Exigences médicales"
    type: medical_requirements
    line_start: 221
  - id: tarification_financiere
    name: "Tarification et exigences financières"
    type: financial_underwriting
    line_start: 476
  - id: autres_directives
    name: "Autres directives de tarification"
    type: other_guidelines
    line_start: 477
  - id: considerations_particulieres
    name: "Considérations particulières touchant la tarification"
    type: special_considerations
    line_start: 478
  - id: tarification_garanties
    name: "Tarification de garanties complémentaires"
    type: rider_underwriting
    line_start: 479
  - id: directives_entreprise
    name: "Directives de tarification des produits d'entreprise"
    type: business_underwriting
    line_start: 480
  - id: directives_maladie_grave
    name: "Directives de tarification particulières à la police rétablissement d'une maladie grave"
    type: critical_illness_underwriting
    line_start: 481

# Document Segments (Original PDF)
document_segments:
  - name: "Directives de Tarification Assurance Invalidité et Maladies Graves"
    pages: 0-544
    confidence: High

# Document Statistics
statistics:
  total_product_series: 11
  proposal_validity_months: 12
  coverage_note_duration_days: 90
  age_calculation_methods: 2
  medical_requirement_categories: 5
  financial_documentation_types: 4
  proposal_filling_guidelines: 8
  policy_delivery_processes: 3
---

# Directives de Tarification - Assurance Invalidité et Maladies Graves RBC

> **Document Type:** Directives de tarification assurance invalidité et maladies graves  
> **Company:** RBC Assurances  
> **Language:** Français  
> **Last Updated:** Juillet 2025  
> **Categories:** Directives de tarification, Assurance invalidité, Assurance maladies graves, RBC Assurance

## Vue d'ensemble

Ce manuel sert de référence pour les directives, les limites et les exigences clés de tarification pour l'assurance invalidité individuelle et l'assurance en cas de maladie grave. Il renferme une mine de renseignements portant sur la plupart des aspects de la tarification, y compris les nouvelles propositions, les modifications et les remises en vigueur de police.

---

## Table des matières

1. [Vue d'ensemble](#vue-densemble)
2. [Introduction aux directives de tarification](#introduction-aux-directives-de-tarification)
3. [Renseignements sur les produits](#renseignements-sur-les-produits)
4. [Rédaction de la proposition et directives concernant la délivrance de la police](#rédaction-de-la-proposition-et-directives-concernant-la-délivrance-de-la-police)
5. [Exigences médicales](#exigences-médicales)
6. [Tarification et exigences financières](#tarification-et-exigences-financières)
7. [Autres directives de tarification](#autres-directives-de-tarification)
8. [Considérations particulières touchant la tarification](#considérations-particulières-touchant-la-tarification)
9. [Tarification de garanties complémentaires](#tarification-de-garanties-complémentaires)
10. [Directives de tarification des produits d'entreprise](#directives-de-tarification-des-produits-dentreprise)
11. [Directives de tarification particulières à la police rétablissement d'une maladie grave](#directives-de-tarification-particulières-à-la-police-rétablissement-dune-maladie-grave)

---

## Introduction aux directives de tarification

### Objectif du manuel

Ce manuel fournit des directives utiles pour la plupart des situations de tarification. Toutefois, tous les aspects du cas sont considérés au cours de l'évaluation de chacune des propositions et ensuite une décision appropriée est prise par le tarificateur.

### Processus dynamique

Le processus de la tarification des propositions d'assurance invalidité et d'assurance en cas de maladie grave est dynamique. S'il advient que vous faisiez face à une situation dont il n'y a aucune mention dans ces directives, nous vous encourageons d'en discuter avec votre représentant des ventes ou notre Service de la tarification avant de déposer une proposition.

### Unicité des propositions

Comme chacun des proposants est unique, il en est de même pour chacune des propositions d'assurance invalidité et d'assurance en cas de maladie grave.

---

## Renseignements sur les produits

### Portefeuille des produits d'assurance individuelle à prestations du vivant

#### Série Avant-garde
- Guide du conseiller en assurance
- Guide des taux

#### Série Fondations
- Guide du conseiller en assurance

#### Série Fondamentale
- Guide du conseiller en assurance
- Guide des taux

#### Série Professions
- Guide du conseiller en assurance

#### Quantum
- Guide du conseiller en assurance

#### Maladie Grave
- Guide du conseiller en assurance

#### Protection - Retraite
- Guide du conseiller en assurance

#### Protection Prêt commercial
- Guide du conseiller en assurance

#### Frais généraux d'entreprise
- Guide du conseiller en assurance

#### Rachat en cas d'invalidité
- Guide du conseiller en assurance

#### Protection Personne clé
- Guide du conseiller en assurance

---

## Rédaction de la proposition et directives concernant la délivrance de la police

### Importance de la proposition

La bonne façon de remplir une proposition constitue l'un des facteurs les plus importants du traitement et de l'établissement ultime des polices. Le tarificateur doit prendre des décisions reposant sur les renseignements inscrits sur la proposition.

### Qualité des renseignements

La qualité et la précision de ces renseignements influent directement sur le besoin d'obtenir ou non des exigences additionnelles de tarification et contribuent énormément aux frais engagés et aux retards du temps de service.

### Document de référence

La proposition est le document de référence le plus important et, dans bien des cas, fournit tous les renseignements nécessaires. Il faut donc s'assurer que les renseignements fournis sont complets, précis et de première main.

### Index des directives

#### Acompte avec la proposition
- Montant minimal requis
- Chèques datés acceptés
- Protection de la Note de couverture

#### Âge à l'établissement de la police
- Calcul selon le plus proche anniversaire
- Sauvegarde de l'âge (antidatation jusqu'à 30 jours)
- Exceptions pour certaines séries

#### Âges minimal et maximal à la souscription
- Limites selon le produit
- Disponibilité des taux

#### Antécédents médicaux
- Éléments les plus importants
- Réponses complètes et claires requises
- Informations détaillées nécessaires

#### Autorisation
- Signature et datation essentielles
- Aucune restriction ou modification acceptée

#### Confidentialité (Protection de la vie privée)
- Respect des lois provinciales
- Utilisation des renseignements

#### Datation et déclaration signée confirmant aucun changement dans l'état de santé
- Date de la proposition non modifiable
- Date courante (5 jours ouvrables)
- Déclaration requise après 90 jours

#### Délivrance de la police
- Processus de délivrance
- Conditions de délivrance

#### Deuxième proposition d'assurance
- Règles applicables
- Priorité des propositions

#### Document légal
- Partie intégrante du contrat
- Droits juridiques régis par la proposition

#### Fiche d'information à l'intention du consommateur-préavis
- Remise obligatoire
- Information sur le BRM et l'EAP

#### Formulaires de remplacement et de divulgation
- Obligations de divulgation
- Processus de remplacement

#### Limites pour les risques « surâgés »
- Restrictions d'âge
- Conditions spéciales

#### Lisibilité
- Écriture à l'encre (noire ou bleue)
- Pas de liquide correcteur
- Information supplémentaire sur feuille distincte

#### Montant minimal de la police
- 450$ d'indemnisation mensuelle totale
- Majoration en tranches de 25$

#### Noms
- Nom légalement connu
- Bons titres
- Anciens noms

#### Note de couverture
- Protection conditionnelle
- Acompte minimal requis
- Conditions d'entrée en vigueur

#### Police refusée
- Processus de refus
- Motifs de refus

#### Profession et tâches
- Description détaillée requise
- Impact sur la tarification

#### Proposition
- Validité de 12 mois
- Questions obligatoires
- Réponses fidèles et complètes

#### Proposition et réponses aux questions
- Remplissage au moment de l'entretien
- Questions posées avec soin
- Réponses inscrites entièrement

#### Proposition préliminaire
- Processus préliminaire
- Conditions spéciales

#### Propositions d'ÉSG et propositions entièrement souscrites concordantes
- Règles de concordance
- Processus de traitement

#### Propositions d'OAARF et d'ÉSG concordantes
- Règles de concordance
- Processus de traitement

#### Rapport du représentant
- Signature obligatoire
- Responsabilités

#### Remplacement
- Processus de remplacement
- Obligations de divulgation

#### Signatures
- Signature obligatoire
- Conditions de signature

---

## Directives détaillées

### Proposition (11/2013)

#### Définition
La proposition identifie la personne à assurer, précise le genre d'assurance et de garanties demandées et fournit certains renseignements tels des précisions sur d'autres assurances en vigueur et récemment demandées, ainsi que des renseignements financiers de base et les antécédents médicaux de la personne à assurer.

#### Contenu
La proposition renferme également des précisions nécessaires à la tarification dans le cas de contrats spécialisés ou de situations exceptionnelles. La proposition a été conçue de façon à contenir le plus petit nombre possible de questions nécessaires à une sélection normale.

#### Obligations
- Toutes les questions dans la proposition doivent être posées au proposant
- Toutes réponses doivent être fidèlement et complètement enregistrées
- Les déclarations faites au conseiller en assurance et non consignées dans la proposition n'imposent aucune obligation à la Compagnie

#### Validité
Une proposition d'assurance est valide pendant 12 mois.

### Propositions et réponses aux questions (29 juillet 2024)

#### Remplissage de la proposition
- Il est préférable que la proposition soit remplie au moment même de l'entretien du conseiller en assurance avec le proposant
- Le conseiller en assurance doit poser toutes les questions avec soin et les réponses doivent être inscrites entièrement
- Un examen paramédical peut être complété au lieu de la partie 2 de la proposition si la proposition d'assurance invalidité fait partie d'un Régime D'Indemnités Pour Perte de Salaire (RIPS)

#### Conversation téléphonique
- La proposition peut être remplie au cours d'une conversation téléphonique entre le conseiller en assurance et le proposant
- Le conseiller doit dûment remplir la proposition en enregistrant les réponses du proposant aux questions contenues dans la proposition
- Ensuite, le conseiller envoie la proposition à la personne à assurer/le titulaire proposé pour examen, signature et date
- La proposition est par la suite retournée au conseiller en assurance qui signe et remplit le Rapport du Représentant

#### Exigences géographiques
- Les propositions doivent être remplies et signées au Canada
- L'assuré et le titulaire doivent chacun être résidents canadiens
- L'assuré et le titulaire doivent chacun signer la proposition dans la province où le conseiller est autorisé
- Aucune proposition ne peut être obtenue dans une province ou un pays dans lequel le conseiller en assurance n'est pas autorisé à réaliser des affaires à la date de rédaction de la proposition

#### Règles de modification
- Toutes les questions doivent avoir été répondues avant la signature de la proposition
- Tout changement, ajout ou rature à la partie de la proposition du proposant doit être apporté en sa présence et doit porter les initiales du proposant
- Personne ne peut ajouter, raturer, altérer ou modifier tout renseignement contenu sur ces pages une fois que la proposition a été signée
- Des propositions non remplies ne peuvent pas être signées, en aucun cas

#### Autorisation
- La souscription ne peut pas commencer tant qu'une Convention et une Autorisation signées n'ont pas été reçues

### Autorisation

#### Exigences
Il est essentiel que la partie Autorisation de la proposition soit signée et datée, aussi bien dans le cas de propositions préliminaires que dans celui de propositions ordinaires.

#### Restrictions
Nous ne sommes pas en mesure de traiter une proposition quelconque dont l'Autorisation n'a pas été signée, comporte quelque restriction ou a été modifiée.

### Note de couverture (30 novembre 2022)

#### Produits d'assurance individuelle en cas d'invalidité

##### Protection conditionnelle
Si un acompte minimal est versé au moment de la proposition, le proposant est protégé par la Note de couverture, s'il est un risque assurable. En d'autres termes, si le proposant n'est pas assurable, pour une raison quelconque (revenu, profession, antécédents médicaux), à la date de la proposition, il n'est pas assuré en vertu de la Note de couverture.

##### Acompte minimal
L'acompte minimal correspond au montant de la prime mensuelle, lorsque la prime est payable mensuellement, et à 10% de la prime annuelle, dans le cas des autres modes de paiement.

##### Chèques acceptés
Nous acceptons les chèques datés de 10 jours civils avant ou après la date de la proposition. Tous les autres chèques doivent être retournés au client. Le chèque doit être soumis avec la proposition car nous n'accepterons pas d'argent pendant la tarification.

##### Entrée en vigueur
L'assurance en vertu de la Note de couverture entre en vigueur à la dernière des éventualités suivantes :
- La date à laquelle nous avons reçu l'acompte minimal, ou
- La date à laquelle la proposition et tous les examens médicaux et tous les tests supplémentaires que nous avons exigés conformément à nos directives et pratiques de tarification sont terminés, ou
- La date d'effet précisée dans la proposition par la personne à assurer, si cette date est postérieure

##### Conditions d'assurance
L'assurance prévue par la Note de couverture est assujettie aux conditions suivantes :
- Nous devons recevoir l'acompte minimal requis
- La personne à assurer a rempli la proposition et a subi tous les examens médicaux et les tests supplémentaires que nous avons exigés
- La personne à assurer est admissible à l'assurance, conformément à nos directives et pratiques de tarification
- Le Rapport du Conseiller a été signé par un conseiller en assurance autorisé

##### Exclusions
Aucune assurance n'est prévue par la Note de couverture :
- Si le proposant répond « oui » à la question 1 ou 2 de la Note de couverture ou n'y inscrit rien
- S'il est question d'une non-déclaration de faits importants dans la proposition
- Si le décès est en raison d'un suicide
- Si le proposant n'est pas assurable selon nos directives et pratiques de tarification

##### Proposition sans exigence médicale d'office
Si un proposant est assurable comme risque normal ou taré, ce proposant est protégé par la Note de couverture (sous réserve de ses modalités et restrictions) à compter de la date de la proposition, si aucune exigence médicale d'office n'est requise d'après l'âge du proposant ou le montant d'assurance souscrit.

##### Proposition comportant des exigences médicales d'office
Si nous devons exiger, d'après le montant d'assurance souscrit, une analyse de sang, d'urine, un examen paramédical, une entrevue téléphonique, ou des signes vitaux selon nos exigences médicales d'office publiées, l'assurance prévue par la Note de couverture ne prend effet que le jour où cette exigence est remplie.

##### Résiliation de la Note de couverture
Si l'assurance conditionnelle entre en vigueur, celle-ci prendra fin à la première des éventualités suivantes :
- La date à laquelle une police quelconque, établie par suite de la proposition, est délivrée au proposant et prend effet
- 90 jours suivant la date d'effet
- La date à laquelle nous vous avisons par écrit ne pas être en mesure d'approuver l'établissement de la police

#### Régimes rétablissement d'une maladie grave

##### Caractéristiques
Le libellé et les modalités de cette Note de couverture prévoient un montant limité d'assurance provisoire pendant la durée du processus de tarification.

##### Différences avec l'assurance invalidité
- La Note de couverture pour une assurance en cas de maladie grave ne protège pas l'assurabilité du proposant, tel qu'il est le cas pour l'assurance invalidité
- L'assurance prévue par cette Note de couverture n'est pas conditionnelle aux exigences médicales d'office, tel qu'il est le cas pour l'assurance invalidité

##### Critères d'admissibilité
Un proposant doit répondre aux critères d'admissibilité stipulés dans la Demande de Note de couverture relative aux propositions d'assurance maladie grave et l'assurance provisoire est assujettie aux modalités de la Quittance et Note de couverture.

##### Remplacement interne
Lorsqu'une proposition est déposée en tant que remplacement interne, contrairement à l'assurance invalidité, aucune assurance conditionnelle n'est en vigueur à moins que le proposant réponde aux critères d'admissibilité établis dans la Demande de Note de couverture relative aux propositions d'assurance maladie grave et que le dépôt de prime ait été versé.

##### Non-admissibilité
La personne à assurer n'est pas admissible à faire une demande de note de couverture relative aux propositions d'assurance maladies graves, si :
- L'une des questions est répondu « oui » sur la demande de note de couverture relative aux propositions d'assurance maladies graves, ou n'y inscrit rien
- La personne à assurer a plus de 64 ans
- A une assurance maladies graves en vigueur auprès de la Compagnie d'assurance vie RBC ou qu'une assurance maladies graves est en vigueur ou à l'étude auprès d'une autre compagnie d'assurance et que le montant total cumulative de ses assurances s'élève à 250 000$ ou plus

### Datation et déclaration signée confirmant aucun changement dans l'état de santé (29 septembre 2022)

#### Règles de datation
- La date indiquée sur la proposition doit être celle à laquelle cette dernière a été remplie
- Cette date ne peut en aucun cas être changée
- Toutes les polices établies portent la date courante, sauf lorsqu'une autre date est demandée expressément

#### Date courante
La date courante est celle qui correspond à cinq jours ouvrables suivant la date à laquelle nous avons établi la police, sauf dans le cas des polices de la série Avant-garde ou Rachat en cas d'invalidité, dont la date d'établissement est la même que la date à laquelle nous établissons la police.

#### Restrictions de datation
- Nous ne datons pas les polices du 29, 30 ou 31 du mois
- Pour éviter ces dates, l'assurance sera datée du premier du mois suivant
- Aucun acompte sera accepté après qu'une proposition aura été soumise pour étude au service de la tarification

#### Déclaration de santé
Toutes les polices approuvées plus de 90 jours après la date de la proposition (ou date du paramédical ou de l'entrevue téléphonique, s'il y a lieu) comprendront une déclaration à signer pour confirmer qu'il n'y a aucun changement dans l'état de santé du proposant ni aucun changement dans les réponses aux questions contenues dans la proposition.

#### Sauvegarde de l'âge
- L'obtention d'un acompte au moment de la proposition afin de protéger au maximum le proposant au titre de la Note de couverture est d'une grande valeur
- Afin de sauvegarder l'âge, nous antidaterons les polices d'au plus trente jours avant la date de la proposition
- Nous émettons toute police avec date courante, à moins qu'une demande expresse de sauvegarder l'âge nous ait été présentée

#### Remplacements
- Les remplacements internes seront datés de la date à laquelle les primes de la police à remplacer sont payées
- À l'exception de l'assurance en cas de maladie grave, les propositions soumises pour remplacements internes sont considérées comme des propositions prépayées
- Les remplacements internes d'une police en déchéance porteront la date courante

#### Demandes de date précise
- Les demandes de date précise doivent être faites au moment de la proposition ou, au moins, avant l'approbation de la police
- Une proposition visant à remplacer une assurance en vigueur auprès d'un autre assureur portera la date de remplacement de l'autre assurance
- La demande de datation de remplacement doit être faite au moment de la proposition et la date exacte du remplacement doit y être précisée
- Cette date ne peut tomber plus de 90 jours après celle de la proposition

#### Classement des propositions
- Toutes les propositions seront classées comme étant incomplètes 90 jours après la date de la proposition
- Tout acompte sur la prime sera remboursé au titulaire proposé
- Lorsqu'une proposition classée comme incomplète est par la suite rouverte, la prime est exigible à la délivrance de la police

### Âge à l'établissement de la police

#### Calcul de l'âge
Sauf pour les polices de la série Avant-garde et Rachat en cas d'invalidité, où l'âge est calculé en fonction du dernier anniversaire de naissance, l'âge est calculé selon le plus proche anniversaire plutôt que le dernier anniversaire.

#### Exemple
Si la date d'anniversaire du proposant est le 24 décembre 1960 et il souscrit à une assurance le 29 juillet 2004, l'âge à l'établissement de l'assurance est 44 (même s'il n'aura pas 44 ans avant son prochain anniversaire).

#### Règle des six mois
Il pourrait s'avérer utile de se rappeler que si le proposant fait sa demande d'assurance six mois et un jour après son dernier anniversaire, l'âge au plus proche anniversaire est celui qui doit être retenu aux fins du calcul des taux.

#### Antidatation
Il est possible d'antidater une assurance jusqu'à 30 jours avant la date réelle de la proposition aux fins de retenir l'âge inférieur. Dans ce cas, la demande de « sauvegarde de l'âge » doit être indiquée sur la proposition.

### Document légal

#### Statut juridique
La proposition fait partie intégrante du contrat d'assurance, ce contrat étant un document légal.

#### Droits juridiques
Les droits juridiques à la fois de la personne à assurer et de la Compagnie sont régis par la proposition s'il advenait que des problèmes d'ordre juridique surgiraient par la suite.

### Lisibilité (29 septembre 2017)

#### Exigences d'écriture
- Les propositions manuscrites doivent être remplies à l'encre, de préférence à l'encre noire ou bleue
- Une écriture lisible accélère le processus de la tarification en évitant les demandes d'éclaircissement

#### Restrictions
- On ne doit pas appliquer de liquide correcteur sur les réponses ni récrire par-dessus
- Une réponse trop longue pour l'espace prévu peut se poursuivre sur une feuille distincte, clairement identifiée, annexée à la proposition
- Cette information supplémentaire doit être signée et datée par la personne à assurer

### Antécédents médicaux

#### Importance
Les antécédents médicaux du proposant représentent un des éléments les plus importants au cours du processus de la tarification.

#### Exigences
Il est essentiel que les réponses inscrites soient complètes et claires. Les antécédents médicaux devraient non seulement identifier le problème d'ordre médical, mais aussi fournir :
- Les symptômes
- Le diagnostic
- Le traitement
- La date de survenance
- La durée des symptômes
- La durée d'absence au travail
- Le nom et l'adresse de tous les médecins

### Fiche d'information à l'intention du consommateur-préavis (1 juin 2021)

#### Obligation
La Fiche D'Information à L'Intention du Consommateur – Préavis doit être remise au proposant lorsque la proposition est signée.

#### Contenu
La Fiche D'Information à L'Intention du Consommateur – Préavis fournit à la personne à assurer un avis écrit concernant :
- Le processus du Bureau de renseignements médicaux (BRM)
- Notre Entretien sur les antécédents personnels (EAP)

### Limites d'âges minimal et maximal à la souscription

#### Référence
Veuillez vous reporter aux détails des régimes précis dans la section Renseignements sur les produits.

#### Disponibilité des taux
La disponibilité des taux indique l'âge minimal et l'âge maximal auquel chacun de nos produits en cas d'invalidité est offert.

### Montant minimal de la police

#### Polices individuelles en cas d'invalidité
Le montant minimal d'une police individuelle en cas d'invalidité est de 450$ d'indemnisation mensuelle totale.

#### Composition
Ce montant peut représenter :
- Seulement une indemnisation de base de 450$
- Une indemnisation minimale de base de 150$, en plus d'une indemnisation mensuelle complémentaire (avec période d'indemnisation de plus de six mois)

#### Majoration
Une fois que les exigences relatives au montant minimal de la police ont été satisfaites, l'indemnisation peut être majorée en tranches de 25$.

### Noms

#### Exigences
- Le nom de la personne à assurer doit être inscrit lisiblement et correctement en caractères d'imprimerie et être celui qui est légalement connu
- Les bons titres doivent être donnés
- Le contrat et tout document s'y rattachant porteront le nom tel qu'il figure sur la proposition

#### Format de la police
Une fois établie, la police figurera le nom, généralement dans l'ordre habituel : prénom, initiale du second nom et nom de famille.

#### Anciens noms
- Assurez-vous d'indiquer tous les anciens noms
- Sur la page fournie dans la proposition pour tout autre renseignement pertinent, veuillez fournir les détails concernant tout changement de nom depuis la dernière proposition

---

## Points clés à retenir

### Processus de tarification
- **Propositions uniques** : Chaque proposant et chaque proposition sont uniques
- **Processus dynamique** : La tarification est un processus dynamique nécessitant une évaluation complète
- **Décision du tarificateur** : Tous les aspects du cas sont considérés avant une décision appropriée

### Qualité de la proposition
- **Document de référence** : La proposition est le document de référence le plus important
- **Renseignements complets** : Les renseignements doivent être complets, précis et de première main
- **Impact sur la tarification** : La qualité des renseignements influence directement les exigences additionnelles et les délais

### Règles de remplissage
- **Validité** : Une proposition est valide pendant 12 mois
- **Questions obligatoires** : Toutes les questions doivent être posées et répondues fidèlement
- **Signature** : Toutes les questions doivent être répondues avant la signature
- **Modifications** : Aucune modification après signature sans initiales du proposant

### Note de couverture
- **Protection conditionnelle** : Protection si le proposant est un risque assurable
- **Acompte minimal** : Prime mensuelle ou 10% de la prime annuelle
- **Entrée en vigueur** : À la dernière des éventualités (acompte, examens terminés, date d'effet)
- **Durée** : 90 jours maximum ou jusqu'à délivrance de la police

### Règles de datation
- **Date de la proposition** : Non modifiable après remplissage
- **Date courante** : 5 jours ouvrables après établissement de la police
- **Sauvegarde de l'âge** : Antidatation possible jusqu'à 30 jours
- **Déclaration de santé** : Requise après 90 jours

### Exigences médicales
- **Importance** : Les antécédents médicaux sont un des éléments les plus importants
- **Complétude** : Les réponses doivent être complètes et claires
- **Détails requis** : Symptômes, diagnostic, traitement, dates, durées, médecins

### Montants minimaux
- **Assurance invalidité** : 450$ d'indemnisation mensuelle totale
- **Majoration** : En tranches de 25$ après le minimum
- **Composition** : Base seule ou base + complémentaire

### Règles géographiques
- **Signature au Canada** : Obligatoire pour l'assuré et le titulaire
- **Résidence canadienne** : Requise pour l'assuré et le titulaire
- **Autorisation provinciale** : Le conseiller doit être autorisé dans la province

---

## Métadonnées pour indexation

**Mots-clés:** directives de tarification, assurance invalidité, assurance maladies graves, RBC Assurance, proposition d'assurance, note de couverture

**Types de produits:** Série Avant-garde, Série Fondations, Série Fondamentale, Série Professions, Quantum, Maladie Grave, Protection Retraite, Protection Prêt commercial, Frais généraux d'entreprise, Rachat en cas d'invalidité, Protection Personne clé

**Processus de tarification:** Proposition, Note de couverture, Exigences médicales, Exigences financières, Délivrance de police

**Règles de proposition:** Validité 12 mois, Questions obligatoires, Signature obligatoire, Modifications interdites, Renseignements complets

**Note de couverture:** Acompte minimal, Protection conditionnelle, Entrée en vigueur, Durée 90 jours, Exclusions

**Règles de datation:** Date courante, Sauvegarde de l'âge, Antidatation 30 jours, Déclaration de santé après 90 jours

**Exigences médicales:** Antécédents médicaux, Symptômes, Diagnostic, Traitement, Dates, Durées, Médecins

**Montants minimaux:** 450$ indemnisation mensuelle, Majoration 25$, Base 150$, Complémentaire

**Règles géographiques:** Signature au Canada, Résidence canadienne, Autorisation provinciale, Conseiller autorisé

**Exclusions:** Non-déclaration, Suicide, Non-assurabilité, Questions répondues oui, Restrictions