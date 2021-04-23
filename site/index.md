---
title: Home
has_more_link: true
more_link_text: Keep reading
seo:
  title: {{page.title}}
  description: {{site.header.tagline}}
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: {{site.title}}
      keyName: property
    - name: 'og:description'
      value: {{site.header.tagline}}
      keyName: property
    - name: 'og:image'
      value: images/home.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: {{site.title}}
    - name: 'twitter:description'
      value: {{site.header.tagline}}
    - name: 'twitter:image'
      value: images/home.jpg
      relativeUrl: true
layout: home
---
