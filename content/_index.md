---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: collection
    id: working
    content:
      title: Working Papers
      filters:
        folders:
          - working
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: markdown
    id: teaching
    content:
      title: Teaching
      subtitle: 
      text: |
        - **Course Name**: The Politics of the Bureaucracy  
          - **Role**: Instructor  
          - **Terms**: Fall 2021, Fall 2023, Spring 2023

        - **Course Name**: Race, Innocence, and the Decline of the Death Penalty  
          - **Role**: Teaching Assistant  
          - **Term**: Spring 2022

        - **Course Name**: Introduction to American Politics  
          - **Role**: Teaching Assistant  
          - **Terms**: Spring 2021, Fall 2022, Spring 2023

---
