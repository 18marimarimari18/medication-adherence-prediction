Predicting Medication Non-Adherence: A Study of Financial Toxicity🏥 

Overview
Medication non-adherence is a multi-billion dollar systemic failure in Canadian healthcare. While traditional models often attribute non-adherence to patient behavior, this research shifts the focus to structural determinants: insurance architecture and socioeconomic barriers.By quantifying "Financial Toxicity," this project identifies how insurance tiers and plan contributions act as the primary drivers of therapy abandonment, specifically pinpointing the "Month 3 Cliff"—the 90-day window where systemic failure is most acute.

📊 Key Findings
The Insurance Factor: Using Lasso (L1) Regularization, I isolated insurance tier as a predictor as potent as biological age, achieving a ROC-AUC of 0.88.
Precision Triage: An Ensemble (Random Forest) approach achieved 96% Precision in identifying high-risk cohorts, essential for reducing clinical alert fatigue.Temporal Decay: Survival analysis revealed a statistically significant 8.3% higher Hazard Ratio (HR = 1.0825, P < 0.001) for specific demographics lacking work-integrated benefits.

🛠 Technical Stack
Language: Python
Libraries: scikit-learn (Modeling), lifelines (Survival Analysis), pandas (Data Engineering), matplotlib/seaborn (Visualization).
Methodology: * Lasso Regression: For high-dimensional feature selection and mitigating multi-collinearity.
Random Forest: To capture non-linear interactions between socioeconomic features.Cox Proportional Hazards: To map the "time-to-event" decay of treatment persistence.📁 Repository StructurePlaintext├── PredictingMedicationNonAdherence_ModelComparison.ipynb  

# Main Analysis
├── data/                                                  # Synthetic/Sanitized Dataset
├── README.md                                              # Project Documentation
└── requirements.txt                                       # Dependencies

🚀 The "Target 90" ProtocolThe ultimate goal of this model is a proactive clinical intervention strategy. By identifying the Month 3 Cliff, healthcare providers can trigger automated "Day 60 Interventions" (financial counseling, insurance navigation support) to pre-empt the 90-day collapse in treatment adherence.
📝 About the ResearcherI am a Health Data Scientist focused on using machine learning to solve systemic inequities in healthcare access. This project was developed as part of my work at the University of Waterloo, driven by the intersection of clinical data and public health advocacy.Keywords: 

#HealthTech #SurvivalAnalysis #FinancialToxicity #PredictiveModeling
