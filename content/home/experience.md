---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 50

title: Experience
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
  - title: Research Intern
    company: Knowledge Induction Group, IBM Research AI
    company_url: 'https://researcher.watson.ibm.com/researcher/view_group.php?id=7140'
    location: Yorktown Heights, NY
    date_start: '2021-05-20'
    date_end: ''
    description: |2-
        Worked with the Knowledge Induction Team in Summer 2021 on a retrieval-based language model for Fact Verification task. The Retrieval Augmented Generation (RAG) and Dense Passage Retrieval (DPR) based model (Re2G) is the current state-of-art for multiple tasks including Fact Verification on <a href = "https://ai.facebook.com/tools/kilt/">KILT dataset</a> created by Facebook AI. The research is published in <a href="/publication/re2g/">NAACL 2022</a>.</br></br> Currently, I am working with the group on a Table Augmentation task. We are developing a neural retrieval (Dense Passage Retrieval) and span selection based model for cell filling on WikiTables Corpus. Moreover, we are working on a self-supervised architecture for improving DPR training.<a href="/project/retrievalmodels/"> See More ..</a>

  - title: Graduate Student Researcher
    company: Information Extraction and Synthesis Laboratory
    company_url: 'http://www.iesl.cs.umass.edu/'
    location: Amherst, MA
    date_start: '2021-03-01'
    date_end: '2022-05-19'
    description: Worked on a knowledge base question answering project. We developed a semi-parametric model which leverages structural similarity between local neighborhoods of subgraphs. Reasoning paths obtained from these subgraphs created around query entities were used for finding the answer entities. The research extensively focuses on case-based reasoning approach over localized subgraphs. This research is published in <a href = "/publication/cbrsubg/">ICML 2022</a>.

  - title: Machine Learning Intern
    company: Walmart
    company_url: 'https://www.zs.com/'
    location: Bentonville, Arkansas
    date_start: '2020-05-20'
    date_end: '2020-07-20'
    description:
        Worked with the Global People Analytics Team at Walmart Inc. for setting up a Fairness algorithm for Walmart Store hiring across the United States. Implemented a fairness algorithm using PyTorch and redesigned its loss function to improve performance.

  - title: Graduate Researcher
    company: GE Healthcare
    company_url: 'https://www.gehealthcare.in/'
    location: Remote
    date_start: '2020-01-01'
    date_end: '2020-05-20'
    description: |2-
        Worked on utilizing Knowledge Distillation framework to deploy a deep CNN model on-device for carrying out disease detection from X-Ray images. The finding from the semester project were published in Conference on Machine Intelligence in Medical Imaging at Society for Imaging Informatics in Medicine. <a href="https://cdn.ymaws.com/siim.org/resource/resmgr/mimi20/abstracts/knowledge_distill_maryala.pdf"> See More ..</a>

  - title: Data Scientist
    company: ZS Associates
    company_url: 'https://www.zs.com/'
    location: Pune, India
    date_start: '2017-07-01'
    date_end: '2019-07-01'
    description: |2-
        ZS is a healthcare consulting company which devises ML-oriented solutions for Sales and Marketing problems of Pharma companies like Amgen, Novartis, Pfizer. <br /> At the Data Science Lab at ZS Associates, I have worked on gamut of projects ranging from application of NLP and Deep Learning techniques for social media data (Twitter), patient medical history data to using statistical machine learning for dynamic sales targeting and clinical trial optimizations.<a href="/project/biomedicalapplications/"> See More ..</a>
design:
  columns: '2'
---
