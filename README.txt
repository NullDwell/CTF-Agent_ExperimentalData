Experimental Data
This directory contains the experimental data for the paper "[CTF-Agent: Auditable Execution Discipline and Context-Efficient Agent Orchestration for Automated CTF Solving]". It consists of two parts: raw execution logs and a structured results spreadsheet. This README.txt explains the contents, structure, and how to interpret them.

1. Directory Overview
.
├── logs/                      # Raw execution logs for every experimental run
├── ctf_agent_results.xlsx     # Structured experimental results (accuracy, token usage, context, etc.)
└── README.txt                  # This file
2. logs/ — Raw Execution Logs
This folder contains the complete execution logs of all experimental runs. Each run is stored as a separate log file, named according to the convention below:

Naming convention: [describe, e.g., <log>_<run_date>.log]

One file per run: Each file records the full interaction trace of a single run, including the agent's actions, tool calls, intermediate outputs, and final answer.

The logs are provided for full transparency and reproducibility, allowing reviewers to inspect the exact behavior behind each entry in the results spreadsheet.

3. ctf_agent_results.xlsx — Structured Results
This spreadsheet contains the aggregated experimental results. It contains the following sheet(s) and columns.