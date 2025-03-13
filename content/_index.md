---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      #button:
      #  text: Download CV
      #  url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: zinc
        #image:
          # Add your image background to `assets/media/`.
          #filename: stacked-peaks.svg
          #filters:
          #  brightness: 1.0
          #size: cover
          #position: center
          #parallax: false
#  - block: markdown
#    content:
#      title: 'Publications and Working Papers'
#      subtitle: ''
#      text: |-
#        Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.

#        I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.
        
#        Please reach out to collaborate 😃
#    design:
#      columns: '1'
#  - block: collection
#    id: papers
#    content:
#      title: Featured Publications
#      filters:
#        folders:
#          - publication
#        featured_only: true
#    design:
#      view: article-grid
#      columns: 2
  - block: markdown
    id: papers
    content:
      title: Publications
      text: |-
        {{< spoiler text="Lawrence J. Liu. 2024. Independence through Judicialization: The Politics Surrounding Administrative Adjudicators, 1929-1949. _Michigan Journal of Environmental and Administrative Law_ 13(2): 522-69." >}}[Link](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4895926) 
        One front in today’s battle to define the scope of the administrative state concerns the authority, status, and future of its 10,000-plus administrative adjudicators. Decisions by federal courts and the executive branch to increase the dependence of administrative adjudicators on the executive have sparked strong reactions from observers, with many advocating for measures to increase adjudicator “independence.” But who should administrative adjudicators be independent of, which ought to be independent, and why? 
        
        Calls for administrative adjudicator independence are not new. This Article draws on primary documents produced by private actors, congressional decisionmakers, and federal executive agents to present a political legal history of legislative proposals between 1929 and 1949 to understand whether, how, and why different actors sought to insulate administrative adjudicators from their agencies or the President. Leading up to and following the enactment of the Administrative Procedure Act in 1946, politicians and interested citizens advanced proposals to increase the independence of the individuals who conducted hearings and served as factfinders in administrative agencies. Then, like now, observers debated administrative adjudicator independence in the context of discussions about the power of administrative agencies. The loudest supporters of independence were anti-New Dealers trying to halt and reverse the growth of administrative power, who were joined by a subset of legal professionals interested in using law to check its operation. These critics attempted to “judicialize” administrative adjudication by increasing the resemblance of administrative adjudicators to the federal judiciary.  
        
        What does this history teach? First, it illustrates how actors past and present deploy seemingly apolitical terms like judicial values, independence, or administrative procedure to obtain substantive political ends. Indeed, such terms can take on different meanings at different times, perhaps varying with views of the federal judiciary and active government, the policies and political strength of the President, the issues decided by administrative agencies, or the types of claimants subject to adjudication. Second, it highlights how early supporters of administrative agencies emphasized the diversity among administrative adjudicators, while opponents grouped them together to collectively limit their authority. Today, rather than pursuing one-size-fits-all reforms, I suggest that different rules should apply to different administrative adjudicators depending on the questions and claimants involved. Decisions about ratemaking or regulatory enforcement differ from individualized determinations whether citizens qualify for government benefits or licenses. Claims by business interests might be treated differently from those by more vulnerable groups, such as disability-benefits recipients or noncitizens at risk of removal. In any event, when making policy recommendations, reformers should begin by understanding who administrative adjudicators are and the functions they perform, an understanding that also underscores whether and how politics should animate arguments about adjudicator independence.
        {{< /spoiler >}
  - block: markdown
    id: teaching
    content:
      title: Teaching
      text: ""
    design: 
      columns: '1'
#      filters:
#        folders:
#          - publication
#        exclude_featured: false
#  - block: collection
#    id: news
#    content:
#      title: Recent News
#      subtitle: ''
#      text: ''
      # Page type to display. E.g. post, talk, publication...
#      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
#      count: 5
      # Filter on criteria
#      filters:
#        author: ""
#        category: ""
#        tag: ""
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ""
      # Choose how many pages you would like to offset by
#      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
#      order: desc
 #   design:
      # Choose a layout view
 #     view: date-title-summary
      # Reduce spacing
 #     spacing:
 #       padding: [0, 0, 0, 0]
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!
        
        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
