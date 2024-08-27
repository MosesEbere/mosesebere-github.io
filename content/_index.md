---
# Leave the homepage title empty to use the site title
title:
date: 2023-09-28
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
      title: Technical Skills
      items:
        - name: ROS
          icon: ros-icon
          icon_pack: custom
        - name: Python
          icon: python-icon
          icon_pack: custom
        - name: Matlab
          icon: Matlab_Logo
          icon_pack: custom
        - name: PyTorch
          icon: pytorch-icon
          icon_pack: custom
        - name: TensorFlow
          icon: tensorflow-icon
          icon_pack: custom
        - name: Gazebo
          icon: gazebo
          icon_pack: custom
        - name: Stonefish
          icon: stone_fish-logo
          icon_pack: custom
        - name: CATIA
          icon: catia1
          icon_pack: custom
      design:
        columns: '2'
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
              * Curated underwater object-detection and optical flow datasets with a remotely operated Underwater Vehicle fitted with a DAVIS camera at the Institute for Underwater Robotics research lab.
              * Developed a modular event data preprocessing and visualization pipeline for the underwater perception group in Python.
              * Experimentally tested and validated optimization-based techniques for annotating underwater object detection datasets.
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
        - name: Robotics
          tag: Robotics
        - name: Neuromorphic Vision
          tag: Neuromorphic Vision
        - name: Industrial Robots
          tag: Industrial Robots
        - name: Computer Vision
          tag: Computer Vision
        - name: Reinforcement Learning
          tag: Reinforcement Learning
        - name: LLMs
          tag: LLMs
        - name: CAD
          tag: CAD
        - name: Control
          tag: Control
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
        {{< gallery album="gallery_photos" >}}
    design:
      columns: '1'
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
      directions: Enter the D-building and locate the Laboratory for Robotics and Intelligent Control Systems (LARICS).
      coordinates:
        latitude: '45.80087989204637'
        longitude: '15.971365968681713'
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
<form name="contact" netlify>
  <p>
    <label>Name <input type="text" name="name" /></label>
  </p>
  <p>
    <label>Email <input type="email" name="email" /></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>


aliases:
  - /masters-thesis/
---
