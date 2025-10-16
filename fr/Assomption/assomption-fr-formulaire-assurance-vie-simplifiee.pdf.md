---
# Document Metadata
document_id: "assomption-fr-formulaire-assurance-vie-simplifiee-v1.0"
document_type: application_form
schema_version: "2.0"
version: 1.0
document_title: "Formulaire de Collecte de Données - Assurance Vie Simplifiée Assomption Vie"
full_product_name: "Simplified Life Insurance Application Form (Assomption Vie)"
total_pages: 10
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
    - "Protection Or Vie Entière"
    - "Protection Argent"
    - "Protection Bronze"
    - "Protection Platine Temporaire"
    - "Protection Or Temporaire"

# Classification
language: fr-CA
region: CA
target_audience: 
  - insurance_agents
  - advisors
  - data_entry_staff

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
  - assurance-vie-simplifiee
  - formulaire
  - collecte-donnees
  - assomption
  - protection-platine
  - protection-or
  - protection-argent
  - protection-bronze
  - lia

# Machine-Readable Features
features:
  electronic_application: true
  medical_questionnaire: true
  underwriting_tiers: true
  data_collection: true
  lia_integration: true

# Disclaimer
disclaimer: "Ceci n'est pas une proposition - ne pas soumettre. Document de collecte de données uniquement."

# Document Structure Map
sections:
  - id: notice_importante
    name: "Notice Importante"
    type: notice
    line_start: 41
  - id: table_matieres
    name: "Table des Matières"
    type: reference
    line_start: 49
  - id: section_1
    name: "Section 1 - Personne à Assurer"
    type: form_section
    line_start: 66
  - id: section_2
    name: "Section 2 - Propriétaire de la Police"
    type: form_section
    line_start: 128
  - id: section_3
    name: "Section 3 - Déclaration de Résidence aux Fins de l'Impôt"
    type: form_section
    line_start: 198
  - id: section_4
    name: "Section 4 - Désignation de Bénéficiaire"
    type: form_section
    line_start: 254
  - id: section_5
    name: "Section 5 - Remplacement d'Assurance"
    type: form_section
    line_start: 304
  - id: section_6
    name: "Section 6 - Sélection du Produit"
    type: form_section
    line_start: 325
  - id: section_7
    name: "Section 7 - Déclarations d'Assurabilité"
    type: form_section
    line_start: 445
  - id: section_8
    name: "Section 8 - Prime et Mode de Paiement"
    type: form_section
    line_start: 787
  - id: section_9
    name: "Section 9 - Accord de Débit Préautorisé"
    type: form_section
    line_start: 825
  - id: section_10
    name: "Section 10 - Directives Spéciales"
    type: form_section
    line_start: 898

# Document Segments (Original PDF)
document_segments:
  - name: "Formulaire Assurance Vie Simplifiée"
    pages: 0-10
    confidence: High

# Document Statistics
statistics:
  total_form_sections: 10
  underwriting_tiers: 4
  medical_questions_by_tier:
    platine: 19
    or: 13
    argent: 9
    bronze: 0
  product_variants: 6
  riders: 3
  coverage_amounts:
    min: 5000
    max: 750000
  age_ranges:
    min: 18
    max: 85
---

# Formulaire de Collecte de Données
## Assurance Vie Simplifiée - Assomption Vie

---

## Notice Importante

**Ce document a pour but de recueillir des données sur la personne à assurer afin de les saisir dans l'application électronique Lia.**

⚠️ **CECI N'EST PAS UNE PROPOSITION - NE PAS SOUMETTRE**

---

## Table des Matières

| Section | Titre | Page de Référence |
|---|---|---|
| **Section 1** | Personne à Assurer | - |
| **Section 2** | Propriétaire de la Police | - |
| **Section 3** | Déclaration de Résidence aux Fins de l'Impôt | - |
| **Section 4** | Désignation de Bénéficiaire | - |
| **Section 5** | Remplacement d'Assurance | - |
| **Section 6** | Sélection du Produit | - |
| **Section 7** | Déclarations d'Assurabilité | - |
| **Section 8** | Prime et Mode de Paiement | - |
| **Section 9** | Accord de Débit Préautorisé (DPA) | - |
| **Section 10** | Directives Spéciales | - |

---

## Section 1 - Personne à Assurer

### Informations Personnelles

| Champ | Information |
|---|---|
| **Prénom** | _________________ |
| **Nom de famille** | _________________ |
| **Nom à la naissance** (si différent) | _________________ |

### Adresse

| Champ | Information |
|---|---|
| **Numéro civique** | _____ |
| **Rue** | _________________ |
| **Appartement** | _____ |
| **Case postale** | _____ |
| **Ville** | _________________ |
| **Province/Territoire** | _________________ |
| **Code postal** | _________________ |

### Informations de Naissance

| Champ | Information |
|---|---|
| **Date de naissance** | JJ / MM / AAAA: _____ / _____ / _________ |
| **Âge** (au plus proche anniversaire) | _____ ans |
| **Province de naissance** | _________________ |
| **Pays de naissance** | _________________ |
| **Sexe** | ☐ M  ☐ F |

### Statut de Résidence au Canada

| Statut | Sélection |
|---|---|
| ☐ Canadien(ne) | |
| ☐ Résident(e) permanent(e) | |
| ☐ Autre (précisez): _________________ | Si autre, date du statut: JJ / MM / AAAA |

### Coordonnées

| Champ | Information |
|---|---|
| **Numéro d'assurance sociale** | _____ - _____ - _____ |
| **Téléphone domicile** | (____) _____ - ________ |
| **Téléphone bureau** | (____) _____ - ________ |
| **Courriel** | _________________ |

### Statut Fumeur

**Question:** Au cours des douze derniers mois, avez-vous fait usage de substances ou produits contenant du tabac, de la nicotine ou de la marijuana mélangée à de la nicotine ou fait usage de cigarettes électroniques?

| Réponse | Classe de Prime |
|---|---|
| ☐ Non | Classe non-fumeur |
| ☐ Oui | Classe fumeur |

**Important:** Veuillez vérifier la date de naissance de la personne à assurer au moyen d'une pièce d'identité originale.

---

## Section 2 - Propriétaire de la Police

### Type de Propriétaire

| Option | Sélection |
|---|---|
| ☐ **Personne à assurer** (même personne qu'en Section 1) | |
| ☐ **Autre** (Personne morale ou personne autre que la personne à assurer) | |

### Informations du Propriétaire (Si autre que la personne à assurer)

#### Personne Physique

| Champ | Information |
|---|---|
| **Prénom** | _________________ |
| **Nom de famille** | _________________ |
| **Lien avec la personne à assurer** | _________________ |

**Adresse:**

| Champ | Information |
|---|---|
| **Numéro civique** | _____ |
| **Rue** | _________________ |
| **Appartement** | _____ |
| **Case postale** | _____ |
| **Ville** | _________________ |
| **Province/Territoire** | _________________ |
| **Code postal** | _________________ |

**Autres informations:**

| Champ | Information |
|---|---|
| **Date de naissance** | JJ / MM / AAAA: _____ / _____ / _________ |
| **Sexe** | ☐ M  ☐ F |
| **Numéro d'assurance sociale** | _____ - _____ - _____ |
| **Téléphone domicile** | (____) _____ - ________ |
| **Téléphone bureau** | (____) _____ - ________ |
| **Courriel** | _________________ |

#### Personne Morale (Si applicable)

**Remplissez cette section si le propriétaire est une corporation, société, etc.**

| Champ | Information |
|---|---|
| **Nom de la personne morale** | _________________ |
| **Numéro d'enregistrement** | _________________ |
| **Lien avec la personne à assurer** | _________________ |

**Administrateurs de la société:**

| Administrateur | Nom Complet |
|---|---|
| 1. | _________________ |
| 2. | _________________ |
| 3. | _________________ |
| 4. | _________________ |

**Personnes autorisées à signer:**

| Nom | Titre |
|---|---|
| _________________ | _________________ |
| _________________ | _________________ |

---

## Section 3 - Déclaration de Résidence aux Fins de l'Impôt

### Contexte Légal

Selon la **partie XVIII et partie XIX de la Loi de l'impôt sur le revenu**, les institutions financières canadiennes doivent recueillir les renseignements que vous fournissez sur ce formulaire pour déterminer si elles doivent signaler l'existence de votre compte financier à l'**Agence du revenu du Canada (ARC)**.

**Important:**
- L'ARC peut communiquer ces renseignements au gouvernement d'une juridiction étrangère dont vous êtes résident aux fins de l'impôt
- Ou au gouvernement des États-Unis si vous êtes citoyen de ce pays
- Vous pouvez demander à votre institution financière si elle a signalé l'existence de votre compte financier à l'ARC et quels renseignements elle lui a fournis

**Note pour personne morale:** Veuillez compléter le formulaire RC519 disponible dans notre centre de documentation sur le Coin du conseiller.

### Sélectionnez Tout ce qui S'applique

#### Résidence Canadienne

| Statut | Sélection |
|---|---|
| ☐ **Le propriétaire est un résident ou résidente du Canada aux fins de l'impôt** | |

#### Résidence Américaine

| Statut | Sélection |
|---|---|
| ☐ **Le propriétaire est un résident des États-Unis aux fins de l'impôt ou de citoyenneté américaine** | |
| **Numéro d'identification fiscal (NIF) des États-Unis:** | _____ - _____ - _________ |

**Si le propriétaire n'a pas de NIF des États-Unis:**
- Il devra faire une demande de NIF dans les **90 jours** suivant la soumission de la proposition
- Une fois le NIF reçu, le propriétaire s'engage-t-il à le fournir à Assomption Vie dans les **15 jours** suivant sa réception?
  - ☐ Oui
  - ☐ Non

⚠️ **Si le propriétaire n'accepte pas de suivre les exigences de l'ARC, il ne peut continuer le processus de demande.**

#### Autre Juridiction

| Statut | Sélection |
|---|---|
| ☐ **Le propriétaire est un résident d'une juridiction autre que le Canada ou les États-Unis aux fins de l'impôt** | |
| **Juridiction:** | _________________ |
| **Numéro d'identification fiscal (NIF):** | _________________ |

**Si le propriétaire n'a pas de NIF pour une juridiction spécifique, sélectionnez la raison:**

| Raison | Sélection |
|---|---|
| ☐ La demande est en cours et/ou sera effectuée dans les 90 jours | |
| ☐ L'impôt n'émet pas de NIF à ses résidents | |
| ☐ Autres raisons | |

**Note:** Pour ce formulaire, « Autres raisons » est suffisant. Cependant, vous devez quand même donner la raison précise à votre institution financière.

---

## Section 4 - Désignation de Bénéficiaire

### Bénéficiaires Primaires

| Prénom | Nom de Famille | Lien de Parenté* | Âge | %** | Révocable / Irrévocable |
|---|---|---|---|---|---|
| _________ | _________ | _________ | ___ | ___% | ☐ Rév. ☐ Irr. |
| _________ | _________ | _________ | ___ | ___% | ☐ Rév. ☐ Irr. |
| _________ | _________ | _________ | ___ | ___% | ☐ Rév. ☐ Irr. |

*Au Québec: lien avec le propriétaire

### Bénéficiaires en Sous-Ordre

**Si tous les bénéficiaires primaires décèdent avant la personne à assurer:**

| Prénom | Nom de Famille | Lien de Parenté* | Âge | %** | Révocable / Irrévocable |
|---|---|---|---|---|---|
| _________ | _________ | _________ | ___ | ___% | ☐ Rév. ☐ Irr. |
| _________ | _________ | _________ | ___ | ___% | ☐ Rév. ☐ Irr. |

### Désignation d'un Fiduciaire (Optionnel)

**Dans le cas d'un bénéficiaire mineur, veuillez désigner un fiduciaire:**

| Nom du Fiduciaire | Lien avec le Bénéficiaire |
|---|---|
| _________________ | _________________ |

### Notes Importantes sur les Bénéficiaires

**Pourcentage (%):**
- Si un pourcentage n'est pas indiqué, les prestations de décès seront payables à parts égales aux bénéficiaires survivant de la personne à assurer
- Si un % est indiqué et qu'un bénéficiaire subrogé a été désigné, les prestations de décès seront payables au bénéficiaire subrogé dans le cas où le bénéficiaire principal décède avant la personne à assurer
- Si tous bénéficiaires principaux ou subrogés sont décédés avant la personne à assurer, les prestations de décès seront divisées également entre tous les bénéficiaires en sous-ordre désignés encore vivants après le décès de la personne à assurer
- Vous pouvez désigner un bénéficiaire subrogé en soumettant le formulaire de « Changement de bénéficiaire – Option bénéficiaire subrogé » disponible dans le Centre de documentation

**Au Québec:**
- La désignation du conjoint en vertu d'un mariage ou d'une union civile du propriétaire à titre de bénéficiaire est automatiquement **irrévocable**, à moins d'indication contraire

**Révocable (Rév.) ou Irrévocable (Irr.):**
- À moins d'indication contraire ou que cela ne soit pas permis par la loi, toute désignation de bénéficiaire est révocable
- Si un bénéficiaire est désigné à titre irrévocable, son consentement sera requis lors de toute demande qui pourrait affecter ses droits, incluant la désignation d'un nouveau bénéficiaire

**Droits des bénéficiaires:**
- La police ne confère aucun droit aux bénéficiaires en sous-ordre avant le décès des bénéficiaires primaires et subrogés
- La police ne confère aucun droit aux bénéficiaires subrogés avant le décès des bénéficiaires primaires

---

## Section 5 - Remplacement d'Assurance

### Questions sur le Remplacement

| Question | Réponse |
|---|---|
| **L'assurance demandée a-t-elle pour but de remplacer toute autre assurance vie individuelle?** | ☐ Non  ☐ Oui |
| **Si « Oui », est-ce que la police originale à remplacer est une police d'Assomption Vie?** | ☐ Non  ☐ Oui |

### Avis Important - Remplacement de Police

**Si vous remplacez une assurance vie existante:**

1. **Exigences provinciales:** Veuillez vous assurer de satisfaire aux exigences de la province de la personne à assurer en matière de divulgation à l'égard du remplacement d'une police d'assurance vie

2. **Police Assomption Vie:** Si la police originale étant remplacée en est une d'Assomption Vie:
   - Un avis écrit OU une « demande de service » signée par le propriétaire de la police originale doit être envoyée à Assomption Vie
   - Ceci afin de résilier la police existante

---

## Section 6 - Sélection du Produit

### Produits Vie Entière

#### Protection Platine Vie Entière

**Type de couverture:** Immédiate  
**Déclaration d'assurabilité:** Page 5

| Âge à l'Émission | Capital Assuré Min. | Capital Assuré Max. | Options de Paiement |
|---|---|---|---|
| 18-50 ans | 10 000 $ | 750 000 $ | ☐ Payables à vie  ☐ Payables sur 20 ans |
| 51-75 ans | 10 000 $ | 500 000 $ | ☐ Payables à vie  ☐ Payables sur 20 ans |
| 76-80 ans | 10 000 $ | 250 000 $ | ☐ Payables à vie  ☐ Payables sur 20 ans |
| 81-85 ans | 10 000 $ | 250 000 $ | ☐ Payables à vie |

**Capital assuré demandé:** _____________ $

---

#### Protection Or Vie Entière

**Type de couverture:** Immédiate  
**Déclaration d'assurabilité:** Page 7

| Âge à l'Émission | Capital Assuré Min. | Capital Assuré Max. | Options de Paiement |
|---|---|---|---|
| 18-75 ans | 5 000 $ | 250 000 $ | ☐ Payables à vie  ☐ Payables sur 20 ans |
| 76-80 ans | 5 000 $ | 100 000 $ | ☐ Payables à vie  ☐ Payables sur 20 ans |
| 81-85 ans | 5 000 $ | 100 000 $ | ☐ Payables à vie |

**Capital assuré demandé:** _____________ $

---

#### Protection Argent

**Type de couverture:** Différée progressive*  
**Déclaration d'assurabilité:** Page 9

| Âge à l'Émission | Capital Assuré Min. | Capital Assuré Max. | Options de Paiement |
|---|---|---|---|
| 18-75 ans | 5 000 $ | 50 000 $ | ☐ Payables à vie  ☐ Payables sur 20 ans |
| 76-80 ans | 5 000 $ | 25 000 $ | ☐ Payables à vie  ☐ Payables sur 20 ans |
| 81-85 ans | 5 000 $ | 25 000 $ | ☐ Payables à vie |

**Capital assuré demandé:** _____________ $

**Prestation de décès différée progressive:*
- Aux primes payées avec intérêt de 3 % par an si le décès de l'assuré est non accidentel et survient **avant le 1er anniversaire** de la police ou de l'avenant
- À **50 % du capital assuré** si le décès de l'assuré est non accidentel et survient **entre le 1er et avant le 2e anniversaire** de la police ou de l'avenant
- À **100 % du capital assuré** si le décès de l'assuré est non accidentel et survient **à partir du 2e anniversaire** de la police ou de l'avenant

---

#### Protection Bronze

**Type de couverture:** Différée  
**Produit à émission garantie - Aucune déclaration d'assurabilité requise**

| Âge à l'Émission | Capital Assuré Min. | Capital Assuré Max. | Options de Paiement |
|---|---|---|---|
| 18-75 ans | 5 000 $ | 50 000 $ | ☐ Payables à vie |
| 76-80 ans | 5 000 $ | 25 000 $ | ☐ Payables à vie |

**Capital assuré demandé:** _____________ $

---

### Produits Temporaires

#### Protection Platine Temporaire

**Type de couverture:** Immédiate  
**Déclaration d'assurabilité:** Page 5

| Âge à l'Émission | Capital Assuré Min. | Capital Assuré Max. | Options de Terme |
|---|---|---|---|
| 18-44 ans | 50 000 $ | 750 000 $ | ☐ Terme 10  ☐ Terme 20 |
| 45-50 ans | 25 000 $ | 750 000 $ | ☐ Terme 10  ☐ Terme 20 |
| 51-70 ans | 25 000 $ | 500 000 $ | ☐ Terme 10  ☐ Terme 20 |
| 71-75 ans | 25 000 $ | 500 000 $ | ☐ Terme 10 |

**Capital assuré demandé:** _____________ $

---

#### Protection Or Temporaire

**Type de couverture:** Immédiate  
**Déclaration d'assurabilité:** Page 7

| Âge à l'Émission | Capital Assuré Min. | Capital Assuré Max. | Options de Terme |
|---|---|---|---|
| 18-44 ans | 50 000 $ | 250 000 $ | ☐ Terme 20 |
| 45-70 ans | 25 000 $ | 250 000 $ | ☐ Terme 20 |

**Capital assuré demandé:** _____________ $

---

### Garanties Complémentaires (Avenants)

| Produit Principal | FRAC*** | MA**** | BAE***** |
|---|---|---|---|
| **Protection Platine Vie Entière** | ☐ 1 unité  ☐ 2 unités | ☐ _______ $ | ☐ 10 000 $  ☐ 20 000 $ |
| **Protection Platine Temporaire** | ☐ 1 unité  ☐ 2 unités | ☐ _______ $ | ☐ 10 000 $  ☐ 20 000 $ |
| **Protection Or Vie Entière** | ☐ 1 unité  ☐ 2 unités | N/A | N/A |
| **Protection Or Temporaire** | ☐ 1 unité  ☐ 2 unités | N/A | N/A |
| **Protection Argent** | ☐ 1 unité  ☐ 2 unités | N/A | N/A |
| **Protection Bronze** | N/A | N/A | N/A |

**Notes:**
- ***** Ne doit pas excéder la couverture maximale combinée pour une police à émission simplifiée en vigueur chez Assomption Vie
- ***** FRAC: Âge maximal de l'assuré est 69 ans
- ****** MA: Âge maximal de l'assuré est 55 ans. Le montant de l'avenant MA ne peut être supérieur au capital assuré initial
- ******* BAE: Âge maximal de l'assuré est 60 ans

---

## Section 7 - Déclarations d'Assurabilité

### Protection Platine - 19 Questions

**Si vous avez répondu « NON » aux 19 questions ci-dessous, vous êtes éligible pour la Protection Platine Vie Entière ou la Protection Platine Temporaire.**

#### Question 1 - Taille et Poids

**Votre poids dépasse-t-il celui correspondant à votre taille dans le tableau suivant?**

**Taille de l'assuré:** _______ pi _______ po / _______ cm  
**Poids de l'assuré:** _______ lb / _______ kg

| Taille (pi/po) | Taille (cm) | Poids Max (lb) | Poids Max (kg) | Taille (pi/po) | Taille (cm) | Poids Max (lb) | Poids Max (kg) | Taille (pi/po) | Taille (cm) | Poids Max (lb) | Poids Max (kg) |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 4' 10" | 147 | 192 | 87 | 5' 6" | 168 | 247 | 112 | 6' 2" | 188 | 310 | 141 |
| 4' 11" | 150 | 198 | 90 | 5' 7" | 170 | 254 | 115 | 6' 3" | 191 | 318 | 144 |
| 5' 0" | 152 | 205 | 93 | 5' 8" | 173 | 262 | 119 | 6' 4" | 193 | 326 | 148 |
| 5' 1" | 155 | 212 | 96 | 5' 9" | 175 | 270 | 122 | 6' 5" | 196 | 334 | 151 |
| 5' 2" | 157 | 219 | 99 | 5' 10" | 178 | 278 | 126 | 6' 6" | 198 | 342 | 155 |
| 5' 3" | 160 | 226 | 103 | 5' 11" | 180 | 286 | 130 | 6' 7" | 201 | 350 | 159 |
| 5' 4" | 163 | 233 | 106 | 6' 0" | 183 | 294 | 133 | 6' 8" | 203 | 358 | 162 |
| 5' 5" | 165 | 240 | 109 | 6' 1" | 185 | 302 | 137 | 6' 9" | 206 | 366 | 166 |

☐ Non  ☐ Oui

#### Question 2 - Hospitalisation Actuelle

**Êtes-vous présentement:**

a) Admis(e) dans un hôpital?  
☐ Non  ☐ Oui

b) Résident(e) ou êtes-vous sur une liste d'attente pour résider dans un établissement de soins prolongés, dans un foyer de soins infirmiers, dans un établissement de soins qualifiés ou dans tout autre établissement nécessitant des soins d'un personnel qualifié?  
☐ Non  ☐ Oui

#### Question 3 - Perte de Poids

**Au cours des 12 derniers mois, votre poids a-t-il diminué de plus de 9,08 kg (20 lb) autre qu'en raison d'une grossesse, d'une chirurgie bariatrique, d'un régime alimentaire intentionnel ou de l'exercice physique?**

☐ Non  ☐ Oui

#### Question 4 - Chirurgie Bariatrique

**Au cours des 6 derniers mois, avez-vous subi une chirurgie bariatrique?**

☐ Non  ☐ Oui

#### Question 5 - Signes et Symptômes Médicaux

**Êtes-vous au courant de signes, symptômes ou tests médicaux anormaux pour lesquels:**

*(Vous n'avez pas besoin de nous indiquer les symptômes d'un rhume ou d'une grippe, les résultats d'un suivi de routine sans nouveaux symptômes ou ceux d'une visite prénatale de routine.)*

a) Vous n'avez pas encore consulté de médecin ou vous avez consulté un médecin sans avoir reçu de diagnostic?  
☐ Non  ☐ Oui

b) Vous faites présentement l'objet d'une investigation?  
☐ Non  ☐ Oui

c) Vous avez une consultation en cours avec un médecin spécialiste? *(Une consultation en cours n'inclut pas un suivi de routine, et un médecin spécialiste n'inclut pas un médecin généraliste)*  
☐ Non  ☐ Oui

d) Vous avez consulté un médecin spécialiste sans avoir reçu de diagnostic?  
☐ Non  ☐ Oui

e) Vous êtes actuellement en attente d'une intervention chirurgicale *(autre qu'une intervention chirurgicale qui ne nécessite pas une nuit d'hospitalisation, telle qu'une chirurgie d'un jour ou une chirurgie ambulatoire)?*  
☐ Non  ☐ Oui

#### Question 6 - Conditions Médicales Graves

**Avez-vous déjà:**

a) Été avisé par un médecin que vous étiez atteint(e) d'une maladie terminale pour laquelle vous recevez présentement des soins palliatifs ou des soins en fin de vie, ou avez discuté de ce type de soins avec un professionnel de la santé?  
☐ Non  ☐ Oui

b) Eu l'insertion d'un stimulateur cardiaque (pacemaker) ou d'un défibrillateur cardiaque implantable (DCI)?  
☐ Non  ☐ Oui

#### Question 7 - Diagnostics Graves

**Avez-vous déjà reçu un diagnostic en raison:**

**Système immunitaire:**
- a) Du Sida (syndrome d'immunodéficience acquise) ou testé positif au VIH (le virus qui cause le Sida)?  
  ☐ Non  ☐ Oui

**Système nerveux:**
- b) De la maladie de Huntington, de la sclérose latérale amyotrophique (maladie de Lou Gehrig), de la maladie d'Alzheimer ou de la démence?  
  ☐ Non  ☐ Oui

**Système cardiovasculaire:**
- c) D'une insuffisance cardiaque congestive?  
  ☐ Non  ☐ Oui

**Système gastro-intestinal:**
- d) D'une cirrhose du foie, d'une pancréatite chronique, ou 2 épisodes ou plus de pancréatite aiguë?  
  ☐ Non  ☐ Oui

**Système respiratoire:**
- e) De la fibrose kystique?  
  ☐ Non  ☐ Oui

**Système musculosquelettique:**
- f) D'une dystrophie musculaire?  
  ☐ Non  ☐ Oui

#### Question 8 - Diabète avec Complications

**Avez-vous déjà reçu un diagnostic de diabète (autre que le diabète gestationnel) ET avez-vous déjà présenté l'une des conditions suivantes:**
- Crise cardiaque (infarctus du myocarde)
- Angine
- Accident vasculaire cérébral (AVC)
- Maladie vasculaire/artérielle périphérique
- Gangrène
- Amputation liée à des complications de votre diabète (telles qu'une mauvaise circulation ou une infection)
- Coma hypoglycémique
- Neuropathie ou néphropathie

☐ Non  ☐ Oui

#### Question 9 - Dernières 10 Années

**Au cours des 10 dernières années, avez-vous:**

a) Reçu une greffe de la moelle osseuse ou d'organe(s) (autre qu'une greffe de la cornée) ou avez-vous été avisé(e) que votre condition en nécessitait une?  
☐ Non  ☐ Oui

b) Reçu un diagnostic, été hospitalisé(e) ou subi(e) des traitements (y compris un traitement avec des médicaments prescrits) en raison d'une cardiomyopathie ou d'une hépatite B ou C?  
☐ Non  ☐ Oui

c) Nécessité l'administration d'oxygène pour un trouble respiratoire chronique (autre que l'apnée du sommeil)?  
☐ Non  ☐ Oui

#### Question 10 - Dernières 5 Années (Diagnostic ou Hospitalisation)

**Au cours des 5 dernières années, avez-vous reçu un diagnostic ou été hospitalisé(e) en raison:**

**Système nerveux et santé mentale:**
- a) De convulsions, d'épilepsie, de paralysie, de sclérose en plaques ou de troubles bipolaires?  
  ☐ Non  ☐ Oui

**Système cardiovasculaire:**
- b) D'une angine ou d'une crise cardiaque (infarctus du myocarde) ou avez-vous subi une angioplastie coronaire (avec ou sans l'insertion d'un stent/endoprothèse vasculaire) ou un pontage aorto-coronarien?  
  ☐ Non  ☐ Oui

- c) D'un accident vasculaire cérébral (AVC) ou d'un accident ischémique transitoire (AIT ou mini-AVC)?  
  ☐ Non  ☐ Oui

- d) D'un souffle au cœur ou d'une arythmie (rythme cardiaque irrégulier tel que fibrillation/flutter auriculaire, tachycardie, bradycardie, tachycardie supraventriculaire, fibrillation ventriculaire ou battements ectopiques)?  
  ☐ Non  ☐ Oui

**Système gastro-intestinal:**
- e) De la maladie de Crohn ou d'une colite ulcéreuse?  
  ☐ Non  ☐ Oui

**Système musculosquelettique:**
- f) De l'arthrite rhumatoïde?  
  ☐ Non  ☐ Oui

**Système génito-urinaire:**
- g) D'une maladie rénale chronique ou d'une maladie polykystique des reins, ou avez-vous subi(e) une dialyse?  
  ☐ Non  ☐ Oui

#### Question 11 - Dernières 5 Années (Diagnostic, Hospitalisation ou Traitements)

**Au cours des 5 dernières années, avez-vous reçu un diagnostic, été hospitalisé(e) ou subi(e) des traitements (y compris un traitement avec des médicaments prescrits) en raison:**

**Système immunitaire:**
- a) De la sclérodermie, de la morphée, du syndrome CREST ou Lupus érythémateux disséminé (LED)?  
  ☐ Non  ☐ Oui

**Système nerveux et santé mentale:**
- b) De la maladie de Parkinson, de la schizophrénie, d'un trouble schizo-affectif ou d'une psychose?  
  ☐ Non  ☐ Oui

**Cancer:**
- c) De la leucémie, d'un cancer, d'un lymphome ou d'un mélanome? *(Vous n'avez pas besoin de nous indiquer la présence de carcinome basocellulaire)*  
  ☐ Non  ☐ Oui

- d) D'une tumeur de la moelle épinière ou du cerveau?  
  ☐ Non  ☐ Oui

#### Question 12 - Dernières 2 Années (Changements de Médication)

**Au cours des 2 dernières années, avez-vous été prescrit un nouveau médicament, reçu une augmentation de la dose d'un médicament ou arrêté la prise d'un médicament pour l'arythmie (rythme cardiaque irrégulier), l'arthrite rhumatoïde, la maladie de Crohn, la colite ulcéreuse, l'épilepsie, la sclérose en plaques ou les troubles bipolaires?**

☐ Non  ☐ Oui

#### Question 13 - Dernières 2 Années (Hospitalisation Respiratoire)

**Au cours des 2 dernières années, avez-vous été hospitalisé(e) en raison d'une maladie pulmonaire obstructive chronique (MPOC) ou d'un emphysème?**

☐ Non  ☐ Oui

#### Question 14 - Derniers 12 Mois (Corticostéroïdes)

**Au cours des 12 derniers mois, avez-vous été prescrit(e) de la Prednisone orale ou un autre corticostéroïde oral pour un trouble respiratoire quelconque (tel que, sans s'y limiter, l'asthme, la pneumonie, la tuberculose, une bronchite aiguë et chronique, une maladie pulmonaire obstructive chronique (MPOC), un emphysème, une bronchiectasie, des troubles respiratoires professionnels, une embolie pulmonaire ou une sarcoïdose pulmonaire)?**

*La Prednisone orale ou tout autre corticostéroïde oral n'inclut pas les inhalateurs qui peuvent contenir de la prednisone ou un autre corticostéroïde.*

☐ Non  ☐ Oui

#### Question 15 - Antécédents Familiaux (Pour assurés de 50 ans ou moins)

**Y a-t-il quelqu'un parmi votre famille biologique (père, mère, frère, sœur) ayant reçu un diagnostic de chorée de Huntington ou de maladie polykystique des reins et pour laquelle vous n'avez pas fait l'objet d'une investigation pour ces maladies?**

☐ Non  ☐ Oui  ☐ N/A (Plus de 50 ans)

#### Question 16 - Dernières 3 Années (Substances et Activités Illégales)

**Au cours des 3 dernières années, avez-vous:**

a) Consommé du cannabis (comme la marijuana ou le haschisch) plus de 10 fois par semaine?  
☐ Non  ☐ Oui

b) Consommé d'autres drogues ou médicaments sur ordonnance qui ne vous ont pas été prescrits tels que la cocaïne, le LSD, les amphétamines, les hallucinogènes, les narcotiques, les barbituriques ou les stéroïdes anabolisants? *(Vous n'avez pas besoin de nous indiquer les médicaments obtenus en vente libre)*  
☐ Non  ☐ Oui

c) Été conseillé(e) par un professionnel de la santé de cesser ou de réduire votre consommation d'alcool ou de drogues, ou avez-vous reçu des conseils ou des traitements (y compris un traitement avec des médicaments prescrits) pour abus d'alcool ou de drogues?  
☐ Non  ☐ Oui

d) Été incarcéré(e), placé(e) en détention à domicile, en probation ou reconnu(e) coupable d'un acte criminel ou êtes-vous présentement accusé(e) d'un acte criminel pour lequel aucun verdict n'a encore été rendu?  
☐ Non  ☐ Oui

e) Été accusé(e) ou condamné(e) d'une infraction pour conduite sous l'effet de l'alcool ou la drogue ou refusé de vous soumettre à un alcootest?  
☐ Non  ☐ Oui

#### Question 17 - Permis de Conduire

**Votre permis de conduire est-il présentement suspendu ou révoqué à la suite d'infractions au code de la route?**

☐ Non  ☐ Oui

#### Question 18 - Sports et Activités Dangereuses

**Au cours des 12 prochains mois, prévoyez-vous ou envisagez-vous de pratiquer une activité ou un sport dangereux ou d'effectuer des envolées aériennes autres qu'en tant que passager payant, pilote commercial ou membre d'équipage d'un vol commercial?**

☐ Non  ☐ Oui

#### Question 19 - Voyages Internationaux

**Au cours des 12 prochains mois, prévoyez-vous ou envisagez-vous de voyager en dehors de l'Amérique du Nord, des Caraïbes (à l'exception d'Haïti) ou de l'Europe de l'Ouest pendant plus de 12 semaines consécutives?**

☐ Non  ☐ Oui

---

### Protection Or - 13 Questions

**Si vous avez répondu « NON » aux 13 questions ci-dessous, vous êtes éligible pour la Protection Or Vie Entière ou la Protection Or Temporaire.**

#### Question 1 - Taille et Poids

**Votre poids dépasse-t-il celui correspondant à votre taille dans le tableau suivant?**

**Taille de l'assuré:** _______ pi _______ po / _______ cm  
**Poids de l'assuré:** _______ lb / _______ kg

| Taille (pi/po) | Taille (cm) | Poids Max (lb) | Poids Max (kg) | Taille (pi/po) | Taille (cm) | Poids Max (lb) | Poids Max (kg) | Taille (pi/po) | Taille (cm) | Poids Max (lb) | Poids Max (kg) |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 4' 10" | 147 | 206 | 93 | 5' 6" | 168 | 264 | 120 | 6' 2" | 188 | 330 | 150 |
| 4' 11" | 150 | 213 | 97 | 5' 7" | 170 | 272 | 123 | 6' 3" | 191 | 339 | 154 |
| 5' 0" | 152 | 220 | 100 | 5' 8" | 173 | 280 | 127 | 6' 4" | 193 | 348 | 158 |
| 5' 1" | 155 | 227 | 103 | 5' 9" | 175 | 288 | 131 | 6' 5" | 196 | 357 | 162 |
| 5' 2" | 157 | 234 | 106 | 5' 10" | 178 | 296 | 134 | 6' 6" | 198 | 366 | 166 |
| 5' 3" | 160 | 241 | 109 | 5' 11" | 180 | 304 | 138 | 6' 7" | 201 | 375 | 170 |
| 5' 4" | 163 | 248 | 112 | 6' 0" | 183 | 312 | 142 | 6' 8" | 203 | 384 | 174 |
| 5' 5" | 165 | 256 | 116 | 6' 1" | 185 | 321 | 146 | 6' 9" | 206 | 393 | 178 |

☐ Non  ☐ Oui

#### Questions 2-13

*(Questions similaires à Protection Platine, mais en nombre réduit - se référer au formulaire complet pour les détails)*

**Résumé des questions Protection Or:**
1. Taille et poids
2. Hospitalisation actuelle
3. Perte de poids (12 mois)
4. Chirurgie bariatrique (6 mois)
5. Signes et symptômes médicaux
6. Maladie terminale
7. Diagnostics graves (HIV, Alzheimer, insuffisance cardiaque, cirrhose, fibrose kystique, dystrophie musculaire)
8. Diabète avec complications (3 dernières années)
9. 5 dernières années (greffe d'organes, cardiomyopathie, hépatite, oxygène)
10. 3 dernières années (angine, crise cardiaque, AVC, maladie rénale)
11. 3 dernières années (cancer, leucémie, lymphome, mélanome)
12. 12 derniers mois (hospitalisation MPOC/emphysème, corticostéroïdes oraux)
13. 2 dernières années (consommation de drogues/alcool)

---

### Protection Argent - 9 Questions

**Si vous avez répondu « NON » aux 9 questions ci-dessous, vous êtes éligible pour la Protection Argent.**

#### Question 1 - Taille et Poids

**Votre poids dépasse-t-il celui correspondant à votre taille dans le tableau suivant?**

**Taille de l'assuré:** _______ pi _______ po / _______ cm  
**Poids de l'assuré:** _______ lb / _______ kg

| Taille (pi/po) | Taille (cm) | Poids Max (lb) | Poids Max (kg) | Taille (pi/po) | Taille (cm) | Poids Max (lb) | Poids Max (kg) | Taille (pi/po) | Taille (cm) | Poids Max (lb) | Poids Max (kg) |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 4' 10" | 147 | 236 | 107 | 5' 6" | 168 | 303 | 137 | 6' 2" | 188 | 379 | 172 |
| 4' 11" | 150 | 244 | 110 | 5' 7" | 170 | 312 | 142 | 6' 3" | 191 | 389 | 176 |
| 5' 0" | 152 | 252 | 114 | 5' 8" | 173 | 321 | 146 | 6' 4" | 193 | 399 | 181 |
| 5' 1" | 155 | 260 | 118 | 5' 9" | 175 | 330 | 150 | 6' 5" | 196 | 409 | 186 |
| 5' 2" | 157 | 268 | 122 | 5' 10" | 178 | 339 | 154 | 6' 6" | 198 | 419 | 190 |
| 5' 3" | 160 | 276 | 125 | 5' 11" | 180 | 349 | 158 | 6' 7" | 201 | 429 | 195 |
| 5' 4" | 163 | 285 | 129 | 6' 0" | 183 | 359 | 163 | 6' 8" | 203 | 439 | 199 |
| 5' 5" | 165 | 294 | 133 | 6' 1" | 185 | 369 | 167 | 6' 9" | 206 | 449 | 204 |

☐ Non  ☐ Oui

#### Questions 2-9

**Résumé des questions Protection Argent:**
1. Taille et poids
2. Hospitalisation actuelle
3. Signes et symptômes médicaux
4. Maladie terminale
5. Diagnostics graves (HIV, Alzheimer, insuffisance cardiaque, fibrose kystique, dystrophie musculaire)
6. 5 dernières années (greffe d'organes, cardiomyopathie)
7. 2 dernières années (angine, crise cardiaque, AVC, maladie rénale)
8. 2 dernières années (cancer, leucémie, lymphome, mélanome)
9. 12 derniers mois (traitement abus d'alcool ou drogues)

---

### Protection Bronze - Émission Garantie

**Il s'agit d'un produit à émission garantie.**

✅ **Aucune déclaration d'assurabilité n'est requise pour la Protection Bronze.**

**Important:** Veuillez vous assurer que toutes les informations sont remplies et que les directives du produit sont respectées.

---

## Section 8 - Prime et Mode de Paiement

### Mode de Paiement

**Indiquez la prime totale du contrat selon le mode de paiement de la prime:***

| Mode de Paiement | Prime | Sélection |
|---|---|---|
| **Mensuel** (Voir section 9) | _______ $ | ☐ |
| **Annuel** | _______ $ | ☐ |
| **Semestriel** | _______ $ | ☐ |
| **Trimestriel** | _______ $ | ☐ |

*Les primes d'assurance peuvent être assujetties à la taxe de vente provinciale (TVP)

### Paiement Initial

**(a) Somme versée avec la proposition:** _____________ $

### Payeur

**(b) Payeur:**

| Payeur | Sélection |
|---|---|
| ☐ Personne à assurer | |
| ☐ Propriétaire (autre tel que précisé dans la section 2) | |
| ☐ Autre (remplir ci-dessous) | |

**Si autre, précisez:**

| Champ | Information |
|---|---|
| **Nom** | _________________ |
| **Adresse** | _________________ |

---

## Section 9 - Accord de Débit Préautorisé (DPA)

**SEULEMENT SI DPA A ÉTÉ CHOISI DANS LA PROPOSITION**

### Information Bancaire

**Si l'information bancaire n'a pas été fournie dans la proposition, prière de joindre un chèque avec la mention « NUL ».**

Remplissez seulement si un spécimen de chèque n'est pas disponible, si le chèque n'est pas préimprimé ou s'il s'agit d'un compte d'épargne.

| Champ | Information |
|---|---|
| **Nom de l'institution financière** | _________________ |
| **Adresse** | _________________ |
| **Numéro de succursale** | _____ - _____ - _____ |
| **Numéro de l'institution financière** | _____ - _____ - _____ |
| **Numéro de compte** | _________________ |

### Type de Service

| Type | Sélection |
|---|---|
| ☐ **Personnel** - Si les fonds sont prélevés sur un compte bancaire personnel | |
| ☐ **Entreprise** - Si les fonds sont prélevés sur un compte bancaire d'entreprise | |

### Caractéristiques des Débits

**Cet accord de débit préautorisé est un accord variable.**

**Autorisations:**
- J'autorise Assomption Vie à débuter, en tout temps, les prélèvements réguliers sur mon compte selon mes instructions telles qu'indiquées dans la proposition
- Si un débit préautorisé est retourné dû à une insuffisance de provisions au compte, Assomption Vie prélèvera du même compte bancaire, sans préavis, des frais de **25 $**

**Date de prélèvement:**
- J'accepte que mon compte soit débité le **_______ jour du mois** (1er au 28e jour du mois) ou le jour ouvrable suivant (sujet à modification)

**Note:** Le premier retrait au compte bancaire sera effectué le premier jour ouvrable suivant la date d'émission de la police et selon le délai de votre institution financière. La date de retrait suivante respectera l'entente de DPA. Notez que deux primes pourraient alors être prises dans le même mois.

**Couverture provisoire:**
- J'accepte que le premier DPA soit effectué dès la signature des présentes si toutes les conditions préalables de la note de couverture d'assurance provisoire conditionnelle sont remplies
- ☐ Cochez si vous refusez

### Renonciation

Je renonce au droit de recevoir un avis de 10 jours dans le cas d'une augmentation ou diminution du montant du débit préautorisé ou d'un changement de la date du débit.

### Annulation

**Annulation par Assomption Vie:**
Assomption Vie annulera cet accord de débit préautorisé sur réception d'un avis écrit d'annulation d'au moins 10 jours avant la date d'annulation demandée.

**Vos droits:**
Contactez votre institution financière à propos de vos droits concernant l'annulation d'un DPA. (Un formulaire d'annulation standard est disponible à <www.cdnpay.ca>)

**Mode de paiement:**
L'annulation de cet accord de débit préautorisé n'affectera en aucune façon l'accord en vigueur entre vous et Assomption Vie pourvu que le paiement soit soumis d'une autre manière.

### Recours et Remboursement

Vous avez certains droits de recours si un débit n'est pas conforme au présent accord. Par exemple, vous avez le droit de recevoir le remboursement de tout débit qui n'est pas autorisé ou qui n'est pas compatible avec le présent Accord de DPA.

**Pour obtenir plus d'information sur vos droits de recours:**
- Communiquez avec votre institution financière
- Visitez <www.cdnpay.ca>

### Droits Exclusifs

Tous les montants transférés du compte préautorisé pour le paiement des primes sont pour le bénéfice exclusif du propriétaire de la police d'assurance.

**Note:** Assomption Vie n'augmentera pas votre débit préautorisé et ne changera pas votre date de débit après l'entrée en vigueur de votre contrat sans vous en aviser.

---

## Section 10 - Directives Spéciales

**Espace pour notes ou directives spéciales:**

_______________________________________________________________________________

_______________________________________________________________________________

_______________________________________________________________________________

_______________________________________________________________________________

_______________________________________________________________________________

---

## Message Important au Représentant

### Responsabilités du Représentant

**Veuillez vous assurer d'avoir:**

✅ Remis et expliqué au client un formulaire **Déclaration de l'agent** exposant:
   - Votre méthode de rémunération et autres avantages financiers
   - Le nom des assureurs que vous représentez
   - Tout conflit d'intérêt

✅ Dûment vérifié la date de naissance de toute personne à assurer

✅ Expliqué les questions apparaissant dans ce formulaire à tout propriétaire et personne à assurer

### Identification du Représentant

**Nom du représentant (agent/conseiller) en lettres moulées:**

_______________________________________________________________________________

**Signature:** _______________________________________________________________________________

**Date:** _____ / _____ / _________

---

## Glossaire des Termes

| Terme | Définition |
|---|---|
| **Assurance vie simplifiée** | Assurance vie avec processus de souscription simplifié, généralement basé sur un questionnaire médical sans examen médical |
| **Couverture immédiate** | Assurance qui entre en vigueur dès l'émission de la police sans période d'attente |
| **Couverture différée** | Assurance où la pleine couverture n'est disponible qu'après une période d'attente |
| **Couverture différée progressive** | Assurance où le montant de couverture augmente graduellement pendant les premières années |
| **Émission garantie** | Produit d'assurance accepté sans questions médicales ni examen |
| **Protection Platine** | Niveau de couverture le plus élevé chez Assomption Vie (19 questions) |
| **Protection Or** | Niveau de couverture intermédiaire chez Assomption Vie (13 questions) |
| **Protection Argent** | Niveau de couverture avec souscription simplifiée (9 questions) |
| **Protection Bronze** | Produit à émission garantie sans questions médicales |
| **FRAC** | Franchise d'assurance invalidité et cotisation (avenant) |
| **MA** | Majoration assurée (avenant permettant d'augmenter la couverture) |
| **BAE** | Bénéfice anticipé pour maladie en phase terminale (avenant) |
| **DPA** | Débit préautorisé (prélèvement automatique bancaire) |
| **Lia** | Application électronique d'Assomption Vie pour la saisie de données |
| **Bénéficiaire révocable** | Bénéficiaire qui peut être changé sans son consentement |
| **Bénéficiaire irrévocable** | Bénéficiaire qui ne peut être changé sans son consentement |
| **Bénéficiaire en sous-ordre** | Bénéficiaire qui reçoit les prestations si tous les bénéficiaires primaires sont décédés |
| **Capital assuré** | Montant d'assurance vie payable au décès |
| **Prime** | Paiement périodique pour maintenir la couverture d'assurance |
| **Assurabilité** | Admissibilité d'une personne à obtenir une assurance vie basée sur son état de santé |

---

## Tableau Comparatif des Produits

| Produit | Type de Couverture | Âge Min-Max | Capital Min | Capital Max | Questions d'Assurabilité |
|---|---|---|---|---|---|
| **Protection Platine VE** | Immédiate | 18-85 | 10 000 $ | 750 000 $ | 19 questions |
| **Protection Or VE** | Immédiate | 18-85 | 5 000 $ | 250 000 $ | 13 questions |
| **Protection Argent** | Différée progressive | 18-85 | 5 000 $ | 50 000 $ | 9 questions |
| **Protection Bronze** | Différée | 18-80 | 5 000 $ | 50 000 $ | Aucune (émission garantie) |
| **Protection Platine T** | Immédiate | 18-75 | 25 000 $ | 750 000 $ | 19 questions |
| **Protection Or T** | Immédiate | 18-70 | 25 000 $ | 250 000 $ | 13 questions |

**Légende:** VE = Vie Entière, T = Temporaire

---

## Informations de Contact

### Assomption Vie

**Site web:** <https://www.assomption.ca>

**Centre d'appel:** 1-800-455-7337

**Adresse postale:**  
C.P. 160  
770, rue Main  
Moncton (N.-B.) E1C 8L1

**Département:**
- Assurance individuelle
- Assurance collective
- Placements et retraite

---

## Notes Juridiques

Ce formulaire de collecte de données est la propriété d'Assomption Vie et est destiné uniquement à la saisie d'informations dans l'application électronique Lia.

**Important:** Ce document N'EST PAS une proposition d'assurance. Il ne doit pas être soumis comme tel.

Les informations recueillies sont confidentielles et protégées conformément aux lois sur la protection des renseignements personnels.

**Dernière mise à jour:** Référez-vous à la version la plus récente de ce formulaire pour les informations les plus actuelles.
