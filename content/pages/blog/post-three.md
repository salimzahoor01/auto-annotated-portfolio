---
type: PostLayout
title: Composable - the future of web
colors: colors-b
date: '2024-01-01'
author: content/data/team/doris-soto.json
excerpt: ''
backgroundImage:
  type: BackgroundImage
  url: /images/gallery-2.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 10
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
        width: wide
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
Composable architecture is shaping the future of web development by promoting flexibility, scalability, and efficiency. This approach breaks down applications into smaller, independent, and reusable components or microservices, allowing developers to build web applications by assembling pre-built, modular elements. Instead of building everything from scratch, developers can integrate various specialized services (such as authentication, payment, or CMS) into a seamless experience.

The future of the web lies in this composable approach, as it enables businesses to rapidly adapt to changing demands and innovate faster. With composable systems, developers can choose the best-in-class tools for each feature, creating highly customizable and dynamic applications that can be easily updated and scaled without major overhauls.

By decoupling the front-end from the back-end, composable architecture offers a more flexible, modular, and agile way to develop and maintain web apps. This means teams can work concurrently on different parts of the system, improving productivity and time-to-market. With composable solutions, the web becomes more personalized, more efficient, and better suited for rapid evolution, making it the future of modern web development.

### Syntax highlighter in Next.js

```css
.colors-a {
  @apply bg-dark text-on-dark;
  .sb-input,
  .sb-select,
  .sb-textarea {
    @apply text-on-dark placeholder-on-dark placeholder-opacity-75;
  }
  .sb-header-links-primary .sb-component-link:before,
  .sb-component-header .sb-component-social:before {
    @apply bg-on-dark;
  }
  .sb-header-links-primary .sb-component-link:hover,
  .sb-component-header .sb-component-social:hover {
    @apply text-dark;
  }
  .sb-header-overlay {
    @apply bg-dark;
  }
}
```

