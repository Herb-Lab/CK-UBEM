# CK-UBEM
This is a documentation for the Grasshopper pipeline, questionnaire, and HVAC selection map used for collecting community knowledge and perform community knowledge-based UBEM simulation. 
## Content: 
- **questionnaire_preview.pdf**: Preview of the questionnaire used to collect community knowledge from householders. The questionnaire is built with jotform. Access to the questionnaire: https://form.jotform.com/251915919185063.
- **pipeline.gh**: The main pipeline used to process the submission of the questionnaire to inputs for UrbanOPT simulation. The pipeline is built mainly with Ladybug tools, and its operation require the installations of Rhino, Ladybug plugin, Honeybee plugin, Dragonfly plugin, and UrbanOPT CLI. 
- **HVAC.xlsx**: The library used to match the questionnaire submissions for a household's heat fuel, heating types, and cooling types to a certain HVAC system that can be recognized by Dragonfly.

## How to use: 
- **Collect community information with the questionnaire**:
  - ...... 
- **Get system prepared**:
  - Install Rhino 7 or 8
  - Install grasshopper plugins through https://app.pollination.solutions/cad-plugins
  - Install UrbanOPT CLI through https://docs.urbanopt.net/installation/installation.html
- **Process questionnaire submissions with the pipeline**:
  - Download the questionnaire submission as CSV file on jotform
  - Open the pipeline with grasshopper
  - Input the CSV file path in 'Community Knowledge' panel
  - Input your EPW weather file path in 'Weather File' panel
  - Input your simulation year in the 'Simulation Year' panel
  - Define your output path in the 'Output Path' panel
  - Click on 'Run Modeling', and wait for the simulation finish
- **Optional Parameters**:
  - UrbanOPT model ouputs only without running the simlation: ......
  - Custom building ploygon input: ...... 
