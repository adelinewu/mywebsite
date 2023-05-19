---
date: "2022-10-24"
sections:
- block: about.biography
  content:
    title: Biography
    username: admin
  id: about
- block: features
  content:
    items:
    - description: Great
      icon: microsoft
      icon_pack: fab
      name: MS Office
    - description: Great
      icon: axure
      icon_pack: custom
      name: Axure
    - description: Good
      icon: chart-line
      icon_pack: fas
      name: SPSS
    - description: Good
      icon: tableau
      icon_pack: custom
      name: Tableau
    - description: mostly Photoshop/Audition
      icon: adobe
      icon_pack: custom
      name: Adobe
    - description: mostly Python/R for NLP
      icon: code
      icon_pack: fas
      name: Code
    title: Skills
- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: 江苏航天七零六信息科技有限公司
      company_logo: hangtian
      company_url: ""
      date_end: "2021-09-01"
      date_start: "2021-07-01"
      description: |2-
          江苏航天七零六信息科技有限公司隶属于中国航天科工二院七〇六所，作为其信创企业总部，在党、政、军相关领域深度参与信创建设。实习期间，我主要负责完成的工作包括：
          *  **S市市委督办系统项目** 根据市委督查系统需求，运用Axure绘制完整的督办系统模拟原型，并撰写相应的督办系统用户操作手册。您可点击[此处](https://z6ldg3.axshare.com)预览该原型(access code:202108)。
          *  **S市W区智慧城市治理项目** 结合建设城市大脑智慧平台的需要，搭建智慧城市治理指挥中心。您可点击[此处](https://ycdfav.axshare.com)预览该可视化看板(access code:202108)。
          * Deploying
      location: 南京
      title: 产品实习生
    - company: University X
      company_logo: org-x
      company_url: ""
      date_end: "2020-12-31"
      date_start: "2016-01-01"
      description: Taught electronic engineering and researched semiconductor physics.
      location: California
      title: Professor of Semiconductor Physics
    title: Internship Experience
  design:
    columns: "2"
  id: experience
- block: accomplishments
  content:
    date_format: Jan 2006
    items:
    - certificate_url: https://www.coursera.org
      date_end: ""
      date_start: "2021-01-25"
      description: ""
      organization: Coursera
      organization_url: https://www.coursera.org
      title: Neural Networks and Deep Learning
      url: ""
    - certificate_url: https://www.edx.org
      date_end: ""
      date_start: "2021-01-01"
      description: Formulated informed blockchain models, hypotheses, and use cases.
      organization: edX
      organization_url: https://www.edx.org
      title: Blockchain Fundamentals
      url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
    - certificate_url: https://www.datacamp.com
      date_end: "2020-12-21"
      date_start: "2020-07-01"
      description: ""
      organization: DataCamp
      organization_url: https://www.datacamp.com
      title: Object-Oriented Programming in R
      url: ""
    subtitle: null
    title: Accomplish&shy;ments
  design:
    columns: "2"
- block: collection
  content:
    count: 5
    filters:
      author: ""
      category: ""
      exclude_featured: false
      exclude_future: false
      exclude_past: false
      folders:
      - post
      publication_type: ""
      tag: ""
    offset: 0
    order: desc
    subtitle: ""
    text: ""
    title: Recent Posts
  design:
    columns: "2"
    view: compact
  id: posts
- block: portfolio
  content:
    buttons:
    - name: All
      tag: '*'
    - name: Deep Learning
      tag: Deep Learning
    - name: Other
      tag: Demo
    default_button_index: 0
    filters:
      folders:
      - project
    title: Projects
  design:
    columns: "1"
    flip_alt_rows: false
    view: showcase
  id: projects
- block: markdown
  content:
    subtitle: ""
    text: '{{< gallery album="demo" >}}'
    title: Gallery
  design:
    columns: "1"
- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - publication
    title: Featured Publications
  design:
    columns: "2"
    view: card
  id: featured
- block: collection
  content:
    filters:
      exclude_featured: true
      folders:
      - publication
    text: |-
      {{% callout note %}}
      Quickly discover relevant content by [filtering publications](./publication/).
      {{% /callout %}}
    title: Recent Publications
  design:
    columns: "2"
    view: citation
  id: recent
- block: collection
  content:
    filters:
      folders:
      - event
    title: Recent & Upcoming Talks
  design:
    columns: "2"
    view: compact
  id: talks
- block: tag_cloud
  content:
    title: Popular Topics
  design:
    columns: "2"
- block: contact
  content:
    address:
      city: Nanjing
      country: China
      postcode: "210018"
      region: CN
    email: adelinewu@sina.cn
    form:
      formspree:
        id: null
      netlify:
        captcha: false
      provider: netlify
    subtitle: null
    text: Please feel free to contact me at any time.
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
