# ComKnow-UBEM
This is a documentation for the questionnaire and Grasshopper workflow used for collecting community knowledge and perform community knowledge-based UBEM simulation. 
## Content: 
- **Household_Information_Survey_questionnaire_preview.pdf**: Preview of the questionnaire used to collect community knowledge from householders. The questionnaire is built with jotform. Access to the questionnaire: https://form.jotform.com/251915919185063.
- **pipeline_questionnaire.gh**: The main workflow used to process the submission of the questionnaire and perform UrbanOPT simulation. The workflow is built mainly with Ladybug tools, and its operation require the installations of Rhino, Ladybug plugin, Honeybee plugin, Dragonfly plugin, and UrbanOPT CLI. 
- **Household_Information_Survey_submission_template.csv**: The template for questionnaire submissions with one submission instance. The input for grasshopper workflow will be in such format. 
- **Household_Information_Survey_submission_sample.csv**: The samplate file that documents the building characteristics used in the simulation for the case study community in the city of Worcester

## How to use: 
1. **Get system prepared**:
    - Install Rhino 7 or 8
    - Install grasshopper plugins through https://app.pollination.solutions/cad-plugins
    - Install UrbanOPT CLI through https://docs.urbanopt.net/installation/installation.html
      
2. **Process questionnaire submissions with the workflow**:
    - Download the questionnaire submissions on jotform as CSV file, the submission file will be named as "Household_Information_Survey.csv"
    - Open the pipeline_questionnaire.gh workflow with grasshopper and following the instruction