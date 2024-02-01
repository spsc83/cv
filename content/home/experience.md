---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 35

title: Working Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Senior Data Engineer
    company: GeneDx | Sema4
    company_url: 'https://www.genedx.com'
    company_logo: genedx
    location: Remote, USA
    date_start: '2022-04-15'
    date_end: ''
    description: |2-
        As a senior data engineer, have been involved in multiple projects. 
        * Azure data lake project: This data lake is for GeneDx’s exome and genome sequencing data. To build the data lake from scratch I developed a data management system called Mocha. My role encompassed the comprehensive development of Python scripts for Mocha's ETL pipeline, data archival and retrieval, database design, front-end design and development, document automation updates, CI/CD with GitHub actions, as well as the design and execution of unit tests and function tests. Here is the tech stack of the Azure data lake: Python, Django, Bootstrap, jQuery, HTML, SQLite, PostgreSQL, and Azure cloud storage. 
        * The cloud data send-out system: It is a system that automatically delivers clinical data to GeneDx's customers' cloud storage based on the requirements specified by Genetic Counselors. It supports various cloud storage options, including AWS S3, Azure cloud storage, Google Cloud Platform, sFTP, and Citrix Sharefile. Throughout this project, I collaborated closely with Genetic Counselors to gather their requirements, and subsequently, I developed the complete script and conducted unit tests and function tests. This project helps the Genetic Counselors to reduce the turnaround time for data requests from 1 month to 1 week.
        * QC Service Project: The QC service is a web application functioning as the primary decision engine, utilizing defined metrics per SOP (Standard Operating Procedure) and delivering decision outcomes. In this project, I design the data module according to the requirment of the team lead for the QC decision engine and developed the Restful API service using the FastAPI framework.
        * WGS in Cloud Project: This initiative involves the development of GeneDx's new WGS pipeline within the AWS environment. I am fortunate to be involved in this project, where my responsibilities encompass managing data transfer operations between AWS S3 and on-premises storage systems. Leveraging Python scripting, I successfully implemented the IAM roles anywhere method, establishing a secure mechanism for the application to acquire temporary AWS credentials. Additionally, I effectively developed data transfers between AWS S3 and on-premises storage systems with AWS Boto3.


  - title: Programmer
    company: Albert Einstein College of Medicine, Genetics Department
    company_url: 'https://einsteinmed.edu'
    company_logo: einstein
    location: Bronx New York, USA
    date_start: '2019-04-15'
    date_end: '2022-03-31'
    description: |2-
        As a programmer, I implement multiple projects and help the postdocs, professors, and labs with their projects. 
        * SomaMutDB is a website database that compiles all available somatic mutations data in healthy tissues including in-house data and publicly available data up to date. It provides multiple functions such as data visualization, data browsing, signature analyzing and data download. I implemented 6 tools including MutationalPatterns, SomaticSignatures, hdp, signature_tools_lib, Sigprofiler, and mmsig in the signature analyzing module of the website. I designed the structure of the website system, programmed the front end and the back end with Python, HTML, CSS, JavaScript, jQuery, SQL and etc. And I set up the MySQL database for the website. The paper of this website database was published on Nucleic Acids Research. I am the co-first author.
        * PEA (phasing, enhanced reference genome and assembly) method is to identify genome structural variations from single-cell whole-genome sequencing (WGS) data. I designed the whole pipeline and programmed the pipeline with Python and Bash script under the supervision of a postdoc. The paper of PEA method was submitted to Nature Methods. I am the co-first author.
        * I refactored and optimized a single-cell variant calling pipeline for one lab with Python. I simplified the whole pipeline from 200 commands and almost 800 parameters per cell to just 1 command and 4 parameters per cell, reduced the IO by 92.8%. And I sped up the pipeline by 10 times with parallel running technic. I also fixed the bugs in the previous version, and make it available for calling short insertions and deletions (INDELs).
        * I expanded the DNA mapping pipeline’s availability from only for the human genome to 7 different species for one lab. And I implemented the pipeline for 48 samples of 6 different species for the lab.
        * I annotated and classified SNVs and indels identified from the WGS data in >1500 22q11.2 deletion syndrome patients into damaging LoF, damaging frameshift, damaging Missense, benign Missense, splice-disrupting, synonymous variants using multiple state-of-art algorithms, software, and public databases including VEP, Bystro, spliceAI, etc. under the supervision of a postdoc. I built an SQLite database for it. And I implemented multiple statistical tests including, for example, Fisher’s exact test, binomial test, variant-Set Test for Association using Annotation infoRmation (STAAR) based on the database. The paper of the project is on the way and I am the second author.
        * I built the lab websites for two PIs on the wowchemy and WIX platforms.
        * I translated the global coordination level (GCL) analysis method from MATLAB to R for one postdoc.
        * I developed a job submission website for students and postdocs in Albert Einstein College of Medicine to facilitate their computational analyze.

  - title: Volunteer and waiting for my H1b visa approval
    company: Albert Einstein College of Medicine, Genetics Department
    company_url: 'https://einsteinmed.edu'
    company_logo: einstein
    location: Bronx New York, USA
    date_start: '2018-06-01'
    date_end: '2019-04-14'
    description: As a volunteer I helped postdocs to implement their analyzing pipelines on HPC. And I learned necessary knowledge (single-cell WGS sequencing, DNA mapping, variant calling, etc.) for optimizing the SNV caller for single-cell sequencing data.
        
  - title: Project Manager
    company: China UnionPay Merchant Services Company, Ltd., Ufood Division
    company_url: 'https://www.chinaums.com/shfw/hyjjfa/canyin/'
    company_logo: ums
    location: Shanghai, China
    date_start: '2016-12-01'
    date_end: '2017-11-01'
    description: Ufood provides solutions for restaurant management. As a project manager, I supervised 10 employees and managed the accounts of over 1000 different vendors. We designed applications for PC, tablet, and POS terminal, website for restaurant management, in addition to creating customized WeChat accounts for vendors and customers to facilitate reservations, ordering, and payments. 

  - title: Programmer
    company: China UnionPay Merchant Services Company, Ltd., MIS-POS (merchant integrated system – point of sale) Department
    company_url: 'https://www.chinaums.com'
    company_logo: ums2
    location: Shanghai, China
    date_start: '2012-05-21'
    date_end: '2016-12-01'
    description: I worked with senior personnel of international companies (Vanguard, McDonald's, Yum, NBA Play zone, Bestseller, ZARA, Decathlon, etc) to develop and implement their integrated payment system for the Chinese market. Our module is deployed on the computers of cashiers or vending machines to drive hardware and communicate with bank servers securely. 
design:
  columns: '2'
---
