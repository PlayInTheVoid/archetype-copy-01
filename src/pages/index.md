---
title: Home
sections:
  - component: HeroBlock
    content: >-
      Hei! salve... come tu ci sia capitato qui è un mistero.\

      Ma se ci sei, prenditi un momento per leggere e magari ascoltare quello
      che ho da dire...


      Ovvio, ti chiederai su cosa...facile! Su ciò che mi appassiona e mi
      condisce il quotidiano.




      # E' un Esperenziale dal nome Archetype
    section_id: hero
    type: heroblock
  - actions:
      - label: Contact Me
        url: /contact
    component: ContentBlock
    content: >-
      This is the "about" excerpt. It can be used to provide a paragraph about
      yourself that people can read on the homepage to get a sense of who you
      are. There also exists a dedicated about page where you can write more
      about yourself for those who are interested.
    section_id: about
    title: About
    type: contentblock
  - actions:
      - label: View Blog
        url: blog/index.html
    component: PostsBlock
    num_posts_displayed: 4
    section_id: recent-posts
    title: Recent Posts
    type: postsblock
menus:
  main:
    title: Home
    weight: 1
template: home
---

