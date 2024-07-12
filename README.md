# Eclipsing Survival Analysis
This dataset seems to be a snapshot of patients with lung cancer, detailing clinical characteristics, treatment types, and mutation statuses that could be analyzed to understand factors influencing survival outcomes in lung cancer patients.

Description of Columns:

    Patient ID: Unique identifier for each patient.
    Survival time (days): Number of days survived after diagnosis.
    Event (death: 1, alive: 0): Indicates whether the patient died (1) or is alive (0).
    Tumor size (cm): Size of the tumor in centimeters.
    Grade: Grade of the tumor.
    Stage (TNM 8th edition): Cancer stage according to the TNM (Tumor, Node, Metastasis) staging system, 8th edition.
    Age: Age of the patient at diagnosis.
    Sex: Gender of the patient.
    Cigarette: Smoking status (Current, Former, Never).
    Pack per year: Number of packs smoked per year.
    Type.Adjuvant: Type of adjuvant treatment.
    batch: Batch number.
    EGFR: EGFR mutation status.
    KRAS: KRAS mutation status.

In the realm of survival analysis, choosing the appropriate statistical model plays a pivotal role in analysis of patient outcomes. This study delves into the comparison between two intriguing methodologies: Poisson regression, renowned for its robustness in handling count data, a continuous counterpart hypothesized to emulate the characteristics of the Poisson distribution.

The investigation scrutinizes their efficacy in hypothesis testing, aiming to unravel which model best captures the intricate nuances of survival times in clinical datasets. By leveraging real-world patient data encompassing diverse demographics and tumor characteristics, this research aims to shed light on which statistical tool offers superior predictive accuracy and interpretability for survival analysis.

Through rigorous statistical evaluation and comparison of model performances, this study seeks to provide valuable insights into selecting the optimal approach for hypothesis testing in survival analysis, thereby enhancing our understanding of factors influencing patient outcomes in oncological settings.
