# ai_hiringdecisions_trust
An analysis of AI trust and human oversight in hiring decisions.

**Overview**

This project explores whether AI systems can be safely trusted to make early-stage hiring decisions or whether human oversight remains necessary. Using a synthetic, anonymized dataset, I simulate an automated candidate screening system and evaluate its reliability across different confidence levels.

**Motivation**

Automated resume screening systems are increasingly used in hiring pipelines. While they promise efficiency, incorrect rejections can exclude qualified candidates. This project examines where AI performs reliably and where human judgment should remain involved.

**Data & Ethics**

Publicly available, anonymized, synthetic dataset

No real resumes or personal identifiable information used

Only features plausibly available at application time were included

**Methodology**

- Baseline logistic regression model

- Evaluation of prediction confidence rather than accuracy alone

- Confidence-based decision thresholds

- Simulation of a human-in-the-loop hiring process

**Key Findings**

- The model performs reasonably well overall but rarely produces high-confidence rejection decisions

- Most candidates fall into a **borderline confidence range**

- Fully autonomous rejection would affect few candidates but risks excluding qualified ones

- A **hybrid human-AI system** improves efficiency while reducing risk

**Conclusion**

AI is best used as a decision-support tool in hiring rather than a fully autonomous decision-maker. Confidence-aware human oversight is essential for responsible deployment.
