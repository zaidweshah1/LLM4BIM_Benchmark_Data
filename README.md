# LLM4BIM_Benchmark_Data

Replication data for **"Toward Reliable LLM-Driven BIM Automation: A Capability-Based Multi-Dimensional Evaluation Framework"**.

This repository contains the prompts, task-level error logs, and summary results used in the experiments.

## Repository Structure

- `docs/`
  - `Prompts.docx`  
    All natural language prompts used in the study, grouped by component-, assembly-, and system-level tasks.
  - `Results_Summary.xlsx`  
    Aggregated results and reliability indicators for all tasks (e.g., number of iterations, total time, success status).

- `data/`
  - `Component_Level_Errors.xlsx`  
    Detailed error logs and iteration history for component-level tasks.
  - `Assembly_Level_Errors.xlsx`  
    Detailed error logs and iteration history for assembly-level tasks.
  - `System_Level_Errors.xlsx`  
    Detailed error logs and iteration history for system-level tasks.

## How to Use

1. Open `docs/Prompts.docx` to see the exact wording of each evaluation prompt.
2. Use the Excel files in `data/` to inspect the errors, iterations, and outcomes for each task.
3. Refer to `docs/Results_Summary.xlsx` for aggregated statistics that match the tables and figures in the paper.

