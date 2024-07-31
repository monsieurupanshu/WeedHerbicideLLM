# WeedHerbicideLLM
## Weed-Herbicide Recommendation System

### Project Overview
This project aims to develop a Weed-Herbicide Recommendation System using a Large Language Model (LLM). The system will provide recommendations for herbicides based on weed control ratings. The project involves data extraction from PDF files, preprocessing the data, and training an LLM to create an intelligent bot capable of providing accurate herbicide recommendations.

### Data Extraction
We used tools like Camelot and Pandas to extract data from the provided PDF files. The data includes tables detailing the effectiveness of various herbicides on different weeds across different seasons.

### Data Preprocessing
The extracted data was cleaned and formatted into a text format suitable for training the LLM. This involved converting CSV rows into structured sentences and ensuring consistency across the dataset.

### Results
The trained model achieved high accuracy in providing herbicide recommendations. Below are some example outputs from the model:

- Input: "Recommend a herbicide for Giant Foxtail in Spring."
- Output: "Herbicide: Glyphosate, Effectiveness: 90-100%"
  
### ChatBot Template
