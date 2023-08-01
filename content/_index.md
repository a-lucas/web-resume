---
# Leave the homepage title empty to use the site title
title: Antoine Lucas
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
      title: Best Tech Skills
      items:
        - name: GoLang / Node 
          description: 5 years / 7 years 
          icon: server
          icon_pack: fas
        - name: Vue3 /  Angular
          description: 5 years / 1 year
          icon: pen-nib
          icon_pack: fas
        - name: Linux / API dev / SQL / Javascript
          description: 10+ years
          icon: sitemap
          icon_pack: fas
  - block: features
    content:
      title:  Soft Skills
      items:
        - name: Active listening
          description: Listening is the first step for a successfull communication.
          icon: headset
          icon_pack: fas
        - name: Critical Thinking
          description: Failure is a respectable opinion and an invaluable experience.
          icon: brain
          icon_pack: fas
        - name: Work Ethics
          description: I have high expectations
          icon: jedi
          icon_pack: fas
  - block: features
    content:
      title: Leadership
      items:
        - name: Discret & Humble
          description: I prefer to focus on facilitating engineering conversations
        - name: Team cohesion
          description: <h4>1 + 1 = 3</h4>  
        - name: Active Listener 
          description: In meeting - I do help PM with technical note taking 
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
        - title: 'Open to work'
          company: "I'd like to meet you"  
          date_start: '2023-08-15'
        - title: 'DataPond engineer'
          company: 'Open Source'
          company_url: 
          company_logo:
          location: Remote
          date_start: '2022-01-01'
          date_end: '2023-08-15'
          description: |2- 
            DataPond is an offline library of books on the theme of sustainability.
            the data is downloaded once from the perma-web - which is a 250 years storage guaranteed - making it a possible successor to Alexandria. 
      
            The tech stack is Vue(Quasar), and a custom database that I authored from scratch that takes advantage of decentralisation by running the datastore on the user's local device. 
        - title: 'Senior Consultant Contractor'
          company: 'Several recruitment agencies'
          company_url: ''
          company_logo: 
          location: Australia (Sydney / Canberra)
          date_start: '2013-01-01'
          date_end: '2021-01-12'
          description: |2-
            I worked across *dozens* of different engineering teams , ranging from governemental, media, financial, defence, insurances, mapping and some agencies.

              My Responsibilities mostly include:
              1. Analysing and implementing requirements with stakeholders or product owners
              2. Modeling solutions
              3. Project rescues
              4. Product design and implementation
        - title: Tech Lead / Architect
          company: ExpatJobs / Webjobs
          company_url: ''
          company_logo: 
          location: Australia - Perth
          date_start: '2010-01-01'
          date_end: '2013-01-01'
          description: |2-
             During my time at Webjobz, I rewrote the whole company system - and deployed a dozen of job boards in several languages - raising by 500% the overal traffic to the network.

             Responsibilities include:

              * The administration of all the company servers. *Unix Webmail, LAMP, SOAP (root)*
              * Design and implementation of several Job boards from scratch
              * Advertising platform integration.
              * Implementation and design of large crawlers using curl & regexes.
              * and much more.

        - title: 5 years Junior - Intermediate
          company: Mostly a web contractor   
          location: France
          date_start: '2004-01-01'
          date_end: '2009-01-01'
          description: |2-
             I started learning web development in 1993 - at 14 years old - I taught myself BAsic on an Atari console for a year.
             In 2001 I taught myself HTML4/CSS2 and a bit of javascript.
             
             I then, for several clients - developed several custom websites using PHP, and became proficient with the LAMP stack (Linux/Apache/MySQL/PHP).
             Until this day, I still use linux on my personal computer.    
    design:
      columns: '1'
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
        - certificate_url: 
          date_end: '2011-01-01'
          date_start: '2010-01-01'
          description: 'One day, a Google AdWord representative popped up in our office - and told us we blew up **the [CTR](https://support.google.com/google-ads/answer/2615875?hl=en) Australian record** on their [DoubleCick platform](https://marketingplatform.google.com/about/enterprise/) . They were quite happy for us to succeed - since our success also mean better income for them. 
          It was interesting to notice that Google chose to NOT invade the Job-board industry - solely because they seem to generate more income within the advertisement market - rather than dealing directly with job advertisers.'

          organization: WebJobz          
          title: Best Doubleclick Click Trough Rate in Australia - 2010-2011
          url: ''
        - certificate_url: 
          title: Best Thales contractor 2021.
          date_end: '2021-01-01'
          date_start: '2021-01-01'
          description: Informal, I got offered a lifetime long permanent position after a good contract. It is often under-rated how iportant a team dynamics is, and this team is legendary. This is how I performed well. I'll send you a photo of the t-shirt on request ^^
          organization: Thales.
          organization_url: https://www.thalesgroup.com/en          
          url: ''
        - certificate_url: 
          date_end: '2023-01-01'
          date_start: '2021-01-01'
          description: 'During my travelling across cultures and continents - I got the privilege to discover, learn, walk and meet within indigenous tribes.'
          organization: Self Development
          organization_url: 
          title: 'A humble discovery with a rich experience'
          url: ''
    design:
      columns: '1'
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 0
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
#  - block: portfolio
#    id: projects
#    content:
#      title: Projects
#      filters:
##        folders:
#         - project
#      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
#      default_button_index: 0
#      # Filter toolbar (optional).
#      # Add or remove as many filters (`filter_button` instances) as you like.
#      # To show all items, set `tag` to "*".
#      # To filter by a specific tag, set `tag` to an existing tag name.
#      # To remove the toolbar, delete the entire `filter_button` block.
      
#    design:
#      # Choose how many columns the section has. Valid values: '1' or '2'.
#      columns: '1'
#      view: showcase
#      # For Showcase view, flip alternate rows?
#      flip_alt_rows: false
#  - block: markdown
#    id: gallery
#    content:
#      title: Gallery
#      subtitle: ''
#      text: |-
#        {{< gallery album="demo" >}}
#    design:
#      columns: '1'
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
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact me for availability
      subtitle:
      text: The best way to contact me is via email - or to schedule a 30 minutes call.        
      # Contact (add or remove contact options as necessary)
      email:  antoine.lucas.australia 'at' gmail.com
      phone: 
      appointment_url: 'https://calendly.com/antony-lucas/30min'
      directions: 
      office_hours:
        - 'Monday-Sunday 08:00 to 20:00'
      # Automatically link email and phone or display as text?
      autolink: false
      # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: false
    design:
      columns: '2'
---
