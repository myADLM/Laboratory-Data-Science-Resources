# Laboratory-Data-Science-Resources
Welcome to the Association for Diagnostics & Laboratory Medicine (ADLM) Data Science Program repository. This collection provides resources, tools, and educational materials for applying data science methods to laboratory medicine and diagnostics.


## Table of Contents
- [Getting Started](#gettingstarted)
- [Laboratory Data Science](#labdatascience)
- [Best Practice for Machine Learning](#bp)
- [Datasets and Code](#datasetcode)
- [R](#r)
- [SQL](#sql)
- [Open-Source Tools & Platforms](#opensource)
- [Journals](#journals)
- [Getting Help](#help)
- [Contributing](#contributing)
- [Acknowledgments](#acknowledgments)

## Getting Started

Start here if you have laboratory experience but are new to data science. 
  1. [Practical Machine Learning in the Clinical Laboratory](https://nspies13.github.io/)
  2. [Applications of Machine Learning in Routine Laboratory Medicine](https://pmc.ncbi.nlm.nih.gov/articles/PMC9007900/)
  3. Programming Basics:
    - [Introduction to Python](https://www.datacamp.com/courses/intro-to-python-for-data-science?utm_cid=22785184688&utm_aid=185890093361&utm_campaign=220808_1-ps-brd~brd~branded-variations_2-b2c_3-nam_4-rtw_5-na_6-na_7-le_8-pdsh-go_9-b-e_10-na_11-na&utm_loc=9007781-&utm_mtd=e-c&utm_kw=datacamp%20python%20course&utm_source=google&utm_medium=paid_search&utm_content=ps-other~nam-en~brd~tech~python&gad_source=1&gad_campaignid=22785184688&gbraid=0AAAAADQ9WsHA-WwTX0UE7KV3GZVFT3crP&gclid=CjwKCAiAuIDJBhBoEiwAxhgyFlePRJEFIy1oBgZ9ifOMjJ5CN0fIaj9ryc_CZOiAliENUOQEb-rXVRoC0CcQAvD_BwE)
    - [Python Tutorial - Kaggle](https://www.kaggle.com/learn/python)
    - [R for Data Science](https://r4ds.hadley.nz/)

## Laboratory Data Science

- [What Is Data Analytics in Lab Medicine Anyway?](https://myadlm.org/community/for-early-career-members/education-resources/what-is-data-analytics-in-lab-medicine-anyway)
- [Machine learning algorithms for predicting urinary tract infections: Integration of demographic data and dipstick reflectance results](https://myadlm.org/education/all-webinars/webinars/2025/november/machine-learning-algorithms-for-predicting-urinary-tract-infections)
- [Advancing patient care with data science in clinical laboratories](https://myadlm.org/education/online-courses/online-courses/advancing-patient-care-with-data-science-in-clinical-laboratories)
- [On Demand Webinars Data Analytics Webinars](https://myadlm.org/education/all-webinars/on-demand-webinars#q=%22data%20analytics%22%20&sort=%40searchdatecoveo%20descending)
- [Data science in laboratory medicine certificate program](https://myadlm.org/education/online-certificate-programs/certificate-programs/data-science-in-laboratory-medicine-certificate-program)

 ## Best Practice for Machine Learning
- [Good Machine Learning Practice](https://www.fda.gov/medical-devices/software-medical-device-samd/good-machine-learning-practice-medical-device-development-guiding-principles)
- [MI-CLAIM Checklist](https://www.equator-network.org/reporting-guidelines/minimum-information-about-clinical-artificial-intelligence-modeling-the-mi-claim-checklist/)
  
## Datasets and Code

### Clinical Chemistry Journal

| Citation | ML Method | Code/Data Access | Application |
|----------|-----------|------------------|-------------|
| Hu H et al. "Expert-Level Immunofixation Electrophoresis Image Recognition." *Clin Chem* 2023;69(2):130-139. [DOI: 10.1093/clinchem/hvac190](https://doi.org/10.1093/clinchem/hvac190) | CNN ensemble (VGG-16, ResNet-18, MobileNet-V2) | [Zenodo: 10.5281/zenodo.7123624](https://doi.org/10.5281/zenodo.7123624) | Monoclonal protein detection |
| Schipper A et al. "Machine Learning-Based Prediction of Hemoglobinopathies." *Clin Chem* 2024;70(8):1064-1075. [DOI: 10.1093/clinchem/hvae081](https://doi.org/10.1093/clinchem/hvae081) | XGBoost, Logistic regression | [GitHub](https://github.com/aschipper/hemoglobinopathies-AI); [FigShare: 10.6084/m9.figshare.25765302](https://doi.org/10.6084/m9.figshare.25765302) | CBC-based hemoglobinopathy screening |
| Steinbach D et al. "Applying Machine Learning to Blood Count Data Predicts Sepsis." *Clin Chem* 2024;70(3):506-515. [DOI: 10.1093/clinchem/hvae001](https://doi.org/10.1093/clinchem/hvae001) | Boosted random forest | [sbcdata (R)](https://github.com/ampel-leipzig/sbcdata), [sbcmodel (MATLAB)](https://github.com/ampel-leipzig/sbcmodel); [Zenodo: 10.5281/zenodo.6922968](https://doi.org/10.5281/zenodo.6922968) | Early sepsis warning |
| Spies NC et al. "Automating Detection of IV Fluid Contamination Using Unsupervised ML." *Clin Chem* 2024;70(2):444-452. [DOI: 10.1093/clinchem/hvad207](https://doi.org/10.1093/clinchem/hvad207) | UMAP unsupervised | [GitHub](https://github.com/nspies13/bmp_umap_paper); [FigShare: 10.6084/m9.figshare.23805456](https://doi.org/10.6084/m9.figshare.23805456) | Preanalytical error detection |
| Spies NC et al. "Validating, Implementing, and Monitoring ML Solutions." *Clin Chem* 2024;70(11):1334-1343. [DOI: 10.1093/clinchem/hvae126](https://doi.org/10.1093/clinchem/hvae126) | XGBoost tutorial | [Tutorial Site](https://nspies13.github.io); [FigShare: 10.6084/m9.figshare.23805456](https://doi.org/10.6084/m9.figshare.23805456) | Educational resource |
|
### Journal of Applied Laboratory Medicine 

| Citation | ML Method | Code/Data Access | Application |
|----------|-----------|------------------|-------------|
| Ammer T et al. "refineR Algorithm for Reference Intervals." *JALM* 2023;8(1):84-91. [DOI: 10.1093/jalm/jfac101](https://doi.org/10.1093/jalm/jfac101) | Box-Cox + MLE | [CRAN: refineR](https://cran.r-project.org/package=refineR); [GitHub mirror](https://github.com/cran/refineR) | Reference interval estimation |
| Mobini M et al. "End-to-End SARS-CoV-2 Data Automation." *JALM* 2023;8(1):41-52. [DOI: 10.1093/jalm/jfac109](https://doi.org/10.1093/jalm/jfac109) | Random forest | Supplementary materials | Lab automation pipeline |
| Spies NC et al. "Data-Driven Anomaly Detection Review." *JALM* 2023;8(1):162-179. [DOI: 10.1093/jalm/jfac114](https://doi.org/10.1093/jalm/jfac114) | Review of methods | Supplementary materials | Methods overview |
| Walke D et al. "SBC-SHAP: Accessibility and Interpretability of ML." *JALM* 2025;10(5):1226-1240. [DOI: 10.1093/jalm/jfaf091](https://doi.org/10.1093/jalm/jfaf091) | SHAP explainability | [GitHub](https://github.com/danielwalke/sbc_app) | Explainable sepsis prediction |
| Boerman AW et al. "Predicting Urine Culture Outcomes." *JALM* 2025;10(6):1439-1452. [DOI: 10.1093/jalm/jfaf131](https://doi.org/10.1093/jalm/jfaf131) | XGBoost | [Supplementary materials](https://academic.oup.com/jalm/article/10/6/1439/8313887) | Urine culture stewardship |

## R

#### R Books

- [R in Action: Data Analysis and Graphics with R](https://amzn.to/2CWUHuz)
- [R for Everyone: Advanced Analytics and Graphics](https://amzn.to/2MH1wF4)

#### R Courses Online
- [Intro to R](https://www.datacamp.com/courses/free-introduction-to-r)
- [R Programming on Coursera](https://www.coursera.org/learn/r-programming)
- [Mastering Software Development in R](https://www.coursera.org/specializations/r)

## SQL

- [Intro to SQL](https://www.datacamp.com/courses/intro-to-sql-for-data-science)
- [SQL Tutorial](https://www.w3schools.com/sql/default.asp)
- [SQLite Tutorial](http://www.sqlitetutorial.net/)

## Open-Source Tools & Platforms
- [Zenodo](https://zenodo.org/) – Repository for sharing datasets.
- [Laboratory Data Package](https://dhlab-tseng.github.io/lab/index.html) - Transforms raw EHR laboratory records into datasets
- [Reference Intervals](https://github.com/SandraKla/AdRI) - Calculates age dependent reference intervals
  

## Journals
- [Journal of Applied Laboratory Medicine](https://academic.oup.com/jalm](https://academic.oup.com/jalm/search-results?page=1&q=data%20science&fl_SiteID=6252&SearchSourceType=1&allJournals=1)) - Has some helpful articles on data science
- [Clinical Chemistry Journal](https://academic.oup.com/clinchem/search-results?page=1&q=data%20science&fl_SiteID=6246&SearchSourceType=1&allJournals=1)

## Getting Help
- Join our Data Science and Informatics Community: [artery.myadlm.org/communities](https://artery.myadlm.org/communities/community-home?CommunityKey=d2d3c9b4-b3d6-4eed-ab45-fdb3d4cc8ff4)

## Contributing

We welcome contributions! This is a community-driven resource.

### How to Contribute

1. **Star this repository** to show support
2. **Submit pull requests** for:
  - New tools and resources
  - Updated links or descriptions
  - New datasets or tutorials
  - Corrections or improvements
3. **Open issues** for:
  - Broken links
  - Outdated information
  - Suggestions for new sections
  - **GitHub Issues**: [Report problems or suggest improvements](https://github.com/myADLM/Laboratory-Data-Science-Resources/issues)
  
### Contribution Guidelines

  - **Quality over quantity**: Focus on resources that are actively maintained and well-documented
  - **Educational value**: Prioritize resources that help people learn
  - **Clinical relevance**: Ensure tools address real laboratory medicine challenges
  - **Open access preferred**: Public repositories and free resources first
  - **Include context**: Explain what tools do and who they’re for
  - **Pull Requests**: [Contribute directly](https://github.com/myADLM/Laboratory-Data-Science-Resources/pulls)
  
## Acknowledgments

This repository is maintained by the ADLM Data Science Program with contributions from laboratory professionals, data scientists, and researchers. We thank our community for their commitment to advancing data science in laboratory medicine.

**Stay Connected**
  - LinkedIn: Follow [@myADLM](https://www.linkedin.com/company/myadlm) for the latest news and resources
  - [Annual Data Science Symposium](https://myadlm.org/science-and-research/data-analytics-in-laboratory-medicine/2026-data-science-symposium): Join us for hands-on data science workshops and networking. Stay tuned for registration for 2026.

*Last Updated: December 2025*

