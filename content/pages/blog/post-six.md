---
type: PostLayout
title: "How to Structure and Organize a Next.js Project \U0001F5C2️"
colors: colors-a
date: '2024-06-03'
author: content/data/team/doris-soto.json
excerpt: ''
bottomSections:
  - elementId: ''
    type: RecentPostsSection
    colors: colors-f
    variant: variant-d
    subtitle: Recent posts
    showDate: true
    showAuthor: false
    showExcerpt: true
    recentCount: 2
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-56
          - pr-4
          - pl-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: center
    showFeaturedImage: true
    showReadMoreLink: true
  - type: ContactSection
    backgroundSize: full
    title: Stay up-to-date with my words ✍️
    colors: colors-f
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: updatesConsent
          label: Sign me up to recieve my words
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit \U0001F680"
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-4
          - mr-4
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
---
Organizing a Next.js project effectively is key to ensuring scalability, maintainability, and ease of collaboration. Here’s how to structure a Next.js project:

1.      pages/
        ├── index.js
        ├── about.js
        └── blog/
            └── [id].js

2.      components/
        ├── Header.js
        ├── Footer.js
        └── Button.js

3.      styles/
        ├── globals.css
        └── Home.module.css

4.      public/
        ├── images/
        └── favicon.ico

5.      utils/
        ├── fetchData.js
        └── useAuth.js

6.  **API Folder**: If you are using Next.js API routes, organize them under the `pages/api/` directory.

By keeping your project organized, you ensure better readability and smoother collaboration as the app grows.
