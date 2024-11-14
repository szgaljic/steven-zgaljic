---
#title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:

  #
  # Hero
  #

  - block: hero
    content:
      title: Untangling Complexity.
      text: Delivering Pragmatic Technical Leadership.
      primary_action:
        text: Learn How
        url: https://hugoblox.com/templates/
        icon: rocket-launch
      # secondary_action:
      #   text: Read the docs
      #   url: https://docs.hugoblox.com
      announcement:
        text: "Let's work together."
        link:
          text: "Reach out"
          url: "/#contact"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: hero.png
          filters:
            brightness: 0.5

  #
  # Aligning technology
  #
    
  - block: markdown
    id: aligning-tech
    content:
      title: 'Aligning technology strategy and execution in complex enterprise environments.'
    design:
      css_style: "text-align: center; font-size: 24px; font-weight: bold; padding: 50px 0;"

  #
  # About
  #

  - block: cta-image-paragraph
    id: about
    content:
      items:
        - title: Hi, I'm Steven.
          text: |
            Steven Zgaljic helps large enterprises and mid-sized companies transform technology frustrations into clear, actionable strategies. With his deep expertise in technology planning, system architecture, and leadership, he delivers pragmatic solutions that align technology with business goals, enabling organizations to achieve their core objectives.
          image: pic.jpg
    design:
      columns: 2
      css_class: "bg-gray-100 dark:bg-gray-900"

  #
  # Services
  #

  - block: cta-image-paragraph
    id: services
    content:
      items:
        - title: Technology Planning & Strategic Alignment
          text: Design detailed technology roadmaps that align with business goals, streamline complex architectures, and enhance system performance. Provides actionable, phased strategies that guide teams through scalable growth while ensuring alignment across technical and business priorities.
          feature_icon: check
          features:
            - "Align IT with Business Objectives"
            - "Roadmap for Innovation"
            - "Optimize IT Investments"
          # Upload image to `assets/media/` and reference the filename here
          image: plan.png
        - title: Team Resourcing and Operational Improvements
          text: Optimize team structure, resource alignment, and cross-functional communication to drive business objectives. Facilitate technical discussions, bridge gaps between tech and business, and provide clear guidance on hiring, restructuring, and aligning teams for maximum impact.
          feature_icon: check
          features:
            - "Enhance Team Dynamics"
            - "Streamline Communication Processes"
            - "Skill Alignment and Development"
          # Upload image to `assets/media/` and reference the filename here
          image: team.png
        - title: Architecture Design & Optimization
          text: Create scalable, secure architectures tailored to organizational needs, including cloud and on-premise, monolith and microservice, and enterprise integration patterns.
          feature_icon: check
          features:
            - "Build Scalable Systems"
            - "Enhance System Security and Reliability"
            - "Tailored Technology Solutions"
          # Upload image to `assets/media/` and reference the filename here
          image: tech.png

  #
  # Jahnel Group
  #

  - block: hero
    id: jahnel-group
    content:
      title: CTO at Jahnel Group
      text: |
        As CTO of Jahnel Group, Steven Zgaljic spearheads innovative technology solutions that drive the company's strategic direction. His role involves overseeing the technology roadmap, leading the development of cutting-edge software solutions, and ensuring technological excellence across the company. His leadership is pivotal in maintaining Jahnel Group's status at the forefront of the industry.
      primary_action:
        text: Visit Jahnel Group
        url: "https://www.jahnelgroup.com"
        target: "_blank"
    design:
      background:
        image:
          filename: hero.jpg  # Ensure this image conveys the enterprise setting of Jahnel Group
          size: cover
          position: center
      text_color: "white"
      overlay:
        color: "rgba(0, 0, 0, 0.5)"  # Adjust for text readability
      css_class: "full-width hero-dark-overlay"
      spacing:
        padding: [3rem, 1rem, 3rem, 1rem]  # Adjust based on your layout preferences

  #
  # Contact
  #

  - block: markdown
    id: contact
    content:
      title: How can I help you?
      text: |
        Let's discuss what's holding your business back. I'm here to help unlock your potential by bridging the gap between business and technology.

        <form id="contactForm" style="color: #333;">
          <label for="name" style="margin-top: 1rem; display: block;">Name</label>
          <input type="text" id="name" name="name" required style="width: 100%; padding: 8px; margin-bottom: 16px; border: 1px solid #ccc; border-radius: 4px;">

          <label for="email" style="margin-top: 1rem; display: block;">Email Address</label>
          <input type="email" id="email" name="email" required style="width: 100%; padding: 8px; margin-bottom: 16px; border: 1px solid #ccc; border-radius: 4px;">

          <label for="message" style="margin-top: 1rem; display: block;">Message</label>
          <textarea id="message" name="message" required style="width: 100%; padding: 8px; margin-bottom: 16px; border: 1px solid #ccc; border-radius: 4px; height: 100px;"></textarea>

          <div class="g-recaptcha" data-sitekey="6LcVrHwqAAAAAMuLnXNeRYqgiP7qluiMf3qLofeB"></div>

          <button type="submit" style="background-color: #04AA6D; color: white; padding: 14px 20px; border: none; border-radius: 4px; cursor: pointer; margin-top: 1rem;">Submit</button>
        </form>

        <script src="https://www.google.com/recaptcha/api.js" async defer></script>

        <div id="responseMessage"></div>
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"
      css_style: "text-align: left; font-size: 16px; padding: 20px;"
---