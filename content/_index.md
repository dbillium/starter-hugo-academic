---
# Leave the homepage title empty to use the site title
title: Davis Psyc Lab @ Witt
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: billy-davis

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
        - title: Associate Professor of Psychology
          company: Wittenberg University
          company_url: https://www.wittenberg.edu/
          company_logo: witt-w
          location: Springfield, OH
          date_start: '2021-08-01'
          date_end: ''
          description: ''
        - title: Assistant Professor of Psychology
          company: Wittenberg University
          company_url: https://www.wittenberg.edu/
          company_logo: witt-w
          location: Springfield, OH
          date_start: '2018-08-01'
          date_end: '2021-07-31'
          description: ''
        - title: Visiting Lecturer
          company: Mount Holyoke College
          company_url: https://www.mtholyoke.edu/
          company_logo: mhc
          location: South Hadley, MA
          date_start: '2015-08-01'
          date_end: '2018-05-31'
          description: ''
    design:
      columns: '2'

  - block: portfolio
    id: projects
    content:
      title: Projects and Activities
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
#      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
#      buttons:
#        - name: All
#          tag: '*'
#        - name: Deep Learning
#          tag: Deep Learning
#        - name: Other
#          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: true

  #- block: markdown
  #  content:
  #    title: Photos
  #    subtitle: ''
  #    text: |-
  #      {{< gallery album="photos" >}}
  #  design:
  #    columns: '1'

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
      view: 2

#  - block: collection
#    content:
#      title: Recent Publications
#      text: |-
#        {{% callout note %}}
#        Quickly discover relevant content by [filtering publications](./publication/).
#        {{% /callout %}}
#      filters:
#        folders:
#          - publication
#        exclude_featured: true
#    design:
#      columns: '2'
#      view: citation

#  - block: markdown
#    content:
#      title: Student Posters
#      subtitle: ''
#      text: |-
#        {{< gallery album="posters" >}}
#    design:
#      columns: '1'


#  - block: collection
#    content:
#      title: Recent Publications
#      text: |-
#        {{% callout note %}}
#        Quickly discover relevant content by [filtering publications](./publication/).
#        {{% /callout %}}
#      filters:
#        folders:
#          - publication
#        exclude_featured: true
#    design:
#      columns: '2'
#      view: 2
---
