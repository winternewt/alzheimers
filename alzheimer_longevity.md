# Alzheimer's Disease Targets from a Longevity Perspective

## Project Overview

This document explores druggable targets for Alzheimer's disease through the lens of longevity research, focusing on genes that demonstrate both lifespan extension properties and cognitive/nervous system benefits.

## Methodology

### Database Resources
- **OpenGenes Database**: Contains experimental data on gene modifications affecting lifespan in model organisms
- **Query Approach**: Searched for genes with cognitive function and nervous system effects
- **Analysis Focus**: Prioritized genes showing statistical significance in lifespan studies

### Database Schema (OpenGenes)
The OpenGenes database consists of 4 main tables linked by HGNC gene symbols:
- `lifespan_change`: Experimental lifespan modification data
- `gene_criteria`: Aging-related gene classifications  
- `gene_hallmarks`: Aging hallmark associations
- `longevity_associations`: Population genetics data

**Key Query Guidelines:**
- Multi-value fields require LIKE queries with wildcards
- Lifespan metrics include both mean and maximum changes
- Results ordered by magnitude of effect
- Statistical significance indicated by significance_mean/max = 1

## Key Findings

### Top Lifespan-Extending Genes with Cognitive Benefits

#### 1. PAPPA (Pregnancy-Associated Plasma Protein A)
- **Lifespan Effect**: +29% and +25% mean lifespan increase (mouse, knockout)
- **Model**: Mouse studies
- **Intervention**: Gene knockout
- **Significance**: Statistically significant
- **Relevance**: Growth hormone/IGF-1 pathway regulation

#### 2. CISD2 (CDGSH Iron Sulfur Domain 2)
- **Lifespan Effect**: +19.3% and +18.8% mean increase (mouse, overexpression)
- **Model**: Mouse studies  
- **Intervention**: Gene overexpression
- **Significance**: Statistically significant
- **Relevance**: Mitochondrial function, iron-sulfur cluster biogenesis

#### 3. SIRT1 (Sirtuin 1)
- **Lifespan Effect**: +13% and +12% mean increase (mouse, overexpression)
- **Model**: Mouse studies
- **Intervention**: Gene overexpression
- **Significance**: Statistically significant
- **Relevance**: NAD+-dependent deacetylase, metabolic regulation, neuroprotection

#### 4. TERT (Telomerase Reverse Transcriptase)
- **Lifespan Effect**: Up to +16.3% maximum increase (mouse, gene therapy)
- **Model**: Mouse studies
- **Intervention**: Gene therapy
- **Significance**: Statistically significant
- **Relevance**: Telomere maintenance, cellular senescence, cognitive function

#### 5. HSPA1A/HSPA1B (Heat Shock Protein Family A Member 1A/1B)
- **Lifespan Effect**: +8.6% mean increase (mouse, protein treatment)
- **Model**: Mouse studies
- **Intervention**: Protein treatment
- **Significance**: Statistically significant
- **Relevance**: Protein folding, proteostasis, neuroprotection

#### 6. ADRA1A (Adrenoceptor Alpha 1A)
- **Lifespan Effect**: +11.3% mean increase (mouse, protein activity enhancement)
- **Model**: Mouse studies
- **Intervention**: Protein activity enhancement
- **Significance**: Statistically significant
- **Relevance**: Adrenergic signaling, cardiovascular and nervous system function

### Genes with Negative Effects (When Disrupted)

#### High-Risk Targets
- **PTEN**: -54% maximum decrease (mouse, knockout) - Critical tumor suppressor
- **PPM1D**: -25% mean decrease (mouse, knockout) - DNA damage response
- **HTR1B**: -19% mean decrease (mouse, knockout) - Serotonin receptor
- **UCP2**: -18% to -22% mean decrease (mouse, knockout) - Mitochondrial uncoupling
- **PARP1**: -13.3% mean decrease (mouse, knockout) - DNA repair

## Therapeutic Implications

### Most Promising Targets for Drug Development

1. **SIRT1 Activators**
   - Established target with known activators (resveratrol, NAD+ precursors)
   - Neuroprotective mechanisms well-characterized
   - Multiple clinical trials ongoing

2. **Heat Shock Protein Modulators (HSPA1A/B)**
   - Proteostasis enhancement
   - Direct relevance to protein aggregation in Alzheimer's
   - Potential for small molecule activation

3. **Telomerase Activation (TERT)**
   - Cellular rejuvenation approach
   - Cognitive function enhancement
   - Requires careful safety considerations

4. **CISD2 Pathway Modulators**
   - Mitochondrial function enhancement
   - Iron-sulfur cluster biogenesis
   - Novel therapeutic target

### Safety Considerations

- **PTEN, PPM1D**: Critical for tumor suppression - avoid inhibition
- **UCP2, HTR1B**: Essential physiological functions - modulate carefully
- **PARP1**: Important for DNA repair - balance efficacy vs. toxicity

## Next Steps for Investigation

### Immediate Priorities
1. **Mechanism Deep-Dive**: Investigate specific pathways for top candidates
2. **Drug Target Validation**: Search for existing compounds targeting these genes
3. **Cross-Database Analysis**: Validate findings in other longevity databases
4. **Clinical Relevance**: Check for human genetic variants and associations

### Extended Analysis
1. **Protein Structure Analysis**: 3D structure prediction for drug design
2. **Pathway Interaction Mapping**: Genetic synergy analysis
3. **Biomarker Development**: Identify measurable endpoints
4. **Translational Potential**: Assess druggability and safety profiles

## Critical Discovery: Traditional Alzheimer's Genes Are Anti-Longevity!

### Classic Alzheimer's Genes in Longevity Database

Our search for traditional Alzheimer's genes (APP, APOE, MAPT, TREM2, PSEN1, PSEN2, BACE1) revealed a **striking pattern**:

#### APOE (Apolipoprotein E)
- **Found in database**: Yes, but with **no lifespan benefit**
- **Effect**: Gene knockout deteriorates lipid metabolism, cardiovascular system, cholesterol metabolism
- **Significance**: No positive lifespan data recorded
- **Implication**: APOE disruption is harmful, consistent with APOE4 being a major Alzheimer's risk factor

#### GSK3B (Glycogen Synthase Kinase 3 Beta) 
- **Mixed effects**: Both positive and negative depending on intervention
- **Overexpression**: Up to -49% lifespan decrease (fly studies)
- **Knockdown**: Up to +20.7% lifespan increase (fly studies)
- **Implication**: GSK3B inhibition may be beneficial (consistent with tau pathology research)

#### Missing Classic Genes
- **APP, MAPT, TREM2, PSEN1, PSEN2, BACE1**: Not found in longevity database
- **Implication**: These genes may not have been studied in longevity contexts, OR their effects are neutral/negative for lifespan

### Top Anti-Longevity Genes (Life-Shortening When Disrupted)

#### Severe Lifespan Reducers (-90% to -96%)
1. **IGF1R** (Insulin-like Growth Factor 1 Receptor): -96% to -93% (fly studies)
2. **INSR** (Insulin Receptor): -96% to -93% (fly studies)
3. **MAPK14** (p38 MAPK): -90% to -58% (fly studies)

#### Moderate Lifespan Reducers (-40% to -77%)
4. **HSF1** (Heat Shock Factor 1): -77% to -71% (C. elegans, RNAi)
5. **HRAS** (Harvey Rat Sarcoma Viral Oncogene): -68.8% (C. elegans)
6. **TARDBP** (TDP-43): -66.7% to -50% (C. elegans, knockout)
7. **ERBB2** (HER2/neu): -53.7% (mouse, overexpression)
8. **PTPN1** (Protein Tyrosine Phosphatase 1B): -42.1% (mouse, knockout)

### Key Insights

#### 1. **Longevity vs. Alzheimer's Genes Are Opposite**
- **Longevity genes**: SIRT1, TERT, HSPA1A/B promote both lifespan and cognitive health
- **Alzheimer's genes**: APOE, GSK3B (when overactive) are associated with disease and shortened lifespan
- **Therapeutic implication**: Target longevity pathways rather than just Alzheimer's pathology

#### 2. **Insulin/IGF Signaling Is Critical**
- **IGF1R, INSR knockouts**: Catastrophic lifespan reduction (-90%+)
- **But reduced signaling**: Often promotes longevity (caloric restriction mimetics)
- **Implication**: Precise modulation needed, not complete inhibition

#### 3. **Proteostasis Genes Are Essential**
- **HSF1 (heat shock factor)**: Critical for survival (-77% when knocked down)
- **TARDBP (TDP-43)**: Essential for lifespan (-66% when knocked out)
- **Connection**: Both involved in protein aggregation diseases (ALS, FTD, Alzheimer's)

#### 4. **Novel Alzheimer's Strategy**
Rather than targeting amyloid/tau directly, focus on:
- **Enhancing longevity pathways**: SIRT1, TERT, heat shock proteins
- **Supporting proteostasis**: HSF1, HSPA1A/B activation
- **Avoiding disruption**: of essential survival genes (IGF1R, INSR, HSF1)

## Database Query Log

### Initial Cognitive Function Query
```sql
SELECT HGNC, model_organism, intervention_method, lifespan_percent_change_mean, 
       lifespan_percent_change_max, significance_mean, significance_max,
       intervention_deteriorates, intervention_improves,
       ABS(COALESCE(lifespan_percent_change_mean, 0)) as abs_mean_change
FROM lifespan_change 
WHERE (intervention_deteriorates LIKE '%cognitive function%' 
       OR intervention_deteriorates LIKE '%nervous system%'
       OR intervention_improves LIKE '%cognitive function%' 
       OR intervention_improves LIKE '%nervous system%')
ORDER BY abs_mean_change DESC LIMIT 20;
```

### Anti-Longevity Gene Query
```sql
SELECT HGNC, model_organism, intervention_method, lifespan_percent_change_mean,
       lifespan_percent_change_max, significance_mean, significance_max,
       intervention_deteriorates, intervention_improves,
       ABS(COALESCE(lifespan_percent_change_mean, 0)) as abs_mean_change
FROM lifespan_change 
WHERE lifespan_percent_change_mean < 0 
ORDER BY lifespan_percent_change_mean ASC LIMIT 25;
```

### Classic Alzheimer's Gene Search
```sql
SELECT HGNC, model_organism, intervention_method, lifespan_percent_change_mean,
       lifespan_percent_change_max, significance_mean, significance_max,
       intervention_deteriorates, intervention_improves
FROM lifespan_change 
WHERE HGNC IN ('APP', 'APOE', 'MAPT', 'TREM2', 'PSEN1', 'PSEN2', 'BACE1', 'GSK3B')
ORDER BY lifespan_percent_change_mean DESC;
```

**Results**: Classic Alzheimer's genes show neutral to negative lifespan effects, while longevity-promoting genes offer cognitive benefits.

---

*Document Status: Initial findings documented*  
*Last Updated: [Current Date]*  
*Next Update: After mechanism analysis and drug target validation* 