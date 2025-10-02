# OCR-Mini-Project

This is a mini proof-of-concept (PoC) that demonstrates how to extract key information from insurance policy PDFs and compare them to identify differences. The workflow combines NLP, regex-based extraction, and data visualization.

# Insurance Policy Comparison PoC

This is a **mini proof-of-concept (PoC)** that demonstrates how to extract key information from insurance policy PDFs and compare them to identify differences. The workflow combines **NLP**, **regex-based extraction**, and **data visualization**.

It simulates a **renewal intelligence workflow**, similar to what platforms like Quandri use, where unstructured policy documents are converted into structured insights for decision-making.

---

## Notebook Name
`Insurance_Policy_Comparison_PoC.ipynb`

---

## Purpose
- Extract **key fields** from insurance policies:
  - Policy Number  
  - Effective Date  
  - Coverage Amount  
  - Organization  
- Compare multiple policies to detect **changes between old and new policies**.  
- Visualize differences for **quick stakeholder understanding**.  

---

## Dependencies
Make sure the following packages are installed:

```bash
pip install pdfplumber spacy pandas matplotlib
python -m spacy download en_core_web_sm
