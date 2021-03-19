---
title: Pricing
sections:
  - section_id: pricing
    type: section_pricing
    background: gray
    title: Pricing Plans
    subtitle: Try a bitdomain for free!
    pricing_plans:
      - title: Basic
        subtitle: For solo developers
        price: free
        details: |
          *   1 bitdomain
          *   10 data sets
          *   2 users
          *   100K rows
          *   Rolling 30 day retention
        actions:
          - label: Learn More
            url: /contact
            style: secondary
      - title: Pro
        subtitle: For teams
        price: $199/mo
        details: |
          *   2 bitdomains
          *   20 data sets
          *   5 users
          *   500K rows
          *   60 day retention
          *   Limited Support
        highlight: true
        actions:
          - label: Learn More
            url: /contact
            style: primary
      - title: Enterprise
        subtitle: For departments
        price: $999/mo
        details: |
          *   Unlimited domains
          *   Unlimited datasets
          *   starts at 20 users
          *   starts at 3M rows
          *   starts at 6 month retention
          *   Full support and optional SLA
        actions:
          - label: Learn More
            url: /contact
            style: secondary
  - section_id: faq
    type: section_faq
    background: gray
    title: Frequently Asked Questions
    faq_items:
      - question: What's a domain?
        answer: >
          A domain is a virtual computing space in our global processing
          network. You can pick what provider (AWS, Azure, Digital Ocean) and
          location (Western US, Eastern US, Europe, Asia) your domain runs on
          but we are not providing you either databases or instances. You get a
          slice of our overall compute.
      - question: What's a user?
        answer: >+
          A user is any person or system that needs to login in to your
          bitdomain(s).

      - question: Can I get my data out?
        answer: >+
          We put your bit domain at the cloud provider (AWS, Azure, Digital
          Ocean) of choice and you have full download and API access to your
          data. At most providers, there is no egress charges for you to have
          your own DB instance at that particular data center. So you can get
          your data out, generally, at no incremental cost to you. We are also
          planning an on prem option where you can setup a master bitdomain in
          your own data center, and then replicate data sets out to through
          bitdomain's public cloud network.

    subtitle: Let us know if you have more at help@bitdomain.dev
seo:
  title: Pricing
  description: This is the pricing page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Pricing
      keyName: property
    - name: 'og:description'
      value: This is the pricing page
      keyName: property
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Pricing
    - name: 'twitter:description'
      value: This is the pricing page
layout: landing
---
