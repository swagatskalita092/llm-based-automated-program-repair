# llm-based-automated-program-repair
# Automated Program Repair using Large Language Models

## Overview

This repository contains a presentation report analyzing two modern approaches to LLM-based Automated Program Repair (APR):

- **RepairAgent** (ICSE 2024)
- **RAPGen** (ICSME 2023)

The report compares autonomous agent-based repair workflows with efficiency-oriented guided generation approaches, highlighting the trade-off between repair power and computational cost.

---

## Report Focus

The report explores:

- Evolution of Automated Program Repair (APR)
- LLM-based repair systems
- Agent-based autonomous reasoning (RepairAgent)
- Retrieval-augmented guided repair (RAPGen)
- Comparative analysis of autonomy vs efficiency
- Experimental evaluation results
- Strengths, limitations, and future research directions

---

## Key Insights

- RepairAgent treats the LLM as an autonomous debugging agent capable of planning, tool usage, and iterative refinement.
- RAPGen constrains patch generation to improve scalability and reduce computational overhead.
- A central trade-off exists between repair flexibility and cost efficiency.
- Future APR systems may benefit from hybrid designs balancing autonomy and efficiency.

---

## Evaluation Benchmarks

Both systems are evaluated primarily on:

- **Defects4J** (real-world Java bug benchmark)
- GitBug-Java (for generalization testing)

Metrics considered:
- Plausible patch rate
- Correct patch rate
- Token usage
- Computational cost
- Repair time per bug

---

## Author

**Swagat Subhash Kalita**  
M.Sc. Computer Science  
University of Passau, Germany  

---

## References

Primary papers discussed:

1. Bouzenia et al., *RepairAgent: An Autonomous, LLM-Based Agent for Program Repair*, ICSE 2024.
2. Wang et al., *RAPGen: Retrieval-Augmented Patch Generation*, ICSME 2023.

---

## Academic Context

This report was prepared as part of a university seminar analyzing recent advances in LLM-based software engineering research.

---

