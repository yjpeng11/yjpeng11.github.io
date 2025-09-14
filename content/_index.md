---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: Depression & Anxiety Computational Neuroscience Lab
      image:
        filename: PKU2.jpg
      text: |-
        **Yujia Peng**

        **School of Psychological and Cognitive Sciences**

        **Peking University**
        
        彭玉佳，抑郁与焦虑计算神经实验室
        
        心理与认知科学学院，北京大学

        <!--Custom spacing-->
        <div class="mb-3"></div>
        <!--GitHub Button JS-->
        <script async defer src="https://buttons.github.io/buttons.js"></script>
    design:
      background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true

        
  - block: about.biography-home
    id: about
    content:
      title: DACN lab
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  
  # - block: experience
  #   content:
  #     title: Experience
  #     # Date format for experience
  #     #   Refer to https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     # Experiences.
  #     #   Add/remove as many `experience` items below as you like.
  #     #   Required fields are `title`, `company`, and `date_start`.
  #     #   Leave `date_end` empty if it's your current employer.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - title: Assistant professor
  #         company: Peking University
  #         company_url: ''
  #         company_logo: org-x
  #         location: Beijing
  #         date_start: '2021-09-01'
  #         date_end: ''
  #         description: |2-
  #             School of Psychological and Cognitive Sciences.

  #             Institute for Artificial Intelligence.
  #       - title: Researcher
  #         company: National Key Laboratory of General Artificial Intelligence, BIGAI
  #         company_url: ''
  #         company_logo: org-x
  #         location: Beijing
  #         date_start: '2021-11-01'
  #         date_end: ''
  #         description: ''  
  #       - title: Postdoctoral researcher
  #         company: UCLA
  #         company_url: ''
  #         company_logo: org-gc
  #         location: California
  #         date_start: '2019-07-01'
  #         date_end: '2021-07-01'
  #         description: |2-
  #             Mentors/Advisors:

  #             * Michelle Craske
  #             * Hakwan Lau
        
  #   design:
  #     columns: '2'
  
  - block: collection
    id: research
    content:
      title: Research Projects
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - research
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
  # - block: portfolio
  #   id: projects
  #   content:
  #     title: Projects
  #     filters:
  #       folders:
  #         - project
  #     # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  #     default_button_index: 0
  #     # Filter toolbar (optional).
  #     # Add or remove as many filters (`filter_button` instances) as you like.
  #     # To show all items, set `tag` to "*".
  #     # To filter by a specific tag, set `tag` to an existing tag name.
  #     # To remove the toolbar, delete the entire `filter_button` block.
  #     buttons:
  #       - name: Current members
  #         tag: '*'
  #       - name: alumni
  #         tag: alumni

    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  
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
  - block: collection
    id: publication
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
  - block: markdown
    content:
      title: Gallerys
      subtitle: ''
      text: |-
        {{< gallery album="labphoto" >}}
    design:
      columns: '1'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Send a message below.
      # Contact (add or remove contact options as necessary)
      email: yujia_peng@pku.edu.cn
      # phone: 888 888 88 88
      # appointment_url: 'https://calendly.com'
      address:
        street: Peking University
        city: Haidian
        region: Beijing
        postcode: '100871'
        country: China
        country_code: PRC
      directions: Philosophy building
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      # contact_links:
      #   - icon: twitter
      #     icon_pack: fab
      #     name: DM Me
      #     link: 'https://twitter.com/Twitter'
      #   - icon: skype
      #     icon_pack: fab
      #     name: Skype Me
      #     link: 'skype:echo123?call'
      #   - icon: video
      #     icon_pack: fas
      #     name: Zoom Me
      #     link: 'https://zoom.com'
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
