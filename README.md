AI driven Honeypot with LLMDriven Threat Analysis

As cyberattacks evolve, traditional honeypots often generate massive volumes of noisy log data that are difficult for analysts
to interpret in real-time. 
This project proposes an Intelligent SSH Honeypot that automates the analysis of attacker behavior.
By integrating the Cowrie honeypot with a Large Language Model (LLM) analysis engine, the system captures attacker commands and uses Generative AI to interpret their intent, classify them based on MITRE ATT&CK categories, and visualize threats on a real-time dashboard.
This approach reduces the manual burden on security analysts by converting raw logs into actionable intelligence.


OBJECTIVE
The primary objectives of the proposed work are to:

-Simulate Realistic Attack Surfaces

-Emulate a production-like Linux SSH environment using Cowrie to attract and retain sophisticated attackers, enabling the capture of high-fidelity intrusion behavior.

-AI-Assisted Command Semantics Analysis

-Use an LLM-powered analysis engine to translate raw shell commands into intent-level explanations (e.g., reconnaissance, privilege escalation, persistence).

-Attack Kill-Chain Mapping

-Automatically map captured commands to stages of the MITRE

-ATT&CK framework, improving contextual understanding of adversary tactics and techniques.

-Design a scoring model that ranks attacker sessions based on impact, intent, and progression depth (low → critical).
