<div align="center">

<img src="assets/DHDS_logo.png" alt="Digital Health Data Science Lab" width="620" />

# Digital Health Data Science Lab · DHDS

**Department of Biomedical Informatics — Korea University College of Medicine**

*Turning national health data into reproducible, publication-ready evidence.*

[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-4285F4?style=flat-square&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=oCfJJuMAAAAJ)
[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0000-0003-4646-8998)
[![Korea University](https://img.shields.io/badge/Korea%20University-862633?style=flat-square)](https://scholarworks.korea.ac.kr/kumedicine/researcher-profile?ep=2170)
[![Email](https://img.shields.io/badge/Contact-D14836?style=flat-square&logo=maildotru&logoColor=white)](mailto:seogsongjeong@korea.ac.kr)

</div>

---

### About the lab

The **Digital Health Data Science Lab (DHDS)** develops reproducible analytic pipelines and causal-inference methods for large-scale health data. We work with national administrative and examination cohorts — Korea's **NHIS** and **KNHANES**, Japan's **JMDC**, and the U.S. **NHANES** — to study cardiometabolic and hepatic disease, medication effects, and clinical risk, and we build open tooling that makes survey-weighted, bias-aware epidemiology fast to run and easy to reproduce.

---

### Research focus

- **Pharmacoepidemiology & causal inference** — target trial emulation, active-comparator new-user designs, marginal structural models, IPTW / IPCW, competing risks (Fine–Gray), and G-methods (G-computation, AIPW, TMLE).
- **Hepatic & cardiometabolic epidemiology** — MASLD / MASH, non-invasive liver staging (CAP / LSM, FIB-4, FLI), and downstream cardiovascular and oncologic outcomes.
- **Clinical prediction modeling** — development, calibration, and external validation of risk models across independent cohorts.
- **Medical informatics & applied AI** — evaluation of large language models for clinical text, digital biomarker development, and automated, reproducible research pipelines.

---

### Methods & data

**Languages & tools**

![SAS](https://img.shields.io/badge/SAS-0F5EAA?style=flat-square&logo=sas&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

**Data sources**

![Korea NHIS](https://img.shields.io/badge/Korea%20NHIS-475569?style=flat-square)
![KNHANES](https://img.shields.io/badge/KNHANES-475569?style=flat-square)
![JMDC](https://img.shields.io/badge/JMDC-475569?style=flat-square)
![NHANES](https://img.shields.io/badge/NHANES-475569?style=flat-square)

---

### Flagship software

**KNHANES + NHANES Research Automation Platform**
A survey-weighted analysis platform that turns national health-examination microdata into publication-ready epidemiologic, temporal-trend, and machine-learning reports. Every estimate is a deterministic complex-survey result computed by the R `survey` package; an optional local LLM only drafts narrative prose and never computes a statistic. Covariate sets are screened for over-adjustment and outcome-definition leakage.

`Streamlit` · `R survey` · `causal-inference (PSM / IPTW / AIPW / G-computation / TMLE)` · `16-model ML panel with SHAP`

→ **[View repository](https://github.com/dhdslab)**

---

### Selected publications

<!-- Curate this list; a couple of recent examples are shown. Full list is on Google Scholar. -->

- Statin Use and Risk of Hepatocellular Carcinoma in Metabolic Dysfunction–Associated Steatotic Liver Disease: A National Retrospective Cohort Study. *Cancer Prevention Research*, 2026;19(5):303–312.
- Coexistence of Atrial Fibrillation and Metabolic Dysfunction–Associated Steatotic Liver Disease as a High-Risk Overlap for Incident Heart Failure in Older Adults. *European Journal of Heart Failure*, 2026;28(2):260–268.

**Full publication list → [Google Scholar](https://scholar.google.com/citations?user=oCfJJuMAAAAJ)**

---

<div align="center">

**Digital Health Data Science Lab (DHDS)**
Department of Biomedical Informatics · Korea University College of Medicine · Seoul, Republic of Korea
📫 [seogsongjeong@korea.ac.kr](mailto:seogsongjeong@korea.ac.kr)

<sub>All released estimates are deterministic and survey-weighted. Findings from our tooling are hypothesis-generating and require external validation.</sub>

</div>
