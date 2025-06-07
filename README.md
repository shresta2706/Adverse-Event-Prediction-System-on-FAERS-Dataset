# Adverse-Event-Prediction-System-on-FAERS-Dataset

Developed a predictive model for identifying occurrence of adverse events using the FDA’s Adverse Event Reporting System (FAERS) dataset, achieving 82% accuracy with Random Forest Classifier.

The FAERS dataset is a comprehensive collection of adverse event reports caused by drugs, compiled from multiple sources. The original dataset is structured across seven distinct tables:

- Demographic  
- Drugs  
- Indications  
- Outcome  
- Reaction  
- Report Source  
- Therapy  

These tables were merged using primary identifiers (`PrimaryID` and `CaseID`) to create a unified dataset for analysis. Dataset is available on the FDA website.

**Dataset Link**: [FDA FAERS Quarterly Data Files – Q3 2024](https://www.fda.gov/drugs/questions-and-answers-fdas-adverse-event-reporting-system-faers/fda-adverse-event-reporting-system-faers-quarterly-data-extract-files#2024)


This model offers significant potential for proactive safety monitoring and real-time risk assessment, paving the way for future research in identifying high-risk drug combinations and mitigating adverse medication outcomes.

