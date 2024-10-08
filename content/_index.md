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
  - block: experience
    id: edu
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
        - title: Ph.D. in Applied Engineering
          company: University of Antwerp
          company_url: 'https://www.uantwerpen.be/en/'
          company_logo: 
          location: Belgium
          date_start: '2021-05-01'
          date_end: ''
          description: 
        - title: M.Sc. in Physics
          company: Indian Institute of Technology Indore
          company_url: 'https://www.iiti.ac.in/'
          company_logo: 
          location: India
          date_start: '2019-07-01'
          date_end: '2021-07-01'
          description: 
        - title: B.Sc. (H) in Physics
          company: University of Delhi
          company_url: 'https://www.du.ac.in/'
          company_logo: 
          location: India
          date_start: '2015-07-01'
          date_end: '2018-07-01'
          description: 
    design:
      columns: '2'
  - block: experience
    id: exp
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
        - title: Research Internship
          company: GIM - Geographic Information Management
          company_url: 'https://www.gim.be/en'
          company_logo: 
          location: Belgium
          date_start: '2024-04-02'
          date_end: '2024-07-31'
          description: 
    design:
      columns: '2'
  # - block: accomplishments
  #   id: acc
  #   content:
  #     # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #     title: 'Schools & Courses'
  #     subtitle:
  #     # Date format: https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     # Accomplishments.
  #     #   Add/remove as many `item` blocks below as you like.
  #     #   `title`, `organization`, and `date_start` are the required parameters.
  #     #   Leave other parameters empty if not required.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - certificate_url: https://coursera.org/share/338861368404ff73cd125e26be05afde
  #         date_end: ''
  #         date_start: '2021-04-25'
  #         description: ''
  #         organization:  DeepLearning.AI & Coursera
  #         organization_url: https://www.coursera.org/learn/deep-neural-network
  #         title: 'Improving Deep Neural Networks: Hyperparameter Tuning, Regularization and Optimization'
  #         url: ''
  #       - certificate_url: https://drive.google.com/file/d/1aBrprczDEhivyja4-fid8QNwyUqZ-JDx/view?usp=sharing
  #         date_end: ''
  #         date_start: '2019-04-25'
  #         description: ''
  #         organization:  IIT Indore & Google
  #         organization_url: https://www.iiti.ac.in/
  #         title: 'Google AI, Explore ML Beginner Track'
  #         url: ''
  #       - certificate_url: https://coursera.org/share/e86f19501dbf617a89b68b2d5d513bd7
  #         date_end: ''
  #         date_start: '2016-07-25'
  #         description: ''
  #         organization:   The University of Tokyo & Coursera
  #         organization_url: https://www.coursera.org/learn/big-bang
  #         title: 'From the Big Bang to Dark Energy'
  #         url: ''
  #       - certificate_url: https://coursera.org/share/a24c63482524f3252b5fe888c8ca6fb0
  #         date_end: ''
  #         date_start: '2019-08-25'
  #         description: ''
  #         organization:  Stanford University & Coursera
  #         organization_url: https://www.coursera.org/specializations/machine-learning-introduction
  #         title: 'Machine Learning'
  #         url: ''
  #       - certificate_url: https://coursera.org/share/fbe403142fe0e225411ce2d5d184abcf
  #         date_end: ''
  #         date_start: '2021-03-25'
  #         description: ''
  #         organization:  DeepLearning.AI & Coursera
  #         organization_url: https://www.coursera.org/learn/neural-networks-deep-learning
  #         title: 'Neural Networks and Deep Learning'
  #         url: ''
  #       - certificate_url: https://drive.google.com/file/d/1WSr3cObQ0hnj_ZrapXQEze-WrMFU5pmy/view?pli=1
  #         date_end: ''
  #         date_start: '2022-09-16'
  #         description: ''
  #         organization: University of Sheffield
  #         organization_url: https://www.sheffield.ac.uk/
  #         title: Gaussian Process and Uncertainty Quantification Summer School 2022
  #         url: ''
  #   design:
  #     columns: '2'
  # - block: portfolio
  #   id: projects
  #   content:
  #     title: Projects
  #     filters:
  #       folders:
  #         - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
    #   default_button_index: 0
    #   # Filter toolbar (optional).
    #   # Add or remove as many filters (`filter_button` instances) as you like.
    #   # To show all items, set `tag` to "*".
    #   # To filter by a specific tag, set `tag` to an existing tag name.
    #   # To remove the toolbar, delete the entire `filter_button` block.
    #   buttons:
    #     - name: All
    #       tag: '*'
    #     - name: Deep Learning
    #       tag: Deep Learning
    #     - name: Other
    #       tag: Demo
    # design:
    #   # Choose how many columns the section has. Valid values: '1' or '2'.
    #   columns: '1'
    #   view: showcase
    #   # For Showcase view, flip alternate rows?
    #   flip_alt_rows: false

  - block: collection
    id: featured
    content:
      title: Publications & Preprints
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: compact
  # - block: collection
  #   id: posts
  #   content:
  #     title: Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'
  # - block: collection
  #   id: talks
  #   content:
  #     title: Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact
  - block: markdown
    id: mm
    content:
      title: Gallery
      subtitle: 'Reach out for collaboration!'
      text: |-
        {{< gallery album="demo">}}      

    design:
      columns: '2'
---
