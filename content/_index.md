---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
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
        - title: Deep Learning and Neuromorphic Vision Intern
          company: ViCOROB
          company_url: 'https://vicorob.udg.edu/'
          company_logo: vicorob
          location: Girona
          date_start: '2023-06-09'
          date_end: '2023-09-15'
          description: |2-

              * Explored deep learning architectures such as SNNs, Recurrent ViTs, and Asynchronous CNNs, that leverage the asynchronous nature of event data from event-based vision sensors for object detection using PyTorch.
              * Curated underwater object-detection and optical flow datasets with a remotely-operated Underwater Vehicle fitted with a DAVIS camera at the Institute for Underwater Robotics research lab.
              * Developed a modular event data preprocessing and visualization pipeline for the underwater perception group in Python.
              * Experimental tested and validated optimization-based techniques for annotating underwater object detection datasets.
        - title: Graduate Teaching Assistant
          company: Sabanci University 
          company_url: 'https://www.sabanciuniv.edu/en'
          company_logo: sabanci_logo
          location: Istanbul
          date_start: '2021-09-20'
          date_end: '2022-08-31'
          description: |2-
              * Taught Differential Equations (MATH 202) and Introduction to Probability (MATH 203) recitation classes to undergraduate students over the course of two semesters.
              * Provided grading and proctoring support to faculty members.
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
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Feel free to leave me a message.
      # Contact (add or remove contact options as necessary)
      email: moseschukaebere@gmail.com
      phone: +34 645 287 887
      address:
        street: Unska ul. 3
        city: Zagreb
        postcode: '10000'
        country: Croatia
        country_code: HR
      maplink: {{< leaflet latitude="51.5074" longitude="-0.1278" >}}
      directions: Enter any of the buildings and locate the Robot Perception Lab
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: true
    design:
      columns: '2'
---

## Company Information
### About eSolia: Our Vision
As a leader in our market for outsourced IT services, eSolia's vision is to consistently provide our clients with comprehensive, exemplary IT services unbiased by maker affiliation, designed and delivered with a keen awareness of business and culture. Acting with the highest standards of ethics, professionalism and integrity, eSolia experts will help you grow the foundation for your business success.

### General

* * *
<div class="row">
  <div class="col s12 m4"><strong>HEADQUARTERS</strong></div>
  <div class="col s12 m8">Sawa Building 6F, Nishi-Shimbashi 2-2-2,<br>
    Minato-ku, Tokyo 105-0003 Japan<br>
    <em>TEL</em>: <a href="tel:+81-3-6273-3510">+81-3-6273-3510</a> | <em>FAX</em>: +81-3-3593-3511<br>
    <hr>
  </div>
  <div class="col s12 m4"><strong>CONTACT</strong></div>
  <div class="col s12 m8"><a href="/info-request">Request Information</a> or email to <a href="mailto:info@esolia.co.jp">info@esolia.co.jp</a>.
    <hr>
  </div>
  <div class="col s12 m4"><strong>DIRECTORS</strong></div>
  <div class="col s12 m8">James R. Cogley, RD and CEO<br>
    Takumi Fukuoka, RD and COO<br>
    <hr>
  </div>
  <div class="col s12 m4"><strong>ESTABLISHED</strong></div>
  <div class="col s12 m8">7 July 1999
    <hr>
  </div>
  <div class="col s12 m4"><strong>WEB PROPERTIES</strong></div>
  <div class="col s12 m8"><em>English</em>: <a href="http://esolia.com">esolia.com</a><br>
    <em>Japanese</em>: <a href="http://esolia.co.jp">esolia.co.jp</a><br>
  </div>
</div>
* * *

### Lines of Business

* Bilingual IT Consulting and Solutions
* Project Management
* System Engineering - Design, Build, Validate, Test, Upgrade
* Outsourced Run and Maintain for IT Systems
* Outsourced User Support and Helpdesk
* Training
* Online General Business Database Service

### Access Map

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3241.377084474057!2d139.75146199999998!3d35.667716!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x60188b933eb5098d%3A0xb799ee788fa28eb7!2seSolia+Inc.!5e0!3m2!1sen!2sjp!4v1434536695719" width="600" height="450" frameborder="0" style="border:0"></iframe>
