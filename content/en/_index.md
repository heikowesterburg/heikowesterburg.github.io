---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Overview
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: skills
    content:
      title: Skills
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Co-lecturer
          company: INeKO | Institut an der Universität zu Köln
          company_url: 'https://ineko-cologne.com'
          company_logo: 
          location: Cologne
          date_start: '2023-12-17'
          date_end: ''
          description: |2-
              Responsibilities include:
              * Co-facilitation of mediation training modules. 
        - title: Intern
          company: IDA | Institut für Diversity- & Antidiskriminierungsforschung
          company_url: 'https://www.diversity-institut.info/'
          company_logo: 
          location: Cologne
          date_start: '2023-01-27'
          date_end: '2023-12-07'
          description: |2-
              Responsibilities included:
              * Participated in and administratively supported a 200h mediation training. 
              * Participated and contributed scientific inputs in 5 research meetings.
              * Assisted in the facilitation of diversity and inclusion trainings for a large energy company.
        - title: Adviser
          company: BILDERLEBEN | Psychoanalysis of Art 
          company_url: 'https://www.bilderleben.net/en/index.html'
          company_logo: 
          location: Cologne
          date_start: '2021-10-01'
          date_end: ''
          description: |2-
              Responsibilities include:
              * Facilitated >50 guided psychological art tours in three large museums in Cologne. 
              * Recruitment, onboarding, accompaniment, and offboarding of 5 interns.
              * Production of >20 Instagram reels displaying the initiative's work.
              * Team-coordination of appointments.
        - title: Experience-pedagogical Adviser
          company: Quovadis Gesellschaft für Soziale Bildung UG
          company_url: 'https://www.quovadis-soziale-bildung.de/'
          company_logo: 
          location: Heimbach
          date_start: '2021-09-01'
          date_end: '2023-12-31'
          description: |2-
              Responsibilities included:
              * Guided 22 class travels, 2 children’s camps, and 3 family retreats for diverse educational and socioeconomic target groups.
              * Familiarized six new colleagues with the implementation and future leading of four thematically diverse pedagogical programmes.
        - title: Student Assistant
          company: University Hospital Cologne | Center for Memory Disorders
          company_url: 'https://psychiatrie-psychotherapie.uk-koeln.de/klinik/ambulante-behandlung/spezialambulanz-gedaechtnisstoerungen/'
          company_logo: 
          location: Cologne
          date_start: '2021-02-01'
          date_end: '2021-09-30'
          description: |2-
              Responsibilities included:
              * Supported the methodology/steering group in a large-scale literature review revising the S3 guideline *Dementias*.
              * Screened about 5000 research articles based on predefined search terms; evaluated these articles for further guideline use.
              * Assessed methodological quality of about 500 research articles along the NICE guideline as well as CASP checklists.
        - title: Intern
          company: University Hospital Cologne | Center for Memory Disorders
          company_url: 'https://psychiatrie-psychotherapie.uk-koeln.de/klinik/ambulante-behandlung/spezialambulanz-gedaechtnisstoerungen/'
          company_logo: 
          location: Cologne
          date_start: '2020-10-01'
          date_end: '2021-01-31'
          description: |2-
              Responsibilities included:
              * Conducted 50 neuropsychological tests, with consequent diagnostic evaluation and supervised report writing.
              * Summarized diagnostical results for interdisciplinary case conferences, including sorting of about 450 patient files.
              * Edited stimulus templates for a multinational research project on social cognition in dementia.
              * Prepared and analyzed neuropsychological study data from a europewide large-scale multicenter study at four memory centers.
              * Assisted in the organization of a symposium, including the coordination of 1400 invitations.
        - title: Teaching assistant
          company: University Cologne | Department of Psychology 
          company_url: 'https://www.hf.uni-koeln.de/2013'
          company_logo: 
          location: Cologne
          date_start: '2020-10-01'
          date_end: '2023-11-30'
          description: |2-
              Responsibilities included:
              * Facilitated the content-related first semester Bachelor's introductory program in four cohorts, guiding approx. 48 students through a scientific knowledge gain cycle by designing, running, analyzing, and reporting their first small psychological study.
        - title: Intern
          company: BILDERLEBEN | Psychoanalysis of Art 
          company_url: 'https://www.bilderleben.net/en/index.html'
          company_logo: 
          location: Cologne
          date_start: '2020-02-01'
          date_end: '2021-09-30'
          description: |2-
              Responsibilities included:
              * Facilitated approx. 5 guided psychological art tours in three large museums in Cologne. 
              * Training in depth-psychological interviewing.
        - title: Student Assistant
          company: University Cologne | Department of Psychology | Chair of Applied Social Psychology and Decisionmaking
          company_url: 'https://soccco.uni-koeln.de/groups/dohle'
          company_logo: 
          location: Cologne
          date_start: '2019-10-01'
          date_end: '2020-03-31'
          description: |2-
              Responsibilities included:
              * Supervised three psychological experiments, both in the laboratory and online, recruiting 400 participants on site.
              * Conducted three studies as an investigator, both in the laboratory and online, according to standardized procedures.
              * Assisted in the cleaning and preparation of data with up to 40,000 data points for subsequent analyses.
              * Prepared a systematic review of a chair research project using established criteria for transparent and ethical research.
              * Accelerated further organizational support work for research and teaching at the chair.
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.coursera.org
          date_end: ''
          date_start: '2021-01-25'
          description: ''
          icon: coursera
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Neural Networks and Deep Learning
          url: ''
        - certificate_url: https://www.edx.org
          date_end: ''
          date_start: '2021-01-01'
          description: Formulated informed blockchain models, hypotheses, and use cases.
          icon: edx
          organization: edX
          organization_url: https://www.edx.org
          title: Blockchain Fundamentals
          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
        - certificate_url: https://www.datacamp.com
          date_end: '2020-12-21'
          date_start: '2020-07-01'
          description: ''
          icon: datacamp
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: 'Object-Oriented Programming in R'
          url: ''
    design:
      columns: '2'
  #- block: collection
    #id: posts
    #content:
      #title: Recent Posts
      #subtitle: ''
      #text: ''
    # Choose how many pages you would like to display (0 = all pages)
      #count: 5
    # Filter on criteria
      #filters:
        #folders:
          #- post
        #author: ""
        #category: ""
        #tag: ""
        #exclude_featured: false
        #exclude_future: false
        #exclude_past: false
        #publication_type: ""
    # Choose how many pages you would like to offset by
      #offset: 0
    # Page order: descending (desc) or ascending (asc) date.
      #order: desc
    #design:
      # Choose a layout view
      #view: compact
      #columns: '2'
  #- block: portfolio
    #id: projects
    #content:
      #title: Projects
      #filters:
        #folders:
          #- projects
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      #default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      #buttons:
        #- name: All
          #tag: '*'
        #- name: Deep Learning
          #tag: Deep Learning
        #- name: Other
          #tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: moderation.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  #- block: markdown
   # content:
     # title: Gallery
     # subtitle: ''
     # text: |-
      #  {{< gallery album="demo" >}}
    # design:
    # columns: '1'
  #- block: collection
    #id: featured
    #content:
      #title: Featured Publications
      #filters:
        #folders:
          #- publication
        #featured_only: true
    #design:
      #columns: '2'
      #view: card
  #- block: collection
    #content:
      #title: Recent Publications
      #text: |-
        #{{% callout note %}}
        #Quickly discover relevant content by [filtering publications](./publication/).
        #{{% /callout %}}
      #filters:
        #folders:
          #- publication
        #exclude_featured: true
    #design:
      #columns: '2'
      #view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Get in touch
      subtitle:
      text: |-
        Feel free to send an e-mail. I will get back to you as soon as possible. Looking forward!
      # Contact (add or remove contact options as necessary)
      email: heiko.westerburg@outlook.de
      #phone: 888 888 88 88
      #appointment_url: 'https://calendly.com'
      #address:
       # street: 450 Serra Mall
       # city: Stanford
       # region: CA
       # postcode: '94305'
       # country: United States
       # country_code: US
      #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'appointment via e-mail'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      #coordinates:
      #  latitude: '37.4275'
      #  longitude: '-122.1697'  
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM
          link: 'https://twitter.com/heikowes'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      #form:
       # provider: netlify
       # formspree:
        #  id:
       # netlify:
        #  # Enable CAPTCHA challenge to reduce spam?
        #  captcha: false
    design:
      columns: '2'
---
