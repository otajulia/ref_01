# Text-to-Reference Match (Direct Content Mapping)

## Scope
- Base text: `manuscript_with_citations_35.txt`
- Reference list: `references_bmc_35.txt`
- Goal: show whether each key manuscript claim is supported by cited references.

## Claim-Level Matching
1. Claim: Low physical activity increases chronic disease burden and mortality.  
   Manuscript location: Background para 1.  
   Evidence refs: [1], [2], [3], [4].  
   Why it matches: These are large meta-analyses/systematic reviews quantifying dose-response links between physical inactivity (or lower activity) and NCD incidence/mortality.

2. Claim: Physical inactivity contributes materially to healthcare expenditure.  
   Manuscript location: Background para 1.  
   Evidence refs: [5], [6], [7].  
   Why it matches: Global burden and cost-of-inaction analyses plus systematic review of healthcare-cost impact.

3. Claim: International guideline supports regular physical activity across lifespan.  
   Manuscript location: Background para 1.  
   Evidence refs: [8].  
   Why it matches: WHO 2020 guideline consensus paper.

4. Claim: CRF can be considered a clinical vital sign and predicts prognosis.  
   Manuscript location: Background para 2.  
   Evidence refs: [9], [10], [11].  
   Why it matches: AHA statement and foundational prospective/meta-analytic CRF outcome evidence.

5. Claim: Higher CRF is linked to lower healthcare costs.  
   Manuscript location: Background para 2; Discussion para 1.  
   Evidence refs: [12], [13], [14].  
   Why it matches: Direct healthcare-cost analyses using exercise-testing cohorts (including diabetes subgroup).

6. Claim: Lower activity is associated with higher healthcare utilization.  
   Manuscript location: Background para 2.  
   Evidence refs: [15].  
   Why it matches: Health economics study directly evaluating inactivity and utilization.

7. Claim: Handgrip strength is a strong prognostic marker.  
   Manuscript location: Background para 3; Discussion para 2.  
   Evidence refs: [16], [17].  
   Why it matches: Large multinational cohort and meta-analysis showing robust associations with mortality/CVD outcomes.

8. Claim: Weak grip and poor TUG are associated with higher hospitalization costs in older adults.  
   Manuscript location: Background para 3; Discussion para 2.  
   Evidence refs: [18].  
   Why it matches: Population-based cost study with handgrip and TUG predictors.

9. Claim: Functional mobility tests (TUG/6MWT/gait speed/Figure-of-8) are valid and clinically informative.  
   Manuscript location: Background para 3; Discussion para 2.  
   Evidence refs: [19], [20], [21], [22], [23].  
   Why it matches: Original/validation and prognostic studies for mobility and function tests.

10. Claim: Balance-focused exercise prevents falls; falls are high-cost events.  
    Manuscript location: Background para 3; Discussion para 2.  
    Evidence refs: [24], [25].  
    Why it matches: Cochrane review on fall-prevention exercise and economic burden of falls.

11. Claim: Frailty mechanism explains higher expenditure with low function.  
    Manuscript location: Background para 4; Discussion para 3.  
    Evidence refs: [26], [27], [28].  
    Why it matches: Frailty phenotype model and clinical/public-health implications literature.

12. Claim: Gamma-log GLM is appropriate for skewed healthcare cost outcomes.  
    Manuscript location: Methods, Statistical analysis.  
    Evidence refs: [29].  
    Why it matches: Canonical health-econometric modeling guidance for log/cost models.

13. Claim: NHIS-based Korean national claims/screening cohorts are valid infrastructure for linkage analyses.  
    Manuscript location: Methods, Study design and data sources.  
    Evidence refs: [30], [31], [32].  
    Why it matches: Official cohort/data resource profile papers for NHIS databases.

14. Claim: NFA100-derived functional fitness metrics are usable for Korean population modeling.  
    Manuscript location: Methods, Study design and data sources.  
    Evidence refs: [33], [34].  
    Why it matches: NFA-based Korean studies reporting functional fitness modeling and cohort utility.

15. Claim: Ethical framework follows Declaration of Helsinki.  
    Manuscript location: Methods, Ethics.  
    Evidence refs: [35].  
    Why it matches: Standard global ethics statement document.

## Consistency Verdict
- Overall verdict: `Matched`.
- Practical note: This mapping supports scientific consistency of the manuscript narrative and the 35-reference list at claim level (background, methods rationale, discussion interpretation).

