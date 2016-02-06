---
title: Home
blog_url: blog
body_classes: 

sitemap:
    changefreq: monthly
    priority: 1.03

content:
    items: @self.children
    order:
        by: date
        dir: desc
    limit: 60
    pagination: true

feed:
    description: blog at robmillerjones.com
    limit: 60

pagination: true
---


