---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: 
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  #- block: skills
  #  content:
  #    title: Skills
  #    text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
  #    username: admin
  #  design:
  #    columns: '1'
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
        - title: Professor of Language Technologies and Cognitive Assistants
          company: Technische Hochschule Augsburg
          company_url: 'https://www.tha.de/'
          company_logo: tha
          location: Augsburg, Germany
          date_start: '2022-03-01'
          date_end: ''        
        - title: Chief Scientist
          company: Fraunhofer IIS
          company_url: 'https://www.iis.fraunhofer.de/'
          company_logo: fraunhofer
          location: Erlangen, Germany
          date_start: '2023-01-01'
          date_end: ''
        - title: Senior Scientist and Component Lead for Data Acquisition and Management
          company: Fraunhofer IIS
          company_url: 'https://www.iis.fraunhofer.de/'
          company_logo: fraunhofer
          location: Erlangen, Germany
          date_start: '2020-09-01'
          date_end: '2022-02-15'
        - title: Research Associate
          company: Fraunhofer IIS
          company_url: 'https://www.iis.fraunhofer.de/'
          company_logo: fraunhofer
          location: Erlangen, Germany
          date_start: '2018-09-01'
          date_end: '2022-02-15'          
        - title: Postdoctoral Researcher
          company: Universität des Saarlandes
          company_url: 'https://www.uni-saarland.de/'
          company_logo: uni-saarland
          location: Saarbrücken, Germany
          date_start: '2014-08-01'
          date_end: '2018-08-31'
        - title: PhD student and researcher
          company: Universität Stuttgart
          company_url: 'https://www.uni-stuttgart.de/'
          company_logo: uni-stuttgart
          location: Stuttgart, Germany
          date_start: '2009-08-17'
          date_end: '2014-07-31'
    design:
      columns: '2'
  #- block: accomplishments
  #  content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #    title: 'Accomplish&shy;ments'
  #    subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
  #    date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
   #   items:
    #    - certificate_url: https://www.coursera.org
    #      date_end: ''
    #      date_start: '2021-01-25'
    #      description: ''
    #      icon: coursera
    #      organization: Coursera
    #      organization_url: https://www.coursera.org
    #      title: Neural Networks and Deep Learning
    #      url: ''
    #design:
    #  columns: '2'
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 3
      # Filter on criteria
      filters:
        folders:
          - news
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
  #- block: portfolio
  #  id: projects
  #  content:
  #    title: Projects
  #    filters:
  #      folders:
  #        - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  #    default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
  #    buttons:
  #      - name: All
  #        tag: '*'
  #      - name: Deep Learning
  #        tag: Deep Learning
  #      - name: Other
  #        tag: Demo
  #  design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
  #    columns: '1'
  #    view: showcase
      # For Showcase view, flip alternate rows?
  #    flip_alt_rows: false
  #- block: markdown
  #  content:
  #    title: Gallery
  #    subtitle: ''
  #    text: |-
  #      {{< gallery album="demo" >}}
  #  design:
  #    columns: '1'
  #- block: collection
  #  id: featured
  #  content:
  #    title: Featured Publications
  #    filters:
  #      folders:
  #        - publication
  #      featured_only: true
  #  design:
  #    columns: '2'
  #    view: card
  #- block: collection
  #  content:
  #    title: Recent Publications
  #    text: |-
  #      {{% callout note %}}
  #      You can [filter my publications](./publication/) here. # Quickly discover relevant content by [filtering publications](./publication/).
  #      {{% /callout %}}
  #    filters:
  #      folders:
  #        - publication
  #      exclude_featured: false
  #  design:
  #    columns: '2'
  #    view: citation
  #- block: collection
  #  id: talks
  #  content:
  #    title: Recent & Upcoming Talks
  #    filters:
  #      folders:
  #        - event
  #  design:
  #    columns: '2'
  #    view: compact
  #- block: tag_cloud
  #  content:
  #    title: Popular Topics
  #  design:
  #    columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      #subtitle:
      #text: |-
      #  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: alessandra (dot) zarcone (at) tha (dot) de
      phone: +49 821 5586 3457
      #appointment_url: 'https://calendly.com'
      address:
        street: An der Hochschule 1
        city: Augsburg
        #region: CA
        postcode: '86153'
        country: Germany
        #country_code: US
      #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      #office_hours:
      #  - 'Monday 10:00 to 13:00'
      #  - 'Wednesday 09:00 to 10:00'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
     # coordinates:
     #   latitude: '48.35827135633456'
     #   longitude: '10.906488645341996'  
      #contact_links:
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
      #form:
      #  provider: netlify
      #  formspree:
      #    id:
      #  netlify:
          # Enable CAPTCHA challenge to reduce spam?
      #    captcha: false
    design:
      columns: '2'
---
