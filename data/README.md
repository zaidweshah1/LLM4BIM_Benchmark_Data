# Task-Level Error Logs

This folder contains the detailed task-level error logs used in the LLM4BIM benchmark.  
Each Excel file records the final error statistics for one task level.

- **Component_Level_Errors.xlsx**  
- **Assembly_Level_Errors.xlsx**  
- **System_Level_Errors.xlsx**

Each sheet uses the same column structure:

- **Task ID**  
  Short identifier for the task (e.g., C3, A5, S7).

- **Prompt Used**  
  The exact natural language prompt given to the LLM.

- **Testing Phase**  
  Task level or phase (Component, Assembly, or System).

- **Error Message**  
  The main error message returned by Revit / Python for that task.

- **Error Category**  
  The mapped error type, such as API Misuse, Geometry Error, Environment Error, etc.

- **Error Count / prompt**  
  Total number of errors associated with that prompt.

- **Success (Y/N)**  
  Whether the task ultimately succeeded after corrections (Y) or not (N).

- **Notes**  
  Any brief comments or clarifications about the error or correction.

- **Python code**  
  The final version of the BIM script associated with that task.
