---
title: Booking
url: booking
image:
  - /content/upload/gravenogol.png
components:
  - type: form
    title: Booking
    name: Booking
    action: /contact/thanx
    template: components/form/form.liquid
    elements:
      - type: text
        inputtype: text
        required: true
        title: Name
        placeholder: "Your Name "
      - type: text
        inputtype: email
        required: true
        title: Email
        placeholder: Email
      - type: options
        inputtype: Radio
        required: true
        title: Artist
        option:
          - checked: false
            title: David
          - checked: true
            title: Thomas
          - checked: false
            title: Rasmus
      - type: textarea
        title: Message
        required: true
      - type: button
        title: Go Go Lucifer
        resettitle: Reset
        reset: true
    text: |-
      Y﻿ou can totally contact us :)
      t﻿ext with stuff on it
tags:
  - graven
order: 1
layout: page/page.liquid
date: 2023-06-21 20:03:22
eleventyExcludeFromCollections: false
eleventyNavigation:
  title: Booking
  parent: main
  order: 20
---
For booking please use this form. 

