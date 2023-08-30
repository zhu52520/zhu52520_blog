---
# Leave the homepage title empty to use the site title
title: Yuxuan Zhu
date: 2023-08-30
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  # - block: features
  #   content:
  #     title: Skills
  #     items:
  #       - name: R
  #         description: 90%
  #         icon: r-project
  #         icon_pack: fab
  #       - name: Statistics
  #         description: 100%
  #         icon: chart-line
  #         icon_pack: fas
  #       - name: Photography
  #         description: 10%
  #         icon: camera-retro
  #         icon_pack: fas
  - block: experience
    content:
      title: |2-
        Research
        Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Pos-Moore Microelectronics and Integrated Circuit Center
          company: Supervised by Prof. Xufeng Kou
          company_url: 'http://pmicc.sist.shanghaitech.edu.cn/'
          company_logo: pmicc
          location: Shanghai, China
          date_start: '2023-04-01'
          date_end: ''
          description: Model devices for CMOS transistors at extremely low emperatures approaching absolute zero.
        - title: Power System Protection and Automation Laboratory
          company: Supervised by Prof. Yu Liu
          company_url: 'https://pspal.shanghaitech.edu.cn/index.html'
          company_logo: pspal
          location: Shanghai, China
          date_start: '2022-05-01'
          date_end: ''
          description: Fully explore the redundancy of fault localization problems based on a limited number of measurements.
    design:
      columns: '2'
  - block: experience
    content:
      title: |2-
        Teaching
        Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Course of Introduction to Logic Circuit
          company:  Wellington College International Shanghai
          company_url: 'https://sh-zh.wellingtoncollege.cn/'
          company_logo: wellington
          location: Shanghai, China
          date_start: '2023-01-01'
          date_end: ''
          description: |2-
            Personalized course content for each student to suit their individual learning pace and fundamental knowledge level and provided full English language instruction;
            Developed project themes based on Multisim and guided students to self-expand.
        - title: Course of Digital Circuit
          company: No.2 High School of East China Normal University
          company_url: 'http://www.hsefz.cn/'
          company_logo: hsefz
          location: Shanghai, China
          date_start: '2021-09-01'
          date_end: ''
          description: |2-
            Adjusted the course content to make it accessible to high school students;
            Designed experiment content, including simulation in Multisim and breadboard construction;
            Guided students to explore independently, and introduced PCB drawing-related content.
        - title: Course of Signals and Systems
          company: ShanghaiTech University
          company_url: 'https://www.shanghaitech.edu.cn/'
          company_logo: shanghaitech_university
          location: Shanghai, China
          date_start: '2022-02-01'
          date_end: '2022-06-01'
          description: |2-
            Produced and graded homework and exams;
            Held practice sessions and answered question.
        - title: Course of Electric Circuit
          company: ShanghaiTech University
          company_url: 'https://www.shanghaitech.edu.cn/'
          company_logo: shanghaitech_university
          location: Shanghai, China
          date_start: '2021-09-01'
          date_end: '2022-01-01'
          description: |2-
            Produced and graded homework and exams;
            Held practice sessions and answered question.
    design:
      columns: '2'
  - block: collection
    content:
      title: Recent Publications
      # text: |-
      #   {{% callout note %}}
      #   Quickly discover relevant content by [filtering publications](./publication/).
      #   {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Honors & Awards'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: ''
          date_end: ''
          date_start: '2022-06-01'
          description: ''
          organization: ShanghaiTech University
          organization_url: 'https://www.shanghaitech.edu.cn/'
          title: Merit Student
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2022-06-01'
          description: ''
          organization: ShanghaiTech University
          organization_url: 'https://www.shanghaitech.edu.cn/'
          title: Second Prize Scholarship (Top 7%) 
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2022-06-01'
          description: ''
          organization: ShanghaiTech University
          organization_url: 'https://www.shanghaitech.edu.cn/'
          title: Outstanding Volunteer
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2021-06-01'
          description: ''
          organization: ShanghaiTech University
          organization_url: 'https://www.shanghaitech.edu.cn/'
          title: Merit Student
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2021-06-01'
          description: ''
          organization: ShanghaiTech University
          organization_url: 'https://www.shanghaitech.edu.cn/'
          title: Second Prize Scholarship (Top 7%) 
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2021-06-01'
          description: ''
          organization: ShanghaiTech University
          organization_url: 'https://www.shanghaitech.edu.cn/'
          title: Outstanding Student Cadre
          url: ''
    design:
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
        - name: Software Simulation
          tag: Software Simulation
        - name: Embbed System
          tag: Embbed System
        - name: Programming
          tag: Programming
        - name: Course Project
          tag: Course Project
        - name: Self-motivation Project
          tag: Self-motivation Project
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
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
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: test@example.org
      phone: 888 888 88 88
      appointment_url: 'https://calendly.com'
      address:
        street: 450 Serra Mall
        city: Stanford
        region: CA
        postcode: '94305'
        country: United States
        country_code: US
      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/Twitter'
        - icon: skype
          icon_pack: fab
          name: Skype Me
          link: 'skype:echo123?call'
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://zoom.com'
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
