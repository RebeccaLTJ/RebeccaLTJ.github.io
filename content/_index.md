---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2026-01-05
type: landing

sections:
  # Developer Hero - Gradient background with name, role, social, and CTAs
  - block: dev-hero
    id: hero
    content:
      username: me
      greeting: "Hi, I'm"
      show_status: true
      show_scroll_indicator: true
      typewriter:
        enable: true
        prefix: "I apply"
        strings:
          - "machine learning to Parkinson's disease"
          - "statistical modelling to real-world data"
          - "causal gene regulatory networks"
          - "multi-cohort and multi-omics data analysis"
        type_speed: 70
        delete_speed: 40
        pause_time: 2500
      cta_buttons:
        - text: View Projects
          url: "#projects"
          icon: arrow-down
        - text: Contact Me
          url: "#contact"
          icon: envelope
    design:
      style: centered
      avatar_shape: circle
      animations: true
      background:
        color:
          light: "#fafafa"
          dark: "#0a0a0f"
      spacing:
        padding: ["6rem", "0", "4rem", "0"]
  
  # Filterable Portfolio - Alpine.js powered project filtering
  - block: portfolio
    id: projects
    content:
      title: "Research Projects"
      subtitle: "Machine learning and statistical modelling in Parkinson's disease"
      count: 0
      filters:
        folders:
          - projects
      buttons:
        - name: All
          tag: '*'
        - name: Machine Learning
          tag: ML
        - name: Real-World Evidence
          tag: RWE
        - name: Bioinformatics
          tag: bioinfo
        - name: Statistics
          tag: stat
      default_button_index: 0
      # Archive link auto-shown if more projects exist than 'count' above
      # archive:
      #   enable: false  # Set to false to explicitly hide
      #   text: "Browse All"  # Customize text
      #   link: "/work/"  # Custom URL
    design:
      columns: 3
      background:
        color:
          light: "#ffffff"
          dark: "#0d0d12"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]
  
  # Visual Tech Stack - Icons organized by category
  - block: tech-stack
    id: skills
    content:
      title: "Methods & Tools"
      subtitle: "Techniques used in my research"
      categories:
        - name: Methods
          items:
            - name: Machine Learning
              icon: hero/cpu-chip
            - name: Longitudinal Data Analysis
              icon: hero/chart-bar
            - name: Gene regulatory network
              icon: hero/share
        - name: Tools
          items:
            - name: Python
              icon: devicon/python
            - name: R
              icon: devicon/r
            - name: SAS
              icon: hero/cpu-chip
            - name: SQL
              icon: hero/circle-stack
            - name: HPC
              icon: hero/server
        - name: Domains
          items:
            - name: Real-World Evidence
              icon: hero/circle-stack
            - name: Neurodegenerative Disorders
              icon: hero/brain
            - name: Oncology
              icon: hero/magnifying-glass
    design:
      style: grid
      show_levels: false
      background:
        color:
          light: "#f5f5f5"
          dark: "#08080c"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]
  
  # Experience Timeline
  - block: resume-experience
    id: experience
    content:
      title: Experience
      date_format: Jan 2006
      items:
        - title: Postdoctoral Researcher
          company: Luxembourg Centre for Systems Biomedicine (LCSB)
          company_url: 'https://www.uni.lu/lcsb-en/'
          company_logo: ''
          location: Belval, Luxembourg
          date_start: '2025-04-01'
          date_end: ''
          description: |2-
            * Develop knowledge-guided and multi-scale machine learning frameworks integrating clinical data and multi-omics data
            * Construct and analyze gene regulatory networks to enhance biological interpretability
            * Apply causal machine learning approaches to identify robust risk factor across heterogeneous datasets
            * Integrate high-dimensional data (e.g., transcriptomics, metabolomics) for disease modelling and patient stratification
            * Collaborate with interdisciplinary teams across computational biology, data science, and clinical research
        - title: Doctoral Researcher
          company: Luxembourg Centre for Systems Biomedicine (LCSB)
          company_url: 'https://www.uni.lu/lcsb-en/'
          company_logo: ''
          location: Belval, Luxembourg
          date_start: '2022-02-01'
          date_end: '2025-03-31'
          description: |2-
            * Developed machine learning and time-to-complication models to predict motor and cognitive complications
            * Performed cross-cohort validation across independent datasets to assess robustness and generalizability
            * Identified clinical predictors of disease progression using large-scale longitudinal datasets
            * Applied interpretable machine learning methods to improve transparency and clinical relevance
            * Designed analytical pipelines for integrating multi-source clinical data
        - title: Real-World Evidence (RWE) Data Scientist
          company: Novartis
          company_url: 'https://www.novartis.com/'
          company_logo: ''
          location: Petaling Jaya, Malaysia
          date_start: '2019-07-01'
          date_end: '2021-11-30'
          description: |2-
            * Led RWE analytics projects across neuroscience, oncology, cardiovascular, and rare diseases
            * Analyzed large-scale datasets including MarketScan, JMDC, MDV, hospital and registry data
            * Developed machine learning models and statistical analyses for outcome prediction and patient stratification
            * Built interactive dashboards (R shiny, IHD) to communicate insights to cross-functional stakeholders
            * Supported evidence generation and decision-making for internal teams
        - title: Data Scientist
          company: Boobook world
          company_url: 'https://www.boobook.world/'
          company_logo: ''
          location: Remote (Belgium)
          date_start: '2018-04-01'
          date_end: '2019-07-31'
          description: |2-
            * Applied advanced statistical methods (e.g., segmentation, MaxDiff, Gabor-Granger, brand mapping) to derive insights
            * Developed reusable R functions and analytical pipelines to improve team efficiency
            * Built dashboards (Power BI) to visualize and communicate results
            * Collaborated with stakeholders to translate business questions into analytical solutions
        - title: SAS Programmer
          company: NMG Consulting
          company_url: 'https://www.nmg-consulting.com/'
          company_logo: ''
          location: Kuala Lumpur, Malaysia
          date_start: '2016-04-01'
          date_end: '2019-07-31'
          description: |2-
            * Built and managed automated reporting pipelines for multiple international projects
            * Performed statistical analysis and data validation to ensure accuracy and consistency
            * Improved reporting efficiency through process automation and optimization
            * Supported ad hoc analytical requests and data investigation
        - title: Research Assistant
          company: Universiti Putra Malaysia
          company_url: 'https://upm.edu.my/'
          company_logo: ''
          location: Serdang, Malaysia
          date_start: '2013-09-01'
          date_end: '2015-08-31'
          description: |2-
            * Assisted in teaching SAS and R programming to undergraduate students
            * Guided students in developing statistical programs and solving applied problems
            * Provided support in understanding statistical concepts and data analysis workflows
        - title: Demonstrator
          company: Universiti Putra Malaysia
          company_url: 'https://upm.edu.my/'
          company_logo: ''
          location: Serdang, Malaysia
          date_start: '2013-01-01'
          date_end: '2013-06-30'
          description: |2-
            * Conducted tutorial sessions and guided students in solving statistical problems
            * Explained core statistical concepts and methodologies through practical examples
            * Provided one-on-one academic support to improve student understanding
    design:
      columns: '1'
      background:
        color:
          light: "#ffffff"
          dark: "#0d0d12"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]

  # Recent Blog Posts
  - block: collection
    id: blog
    content:
      title: Recent Posts
      subtitle: "Machine learning, real-world data, and Parkinson's disease"
      text: ''
      filters:
        folders:
          - blog
        exclude_featured: false
      count: 3
      order: desc
    design:
      view: card
      columns: 3
      background:
        color:
          light: "#f5f5f5"
          dark: "#08080c"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]
  
  # Recent Publications
  - block: collection
    id: publications
    content:
      title: Publications
      subtitle: Peer-reviewed research outputs
      filters:
        folders:
          - publications
        exclude_featured: false
      count: 10
      order: desc
    design:
      view: citation
      columns: 1
      background:
        color:
          light: "#f5f5f5"
          dark: "#08080c"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]
  
  # Contact Section
  - block: contact-info
    id: contact
    content:
      title: Get In Touch
      subtitle: "Research collaboration and career opportunities"
      text: |-
        I am open to opportunities in, machine learning scientist, real-world evidence, biomedical data science, neurodegenerative disease research, bioinformatics

        Feel free to reach out for collaboration or roles.
      email: jiinjiinloo@gmail.com
      autolink: true
    design:
      columns: '1'
      background:
        color:
          light: "#ffffff"
          dark: "#0d0d12"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]
  
  # CTA Card
  - block: cta-card
    content:
      title: "Open to Opportunities"
      text: |-
        I'm open to opportunities in **Real-World Evidence (RWE) data scientist**, **Machine learning scientist**, or **biomedical data scientist** roles.
        
        Feel free to reach out for collaboration or roles.
      button:
        text: 'Download Resume'
        url: uploads/CV_REBECCA_LOO_TING_JIIN.pdf
        new_tab: true
    design:
      card:
        # Light mode: soft pastel theme gradient | Dark mode: rich deep gradient
        css_class: 'bg-gradient-to-br from-primary-200 via-primary-100 to-secondary-200 dark:from-primary-600 dark:via-primary-700 dark:to-secondary-700'
        text_color: dark
      background:
        color:
          light: "#f5f5f5"
          dark: "#08080c"
      spacing:
        padding: ["4rem", "0", "6rem", "0"]
---
