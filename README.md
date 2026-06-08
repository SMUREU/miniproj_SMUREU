# SMU Data Science REU 2026 Mini Project
## Project Requirements
*Taken from [python_bootcamp/data_storytelling_project.md](https://github.com/gw3ntd/python_bootcamp/blob/main/data_storytelling_project.md)*  
- For this project, I will create a short data story inspired by the work of organizations such as The Pudding
- The goal is not to build the most advanced model or analyze the largest dataset
- Instead, the goal is to investigate an interesting question, use data as evidence, and communicate my findings clearly
- Create an 8-minute presentation that tells a compelling story using data

**My project should demonstrate the major stages of the data science workflow:**
1. Question Formulation
2. Data Collection
3. Data Cleaning
4. Analysis
5. Visualization
6. Interpretation

**My project must:**
- Investigate a question that can be answered with data
- Use a dataset large enough to support analysis
- Include at least two original visualizations
- Use Python for some portion of the analysis
- Cite all datasets and external sources
- Be reproducible by another student
*Projects do not need to use advanced statistics or machine learning*

## My Project
- Which features best explain gun ownership in America?
### My Data
*The following is what my data table looks like*
|Index|Geography|LocYear|%>=HS|%>=Bachelor's|Pov for 25yo<=, <HS|Pov for 25yo<=, >=Bachelor's|GeoFIPS|HFR|SNAP_rate|DPI_rate|PI_rate|
|---|---|---|---|---|---|---|---|---|---|---|---|
|n|geographic identifier|State Abbreviation + Year|Percent high school graduate or higher|	Percent bachelor's degree or higher|Poverty rate for the population 25 years and over for whom poverty status is determined by educational attainment level, less than high school graduate|Poverty rate for the population 25 years and over for whom poverty status is determined by educational attainment level, bachelor's degree or higher|geographic FIPS code|Factor scores for household firearm ownership latent factor|people who get CashPublicAssistanceORFoodStamps/SNAP divided by total population|Disposable Personal Income / total population|Personal Income / total population|
|...|...|...|...|...|...|...|...|...|...|...|...|
