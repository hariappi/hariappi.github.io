---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: books-list
    content:
      title: "Book Recommendations"
      books:
        - title: "The Pragmatic Programmer"
          author: "Andrew Hunt and David Thomas"
        - title: "Clean Code"
          author: "Robert C. Martin"
        - title: "Deep Work"
          author: "Cal Newport"
    design:
      css_class: light
      background:
        color: white

  - block: resume-biography-3
    content:
      text: |
        ## About Me

        Hi, I'm Hari, software engineer at AWS and currently building generative AI tools for enterprise customers.
      button:
        text: Download Resume
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
---
