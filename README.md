# HDA: A Natural Language Interface for Healthcare Data Analysis

**HDA (Healthcare Discharge Analytics)** is an Italian-language analytics engine that lets doctors, ward managers and quality managers query hospital discharge records (SDO) using natural language, with no SQL knowledge required.
A locally hosted open-weight quantised LLM never writes executable code: it selects among pre-built, pre-tested analytical actions, so no patient data ever leaves the machine.
The system reaches **84% accuracy** in selecting the correct analysis.

## Key ideas

- **Text-to-API instead of Text-to-SQL**: the model outputs a validated intent (an audited action plus its parameters) or a plan from a small fixed grammar restricted to columns declared in a semantic model.
- **Privacy by design**: the whole pipeline runs on-premise with a local model; no external services or cloud APIs.
- **Proactive answers**: automatic primary chart or summary, secondary charts on other dimensions, a plain-Italian summary, and suggested follow-up questions.
- **Reuse of confirmed answers**: answers inspected and confirmed by the user are stored and replayed, so repeated questions are faster and model-free.

## Inside this repo

- Introduction of the thesis
- Thesis slides

