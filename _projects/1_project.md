---
layout: page
title: The Monetary Policy Statement Database (MPSD) 
#description: with background image
#img: assets/img/12.jpg
importance: 1
category: work
related_publications: true
---

**The Monetary Policy Statement Database (MPSD)**

* **Details of the public release coming by Fall of 2025**


* **Authors:** Cory Baird, Jonathan Benchimol, Vira Vyshnevska, Iegor Vyshnevskyi, and Wook Sohn

* **Database Scope:** The MPSD contains approximately 6,746 unique monetary policy statements from 51 central banks worldwide, with data spanning from 1990 to 2024. The coverage and frequency vary by country, with the Hungarian National Bank (MNB), Bank of Japan (BoJ), and European Central Bank (ECB) being the most prolific publishers.

* **Database Architecture:** The MPSD is a comprehensive research infrastructure for analyzing monetary policy statements from 51 central banks. It uses a distributed architecture with **Data Version Control (DVC)** and Git to ensure full data lineage, reproducibility, and collaborative development.

* **Technical Infrastructure:** The project uses a sophisticated technical stack including Pyenv for Python version control, Poetry for package management, and Amazon S3 for data storage. It employs a modular "cookiecutter" folder structure for clear organization.

* **LLM Framework:** An abstract class allows seamless integration of various large language models (LLMs) like Gemini, ChatGPT, and open-source models from Hugging Face. This enables researchers to easily test and reproduce analyses across different AI models.

* **Data Management:** The system is designed for scalability and continuous integration. Automated DVC pipelines and GitHub Actions perform daily checks for new policy statements, ensuring the database is regularly updated while maintaining historical versions.