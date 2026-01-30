# Coding Agent Instructions: 2026 Student Research Case Study - Actuaries in Space

## 1. Project Overview
**Title:** Actuaries in Space: The Pricing Frontier
**Date:** January 16, 2026
**Context:** It is the year 2175. Space travel and interstellar mining are established industries.
**Role:** Actuarial Team at **Galaxy General Insurance Company**.
**Client:** **Cosmic Quarry Mining Corporation**, a major interstellar mining company operating in multiple solar systems.
**Goal:** Response to an RFP to provide insurance coverage for Cosmic Quarry's expanding operations.

## 2. Key Entities & Solar Systems
### Galaxy General Insurance Company (The Insurer)
- Market leader in Galactic P&C insurance.
- Expertise in autonomous robotic mining, asteroid harvesting, and deep-space risks.
- Uses "Q-RISK Engine" (quantum risk assessment) and "Interplanetary Claims Grid".

### Cosmic Quarry Mining Corporation (The Client)
- Founded 2110 on Earth.
- Operates in:
    - **Helionis Cluster**: Stable star, 2 planets (temperate & cold/rocky), 2 asteroid clusters.
    - **Bayesia System**: Binary star (radiation spikes), 1 mining planet (high gravity, radiation), stable asteroid belt.
    - **Oryn Delta**: Dim dwarf star (low light), habitable zone mining, "asymmetric asteroid ring" (hazardous).
- **Financials (2174):** Net Revenue Đ 61.5B, Net Income Đ 14.8B.

### Other Systems (Contextual)
- **Zeta**: Yellow-white star, icy giant planet, chaotic outer belt.
- **Epsilon**: Bright/UV intense star, corrosive atmosphere planet.

## 3. Scope of Work (The 4 Hazard Areas)
You must design insurance products and pricing models for the following 4 coverages:
1.  **Equipment Failure**: Machinery breakdown (Quantum Bores, Graviton Extractors, etc.).
2.  **Cargo Loss**: Loss of ore/goods during transport between hubs.
3.  **Workers' Compensation**: Injury/death of biological staff (accidents, radiation, psychological stress).
4.  **Business Interruption**: Loss of revenue due to operational halts.

## 4. Data Description
You have access to 4 historical claims datasets (one per hazard).
*Note: All datasets likely contain `policy_id`, `solar_system`, `station_id`, `exposure`, `claim_count`, `claim_amount`.*

### A. Business Interruption
- **Key Vars**: `production_load`, `energy_backup_score` (1-5), `supply_chain_index`, `maintenance_freq`.
- **Unit**: Currency approx 28K - 1,426K.

### B. Cargo Loss
- **Key Vars**: `origin`, `destination` (Planets), `cargo_type` (Platinum, etc.), `weight`, `route_risk`, `solar_radiation`, `debris_density`.
- **Unit**: Millions of solar system currency.

### C. Equipment Failure
- **Key Vars**: `equipment_type` (e.g., Fusion Transport), `equipment_age`, `maintenance_int`, `usage_intensity`.
- **Unit**: Approx 11K - 790K.

### D. Workers' Compensation
- **Key Vars**: `occupation`, `psych_stress_index` (1-5), `gravity_level` (0.75-1.50), `safety_training_index`, `protective_gear_quality`.
- **Unit**: Approx 5K - 170K (Claim amount).

**New Business Data (Prospective Exposure):**
- You will need to price for the specific profile of Cosmic Quarry's operations in Helionis, Bayesia, and Oryn Delta using the provided "New Business Data" (found in spreadsheets/RFP data - *Agent Note: Verify if separate CSVs exist, otherwise rely on descriptions*).

## 5. Objectives & Requirements
Your Actuarial Report must address:

### A. Modeling & Quantitative Analysis
1.  **Aggregate Loss Distributions**: Short-term and Long-term ranges for Costs, Returns, and Net Revenue for each hazard.
2.  **Statistics**: Expected values, Variances, Tail behaviors (VaR/TVaR).
3.  **Stress Testing**: Extreme scenarios (e.g., 1-in-100 year events like solar storms affecting multiple systems).

### B. Product Design
- **Benefit Structures**: Deductibles, limits, coinsurance.
- **Triggers**: What events cause a payout?
- **Exclusions**: Specific hazards not covered.
- **Adaptability**: How the product scales for future risks.

### C. Qualitative & Strategic
- **Rationale**: Why include/exclude specific products?
- **Solar System Adaptation**: Tailor designs for the unique risks of Helionis (debris), Bayesia (radiation), Oryn Delta (low light/navigational hazards).
- **Social/Environmental (ESG)**: Optional but recommended.

## 6. Deliverable Format
- **Format**: PDF or Word (No macros).
- **Length**: Body **Maximum 10 pages** (1 inch margins, 12pt font).
- **Appendices**: Unlimited length, but main points **must** be in the body. Appendices are for supporting details/code.
- **Anonymity**: Team Name on file/cover. NO School Name or Student Names in the body/filename (only on cover/form).

## 7. Rules & Constraints
- **Team**: 2-5 students + 1 Faculty Advisor.
- **AI Policy**: Generative AI *can* be used but must be disclosed, documented, and validated. You are responsible for accuracy.
- **Originality**: Must be original work.
- **Deadline**: Submission by March 13, 2026 (3:00 PM CDT).

## 8. Tips for Success (from Podcast)
1.  **Audience**: Busy executives (some non-technical).
2.  **Communication**: Put **results first**, then support. Avoid "TL;DR".
3.  **Narrative**: Clear logic flow. Don't just show math; explain *why* it matters for the business.
4.  **Assumptions**: Clearly document all assumptions and their rationales (Critical!).
5.  **Creativity**: Distinguish your submission with innovative product features or risk insights.
6.  **Realism**: Data is "real-world" dirty. Clean it, manipulate it, explain it.

## 9. Next Steps for Agent
1.  Load the datasets (CSV/Excel files).
2.  Perform EDA (Exploratory Data Analysis) to understand risk drivers (e.g., does `solar_radiation` correlate with `cargo_loss`?).
3.  Fit frequency and severity models for each hazard.
4.  Simulate aggregate losses for the 3 solar systems based on their specific risk profiles (e.g., higher radiation in Bayesia).
5.  Draft the 10-page report focusing on business recommendations.
