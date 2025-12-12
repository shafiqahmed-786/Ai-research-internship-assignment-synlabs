TASK 3 — HIGH-LEVEL TO LOW-LEVEL ARCHITECTURE TOOL  
----------------------------------------------------

Overview:
This task converts high-level business requirements into detailed low-level
technical specifications using:
- AI or fallback logic to break down requirements
- Automatic generation of:
  - Modules
  - Database schema (tables, columns, relations)
  - Pseudocode flow for major operations
  - Notes / assumptions

Directory Contents:
- task3_notebook.ipynb        → Full implementation notebook
- task3_report.md / .pdf      → Explanation of logic and methodology
- sample_requirement.txt       → Input requirement used during testing
- output_architecture.json     → Generated architecture output
- README_Task3.txt            → This file

How to Run:
1. Open the notebook in Google Colab.
2. Install dependencies (Python standard libraries only — no extras needed).
3. Add OPENAI_API_KEY to `.env` (optional).  
   Fallback architecture generator works without API.
4. Run all cells step-by-step.
5. Output saved at:  
   `output_architecture.json`

Important Notes:
- Fallback logic includes deterministic rule-based architecture generation.
- Output JSON follows a strict structure:
  {
    modules: [],
    schema: [],
    pseudocode: {},
    notes: []
  }
- Designed to be extendable for real-world enterprise use.

