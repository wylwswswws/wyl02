---
# Display name
title: Alan (Yulun) Wu

# Name pronunciation (optional)
#name_pronunciation: Yulun Wu

# Full name (for SEO)
first_name: Yulun
last_name: Wu

# Status emoji
#status:
  #icon: ☕️

# Is this the primary user of the site?
superuser: true

# Role/position/tagline
role: Data Scientist | ML Enthusiast | Specializing in Predictive Analytics & Data Solutions
# Organizations/Affiliations to display in Biography blox
organizations:
  - name: University of Pennsylvania
    url: https://www.upenn.edu/

# Social network links
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
# Social network links
profiles:
  - icon: at-symbol
    url: 'mailto:wyulun@seas.upenn.edu'
    label: E-mail Me
  - icon: brands/github
    url: https://github.com/wylwswswws
  - icon: brands/linkedin
    url: https://www.linkedin.com/in/yulunwu02

education:
  - area: Master of Science in Data Science
    institution: University of Pennsylvania
    date_start: 2024-08-27
    date_end: 2026-05-20
    summary: |
      Pursuing advanced studies in data science, applied machine learning, and statistical modeling. 
      
  - area: Bachelor of Science (Honours) in Mathematics with Applied Mathematics
    institution: University of Nottingham
    date_start: 2020-09-27
    date_end: 2024-07-14
    summary: |
      - Overall GPA: 3.90/4.00 | First Class | Provost’s Scholarship (06/2021)
      - Specialized in probability theory, statistical methods, and mathematical modeling. 
work:
  - position: Senior Analyst
    company_name: Wharton Analytics Fellows
    company_url: 'https://ai-analytics.wharton.upenn.edu/for-students/wharton-analytics-fellows/'
    date_start: 2025-02-13
    date_end: 2025-04-05
    summary: |
      - Collaborating within the Wharton AI & Analytics Accelerator Team to develop an AI-driven tool that predicts sales trends for Spencer’s Gifts, focusing on t-shirts and other trendy items. 
      - Analyzing historical and current sales data to forecast changes in sales magnitude, timing, and revenue impact.
      - Preparing weekly reports with actionable insights for the client’s Planning Team to support strategic decision-making. 
  - position: Data Analyst Intern
    company_name: Novo Nordisk (China) Pharmaceuticals Co., Ltd.
    company_url: 'https://www.novonordisk.com.cn/'
    date_start: 2023-06-18
    date_end: 2023-09-15
    summary: |
      - Collaborated with Microsoft China on a company-wide SQL database migration project regarding to customer representative behavior, consolidating five databases into one. Reduced query runtime by 30% through SQL optimization, increasing database migration efficiency.
      - Leveraged Python and statistical techniques to process and analyze historical sales promotion data for pharmaceuticals. Generated predictive insights that improved promotional budget allocation accuracy by 20%, contributing to $100,000 in cost savings. 
      
  - position: Data Analyst Intern
    company_name: Central Institute of Mental Health
    company_url: 'https://www.zi-mannheim.de/en/index.html'
    date_start: 2023-01-15
    date_end: 2023-05-15
    summary: |
      - Explored neurophysiological activity under stress conditions using a neuropsychological paradigm and combining functional MRI and heart rate signal (in collaboration with the Max Planck Institute of Psychiatry). 
      - Analyzed fMRI-BOLD and photoplethysmogram signals respectively utilizing generalized linear models (GLM) and wabp algorithm in MATLAB and found brain regions’ interaction with the autonomic nervous system under stress. 
      - Collaborated with a multidisciplinary team of researchers to prepare and deliver a comprehensive presentation at an academic seminar at Heidelberg University, engaging over 20 scholars and researchers in discussions about findings. 
# Skills
skills:
  - name: Software Skills
    items:
      - name: 'Python'
        icon: devicon/python
      - name: R
        icon: devicon/rstudio
      - name: SQL
        icon: devicon/mysql
      - name: MATLAB
        icon: devicon/matlab
      - name: C/C++
        icon: custom/C++
      - name: PowerBI
        icon: custom/PowerBI
      - name: Tableau
        icon: custom/Tableau
  - name: Analytic Skills
    items:
      - name: Statistical Modeling
      - name: A/B Testing
      - name: Causal Inference
      - name: Data Cleaning
      - name: Data Mining
      - name: Data Visualization
      - name: Data Engineering


# Projects
awards:
- title: News Source Classification
  # url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  date: '2024-12-01'
  awarder: University of Pennsylvania
  summary: |
    - Developed binary classification models to predict news headlines’ sources (Fox News vs. NBC News), leveraging advanced NLP techniques to reveal stylistic and vocabulary differences.
    - Web-scraped and processed 3,800+ headlines using Python, transforming text data via TF-IDF and Word2Vec vectorization, and enriching features through bigram/trigram extraction.
    - Built and tuned a Bidirectional LSTM model (80% accuracy), outperforming a baseline Logistic Regression (66%); mitigated overfitting through extensive hyperparameter optimization.

- title: Credit Card Fraud Prediction
  # url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  date: '2024-12-01'
  awarder: University of Pennsylvania
  summary: |
    - Led a credit card fraud prediction project using Python and SQL, analyzing over 50,000 transaction records to identify key patterns and factors contributing to fraudulent activities, such as transaction amount, location anomalies, and user behavior.
    - Utilized SMOTE and ADASYN methods to address data imbalance, increasing sample size for robust model training. Enhanced feature extraction by leveraging Long Short-Term Memory (LSTM) networks for detecting temporal patterns.
    - Built and evaluated classification models including Logistic Regression, Random Forest, and XGBoost, achieving a 90% prediction accuracy with XGBoost. Explained model predictions using SHAP value charts, enabling stakeholders to understand key drivers of fraud.

- title: Customer Churn Analysis 
  # url: https://www.coursera.org/learn/neural-networks-deep-learning
  date: '2024-09-01'
  # awarder: 'June 2023 - August 2023'
  summary: |
    - Led a comprehensive customer churn analysis using Python, analyzing data from over 7,000 customer records to identify key factors such as contract length, monthly charges and customer service response time influencing churn rates. 
    - Applied the SMOTE method to increase sample size and developed multiple classification models (Logistic Regression, Random Forest, XGBoost) to predict potential customer churn. Achieved an accuracy of 0.9 using XGBoost and created SHAP value charts to explain the model. 
    - Designed and implemented A/B testing to validate data-driven strategies for reducing customer churn, comparing pre-and post-intervention churn rates to measure the effectiveness of the campaign. 

#- title: Traffic Flow Modeling
#  url: https://github.com/wylwswswws/Traffic-Flow-Modeling
#  date: '2024-04-01'
#  awarder: University of Nottingham
#  summary: |
#    - Developed and implemented traffic flow models, including cellular automata, car-following models, and partial differential equations (PDE), to simulate realistic traffic dynamics across various densities and driver behaviors.
#    - Conducted extensive simulations to assess the impact of different traffic densities and road conditions, optimizing model parameters for enhanced predictive accuracy.
#    - Analyzed and identified optimal density levels and behavioral factors that aligned closely with real-world traffic patterns, providing recommendations to improve flow and reduce congestion.

#- title: Pharmacological Discovery and Development of Marine Fungi
  # url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
#  date: '2023-12-01'
#  awarder: Peking University Health Science Center
#  summary: |
#    - Conducted in-depth bioinformatic analysis to predict the function of biosynthetic gene clusters in marine fungi, adding in the identification of novel bioactive compounds. 
#    - Applied advanced gene mining techniques to systematically search for potential pharmaceutical candidates, contributing to the discovery of marine-derived natural products with therapeutic potential. 

- title: Dimension Reduction Analysis
  # url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  date: '2023-05-01' 
  # awarder: 'May 2023 - June 2023'
  summary: |
    - Implemented PCA and CAE techniques for data compression and decompression on 48 videos with different initial conditions related to Reduced Order Modeling & Video Prediction. 
    - Compared the reconstruction accuracy of PCA and CAE against various dimensions of the reduced space and found better accuracy for larger dimensions using CAE and for smaller dimensions using PCA. 
    - Developed a sequence-to-sequence predictive model (LSTM) for four timesteps in the reduced space and achieved a 92% accuracy rate in decoding predicted results in the full space. 

#- title: Data Fusion Research
  # url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
#  date: '2022-12-01'
#  awarder: University of Nottingham
#  summary: |
#    - Consulted the literature on the history and different approaches to data fusion and identified key trends and advancements. 
#    - Designed and developed algorithms with Kalman filter and fuzzy logic using C++ for data fusion. 
#    - Drafted a report summarizing the advantages and challenges of the approaches of data fusion in the project and shared it with the entire research group for further discussion and collaboration. 

---

Hello! I’m Alan Wu, a graduate student in Data Science at the University of Pennsylvania and a Mathematics alumnus from the University of Nottingham. My passion lies in transforming complex data into actionable insights using advanced analytics, statistical modeling, and scalable data engineering tools. I’m dedicated to harnessing data-driven strategies that spark innovation and deliver tangible business impact. When I’m not coding or analyzing datasets, you can find me exploring the latest data science research or refining my visualization skills to bring stories to life through data. Welcome to my space – feel free to explore my projects and connect!
