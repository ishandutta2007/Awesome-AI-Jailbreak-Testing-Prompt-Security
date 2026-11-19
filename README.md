# Awesome-AI-Jailbreak-Testing-Prompt-Security

## Top AI Jailbreak Testing & Prompt Security Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Automated LLM Red-Teaming, Prompt Injection & Jailbreak Testing, AI Security Firewalls, System-Prompt Transparency & Adversarial Defense*  

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Jailbreak Testing & Prompt Security**. These tools probe language models and autonomous agents for jailbreaks, direct/indirect prompt injections, system-prompt extraction, and data leakage—while providing runtime firewalls and safety classifiers to harden production AI systems.



**Examples** include Lakera Guard, Mindgard, Cisco AI Defense (Robust Intelligence), Protect AI, HiddenLayer, Vigil AI, Promptfoo, NVIDIA Garak, Microsoft PyRIT, Meta CyberSecEval, and elder-plinius/CL4R1T4S (the category leaders). 



**Open-source emphasis**: This section is heavily expanded with every major active project for automated LLM vulnerability scanners (`Garak`, `PyRIT`, `Promptfoo`, `Giskard`), adversarial red-teaming & system-prompt research (`CL4R1T4S`, `L1B3RT4S`, `AutoDAN`, `PAIR`), runtime prompt-injection firewalls (`LLM Guard`, `Rebuff`, `NeMo Guardrails`), and open-weight safeguard models (`Llama Guard`, `Prompt Guard`, `WildGuard`) — ideal for AI security engineers, red-teamers, AppSec teams, and safety researchers.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Platform | Valuation / Size | Starting Pricing | Free Tier / Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[Cisco AI Defense](https://cisco.com)** *(formerly Robust Intelligence)* | **$375B+** *(Parent Market Cap; RI acquired for ~$400M)* | **$50,000/yr** *(AWS/Azure Marketplace private offer baseline; enterprise contract packages)* | **Free Explorer Edition** *(Self-serve access for developer scanning & red-teaming; 30-day guided enterprise PoC available)* | Enterprise AI validation and runtime protection suite providing automated algorithmic red-teaming, jailbreak stress-testing, and real-time runtime guardrails. |
| **[Protect AI](https://protectai.com)** *(Guardian & Layer)* | **$260B+** *(Parent Market Cap; acquired by Palo Alto Networks for ~$700M)* | **$30,000/yr** *(AWS Marketplace annual enterprise license baseline; metered per scanning dimension)* | **14 to 30 days** *(Custom enterprise proof-of-concept/pilot via sales; free MLSecOps foundation tools)* | Enterprise AI security platform offering real-time prompt firewalling, ML supply-chain scanning, and continuous automated red-teaming for generative AI apps. |
| **[Lakera Guard](https://lakera.ai)** | **$15B+** *(Parent Market Cap; acquired by Check Point for ~$300M)* | **$0.0015/request** *(or $250/mo starter; custom volume plans for enterprise)* | **Free forever: 10,000 requests/mo** *(Up to 8k tokens context/request, full API & dashboard access)* | Ultra-low-latency real-time AI security firewall protecting LLM applications and agents against prompt injections, jailbreaks, system-prompt leaks, and toxic content via API. |
| **[TrojAI](https://troj.ai)** | **$2.1B** *(Parent Market Cap; acquired by A10 Networks for undisclosed valuation; raised $9.1M)* | **$1,500/mo** *(Annual subscription starting package via A10 Networks / Azure Marketplace)* | **30-day free trial** *(Full access to A10 Defend / TrojAI Detect & Defend evaluation environment upon request)* | Enterprise AI security platform specializing in automated red-teaming, adversarial robustness testing, and real-time firewall protection against prompt injection and data exfiltration. |
| **[HiddenLayer](https://hiddenlayer.com)** | **$500M+** *(Valuation est.; $156M total funding raised including $100M Series B)* | **$500/mo** *(Baseline scanning tier; AWS Marketplace enterprise contracts up to $5M/yr)* | **14-day guided PoC** *(Enterprise pilot with model scanner community evaluation access)* | Enterprise AI security platform delivering real-time adversarial attack detection, prompt injection monitoring, model scanning, and automated AI red-teaming. |
| **[Fiddler AI](https://fiddler.ai)** *(Fiddler Guardrails)* | **$400M** *(Acquisition valuation by CrowdStrike; $100M total venture funding raised)* | **$0.002/trace** *(Developer Tier pay-as-you-go; custom enterprise deployment plans)* | **Free forever: Unlimited Real-Time Guardrails** *(Centor Model safety/jailbreak/injection enforcement; traces excluded)* | Enterprise AI observability and governance platform offering sub-100ms jailbreak, safety, PII, and faithfulness guardrails alongside drift monitoring. |
| **[Patronus AI](https://patronus.ai)** | **$250M+** *(Valuation est.; $70M total funding raised including $50M Series B)* | **$10 per 1,000 evaluator calls** *(Pay-as-you-go API; custom enterprise agreements)* | **Free forever: 2 projects & 5 experiments/project** *(Includes $10 free API credits, 2-week trace retention)* | Automated AI safety and evaluation platform featuring adversarial test generation, specialized hallucination/safety detection models, and enterprise policy benchmarking. |
| **[Mindgard](https://mindgard.ai)** | **$120M+** *(Valuation est.; $42M total funding raised including $30M Series A)* | **$1,200/mo** *(Annual baseline contract; custom quotes based on models & agents tested)* | **Free forever: Mindgard AI Security Labs** *(Free community CLI & web sandbox for individual model red-teaming; 14-day enterprise PoC)* | Continuous automated AI red-teaming and security testing platform uncovering jailbreaks, evasion attacks, model inversion, and data poisoning across LLMs and multimodal systems. |
| **[Vigil AI / Promptfoo Enterprise](https://promptfoo.dev)** | **$86M** *(Acquired by OpenAI in 2026; $23.6M funding raised prior to acquisition)* | **$500/mo** *(Team/Enterprise hosted dashboard; custom enterprise tier)* | **Free forever: 10,000 probes/mo** *(Open-source CLI is 100% free; includes community evaluation engine & vulnerability scanner)* | Enterprise continuous AI red-teaming and vulnerability management platform automating OWASP Top 10 for LLMs testing, compliance reporting, and regression gating. |
| **[Arthur Shield](https://arthur.ai)** *(Arthur AI)* | **$45M – $168M** *(Valuation range; $42M Series B funding; est. $8M+ ARR)* | **$60/mo** *(Premium Tier; covers up to 100 use cases & 30-day retention; custom enterprise)* | **Free forever: Up to 4 use cases** *(Core LLM firewall/observability metrics, unlimited seats, 7-day retention)* | Real-time LLM firewall and observability suite providing prompt injection detection, PII/sensitive data filtering, hallucination scoring, and toxicity guardrails. |





## Open-Source GitHub Projects



- **[elder-plinius/CL4R1T4S](https://github.com)**  

  Open-source AI transparency and adversarial prompt-security repository documenting extracted system prompts, tool schemas, and guardrail structures across frontier models to help researchers audit model behavior and alignment boundaries.



- **[NVIDIA Garak (`NVIDIA/garak`)](https://github.com)**  

  Industry-standard open-source (`Apache-2.0`) LLM vulnerability scanner from NVIDIA that probes models and endpoints for jailbreaks, prompt injections, encoding bypasses, hallucination, and data leakage.



- **[Microsoft PyRIT (`Azure/PyRIT`)](https://github.com)**  

  Open-source (`MIT`) Python Risk Identification Tool for generative AI from Microsoft's AI Red Team enabling security professionals to automate multi-turn adversarial jailbreak campaigns and scoring.



- **[Promptfoo (`promptfoo/promptfoo`)](https://github.com)**  

  Fast open-source (`MIT`) CLI and library featuring a dedicated adversarial red-teaming engine (`promptfoo redteam`) that generates dynamic jailbreak, indirect injection, and PII-leakage tests for CI/CD.



- **[CyberSecEval / Purple Llama (`meta-llama/PurpleLlama`)](https://github.com)**  

  Open-source cybersecurity and prompt-security benchmark suite from Meta evaluating LLM susceptibility to prompt injection, cyberattack assistance, and insecure code generation alongside `Prompt Guard` and `Llama Guard` weights.



- **[LLM Guard (`protectai/llm-guard`)](https://github.com)**  

  Comprehensive open-source (`MIT`) security toolkit by Protect AI providing local input/output scanners for prompt injection detection, secrets scanning, PII anonymization, and toxicity filtering.



- **[NVIDIA NeMo Guardrails (`NVIDIA/NeMo-Guardrails`)](https://github.com)**  

  Flagship open-source (`Apache-2.0`) programmable guardrail runtime using Colang to enforce topical, jailbreak, safety, and tool-execution boundaries on conversational and agentic LLM systems.



- **[Guardrails AI (`guardrails-ai/guardrails`)](https://github.com)**  

  Popular open-source (`Apache-2.0`) Python framework and validator Hub for enforcing structural, semantic, PII, and prompt-injection safety checks on LLM inputs and outputs.



- **[Giskard (`Giskard-AI/giskard-oss`)](https://github.com)**  

  Open-source (`Apache-2.0`) automated QA and red-teaming scanner for LLM agents and RAG apps that automatically probes for prompt injection, sensitive information disclosure, and sycophancy.



- **[Rebuff (`protectai/rebuff`) & Vigil (`deadbits/vigil-llm`)](https://github.com)**  

  Open-source (`Apache-2.0` / `MIT`) multi-layered prompt-injection detection frameworks combining vector similarity signatures, heuristic rules, canary tokens, and LLM classifiers.



- **[AgentDojo (`ethz-spylab/agentdojo`)](https://github.com)**  

  Open-source (`MIT`) dynamic evaluation environment and benchmark from ETH Zurich specifically designed to test tool-calling AI agents against indirect prompt injection attacks.



- **[JailbreakBench (`JailbreakBench/jailbreakbench`)](https://github.com)**  

  Open-source (`MIT`) standardized robustness benchmark and artifact repository tracking reproducible jailbreak attacks (`PAIR`, `GCG`, `DSN`) and defense mechanisms across open and closed models.



- **[HarmBench (`centerforaisafety/HarmBench`)](https://github.com)**  

  Open-source (`MIT`) standardized evaluation framework from the Center for AI Safety for automated red-teaming and robust refusal benchmarking across 18+ adversarial attack methods.



- **[AutoDAN (`SheltonLiu-N/AutoDAN`) & TAP (`ricommunity/TAP`)](https://github.com)**  

  Open-source (`MIT`) automated black-box adversarial jailbreak research frameworks using hierarchical genetic algorithms and Tree-of-Attacks pruning to test model safety alignment.



- **[DeepTeam (`confident-ai/deepteam`)](https://github.com)**  

  Open-source (`Apache-2.0`) LLM red-teaming framework built by the creators of DeepEval simulating 40+ vulnerability and adversarial attack vectors (`jailbreaking`, `prompt probing`, `BOLA`, `excessive agency`).



- **[WildGuard (`allenai/wildguard`) & ShieldGemma (`google-deepmind/gemma`)](https://github.com)**  

  Open-weight (`Apache-2.0` / `Gemma Terms`) safety moderation and adversarial prompt-detection classifier models engineered to detect jailbreak attempts and harmful outputs locally.



### Additional Strong Open-Source Options



- **[elder-plinius/L1B3RT4S](https://github.com)** and **[Awesome-Jailbreak-on-LLMs (`yueliu1999/Awesome-Jailbreak-on-LLMs`)](https://github.com)** for curated academic and community research indexes of adversarial jailbreak techniques and defense papers.

- **[InjecAgent (`uiuc-kang-lab/InjecAgent`)](https://github.com)** and **[BIPIA (`microsoft/BIPIA`)](https://github.com)** for benchmarking indirect prompt injection vulnerabilities when AI agents ingest untrusted emails, web pages, or tool outputs.

- **[Inspect AI (`UKGovernmentBEIS/inspect_ai`)](https://github.com)** for the UK AI Security Institute's open-source framework evaluating frontier model safety, cyber capabilities, and agentic guardrails.

- **[LlamaFirewall (`meta-llama/PurpleLlama`)](https://github.com)** for Meta's open-source multi-layer agent defense combining `PromptGuard 2`, `Agent Alignment Checks`, and `CodeShield` static analysis.
