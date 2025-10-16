# Emma Insurance Documentation

French-language insurance product documentation from major Canadian insurers, structured in markdown format with machine-readable metadata.

## Overview

This repository contains comprehensive insurance product documentation covering life insurance, disability insurance, critical illness coverage, and related products from leading Canadian insurance companies. All documents are in French (fr-CA) and structured for easy parsing and retrieval.

## Repository Structure

```
Produits - Assurance - Docs - French/
├── Assomption/          # Assomption Vie
├── Emma/                # Emma Services Financiers
├── Empire/              # L'Empire, Compagnie d'Assurance-Vie
├── Humania/             # Humania Assurance
├── iA/                  # iA Groupe financier
├── PPC/                 # Plan de Protection du Canada (PPC)
├── RBC/                 # RBC Assurances
└── UV/                  # UV Assurance (L'Union-Vie)
```

## File Naming Convention

All documentation files follow a consistent naming structure for easy identification and organization:

### Structure

```
[company]-[language]-[document-description].pdf.md
```

### Example Breakdown

Using `emma-fr-guide-de-tarification.pdf.md` as an example:

| Segment | Value | Description |
|---------|-------|-------------|
| **Company** | `emma` | Emma Services Financiers |
| **Language** | `fr` | French (fr-CA) |
| **Document Type** | `guide-de-tarification` | Underwriting Guide |
| **Extension** | `.pdf.md` | Markdown format (converted from PDF) |

### Common Company Prefixes

- `assomption` - Assomption Vie
- `emma` - Emma Services Financiers
- `empire` - L'Empire, Compagnie d'Assurance-Vie
- `humania` - Humania Assurance
- `ia` - iA Groupe financier
- `ppc` - Plan de Protection du Canada
- `rbc` - RBC Assurances
- `uv` - UV Assurance (L'Union-Vie)

## Insurance Companies

| Company | Products | Document Count |
|---------|----------|----------------|
| **Assomption Vie** | Simplified life insurance (4 tiers) | 4 docs |
| **Emma** | Life, child rider, disability, critical illness | 3 docs |
| **Empire Vie** | Life, critical illness, preferred ratings | 5 docs |
| **iA Financial** | Life, disability, underwriting guides | 5 docs |
| **PPC** | Simplified issue life insurance | 1 doc |
| **RBC** | Disability insurance (multiple series) | 5 docs |
| **UV Assurance** | Life, term, permanent, riders | 14 docs |

## Document Types

- **Underwriting Guides** (`underwriting_guide`) - Risk assessment criteria
- **Product Guides** (`product_guide`) - Product features and benefits
- **Rate Guides** (`rate_guide`) - Premium calculations and tables
- **Application Forms** (`application_form`) - Data collection forms
- **Quick Reference** (`quick_reference_guide`) - Eligibility matrices
- **Policy Specimens** (`specimen_contract`) - Sample contracts
- **Technical Guides** (`technical_product_guide`) - Product specifications

## Document Format

All documents follow a consistent structure:

### YAML Frontmatter
```yaml
document_id: unique-identifier
document_type: type_classification
insurer: company_information
product: product_details
coverage: limits_and_ranges
tags: searchable_keywords
features: machine_readable_flags
```

### Content Sections
- Structured markdown with headers
- Tables for data presentation
- Embedded JSON for machine-readable data
- Cross-references and internal links
- Glossaries and definitions

## Documentation Files

Below is a comprehensive list of all documentation files organized by insurance company, with brief descriptions of their content and purpose.

### Assomption

| Filename | Description |
|----------|-------------|
| `assomption-fr-formulaire-assurance-vie-simplifiee.pdf.md` | Data collection form for simplified life insurance applications with medical and non-medical questionnaires. |
| `assomption-fr-guide-assurance-vie-simplifiee.pdf.md` | Quick reference guide showing eligibility criteria for 4-tier simplified life insurance products (Platine, Or, Argent, Bronze). |
| `assomption-fr-guide-de-tarification-feuillet.pdf.md` | Marketing flyer highlighting simplified life insurance solutions with immediate coverage and medical condition acceptability. |
| `assomption-fr-guide-de-tarification-questions.pdf.md` | Medical questionnaire guide listing specific questions for each life insurance product across the portfolio. |
| `assomption-fr-guide-de-tarification.pdf.md` | Complete underwriting guide covering medical and non-medical risks, height/weight tables, and underwriting decisions. |

### Emma

| Filename | Description |
|----------|-------------|
| `emma-fr-guide-de-tarification.pdf.md` | Underwriting and preselection guide for Emma life insurance products with detailed medical conditions and risk assessment criteria. |
| `emma-fr-sommaire-produit-assurance-vie.pdf.md` | Product summary detailing Emma T100 and term life insurance, plus riders for dependents, cancer, and disability coverage. |
| `emma-fr-specimen-de-contrat.pdf.md` | Specimen insurance contract showing policy terms, definitions, guarantees, and general provisions for Emma life insurance products. |

### Empire

| Filename | Description |
|----------|-------------|
| `empire-fr-guide-de-tarification-elite-privilégie.pdf.md` | Pricing guide for Elite and Privilégié preferred rating categories with health and lifestyle qualification criteria. |
| `empire-fr-guide-de-tarification-exigences-d-appreciation-des-risques.pdf.md` | Risk assessment requirements guide showing medical exam and test requirements by age and coverage amount. |
| `empire-fr-guide-de-tarification.pdf.md` | Comprehensive underwriting guide for life and critical illness insurance covering medical and non-medical risk factors. |
| `empire-fr-personnes-immigrantes-guide.pdf.md` | Immigration guidelines for newcomers to Canada with coverage limits and requirements by immigration status. |
| `empire-fr-tarification-privilegiee-guide.pdf.md` | Preferred rating guide for Solution Series term life products with elite and preferred tier qualification criteria. |

### Humania

| Filename | Description |
|----------|-------------|
| `humania-fr-guide-preselection-assurance-salaire-accident-maladie-invalidite.pdf.md` | Preselection guide for disability insurance covering medical conditions, occupations, and eligibility criteria. |
| `humania-fr-guide-produit-assurance-salaire-accident-maladie-invalidite.pdf.md` | Product guide for salary insurance detailing total and partial disability benefits, plans, and riders. |
| `humania-fr-product-guide-assem.pdf.md` | ASSEM product guide for no medical exam life insurance with simplified issue process covering life, critical illness, and disability. |

### iA

| Filename | Description |
|----------|-------------|
| `ia-fr-acces-vie-guide-de-tarification.pdf.md` | Accès Vie simplified life insurance underwriting guide with medical condition eligibility and step-by-step process. |
| `ia-fr-acces-vie-questionnaire-de-prequalification.pdf.md` | Prequalification questionnaire for Accès Vie with 3-step eligibility process for deferred and immediate coverage. |
| `ia-fr-exigences-medicales-assurance-vie-et-assurance-invalidite.pdf.md` | Medical requirements matrix showing exam and test requirements by age and coverage amount for life and disability insurance. |
| `ia-fr-guide-de-tarification-assurance-vie-et-maladies-graves.pdf.md` | Comprehensive underwriting guide for life and critical illness insurance with medical, non-medical, and financial risk assessment. |
| `ia-fr-tarification-financiere-assurance-vie.pdf.md` | Financial underwriting guidelines for personal and business life insurance with income verification requirements. |

### PPC

| Filename | Description |
|----------|-------------|
| `ppc-fr-cpp-guide-produits-tarification-assurance-vie.pdf.md` | Product and pricing guide for Plan de Protection du Canada simplified life insurance with 6 product tiers and eligibility criteria. |

### RBC

| Filename | Description |
|----------|-------------|
| `rbc-fr-assurance-salaire-invalidite-fondamentale-series-exemple-police-contrat.pdf.md` | Policy specimen for Fundamental Series disability insurance detailing coverage terms, definitions, and benefit calculations. |
| `rbc-fr-assurance-salaire-invalidite-series-tradition.pdf.md` | Comprehensive underwriting guide for Traditional Series disability insurance covering medical and financial risk assessment. |
| `rbc-fr-assurance-salaire-invalidite-simplifiee-exemple-police-contrat.pdf.md` | Policy specimen for Simplified Disability Insurance showing contract terms, benefits, exclusions, and renewal provisions. |
| `rbc-fr-directives-tarification-assurance-invalidite-maladies-graves.pdf.md` | Underwriting manual for disability and critical illness insurance covering proposal guidelines, medical requirements, and policy delivery. |
| `rbc-fr-guide-de-taux-assurance-invalidite-serie-fondamentale.pdf.md` | Rate guide for Fundamental Series disability insurance with premium tables by age, occupation, and benefit period. |

### UV

| Filename | Description |
|----------|-------------|
| `uv-fr-assurance-fiche-technique-types-emissions.pdf.md` | Technical guide explaining different issue types (Express, Immediate, Regular) for UV life insurance products. |
| `uv-fr-assurance-individuelle-avenant-assurance-dette-guide-pratique.pdf.md` | Practical guide for debt insurance rider covering eligibility, disability definitions, and benefit calculations. |
| `uv-fr-assurance-individuelle-exigences-admissibilite.pdf.md` | Eligibility requirements matrix showing medical requirements by age and coverage amount for all UV life insurance products. |
| `uv-fr-assurance-protection-eveil-complementaire-enfant-gratuit.pdf.md` | L'Éveil child protection guide offering free 12-month coverage for children with accident benefits and medical expense reimbursement. |
| `uv-fr-assurance-sommaire-des-protections-complementaires.pdf.md` | Summary of supplementary protections and riders including debt insurance, child coverage, premium waiver, and critical illness. |
| `uv-fr-assurance-vie-entiere-20-paiements-valeurs-elevees.pdf.md` | Whole life insurance guide for 20-payment high-value product with cash value accumulation and policy loan options. |
| `uv-fr-assurance-vie-guide-selection-des-risques-tarification.pdf.md` | Risk selection and underwriting guide for life insurance covering medical conditions, height/weight tables, and rating decisions. |
| `uv-fr-assurance-vie-individuelle-et-maladies-graves-proposition.pdf.md` | Individual life and critical illness insurance application form with personal information, medical questions, and advisor report. |
| `uv-fr-assurance-vie-permanente-adaptable-guide.pdf.md` | L'Adaptable permanent life insurance guide featuring two-chapter structure, flexible payment options, and guaranteed future insurability. |
| `uv-fr-assurance-vie-simplifiee-immediate-secrets.pdf.md` | Secrets guide for immediate simplified issue life insurance explaining premium calculations and medical condition acceptability. |
| `uv-fr-assurance-vie-temporaire-superieur-plus.pdf.md` | Superior+ term life insurance guide covering T-10 through T-30 products with renewal, exchange, and conversion rights. |
| `uv-fr-emission-simplifiee-aide-memoire-pour-les-16-a-80-ans.pdf.md` | Simplified issue cheat sheet for ages 16-80 showing medical conditions, eligibility criteria, and height/weight tables. |
| `uv-fr-questionnaire-d-admissibilite-emission-simplifiee-immediate.pdf.md` | Eligibility questionnaire for immediate simplified issue term life insurance with medical and lifestyle questions. |
| `uv-fr-questionnaire-d-admissibilite-emission-simplifiee.pdf.md` | Eligibility questionnaire for Express simplified issue covering permanent and term life products with medical screening questions. |

## Usage

### Via MCP Server (Recommended)
Access this documentation through our MCP server:
- **Endpoint:** `https://emma-insurance-docs-production.up.railway.app/mcp`
- **Available Tools:**
  - `search_docs` - Semantic search across all documentation
  - `list_libraries` - List all available insurance providers
  - `fetch_documentation` - Retrieve specific documents

### Search by Company
Navigate to the company folder (e.g., `Assomption/`, `Emma/`, `RBC/`, `UV/`)

### Search by Product Type
Use tags in frontmatter:
- `assurance-vie` - Life insurance
- `assurance-invalidite` - Disability insurance
- `maladies-graves` - Critical illness
- `emission-simplifiee` - Simplified issue

### Search by Document Type
Filter by `document_type` in frontmatter

## Key Features

- ✅ Structured metadata for AI/LLM retrieval
- ✅ Consistent document schema (v2.0)
- ✅ Bilingual field names (FR/EN)
- ✅ Machine-readable tables and data
- ✅ Comprehensive tagging system
- ✅ Cross-referenced glossaries

## Metadata Standards

**Schema Version:** 2.0

**Required Fields:**
- `document_id` - Unique identifier
- `document_type` - Classification
- `insurer` - Company information
- `product` - Product details
- `language` - fr-CA
- `tags` - Searchability keywords

## Coverage Information

- **Age ranges:** 0-85 years (varies by product)
- **Coverage amounts:** $1,000 - $5,000,000 CAD (varies by product)
- **Product types:** Life, Disability, Critical Illness, Riders (varies by product)
- **Underwriting types:** Full, Simplified, Guaranteed Issue (varies by product)

## License

Proprietary insurance documentation. All rights reserved by respective insurance companies.

## Last Updated

October 2025

---

**Note:** This documentation is for reference purposes. For current product offerings and terms, consult directly with the respective insurance companies.