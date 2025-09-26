# Client Research Report Tool

## 📋 Overview

This tool provides a **ready-to-use JSON schema** for generating preliminary client research reports. 
It covers the full lifecycle of a consulting or research project, from capturing client details and objectives, through documenting findings, to summarizing communication strategies.  

<img width="2160" height="792" alt="image" src="https://github.com/user-attachments/assets/cde4df8d-49ab-4fff-a1bf-9a7bcacef7f1" />

### Trigger another workflow for online research:

<img width="1680" height="564" alt="image" src="https://github.com/user-attachments/assets/34bfd420-88e4-45fd-86af-eabec221c929" />

---


## ⚙️ Core Sections

### 1. 👤 Client Information
- Captures client info (eg: name, contact details, and date of request, description)

### 2. 🔍 Research Findings
- Documents insights grouped into:  
  - **Client Requirements**  
  - **Technical Feasibility**  
  - **Workflow Optimisation**  
  - **Pain Points**  
  - **Pricing & Timelines**  

### 3. 💬 Client Communication
- Captures how findings are communicated back to the client  
- Includes:  
  - Introduction  
  - Workflow & Process Issues  
  - Technical Preferences  
  - Quality Assurance steps  
  - Long-term Vision  
- Ends with a concise **Summary** for decision-makers


## 📦 Example

```json
{
  "Client Research Report": {
    "Client": "Example Client",
    "Date": "2025-09-26",
    "Project Objective": "Describe the project goal here",
    "Research Structure": [
      "Background",
      "Findings",
      "Challenges",
      "Recommendations"
    ],
    "Research Findings": {
      "Client Requirements": [""],
      "Technical Feasibility": [""],
      "Workflow Optimisation": [""],
      "Pain Points": [""],
      "Pricing & Timelines": [""]
    },
    "Client Communication": {
      "Introduction": "",
      "Workflow and Process Issues": [],
      "Summary": ""
    }
  }
}
