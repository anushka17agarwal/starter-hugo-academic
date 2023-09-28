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
      username: admin
  - block: features
    content:
      title: Skills
      items:

        - name: Deep Learning
          description: Generative AI| 3D Reconstruction | Neural Rendering | Multi Modal ML | Video Synthesis | Langchain |
          icon: centos
          icon_pack: fab
          
        - name: Frameworks
          description: Tensorflow - Keras | Pytorch | GANs | Vision Transformers | NERFs | Volume Rendering | 
          icon: laptop-code
          icon_pack: fas
          
        - name: Databases
          description: MongoDB (PyMongo) | Firebase (Pyrebase) | MYSQL (SQLite3)
          icon: database
          icon_pack: fas
          
        - name: Web Frameworks 
          description: Django |Flask | Streamlit | FastAPI | Postman | HTML | CSS |
          icon: codepen
          icon_pack: fab
          
        - name: Programming Languages
          description: Python | C/C++ | Java
          icon: keyboard
          icon_pack: fas

          

  - block: experience
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
        - title: Machine Learning Engineer 
          company: NeuralGarage
          company_url: 'https://visualdub.in/'
          # company_logo: org-gc
          location: Bengaluru
          date_start: '2023-01-01'
          date_end: ''
          description: |2-
           

              * Researching and developing novel algorithms for the generation of Synthetic Lip-Synced Videos using GANs, Autoencoders and  Transformers. 
              * Using 3D rendering and Cross Attention Transformers to build archietctures for high level video generation in multiple languages.
              
              
        - title: Research Intern
          company: Air Lab, Carnegie Mellon University
          company_url: 'https://theairlab.org/team/past_members/anushka/'
          # company_logo: org-x
          location: Remote
          date_start: '2022-02-01'
          date_end: '2022-08-31'
          description: |2-


            * Worked under Dr. Sebastian Scherer on vision-based aircraft detection and tracking system for detect-and-avoid applications. 
            * Contributed to the Airborne Object Tracking challenge using a multi-stage pipeline incorporating optical flow and center
              tracking.
            * Trained the pipeline using the Amazon Airborne Detection Challenge dataset and optimized models using TensorRT and
              TorchJIT for improved performance

        - title: Research Collaborator
          company: Xi’an Jiaotong-Liverpool University 
          company_url: 'https://www.xjtlu.edu.cn/en/study/departments/entrepreneur-college-taicang/college-staff/academic-staff/staff/hongseng-gan'
          # company_logo: org-x
          location: Remote
          date_start: '2022-02-01'
          date_end: '2022-08-31'
          description: |2-
         

            * Working on disease prediction using Multi-Modal Cross Attention Transformer Attention and Vision Transformers with
              Graph Neural Networks.
            * Worked on image feature extractor, explored State of the art architectures - SWIN transformer and VIT Transformer as image backbone for Fashion product image retrieval

        - title: Computer Vision Intern
          company: Omnipresent Robottech 
          company_url: 'https://www.linkedin.com/company/omnipresent-robot-tech/?originalSubdomain=in'
          # company_logo: org-x
          location: Delhi
          date_start: '2021-07-01'
          date_end: '2021-08-31'
          description: |2-
     
            * Worked closely on the Camera Health Management System by automating video surveillance using Deep Learning techniques
            * Implemented facial recognition, object detection, object tracking, and human detection to track CCTV camera behavior.
            * Deployed machine learning and deep learning models on hardware for real time monitoring and analysis of camera health

    design:
      columns: '2'
  # - block: accomplishments
  #   content:
  #     # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #     title: 'Accomplish&shy;ments'
  #     subtitle:
  #     # Date format: https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     # Accomplishments.
  #     #   Add/remove as many `item` blocks below as you like.
  #     #   `title`, `organization`, and `date_start` are the required parameters.
  #     #   Leave other parameters empty if not required.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - certificate_url: https://www.coursera.org
  #         date_end: ''
  #         date_start: '2021-01-25'
  #         description: ''
  #         organization: Coursera
  #         organization_url: https://www.coursera.org
  #         title: Neural Networks and Deep Learning
  #         url: ''
  #       - certificate_url: https://www.edx.org
  #         date_end: ''
  #         date_start: '2021-01-01'
  #         description: Formulated informed blockchain models, hypotheses, and use cases.
  #         organization: edX
  #         organization_url: https://www.edx.org
  #         title: Blockchain Fundamentals
  #         url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  #       - certificate_url: https://www.datacamp.com
  #         date_end: '2020-12-21'
  #         date_start: '2020-07-01'
  #         description: ''
  #         organization: DataCamp
  #         organization_url: https://www.datacamp.com
  #         title: 'Object-Oriented Programming in R'
          # url: ''
  #   design:
  #     columns: '2'
  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
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
    # design:
    #   # Choose a layout view
    #   view: compact
    #   columns: '2'
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
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'
  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: card
  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: |-
  #       {{% callout note %}}
  #       Quickly discover relevant content by [filtering publications](./publication/).
  #       {{% /callout %}}
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: true
  #   design:
  #     columns: '2'
  #     view: citation
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'
  # - block: contact
  #   id: contact
  #   content:
  #     title: Contact
  #     subtitle:
  #     text: |-
  #       Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
  #     # Contact (add or remove contact options as necessary)
  #     email: test@example.org
  #     phone: 888 888 88 88
  #     appointment_url: 'https://calendly.com'
  #     address:
  #       street: 450 Serra Mall
  #       city: Stanford
  #       region: CA
  #       postcode: '94305'
  #       country: United States
  #       country_code: US
  #     directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  #     office_hours:
  #       - 'Monday 10:00 to 13:00'
  #       - 'Wednesday 09:00 to 10:00'
  #     contact_links:
  #       - icon: twitter
  #         icon_pack: fab
  #         name: DM Me
  #         link: 'https://twitter.com/Twitter'
  #       - icon: skype
  #         icon_pack: fab
  #         name: Skype Me
  #         link: 'skype:echo123?call'
  #       - icon: video
  #         icon_pack: fas
  #         name: Zoom Me
  #         link: 'https://zoom.com'
  #     # Automatically link email and phone or display as text?
  #     autolink: true
  #     # Email form provider
  #     form:
  #       provider: netlify
  #       formspree:
  #         id:
  #       netlify:
  #         # Enable CAPTCHA challenge to reduce spam?
  #         captcha: false
    design:
      columns: '2'
---
