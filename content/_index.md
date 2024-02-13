---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: trey-wood
    
  - block: features
    content:
      title: Skills
      items:
        - name: Python
          description: ''
          icon: python
          icon_pack: fab
        - name: R
          description: ''
          icon: r-project
          icon_pack: fab
        - name: SQL
          description: ''
          icon: database
          icon_pack: fas
    
  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Data Scientist
          company: Science Applications International Corporation (SAIC)
          company_url: 'https://www.saic.com'
          company_logo: SAIC
          location: Lexington, KY
          date_start: '2023-10-01'
          date_end: ''
          description: |2-

              * Spearheaded multiple facial recognition algorithm evaluations on behalf of the Department of Homeland Security
              * Utilized cutting-edge cloud computing and analytical methodologies to deliver compelling insights and actionable recommendations
        
        - title: Graduate Researcher
          company: University of Kentucky
          company_url: 'https://polisci.as.uky.edu'
          company_logo: UK
          location: Lexington, KY
          date_start: '2019-08-01'
          date_end: '2023-05-06'
          description: |2-

              * Developed more than fifteen innovative quantitative research projects in rigorous coursework
              * Constructed and analyzed datasets using diverse modeling techniques in STATA and R
    
        - title: Primary Instructor
          company: University of Kentucky
          company_url: 'https://polisci.as.uky.edu'
          company_logo: UK
          location: Lexington, KY
          date_start: '2019-08-01'
          date_end: '2023-05-06'
          description: |2-

              * Condensed intricate political theories into succinct lessons for classes of 50-60 undergraduates
              * Taught graduate statistics to 10 students, covering advanced methods and statistical software

        - title: STATA Orientation Leader
          company: University of Kentucky
          company_url: 'https://polisci.as.uky.edu'
          company_logo: UK
          location: Lexington, KY
          date_start: '2022-08-01'
          date_end: '2022-08-01'
          description: |2-

              * Pioneered the inaugural Statistics Boot Camp for the University’s Political Science Department
              * Instructed a cohort of first-year graduate students in advanced STATA functionality

        - title: Data Hub/Community Impact Intern
          company: United Way of Greater Chattanooga
          company_url: 'https://unitedwaycha.org'
          company_logo: UW
          location: Chattanooga, TN
          date_start: '2018-01-01'
          date_end: '2018-05-01'
          description: |2-

              * Generated GIS maps for Chattanooga neighborhood and crime data for community advocacy
              * Offered housing trend insights to Hamilton Count officials through impactful GIS visualizations
    design:
      columns: '2'
    
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ment'
      title: 'Software Training'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.datacamp.com/statement-of-accomplishment/track/5911e494eb9909e1a17707f9ac41002cd0046b6a?raw=1
          date_end: ''
          date_start: '2023-09-04'
          description: 'Successfully completed the Data Scientist Professional with Python career track on DataCamp.'
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: 'Data Scientist Professional with Python'
          url: ''
    
        - certificate_url: https://www.datacamp.com/statement-of-accomplishment/track/890e82b3bffb40d4ea3fe9ed4eadfd42262de3ff?raw=1
          date_end: ''
          date_start: '2023-01-21'
          description: 'Successfully completed the Data Scientist with R career track on DataCamp'
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: 'Data Scientist with R'
          url: ''

        - certificate_url: https://www.datacamp.com/statement-of-accomplishment/track/1bffc4253b9393bca0ce92aab348965dcc56f152?raw=1
          date_end: ''
          date_start: '2023-01-17'
          description: 'Successfully completed the Data Analyst with SQL career track on DataCamp'
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: 'Data Analyst with SQL'
          url: ''
    
        - certificate_url: https://www.datacamp.com/statement-of-accomplishment/track/180bca800ea843793bb00a3d3b2163b678acdb8f?raw=1
          date_end: ''
          date_start: '2023-01-11'
          description: 'Successfully completed the Data Analyst with Power BI career track on DataCamp'
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: 'Data Analyst with Power BI'

        - certificate_url: https://www.datacamp.com/statement-of-accomplishment/track/a3b7c6327c37da013a9cb3bd334fa0ab372e7352?raw=1
          date_end: ''
          date_start: '2023-09-26'
          description: 'Successfully completed the Data Scientist Professional with R career track on DataCamp'
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: 'Data Scientist Professional with R'
          url: ''

        - certificate_url: https://www.datacamp.com/statement-of-accomplishment/track/152e3eb5d2a8337103647bb1748851da7218ad6f?raw=1
          date_end: ''
          date_start: '2023-10-06'
          description: 'Successfully completed the Machine Learning Scientist with R career track on DataCamp'
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: 'Machine Learning Scientist with R'
          url: ''
    design:
      columns: '2'
    
#  - block: collection
#    id: posts
#    content:
#      title: Recent Posts
#      subtitle: ''
#      text: ''
#      # Choose how many pages you would like to display (0 = all pages)
#      count: 5
#      # Filter on criteria
#      filters:
#        folders:
#          - post
#        author: ""
#        category: ""
#        tag: ""
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ""
#      # Choose how many pages you would like to offset by
#      offset: 0
#      # Page order: descending (desc) or ascending (asc) date.
#      order: desc
#    design:
#      # Choose a layout view
#      view: compact
#      columns: '2'
    
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Kaggle
          tag: Kaggle
        - name: Fun
          tag: Fun
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
    
#  - block: markdown
#    content:
#      title: Gallery
#      subtitle: ''
#      text: |-
#        {{< gallery album="demo" >}}
#    design:
#      columns: '1'
    
 # - block: portfolio
 #   id: papers
  #  content:
   #   title: Working Papers
    #  filters:
     #   folders:
      #    - working_papers
       # featured_only: false
   # design:
    #  columns: '2'
     # view: card
    
  - block: portfolio
    id: papers
    content:
      title: Working Papers 
    #  text: |-
       # {{% callout note %}}
       # Quickly discover relevant content by [filtering publications](./publication/).
       # {{% /callout %}}
      filters:
        folders:
          - working_papers
        exclude_featured: true
    design:
      columns: '2'
      view: citation
    
#  - block: collection
#    id: talks
#    content:
#      title: Recent & Upcoming Talks
#      filters:
#        folders:
#          - event
#    design:
#      columns: '2'
#      view: compact
#  - block: tag_cloud
#    content:
#      title: Popular Topics
#    design:
#      columns: '2'

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Feel free to reach out! I'm looking forward to answering industry or research questions. 
      # Contact (add or remove contact options as necessary)
      email: totreywood@aol.com
      # phone: 888 888 88 88
      # appointment_url: 'https://calendly.com'
      address:
      # street: 450 Serra Mall
        city: Lexington
        region: KY
      # postcode: '94305'
        country: United States
        country_code: US
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      # contact_links:
      #  - icon: twitter
      #    icon_pack: fab
      #    name: DM Me
      #    link: 'https://twitter.com/Twitter'
      #  - icon: skype
      #    icon_pack: fab
      #    name: Skype Me
      #    link: 'skype:echo123?call'
      #  - icon: video
      #    icon_pack: fas
      #    name: Zoom Me
      #    link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'

---
