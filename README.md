# 🛡️ Cognitive AI for Cybersecurity: A Neuro-Symbolic, RL, and Agentic Hybrid Framework

## Overview
This repository accompanies the paper **“Cognitive Hybrid AI System for Real-Time Cyber Intelligence Threat Detection”**.  
We introduce a novel **cognitive AI framework** that integrates:
- 🤖  **Autonomous real-time decision-making** with reinforcement learning agents 
- 🧩 **Neuro-Symbolic Reasoning** for logical transparency and rule-based adaptability  
- 🌫️ **Fuzzy Logic for Uncertainty & Risk Management**, enabling probabilistic reasoning under ambiguity and robust detection of unforeseen AI-driven attacks.  
- 🗨️ **Agentic LLM Chatbot ("System Brain")** for explainability, analyst training, and natural-language queries  

Our system enables **real-time fraud detection, adversarial robustness, interpretability, and resilience** against both current and emerging AI-powered cyberattacks.

---

## 🔥 Problem
Traditional ML-based fraud detection and intrusion systems suffer from:
- Rigid thresholds → vulnerable to adversarial bypass  
- Lack of interpretability → “black-box” decisions hinder analyst trust  
- Dependence on massive retraining → poor adaptability to zero-day attacks  
- Inability to **separate authentic from falsified data streams**  

---

## 💡 Solution
We propose a **hybrid cognitive AI architecture** that:
1. Detects threats with **perfect accuracy under adversarial noise**, outperforming XGBoost, neural-only, and RL-only baselines  
2. Differentiates **genuine vs. fake data streams** reliably, even when adversarially manipulated  
3. Provides **explainable reasoning tracebacks** and human-readable narratives through the LLM chatbot  
4. Adapts to **novel and unforeseen attacks** by updating symbolic rules while leveraging RL for continuous learning  

---

## 🔎 Results

Our experiments evaluated the proposed system against both traditional and advanced baselines under noisy adversarial conditions:

- **Neuron-Symbolic Logic AI (noisy):** Achieved strong robustness with Precision = 0.97, Recall = 0.96, F1 = 0.97.  
- **Reinforcement Learning Agent (noisy):** Adapted effectively to dynamic attack vectors, with Precision = 0.99, Recall = 0.94, F1 = 0.97.
- **XGBoost (baseline, noisy input):** Collapsed under adversarial perturbations with F1 = 0.52, highlighting vulnerability to manipulated data streams.  
- **Voting System Ensemble Hybrid (Proposed):** Outperformed all baselines with **Precision = 1.0, Recall = 1.0, F1 = 1.0**, maintaining real-time operation with latency < 50ms.  

📊 **Key Insight:**  
These results confirm the system’s ability not only to resist adversarial manipulation but also to reliably differentiate between genuine and fake inputs, ensuring resilience against both current and future AI-driven attack patterns.  

---

## ⚙️ System Workflow
1. Data ingestion & preprocessing  
2. Threat detection (XGBoost / RL / Neuro-Symbolic module)  
3. Hybrid ensemble fusion with fuzzy reasoning  
4. Analyst-facing **LLM Agentic Chatbot** for explanations & queries  

---

## 🗝️ Keywords
`Cognitive AI` · `Neuro-Symbolic Reasoning` · `Reinforcement Learning` · `Agentic AI` · `Fuzzy Logic` · `Large Language Models (LLMs)` · `Explainable AI (XAI)` · `Cyber Intelligence` · `Finance Security`

---

## 📌 Limitations
- Symbolic rules must be updated when **entirely new attack strategies** emerge  
- Real-time RL decision-making requires **scalable big-data infrastructure** for high-volume cyber environments  

---

## 🚀 Future Work
- Expanding defense against **complex data forgeries** and unseen AI-driven attacks  
- Strengthening **scalability** for global banking deployments  
- Enhancing **human-AI collaboration** with advanced analyst training modules  

---

---

## 🛡️ Protected Research & Copyright
© 2025 Mohamad Khaled. All rights reserved.  

This repository and the accompanying paper **“Cognitive Hybrid AI System for Real-Time Cyber Intelligence Threat Detection”** present **original architectures, algorithms, and evaluation methods** for AI-driven cybersecurity.  

Any reuse, modification, or redistribution of the methods, models, or experimental results without **explicit written permission** is strictly prohibited.  

This work is protected under international copyright and intellectual property laws.  

---

