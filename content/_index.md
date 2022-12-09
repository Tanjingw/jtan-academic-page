---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
      
      
    - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Publications'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://doi.org/10.1109/CISAI54367.2021.00060
          date_end: ''
          date_start: '2021'
          description: ''
          organization: Coursera
          organization_url: https://doi.org/10.1109/CISAI54367.2021.00060
          title: Platform Incentives and Willingness of Participant for Investment on Livestreaming E-commerce Model
          url: 'https://doi.org/10.1109/CISAI54367.2021.00060'
    design:
      columns: '2'    
      
      
  - block: experience
    content:
      title: Education
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Postgraduate in Economics
          company: University of Copenhagen
          company_url: 'https://www.ku.dk/english/'
          company_logo: org-gc
          location: Copenhagen, Denmark
          date_start: '2022-09-01'
          date_end: ''
          description: |2-
              Postgraduate courses include:
              * Advanced Microeconometric
              * Advanced Macroeconometric
              * Econometric II
              * Applied Econometric Policy Evaluation
              * Advanced Empirical Macroeconomic Analysis
        - title: Bachelor of Economics
          company: Henan University
          company_url: 'https://iao.henu.edu.cn/yw/Home.htm'
          company_logo: org-x
          location: Zhengzhou, China
          date_start: '2018-09-01'
          date_end: '2022-06-01'
          description: Majoring in International Economics and Trade.
    design:
      columns: '2'
      
      
      
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
      # Contact (add or remove contact options as necessary)
      email: tjw@henu.edu.cn
      directions: Øster Farimagsgade 5, Copenhagen, DK-1353, Denmark
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: tjw_ku
          link: 'https://twitter.com/tjw_ku'

---
