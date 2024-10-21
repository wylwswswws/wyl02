---
title: 'Home'

type: landing

design:
  # Default section spacing
  spacing: "4rem"

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: biography
    content:
      username: admin
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download Résumé
        url: uploads/resume.pdf
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: kalen-emsley-Bkci_8qcdvQ-unsplash.jpg
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em;'
  - block: experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: true
  - block: skills
    content:
      title: Skills
      username: admin
  - block: awards
    content:
      title: Projects
      username: admin
      items:
        - title: Customer Churn Analysis
          date_start: '2024-06-01'
          date_end: '2024-08-01'
          summary: |
            - Led a comprehensive customer churn analysis using Python, analyzing data from over 7,000 customer records to identify key factors influencing churn rates.
            - Applied the SMOTE method to increase sample size and developed multiple classification models (Logistic Regression, Random Forest, XGBoost) to predict potential customer churn. Achieved an accuracy of 0.9 using XGBoost and created SHAP value charts to explain the model.
            - Designed and implemented A/B testing to validate data-driven strategies for reducing customer churn, comparing pre- and post-intervention churn rates to measure the effectiveness of the campaign.
        - title: Dimension Reduction Analysis
          date_start: '2023-04-01'
          date_end: '2023-05-01'
          summary: |
            - Implemented PCA and CAE techniques for data compression and decompression on 48 videos with different initial conditions related to Reduced Order Modeling & Video Prediction.
            - Compared the reconstruction accuracy of PCA and CAE against various dimensions of the reduced space and found better accuracy for larger dimensions using CAE and for smaller dimensions using PCA.
            - Developed a sequence-to-sequence predictive model (LSTM) for four timesteps in the reduced space and achieved a 92% accuracy rate in decoding predicted results in the full space.
        - title: Pharmacological Discovery and Development of Marine Fungi
          date_start: '2023-08-01'
          date_end: '2023-12-01'
          awarder: Peking University Health Science Center
          summary: |
            - Conducted in-depth bioinformatic analysis to predict the function of biosynthetic gene clusters in marine fungi, adding in the identification of novel bioactive compounds.
            - Applied advanced gene mining techniques to systematically search for potential pharmaceutical candidates, contributing to the discovery of marine-derived natural products with therapeutic potential.
        - title: Data Fusion Research
          date_start: '2022-06-01'
          date_end: '2022-12-01'
          awarder: University of Nottingham
          summary: |
            - Consulted the literature on the history and different approaches to data fusion and identified key trends and advancements.
            - Designed and developed algorithms with Kalman filter and fuzzy logic using C++ for data fusion.
            - Drafted a report summarizing the advantages and challenges of the approaches of data fusion in the project and shared it with the entire research group for further discussion and collaboration.
        - title: Traffic Flow Modeling
          date_start: '2024-01-01'
          date_end: '2024-04-01'
          awarder: University of Nottingham
          summary: |
            - Developed traffic flow models using cellular automata and car-following approaches. Simulated the behavior of vehicles under varying traffic densities and driver reaction times.
    design:
      # Hugo date format
      date_format: 'January 2006'
---
