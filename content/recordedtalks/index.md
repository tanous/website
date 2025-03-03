---
# Page title
title: Recorded talks
# Page type - we want a landing page (such as a homepage)
type: landing

# Your landing page sections - add as many different content blocks as you like

sections:
  - block: markdown
    content:
      title: |
        <span style="font-size: 4.4rem"> Recorded Talks </span>
      subtitle: 'Scroll down for a selection of my talks'
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: deSitter.jpeg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: 40%
          text_color_light: true
      spacing:
        padding: ['140px', '0', '140px', '0']
      #css_class: fullscreen
  - block: markdown
    id: sailing
    content:
      title: |- 
        <span style="font-size:1.5rem; color:#1C4E9D">
        An introduction to the black hole information paradox</span> 
        

        <span style="font-size:1.5rem; color:#1C4E9D">([Lecture Series](https://www.youtube.com/watch?v=v4axC6pJlvQ&list=PLlva4MroG-KEvFT66gZWotWgNKYJaiAFh&index=5))</span>
      subtitle: |- 
        <span style="font-size: 0.9rem;">[LONTI, 2025](https://lonti.weebly.com/2024-25-series.html)</span>
      text: "{{< youtube id=v4axC6pJlvQ loading=lazy >}}" 
    design:
      columns: '2'    
  - block: markdown
    id: EFT-matrix
    content:
      title: |-
        <span style="font-size: 1.5rem; color:#1C4E9D">An EFT principle for low dimensional gravity</span>
      subtitle: |- 
        <span style="font-size: 0.9rem;">Bootstrapping Quantum Gravity, KITP, February 2023</span>
      text:  |-
        {{< video src="https://kitpcloud.s3-us-west-2.amazonaws.com/bootstrap23/Anous_Bootstrap23_KITP.mp4" controls="yes" >}} 
    design:
      columns: '2'
  - block: markdown
    id: sailing
    content:
      title: |- 
        <span style="font-size: 1.5rem; color:#1C4E9D">Sailing past the edge of the world</span>
      subtitle: |- 
        <span style="font-size: 0.9rem;">IAS, April 2022</span>
      text: "{{< youtube sJDMpuP_Qjk >}}"
    design:
      columns: '2'
  - block: markdown
    id: fragment
    content:
      title: |- 
        [Towards a model of AdS Fragmentation](https://pirsa.org/22010085)
        {style="font-size: 1.5rem; color:#1C4E9D"}
      subtitle: |- 
        <span style="font-size: 0.9rem;">Perimeter Institute, January 2022</span>
      text: |-  
        {{< video src="http://streamer2.perimeterinstitute.ca/mp4-med/22010085.mp4" controls="yes" >}}
    design:
      columns: '2'
  - block: markdown
    id: principal
    content:
      title: |- 
       [An invitation to the principal series](https://educast.fccn.pt/vod/clips/2cby2w9szy/streaming.html?locale=pt)
       {style="font-size: 1.5rem; color:#1C4E9D"}
      subtitle: |- 
        <span style="font-size: 0.9rem;">IST Lisbon, May 2021</span>
      text: |-  
        {{< video src="https://educast.fccn.pt/vod/clips/2cby2w9szy/desktop.mp4" controls="yes" >}}
    design:
      columns: '2'
  - block: markdown
    id: model-building
    content:
      title: |-
        <span style="font-size: 1.5rem; color:#1C4E9D">Holography from a model builder's perspective</span>
      subtitle: |- 
        <span style="font-size: 0.9rem;">Gravitational Holography, KITP, February 2020</span>
      text:  |-
        {{< video src="https://kitpcloud.s3-us-west-2.amazonaws.com/qgravity20/Anous_QGravity20_KITP.mp4" controls="yes" >}} 
    design:
      columns: '2'
  - block: markdown
    id: model-building2
    content:
      title: |-
        <span style="font-size: 1.5rem; color:#1C4E9D">Black hole collapse in the 1/c expansion</span>
      subtitle: |- 
          <span style="font-size: 0.9rem;">SoCal strings meeting, May 2016</span>
      text:  |-
          {{< video src="https://s3-us-west-2.amazonaws.com/kitpcloud/scss16/Anous_SCSS16_KITP.mp4" controls="yes" >}} 
    design:
      columns: '2'
  - block: markdown
    id: model-building2
    content:
      title: |-
        <span style="font-size: 1.5rem; color:#1C4E9D">AdS2 and the Emergence of SL(2,R)</span>
      subtitle: |- 
          <span style="font-size: 0.9rem;">UCSB, November 2014</span>
      text:  |-
          {{< video src="http://s3-us-west-2.amazonaws.com/kitpcloud/joint98/Anous_TheorySeminar_KITP.mp4" controls="yes" >}} 
    design:
      columns: '2'


---
