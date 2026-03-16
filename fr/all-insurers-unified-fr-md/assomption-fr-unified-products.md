---
# ═══════════════════════════════════════════════════════════════════════
# UNIFIED INSURER DOCUMENT
# ═══════════════════════════════════════════════════════════════════════

# Document Metadata
document_id: "assomption-fr-unified-products-v1.0"
document_type: unified_insurer_guide
schema_version: "3.0"
version: 1.0
document_title: "Guide Unifié des Produits - Assomption Vie"
last_updated: "2024-01-01"
effective_date: "2024-01-01"
language: fr-CA
region: CA

# ═══════════════════════════════════════════════════════════════════════
# INSURER PROFILE
# ═══════════════════════════════════════════════════════════════════════
insurer:
  id: "assomption"
  name: "Assomption Vie"
  legal_name: "Assomption Vie"
  type: "mutual_company"
  founded: 1903
  experience_years: 120
  simplified_issue_experience: 25
  address: "770, rue Main, C.P. 160, Moncton (N.-B.) E1C 8L1"
  phone_advisors: "1-800-455-7337"
  website: "https://www.assomption.ca"
  electronic_platform: "Lia"

# ═══════════════════════════════════════════════════════════════════════
# PRODUCTS CATALOG
# ═══════════════════════════════════════════════════════════════════════
products:
  # ─────────────────────────────────────────────────────────────────────
  # FULLY UNDERWRITTEN PRODUCTS
  # ─────────────────────────────────────────────────────────────────────
  
  # PRODUCT 1: FlexTerm
  - id: "assomption-flexterm"
    name: "FlexTerm"
    name_en: "FlexTerm Term Life Insurance"
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
      - "Family protection"
      - "Business key person insurance"
    
    eligibility:
      age_range: [18, 75]
      residency: "Canadian resident"
    
    variants:
      - id: "flexterm-10"
        name: "FlexTerm 10"
        term_length: 10
        renewable: true
        convertible: true
      - id: "flexterm-15"
        name: "FlexTerm 15"
        term_length: 15
        renewable: true
        convertible: true
      - id: "flexterm-20"
        name: "FlexTerm 20"
        term_length: 20
        renewable: true
        convertible: true
      - id: "flexterm-25"
        name: "FlexTerm 25"
        term_length: 25
        renewable: true
        convertible: true
      - id: "flexterm-30"
        name: "FlexTerm 30"
        term_length: 30
        renewable: true
        convertible: true
    
    coverage:
      min_amount: 10000
      max_amount: 10000000
      currency: CAD
    
    features:
      renewable: true
      convertible: true
      cash_value: false
      participating: false
    
    questionnaire:
      sections: 3
      section_a: "Évaluation médicale"
      section_b: "Mode de vie"
      section_c: "Autre information"
    
    source_documents:
      - document_id: "assomption-fr-guide-de-tarification.mdx"
        type: "underwriting_guide"
      - document_id: "assomption-fr-guide-de-tarification-questions.mdx"
        type: "questionnaire_guide"
    
    tags:
      - assurance-vie-temporaire
      - flexterm
      - produit-tarifie
      - assomption

  # PRODUCT 2: Vie Entière Non Participante
  - id: "assomption-vie-entiere-np"
    name: "Vie Entière Non Participante"
    name_en: "Non-Participating Whole Life"
    category: "permanent_life_insurance"
    underwriting_type: "full"
    status: "active"
    
    audience:
      primary:
        - insurance_advisors
        - agents
      secondary:
        - clients
        - financial_planners
    
    use_cases:
      - "Estate planning"
      - "Final expenses"
      - "Wealth transfer"
    
    eligibility:
      age_range: [18, 85]
      residency: "Canadian resident"
    
    coverage:
      min_amount: 10000
      max_amount: 10000000
      currency: CAD
    
    features:
      participating: false
      cash_value: true
    
    source_documents:
      - document_id: "assomption-fr-guide-de-tarification.mdx"
        type: "underwriting_guide"
    
    tags:
      - assurance-vie-entiere
      - non-participante
      - produit-tarifie
      - assomption

  # PRODUCT 3: ParPlus (Participating Whole Life)
  - id: "assomption-parplus"
    name: "ParPlus"
    name_en: "Participating Whole Life"
    category: "permanent_life_insurance"
    underwriting_type: "full"
    status: "active"
    
    audience:
      primary:
        - insurance_advisors
        - agents
        - financial_planners
      secondary:
        - clients
    
    use_cases:
      - "Estate planning"
      - "Wealth accumulation"
      - "Tax-advantaged savings"
      - "Legacy planning"
    
    eligibility:
      age_range: [18, 85]
      residency: "Canadian resident"
    
    coverage:
      min_amount: 10000
      max_amount: 10000000
      currency: CAD
    
    features:
      participating: true
      cash_value: true
      dividends: true
    
    source_documents:
      - document_id: "assomption-fr-guide-de-tarification.mdx"
        type: "underwriting_guide"
      - document_id: "assomption-fr-guide-de-tarification-questions.mdx"
        type: "questionnaire_guide"
    
    tags:
      - assurance-vie-entiere
      - participante
      - parplus
      - produit-tarifie
      - assomption

  # PRODUCT 4: ParPlus Junior
  - id: "assomption-parplus-junior"
    name: "ParPlus Junior"
    name_en: "Participating Whole Life for Children"
    category: "juvenile_life_insurance"
    underwriting_type: "full"
    status: "active"
    
    audience:
      primary:
        - insurance_advisors
        - agents
      secondary:
        - parents
        - grandparents
    
    use_cases:
      - "Child protection"
      - "Future insurability guarantee"
      - "Savings for child"
    
    eligibility:
      age_range: [0, 17]
      residency: "Canadian resident"
    
    coverage:
      min_amount: 10000
      max_amount: 500000
      currency: CAD
    
    features:
      participating: true
      cash_value: true
      dividends: true
      conversion_at_majority: true
    
    source_documents:
      - document_id: "assomption-fr-guide-de-tarification-questions.mdx"
        type: "questionnaire_guide"
    
    tags:
      - assurance-vie-juvenile
      - parplus-junior
      - enfant
      - assomption

  # PRODUCT 5: Option Jeunesse
  - id: "assomption-option-jeunesse"
    name: "Option Jeunesse"
    name_en: "Youth Option Term Life"
    category: "juvenile_life_insurance"
    underwriting_type: "full"
    status: "active"
    
    audience:
      primary:
        - insurance_advisors
        - agents
      secondary:
        - parents
        - grandparents
    
    use_cases:
      - "Affordable child protection"
      - "Future insurability"
    
    eligibility:
      age_range: [0, 17]
      residency: "Canadian resident"
    
    coverage:
      min_amount: 10000
      max_amount: 250000
      currency: CAD
    
    features:
      term_type: "to_age_25"
      convertible: true
    
    source_documents:
      - document_id: "assomption-fr-guide-de-tarification-questions.mdx"
        type: "questionnaire_guide"
    
    tags:
      - assurance-vie-juvenile
      - option-jeunesse
      - enfant
      - assomption

  # PRODUCT 6: Protection Vitale (Critical Illness)
  - id: "assomption-protection-vitale"
    name: "Protection Vitale"
    name_en: "Critical Illness Insurance"
    category: "critical_illness_insurance"
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
      - "Lump sum payment upon diagnosis"
      - "Treatment costs coverage"
      - "Income replacement during recovery"
    
    eligibility:
      age_range: [18, 65]
      residency: "Canadian resident"
    
    coverage:
      min_amount: 10000
      max_amount: 2000000
      currency: CAD
    
    features:
      return_of_premium: true
    
    source_documents:
      - document_id: "assomption-fr-guide-de-tarification.mdx"
        type: "underwriting_guide"
    
    tags:
      - maladies-graves
      - protection-vitale
      - produit-tarifie
      - assomption

  # ─────────────────────────────────────────────────────────────────────
  # SIMPLIFIED ISSUE PRODUCTS
  # ─────────────────────────────────────────────────────────────────────
  
  # PRODUCT 7: Protection Platine
  - id: "assomption-protection-platine"
    name: "Protection Platine"
    name_en: "Platinum Protection Simplified Issue"
    category: "simplified_issue_life_insurance"
    underwriting_type: "simplified"
    status: "active"
    
    audience:
      primary:
        - insurance_advisors
        - agents
        - brokers
      secondary:
        - clients
    
    use_cases:
      - "Clients with medical history"
      - "Fast approval needed"
      - "Higher coverage simplified issue"
    
    eligibility:
      age_range: [18, 85]
      residency: "Canadian resident"
    
    variants:
      - id: "platine-vie-entiere"
        name: "Protection Platine Vie Entière"
        type: "whole_life"
        min_amount: 10000
        max_amount: 750000
      - id: "platine-temporaire"
        name: "Protection Platine Temporaire"
        type: "term_life"
        min_amount: 25000
        max_amount: 750000
    
    coverage:
      min_amount_ve: 10000
      max_amount_ve: 750000
      min_amount_temp: 25000
      max_amount_temp: 750000
      currency: CAD
    
    questionnaire:
      questions: 19
      type: "simplified"
    
    features:
      coverage_type: "immediate"
      premium_level: "lowest"
      health_requirement: "excellent_to_very_good"
      medical_exam: false
    
    source_documents:
      - document_id: "assomption-fr-guide-assurance-vie-simplifiee.mdx"
        type: "quick_reference_guide"
      - document_id: "assomption-fr-guide-de-tarification-feuillet.mdx"
        type: "marketing_flyer"
    
    tags:
      - emission-simplifiee
      - protection-platine
      - couverture-immediate
      - assomption

  # PRODUCT 8: Protection Or
  - id: "assomption-protection-or"
    name: "Protection Or"
    name_en: "Gold Protection Simplified Issue"
    category: "simplified_issue_life_insurance"
    underwriting_type: "simplified"
    status: "active"
    
    audience:
      primary:
        - insurance_advisors
        - agents
        - brokers
      secondary:
        - clients
    
    use_cases:
      - "Clients with moderate medical history"
      - "Mid-range simplified coverage"
    
    eligibility:
      age_range: [18, 85]
      residency: "Canadian resident"
    
    variants:
      - id: "or-vie-entiere"
        name: "Protection Or Vie Entière"
        type: "whole_life"
        min_amount: 5000
        max_amount: 250000
      - id: "or-temporaire"
        name: "Protection Or Temporaire"
        type: "term_life"
        min_amount: 25000
        max_amount: 250000
    
    coverage:
      min_amount_ve: 5000
      max_amount_ve: 250000
      min_amount_temp: 25000
      max_amount_temp: 250000
      currency: CAD
    
    questionnaire:
      questions: 13
      type: "simplified"
    
    features:
      coverage_type: "immediate"
      premium_level: "medium"
      health_requirement: "good_to_average"
      medical_exam: false
    
    source_documents:
      - document_id: "assomption-fr-guide-assurance-vie-simplifiee.mdx"
        type: "quick_reference_guide"
    
    tags:
      - emission-simplifiee
      - protection-or
      - couverture-immediate
      - assomption

  # PRODUCT 9: Protection Argent
  - id: "assomption-protection-argent"
    name: "Protection Argent"
    name_en: "Silver Protection Simplified Issue"
    category: "simplified_issue_life_insurance"
    underwriting_type: "simplified"
    status: "active"
    
    audience:
      primary:
        - insurance_advisors
        - agents
      secondary:
        - clients
    
    use_cases:
      - "Clients with significant medical history"
      - "Final expenses"
    
    eligibility:
      age_range: [18, 85]
      residency: "Canadian resident"
    
    coverage:
      min_amount: 5000
      max_amount: 50000
      currency: CAD
    
    questionnaire:
      questions: 9
      type: "simplified"
    
    features:
      coverage_type: "graded_progressive"
      premium_level: "higher"
      health_requirement: "average"
      medical_exam: false
      graded_benefit:
        enabled: true
        year_1: "premiums_plus_interest"
        year_2: "50_percent"
        year_3_plus: "100_percent"
    
    source_documents:
      - document_id: "assomption-fr-guide-assurance-vie-simplifiee.mdx"
        type: "quick_reference_guide"
    
    tags:
      - emission-simplifiee
      - protection-argent
      - couverture-differee-progressive
      - assomption

  # PRODUCT 10: Protection Bronze
  - id: "assomption-protection-bronze"
    name: "Protection Bronze"
    name_en: "Bronze Protection Guaranteed Issue"
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
      - "Clients with serious medical history"
      - "No medical questions needed"
      - "Final expenses"
      - "Guaranteed acceptance"
    
    eligibility:
      age_range: [18, 80]
      residency: "Canadian resident"
      guaranteed_acceptance: true
    
    coverage:
      min_amount: 5000
      max_amount: 50000
      currency: CAD
    
    questionnaire:
      questions: 0
      type: "guaranteed_issue"
    
    features:
      coverage_type: "deferred"
      premium_level: "highest"
      health_requirement: "none"
      medical_exam: false
      medical_questions: false
      graded_benefit:
        enabled: true
        period_years: 2
        description: "Période d'attente de 2 ans - remboursement des primes si décès non-accidentel"
    
    exclusions:
      extended: true
      suicide_period_years: 2
    
    source_documents:
      - document_id: "assomption-fr-guide-assurance-vie-simplifiee.mdx"
        type: "quick_reference_guide"
    
    tags:
      - emission-garantie
      - protection-bronze
      - couverture-differee
      - sans-questions-medicales
      - assomption

  # ─────────────────────────────────────────────────────────────────────
  # RIDERS
  # ─────────────────────────────────────────────────────────────────────
  
  # RIDER 1: Rente d'Invalidité
  - id: "assomption-rente-invalidite"
    name: "Rente d'Invalidité"
    name_en: "Disability Income Rider"
    category: "rider"
    parent_products: ["assomption-flexterm", "assomption-vie-entiere-np", "assomption-parplus"]
    underwriting_type: "full"
    status: "active"
    
    eligibility:
      age_range: [18, 60]
    
    features:
      type: "monthly_income_replacement"
      elimination_period_options: ["30_days", "60_days", "90_days"]
      benefit_period_options: ["2_years", "5_years", "to_age_65"]
    
    source_documents:
      - document_id: "assomption-fr-guide-de-tarification.mdx"
        type: "underwriting_guide"
    
    tags:
      - avenant
      - rente-invalidite
      - assomption

  # RIDER 2: Exonération des Primes
  - id: "assomption-exoneration-primes"
    name: "Exonération des Primes"
    name_en: "Premium Waiver Rider"
    category: "rider"
    parent_products: ["assomption-flexterm", "assomption-vie-entiere-np", "assomption-parplus"]
    underwriting_type: "full"
    status: "active"
    
    eligibility:
      age_range: [18, 55]
    
    features:
      waiver_condition: "Invalidité totale"
    
    source_documents:
      - document_id: "assomption-fr-guide-de-tarification-questions.mdx"
        type: "questionnaire_guide"
    
    tags:
      - avenant
      - exoneration-primes
      - assomption

# ═══════════════════════════════════════════════════════════════════════
# SIMPLIFIED ISSUE ELIGIBILITY MATRIX
# ═══════════════════════════════════════════════════════════════════════
simplified_issue_eligibility:
  products_comparison:
    - product: "Protection Platine"
      coverage_type: "Immédiate"
      questions: 19
      health_level: "Excellent à très bon"
      premium: "Plus basse"
      amount_ve: "10 000 $ - 750 000 $"
      amount_temp: "25 000 $ - 750 000 $"
      age_range: "18-85"
      payout: "Immédiat"
      exclusions: "Standard"
    
    - product: "Protection Or"
      coverage_type: "Immédiate"
      questions: 13
      health_level: "Bon à moyen"
      premium: "Moyenne"
      amount_ve: "5 000 $ - 250 000 $"
      amount_temp: "25 000 $ - 250 000 $"
      age_range: "18-85"
      payout: "Immédiat"
      exclusions: "Standard"
    
    - product: "Protection Argent"
      coverage_type: "Différée progressive"
      questions: 9
      health_level: "Moyen"
      premium: "Plus élevée"
      amount_ve: "5 000 $ - 50 000 $"
      amount_temp: "N/A"
      age_range: "18-85"
      payout: "Progressive (0-2 ans)"
      exclusions: "Standard"
    
    - product: "Protection Bronze"
      coverage_type: "Différée"
      questions: 0
      health_level: "Aucune exigence"
      premium: "La plus élevée"
      amount_ve: "5 000 $ - 50 000 $"
      amount_temp: "N/A"
      age_range: "18-80"
      payout: "Différé (2 ans)"
      exclusions: "Étendue"

# ═══════════════════════════════════════════════════════════════════════
# MEDICAL CONDITIONS - SIMPLIFIED ISSUE
# ═══════════════════════════════════════════════════════════════════════
medical_conditions_simplified:
  categories:
    cancer:
      conditions:
        - name: "Carcinome basocellulaire"
          platine: "✓"
          or: "✓"
          argent: "✓"
          bronze: "✓"
          note: "Accepté sans condition pour tous les produits"
        - name: "Cancer, leucémie, lymphome, mélanome"
          platine: "> 5 ans depuis diagnostic/traitement"
          or: "> 3 ans depuis diagnostic/traitement"
          argent: "> 2 ans depuis diagnostic/traitement"
          bronze: "✓"
    
    cardiovascular:
      conditions:
        - name: "Arythmie ou souffle au cœur"
          platine: "> 5 ans depuis diagnostic OU > 2 ans depuis changement médicament"
          or: "✓"
          argent: "✓"
          bronze: "✓"
        - name: "Angine ou crise cardiaque"
          platine: "> 5 ans depuis diagnostic"
          or: "> 3 ans depuis diagnostic"
          argent: "> 2 ans depuis diagnostic"
          bronze: "✓"
        - name: "Cardiomyopathie"
          platine: "> 10 ans depuis diagnostic"
          or: "> 5 ans depuis diagnostic"
          argent: "> 5 ans depuis diagnostic"
          bronze: "✓"
        - name: "Angioplastie/Pontage"
          platine: "> 5 ans depuis intervention"
          or: "> 3 ans depuis intervention"
          argent: "> 2 ans depuis intervention"
          bronze: "✓"
        - name: "Hypertension artérielle"
          platine: "✓"
          or: "✓"
          argent: "✓"
          bronze: "✓"
          note: "Accepté si bien contrôlée"
        - name: "Stimulateur cardiaque (Pacemaker)"
          platine: "✗"
          or: "✓"
          argent: "✓"
          bronze: "✓"
        - name: "AVC"
          platine: "> 5 ans depuis épisode"
          or: "> 3 ans depuis épisode"
          argent: "> 2 ans depuis épisode"
          bronze: "✓"
        - name: "AIT (mini-AVC)"
          platine: "> 5 ans depuis épisode"
          or: "✓"
          argent: "✓"
          bronze: "✓"
    
    endocrine:
      conditions:
        - name: "Diabète (sans complications)"
          platine: "✓"
          or: "✓"
          argent: "✓"
          bronze: "✓"
        - name: "Diabète avec complications"
          platine: "✗"
          or: "> 3 ans depuis complications"
          argent: "✓"
          bronze: "✓"
        - name: "Insuline prescrite"
          platine: "✓"
          or: "✓"
          argent: "✓"
          bronze: "✓"
    
    gastrointestinal:
      conditions:
        - name: "Maladie de Crohn ou Colite ulcéreuse"
          platine: "> 5 ans depuis diagnostic OU > 2 ans depuis changement médicament"
          or: "✓"
          argent: "✓"
          bronze: "✓"
        - name: "Hépatite B ou C"
          platine: "> 10 ans depuis diagnostic/traitement"
          or: "> 5 ans depuis diagnostic/traitement"
          argent: "✓"
          bronze: "✓"
    
    genitourinary:
      conditions:
        - name: "Maladie rénale chronique"
          platine: "> 5 ans depuis diagnostic"
          or: "> 3 ans depuis diagnostic"
          argent: "> 2 ans depuis diagnostic"
          bronze: "✓"
    
    mental_health:
      conditions:
        - name: "Anxiété ou dépression"
          platine: "✓"
          or: "✓"
          argent: "✓"
          bronze: "✓"
        - name: "Troubles bipolaires"
          platine: "> 5 ans depuis diagnostic OU > 2 ans depuis changement médicament"
          or: "✓"
          argent: "✓"
          bronze: "✓"
        - name: "Syndrome de Down"
          platine: "✓"
          or: "✓"
          argent: "✓"
          bronze: "✓"
        - name: "Épilepsie"
          platine: "> 5 ans depuis diagnostic OU > 2 ans depuis changement médicament"
          or: "✓"
          argent: "✓"
          bronze: "✓"
        - name: "Sclérose en plaques"
          platine: "> 5 ans depuis diagnostic OU > 2 ans depuis changement médicament"
          or: "✓"
          argent: "✓"
          bronze: "✓"
        - name: "Schizophrénie ou psychose"
          platine: "> 5 ans depuis diagnostic/traitement"
          or: "✓"
          argent: "✓"
          bronze: "✓"
    
    respiratory:
      conditions:
        - name: "Asthme"
          platine: "✓"
          or: "✓"
          argent: "✓"
          bronze: "✓"
        - name: "Apnée du sommeil"
          platine: "✓"
          or: "✓"
          argent: "✓"
          bronze: "✓"
        - name: "MPOC"
          platine: "> 2 ans depuis hospitalisation"
          or: "> 12 mois depuis hospitalisation"
          argent: "✓"
          bronze: "✓"
        - name: "Prednisone orale (trouble respiratoire)"
          platine: "> 12 mois depuis prescription"
          or: "> 12 mois depuis prescription"
          argent: "✓"
          bronze: "✓"
          note: "Inhalateurs non visés"
        - name: "Oxygène (trouble respiratoire chronique)"
          platine: "> 10 ans depuis administration"
          or: "> 5 ans depuis administration"
          argent: "✓"
          bronze: "✓"
          note: "Ne s'applique pas à l'apnée du sommeil"
    
    transplant:
      conditions:
        - name: "Greffe d'organe ou moelle osseuse"
          platine: "> 10 ans depuis greffe, pas en attente"
          or: "> 5 ans depuis greffe, pas en attente"
          argent: "> 5 ans depuis greffe, pas en attente"
          bronze: "✓"

# ═══════════════════════════════════════════════════════════════════════
# NON-MEDICAL CONDITIONS - SIMPLIFIED ISSUE
# ═══════════════════════════════════════════════════════════════════════
non_medical_conditions_simplified:
  conditions:
    - name: "Consommation de drogue"
      platine: "> 3 ans depuis consommation"
      or: "> 2 ans depuis consommation"
      argent: "✓"
      bronze: "✓"
    - name: "Traitement alcool/drogue"
      platine: "> 3 ans depuis traitement"
      or: "> 2 ans depuis traitement"
      argent: "> 12 mois depuis traitement"
      bronze: "✓"
    - name: "Faillite"
      platine: "✓"
      or: "✓"
      argent: "✓"
      bronze: "✓"
    - name: "Refus d'assurance passé"
      platine: "✓"
      or: "✓"
      argent: "✓"
      bronze: "✓"
    - name: "Infraction conduite alcool/drogue"
      platine: "> 3 ans depuis accusation/condamnation"
      or: "> 2 ans depuis accusation/condamnation"
      argent: "✓"
      bronze: "✓"
    - name: "Sports dangereux/aviation privée"
      platine: "Exclu si planifié 12 prochains mois"
      or: "✓"
      argent: "✓"
      bronze: "✓"
    - name: "Nouveaux résidents du Canada"
      platine: "✓ (voir guide)"
      or: "✓ (voir guide)"
      argent: "✓ (voir guide)"
      bronze: "✓ (voir guide)"
      max_coverage: 750000
    - name: "Voyage international"
      platine: "< 12 semaines consécutives hors Amérique du Nord/Europe/Caraïbes"
      or: "✓"
      argent: "✓"
      bronze: "✓"

# ═══════════════════════════════════════════════════════════════════════
# UNDERWRITING - FULLY UNDERWRITTEN PRODUCTS
# ═══════════════════════════════════════════════════════════════════════
underwriting:
  electronic_platform: "Lia"
  
  abbreviations:
    RMT: "Rapport du médecin traitant"
    MG: "Maladie grave"
    RI: "Rente d'invalidité"
    PS: "Profil sanguin"
    ESV: "Examen des signes vitaux"
  
  questionnaires:
    - code: "3876-00F"
      name: "Questionnaire sur la consommation d'alcool"
    - code: "3886-00F"
      name: "Questionnaire sur le diabète"
    - code: "3887-00F"
      name: "Questionnaire sur la consommation de drogues"
    - code: "3894-00F"
      name: "Questionnaire sur les problèmes gastro-intestinaux"
    - code: "3900-00F"
      name: "Questionnaire sur les troubles psychologiques ou nerveux"
    - code: "3907-00F"
      name: "Questionnaire sur les troubles respiratoires"
    - code: "4413-00F"
      name: "Questionnaire sur l'arthrite"
    - code: "5450-00F"
      name: "Questionnaire sur les troubles musculosquelettiques"
    - code: "6869-00F"
      name: "Questionnaire sur l'apnée du sommeil"
  
  decision_types:
    - id: "standard"
      name: "Taux standard"
      description: "Police émise aux taux standards"
    - id: "rated"
      name: "Surprime"
      description: "Police émise avec surprime (%, $ par mille)"
    - id: "exclusion"
      name: "Exclusion"
      description: "Police émise avec exclusion de condition"
    - id: "declined"
      name: "Refus"
      description: "Aucune offre ne peut être faite"
  
  smoker_definition: "Abstention de tabac, nicotine, ou marijuana mélangée à de la nicotine, et pas d'utilisation de cigarettes électroniques durant les 12 derniers mois. Maximum 12 cigares par an autorisé si test nicotine négatif."

# ═══════════════════════════════════════════════════════════════════════
# MEDICAL CONDITIONS - FULL UNDERWRITING
# ═══════════════════════════════════════════════════════════════════════
medical_conditions_full:
  total_conditions: 25
  
  categories:
    alcohol_abuse:
      name: "Abus d'alcool / Alcoolisme"
      life_decision: "Surprime 300% après 2 ans abstinence; Standard après 5 ans sans rechute; Rechute = Refus"
      ci_decision: "< 5 ans abstinence = Refus; > 5 ans = Standard possible"
      ri_decision: "< 5 ans abstinence = Refus; > 5 ans = Standard possible"
      decline_triggers: ["Rechute", "Antécédents drogues ou maladie mentale"]
    
    stroke:
      name: "Accident vasculaire cérébral (AVC)"
      life_decision: "Selon âge au diagnostic et cause; < 6 mois = Refus; Récurrence = Refus"
      ci_decision: "Non assurable"
      ri_decision: "Non assurable"
      requirements: ["RMT"]
    
    family_history:
      name: "Antécédents familiaux"
      life_decision: "1 membre < 60 ans = Standard; 2+ membres même condition = Standard à 150%"
      ci_decision: "Mêmes critères, exclusion possible pour maladies héréditaires"
      ri_decision: "Mêmes critères, exclusion possible"
      note: "Ne pas divulguer tests génétiques"
    
    sleep_apnea:
      name: "Apnée du sommeil"
      life_decision: "Standard à refus selon gravité et observance traitement"
      ci_decision: "Standard à refus"
      ri_decision: "Standard à refus, aucune exclusion"
      requirements: ["Questionnaire 6869-00F", "Étude sommeil", "RMT"]
    
    rheumatoid_arthritis:
      name: "Arthrite rhumatoïde"
      life_decision: "Légère: 150%; Modérée: 175%+; Sévère: 250% à refus"
      ci_decision: "Légère: 150%; Modérée à sévère: Refus"
      ri_decision: "Tâches manuelles: Refus; Autres: 150% avec exclusion ou refus"
      requirements: ["Questionnaire 4413-00F", "RMT"]
    
    asthma:
      name: "Asthme"
      life_decision: "Crises mineures: Standard; Autres: 150%+"
      ci_decision: "Léger à modéré non-fumeur: Standard; Autres: 150%+"
      ri_decision: "Standard à refus selon gravité, exclusion possible"
      note: "Fumeur = taux augmenté"
    
    cancer:
      name: "Cancer"
      life_decision: "Selon date diagnostic, âge, type, stade; 2-3 ans attente minimum (sauf carcinome basocellulaire)"
      ci_decision: "Plupart non assurables; Carcinome basocellulaire = exception; Exclusion possible"
      ri_decision: "5-10 ans attente selon type; Exclusion possible"
    
    heart_disease:
      name: "Cardiopathie"
      life_decision: "6 mois minimum après traitement; < 35 ans: Refus probable; 200% à refus"
      ci_decision: "Refus probable"
      ri_decision: "Refus probable"
      requirements: ["RMT"]
    
    crohn_colitis:
      name: "Maladie de Crohn / Colite ulcéreuse"
      life_decision: "Légère après 2 ans: Standard; Moyenne: 200%+; Sévère: 300% ou refus"
      ci_decision: "< 2 ans: Refus ou 200% + exclusion; > 2 ans: 150-175% + exclusion; Complications: Refus"
      ri_decision: "< 2 ans: Non considéré; > 5 ans: 150%+ avec exclusion"
      requirements: ["Questionnaire 3894-00F", "RMT"]
    
    diabetes:
      name: "Diabète"
      life_decision: "Type 1 et 2: Standard à refus selon âge, durée, contrôle"
      ci_decision: "Insulinodépendants: Non assurables; < 40 ans: Non assurables; 40+ oral/régime: 200% à refus"
      ri_decision: "Insulinodépendants: Non assurables; < 40 ans: Non assurables; 40+ oral/régime: 175% à refus après 6 mois"
      requirements: ["Profil sanguin avec A1C", "Microalbumine urine", "Questionnaire 3886-00F", "RMT possible"]
      note: "Diabète gestationnel: Vie = Standard; MG = selon âge"
    
    drug_use:
      name: "Consommation de drogues"
      life_decision: "Drogues illégales actuelles: Refus; Marijuana: Standard à refus selon fréquence"
      ci_decision: "Mêmes critères"
      ri_decision: "Mêmes critères"
      note: "Marijuana médicinale: tarifier selon condition sous-jacente"
    
    fibromyalgia:
      name: "Fibromyalgie"
      life_decision: "Bien contrôlée sans dépression: Standard"
      ci_decision: "Bien contrôlée sans dépression: Standard"
      ri_decision: "Non assurable"
    
    hepatitis:
      name: "Hépatite"
      life_decision: "A guérie: Standard; B inactive: légère surprime; B chronique: Standard à refus; C: 175%+ ou non assurable"
      ci_decision: "Standard à refus selon type"
      ri_decision: "Standard à refus selon type"
      requirements: ["Profil sanguin", "Dépistage hépatite", "RMT possible"]
    
    hypertension:
      name: "Hypertension"
      life_decision: "Lectures normales, pas de comorbidité: Standard"
      ci_decision: "Standard si bien contrôlée"
      ri_decision: "Standard si bien contrôlée"
      requirements: ["Signes vitaux ou paramédical"]
    
    renal_failure:
      name: "Insuffisance rénale"
      life_decision: "Standard à refus selon stade et si aiguë/chronique"
      ci_decision: "Standard à refus"
      ri_decision: "Standard à refus"
      requirements: ["RMT"]
    
    lipids:
      name: "Lipides (cholestérol)"
      life_decision: "Bien contrôlé sans autre problème: Standard"
      ci_decision: "Standard si bien contrôlé"
      ri_decision: "Standard si bien contrôlé"
      requirements: ["Profil sanguin possible"]
    
    copd:
      name: "MPOC"
      life_decision: "Légère: Standard à 150%; Modérée: 200-250% ou refus; Sévère: Refus"
      ci_decision: "150% à refus selon gravité/tabagisme"
      ri_decision: "150% à refus selon gravité/tabagisme, exclusion possible"
      note: "Fumeur modéré à lourd: Refus"
      requirements: ["Questionnaire 3907-00F", "RMT"]
    
    multiple_sclerosis:
      name: "Sclérose en plaques"
      life_decision: "150%+ selon années depuis apparition et limitations"
      ci_decision: "Exclusion probable ou refus"
      ri_decision: "Exclusion probable ou refus"
      requirements: ["RMT"]
    
    depression:
      name: "Trouble dépressif"
      life_decision: "Léger/modéré: 150% si < 1 an, Standard après 1 an; Sévère: 200% après 1 an; Congé maladie: Refus"
      ci_decision: "Léger/modéré: Standard après 1 an; Sévère: 200%+ après 1 an"
      ri_decision: "Léger/modéré: Standard après 1 an; Sévère: Refus ou 200%+"
      note: "Tentative suicide: surprime fixe décroissante"
      requirements: ["Questionnaire 3900-00F", "RMT possible"]
    
    autism:
      name: "Troubles du spectre autistique"
      life_decision: "Selon capacité à vivre indépendamment et antécédents médicaux/comportementaux"
      ci_decision: "Selon capacité et antécédents"
      ri_decision: "Selon capacité et antécédents"

# ═══════════════════════════════════════════════════════════════════════
# NON-MEDICAL RISKS
# ═══════════════════════════════════════════════════════════════════════
non_medical_risks:
  occupation:
    description: "Risques liés à la profession"
    typical_rating: "Standard à surprime selon risque"
  
  travel:
    description: "Voyages en zones à risque"
    typical_rating: "Standard à surprime selon destination et durée"
  
  lifestyle:
    description: "Activités dangereuses (sports extrêmes, aviation privée)"
    typical_rating: "Standard à surprime ou exclusion"

# ═══════════════════════════════════════════════════════════════════════
# BUILD TABLE
# ═══════════════════════════════════════════════════════════════════════
build_tables:
  flexterm:
    description: "Limites de poids acceptables pour FlexTerm (produit tarifié)"
    entries:
      - height: "4'10\""
        height_cm: 147
        max_weight_lb: 158
        max_weight_kg: 72
      - height: "5'0\""
        height_cm: 152
        max_weight_lb: 169
        max_weight_kg: 77
      - height: "5'3\""
        height_cm: 160
        max_weight_lb: 188
        max_weight_kg: 85
      - height: "5'6\""
        height_cm: 168
        max_weight_lb: 205
        max_weight_kg: 93
      - height: "5'9\""
        height_cm: 175
        max_weight_lb: 224
        max_weight_kg: 102
      - height: "6'0\""
        height_cm: 183
        max_weight_lb: 242
        max_weight_kg: 110
      - height: "6'3\""
        height_cm: 191
        max_weight_lb: 264
        max_weight_kg: 120
      - height: "6'6\""
        height_cm: 198
        max_weight_lb: 285
        max_weight_kg: 129
      - height: "6'9\""
        height_cm: 206
        max_weight_lb: 308
        max_weight_kg: 140

# ═══════════════════════════════════════════════════════════════════════
# WEIGHT LOSS GUIDELINES
# ═══════════════════════════════════════════════════════════════════════
weight_loss_guidelines:
  life_insurance:
    calculation: "Ajouter 50% du poids perdu au cours des 12 derniers mois au poids actuel"
    surgical_waiting_period_months: 6
  critical_illness:
    max_rating_for_weight: 275
    surgical_waiting_period_months: 12
  disability:
    max_rating_for_weight: 250
    surgical_waiting_period_months: 12

# ═══════════════════════════════════════════════════════════════════════
# COMPETITIVE ADVANTAGES
# ═══════════════════════════════════════════════════════════════════════
competitive_advantages:
  - id: "experience"
    name: "Expérience inégalée"
    description: "Plus de 25 ans sur le marché de l'émission simplifiée"
  - id: "flexibility"
    name: "Flexibilité maximale"
    description: "Acceptation de conditions médicales complexes, chartes taille/poids généreuses"
  - id: "immediate"
    name: "Solutions immédiates"
    description: "Couverture immédiate pour conditions majeures, processus rapide et simplifié"
  - id: "high_coverage"
    name: "Couvertures élevées"
    description: "Jusqu'à 750 000 $ pour certains profils en émission simplifiée"
  - id: "inclusivity"
    name: "Inclusivité"
    description: "Nouveaux arrivants et clients avec antécédents financiers acceptés"

# ═══════════════════════════════════════════════════════════════════════
# DOCUMENT STATISTICS
# ═══════════════════════════════════════════════════════════════════════
statistics:
  total_products: 12
  fully_underwritten: 6
  simplified_issue: 4
  riders: 2
  product_categories:
    term_life: 1
    permanent_life: 2
    participating: 2
    juvenile: 2
    critical_illness: 1
    simplified_issue: 4
    riders: 2
  coverage_range:
    min: 5000
    max: 10000000
    currency: "CAD"
  age_ranges:
    fully_underwritten: [0, 85]
    simplified_issue: [18, 85]
    guaranteed_issue: [18, 80]
  medical_conditions_documented: 25
  simplified_issue_conditions: 30

# ═══════════════════════════════════════════════════════════════════════
# SOURCE DOCUMENTS
# ═══════════════════════════════════════════════════════════════════════
source_documents:
  - id: "assomption-fr-guide-de-tarification.mdx"
    type: "underwriting_guide"
    description: "Guide de tarification complet pour produits tarifés"
  - id: "assomption-fr-guide-assurance-vie-simplifiee.mdx"
    type: "quick_reference_guide"
    description: "Guide de référence rapide émission simplifiée"
  - id: "assomption-fr-guide-de-tarification-questions.mdx"
    type: "questionnaire_guide"
    description: "Questions médicales par produit"
  - id: "assomption-fr-guide-de-tarification-feuillet.mdx"
    type: "marketing_flyer"
    description: "Feuillet marketing émission simplifiée"
  - id: "assomption-fr-formulaire-assurance-vie-simplifiee.mdx"
    type: "application_form"
    description: "Formulaire de collecte de données"

# Tags for Searchability
tags:
  - assomption
  - assurance-vie
  - emission-simplifiee
  - flexterm
  - parplus
  - protection-platine
  - protection-or
  - protection-argent
  - protection-bronze
  - maladies-graves
  - tarification
  - underwriting
  - unified-guide
---

# Assomption Vie - Guide Unifié des Produits

## Vue d'ensemble

**Assomption Vie**, fondée en 1903, est l'une des plus importantes mutuelles d'assurance vie au Canada. Avec **plus de 25 ans d'expérience** sur le marché de l'émission simplifiée, Assomption Vie offre des solutions innovantes pour les clients ayant des antécédents médicaux.

### Informations sur l'Assureur

| Élément | Détails |
|---------|---------|
| **Nom légal** | Assomption Vie |
| **Type** | Compagnie mutuelle d'assurance |
| **Fondée** | 1903 |
| **Siège social** | 770, rue Main, Moncton (N.-B.) E1C 8L1 |
| **Téléphone conseillers** | 1-800-455-7337 |
| **Site web** | [assomption.ca](https://www.assomption.ca) |
| **Plateforme électronique** | Lia |

---

## Catalogue des Produits

### Tableau Comparatif - Produits Tarifés

| Produit | Type | Âge | Couverture | Participation |
|---------|------|-----|------------|---------------|
| **FlexTerm** | Temporaire (10-30 ans) | 18-75 | 10K$ - 10M$ | Non |
| **Vie Entière NP** | Permanente | 18-85 | 10K$ - 10M$ | Non |
| **ParPlus** | Permanente | 18-85 | 10K$ - 10M$ | Oui |
| **ParPlus Junior** | Juvénile permanente | 0-17 | 10K$ - 500K$ | Oui |
| **Option Jeunesse** | Juvénile temporaire | 0-17 | 10K$ - 250K$ | Non |
| **Protection Vitale** | Maladies graves | 18-65 | 10K$ - 2M$ | Non |

### Tableau Comparatif - Produits à Émission Simplifiée

| Produit | Couverture | Questions | Montant VE | Montant Temp | Âge | Primes |
|---------|------------|-----------|------------|--------------|-----|--------|
| **Protection Platine** | Immédiate | 19 | 10K$ - 750K$ | 25K$ - 750K$ | 18-85 | Plus basses |
| **Protection Or** | Immédiate | 13 | 5K$ - 250K$ | 25K$ - 250K$ | 18-85 | Moyennes |
| **Protection Argent** | Différée progressive | 9 | 5K$ - 50K$ | N/A | 18-85 | Plus élevées |
| **Protection Bronze** | Différée (Garantie) | 0 | 5K$ - 50K$ | N/A | 18-80 | Les plus élevées |

---

## Produits Tarifés (Full Underwriting)

### 1. FlexTerm - Assurance Vie Temporaire

#### Fiche Technique

| Caractéristique | Détails |
|-----------------|---------|
| **Type** | Assurance vie temporaire renouvelable et transformable |
| **Termes disponibles** | 10, 15, 20, 25, 30 ans |
| **Âge d'établissement** | 18 à 75 ans |
| **Capital minimum** | 10 000 $ |
| **Capital maximum** | 10 000 000 $ |

#### Sections du Questionnaire

- **Section A:** Évaluation médicale
- **Section B:** Mode de vie
- **Section C:** Autre information

---

### 2. ParPlus - Assurance Vie Participante

#### Fiche Technique

| Caractéristique | Détails |
|-----------------|---------|
| **Type** | Assurance vie entière participante |
| **Âge d'établissement** | 18 à 85 ans |
| **Capital minimum** | 10 000 $ |
| **Capital maximum** | 10 000 000 $ |
| **Participations** | Oui (dividendes) |
| **Valeur de rachat** | Oui |

---

### 3. Protection Vitale - Assurance Maladies Graves

#### Fiche Technique

| Caractéristique | Détails |
|-----------------|---------|
| **Type** | Assurance maladies graves |
| **Âge d'établissement** | 18 à 65 ans |
| **Capital minimum** | 10 000 $ |
| **Capital maximum** | 2 000 000 $ |
| **Remboursement des primes** | Disponible |

---

## Produits à Émission Simplifiée

### Organigramme de Décision

```
Client avec condition médicale/non-médicale
                ↓
    Condition présente dans les tableaux?
                ↓
        OUI                     NON
         ↓                       ↓
  Vérifier tableau    →   Protection Platine
         ↓                (si aucune autre condition)
  Lire les conditions
         ↓
Protection Platine possible? → OUI → Utiliser Platine
         ↓ NON
Protection Or possible? → OUI → Utiliser Or
         ↓ NON
Protection Argent possible? → OUI → Utiliser Argent
         ↓ NON
Protection Bronze → Toujours disponible (Émission garantie)
```

---

### 4. Protection Platine

#### Fiche Technique

| Caractéristique | Vie Entière | Temporaire |
|-----------------|-------------|------------|
| **Questions** | 19 | 19 |
| **Couverture** | Immédiate | Immédiate |
| **Montant min** | 10 000 $ | 25 000 $ |
| **Montant max** | 750 000 $ | 750 000 $ |
| **Âge** | 18-85 ans | 18-85 ans |
| **Primes** | Plus basses | Plus basses |

#### Avantages

- Meilleures primes de la gamme simplifiée
- Couverture immédiate complète
- Montants élevés (jusqu'à 750 000 $)

---

### 5. Protection Or

#### Fiche Technique

| Caractéristique | Vie Entière | Temporaire |
|-----------------|-------------|------------|
| **Questions** | 13 | 13 |
| **Couverture** | Immédiate | Immédiate |
| **Montant min** | 5 000 $ | 25 000 $ |
| **Montant max** | 250 000 $ | 250 000 $ |
| **Âge** | 18-85 ans | 18-85 ans |
| **Primes** | Moyennes | Moyennes |

#### Avantages

- Processus simplifié (13 questions seulement)
- Couverture immédiate
- Accepte plus de conditions médicales que Platine

---

### 6. Protection Argent

#### Fiche Technique

| Caractéristique | Détails |
|-----------------|---------|
| **Questions** | 9 |
| **Type couverture** | Différée progressive |
| **Montant min** | 5 000 $ |
| **Montant max** | 50 000 $ |
| **Âge** | 18-85 ans |
| **Type produit** | Vie entière seulement |

#### Couverture Différée Progressive

| Année | Paiement en cas de décès |
|-------|--------------------------|
| **Année 1** | Primes + intérêts |
| **Année 2** | 50% du capital |
| **Année 3+** | 100% du capital |

---

### 7. Protection Bronze (Émission Garantie)

#### Fiche Technique

| Caractéristique | Détails |
|-----------------|---------|
| **Questions médicales** | 0 (aucune) |
| **Type couverture** | Différée |
| **Montant min** | 5 000 $ |
| **Montant max** | 50 000 $ |
| **Âge** | 18-80 ans |
| **Acceptation** | Garantie |

#### Période d'Attente

| Période | Décès non-accidentel | Décès accidentel |
|---------|---------------------|------------------|
| **0-2 ans** | Remboursement primes | Capital complet |
| **2+ ans** | Capital complet | Capital complet |

---

## Conditions Médicales - Émission Simplifiée

### Légende

| Symbole | Signification |
|---------|---------------|
| **✓** | Admissible |
| **✗** | Non admissible |
| **»** | Admissible avec conditions |

### Conditions Acceptées Sans Restriction (Tous Produits)

| Condition | Platine | Or | Argent | Bronze |
|-----------|---------|-----|--------|--------|
| Hypertension artérielle (contrôlée) | ✓ | ✓ | ✓ | ✓ |
| Diabète (sans complications) | ✓ | ✓ | ✓ | ✓ |
| Insuline prescrite | ✓ | ✓ | ✓ | ✓ |
| Anxiété ou dépression | ✓ | ✓ | ✓ | ✓ |
| Asthme | ✓ | ✓ | ✓ | ✓ |
| Apnée du sommeil | ✓ | ✓ | ✓ | ✓ |
| Carcinome basocellulaire | ✓ | ✓ | ✓ | ✓ |
| Syndrome de Down | ✓ | ✓ | ✓ | ✓ |

### Conditions Cardiovasculaires

| Condition | Platine | Or | Argent | Bronze |
|-----------|---------|-----|--------|--------|
| Angine ou crise cardiaque | > 5 ans | > 3 ans | > 2 ans | ✓ |
| AVC | > 5 ans | > 3 ans | > 2 ans | ✓ |
| AIT (mini-AVC) | > 5 ans | ✓ | ✓ | ✓ |
| Angioplastie/Pontage | > 5 ans | > 3 ans | > 2 ans | ✓ |
| Pacemaker | ✗ | ✓ | ✓ | ✓ |
| Cardiomyopathie | > 10 ans | > 5 ans | > 5 ans | ✓ |

### Cancer

| Condition | Platine | Or | Argent | Bronze |
|-----------|---------|-----|--------|--------|
| Cancer, leucémie, lymphome, mélanome | > 5 ans | > 3 ans | > 2 ans | ✓ |

### Conditions Métaboliques et Respiratoires

| Condition | Platine | Or | Argent | Bronze |
|-----------|---------|-----|--------|--------|
| Diabète avec complications | ✗ | > 3 ans | ✓ | ✓ |
| MPOC | > 2 ans hosp. | > 12 mois hosp. | ✓ | ✓ |
| Oxygène chronique | > 10 ans | > 5 ans | ✓ | ✓ |

### Conditions Non Médicales

| Condition | Platine | Or | Argent | Bronze |
|-----------|---------|-----|--------|--------|
| Faillite | ✓ | ✓ | ✓ | ✓ |
| Refus d'assurance passé | ✓ | ✓ | ✓ | ✓ |
| Nouveaux résidents Canada | ✓ | ✓ | ✓ | ✓ |
| Consommation de drogue | > 3 ans | > 2 ans | ✓ | ✓ |
| Infraction conduite alcool | > 3 ans | > 2 ans | ✓ | ✓ |

---

## Conditions Médicales - Produits Tarifés

### Décisions Typiques par Condition

| Condition | Vie | Maladies Graves | Rente Invalidité |
|-----------|-----|-----------------|------------------|
| **Alcoolisme** | 300% après 2 ans abstinence | Refus < 5 ans | Refus < 5 ans |
| **AVC** | Selon âge/cause, Refus si < 6 mois | Non assurable | Non assurable |
| **Asthme léger** | Standard | Standard (non-fumeur) | Standard à refus |
| **Cancer** | 2-3 ans attente minimum | Plupart non assurables | 5-10 ans attente |
| **Diabète Type 2** | Standard à refus | 40+: 200% à refus | 40+: 175% à refus |
| **Dépression légère** | Standard après 1 an | Standard après 1 an | Standard après 1 an |
| **Hypertension contrôlée** | Standard | Standard | Standard |
| **MPOC légère** | Standard à 150% | 150% à refus | 150% à refus |
| **Sclérose en plaques** | 150%+ | Exclusion ou refus | Exclusion ou refus |

---

## Définition de Non-Fumeur

Personne s'étant abstenue de:

- Tabac sous toute forme
- Nicotine
- Marijuana mélangée à de la nicotine
- Cigarettes électroniques

**Période:** 12 derniers mois

**Exception:** Maximum 12 cigares par an autorisé si test nicotine négatif (cigarillos non inclus)

### Marijuana

- **Fumée ou ingérée:** Taux non-fumeur si non mélangée à nicotine
- **Vaporisateur:** Taux non-fumeur si test nicotine négatif
- **Médicinale:** Tarifier selon condition sous-jacente

---

## Avantages Compétitifs

### Pourquoi Choisir Assomption Vie?

| Avantage | Description |
|----------|-------------|
| **Expérience** | Plus de 25 ans en émission simplifiée |
| **Flexibilité** | Acceptation de conditions médicales complexes |
| **Couverture immédiate** | Solutions immédiates pour conditions majeures |
| **Montants élevés** | Jusqu'à 750 000 $ en émission simplifiée |
| **Inclusivité** | Nouveaux arrivants et faillites acceptés |

### Conditions Médicales Spéciales Acceptées

| Condition | Flexibilité |
|-----------|-------------|
| **Diabète Type 1 ou 2** | Insulinodépendance acceptée, changement médicament récent accepté |
| **AVC** | Traitement en cours et suivis acceptés |
| **Crise cardiaque** | Traitement en cours et suivis acceptés |
| **Cancer** | Tous types, métastases et récidives acceptés |
| **Dépression/Anxiété** | Arrêt de travail et changements de médication acceptés |
| **MPOC** | Couverture disponible |
| **Surpoids** | Chartes taille/poids parmi les plus généreuses |

---

## Ressources

### Portails en Ligne

- **Site web:** [www.assomption.ca](https://www.assomption.ca)
- **Plateforme Lia:** Soumission électronique des propositions

### Contact

| Service | Coordonnées |
|---------|-------------|
| **Ligne conseillers** | 1-800-455-7337 |
| **Heures** | Lundi au vendredi, 8h00 - 17h00 (HNE) |
| **Support Lia** | Disponible via le Coin du conseiller |

### Questionnaires Disponibles

| Code | Description |
|------|-------------|
| 3876-00F | Consommation d'alcool |
| 3886-00F | Diabète |
| 3887-00F | Consommation de drogues |
| 3894-00F | Troubles gastro-intestinaux |
| 3900-00F | Troubles psychologiques/nerveux |
| 3907-00F | Troubles respiratoires |
| 4413-00F | Arthrite |
| 5450-00F | Troubles musculosquelettiques |
| 6869-00F | Apnée du sommeil |

---

## Notes Légales

**Avertissement:** Ce guide est fourni à titre informatif seulement et ne constitue pas une garantie d'émission. Toutes les demandes font l'objet d'une étude individuelle.

**Réserve de droits:** Assomption Vie se réserve le droit de demander toute exigence jugée nécessaire, quel que soit l'âge du proposant ou le montant d'assurance visé.

**Décision finale:** L'offre finale du service de tarification peut différer des indications du présent guide.

---

*Dernière mise à jour: 2025-11-27*

**© Assomption Vie** - Tous droits réservés.

