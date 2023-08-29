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
        - name: R
          description: 90%
          icon: r-project
          icon_pack: fab
        - name: Statistics
          description: 100%
          icon: chart-line
          icon_pack: fas
        - name: Photography
          description: 10%
          icon: camera-retro
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
        - title: Graduate Researcher
          company: University of Kentucky
          company_url: 'https://polisci.as.uky.edu'
          company_logo: UK
          location: Lexington, KY
          date_start: '2019-08-01'
          date_end: '2023-05-06'
          description: |2-

              * Produced over fifteen original quantitative research projects during intensive coursework
              * Built and analyzed datasets with multiple modeling strategies in STATA and R
    
        - title: Primary Instructor
          company: University of Kentucky
          company_url: 'https://polisci.as.uky.edu'
          company_logo: UK
          location: Lexington, KY
          date_start: '2019-08-01'
          date_end: '2023-05-06'
          description: |2-

              * Distilled complex political theories into concise lessons for 50-60 undergraduate students
              * Trained 10 graduate students in advanced quantitative methods and statistical software

        - title: STATA Orientation Leader
          company: University of Kentucky
          company_url: 'https://polisci.as.uky.edu'
          company_logo: UK
          location: Lexington, KY
          date_start: '2022-08-01'
          date_end: '2022-08-01'
          description: |2-

              * Launched the first statistics boot-camp for the University’s Political Science Department
              * Taught a cohort of first year graduate students on intermediate STATA functionality

        - title: Data Hub/Community Impact Intern
          company: United Way of Greater Chattanooga
          company_url: 'https://unitedwaycha.org'
          company_logo: UW
          location: Chattanooga, TN
          date_start: '2018-01-01'
          date_end: '2018-05-01'
          description: |2-

              * Created GIS maps of Chattanooga neighborhoods and crime for community advocacy groups
              * Informed city elected officials on Hamilton Country housing trends with GIS images
    design:
      columns: '2'
    
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
    
        - certificate_url: https://www.datacamp.com/statement-of-accomplishment/track/890e82b3bffb40d4ea3fe9ed4eadfd42262de3ff?raw=1
          date_end: '2023-01-21'
          date_start: ''
          description: 'Statement of Accomplishment for completing Data Scientist in R track'
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: 'Data Scientist in R'
          url: ''

        - certificate_url: https://www.datacamp.com/statement-of-accomplishment/track/1bffc4253b9393bca0ce92aab348965dcc56f152?raw=1
          date_end: '2023-01-17'
          date_start: ''
          description: 'Statement of Accomplishment for completing Data Analyst in SQL track'
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: 'Data Analyst in SQL'
          url: ''
    design:
      columns: '2'
    
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
    
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
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
    
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
    
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
    
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
    
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
