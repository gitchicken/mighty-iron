---
title: Home
sidebar:
  entries:
  - title: Welcome
    url: "#intro"
    is_primary: true
  - title: Who we are
    url: "#one"
    is_primary: false
  - title: What we do
    url: "#two"
    is_primary: false
  - title: Get in touch
    url: "#three"
    is_primary: false
sections:
- type: intro
  template: intro
  title: Stanky Jigs&trade;
  subtitle: "Cras aliquam amet adipiscing nibh faucibus suscipit ut Parturient  \ncol
    accumsan est arcu donec sed Eleifend Integer."
  section_id: intro
  background_style: style1
  actions:
  - label: Like Us On Facebook
    url: https://www.facebook.com/stankyjigs/
    is_scrolly: true
    is_primary: false
  component: intro.html
- type: spotlights
  template: spotlights
  title: Spotlights Section
  section_id: one
  background_style: style2
  component: spotlights.html
- type: contact
  template: contact
  title: Get in touch
  text: Have a question of comments? - Please feel free to use any of the methods
    below.
  section_id: three
  background_style: style1
  contact_list:
  - title: Email
    text: gregg@digitallobotomy.net
    url: mailto:gregg@digitallobotomy.net
  - title: Phone
    text: "(305) 725-0948"
    url: tel:+13057250948
  social:
    title: Social
    social_icons:
    - title: Facebook
      icon: fa-facebook
      url: https://www.facebook.com/stankyjigs
  component: contact.html
layout: home
menu:
  main:
    weight: 1

---
