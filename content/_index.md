---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
      
      
      
  - block: collection
    id: featured
    content:
      title: Publications
      text: |-
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '3'
      view: citation
      
      
      
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
      # Contact (add or remove contact options as necessary)
      email: tjw@henu.edu.cn
      directions: Øster Farimagsgade 5, Copenhagen, DK-1353, Denmark
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: tjw_ku
          link: 'https://twitter.com/tjw_ku'

---
