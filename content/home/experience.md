---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

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
  - title: Graduate Research Assistant
    company: University of British Columbia
    company_url: 'https://ece.ubc.ca/'
    company_logo: ece
    location: Vancouver, BC
    date_start: '2021-09-01'
    date_end: ''
    # description: |2-
    #     Responsibilities include:
        
    #     * Analysing
    #     * Modelling
    #     * Deploying

  - title: Technical System Analyst
    company: Royal Bank of Canada
    company_url: 'https://www.rbccm.com/en/'
    company_logo: rbc
    location: Toronto, ON
    date_start: '2019-09-01'
    date_end: '2019-12-31'
    description: Worked at RBC Capital Markets

  - title: Software Engineering Co-op
    company: National Research Council
    company_url: 'https://nrc.canada.ca/en/'
    company_logo: nrc
    location: Victoria, BC
    date_start: '2019-01-01'
    date_end: '2019-04-30'
    description: Worked on {{< staticref "https://www.tmt.org/" "newtab" >}} Thirty Meter Telescope {{< /staticref >}} real time controler. 

design:
  columns: '2'
---
