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
        - name: C++
          icon: c
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
        - title: Doctoral Researcher in Robotics
          company: Delft University of Technology 
          company_url: 'https://www.tudelft.nl/en/me/about/departments/cognitive-robotics-cor'
          company_logo: TU_Delft_Logo
          location: Delft
          date_start: '2024-11-01'
          date_end: '2028-10-31'
          description: |2-
              * Conducting research on ”Safe Planning and Control for Autonomous Robots,” at the Department of Cognitive Robotics.
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
        - name: Multi-Robot Systems
          tag: Multi-Robot Systems
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
      email: m.c.ebere@tudelft.nl
      phone: +34 645 287 887
      address:
        street: Building 34, Mekelweg 2
        city: Delft
        postcode: 2628 CD
        country: Netherlands
        country_code: NL
      directions: 34.F-1-560
      coordinates:
        latitude: '52.000978'
        longitude: '4.3718974'
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


aliases:
  - /masters-thesis/
---
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
