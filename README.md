# DS Seminars: Dealing with complex and unstructured big data in biomedical domain


## Project Overview
This project to retrieve Diseas and Symtom data from the Medline database. 

---

## Notebooks
The project consists of **one notebook** with all the code:
1. `medline_extraction.ipynb` – Data Extraction
---

## Dependencies
Listed in 'dependencies' file. 

```pip install -r requirements.txt```

---

## Folders

### `/output`
- Contains the output .csv file after notebook execution. 

### `/input`
- To execute please download the .xml and .dtd files under https://medlineplus.gov/xml.html and place in this folder. 
- The notebook was tested with the 'mplus_topics_2012-06-01.dtd' and 'mplus_topics_2025-03-04.xml' version. 

### `/umls_metathesaurus`
- To execute please download the MRSTY.RRF & MRCONSO.RRF databases under https://www.nlm.nih.gov/research/umls/licensedcontent/umlsknowledgesources.html (both included in the full releas) and place in this folder
---

## Execution Instructions
1. Ensure all necessary dependencies are installed. (dependencies)
2. To execute please download the .xml and .dtd files under https://medlineplus.gov/xml.html and place in this folder. The notebook was tested with the 'mplus_topics_2012-06-01.dtd' and 'mplus_topics_2025-03-04.xml' version. 
3. Change path variables `medline_extraction.ipynb` if needed
4. Add a .env file and add your UTS Api Key in the following format "API_KEY=...". The link to your key can be found in the UTS API documentation (https://documentation.uts.nlm.nih.gov/rest/search/).
