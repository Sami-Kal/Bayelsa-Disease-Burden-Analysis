**BAYELSA STATE DISEASE BURDEN ANALYSIS 2013 - 2023**

**Table Of Content**

•	The Story Behind the Data

•	Project Overview

•	Business Problem

•	Project Objectives

•	Datasets

•	Tools and technology

•	Data Preparation

•	Dashboard Pages

•	Key Insights

•	Recommendations

•	Public Health value

•	Limitations

•	References

**THE STORY BEHIND THE DATA**

In 2013, a little over a decade, the story of disease in Bayelsa was, in many ways, a common Niger Delta story. Malaria reigned supreme, as it had for generations. The entire landscape is characterised by swamp, dense vegetation, occasional flooding, and stagnant water. The environment in a nutshell is a fertile breeding ground for the culprit; the female anopheles’ mosquitoes.

Children died from diarrheal diseases carried in unsafe water. Neonatal deaths were painfully common in communities where skilled birth attendance was a privilege. Meningitis outbreak was on rampage. Lower respiratory infections claimed lives that antibiotics could have saved. These are all familiar enemies, and the sustained war against them is as old as their exploit. However, something began shifting beneath the surface.

By 2023, a decade of quiet transformation had reshaped Bayelsa’s disease landscape in ways that are both remarkable and alarming. The old enemies had not disappeared but they had retreated, driven back by years of immunization campaigns, malaria control programs, improved sanitation efforts, and expanded primary healthcare access. For the first time, Diarrheal disease deaths had fallen 43 per 100,000 people. Malaria, still present and dangerous, had dropped from the summit it had held for years. The infectious disease burden, while far from defeated, was finally measurably yielding ground. Yet in their wake, a new and more insidious threat had risen.

Ischemic Heart Disease, once an afterthought in Bayelsa’s health planning, ranked 7th in 2013, had by 2023 become the leading cause of death in the state. Stroke was climbing. Chronic Kidney Disease had entered the top 10 where it had never featured before. These are diseases of lifestyle, urbanization and dietary change. Diseases that thrive in communities shifting from subsistence living to sedentary urban lifestyle, from fresh local foods to processed alternatives. Bayelsa had, in one decade, begun crossing a threshold that took high-income countries generation to traverse. 

This dashboard tells that story. Not just in numbers, but in what those numbers mean for the Bayelsa people, and for the public health planners, policymakers, and healthcare workers who must now fight a war on two fronts: finishing the battles against the old enemies while preparing defence against the new ones.

**PROJECT OVERVIEW**

This project analyses the top 10 causes of death and top 10 causes of disability (DALYs) in Bayelsa state between 2013 and 2023. The data used was sourced from the Global Burden of Disease (GBD) study 2023 published by the Institute for Health Metrics and Evaluation (IHME). The findings are benchmarked against 8 peer Nigeria states and a global Low-Middle SDI comparison group.
The analysis is presented through a 6-page interactive Power BI dashboard designed to inform public health planning, resource allocation, and evidence-based policy decision at the state level.

**BUSINESS PROBLEM**

The state Ministry of Health and other health policy makers require evidence-based answers to the following critical questions:
1.	What is the leading cause of death and disability in Bayelsa state as at 2023?
2.	How has the disease burden changed over the past decade?
3.	Which diseases are worsening and which are improving?
4.	Is Bayelsa experiencing an epidemiological transition towards NCDs?
5.	What risk factors are driving the emerging NCD burden?
6.	How does Bayelsa’s burden compare to peer Nigeria states and global development peers?
7.	Where should limited healthcare resources be targeted for maximum impact?
Without these insights, healthcare policy-makers risk:
1.	Continuing to invest in declining threats while emerging ones go unaddressed
2.	Missing the window for early NCD prevention before the burden becomes entrenched
3.	Failing to track progress toward Nigeria’s health sector development goals
4.	Inability to make the evidence-based for increased funding

**PROJECT OBJECTIVES**

1.	Identify the top 10 leading causes of death in Bayelsa state in 2023
2.	Track rank and absolute changes of DALYs in causes of death between 2013 and 2023
3.	Identify the top 10 causes of DALYs and measure their 10-year improvement
4.	Analyse the top 10 risk factors driving the disease burden
5.	Benchmark the Bayelsa’s burden against 8 peer Nigerian states and the global Middle SDI group
6.	Classify all conditions as Worsening or Improving based on decade-long trends
7.	Develop evidence-based public health recommendations grounded in the data
8.	Present findings through a 6-page executive Power BI dashboard

**DATASET**

•	Data Source: Global Burden of Disease (GBD) Study 2023 - IHME
•	Location: Bayelsa State, Nigeria.
•	Period: 2013 – 2023h
•	Access: GDB Results Tool
•	Citation: GBD 2023 Collaborators. The Lancet. 2025. https://doi.org/10.1016/S0140-6736(25)01637-X

**FILE USED**

Files	Descriptions
1.	Bayelsa-deaths-rank-chart.csv	Top 10 causes of death - 2023 rank and absolute change per 100k from 2013
2.	Bayelsa-daly-rank-chart.csv	Top 10 risk factors — 2023 rank and DALYs change per 100k
3.	Bayelsa-benchmark-table-DALY.csv	DALYs rankings - Bayelsa vs 8 peer states and SDI comparison group
4.	Bayelsa-daly-hcbar-chart.csv	Top 10 DALYs causes — 2023 rank and % change from 2013
5.	Bayelsa_Combined_Summary.csv	Unified summary of deaths, DALYs and risk factor data
6.	Bayelsa_Disease_Burden_Master.xlsx	Master Excel workbook — all 5 datasets cleaned and structured
	
**KEY VARIABLES**

**Variables	Description**

1.	cause / risk	Disease name or risk factor
2.	Cause type	Category: Communicable, NCD, or Injuries
3.	rank_2013	Burden ranking in 2013
4.	rank_2023	Burden ranking in 2023
5.	rank change	Shift in ranking over the decade
6.	change	Absolute or percentage change in burden
7.	 trend	Worsening or Improving

**TOOLS AND TECHNOLOGIES**

•	Microsoft Excel

•	Power BI

•	Power Query

•	DAX

•	GBD Results Tool

**DATA PREPARATION**

1.	Downloaded 4 datasets from the GBD Results Tool
2.	Cleaned and standardized column headers
3.	Computed rank change column - (2023 rank minus 2013 rank)
4.	Created trend classification - (Worsening or Improving)
5.	Created improvement category column for DALYs data
6.	Added trend column to Risk Factors dataset
7.	Removed citation footnote rows causing null values
8.	Merged all datasets into a single Combined Summary table
9.	Built master Excel workbook with 5 structured sheets
10.	Connected to Power BI and created 22 DAX measures
11.	Applied conditional formatting throughout dashboard

**DASHBOARD PAGES**

Page 1 - Executive Overview: High-level summary of Bayelsa's disease burden for executive and policy stakeholders.

Page 2 - Death Trend Analysis: Tracks the full trajectory of Bayelsa's top 10 causes of death between 2013 and 2023.

Page 3 – DALYs Burden Analysis: Examines the total combined burden of death and disability.

Page 4: State Benchmarking: Benchmarks Bayelsa against 8 peer Nigerian states and the global Low-Middle SDI comparison group.

Page 5: Risk Factor Analysis: Identifies the behavioural, metabolic and environmental risks driving Bayelsa's disease burden

Page 6: Health Insights and Recommendations: Synthesizes all findings into a cohesive evidence-based action plan. Features the epidemiological transition alert, public health progress statement, benchmarking alert, full recommendations table and full data source citation.

**KEY INSIGHTS**

1. The Epidemiological Transition: Bayelsa State has crossed a historic threshold. Ischemic Heart Disease rose from rank 7 in 2013 to become the number one cause of death in 2023, overtaking Malaria which had dominated for generations. Three NCDs now occupy the top 10 causes of death and all are worsening simultaneously. This is our current reality.
2. Communicable Diseases are been contained but Not Gone: Every communicable disease in the top 10 deaths list showed improvement over the decade. Diarrheal diseases recorded the largest absolute reduction resulting to 43.4 fewer deaths per 100,000 people. Malaria deaths fell by 24.4 per 100,000. These gains represent years of sustained public health effort and must be protected, not abandoned, as attention shifts to NCDs.
3. All DALYs Conditions Improved: All 10 leading causes of disability-adjusted life years showed measurable improvement between 2013 and 2023. This is a remarkable public health achievement for a state that only 27 years ago did not exist as an administrative entity. Diarrheal diseases led with an 81.2% reduction in DALYs — the strongest single improvement across the entire analysis.
4. Neonatal Disorders Carry a Hidden Burden: While Neonatal Disorders ranks 4th in deaths, it ranks 1st in DALYs. This means many new-borns are surviving but carrying significant lifelong disability which is a hidden burden that mortality statistics alone cannot reveal. The gap between the death rank and DALYs rank is the widest of any condition in the analysis.
5. Metabolic Risks Are Fuelling the NCD Rise: Six of the top 10 risk factors are worsening, and five of the six are metabolic: High Blood Pressure, High BMI, High Fasting Plasma Glucose, High LDL and Kidney Dysfunction. These are the upstream drivers of the downstream NCD deaths. Without addressing these risk factors at the community level, NCD mortality will continue to climb regardless of how well hospitals treat the consequences.
6. Bayelsa's Malaria Burden Is Disproportionate to Its Development Level: While global Low-Middle SDI peers rank Malaria only 20th in DALYs burden, Bayelsa ranks it 1st. This extraordinary gap reflects the unique ecological reality of the Niger Delta where perennial flooding, dense vegetation and inadequate drainage create near-permanent conditions for malaria transmission that defy the level of control achieved elsewhere at similar development stages.
7. Road Injuries: Road injuries appear in the top 10 DALYs causes but not in the top 10 deaths list indicating significant disability from road traffic injuries that stops short of fatality. This invisible burden demands public health attention beyond the hospital emergency room.

**RECOMMENDATIONS**

1.	Establish NCD screening and prevention programs at all PHC facilities.
2.	Sustain meningitis vaccination and outbreak preparedness.
3.	Strengthen neonatal emergency care and skilled birth attendance across all LGAs.
4.	Sustain and expand malaria control programs. Do not reduce investment in the face of NCD transition.
5.	Address metabolic risk factors through community-based lifestyle intervention programs.
6.	Collaborate with transport authorities on road safety.
7.	Develop a congenital defect registry and early intervention program
8.	Continue TB and HIV/AIDS control programs

**LIMITATIONS**

•	Data derives from GBD modelled estimates and not direct facility surveillance from Bayelsa State health facilities. Actual figures may differ from modelled estimates, particularly for conditions with limited reporting infrastructure.

•	Analysis covers all ages combined. Therefore, age-disaggregated analysis would provide additional depth for targeted intervention planning.

•	LGA-level data is not available in the current GBD subnational dataset. Therefore, all findings reflect state-level aggregates.

•	The benchmark comparison uses DALYs rankings not absolute values. Therefore, ranking differences do not directly translate to proportional burden differences

•	GBD subnational estimates for Nigeria carry wider uncertainty intervals than national-level estimates due to data sparsity at the state level

**REFERENCE**

•	GBD 2023 Collaborators. *Burden of 375 diseases and injuries, risk-attributable burden of 88 risk factors, and healthy life expectancy in 204 countries and territories, including 660 subnational locations, 1990–2023: a systematic analysis for the GBD Study 2023.* The Lancet. 2025. https://doi.org/10.1016/S0140-6736(25)01637-X 

•	Institute for Health Metrics and Evaluation (IHME). *GBD Results Tool.* Seattle, WA: IHME, 2024. https://healthdata.org/data-visualization/gbd-results


