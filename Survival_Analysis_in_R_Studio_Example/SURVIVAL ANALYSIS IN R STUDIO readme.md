# SURVIVAL ANALYSIS IN R STUDIO: Kaplan-Meier and Cox Modeling

## Dataset Summary
This dataset contains sample **clinical data** featuring essential **time-to-event variables** (Time and Event status) required for Survival Analysis. It is designed to demonstrate and validate advanced biostatistical techniques using **R Studio**, particularly for analyzing patient prognosis, treatment efficacy, and time-dependent risk factors in clinical trials.

The successful application of these models proves proficiency in handling core clinical endpoints for prognostic modeling.

---

## File Index and Descriptions

The files in this dataset are structured to provide the necessary input for reproducible survival modeling workflows.

| File Name | Format | Purpose and Content Description |
| :--- | :--- | :--- |
| **`clinical_survival_data.csv`** | CSV | **Input Data:** The primary dataset containing patient records. Critical columns include **Time** (time until event or censoring) and **Status** (binary variable indicating if the event occurred or if the data was censored). |
| **`patient_metadata.csv`** | CSV | **Covariates:** Contains clinical features used as independent variables (covariates) in the Cox Proportional Hazards model (e.g., Age, Treatment Group, Biomarker Status). |
| **`survival_analysis_script.R`** | R Script | **Code:** (Optional - *Include if you uploaded the R script directly*) The main R script containing the code for loading data, generating **Kaplan-Meier survival curves**, performing log-rank tests, and fitting the **Cox Proportional Hazards model**. |
| **`analysis_report.pdf`** | PDF | **Output Report:** (Optional - *Include if your project generated a report*) Final report summarizing statistical findings, including p-values, hazard ratios (HRs), and interpretation of the survival curves. |

---

## Technical Context and Usage

* **Primary Tool Focus:** **R (Survival, Survminer, ggplot2)**.
* **Algorithms Demonstrated:** **Kaplan-Meier Estimator** (Non-parametric) and **Cox Proportional Hazards Model** (Semi-parametric regression).
* **Recommended Use:** This dataset is ideal for:
    1. Validating predictive models related to time-to-event outcomes.
    2. Benchmarking different approaches to handling censored data.
    3. Demonstrating core biostatistics proficiency for clinical research roles.

### 🔗 Linked GitHub Repository (Full Source Code)

The full R script, code logic, and version history for this project can be found here:

> **GitHub Repository:** [**SURVIVAL-ANALYSIS-DONE-USING-R-STUDIO-**](https://github.com/DrNagendra619/SURVIVAL-ANALYSIS-DONE-USING-R-STUDIO-)