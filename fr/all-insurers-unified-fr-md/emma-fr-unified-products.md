---
# ═══════════════════════════════════════════════════════════════════════
# UNIFIED INSURER DOCUMENT
# ═══════════════════════════════════════════════════════════════════════

# Document Metadata
document_id: "emma-fr-unified-products-v1.0"
document_type: unified_insurer_guide
schema_version: "3.0"
version: 1.0
document_title: "Guide Unifié des Produits - Emma"
last_updated: "2025-12-29"
effective_date: "2024-01-01"
language: fr-CA
region: QC

# ═══════════════════════════════════════════════════════════════════════
# INSURER PROFILE
# ═══════════════════════════════════════════════════════════════════════
insurer:
  id: "Emma (Humania)"
  name: "Humania Assurance Inc."
  legal_name: "Humania Assurance Inc."
  address: "1555, rue Girouard Ouest, Saint-Hyacinthe (Québec) J2S 2Z6"
  amf_number: "2000737703"
  complaints_url: "https://www.humania.ca/formuler-plainte"

distributor:
  id: "emma"
  name: "Emma Services financiers Inc."
  legal_name: "Emma Services financiers Inc."
  address: "7900-300, Boul Pierre-Bertrand, Québec (QC) G2J 0C5"
  amf_number: "603236"
  specimen_url: "https://emma.ca/specimen-de-police"

# ═══════════════════════════════════════════════════════════════════════
# PRODUCTS CATALOG
# ═══════════════════════════════════════════════════════════════════════
products:
  # ─────────────────────────────────────────────────────────────────────
  # PRODUCT 1: Emma T100
  # ─────────────────────────────────────────────────────────────────────
  - id: "emma-t100"
    name: "Emma T100"
    name_en: "Emma T100 Permanent Life Insurance"
    category: "permanent_life_insurance"
    underwriting_type: "full"
    status: "active"
    
    audience:
      primary:
        - insurance_advisors
        - agents
        - underwriters
      secondary:
        - clients
        - financial_planners
    
    use_cases:
      - "Long-term estate planning"
      - "Final expense coverage"
      - "Wealth transfer"
      - "Business succession"
    
    eligibility:
      age_range: [18, 80]
      residency: "Canadian permanent resident or citizen"
      citizenship_required: false
      language_requirement: "French or English"
      occupation_restrictions: []
      
    coverage:
      min_amount: 1000
      max_amount: 5000000
      currency: CAD
      
    premium_options:
      - id: "to-100"
        name: "Jusqu'à 100 ans"
        description: "Primes payables jusqu'à 100 ans (paiement viager)"
      - id: "to-65"
        name: "Jusqu'à 65 ans"
        description: "Primes payables jusqu'à 65 ans"
      - id: "20-years"
        name: "Durant 20 ans"
        description: "Primes payables pendant 20 ans"
    
    features:
      renewable: false
      convertible: false
      cash_value: false
      participating: false
    
    exclusions:
      standard:
        - type: "suicide"
          period_years: 2
          description: "Suicide dans les 2 premières années"
        - type: "misrepresentation"
          description: "Fausse déclaration entraînant nullité du contrat"
        - type: "criminal_act"
          description: "Décès résultant d'un acte criminel"
      dangerous_activities:
        - "Alpinisme"
        - "Escalade de glace"
        - "Plongée sous-marine (hors centre de vacances)"
        - "Parapente"
        - "Paravoile"
        - "Deltaplane"
        - "Parachutisme"
        - "Saut à l'élastique"
        - "Héli-ski"
        - "Ski hors-piste"
        - "Motoneige hors-piste"
        - "Aviation (sauf pilotes commerciaux)"
        - "Course automobile"
        - "Kitesurf"
    
    claims:
      notice_period_days: 30
      documents_deadline_days: 90
    
    cancellation:
      free_period_days: 15
      alternative_period_days: 60
      fees_after_period: true
    
    source_documents:
      - document_id: "emma-fr-sommaire-produit-assurance-vie.mdx"
        type: "product_summary"
      - document_id: "emma-fr-specimen-de-contrat.mdx"
        type: "specimen_contract"
    
    tags:
      - assurance-vie-permanente
      - t100
      - emma

  # ─────────────────────────────────────────────────────────────────────
  # PRODUCT 2: Emma Temporaire
  # ─────────────────────────────────────────────────────────────────────
  - id: "emma-term"
    name: "Emma Temporaire"
    name_en: "Emma Term Life Insurance"
    category: "term_life_insurance"
    underwriting_type: "full"
    status: "active"
    
    audience:
      primary:
        - insurance_advisors
        - agents
        - underwriters
      secondary:
        - clients
        - financial_planners
    
    use_cases:
      - "Income replacement"
      - "Mortgage protection"
      - "Debt coverage"
      - "Family protection during working years"
    
    eligibility:
      age_range: [18, 80]
      residency: "Canadian permanent resident or citizen"
      citizenship_required: false
      language_requirement: "French or English"
      occupation_restrictions: []
      
    coverage:
      min_amount: 50000
      max_amount: 5000000
      currency: CAD
    
    term_flexibility:
      type: "pick_a_term"
      min_term: 10
      max_term: 35
      increment: 1
      description: "Le conseiller peut choisir n'importe quel terme entre T10 et T35 (ex: T11, T17, T22, T33)"
    
    features:
      renewable:
        available: true
        frequency: "annual"
        until_age: 80
        evidence_required: false
      convertible:
        available: true
        until_age: 65
        min_amount: 1000
        target_product: "Assurance vie entière sans participation"
        evidence_required: false
      exchange_right:
        available: true
        period: "1st to 5th anniversary"
        max_uses: 1
        description: "Échanger pour un terme plus long sans preuve d'assurabilité"
      cash_value: false
      participating: false
    
    exclusions:
      standard:
        - type: "suicide"
          period_years: 2
          description: "Suicide dans les 2 premières années"
        - type: "misrepresentation"
          description: "Fausse déclaration entraînant nullité du contrat"
        - type: "criminal_act"
          description: "Décès résultant d'un acte criminel"
      dangerous_activities:
        - "Alpinisme"
        - "Escalade de glace"
        - "Plongée sous-marine (hors centre de vacances)"
        - "Parapente"
        - "Paravoile"
        - "Deltaplane"
        - "Parachutisme"
        - "Saut à l'élastique"
        - "Héli-ski"
        - "Ski hors-piste"
        - "Motoneige hors-piste"
        - "Aviation (sauf pilotes commerciaux)"
        - "Course automobile"
        - "Kitesurf"
    
    source_documents:
      - document_id: "emma-fr-sommaire-produit-assurance-vie.mdx"
        type: "product_summary"
      - document_id: "emma-fr-specimen-de-contrat.mdx"
        type: "specimen_contract"
      - document_id: "emma-fr-guide-de-tarification.mdx"
        type: "underwriting_guide"
    
    tags:
      - assurance-vie-temporaire
      - renouvelable
      - transformable
      - emma
      - t10
      - t20
      - t25
      - t30
      - t35
      - assurance-temporaire

  # ─────────────────────────────────────────────────────────────────────
  # PRODUCT 3: Emma GI (Guaranteed Issue)
  # ─────────────────────────────────────────────────────────────────────
  - id: "emma-gi"
    name: "Emma GI"
    name_full: "Assurance vie temporaire 20 ans ou 100 ans Emma"
    name_en: "Emma Guaranteed Issue Life Insurance"
    category: "guaranteed_issue_life_insurance"
    underwriting_type: "guaranteed"
    status: "active"
    
    audience:
      primary:
        - insurance_advisors
        - agents
      secondary:
        - clients
        - seniors
    
    use_cases:
      - "Final expense coverage"
      - "Clients with health conditions"
      - "Simplified application process"
      - "No medical questions"
    
    variants:
      - id: "gi-t20"
        name: "Emma GI T20"
        type: "term_life"
        term_length: 20
        age_range: [18, 60]
        premium_payable_until: 80
        renewable: true
        convertible:
          available: true
          until_age: 65
          min_amount: 5000
      - id: "gi-t100"
        name: "Emma GI T100"
        type: "permanent_life"
        term_length: 100
        age_range: [18, 70]
        premium_payable_until: 100
        renewable: false
        convertible: false
    
    eligibility:
      age_range_t20: [18, 60]
      age_range_t100: [18, 70]
      residency: "Canadian permanent resident or citizen"
      medical_questions: false
      guaranteed_acceptance: true
      
    coverage:
      min_amount: 5000
      max_amount: 100000
      currency: CAD
      max_all_policies: 100000
    
    features:
      graded_benefit:
        enabled: true
        period_years: 2
        description: "Période différée de 2 ans - seul décès accidentel couvert, sinon remboursement des primes"
      renewable:
        available: true
        applies_to: "gi-t20"
        until_age: 80
      convertible:
        available: true
        applies_to: "gi-t20"
        until_age: 65
        min_amount: 5000
      cash_value: false
      participating: false
    
    exclusions:
      standard:
        - type: "suicide"
          period_years: 2
          description: "Suicide dans les 2 premières années"
        - type: "graded_death_benefit"
          period_years: 2
          description: "Période différée: décès non-accidentel = remboursement des primes uniquement"
        - type: "misrepresentation"
          description: "Fausse déclaration entraînant nullité du contrat"
        - type: "criminal_act"
          description: "Décès résultant d'un acte criminel"
      dangerous_activities:
        - "Alpinisme"
        - "Escalade de glace"
        - "Plongée sous-marine (hors centre de vacances)"
        - "Parapente"
        - "Paravoile"
        - "Deltaplane"
        - "Parachutisme"
        - "Saut à l'élastique"
        - "Héli-ski"
        - "Ski hors-piste"
        - "Motoneige hors-piste"
        - "Aviation (sauf pilotes commerciaux)"
        - "Course automobile"
        - "Kitesurf"
    
    source_documents:
      - document_id: "emma-fr-specimen-contrat-gi.md"
        type: "specimen_contract"
    
    tags:
      - assurance-vie
      - emission-garantie
      - guaranteed-issue
      - sans-questions-medicales
      - emma

  # ─────────────────────────────────────────────────────────────────────
  # RIDER 1: Avenant Personne à Charge
  # ─────────────────────────────────────────────────────────────────────
  - id: "emma-dependent-rider"
    name: "Avenant Assurance Vie pour Personne à Charge"
    name_en: "Dependent Life Insurance Rider"
    category: "rider"
    parent_products: ["emma-t100", "emma-term"]
    underwriting_type: "simplified"
    status: "active"
    
    audience:
      primary:
        - insurance_advisors
        - agents
      secondary:
        - clients
    
    use_cases:
      - "Protection for all dependent children"
      - "Automatic coverage for newborns"
      - "Future insurability guarantee"
    
    eligibility:
      dependent_definition:
        - "Under 21 years old"
        - "21-25 years old and full-time student"
        - "Significant functional disability before age 21"
      additional_criteria:
        - "Not married or common-law"
        - "Not employed full-time"
        - "Permanent address in Canada"
        - "Covered by provincial health insurance"
      coverage_starts: "15 days after birth (if discharged from hospital)"
      automatic_coverage: true
      
    coverage:
      fixed_amounts: [15000, 20000, 25000]
      currency: CAD
      max_combined: 25000
    
    features:
      convertible:
        available: true
        multiplier: 5
        description: "Transformable en 5x le montant à l'échéance"
        evidence_required: false
    
    limitations:
      pre_existing_condition_period_months: 12
      applies_to: "Enfants présents à la date d'effet"
    
    source_documents:
      - document_id: "emma-fr-sommaire-produit-assurance-vie.mdx"
        type: "product_summary"
      - document_id: "emma-fr-specimen-de-contrat.mdx"
        type: "specimen_contract"
    
    tags:
      - avenant
      - enfant-a-charge
      - emma

  # ─────────────────────────────────────────────────────────────────────
  # RIDER 2: Avenant Cancer
  # ─────────────────────────────────────────────────────────────────────
  - id: "emma-cancer-rider"
    name: "Avenant Assurance Cancer"
    name_en: "Cancer Insurance Rider"
    category: "rider"
    parent_products: ["emma-t100", "emma-term"]
    underwriting_type: "simplified"
    status: "active"
    
    audience:
      primary:
        - insurance_advisors
        - agents
      secondary:
        - clients
    
    use_cases:
      - "Lump sum payment upon cancer diagnosis"
      - "Financial support during treatment"
      - "Income replacement during recovery"
    
    eligibility:
      age_range: [18, 70]
      residency: "Canadian permanent resident or citizen"
      
    coverage:
      min_amount: 10000
      max_amount: 75000
      currency: CAD
      coverage_until_age: 80
      max_all_policies: 75000
    
    covered_conditions:
      cancer_major:
        definition: "Tumeur maligne avec prolifération anarchique de cellules"
        confirmation: "Test de pathologie requis"
        types:
          - "Carcinome"
          - "Mélanome"
          - "Leucémie"
          - "Lymphome"
          - "Sarcome"
      cancer_minor:
        payment: "One-time only"
        reduction: "Déduit du montant cancer majeur"
        types:
          - "Carcinome in situ (Tis) ou stade Ta"
          - "Mélanome ≤1mm sans ulcération"
          - "Cancer de la peau sans mélanome"
          - "Cancer prostate T1a/T1b"
          - "Cancer thyroïde papillaire/folliculaire ≤2cm stade T1"
          - "Leucémie lymphoïde chronique < stade 1 Rai"
          - "Tumeurs stromales gastro-intestinales < stade 2 AJCC"
    
    limitations:
      moratorium_period_days: 90
      survival_period_days: 30
      pre_existing_condition_period_months: 12
      pre_existing_exclusion_period_months: 24
    
    source_documents:
      - document_id: "emma-fr-sommaire-produit-assurance-vie.mdx"
        type: "product_summary"
      - document_id: "emma-fr-specimen-de-contrat.mdx"
        type: "specimen_contract"
    
    tags:
      - avenant
      - cancer
      - maladies-graves
      - emma

  # ─────────────────────────────────────────────────────────────────────
  # RIDER 3: Avenant Invalidité Totale
  # ─────────────────────────────────────────────────────────────────────
  - id: "emma-disability-rider"
    name: "Avenant Assurance Invalidité Totale"
    name_en: "Total Disability Insurance Rider"
    category: "rider"
    parent_products: ["emma-t100", "emma-term"]
    underwriting_type: "full"
    status: "active"
    
    audience:
      primary:
        - insurance_advisors
        - agents
        - underwriters
      secondary:
        - clients
    
    use_cases:
      - "Debt repayment during disability"
      - "Mortgage protection"
      - "Credit card/loan payments"
    
    eligibility:
      age_range: [18, 60]
      residency: "Canadian resident (6+ months/year)"
      employment: "Full-time (21+ hours/week, 35+ weeks/year)"
      
    coverage:
      min_monthly: 500
      max_monthly: 3000
      currency: CAD
      coverage_until_age: 65
      calculation: "Min(1.5% of life coverage, max by occupation category)"
      use_restriction: "Exclusively for eligible debt repayment"
    
    benefit_periods:
      - id: "2-years"
        name: "2 ans"
        max_payments: 60
      - id: "5-years"
        name: "5 ans"
        max_payments: 84
    
    elimination_period:
      days: 90
      retroactive_to_day: 30
    
    eligible_debts:
      included:
        - "Prêt hypothécaire"
        - "Marge de crédit hypothécaire"
        - "Prêt personnel"
        - "Prêt-auto"
        - "Carte de crédit"
        - "Marge de crédit"
        - "Bail de location (véhicule)"
        - "Taxes foncières et scolaires"
        - "Loyer résidentiel (si pas d'hypothèque, max 2 ans)"
      excluded:
        - "Prêts entre individus"
        - "Prêts commerciaux"
        - "Créances contractées pendant l'invalidité"
        - "Créances contractées dans les 90 jours avant l'invalidité"
        - "Créances couvertes par autre assurance invalidité"
    
    presumption_of_disability:
      conditions:
        - "Perte totale et permanente de deux membres"
        - "Perte totale de l'usage des deux mains ou pieds"
        - "Perte totale et irréversible de l'ouïe (≥90 dB)"
        - "Perte totale de la vue (acuité ≤20/200 ou champ <20°)"
    
    exclusions:
      - "Tentative de suicide ou automutilation"
      - "Acte illégal ou criminel"
      - "Conduite sous influence (alcool/drogue)"
      - "Toxicomanie ou abus d'alcool"
      - "Service dans forces armées"
      - "Voyage aérien non commercial"
      - "Chirurgie esthétique ou élective"
      - "Traitements expérimentaux"
      - "Grossesse (sauf complication pathologique)"
      - "Incarcération"
    
    restrictions:
      bankruptcy: "Prestations cessent en cas de faillite pendant invalidité"
      treatment_refusal: "Suspension possible si refus de traitement"
    
    recurrence_rules:
      categories_B_1A_2A:
        recovery_period_months: 6
        description: "Nouvelle invalidité si rétabli 6+ mois"
      categories_3A_4A:
        recovery_period_months: 12
        description: "Nouvelle invalidité si rétabli 12+ mois"
    
    death_benefit:
      amount: "5x monthly benefit"
      max: 10000
      condition: "Si décès pendant période d'invalidité"
    
    source_documents:
      - document_id: "emma-fr-sommaire-produit-assurance-vie.mdx"
        type: "product_summary"
      - document_id: "emma-fr-specimen-de-contrat.mdx"
        type: "specimen_contract"
    
    tags:
      - avenant
      - invalidite
      - dette
      - salaire
      - emma

# ═══════════════════════════════════════════════════════════════════════
# UNDERWRITING REQUIREMENTS
# ═══════════════════════════════════════════════════════════════════════
underwriting:
  mib_verification: true
  fast_decision_available: true
  electronic_application: true
  
  requirements_matrix:
    legend:
      P: "Proposition"
      PS: "Profil sanguin"
      MU: "Analyse d'urine"
      SV: "Signes vitaux (taille/poids, tension artérielle)"
      RMT: "Rapport du médecin traitant"
      ECG: "Électrocardiogramme"
    
    by_amount_and_age:
      - amount_range: [0, 500000]
        age_18_40: ["P"]
        age_41_50: ["P"]
        age_51_55: ["P"]
        age_56_60: ["P"]
        age_61_plus: ["P"]
      - amount_range: [500001, 1000000]
        age_18_40: ["P"]
        age_41_50: ["P"]
        age_51_55: ["P"]
        age_56_60: ["P"]
        age_61_plus: ["PS", "MU", "SV"]
      - amount_range: [1000001, 1500000]
        age_18_40: ["P"]
        age_41_50: ["P"]
        age_51_55: ["PS", "MU", "SV"]
        age_56_60: ["PS", "MU", "SV"]
        age_61_plus: ["PS", "MU", "SV"]
      - amount_range: [1500001, 2000000]
        age_18_40: ["P"]
        age_41_50: ["P"]
        age_51_55: ["PS", "MU", "SV"]
        age_56_60: ["PS", "MU", "SV"]
        age_61_plus: ["PS", "MU", "SV", "RMT", "ECG"]
      - amount_range: [2000001, 3000000]
        age_18_40: ["PS", "MU", "SV"]
        age_41_50: ["PS", "MU", "SV"]
        age_51_55: ["PS", "MU", "SV"]
        age_56_60: ["PS", "MU", "SV", "RMT"]
        age_61_plus: ["PS", "MU", "SV", "RMT", "ECG"]
      - amount_range: [3000001, 4000000]
        age_18_40: ["PS", "MU", "SV"]
        age_41_50: ["PS", "MU", "SV"]
        age_51_55: ["PS", "MU", "SV", "RMT"]
        age_56_60: ["PS", "MU", "SV", "RMT"]
        age_61_plus: ["PS", "MU", "SV", "RMT", "ECG"]
      - amount_range: [4000001, 5000000]
        age_18_40: ["PS", "MU", "SV"]
        age_41_50: ["PS", "MU", "SV"]
        age_51_55: ["PS", "MU", "SV", "RMT"]
        age_56_60: ["PS", "MU", "SV", "RMT"]
        age_61_plus: ["PS", "MU", "SV", "RMT", "ECG"]
  
  decision_types:
    - id: "standard"
      name: "Accepté Standard"
      description: "Police émise aux taux standards sans surprime"
    - id: "rated"
      name: "Accepté avec Surprime"
      description: "Police émise avec surprime permanente ou temporaire"
    - id: "deferred"
      name: "Différé"
      description: "Reconsidération future possible selon conditions"
    - id: "declined"
      name: "Refus"
      description: "Aucune offre ne peut être faite"
  
  smoker_definition: "N'a pas fait usage de tabac (cigarettes, vapoteuses, e-cigarettes, produits de nicotine, cigarillos, petits cigares, ou plus de 12 gros cigares) dans les 12 derniers mois"

# ═══════════════════════════════════════════════════════════════════════
# INELIGIBILITY CRITERIA
# ═══════════════════════════════════════════════════════════════════════
ineligibility:
  automatic_decline:
    - "En investigation médicale présentement"
    - "Condamné pour conduite avec facultés affaiblies dans la dernière année"
    - "Véhicule équipé d'un antidémarreur éthylométrique"
    - "En attente d'une décision de la cour"
    - "A reçu une sentence dans les deux dernières années"
    - "En période de probation"
    - "Porteur du VIH"
  
  prohibited_drugs:
    - "Stéroïdes anabolisants"
    - "Barbituriques"
    - "Héroïne"
    - "Morphine"
    - "Opium"
    - "Demerol"
    - "Codéine"
    - "Amphétamines (speed)"
    - "Cocaïne"
    - "Fentanyl"
    - "Ecstasy"
    - "LSD"
    - "DMT"
    - "Hallucinogènes"
    - "Méthadone"

# ═══════════════════════════════════════════════════════════════════════
# MEDICAL CONDITIONS SUMMARY
# ═══════════════════════════════════════════════════════════════════════
medical_conditions:
  total_conditions: 47
  categories:
    cardiovascular:
      count: 4
      conditions:
        - name: "AIT/AVC"
          standard_possible: false
          typical_rating: "+50% to +150%"
          decline_triggers: ["<40 years", "Smoker", "Diabetic", "Multiple AVC"]
        - name: "Coronopathie/Infarctus"
          standard_possible: false
          typical_rating: "+125% to +275%"
          decline_triggers: ["Multiple infarcts", "Smoker", "<40 at diagnosis"]
        - name: "Fibrillation Auriculaire"
          standard_possible: true
          conditions: "After 60, no underlying cause, investigation normal"
        - name: "Hypertension"
          standard_possible: true
          conditions: "Well controlled, BP within normal limits"
    
    respiratory:
      count: 2
      conditions:
        - name: "Apnée du Sommeil"
          standard_possible: true
          conditions: "Treated, compliant, obstructive type"
          decline_triggers: ["Central apnea", "Untreated"]
        - name: "MPOC/Emphysème"
          standard_possible: false
          typical_rating: "+50% to +100%"
          decline_triggers: ["Severe", "Smoker"]
    
    metabolic:
      count: 2
      conditions:
        - name: "Diabète"
          standard_possible: true
          conditions: "Type 2, age 56+, well controlled"
          typical_rating: "+50% to decline"
        - name: "Hypercholestérolémie"
          standard_possible: true
          conditions: "Well controlled"
    
    cancer:
      count: 9
      standard_possible: ["Basal cell carcinoma"]
      typically_rated: ["Thyroid", "Prostate (depending on stage)", "Breast (in situ)", "Colon"]
      typically_declined: ["Lung (stage 2+)", "Blood cancers", "Recurrent"]
    
    mental_health:
      count: 4
      conditions:
        - name: "Anxiety"
          standard_possible: true
          conditions: "No complications"
        - name: "Depression"
          typical_rating: "+50% to +100%"
          deferral: "If currently disabled"
        - name: "Bipolar"
          typical_rating: "+50% to +150%"
          deferral: "12 months post-diagnosis"
        - name: "Schizophrenia"
          typical_rating: "+100% to +300%"
          deferral: "12 months post-episode"

# ═══════════════════════════════════════════════════════════════════════
# GENERAL POLICY PROVISIONS
# ═══════════════════════════════════════════════════════════════════════
general_provisions:
  grace_period_days: 30
  incontestability_period_years: 2
  suicide_exclusion_years: 2
  reinstatement_period_years: 2
  reinstatement_quick_days: 90
  minimum_refund_amount: 20
  currency: "CAD"
  participating: false
  cash_value: false
  termination_age: 80

# ═══════════════════════════════════════════════════════════════════════
# CONSUMER RIGHTS
# ═══════════════════════════════════════════════════════════════════════
consumer_rights:
  cancellation:
    legal_minimum_days: 10
    extended_period_days: 15
    alternative_period_days: 60
    fees_after_period: true
  
  freedom_of_choice:
    - "Not obligated to buy from designated provider"
    - "Free to choose product and insurer"
  
  distributor_disclosure:
    compensation_threshold_percent: 30
    disclosure_required: true

# ═══════════════════════════════════════════════════════════════════════
# REGULATORY COMPLIANCE
# ═══════════════════════════════════════════════════════════════════════
regulatory:
  authority: "AMF"
  authority_full_name: "Autorité des marchés financiers"
  authority_phone: "1-877-525-0337"
  authority_url: "https://www.lautorite.qc.ca"
  jurisdiction: "Quebec Insurance Act"

# ═══════════════════════════════════════════════════════════════════════
# DOCUMENT STATISTICS
# ═══════════════════════════════════════════════════════════════════════
statistics:
  total_products: 6
  main_products: 3
  riders: 3
  product_categories:
    permanent_life: 1
    term_life: 1
    guaranteed_issue: 1
    cancer_rider: 1
    disability_rider: 1
    dependent_rider: 1
  coverage_range:
    min: 1000
    max: 5000000
    currency: "CAD"
  age_ranges:
    main_products: [18, 80]
    emma_gi_t20: [18, 60]
    emma_gi_t100: [18, 70]
    cancer_rider: [18, 70]
    disability_rider: [18, 60]
  medical_conditions_documented: 47
  non_medical_conditions_documented: 8
  health_questionnaire_questions: 32

# ═══════════════════════════════════════════════════════════════════════
# HEALTH QUESTIONNAIRE
# ═══════════════════════════════════════════════════════════════════════
health_questionnaire:
  total_questions: 32
  language: "bilingual_fr_en"
  structure:
    section_a:
      name: "Basic Eligibility / Admissibilité de base"
      coverage_range: "5,000$ - 100,000$ (GI)"
      questions: 6
      purpose: "Guaranteed Issue eligibility screening"
    section_b:
      name: "Full Underwriting / Souscription complète"
      coverage_range: "5,000$ - 5,000,000$"
      fasttrack_limit: "750,000$"
      questions: 24
      sub_questions: 15
      purpose: "Complete medical and lifestyle assessment"
  decision_outcomes:
    - "ACCEPTED - Standard rates"
    - "ACCEPTED - Smoker rates"
    - "ACCEPTED - FastTrack (auto-decision up to 750K)"
    - "ACCEPTED - Manual underwriting required"
    - "DECLINED - GI offer only (T10, T20, T100 max 100K)"
    - "DECLINED - End of questionnaire"
    - "ADDITIONAL QUESTIONNAIRE - Further assessment needed"
  categories:
    - citizenship_residency
    - province_territory
    - age_eligibility
    - sex_at_birth
    - tobacco_use
    - terminal_illness
    - pregnancy
    - build_measurements_bmi
    - criminal_history
    - immune_system
    - epilepsy_seizures
    - drug_use_non_prescribed
    - alcohol_drug_treatment
    - gastrointestinal
    - cannabis_frequency
    - cardiovascular
    - diabetes
    - sleep_apnea
    - mental_health_mild
    - mental_health_severe
    - weight_loss
    - employment_status
    - high_risk_occupations
    - family_history_hereditary
    - family_history_multiple
    - unconsulted_symptoms
    - pending_investigations
    - endocrine_disorders
    - cancer_tumors
    - respiratory
    - neurological_muscular
    - multiple_sclerosis
    - other_neurological
    - genitourinary
    - arthritic_disorders
    - travel_plans

# ═══════════════════════════════════════════════════════════════════════
# SOURCE DOCUMENTS
# ═══════════════════════════════════════════════════════════════════════
source_documents:
  - id: "emma-fr-guide-de-tarification.mdx"
    type: "underwriting_guide"
    description: "Guide de tarification et présélection complet"
  - id: "emma-fr-sommaire-produit-assurance-vie.mdx"
    type: "product_summary"
    description: "Sommaire des produits avec droits du consommateur"
  - id: "emma-fr-specimen-de-contrat.mdx"
    type: "specimen_contract"
    description: "Spécimen de police avec termes et conditions"
  - id: "Questionnaire EMMA V2_EN & FR_20-06-2025_FD&Humania 02-09-2025.docx"
    type: "health_questionnaire"
    description: "Questionnaire de santé et d'admissibilité bilingue V2 (Section A: 6 questions, Section B: 24+ questions avec sous-questions)"
    version: "V2 - 2025-06-20"

# Tags for Searchability
tags:
  - emma
  - assurance-vie
  - temporaire
  - permanent
  - t100
  - t10
  - guaranteed-issue
  - emission-garantie
  - cancer
  - invalidite
  - enfant-a-charge
  - quebec
  - unified-guide
  - questionnaire-sante
  - health-questionnaire
  - eligibility
  - admissibilite
---

# Emma - Guide Unifié des Produits

## Vue d'ensemble

**Emma** est une gamme de produits d'assurance vie distribués par **Emma Services financiers Inc.** et émis par **Humania Assurance Inc.** Ces produits sont offerts via une plateforme numérique moderne avec un processus de souscription efficace.

### Relation Produit-Assureur

| Élément | Détails |
|---------|---------|
| **Assureur / Émetteur** | Humania Assurance Inc. |
| **Distributeur** | Emma Services financiers Inc. |
| **Types de souscription** | Pleine sélection (Emma T100, Emma Temporaire) OU Émission garantie (Emma GI) |
| **Vérification MIB** | Oui, pour produits à pleine sélection |

---

## Catalogue des Produits

### Tableau Comparatif - Produits Principaux

| Produit | Type | Souscription | Âge | Couverture | Renouvelable | Transformable |
|---------|------|--------------|-----|------------|--------------|---------------|
| **Emma T100** | Vie permanente | Pleine sélection | 18-80 | 1 000 $ - 5 M$ | Non | Non |
| **Emma Temporaire** | Vie temporaire (T10-T35) | Pleine sélection | 18-80 | 50 000 $ - 5 M$ | Oui (→80 ans) | Oui (→65 ans) |
| **Emma GI T20** | Vie temporaire 20 ans | Émission garantie | 18-60 | 5 000 $ - 100 000 $ | Oui (→80 ans) | Oui (→65 ans) |
| **Emma GI T100** | Vie permanente T100 | Émission garantie | 18-70 | 5 000 $ - 100 000 $ | Non | Non |

### Tableau Comparatif - Avenants (Riders)

| Avenant | Type | Âge | Couverture | Particularités |
|---------|------|-----|------------|----------------|
| **Avenant Enfant** | Protection dépendants | N/A | 15 000 $ - 25 000 $ | Transformable 5x |
| **Avenant Cancer** | Maladies graves | 18-70 | 10 000 $ - 75 000 $ | Période moratoire 90 jours |
| **Avenant Invalidité** | Invalidité totale | 18-60 | 500 $ - 3 000 $/mois | Délai carence 90 jours |

---

## 1. Emma T100 - Assurance Vie Permanente

### Fiche Technique

| Caractéristique | Détails |
|-----------------|---------|
| **Type** | Assurance vie permanente T100 |
| **Âge d'établissement** | 18 à 80 ans |
| **Capital minimum** | 1 000 $ |
| **Capital maximum** | 5 000 000 $ |
| **Valeur de rachat** | Aucune |
| **Participation aux bénéfices** | Non |

### Options de Paiement des Primes

1. **Jusqu'à 100 ans** - Paiement viager
2. **Jusqu'à 65 ans** - Paiement limité
3. **Durant 20 ans** - Paiement limité

### Admissibilité

- Résident permanent ou citoyen canadien
- Doit comprendre et parler français ou anglais

---

## 2. Emma Temporaire - Assurance Vie Temporaire

### Fiche Technique

| Caractéristique | Détails |
|-----------------|---------|
| **Type** | Assurance vie temporaire renouvelable et transformable |
| **Termes disponibles** | T10 à T35 (Pick-a-Term: choix libre entre 10 et 35 ans) |
| **Âge d'établissement** | 18 à 80 ans |
| **Capital minimum** | 50 000 $ |
| **Capital maximum** | 5 000 000 $ |

### Droits du Titulaire

#### Droit de Renouvellement
- **Fréquence:** Annuel après le terme initial
- **Jusqu'à:** 80 ans
- **Preuve d'assurabilité:** Non requise

#### Droit de Transformation
- **Disponible jusqu'à:** 65 ans
- **Montant minimum:** 1 000 $
- **Vers:** Assurance vie entière sans participation
- **Preuve d'assurabilité:** Non requise

#### Droit d'Échange
- **Période:** 1er au 5e anniversaire
- **Maximum:** Une seule fois
- **Description:** Échanger pour un terme plus long sans preuve d'assurabilité

---

## 3. Emma GI - Assurance Vie à Émission Garantie

### Fiche Technique

| Caractéristique | Emma GI T20 | Emma GI T100 |
|-----------------|-------------|--------------|
| **Type** | Temporaire 20 ans | Permanente T100 |
| **Souscription** | Émission garantie (sans questions médicales) | Émission garantie (sans questions médicales) |
| **Âge d'établissement** | 18 à 60 ans | 18 à 70 ans |
| **Capital minimum** | 5 000 $ | 5 000 $ |
| **Capital maximum** | 100 000 $ | 100 000 $ |
| **Primes payables jusqu'à** | 80 ans | 100 ans |
| **Renouvelable** | Oui | Non |
| **Transformable** | Oui (jusqu'à 65 ans) | Non |

### Caractéristiques Clés

#### Émission Garantie
- **Aucune question médicale** requise
- Acceptation garantie pour tous les candidats admissibles
- Processus simplifié

#### Période Différée (Graded Benefit)

> ⚠️ **Important:** Ce produit comporte une **période différée de 2 ans**.

| Cause du décès | Années 1-2 | Après 2 ans |
|----------------|------------|-------------|
| **Décès accidentel** | Capital assuré payé | Capital assuré payé |
| **Décès non-accidentel** | Remboursement des primes seulement | Capital assuré payé |

### Admissibilité

- Résident permanent ou citoyen canadien
- **T20:** 18 à 60 ans
- **T100:** 18 à 70 ans

### Droit de Transformation (T20 seulement)

- **Disponible jusqu'à:** 65 ans
- **Montant minimum:** 5 000 $
- **Sans preuve d'assurabilité**

### Limites de Couverture

| Limite | Montant |
|--------|---------|
| **Minimum** | 5 000 $ |
| **Maximum** | 100 000 $ |
| **Maximum toutes polices Emma GI** | 100 000 $ |

> Si la somme des montants d'assurance dépasse 100 000 $, Humania Assurance paie un maximum de 100 000 $, annule les contrats excédentaires et rembourse les primes en trop.

### Exclusions

- Suicide dans les 2 premières années
- Fausse déclaration (nullité du contrat)
- Participation à un acte criminel
- Activités et sports dangereux (même liste que les autres produits Emma)

---

## 4. Avenant Assurance Vie pour Personne à Charge (Rider)

### Fiche Technique

| Caractéristique | Détails |
|-----------------|---------|
| **Montants disponibles** | 15 000 $, 20 000 $, 25 000 $ |
| **Couverture automatique** | Oui, pour tout nouvel enfant |
| **Début de couverture** | 15 jours après naissance |
| **Transformation** | 5x le montant à l'échéance |

### Définition d'Enfant à Charge

L'enfant doit répondre à **l'un** des critères suivants:
- Moins de 21 ans
- 21-25 ans et étudiant à temps plein
- Déficience fonctionnelle importante (survenue avant 21 ans)

**ET** respecter toutes ces conditions:
- Non marié ou conjoint de fait
- Sans emploi à temps plein
- Adresse permanente au Canada
- Couvert par l'assurance maladie provinciale

### Limitation

- **Clause préexistante:** 12 mois pour enfants présents à la date d'effet

---

## 5. Avenant Assurance Cancer (Rider)

### Fiche Technique

| Caractéristique | Détails |
|-----------------|---------|
| **Âge d'établissement** | 18 à 70 ans |
| **Couverture jusqu'à** | 80 ans |
| **Montant minimum** | 10 000 $ |
| **Montant maximum** | 75 000 $ |
| **Maximum toutes polices** | 75 000 $ |

### Périodes Importantes

| Période | Durée | Description |
|---------|-------|-------------|
| **Moratoire** | 90 jours | Aucune indemnité si symptômes/diagnostic dans cette période |
| **Survie** | 30 jours | L'assuré doit survivre 30 jours après le diagnostic |
| **Préexistante** | 12 mois | Exclusion si condition préexistante |

### Cancer Majeur vs Cancer Mineur

- **Cancer mineur:** Payable une seule fois
- **Réduction:** Le montant cancer mineur est déduit du cancer majeur

---

## 6. Avenant Assurance Invalidité Totale (Rider)

### Fiche Technique

| Caractéristique | Détails |
|-----------------|---------|
| **Âge d'établissement** | 18 à 60 ans |
| **Couverture jusqu'à** | 65 ans |
| **Indemnité mensuelle** | 500 $ à 3 000 $ |
| **Calcul** | Min(1,5% du capital vie, maximum par catégorie d'emploi) |
| **Délai de carence** | 90 jours (rétroactif au 30e jour) |

### Périodes de Couverture

| Option | Versements Maximum |
|--------|-------------------|
| **2 ans** | 60 versements |
| **5 ans** | 84 versements |

### Utilisation des Indemnités

⚠️ **Important:** Les indemnités sont payables **exclusivement** pour le remboursement de créances admissibles.

### Créances Admissibles

| Type | Inclus |
|------|--------|
| ✅ | Prêt hypothécaire |
| ✅ | Marge de crédit hypothécaire |
| ✅ | Prêt personnel / auto |
| ✅ | Carte de crédit |
| ✅ | Taxes foncières (si hypothèque) |
| ✅ | Loyer (si pas d'hypothèque, max 2 ans) |
| ❌ | Prêts entre individus |
| ❌ | Prêts commerciaux |

### Restriction Importante

> **Faillite:** Si l'assuré fait faillite en cours d'invalidité, les prestations cessent immédiatement.

---

## Exigences de Tarification

### Matrice des Exigences par Montant et Âge

| Montant ($) | 18-40 | 41-50 | 51-55 | 56-60 | 61+ |
|-------------|-------|-------|-------|-------|-----|
| 0 - 500K | P | P | P | P | P |
| 500K - 1M | P | P | P | P | PS, MU, SV |
| 1M - 1.5M | P | P | PS, MU, SV | PS, MU, SV | PS, MU, SV |
| 1.5M - 2M | P | P | PS, MU, SV | PS, MU, SV | PS, MU, SV, RMT, ECG |
| 2M - 3M | PS, MU, SV | PS, MU, SV | PS, MU, SV | PS, MU, SV, RMT | PS, MU, SV, RMT, ECG |
| 3M - 4M | PS, MU, SV | PS, MU, SV | PS, MU, SV, RMT | PS, MU, SV, RMT | PS, MU, SV, RMT, ECG |
| 4M - 5M | PS, MU, SV | PS, MU, SV | PS, MU, SV, RMT | PS, MU, SV, RMT | PS, MU, SV, RMT, ECG |

### Légende

| Code | Signification |
|------|---------------|
| **P** | Proposition |
| **PS** | Profil sanguin |
| **MU** | Analyse d'urine |
| **SV** | Signes vitaux (taille/poids, tension artérielle) |
| **RMT** | Rapport du médecin traitant |
| **ECG** | Électrocardiogramme |

---

## Critères d'Inadmissibilité

### Situations Éliminatoires

Le client **n'est pas admissible** s'il répond «oui» à l'une de ces questions:

- ❌ Est-il en investigation médicale présentement?
- ❌ A-t-il été condamné pour conduite avec facultés affaiblies dans la dernière année?
- ❌ Le véhicule est-il équipé d'un antidémarreur éthylométrique?
- ❌ Est-il en attente d'une décision de la cour?
- ❌ A-t-il reçu une sentence dans les deux dernières années?
- ❌ Est-il en période de probation?

### Drogues Prohibées

Usage de l'une de ces substances entraîne un refus automatique:

| Drogues Éliminatoires |
|-----------------------|
| Stéroïdes anabolisants |
| Barbituriques |
| Héroïne, Morphine, Opium |
| Codéine, Demerol, Fentanyl |
| Cocaïne, Amphétamines |
| Ecstasy, LSD, DMT |
| Hallucinogènes |
| Méthadone |

---

## Exclusions Communes

### Activités et Sports Dangereux

Aucune prestation si la réclamation découle de:

| Catégorie | Activités Exclues |
|-----------|-------------------|
| **Alpinisme** | Alpinisme, Escalade de glace |
| **Sports aériens** | Parapente, Paravoile, Deltaplane, Parachutisme, Saut à l'élastique |
| **Aviation** | Toute aviation (sauf pilotes commerciaux sur vols réguliers) |
| **Plongée** | Plongée sous-marine (hors centres de vacances) |
| **Sports d'hiver** | Héli-ski, Ski hors-piste, Motoneige hors-piste |
| **Sports motorisés** | Course automobile, Kitesurf |

> ⚠️ Cette exclusion s'applique même si les activités sont pratiquées de façon récréative, encadrée, ou avec un instructeur.

---

## Conditions Acceptables au Taux Standard

Les conditions suivantes **peuvent** être acceptées au taux standard si bien contrôlées:

- ✅ Anxiété (sans complication)
- ✅ Hypercholestérolémie (bien contrôlée)
- ✅ Hypertension artérielle (bien contrôlée, BP normale)
- ✅ Côlon irritable
- ✅ Hépatite A (guérie, enzymes normales)
- ✅ Carcinome basocellulaire
- ✅ Fibrillation auriculaire (après 60 ans, investigation normale)

---

## Définition de Non-Fumeur

Personne qui n'a pas fait usage de tabac, sous quelque forme que ce soit, au cours des **12 derniers mois**:

- Cigarettes
- Vapoteuses / Cigarettes électroniques
- Produits de nicotine / Succédanés de nicotine
- Cigarillos / Petits cigares
- Plus de 12 gros cigares

---

## Dispositions Générales

| Disposition | Délai |
|-------------|-------|
| **Délai de grâce** | 30 jours |
| **Période d'incontestabilité** | 2 ans |
| **Exclusion pour suicide** | 2 ans |
| **Remise en vigueur** | Jusqu'à 2 ans après résiliation |
| **Remise en vigueur rapide** | 90 jours (sans preuve d'assurabilité) |
| **Âge de terminaison** | 80 ans |

---

## Droits du Consommateur

### Droit d'Annulation

| Type | Délai |
|------|-------|
| **Minimum légal** | 10 jours |
| **Emma T100 - Option 1** | 15 jours après réception |
| **Emma T100 - Option 2** | 60 jours après émission |

### Liberté de Choix

- Vous n'êtes **jamais obligé** d'acheter l'assurance qui vous est offerte
- **C'est à vous de choisir** votre produit et votre assureur

### Divulgation

- Si la rémunération du distributeur est **supérieure à 30%**, il doit vous le dire

---

## Ressources



### Documents de Référence

- **Spécimen de police:** [https://emma.ca/specimen-de-police](https://emma.ca/specimen-de-police)
- **Plaintes:** [https://www.humania.ca/formuler-plainte](https://www.humania.ca/formuler-plainte)

---

## FAQ

### Q: Les patients atteints du VIH sont-ils acceptés?
**R:** Non, Humania Assurance n'accepte pas les clients porteurs du VIH.

### Q: Une femme enceinte est-elle assurable?
**R:** Oui, s'il n'y a aucune complication reliée à la grossesse et pas d'antécédents de grossesse à risque.

### Q: Pouvez-vous utiliser des résultats de tests génétiques?
**R:** Non, conformément à la loi visant à interdire la discrimination génétique.

### Q: Les clients avec un dossier criminel peuvent-ils être acceptés?
**R:** Non si accusations en instance, en probation, ou infractions multiples.

### Q: Avez-vous des lignes directrices pour les voyages?
**R:** Les personnes voyageant fréquemment en zone à risque ne sont généralement pas assurables. Les voyages humanitaires sont refusés.

---

## Questionnaire de santé et admissibilité / Health Questionnaire and Eligibility

Ce questionnaire est utilisé pour évaluer l'admissibilité des candidats à l'assurance vie Emma. Les questions sont présentées en français et en anglais avec la logique de décision.

*This questionnaire is used to assess eligibility for Emma life insurance products. Questions are presented in French and English with decision logic.*

> **Note:** Le questionnaire est divisé en deux sections:
> - **Section A** (Questions 1-6): Admissibilité de base pour couverture 5 000 $ - 100 000 $ (Émission Garantie)
> - **Section B** (Questions 7-32): Souscription complète pour couverture 5 000 $ - 5 000 000 $ (FastTrack jusqu'à 750 000 $)

> ⚠️ **Tarification manuelle:** Toute réponse menant à **"Question suivante + questionnaire additionnel"** implique une **tarification manuelle par un tarificateur humain**. Le dossier sera révisé individuellement et ne pourra pas bénéficier d'une décision automatique (FastTrack).

---

## Section A: Admissibilité de base / Basic Eligibility (5 000 $ - 100 000 $)

### Question A1 - Citoyenneté / Citizenship

**FR:** Êtes-vous citoyen canadien ou résident permanent du Canada?

**EN:** Are you a Canadian citizen or a permanent resident of Canada?

| Réponse | Décision |
|---------|----------|
| ✅ OUI | → Question suivante |
| ❌ NON | → **REFUSÉ** - Fin du questionnaire |

---

### Question A2 - Province / Province

**FR:** Dans quelle province ou territoire du Canada habitez-vous?

**EN:** In which province or territory of Canada do you live?

| Réponse | Décision |
|---------|----------|
| Menu déroulant | → Question suivante |

---

### Question A3 - Date de naissance / Date of Birth

**FR:** Quelle est votre date de naissance?

**EN:** What is your date of birth?

| Réponse | Décision |
|---------|----------|
| Âge 18-80 ans | → Question suivante |
| Autrement | → **REFUSÉ** - Fin du questionnaire |

---

### Question A4 - Sexe à la naissance / Sex at Birth

**FR:** Quel est votre sexe à la naissance?

**EN:** What is your sex at birth?

| Réponse | Décision |
|---------|----------|
| Féminin | → Taux féminins, question suivante |
| Masculin | → Taux masculins, question suivante |

---

### Question A5 - Usage du tabac / Tobacco Use

**FR:** Au cours des 12 derniers mois, à l'exception de 12 gros cigares ou moins, avez-vous consommé du tabac sous quelque forme que ce soit, y compris, mais sans s'y limiter :

* Petits cigares;
* Cigarillos;
* Cigarettes électroniques (vapoteuse);
* Produits à base de nicotine;
* Substituts de nicotine tels que patchs ou gommes à mâcher; ou
* Consommation de marijuana, de cannabis ou de haschisch en combinaison avec le tabac?

**EN:** In the past 12 months, excluding 12 large cigars or less, have you used tobacco in any form, including but not limited to:

* Small cigars;
* Cigarillos;
* Electronic cigarettes (vaping);
* Nicotine products;
* Nicotine substitutes such as patch or gum; or
* Marijuana, cannabis, or hashish use in combination with tobacco?

| Réponse | Décision |
|---------|----------|
| ✅ OUI | → **Taux fumeur**, question suivante |
| ❌ NON | → **Taux non-fumeur**, question suivante |

---

### Question A6 - Maladie terminale / Terminal Illness

**FR:** Avez-vous reçu un diagnostic d'un médecin indiquant qu'il vous reste 24 mois ou moins à vivre, ou êtes-vous actuellement hospitalisé ou souffrez-vous d'une maladie en phase terminale ?

**EN:** Have you received a diagnosis from a doctor indicating that you have 24 months or less to live, or are you currently hospitalized or suffering from a terminal illness?

| Réponse | Décision |
|---------|----------|
| ✅ OUI | → **REFUSÉ** - Fin du questionnaire |
| ❌ NON | → **Offre GI** (T10, T20 ou T100, max 100K$) OU continuer à la Section B |

---

## Section B: Souscription complète / Full Underwriting (5 000 $ - 5 000 000 $)

> **FastTrack:** Jusqu'à 750 000 $ avec décision automatique si toutes les conditions sont remplies.

---

### Question B1 - Grossesse / Pregnancy

*Posée uniquement si Section A Q3 < 50 ans ET Section A Q4 = Féminin*

**FR:** Êtes-vous actuellement enceinte ou avez-vous accouché au cours des 6 derniers mois?

**EN:** Are you currently pregnant or have you given birth in the last 6 months?

| Réponse | Décision |
|---------|----------|
| ✅ OUI | → Question B2 (utiliser poids pré-grossesse) |
| ❌ NON | → Question B2 (utiliser poids actuel) |

---

### Question B2 - Taille / Height

**FR:** Quelle est votre taille?

**EN:** What is your height?

| Réponse | Décision |
|---------|----------|
| Menu déroulant (pieds/pouces ou mètres) | → Question B3 |

---

### Question B3 - Poids / Weight

**FR:** Quel est votre poids? / Quel était votre poids avant la grossesse?

**EN:** What is your weight? / What was your pre-pregnancy weight?

| IMC (BMI) | Décision |
|-----------|----------|
| ≤ 17.0 | → **REFUSÉ** - Offre GI (T10, T20 ou T100, max 100K$) |
| 17.1 - 37.9 | → ✅ **OK, décision automatique** |
| 38.0 - 40.0 | → ✅ **OK, FastTrack jusqu'à 750K$** |
| 40.1 - 44.0 | → ⚠️ **OK, tarification manuelle** (FastTrack refusé) |
| ≥ 44.1 | → **REFUSÉ** - Offre GI (T10, T20 ou T100, max 100K$) |

---

### Question B4 - Antécédents criminels / Criminal Record

**FR:** Au cours des dix dernières années, avez-vous été accusé ou condamné pour une infraction pénale, ou avez-vous actuellement des poursuites en cours, incluant pour la conduite avec un taux d'alcoolémie supérieur à la limite légale ou sous l'influence de drogues?

**EN:** In the last 10 years, have you been charged or convicted of a criminal offense, or do you currently have charges pending, including driving with a blood alcohol level above the legal limit or under the influence of drugs?

| Réponse | Décision |
|---------|----------|
| ✅ OUI | → **REFUSÉ** - Offre GI (T10, T20 ou T100, max 100K$) |
| ❌ NON | → Question suivante |

---

### Question B5 - Système immunitaire / Immune System

**FR:** Avez-vous déjà été diagnostiqué, présenté des symptômes, reçu un traitement ou vous a-t-on recommandé une thérapie ou des médicaments pour l'une des affections suivantes :

* Lupus;
* Sclérodermie;
* SIDA/VIH;
* Toute autre maladie ou trouble du système immunitaire?

**EN:** Have you ever been diagnosed, shown symptoms, received treatment, or were you recommended therapy or medication for any of the following conditions:

* Lupus;
* Scleroderma;
* AIDS/HIV;
* Any other disease or disorder of the immune system?

| Réponse | Décision |
|---------|----------|
| ✅ OUI | → **REFUSÉ** - Offre GI (T10, T20 ou T100, max 100K$) |
| ❌ NON | → Question suivante |

---

### Question B6 - Épilepsie / Epilepsy

**FR:** Avez-vous déjà été diagnostiqué, présenté des symptômes, reçu un traitement ou vous a-t-on recommandé une thérapie ou des médicaments pour l'épilepsie ou les convulsions?

**EN:** Have you ever been diagnosed, shown symptoms, received treatment, or were you recommended therapy or medication for epilepsy or seizures?

| Réponse | Décision |
|---------|----------|
| ✅ OUI | → Question B6.1 |
| ❌ NON | → Question suivante |

**B6.1** Combien de convulsions avez-vous eu au cours des 12 derniers mois?

| Réponse | Décision |
|---------|----------|
| Aucune | → Question suivante |
| 1 à 6 | → Question suivante + questionnaire additionnel |
| 7 ou plus | → **REFUSÉ** - Offre GI |

---

### Question B7 - Drogues non prescrites / Non-Prescribed Drugs

**FR:** À l'exception de la marijuana, du cannabis ou du haschisch, avez-vous consommé des drogues qui ne vous ont pas été prescrites, telles que :

* Stéroïdes anabolisants;
* Barbituriques;
* Héroïne;
* Morphine;
* Opium;
* Démérol;
* Codéine;
* Amphétamines;
* Cocaïne;
* Fentanyl;
* Ecstasy;
* Speed;
* LSD;
* DMT;
* Hallucinogènes;
* Méthadone?

**EN:** Excluding marijuana, cannabis or hashish, have you used any drugs that were not prescribed to you such as: Anabolic Steroids, Barbiturates, Heroin, Morphine, Opium, Demerol, Codeine, Amphetamines, Cocaine, Fentanyl, Ecstasy, Speed, LSD, DMT, Hallucinogens, Methadone?

| Réponse | Décision |
|---------|----------|
| OUI, dernière consommation < 2 ans | → **REFUSÉ** - Offre GI |
| OUI, dernière consommation ≥ 2 ans | → Question B7.1 |
| ❌ NON | → Question suivante |

**B7.1** Depuis combien d'années n'avez-vous pas consommé?

| Réponse | Décision |
|---------|----------|
| < 8 ans | → Question suivante (FastTrack refusé) + questionnaire additionnel |
| ≥ 8 ans | → Question suivante |

---

### Question B8 - Traitement alcool/drogues / Alcohol/Drug Treatment

**FR:** Avez-vous déjà suivi un traitement (y compris la participation à un groupe de soutien) ou vous a-t-on conseillé de réduire votre consommation ou de suivre un traitement concernant la consommation d'alcool ou de drogue?

**EN:** Have you ever received treatment (including the participation in a support group) or were you advised to reduce your consumption or seek treatment regarding the use of alcohol or any drugs?

| Réponse | Décision |
|---------|----------|
| OUI, dernier traitement < 2 ans | → **REFUSÉ** - Offre GI |
| OUI, dernier traitement ≥ 2 ans | → Question B8.1 |
| ❌ NON | → Question suivante |

**B8.1** Depuis combien d'années n'avez-vous pas eu de traitement?

| Réponse | Décision |
|---------|----------|
| < 10 ans | → Question suivante (FastTrack refusé) + questionnaire additionnel |
| ≥ 10 ans | → Question B8.2 |

**B8.2** Consommez-vous encore de l'alcool ou des drogues?

| Réponse | Décision |
|---------|----------|
| ✅ OUI | → Question suivante (FastTrack refusé) + questionnaire additionnel |
| ❌ NON | → Question suivante |

---

### Question B9 - Troubles gastro-intestinaux / Gastrointestinal Disorders

**FR:** Avez-vous déjà été diagnostiqué, présenté des symptômes, reçu un traitement ou vous a-t-on recommandé une thérapie ou des médicaments pour l'une des affections suivantes :

* Maladie de Crohn;
* Colite ulcéreuse;
* Hépatite (à l'exception de l'hépatite A);
* Pancréatite;
* Hémorragie rectale ou intestinale;
* Autres troubles de l'estomac, de l'intestin, du foie, du pancréas?

**EN:** Have you ever been diagnosed, shown symptoms, received treatment, or were you recommended therapy or medication for any of the following conditions: Crohn's disease, Ulcerative colitis, Hepatitis (excluding hepatitis A), Pancreatitis, Rectal or intestinal bleeding, Other disorders of the stomach, intestine, liver, pancreas?

| Réponse | Décision |
|---------|----------|
| ✅ OUI + IMC ≤ 17.9 | → **REFUSÉ** - Offre GI |
| ✅ OUI + IMC > 17.9 | → Questions B9.1-B9.3 |
| ❌ NON | → Question suivante |

---

### Question B10 - Cannabis / Cannabis Use

**FR:** Au cours des 12 derniers mois, avez-vous consommé plus de 4 fois par semaine (ingestion ou inhalation) de la marijuana, du haschisch ou du cannabis sous quelque forme que ce soit?

**EN:** In the last 12 months, have you used more than 4 times per week (ingested or inhaled) marijuana, hashish or cannabis in any form?

| Réponse | Décision |
|---------|----------|
| ✅ OUI | → Question B10.1 |
| ❌ NON | → Question suivante |

**B10.1** Combien de fois par semaine consommez-vous?

| Réponse | Décision |
|---------|----------|
| < 7 fois | → Question suivante |
| ≥ 7 fois | → Question suivante (FastTrack refusé) + questionnaire additionnel |

---

### Question B11 - Maladies cardiovasculaires / Cardiovascular Diseases

**FR:** À l'exception de l'hypertension artérielle et/ou le cholestérol traité et contrôlé, avez-vous déjà été diagnostiqué, présenté des symptômes, reçu un traitement ou vous a-t-on recommandé une thérapie ou des médicaments pour l'une des affections suivantes :

* Maladie cardiaque;
* Crise cardiaque;
* Angine de poitrine;
* Souffle cardiaque;
* Pouls anormal;
* Anévrisme;
* Caillots sanguins;
* Maladie cérébro-vasculaire (accident vasculaire cérébral ou mini accident vasculaire cérébral tel qu'un accident ischémique transitoire (AIT);
* Autres maladies du cœur ou des vaisseaux sanguins (angioplastie, pontage cardiaque, endoprothèse cardiaque (stent), maladie vasculaire périphérique)?

**EN:** Excluding treated and controlled high blood pressure and/or high cholesterol, have you ever been diagnosed, shown symptoms, received treatment, or were you recommended therapy or medication for any of the following conditions: Heart disease, Heart attack, Angina, Heart murmur, Abnormal pulse, Aneurysm, Blood clots, Cerebrovascular disease (stroke or TIA), Any other heart or blood vessel disease?

| Réponse | Décision |
|---------|----------|
| ✅ OUI | → Question B11.1 |
| ❌ NON | → Question suivante |

**B11.1** Vous a-t-on seulement diagnostiqué un souffle cardiaque fonctionnel qui a fait l'objet d'un examen complet et dont le résultat était normal?

| Réponse | Décision |
|---------|----------|
| ✅ OUI | → Question suivante |
| ❌ NON | → Question suivante (FastTrack refusé) + questionnaire additionnel |

---

### Question B12 - Diabète / Diabetes

**FR:** Avez-vous déjà été diagnostiqué ou présentez-vous des symptômes de diabète de type 1 ou de type 2 ou de toute autre forme de diabète nécessitant de l'insuline?

**EN:** Have you ever been diagnosed or do you have symptoms of diabetes type 1, or type 2 or any form of diabetes requiring insulin?

| Réponse | Décision |
|---------|----------|
| ✅ OUI | → Questions B12.1-B12.3 (sous-questions diabète) |
| ❌ NON | → Question suivante |

---

### Question B13 - Apnée du sommeil / Sleep Apnea

**FR:** Avez-vous déjà été diagnostiqué, présenté des symptômes, reçu un traitement ou vous a-t-on recommandé une thérapie ou des médicaments pour l'apnée du sommeil?

**EN:** Have you ever been diagnosed, shown symptoms, received treatment, or were you recommended therapy or medication for sleep apnea?

| Réponse | Décision |
|---------|----------|
| ✅ OUI | → Question B13.1 |
| ❌ NON | → Question suivante |

**B13.1** Utilisiez-vous chaque jour un traitement tel qu'une BiPAP, une CPAP ou toute autre machine ou appareil buccal au cours d'au moins les douze (12) derniers mois ou plus?

| Réponse | Décision |
|---------|----------|
| ✅ OUI | → Question suivante |
| ❌ NON | → Question suivante (FastTrack refusé) + questionnaire additionnel |

---

### Question B14 - Anxiété/Dépression légère / Mild Anxiety/Depression

**FR:** Au cours des cinq (5) dernières années, avez-vous été diagnostiqué, présenté des symptômes, reçu un traitement, ou vous a-t-on recommandé une thérapie ou des médicaments pour l'une des affections suivantes :

* Anxiété généralisée;
* Dépression saisonnière;
* Dépression post-partum?

**EN:** In the last five (5) years, have you been diagnosed, shown symptoms, received treatment, or were you recommended therapy or medication for: Generalized anxiety, Seasonal Depression, Post-partum depression?

| Réponse | Décision |
|---------|----------|
| ✅ OUI | → Questions B14.1-B14.3 (sous-questions) |
| ❌ NON | → Question suivante |

---

### Question B15 - Troubles de santé mentale / Mental Health Disorders

**FR:** Avez-vous déjà été diagnostiqué, présenté des symptômes, reçu un traitement ou vous a-t-on recommandé une thérapie ou des médicaments pour l'une des affections suivantes :

* Dépression;
* Trouble de la personnalité;
* Trouble bipolaire;
* Épuisement professionnel;
* Troubles de l'alimentation;
* Schizophrénie;
* Tentative de suicide?

**EN:** Have you ever been diagnosed, shown symptoms, received treatment, or were you recommended therapy or medication for: Depression, Personality disorder, Bipolar disorder, Burnout, Eating disorder, Schizophrenia, Attempted suicide?

| Réponse | Décision |
|---------|----------|
| ✅ OUI | → Question suivante + questionnaire additionnel |
| ❌ NON | → Question suivante |

---

### Question B16 - Perte de poids / Weight Loss

**FR:** Au cours des 12 derniers mois, à l'exclusion de la période post-partum ou d'une perte de poids intentionnelle suite à un régime ou exercice physique, avez-vous perdu plus de 10% de votre poids corporel?

**EN:** In the past 12 months, excluding post-partum or intentional weight loss such as diet or exercise, have you lost more than 10% of your body weight?

| Réponse | Décision |
|---------|----------|
| ✅ OUI | → Question suivante + questionnaire additionnel |
| ❌ NON | → Question suivante |

---

### Question B17 - Emploi / Employment

**FR:** Travaillez-vous actuellement?

**EN:** Are you employed?

| Réponse | Décision |
|---------|----------|
| OUI, je travaille | → Question B17.1 |
| OUI, en congé parental/maternité/paternité | → Question B17.1 |
| NON, étudiant temps plein ou au foyer | → Question suivante |
| NON, retraité (raison non médicale) | → Question suivante (si < 55 ans → tarification) |
| NON | → Question suivante + questionnaire additionnel |

**B17.1** Est-ce que votre occupation fait partie des fonctions suivantes?

* Plongée commerciale (tel que construction en haute mer ou sauvetage, plongeur, démolisseur, récolte marine, plate-forme pétrolière, pose de câbles ou de tuyaux);
* Travail à des hauteurs supérieures à 10 mètres (30 pieds);
* Pêche en haute mer;
* Exploitation minière souterraine ou en mer;
* Exploitation forestière ou sylviculture (à l'exception des transporteurs de grumes);
* Monteur de lignes électriques ou hydroélectriques;
* Pilote (sauf sur une ligne aérienne commerciale régulière);
* Diplomate;
* Politicien;
* Journaliste voyageant dans des pays à haut risque;
* Personnel militaire déployé ou ayant reçu l'ordre d'être déployé au cours des 12 prochains mois;
* Cascadeur;
* Danseur exotique ou dans l'industrie des films pour adultes?

| Réponse | Décision |
|---------|----------|
| ✅ OUI | → Question suivante + questionnaire additionnel |
| ❌ NON | → Question suivante |

---

### Question B18 - Antécédents familiaux (héréditaires) / Family History (Hereditary)

**FR:** Avant l'âge de 65 ans, un membre de votre famille immédiate (père, mère, frère ou sœur) a-t-il été diagnostiqué avec l'une des conditions médicales suivantes :

* Sclérose latérale amyotrophique;
* Cardiomyopathie;
* Syndrome du cancer du côlon sans polypose héréditaire;
* Syndrome de Lynch;
* Maladie de Huntington;
* Dystrophie musculaire;
* Maladie polykystique des reins?

**EN:** Before the age of 65, have any of your immediate family member(s) (father, mother, brother or sister) been diagnosed with: Amyotrophic Lateral Sclerosis, Cardiomyopathy, Hereditary non-polyposis colon cancer syndrome, Lynch syndrome, Huntington's disease, Muscular dystrophy, Polycystic kidney disease?

| Réponse | Décision |
|---------|----------|
| ✅ OUI | → Question suivante + questionnaire additionnel |
| ❌ NON | → Question suivante |

---

### Question B19 - Antécédents familiaux (multiples) / Family History (Multiple)

**FR:** Avant l'âge de 60 ans, deux ou plusieurs membres de votre famille immédiate (père, mère, frère, sœur) ont-ils été diagnostiqués avec **la même** des conditions médicales suivantes :

* Cancer;
* Accident vasculaire cérébral;
* Crise cardiaque;
* Angine de poitrine;
* Pontage cardiaque;
* Angioplastie;
* Sclérose en plaques;
* Maladie du motoneurone;
* Alzheimer;
* Démence?

**EN:** Before the age of 60, have 2 or more of your immediate family members (father, mother, brother, sister) been diagnosed with **the same** medical condition such as: Cancer, Stroke, Heart attack, Angina, Heart bypass, Angioplasty, Multiple sclerosis, Motor neuron disease, Alzheimer's, Dementia?

| Réponse | Décision |
|---------|----------|
| OUI, DEUX membres avec LA MÊME condition | → Question suivante + questionnaire additionnel |
| NON, UN SEUL membre avec une condition | → Question suivante |
| ❌ NON | → Question suivante |

---

### Question B20 - Symptômes non consultés / Unconsulted Symptoms

**FR:** À l'exclusion des examens annuels, des suivis de routine liés à la grossesse ou à l'accouchement dont les résultats sont normaux, des rhumes, grippes ou allergies saisonnières, des foulures ou entorses...
Avez-vous des symptômes physiques ou mentaux pour lesquels vous n'avez pas encore consulté un professionnel de la santé ?

**EN:** Excluding annual tests, routine pregnancy or childbirth-related follow-ups with normal results, common cold, flu or seasonal allergies, strains or sprains...
Do you have any physical or mental symptoms for which you have not yet consulted a health professional?

| Réponse | Décision |
|---------|----------|
| ✅ OUI | → Question suivante + questionnaire additionnel |
| ❌ NON | → Question suivante |

---

### Question B21 - Investigations médicales / Medical Investigations

**FR:** À l'exclusion des examens annuels, des suivis de routine liés à la grossesse ou à l'accouchement dont les résultats sont normaux, des rhumes, grippes ou allergies saisonnières, des foulures ou entorses...
Au cours des 12 derniers mois, vous a-t-on avisé d'un résultat d'examen anormal, recommandé un traitement ou des examens qui ne sont pas encore commencés ou attendez-vous actuellement les résultats d'examens médicaux?

**EN:** Excluding annual tests, routine pregnancy or childbirth-related follow-ups with normal results, common cold, flu or seasonal allergies, strains or sprains...
In the last 12 months, have you been advised of an abnormal test result, or to have treatment or investigations which have not yet started or been completed, or are you currently awaiting results of any medical investigations?

| Réponse | Décision |
|---------|----------|
| ✅ OUI | → Question suivante + questionnaire additionnel |
| ❌ NON | → Question suivante |

---

### Question B22 - Troubles endocriniens / Endocrine Disorders

**FR:** À l'exception de l'hypothyroïdie et de l'hyperthyroïdie contrôlées, avez-vous déjà été diagnostiqué, présenté des symptômes, reçu un traitement ou vous a-t-on recommandé une thérapie ou des médicaments pour l'un des troubles suivants :

* Glande surrénale;
* Glande parathyroïde;
* Glande pituitaire;
* Hémochromatose;
* Tout autre trouble de la glande endocrine, glandulaire ou métabolique?

**EN:** Excluding controlled hypothyroidism and hyperthyroidism, have you ever been diagnosed, shown symptoms, received treatment, or were you recommended therapy or medication for: Adrenal, Parathyroid, Pituitary, Hemochromatosis, Any other endocrine, gland, or metabolic disorders?

| Réponse | Décision |
|---------|----------|
| ✅ OUI | → Question suivante + questionnaire additionnel |
| ❌ NON | → Question suivante |

---

### Question B23 - Cancer et tumeurs / Cancer and Tumors

**FR:** Avez-vous déjà été diagnostiqué, présenté des symptômes, reçu un traitement ou vous a-t-on recommandé une thérapie ou des médicaments pour l'une des affections suivantes :

* Cancer;
* Polype(s);
* Kyste(s) malin(s);
* Tumeur(s);
* Maladie de Hodgkin;
* Lymphome;
* Leucémie;
* Mélanome;
* Toute autre croissance anormale ou tumeur maligne?

**EN:** Have you ever been diagnosed, shown symptoms, received treatment, or were you recommended therapy or medication for: Cancer, Polyp(s), Malignant Cyst(s), Tumor(s), Hodgkin's disease, Lymphoma, Leukemia, Melanoma, Any other abnormal growth or malignancy?

| Réponse | Décision |
|---------|----------|
| ✅ OUI | → Question suivante + questionnaire additionnel |
| ❌ NON | → Question suivante |

> **Note:** Kyste bénin = répondre NON (pas de tarification requise)

---

### Question B24 - Maladies pulmonaires / Lung Diseases

**FR:** Avez-vous déjà été diagnostiqué, présenté des symptômes, reçu un traitement ou vous a-t-on recommandé une thérapie ou des médicaments pour l'une des affections suivantes :

* Emphysème;
* Maladie pulmonaire obstructive chronique (MPOC);
* Bronchite chronique;
* Fibrose kystique?

**EN:** Have you ever been diagnosed, shown symptoms, received treatment, or were you recommended therapy or medication for: Emphysema, Chronic Obstructive Pulmonary Disease (COPD), Chronic bronchitis, Cystic fibrosis?

| Réponse | Décision |
|---------|----------|
| ✅ OUI | → Question suivante + questionnaire additionnel |
| ❌ NON | → Question suivante |

---

### Question B25 - Troubles musculaires/neurologiques / Muscular/Neurological Disorders

**FR:** Avez-vous déjà été diagnostiqué, présenté des symptômes, reçu un traitement ou vous a-t-on recommandé une thérapie ou des médicaments pour l'une des affections suivantes :

* Dystrophie musculaire;
* Engourdissement ou faiblesse d'un bras ou d'une jambe;
* Paralysie?

**EN:** Have you ever been diagnosed, shown symptoms, received treatment, or were you recommended therapy or medication for: Muscular dystrophy, Numbness or weakness of an arm or leg, Paralysis?

| Réponse | Décision |
|---------|----------|
| ✅ OUI | → Question suivante + questionnaire additionnel |
| ❌ NON | → Question suivante |

---

### Question B26 - Sclérose en plaques / Multiple Sclerosis

**FR:** Avez-vous déjà été diagnostiqué, présenté des symptômes, reçu un traitement ou vous a-t-on recommandé une thérapie ou des médicaments pour la sclérose en plaques?

**EN:** Have you ever been diagnosed, shown symptoms, received treatment, or were you recommended therapy or medication for multiple sclerosis?

| Réponse | Décision |
|---------|----------|
| ✅ OUI | → Question suivante + questionnaire additionnel |
| ❌ NON | → Question suivante |

---

### Question B27 - Autres troubles neurologiques / Other Neurological Disorders

**FR:** Avez-vous déjà été diagnostiqué, présenté des symptômes, reçu un traitement ou vous a-t-on recommandé une thérapie ou des médicaments pour l'une des affections suivantes :

* Maladie du motoneurone;
* Autisme;
* Paralysie cérébrale;
* Syndrome de Down;
* Maladie de Parkinson?

**EN:** Have you ever been diagnosed, shown symptoms, received treatment, or were you recommended therapy or medication for: Motor neuron disease, Autism, Cerebral palsy, Down syndrome, Parkinson's disease?

| Réponse | Décision |
|---------|----------|
| ✅ OUI | → Question suivante + questionnaire additionnel |
| ❌ NON | → Question suivante |

---

### Question B28 - Troubles génito-urinaires / Genitourinary Disorders

*Question selon le sexe à la naissance*

**Pour les hommes / For Males:**

**FR:** Avez-vous déjà été diagnostiqué, présenté des symptômes, reçu un traitement ou vous a-t-on recommandé une thérapie ou des médicaments pour l'une des affections suivantes :

* Trouble de la prostate (à l'exception de la prostatite traitée par antibiotiques);
* Trouble des organes génitaux;
* Néphrite;
* Maladie polykystique des reins;
* Sucre ou sang dans les urines (au cours des 2 dernières années);
* Tout autre trouble génito-urinaire?

**Pour les femmes / For Females:**

**FR:** Avez-vous déjà été diagnostiqué, présenté des symptômes, reçu un traitement ou vous a-t-on recommandé une thérapie ou des médicaments pour l'une des conditions suivantes :

* Frottis vaginal (pap test) anormal au cours des 2 dernières années;
* Trouble des ovaires;
* Trouble de l'utérus ou des organes génitaux;
* Néphrite;
* Maladie polykystique des reins;
* Sucre ou de sang dans les urines au cours des 2 dernières années (à l'exclusion des menstruations);
* Tout autre trouble génito-urinaire?

| Réponse | Décision |
|---------|----------|
| ✅ OUI | → Question suivante + questionnaire additionnel |
| ❌ NON | → Question suivante |

---

### Question B29 - Troubles arthritiques / Arthritic Disorders

**FR:** Avez-vous déjà été diagnostiqué, présenté des symptômes, reçu un traitement ou vous a-t-on recommandé une thérapie ou des médicaments pour l'une des affections suivantes :

* Arthrite rhumatoïde;
* Arthrite psoriasique;
* Maladie du disque vertébral?

**EN:** Have you ever been diagnosed, shown symptoms, received treatment, or were you recommended therapy or medication for: Rheumatoid arthritis, Psoriatic arthritis, Spinal disc disease?

| Réponse | Décision |
|---------|----------|
| ✅ OUI | → Question suivante + questionnaire additionnel |
| ❌ NON | → Question suivante |

---

### Question B30 - Voyages / Travel

**FR:** Au cours des 12 prochains mois, prévoyez-vous de voyager en dehors de l'Amérique du Nord, des Caraïbes (à l'exception d'Haïti), de l'Australie, de la Nouvelle-Zélande ou de l'Union européenne (y compris le Royaume-Uni), ou prévoyez-vous de résider en dehors du Canada pendant plus de 6 mois?

**EN:** In the next 12 months, do you plan to travel outside of North America, the Caribbean (excluding Haiti), Australia, New Zealand, or the European Union (including the United Kingdom) or do you plan to reside outside of Canada for more than 6 months?

| Réponse | Décision |
|---------|----------|
| ✅ OUI | → **FIN** + questionnaire additionnel |
| ❌ NON | → **FIN** |

---

## Exclusions de police / Policy Exclusions

> **Note:** Les activités suivantes ne sont plus posées sous forme de question mais sont **exclues de la couverture** dans les conditions de la police.

**FR:** Au cours des deux dernières années, avez-vous participé ou avez-vous l'intention de participer, au cours des douze prochains mois, à l'une des activités ou à l'un des sports suivants :

* Alpinisme;
* Escalade de glace;
* Plongée sous-marine (autre que dans un centre de vacances);
* Parapente;
* Paravoile;
* Deltaplane;
* Parachutisme;
* Saut à l'élastique;
* Héli-ski;
* Ski hors-piste;
* Motoneige hors-piste;
* Aviation (à l'exception des pilotes commerciaux sur des vols réguliers);
* Course automobile;
* Kitesurf

**EN:** In the last 2 years, have you participated in or, in the next 12 months, do you intend to participate in: Mountain climbing, Ice climbing, Scuba diving (other than at a vacation resort), Paragliding, Parasailing, Hang gliding, Skydiving, Bungee jumping, Heli-skiing, Backcountry skiing, Backcountry snowmobiling, Aviation (excluding commercial pilot), Motor racing, Kitesurfing

> ⚠️ **Ces activités sont exclues de la couverture et ne font pas l'objet de questions de souscription.**

---

## Notes Légales

**Avertissement:** Les informations contenues dans ce guide sont à titre indicatif seulement et n'engagent pas Humania Assurance inc.

**Décisions finales:** Toutes les décisions de tarification sont prises au cas par cas.

**Confidentialité:** Toutes les informations médicales et personnelles sont traitées de manière confidentielle.

---

*Dernière mise à jour: 2025-12-29*

