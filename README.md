# Copilot-twin-Orchestrator-Specification

This repository contains the prompt used in the manuscript:

**Task-Based Feasibility Evaluation of an LLM-Enhanced Digital Twin for Semiconductor Manufacturing Analytics**

This repository is provided to support the transparency and reproducibility of the experiments presented in the manuscript.

## Overview

The prompt defines an LLM Analytics Orchestrator for semiconductor FAB digital twin analytics.

It includes instructions and domain knowledge for:

- Data processing
- Root-cause diagnosis
- Manufacturing KPI analysis
- SQL-based data retrieval
- Tool calling
- Report generation

The prompt is based on semiconductor manufacturing simulation data and domain knowledge derived from the SMT2020 and SMAT2022 academic testbeds.

## Repository Structure

```text
.
├── README.md
├── Orchestrator-Specification.xml
├── Role.xml
├── Input.xml
├── Knowledge_Database_Schema.xml
├── Knowledge_Semiconductor_Manufacturing.xml
├── ToolCalling.xml
└── OutputFormat.xml
```


## File Descriptions
| File | Description |
|---|---|
| Orchestrator-Specification.xml | Contains the complete specification of the LLM Analytics Orchestrator. |
| Role.xml | Defines the role and responsibilities of the LLM Analytics Orchestrator. |
| Input.xml | Defines the supported analysis request types and input interpretation rules. |
| Knowledge_Database_Schema.xml | Contains the database schema of the semiconductor FAB simulator. |
| Knowledge_Semiconductor_Manufacturing.xml | Contains domain knowledge related to semiconductor manufacturing systems. |
| ToolCalling.xml | Defines the tool-selection workflow and tool-calling policies. |
| OutputFormat.xml | Defines the required format of the orchestrator's final responses. |

## Orchestrator Specification

The organization of the orchestrator specification follows the structure described in Section 3.3.2, **“Orchestrator Specification,”** of the manuscript.

The specification consists of the following sections:

1. Role
2. Input
3. Domain Knowledge — Database Schema
4. Domain Knowledge — Semiconductor Manufacturing
5. Tool Calling
6. Output Format

The specification is provided as both a complete XML file and a set of modular XML files. 

## Manuscript Information

Additional information about the associated manuscript, including its publication status, citation details, and related links, will be added in a future update.
