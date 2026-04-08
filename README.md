# Canadian-Food-Regulatory-Compliance-Audit

Regulatory compliance assessment of 10 PepsiCo Canada consumer food products against Canadian Food & Drug Regulations (FDR), CFIA labelling requirements, and the 2026 Front-of-Package (FOP) nutrition symbol rules.

> **Disclaimer:** This is an independent educational audit conducted for skills demonstration purposes. Findings are based on publicly available product labels purchased in Ontario, Canada (April 2026).

## Background

On January 1, 2026, Health Canada's amendments to the Food and Drug Regulations took full effect, requiring mandatory Front-of-Package (FOP) nutrition symbols on prepackaged foods high in saturated fat, sugars, or sodium (≥15% Daily Value). This project audits 10 products for compliance with this and other Canadian labelling requirements.

## Products Audited

| # | Product | Category |
|---|---------|----------|
| 1 | Lay's Classic Potato Chips | Snack |
| 2 | Doritos Nacho Cheese Tortilla Chips | Snack |
| 3 | Tostitos Scoops Tortilla Chips | Snack |
| 4 | Quaker Instant Oatmeal (Maple & Brown Sugar) | Cereal |
| 5 | Quaker Chewy Granola Bar (Chocolate Chip) | Snack |
| 6 | Tropicana Pure Premium Orange Juice | Beverage |
| 7 | Gatorade Lemon-Lime | Beverage |
| 8 | Ruffles All Dressed Potato Chips | Snack |
| 9 | SunChips Harvest Cheddar | Snack |
| 10 | Miss Vickie's Sea Salt & Malt Vinegar | Snack |

## Assessment Categories

Each product was assessed across 6 regulatory categories:

1. **Ingredient Statement** — FDR B.01.008.2 compliance (descending order, common names, sugar grouping, bilingual)
2. **Nutrition Facts Table** — FDR B.01.350 compliance (mandatory nutrients, serving size, % DV)
3. **FOP Nutrition Symbol** — Health Canada FOP amendments (≥15% DV threshold for sat fat, sugars, or sodium)
4. **Allergen Declaration** — FDR B.01.010.1 compliance (12 priority allergens, "Contains:" statement)
5. **Claims Substantiation** — FDR B.01.503 (nutrient content claims verified against thresholds)
6. **Bilingual Compliance** — FDR/SFCR (English and French)

## Key Findings
 
**FOP Symbol Requirement:**
- **5 out of 10 products** require the mandatory Front-of-Package nutrition symbol under Health Canada's January 2026 amendments
- **Sodium** is the primary trigger (Doritos 16% DV, Ruffles 18% DV, Miss Vickie's 18% DV)
- **Sugars** trigger FOP for beverages (Tropicana 22% DV, Gatorade 34% DV)
- Notably, Tropicana 100% orange juice triggers FOP for **naturally occurring sugars** — the regulation does not distinguish between natural and added sugars in its threshold calculation
- Products manufactured before January 1, 2026 may still be on shelves without the FOP symbol under CFIA's transition policy, which permits products packaged before the deadline to remain in market
 
**Allergen Compliance:**
- All 10 products assessed were compliant with FDR B.01.010.1 priority allergen declaration requirements
- Miss Vickie's Sea Salt & Malt Vinegar contains **lactose** (first ingredient in seasoning) — a milk derivative — and correctly declares "Contains Milk and Barley Ingredients" on the Canadian label. This demonstrates proper cross-referencing between ingredient list and allergen declaration for derivative ingredients
- Quaker Chewy Chocolatey Chip includes a comprehensive "May contain" precautionary statement covering 4 additional priority allergens (tree nuts, peanuts, sesame) beyond the 3 declared in the "Contains" statement
 
**Claims Substantiation:**
- All nutrient content claims across the 10 products were substantiated against FDR thresholds
- SunChips "High Source of Fibre" claim verified at exactly 4g fibre per serving (16% DV) — the minimum threshold under FDR for this claim level
- Quaker Oatmeal health claim regarding cholesterol reduction from oat fibre is linked to beta-glucan content, requiring ≥0.75g per serving — consistent with 43g whole grain oat serving
 
**Compliance Summary:**
 
| Category | Compliant | Assessed | Rate |
|----------|-----------|----------|------|
| Ingredient Statement | 10 | 10 | 100% |
| Nutrition Facts Table | 10 | 10 | 100% |
| Allergen Declaration | 10 | 10 | 100% |
| FOP Symbol | 5 | 5 | Pending* |
| Claims Substantiation | 10 | 10 | 100% |
| Bilingual Compliance | 10 | 10 | 100% |
 
*FOP compliance pending in-store verification of symbol presence on current packaging. Products manufactured before January 1, 2026 may lawfully remain on shelves without the symbol under CFIA transition rules.


## Methodology

Standardized assessment procedure documented in [SOP-REG-001](docs/SOP-REG-001.pdf). Non-conformances documented using CAPA reports with 5 Whys root cause analysis.

## Deliverables

| Document | Description |
|----------|-------------|
| [Compliance Matrix](data/Compliance-Matrix.pdf) | Full audit results across 6 categories |
| [Python Analysis](analysis/Canadian_Food_Label_Compliance_Analysis.ipynb) | Compliance visualizations |
| [SOP-REG-001](docs/SOP-REG-001.pdf) | Standardized assessment procedure |
| [CAPA-2026-001](docs/CAPA-2026-001.pdf) | Allergen declaration finding |
| [CAPA-2026-002](docs/CAPA-2026-002.pdf) | FOP symbol compliance finding |
| [Label Photos](label-photos/) | Evidence photographs |

## Regulations Referenced

- Food and Drugs Act (FDA) & Food and Drug Regulations (FDR)
- Safe Food for Canadians Act (SFCA) & Regulations (SFCR)
- CFIA Industry Labelling Tool
- Health Canada FOP Nutrition Symbol Amendments (Canada Gazette Part II, July 2022)

## Skills Demonstrated

Canadian Food & Drug Regulations (FDR) | CFIA compliance assessment | FOP nutrition symbol analysis | Priority allergen declaration review | Nutrient content claims substantiation | Root cause analysis (5 Whys) | CAPA documentation | SOP development | Python (Pandas, Matplotlib)

## Author

**Simran Saran**
B.Sc. Biochemistry, Minor in Computing & Bioinformatics — University of Waterloo| s4saran@uwaterloo.ca
"""
