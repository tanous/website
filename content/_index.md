---
# Leave the homepage title empty to use the site title
title: Tarek Anous Academic Website
date: 2023-08-02
type: landing

sections:
  - block: hero
    content:
      title: |
        The Anous group 
      image:
        filename: deSitter.jpeg
      text: |- 
        <br>

        Welcome to my group's webpage, where you can find out about [current and past members](/people), research and teaching activities, events, and [openings](/openings). 
        {style="font-size: 1rem;"}

  - block: markdown
    content:
      title: Research  
      image:
        filename: 
      text: |-
       ![Collapse](/uploads/collapse.png#center)
       One of the landmark pursuits of theoretical physics is to quantize the gravitational interaction. String theory provides a perturbative approach, but requires extra particles, symmetries, and spacetime dimensions. Worst of all, string theory fails as a framework in expanding spacetimes---and it just so happens that our universe is [expanding at an exponential rate](https://www.nobelprize.org/prizes/physics/2011/summary/).

       Luckily, string theory has led to the development of _holographic dualities_, such as the AdS/CFT correspondence (learn about it [here](https://www.damtp.cam.ac.uk/user/aw846/AdSCFT.html)), which posits that spacetime physics emerges as a strong-coupling, many-body limit of quantum systems that do not interact gravitationally. 

       My research aims to understand how spacetime horizon physics is encoded using such dualities, and explore models that incorporate the expansion of spacetime. Some approaches that I have taken in the past include: 

       - Quantum field theory *on a rigid de Sitter background*, e.g.:
          - Finding [exactly solvable models](/publication/anninos-2024-fty/)
          - Studying the constraints imposed by [symmetries](/publication/anninos-2023-lin) and [unitarity](/publication/anous-2020-nxu)
          - Analyzing the cosmological wavefunction and how it controls the [infrared of loop integrals](/publication/anninos-2014-lwa)
       - Low-dimensional models of classical and quantum gravity, and their holographic duals, e.g.: 
          - Following the process of thermalization after a global quench and demonstrating it as a [dual process to gravitational black hole collapse](/publication/anous-2016-kss)
       - Proposing supersymmetric matrix quantum mechanical systems as [toy models](/publication/anous-2019-rqb) for [string theoretic black holes](/publication/anous-2017-mwr)
       - Suggesting disordered systems as a model of [cold](/publication/anous-2021-eqj) or [fragmented black holes](/publication/anninos-2016-szt)
       



  - block: people
    content:
      title: Meet the team
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Researchers
          - Graduate Students
          - Alumni
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true
  
  - block: contact
    content:
      title: <span style="color:#1C4E9D">Office Address</span>
      text: 
      email: t.anous@qmul.ac.uk
      address:  
        street: School of Mathematical Sciences<br> MB-B24<br> Queen Mary University of London<br> Mile End Road
        city: London
        postcode: 'E1 4NS'
        country: United Kingdom
        country_code: UK
      coordinates:
        latitude: #'51.522419'
        longitude: #'-0.043088'
      directions: We are located between the <span style="color:#38761D">Stepney</span> <span style="color:#C27BA0">Green</span> and <span style="color:#CC0000">Mi</span><span style="color:#38761D">le E</span><span style="color:#C27BA0">nd</span> tube stops<br> 

        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2482.493285291059!2d-0.0457134232438842!3d51.522511671816844!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x48761d2f3123ff19%3A0x1a14b140e802c875!2sSchool%20of%20Mathematical%20Sciences!5e0!3m2!1sen!2suk!4v1691160967834!5m2!1sen!2suk" width="100%" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
      # form:
      #  provider: netlify
      #  formspree:
      #    id:
      #  netlify:
      #    # Enable CAPTCHA challenge to reduce spam?
      #    captcha: false
    design:
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: deSitter.jpeg
          filters:
            brightness: 1
          parallax: true
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
---