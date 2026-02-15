Training Medical Students in Machine Learning and AI for Cognitive Impairment Research

Project Overview

This repository hosts an education-driven research initiative designed to train medical students in applying machine learning (ML) and AI-assisted interpretation to clinically meaningful questions related to cognitive impairment, with a primary focus on Alzheimer’s disease and Mild Cognitive Impairment (MCI).

The project follows a structured learning path:

Python fundamentals → thinking with data → machine learning → (optional) AI-assisted interpretation

The emphasis is on learning-by-doing through small, reproducible GitHub projects, rather than building a diagnostic or clinical decision-making system.

Core Scientific Question

Is cognitive impairment a biologically homogeneous condition, or can individuals with similar clinical presentations be stratified into distinct molecular subtypes based on transcriptomic profiles?

Machine learning is used to discover molecular patterns, while AI is introduced later to support biological and clinical interpretation.

Learning-Centered Project Design

This project is intentionally designed as a curriculum-style research workflow suitable for beginner-level medical students.

Key principles:

Start with programming and data literacy before introducing biomedical complexity

Progress from exploratory analysis to unsupervised machine learning

Treat AI as a supportive interpretation tool, not as a black box

Produce concrete GitHub outputs at each stage

Project Workflow and Training Phases

Phase 0 – Python Foundations (Weeks 1–3)

Focus: Programming basics and analytical thinking

Goals:

Understand core Python concepts (variables, loops, functions)

Work with tabular data using pandas

Create simple visualizations

Mini GitHub Output:

notebooks/00_python_basics.ipynb

reports/phase0_python_summary.md

Phase 1 – Thinking with Data (Weeks 4–6)

Focus: Data literacy and exploratory analysis

Goals:

Load and inspect public transcriptomic datasets

Understand metadata and clinical variables related to cognitive impairment

Perform basic exploratory data analysis

Mini GitHub Output:

notebooks/01_data_exploration.ipynb

reports/phase1_data_literacy.md

Phase 2 – Machine Learning: Unsupervised Discovery (Weeks 7–12)

Focus: Identifying molecular patterns without clinical labels

Goals:

Feature selection and normalization

Dimensionality reduction (PCA, UMAP)

Clustering and identification of molecular subgroups

Core Scientific Output:

A reproducible notebook demonstrating that individuals with cognitive impairment can be stratified into distinct molecular subtypes

Mini GitHub Output:

notebooks/02_unsupervised_ml.ipynb

reports/phase2_unsupervised_results.md

Phase 3 – Biological Interpretation (Weeks 13–16)

Focus: Linking molecular patterns to biology

Goals:

Identify gene signatures defining each subgroup

Perform pathway and biological process analysis

Write biology-focused interpretations

Mini GitHub Output:

notebooks/03_biological_interpretation.ipynb

reports/phase3_biology.md

Phase 4 – AI-Assisted Clinical Interpretation (Optional Extension)

Focus: Translating results into clinical research context

Goals:

Use AI tools to contextualize findings within existing literature

Address questions such as:

What biological processes does this gene set represent?

How has this biology been linked to cognitive impairment in previous studies?

Mini GitHub Output:

reports/phase4_ai_interpretation.md

This phase is explicitly defined as an extension. If not completed, earlier phases remain scientifically valid.

Repository Structure

cognitive-impairment-ml-ai/
│
├── data/          # Raw and processed data (downloaded via scripts)
├── notebooks/     # Jupyter notebooks for each phase
├── src/           # Optional Python modules
├── reports/       # Phase summaries and final report
├── figures/       # Generated plots and visualizations
├── README.md      # Project description and curriculum
├── requirements.txt
└── .gitignore

Expected Learning Outcomes

By the end of the project, students will be able to:

Read and interpret transcriptomic datasets

Apply unsupervised machine learning to biomedical data

Critically evaluate molecular heterogeneity in cognitive impairment

Communicate results in a clinically meaningful research context

Supervision and Collaboration

Active Training and Project Lead:Busranur Delice

Academic Supervisor:Prof. Dr. Süleyman Yıldırım

Students:

Ahmet

Onuralp

The project is conducted under academic supervision. Progress is tracked via GitHub and Trello using clearly defined milestones and deliverables.

License and Data Use

All analyses rely exclusively on publicly available datasets. Data usage follows the original data providers’ terms and citation requirements.

Contact

Active Training and Project Lead:Busranur Delice

For questions regarding the training process, project structure, or collaboration, please contact:📧 delicebusranur@gmail.com
