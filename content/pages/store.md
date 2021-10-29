---
title: Store
layout: store
sections:
  - type: store_section
    section_id: store_section
  - type: featured_products_section
    section_id: featured_products_section
    title: Best sellers
    icon: true
    featured_products:
      - content/pages/products/plant1.md
      - content/pages/products/plant3.md
      - content/pages/products/plant5.md
      - content/pages/products/plant7.md
  - type: promotion_section
    section_id: promotion_section
    title: Hermosos anillos
    subtitle: desde $10.000
    image: images/promo.jpg
    background_image: /images/leaf.svg
    cta:
      title: Discover
      url: /store
      style: secondary
      arrow: true
  - section_id: lorem-ipsum
    title: lorem-ipsum
    featured_categories: []
    type: featured_categories_section
seo:
  title: Store
  description: This is the store page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Store
      keyName: property
    - name: 'og:description'
      value: This is the store page
      keyName: property
    - name: 'og:image'
      value: images/header.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Store
    - name: 'twitter:description'
      value: This is the store page
    - name: 'twitter:image'
      value: images/header.jpg
      relativeUrl: true
white_header: false
---
