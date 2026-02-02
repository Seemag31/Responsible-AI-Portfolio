# Mapping NIST AI RMF to the Data Science Lifecycle

## 1. Typical Data Science Lifecycle Stages
1. Problem definition  
2. Data collection  
3. Data cleaning & preparation  
4. Feature engineering  
5. Model training  
6. Evaluation & validation  
7. Deployment  
8. Monitoring  
9. Decommissioning  

---

## 2. RMF Function Mapping Table

| DS Stage | RMF Function(s) | Governance Actions | Responsible Role | Artifacts Produced |
|----------|------------------|--------------------|------------------|--------------------|
| Problem Definition | Govern, Map | Define purpose, identify stakeholders, assess potential harms | Product lead | Problem statement |
| Data Collection | Map, Govern | Assess data sources, privacy, and bias risks | Data engineer | Data inventory |
| Data Preparation | Map, Measure | Evaluate data quality, representation gaps | Data scientist | Data audit report |
| Feature Engineering | Measure | Check for proxy variables and bias risks | ML engineer | Feature documentation |
| Model Training | Measure | Conduct performance and fairness testing | ML engineer | Metrics report |
| Evaluation | Measure, Manage | Compare tradeoffs, choose thresholds, document risks | ML + product | Evaluation summary |
| Deployment | Govern, Manage | Define usage rules and human oversight | Operations + product | Deployment checklist |
| Monitoring | Monitor, Measure | Track performance, drift, and fairness over time | MLOps | Monitoring dashboard |
| Decommissioning | Manage, Govern | Retire system responsibly and document reasons | Governance lead | Retirement report |

---

## 3. Observations
Early lifecycle stages emphasize Govern and Map functions focused on planning, documentation, and understanding risks. Later stages emphasize Measure, Manage, and Monitor functions where risks are evaluated, mitigated, and tracked in real-world operation.

## 4. Gaps or Tensions
Applying governance practices can slow development timelines, and it may be unclear which team owns certain risk management tasks. Some RMF guidance remains high-level, requiring organizations to define their own operational details.

## 5. Key Insight
> AI governance is not a single step; it evolves across the data science lifecycle as risks shift from design concerns to operational realities.

