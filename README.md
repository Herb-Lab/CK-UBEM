# ComKnow-UBEM
This is a documentation for the Grasshopper workflow, questionnaire, and HVAC selection map used for collecting community knowledge and perform community knowledge-based UBEM simulation. 
## Content: 
- **community_knowledge_collecting_questionnaire_preview.pdf**: Preview of the questionnaire used to collect community knowledge from householders. The questionnaire is built with jotform. Access to the questionnaire: https://form.jotform.com/251915919185063.
- **pipeline.gh**: The main workflow used to process the submission of the questionnaire to inputs for UrbanOPT simulation. The workflow is built mainly with Ladybug tools, and its operation require the installations of Rhino, Ladybug plugin, Honeybee plugin, Dragonfly plugin, and UrbanOPT CLI. 
- **community_knowledge_collecting_questionnaire_submission_template.csv**: The template for questionnaire submiisions with one submission instance. The input for grasshopper workflow will be in such format. 

## How to use: 
1. **Get system prepared**:
    - Install Rhino 7 or 8
    - Install grasshopper plugins through https://app.pollination.solutions/cad-plugins
    - Install UrbanOPT CLI through https://docs.urbanopt.net/installation/installation.html
      
2. **Process questionnaire submissions with the workflow**:
    - Download the questionnaire submissions as CSV file on jotform
    - Open the workflow with grasshopper and following the instruction
      
3. **Optional Parameters**:
    - UrbanOPT model ouputs only without running the simlation: ......
    - Custom building ploygon input: ......
    - 
