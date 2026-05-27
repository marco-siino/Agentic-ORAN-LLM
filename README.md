# Agentic AI for O-RAN Orchestration

Official implementation of "Agentic AI for O-RAN Orchestration: An Embodied Intelligence Architecture for Autonomous Network Intent Generation".
A framework for Level 5 autonomous control using Hybrid-LLM loops vs DRL.

## Evaluated Scenarios in this Repository:
* **Scenario A (Energy Crisis):** Demonstrates Zero-Shot adaptation to dynamic energy pricing and localized safety emergencies. (`Mistral_EnergyCrisisSimulation_DRLvsA_LLM+DRL.ipynb`)
* **Scenario B (Flash Crowd):** Shows dynamic QoS restoration and Pareto-frontier navigation during extreme congestion. (`Mistral_FlashCrowdSimulation_DRLvsA_LLM+DRL.ipynb`)
* **Scenario C (Semantic Security Override):** Simulates a DDoS attack to highlight the "Malicious Traffic Paradox", where traditional DRL wastes resources while the A-LLM enforces an intelligent radio quarantine. (`Mistral_DDoSSimulation_DRLvsA_LLM+DRL.ipynb`)

## Foundation Model Comparison
Includes sensitivity analysis comparing Mistral 7B, Mistral Small, and Mistral Large. (`A_LLM_Versions_Comparison_EnergyCrisisSimulation.ipynb`)
